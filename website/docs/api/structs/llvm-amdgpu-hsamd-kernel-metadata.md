---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/hsamd/kernel/metadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Metadata` Struct Reference

<p>In-memory representation of kernel metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::HSAMD::Kernel::Metadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">llvm/Support/AMDGPUMetadata.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f9b2e23ec871ad269dedfb6bb0422c">Metadata</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a19f9b2e23ec871ad269dedfb6bb0422c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cfb3c235c56581fe5d252b207120c7">mName</a> = std::string()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel">Kernel</a> source name. Required. <a href="#a60cfb3c235c56581fe5d252b207120c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e03457ca1c6f479e5510d98ec18353">mSymbolName</a> = std::string()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel">Kernel</a> descriptor name. Required. <a href="#ad7e03457ca1c6f479e5510d98ec18353">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4fc56eae869a20d6f9c34693899fae">mLanguage</a> = std::string()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Language. Optional. <a href="#a5b4fc56eae869a20d6f9c34693899fae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946cecdc0b653752eed94d7f34cab3e8">mLanguageVersion</a> = std::vector&lt;uint32_t&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Language version. Optional. <a href="#a946cecdc0b653752eed94d7f34cab3e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/attrs/metadata">Attrs::Metadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1edfceb561236e243534224055c02ff0">mAttrs</a> = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/attrs/metadata">Attrs::Metadata</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attributes metadata. Optional. <a href="#a1edfceb561236e243534224055c02ff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/arg/metadata">Arg::Metadata</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662694a0718ccdf5c6695c17c65bc9ea">mArgs</a> = std::vector&lt;<a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/arg/metadata">Arg::Metadata</a>&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arguments metadata. Optional. <a href="#a662694a0718ccdf5c6695c17c65bc9ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata">CodeProps::Metadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f8f65d12ea5413116a489c1fc9179d">mCodeProps</a> = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata">CodeProps::Metadata</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code properties metadata. Optional. <a href="#a78f8f65d12ea5413116a489c1fc9179d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/debugprops/metadata">DebugProps::Metadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b90f591fc810f4845e57b4c427dcec7">mDebugProps</a> = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/debugprops/metadata">DebugProps::Metadata</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug properties metadata. Optional. <a href="#a1b90f591fc810f4845e57b4c427dcec7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>In-memory representation of kernel metadata.</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Metadata() {#a19f9b2e23ec871ad269dedfb6bb0422c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::Kernel::Metadata::Metadata ()</td>
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

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### mArgs {#a662694a0718ccdf5c6695c17c65bc9ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Arg::Metadata&gt; llvm::AMDGPU::HSAMD::Kernel::Metadata::mArgs = std::vector&lt;<a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/arg/metadata">Arg::Metadata</a>&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Arguments metadata. Optional.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mAttrs {#a1edfceb561236e243534224055c02ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attrs::Metadata llvm::AMDGPU::HSAMD::Kernel::Metadata::mAttrs = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/attrs/metadata">Attrs::Metadata</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attributes metadata. Optional.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mCodeProps {#a78f8f65d12ea5413116a489c1fc9179d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeProps::Metadata llvm::AMDGPU::HSAMD::Kernel::Metadata::mCodeProps = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata">CodeProps::Metadata</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code properties metadata. Optional.</p>

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mDebugProps {#a1b90f591fc810f4845e57b4c427dcec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugProps::Metadata llvm::AMDGPU::HSAMD::Kernel::Metadata::mDebugProps = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/debugprops/metadata">DebugProps::Metadata</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug properties metadata. Optional.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mLanguage {#a5b4fc56eae869a20d6f9c34693899fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::Kernel::Metadata::mLanguage = std::string()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Language. Optional.</p>

<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mLanguageVersion {#a946cecdc0b653752eed94d7f34cab3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::AMDGPU::HSAMD::Kernel::Metadata::mLanguageVersion = std::vector&lt;uint32_t&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Language version. Optional.</p>

<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mName {#a60cfb3c235c56581fe5d252b207120c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::Kernel::Metadata::mName = std::string()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel">Kernel</a> source name. Required.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mSymbolName {#ad7e03457ca1c6f479e5510d98ec18353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::Kernel::Metadata::mSymbolName = std::string()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel">Kernel</a> descriptor name. Required.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

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
