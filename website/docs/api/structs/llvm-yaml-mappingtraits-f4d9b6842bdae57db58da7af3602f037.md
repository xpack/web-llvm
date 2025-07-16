---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MappingTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;Kernel::Metadata&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587d9bdb751367010682b1147723230c">mapping</a> (IO &amp;YIO, Kernel::Metadata &amp;MD)</td>
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


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/support/amdgpumetadata-cpp">AMDGPUMetadata.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#a587d9bdb751367010682b1147723230c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; YIO, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata">Kernel::Metadata</a> &amp; MD)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/support/amdgpumetadata-cpp">AMDGPUMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#a1958a762261549463a280bac3274d6d5">llvm::AMDGPU::HSAMD::Kernel::Key::Args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#a47142a8413e4b403d01f9365ac8d7ff7">llvm::AMDGPU::HSAMD::Kernel::Key::Attrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#a248c79945f1cc172df4309d4557f94d9">llvm::AMDGPU::HSAMD::Kernel::Key::CodeProps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#a8079cf6cbeaf89bebb02fbcfe5a85b4c">llvm::AMDGPU::HSAMD::Kernel::Key::DebugProps</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/attrs/metadata/#ae5e97379f6aa5fd2bbb4af6045aa4ef5">llvm::AMDGPU::HSAMD::Kernel::Attrs::Metadata::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#aa191a3cfcaf6ed8a15ae52c3c5910bd3">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/debugprops/metadata/#acf774a76c2ed49c893305add13aed100">llvm::AMDGPU::HSAMD::Kernel::DebugProps::Metadata::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#a2f7d62430cb7da20e8c63e2a4d6fa15a">llvm::AMDGPU::HSAMD::Kernel::Key::Language</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#a5730c59ab40e5a8808ca0736eb7330f7">llvm::AMDGPU::HSAMD::Kernel::Key::LanguageVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#a662694a0718ccdf5c6695c17c65bc9ea">llvm::AMDGPU::HSAMD::Kernel::Metadata::mArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#a1edfceb561236e243534224055c02ff0">llvm::AMDGPU::HSAMD::Kernel::Metadata::mAttrs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#a78f8f65d12ea5413116a489c1fc9179d">llvm::AMDGPU::HSAMD::Kernel::Metadata::mCodeProps</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#a1b90f591fc810f4845e57b4c427dcec7">llvm::AMDGPU::HSAMD::Kernel::Metadata::mDebugProps</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#a5b4fc56eae869a20d6f9c34693899fae">llvm::AMDGPU::HSAMD::Kernel::Metadata::mLanguage</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#a946cecdc0b653752eed94d7f34cab3e8">llvm::AMDGPU::HSAMD::Kernel::Metadata::mLanguageVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#a60cfb3c235c56581fe5d252b207120c7">llvm::AMDGPU::HSAMD::Kernel::Metadata::mName</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/metadata/#ad7e03457ca1c6f479e5510d98ec18353">llvm::AMDGPU::HSAMD::Kernel::Metadata::mSymbolName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#a26f38fac577f2ac006cdf972fdc6bee4">llvm::AMDGPU::HSAMD::Kernel::Key::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a3f9abe4cc7cc808cb6025ed882bcbb7d">llvm::yaml::IO::outputting</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/key/#af0b71165db16633df4a356825edea094">llvm::AMDGPU::HSAMD::Kernel::Key::SymbolName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/amdgpumetadata-cpp">AMDGPUMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
