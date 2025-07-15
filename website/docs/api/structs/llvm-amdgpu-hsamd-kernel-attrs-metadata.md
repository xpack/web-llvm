---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/hsamd/kernel/attrs/metadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Metadata` Struct Reference

<p>In-memory representation of kernel attributes metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">llvm/Support/AMDGPUMetadata.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b799a0446cf443a85d865cb73f9363">Metadata</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a61b799a0446cf443a85d865cb73f9363">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e97379f6aa5fd2bbb4af6045aa4ef5">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4eed191ab52123ae758a48ee40eba7f">notEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829c5d2950eb934883f08b1fba58700c">mReqdWorkGroupSize</a> = std::vector&lt;uint32_t&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'reqd_work_group_size' attribute. Optional. <a href="#a829c5d2950eb934883f08b1fba58700c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b21313323966f1e9b5517121dd9085">mWorkGroupSizeHint</a> = std::vector&lt;uint32_t&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'work_group_size_hint' attribute. Optional. <a href="#aa6b21313323966f1e9b5517121dd9085">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819fa12e3771532b5b218eb07a343115">mVecTypeHint</a> = std::string()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'vec_type_hint' attribute. Optional. <a href="#a819fa12e3771532b5b218eb07a343115">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a018885b99d8f12675d70b6e7a301db">mRuntimeHandle</a> = std::string()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>External symbol created by runtime to store the kernel address for enqueued blocks. <a href="#a4a018885b99d8f12675d70b6e7a301db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>In-memory representation of kernel attributes metadata.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Metadata() {#a61b799a0446cf443a85d865cb73f9363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::Metadata ()</td>
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

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#ae5e97379f6aa5fd2bbb4af6045aa4ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::empty ()</td>
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
<dd><p>True if kernel attributes metadata is empty, false otherwise.</p></dd>
</dl>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Reference <a href="#af4eed191ab52123ae758a48ee40eba7f">notEmpty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### notEmpty() {#af4eed191ab52123ae758a48ee40eba7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::notEmpty ()</td>
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
<dd><p>True if kernel attributes metadata is not empty, false otherwise.</p></dd>
</dl>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>References <a href="#a829c5d2950eb934883f08b1fba58700c">mReqdWorkGroupSize</a>, <a href="#a4a018885b99d8f12675d70b6e7a301db">mRuntimeHandle</a>, <a href="#a819fa12e3771532b5b218eb07a343115">mVecTypeHint</a> and <a href="#aa6b21313323966f1e9b5517121dd9085">mWorkGroupSizeHint</a>.</p>


<p>Referenced by <a href="#ae5e97379f6aa5fd2bbb4af6045aa4ef5">empty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### mReqdWorkGroupSize {#a829c5d2950eb934883f08b1fba58700c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::mReqdWorkGroupSize = std::vector&lt;uint32_t&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>'reqd_work_group_size' attribute. Optional.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3f18e02f49b29247efabd35c84c79b5f/#a28c9fd78eecc77a2b93ffb47781c1db9">llvm::yaml::MappingTraits&lt; Kernel::Attrs::Metadata &gt;::mapping</a> and <a href="#af4eed191ab52123ae758a48ee40eba7f">notEmpty</a>.</p>

</div>
</div>

### mRuntimeHandle {#a4a018885b99d8f12675d70b6e7a301db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::mRuntimeHandle = std::string()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>External symbol created by runtime to store the kernel address for enqueued blocks.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3f18e02f49b29247efabd35c84c79b5f/#a28c9fd78eecc77a2b93ffb47781c1db9">llvm::yaml::MappingTraits&lt; Kernel::Attrs::Metadata &gt;::mapping</a> and <a href="#af4eed191ab52123ae758a48ee40eba7f">notEmpty</a>.</p>

</div>
</div>

### mVecTypeHint {#a819fa12e3771532b5b218eb07a343115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::mVecTypeHint = std::string()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>'vec_type_hint' attribute. Optional.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3f18e02f49b29247efabd35c84c79b5f/#a28c9fd78eecc77a2b93ffb47781c1db9">llvm::yaml::MappingTraits&lt; Kernel::Attrs::Metadata &gt;::mapping</a> and <a href="#af4eed191ab52123ae758a48ee40eba7f">notEmpty</a>.</p>

</div>
</div>

### mWorkGroupSizeHint {#aa6b21313323966f1e9b5517121dd9085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::mWorkGroupSizeHint = std::vector&lt;uint32_t&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>'work_group_size_hint' attribute. Optional.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3f18e02f49b29247efabd35c84c79b5f/#a28c9fd78eecc77a2b93ffb47781c1db9">llvm::yaml::MappingTraits&lt; Kernel::Attrs::Metadata &gt;::mapping</a> and <a href="#af4eed191ab52123ae758a48ee40eba7f">notEmpty</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
