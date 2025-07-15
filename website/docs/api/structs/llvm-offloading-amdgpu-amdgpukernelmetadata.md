---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/offloading/amdgpu/amdgpukernelmetadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AMDGPUKernelMetaData` Struct Reference

<p>Struct for holding metadata related to <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> kernels, for more information about the metadata and its meaning see: <a href="https://llvm.org/docs/AMDGPUUsage.html#code-object-v3">https://llvm.org/docs/AMDGPUUsage.html#code-object-v3</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::offloading::amdgpu::AMDGPUKernelMetaData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">llvm/Frontend/Offloading/Utility.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4dddba5a77aa0288b30ba73da07b0d8">GroupSegmentList</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of group segment memory required by a work-group in bytes. <a href="#ab4dddba5a77aa0288b30ba73da07b0d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b954a932db85e428c5090ee969d02b">PrivateSegmentSize</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of fixed private address space memory required for a work-item in bytes. <a href="#a92b954a932db85e428c5090ee969d02b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22fedc9a61b9a86a32c88ad9526a1e91">SGPRCount</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of scalar registers required by a wavefront. <a href="#a22fedc9a61b9a86a32c88ad9526a1e91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87fa4b4f2eb3d72aad1081a640e84259">VGPRCount</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of vector registers required by each work-item. <a href="#a87fa4b4f2eb3d72aad1081a640e84259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ea896dc71f8a145600d0cee4c92465">SGPRSpillCount</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of stores from a scalar register to a register allocator created spill location. <a href="#a03ea896dc71f8a145600d0cee4c92465">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7daeeb1754518cd3f537cae01e7f7ab7">VGPRSpillCount</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of stores from a vector register to a register allocator created spill location. <a href="#a7daeeb1754518cd3f537cae01e7f7ab7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad507fb56a5d5ddc973d185b83f9ece69">AGPRCount</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of accumulator registers required by each work-item. <a href="#ad507fb56a5d5ddc973d185b83f9ece69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45270b1f404c0b6ec7abca5b7e2d031">RequestedWorkgroupSize</a>[3] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Corresponds to the OpenCL reqd_work_group_size attribute. <a href="#af45270b1f404c0b6ec7abca5b7e2d031">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a82e0213fe9f6b489c17c35ef928de">WorkgroupSizeHint</a>[3] = {<a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>, <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>, <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Corresponds to the OpenCL work_group_size_hint attribute. <a href="#ac2a82e0213fe9f6b489c17c35ef928de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d65149cfec2b81c85bf969ff3fd29b">WavefrontSize</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wavefront size. <a href="#a11d65149cfec2b81c85bf969ff3fd29b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb411d5d269b9d91f9426828ff7050d">MaxFlatWorkgroupSize</a> = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum flat work-group size supported by the kernel in work-items. <a href="#abcb411d5d269b9d91f9426828ff7050d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> indicating that a value is invalid. <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Struct for holding metadata related to <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> kernels, for more information about the metadata and its meaning see: <a href="https://llvm.org/docs/AMDGPUUsage.html#code-object-v3">https://llvm.org/docs/AMDGPUUsage.html#code-object-v3</a>.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AGPRCount {#ad507fb56a5d5ddc973d185b83f9ece69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::AGPRCount = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of accumulator registers required by each work-item.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### GroupSegmentList {#ab4dddba5a77aa0288b30ba73da07b0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::GroupSegmentList = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount of group segment memory required by a work-group in bytes.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### MaxFlatWorkgroupSize {#abcb411d5d269b9d91f9426828ff7050d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::MaxFlatWorkgroupSize = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum flat work-group size supported by the kernel in work-items.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### PrivateSegmentSize {#a92b954a932db85e428c5090ee969d02b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::PrivateSegmentSize = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount of fixed private address space memory required for a work-item in bytes.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### RequestedWorkgroupSize {#af45270b1f404c0b6ec7abca5b7e2d031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::RequestedWorkgroupSize[3]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Corresponds to the OpenCL reqd_work_group_size attribute.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {<a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>, <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>,
                                        <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>}
</div>
</dd>
</dl>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### SGPRCount {#a22fedc9a61b9a86a32c88ad9526a1e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::SGPRCount = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of scalar registers required by a wavefront.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### SGPRSpillCount {#a03ea896dc71f8a145600d0cee4c92465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::SGPRSpillCount = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of stores from a scalar register to a register allocator created spill location.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### VGPRCount {#a87fa4b4f2eb3d72aad1081a640e84259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::VGPRCount = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of vector registers required by each work-item.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### VGPRSpillCount {#a7daeeb1754518cd3f537cae01e7f7ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::VGPRSpillCount = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of stores from a vector register to a register allocator created spill location.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### WavefrontSize {#a11d65149cfec2b81c85bf969ff3fd29b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::WavefrontSize = <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wavefront size.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

### WorkgroupSizeHint {#ac2a82e0213fe9f6b489c17c35ef928de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::WorkgroupSizeHint[3] = {<a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>, <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>, <a href="#a7d08b108e30269ecbdfc7efa0fa40cf1">KInvalidValue</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Corresponds to the OpenCL work_group_size_hint attribute.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### KInvalidValue {#a7d08b108e30269ecbdfc7efa0fa40cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::offloading::amdgpu::AMDGPUKernelMetaData::KInvalidValue</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> indicating that a value is invalid.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      std::numeric_limits&lt;uint32_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()
</div>
</dd>
</dl>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
