---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606
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
struct llvm::yaml::MappingTraits&lt;Kernel::CodeProps::Metadata&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a19c05dcd370eff160c0179bbf9b52">mapping</a> (IO &amp;YIO, Kernel::CodeProps::Metadata &amp;MD)</td>
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


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/support/amdgpumetadata-cpp">AMDGPUMetadata.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#a78a19c05dcd370eff160c0179bbf9b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; YIO, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata">Kernel::CodeProps::Metadata</a> &amp; MD)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/support/amdgpumetadata-cpp">AMDGPUMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#af4c32381941f956c17be0eea54f10f5c">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::GroupSegmentFixedSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#a840a4bd37c3cd2b75794f34d3499cb9a">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::IsDynamicCallStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#a4022771507fc3890f2ceb194fad1228f">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::IsXNACKEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#a5b87932f051df8fec54de14eaf04bc24">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::KernargSegmentAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#ac6a8f40c05397d75ea5690acc1328c42">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::KernargSegmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#af422d46c20c7b2783037b238b9346249">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::MaxFlatWorkGroupSize</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#a2cdc6b690cc0517eb2cb99b4ea116ca3">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mGroupSegmentFixedSize</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#ab8b04326e0b718f0cacc8f207253f7ec">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mIsDynamicCallStack</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#a9cb5f32d879b67485e0e0450e3fad61e">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mIsXNACKEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#a478e0eac063ab6481094213820c2329f">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mKernargSegmentAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#a215d3f775ca94727ede0196cb228427b">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mKernargSegmentSize</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#afc4b4a16150a85c11702d364bafa83c6">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mMaxFlatWorkGroupSize</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#a091de9fc5c638c5c840facd7b3a9b603">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumSGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#a949e7dc9e47daa4e9f15f0c0b0a7433a">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumSpilledSGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#aad4ba18fc68fc19450bde321c25e0b1f">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumSpilledVGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#ab0becb88098b162aabd61424bc1439f4">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumVGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#adfe1aa2787c42d7b494b674189dc4fe9">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mPrivateSegmentFixedSize</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata/#aa47a6d270474829391f9d35134743618">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mWavefrontSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#ab3ae015c304377afcbc3ae1ed54578e8">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::NumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#a2491c3a59657fded84c2c99d58a66c9f">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::NumSpilledSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#a4a0b91e4765d448c2d404f1bd321dd69">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::NumSpilledVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#a0963ad90c895ee3e4e6d9e463c2d2e23">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::NumVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#afb6aab6fd944c598a7dca447ddfc2819">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::PrivateSegmentFixedSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/kernel/codeprops/key/#ac74d328a591ea975a64c340d6578ddc2">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Key::WavefrontSize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/amdgpumetadata-cpp">AMDGPUMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
