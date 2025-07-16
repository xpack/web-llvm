---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/hsamd/metadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Metadata` Struct Reference

<p>In-memory representation of HSA metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::HSAMD::Metadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">llvm/Support/AMDGPUMetadata.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3fe0facf790c53961edbbf76670b45">Metadata</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#abc3fe0facf790c53961edbbf76670b45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5558f6f09996146b125bf792b6c85eb">mVersion</a> = std::vector&lt;uint32_t&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HSA metadata version. Required. <a href="#af5558f6f09996146b125bf792b6c85eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afede90a92b08554b4e8b60bb0fd0cd64">mPrintf</a> = std::vector&lt;std::string&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Printf metadata. Optional. <a href="#afede90a92b08554b4e8b60bb0fd0cd64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata">Kernel::Metadata</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d08c828abe408e0056301aab6c6f024">mKernels</a> = std::vector&lt;<a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata">Kernel::Metadata</a>&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kernels metadata. Required. <a href="#a5d08c828abe408e0056301aab6c6f024">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>In-memory representation of HSA metadata.</p>

<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Metadata() {#abc3fe0facf790c53961edbbf76670b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::Metadata::Metadata ()</td>
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

<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### mKernels {#a5d08c828abe408e0056301aab6c6f024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Kernel::Metadata&gt; llvm::AMDGPU::HSAMD::Metadata::mKernels = std::vector&lt;<a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata">Kernel::Metadata</a>&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kernels metadata. Required.</p>

<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4c0c2ba5ea16381e76eaa75aa0e1667e/#a1823d39a4ef233f11786c2092adc819e">llvm::yaml::MappingTraits&lt; HSAMD::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mPrintf {#afede90a92b08554b4e8b60bb0fd0cd64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::AMDGPU::HSAMD::Metadata::mPrintf = std::vector&lt;std::string&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Printf metadata. Optional.</p>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4c0c2ba5ea16381e76eaa75aa0e1667e/#a1823d39a4ef233f11786c2092adc819e">llvm::yaml::MappingTraits&lt; HSAMD::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mVersion {#af5558f6f09996146b125bf792b6c85eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::AMDGPU::HSAMD::Metadata::mVersion = std::vector&lt;uint32_t&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HSA metadata version. Required.</p>

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4c0c2ba5ea16381e76eaa75aa0e1667e/#a1823d39a4ef233f11786c2092adc819e">llvm::yaml::MappingTraits&lt; HSAMD::Metadata &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
