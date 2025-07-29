---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/hsamd/kernel/arg/metadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Metadata` Struct

<p>In-memory representation of kernel argument metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">llvm/Support/AMDGPUMetadata.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689b269ca7322a4e7af32665ec7ad602">Metadata</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a689b269ca7322a4e7af32665ec7ad602">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438882e1bfe7deba5fb438e6815b4391">mName</a> = std::string()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name. Optional. <a href="#a438882e1bfe7deba5fb438e6815b4391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad0699d808efd9289976b8c4e2dc5c6">mTypeName</a> = std::string()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> name. Optional. <a href="#afad0699d808efd9289976b8c4e2dc5c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8c36105e6a4bd2443a40cba3ca8cca">mSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size in bytes. Required. <a href="#adc8c36105e6a4bd2443a40cba3ca8cca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66769fc55a7b9943b7203ea7ca886e55">mOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset in bytes. Required for code object v3, unused for code object v2. <a href="#a66769fc55a7b9943b7203ea7ca886e55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a34b49dcaa8efd1546efd9d3e34875">mAlign</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Alignment in bytes. Required. <a href="#a13a34b49dcaa8efd1546efd9d3e34875">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a85803b71729d5d098ca2099f23cbf72e">ValueKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8697021c9a21b05b891a5f77b2d41d47">mValueKind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a85803b71729d5d098ca2099f23cbf72ea88183b946cc5f0e8c96b2e66e1c74a7e">ValueKind::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> kind. Required. <a href="#a8697021c9a21b05b891a5f77b2d41d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f55b63f63316dca70be627499ad3bd5">mPointeeAlign</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointee alignment in bytes. Optional. <a href="#a7f55b63f63316dca70be627499ad3bd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a7f822c68e1b547ae15cc6ef4bc59176d">AddressSpaceQualifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4519110cc2ce4e5cb61bfca4f32610c">mAddrSpaceQual</a> = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a7f822c68e1b547ae15cc6ef4bc59176da88183b946cc5f0e8c96b2e66e1c74a7e">AddressSpaceQualifier::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Address space qualifier. Optional. <a href="#ac4519110cc2ce4e5cb61bfca4f32610c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#af0a4ac1832ff2fc3a881f851028632c5">AccessQualifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88dd201ff7572de461b419829985cf1">mAccQual</a> = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#af0a4ac1832ff2fc3a881f851028632c5a88183b946cc5f0e8c96b2e66e1c74a7e">AccessQualifier::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access qualifier. Optional. <a href="#ae88dd201ff7572de461b419829985cf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#af0a4ac1832ff2fc3a881f851028632c5">AccessQualifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03232ba23ebdf59085acb5dee74963f3">mActualAccQual</a> = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#af0a4ac1832ff2fc3a881f851028632c5a88183b946cc5f0e8c96b2e66e1c74a7e">AccessQualifier::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Actual access qualifier. Optional. <a href="#a03232ba23ebdf59085acb5dee74963f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56c55dc7e7eadba8b4f7529cce7429f">mIsConst</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if 'const' qualifier is specified. Optional. <a href="#aa56c55dc7e7eadba8b4f7529cce7429f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa736763916bb2e789fa85198ff363c61">mIsRestrict</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if 'restrict' qualifier is specified. Optional. <a href="#aa736763916bb2e789fa85198ff363c61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8459d056e3513121d80cc9c54b545817">mIsVolatile</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if 'volatile' qualifier is specified. Optional. <a href="#a8459d056e3513121d80cc9c54b545817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ac99bdfb22b80a532b82a9637f6903">mIsPipe</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if 'pipe' qualifier is specified. Optional. <a href="#aa8ac99bdfb22b80a532b82a9637f6903">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>In-memory representation of kernel argument metadata.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Metadata() {#a689b269ca7322a4e7af32665ec7ad602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::Metadata ()</td>
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

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### mAccQual {#ae88dd201ff7572de461b419829985cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccessQualifier llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mAccQual = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#af0a4ac1832ff2fc3a881f851028632c5a88183b946cc5f0e8c96b2e66e1c74a7e">AccessQualifier::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access qualifier. Optional.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mActualAccQual {#a03232ba23ebdf59085acb5dee74963f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccessQualifier llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mActualAccQual = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#af0a4ac1832ff2fc3a881f851028632c5a88183b946cc5f0e8c96b2e66e1c74a7e">AccessQualifier::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Actual access qualifier. Optional.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mAddrSpaceQual {#ac4519110cc2ce4e5cb61bfca4f32610c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressSpaceQualifier llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mAddrSpaceQual = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a7f822c68e1b547ae15cc6ef4bc59176da88183b946cc5f0e8c96b2e66e1c74a7e">AddressSpaceQualifier::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Address space qualifier. Optional.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mAlign {#a13a34b49dcaa8efd1546efd9d3e34875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mAlign = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Alignment in bytes. Required.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mIsConst {#aa56c55dc7e7eadba8b4f7529cce7429f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mIsConst = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if 'const' qualifier is specified. Optional.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mIsPipe {#aa8ac99bdfb22b80a532b82a9637f6903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mIsPipe = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if 'pipe' qualifier is specified. Optional.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mIsRestrict {#aa736763916bb2e789fa85198ff363c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mIsRestrict = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if 'restrict' qualifier is specified. Optional.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mIsVolatile {#a8459d056e3513121d80cc9c54b545817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mIsVolatile = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if 'volatile' qualifier is specified. Optional.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mName {#a438882e1bfe7deba5fb438e6815b4391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mName = std::string()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Name. Optional.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mOffset {#a66769fc55a7b9943b7203ea7ca886e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset in bytes. Required for code object v3, unused for code object v2.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>

</div>
</div>

### mPointeeAlign {#a7f55b63f63316dca70be627499ad3bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mPointeeAlign = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointee alignment in bytes. Optional.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mSize {#adc8c36105e6a4bd2443a40cba3ca8cca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size in bytes. Required.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mTypeName {#afad0699d808efd9289976b8c4e2dc5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mTypeName = std::string()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> name. Optional.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mValueKind {#a8697021c9a21b05b891a5f77b2d41d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueKind llvm::AMDGPU::HSAMD::Kernel::Arg::Metadata::mValueKind = <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a85803b71729d5d098ca2099f23cbf72ea88183b946cc5f0e8c96b2e66e1c74a7e">ValueKind::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> kind. Required.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>.</p>

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
