---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MappingTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;SIMachineFunctionInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">Target/AMDGPU/SIMachineFunctionInfo.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af012311acd92ea9c93c84f48d4b002dc">mapping</a> (IO &amp;YamlIO, SIMachineFunctionInfo &amp;MFI)</td>
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


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#af012311acd92ea9c93c84f48d4b002dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; YamlIO, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo">SIMachineFunctionInfo</a> &amp; MFI)</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#ae201cd41bc4b333606be1bbb656c1333">llvm::yaml::SIMachineFunctionInfo::ArgInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#af5a050a54628c01ef397d4485baef00b">llvm::yaml::SIMachineFunctionInfo::BytesInStackArgArea</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe41cc313a9e7bcb8b71d428f64fb3a8">llvm::DefaultMemoryClusterDWordsLimit</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a2ce6322058842a2f550cdece7f45a460">llvm::yaml::SIMachineFunctionInfo::DynLDSAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a8888b91100f58ca964bebf56c5f7250a">llvm::yaml::SIMachineFunctionInfo::ExplicitKernArgSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a820d8ccceda9b8f7790330579694ef91">llvm::yaml::SIMachineFunctionInfo::FrameOffsetReg</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a58c4552ea5abaeade68a9eed8f2a2bec">llvm::yaml::SIMachineFunctionInfo::GDSSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#adfffa2c248385b2fec7ee03ba4d052ae">llvm::yaml::SIMachineFunctionInfo::HasInitWholeWave</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a18dad3d1a8b82fd293a5af59a4f3138b">llvm::yaml::SIMachineFunctionInfo::HasSpilledSGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a0fb0fa814e38acce0fb19fd57fcd7d3c">llvm::yaml::SIMachineFunctionInfo::HasSpilledVGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a474d30e4754bc67ab1d1e8965549175f">llvm::yaml::SIMachineFunctionInfo::HighBitsOf32BitAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#ade91b18e31b6fd06c7e00178ae87b860">llvm::yaml::SIMachineFunctionInfo::IsChainFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#abcf97495a98d0664ad5d57a3c99d00e0">llvm::yaml::SIMachineFunctionInfo::IsEntryFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a8a016a817ed7bffc76e08a31542f4a02">llvm::yaml::SIMachineFunctionInfo::LDSSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a8567716d726b82e9ea28bdf407454514">llvm::yaml::SIMachineFunctionInfo::LongBranchReservedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a74959e0e9a215d043a54ab005c63d1a0">llvm::yaml::SIMachineFunctionInfo::MaxKernArgAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a06ec65506d35ef9a0bff8486d67e5963">llvm::yaml::SIMachineFunctionInfo::MaxMemoryClusterDWords</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a5a54cebc219a0ce5b9b3b01976f11c91">llvm::yaml::SIMachineFunctionInfo::MemoryBound</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#ade7132a796d315b462bdc59fb10d3a99">llvm::yaml::SIMachineFunctionInfo::Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#ab940a796f6bef2ca14da9145fd48cbd2">llvm::yaml::SIMachineFunctionInfo::NoSignedZerosFPMath</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a6c09f1ebbd201f3dabed263f9247b72b">llvm::yaml::SIMachineFunctionInfo::Occupancy</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a8ed4fbd12c37494064fe27c4882ff4db">llvm::yaml::SIMachineFunctionInfo::PSInputAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a7035afa4e12bf0a99755e4da56adbbf3">llvm::yaml::SIMachineFunctionInfo::PSInputEnable</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a219de208b06027b5835065d3daddc914">llvm::yaml::SIMachineFunctionInfo::ReturnsVoid</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#af3b0a37d098278019f07649dc270bb02">llvm::yaml::SIMachineFunctionInfo::ScavengeFI</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#afae943f235ffb0ac6224181bc5d3b213">llvm::yaml::SIMachineFunctionInfo::ScratchRSrcReg</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a11b88b42beff3cee85a89eb7e5d3dfd3">llvm::yaml::SIMachineFunctionInfo::SGPRForEXECCopy</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#aee024587ab03348def87a3e3923fd5c9">llvm::yaml::SIMachineFunctionInfo::SpillPhysVGPRS</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#afba5cd76321da56b47ddaf51c4727576">llvm::yaml::SIMachineFunctionInfo::StackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#adc4e12fe2a000305ad25837db0d188f5">llvm::yaml::SIMachineFunctionInfo::VGPRForAGPRCopy</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a8ac7d3705f692ab4c299ae91d0573836">llvm::yaml::SIMachineFunctionInfo::WaveLimiter</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a2e7d99cf6836e2e91f35895642a4772b">llvm::yaml::SIMachineFunctionInfo::WWMReservedRegs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
