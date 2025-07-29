---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-681c4c5501468f74165b2beff3cc6c2f
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
struct llvm::yaml::MappingTraits&lt;SIArgumentInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">Target/AMDGPU/SIMachineFunctionInfo.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9426840a4215cc87afb6e93ede9c9e">mapping</a> (IO &amp;YamlIO, SIArgumentInfo &amp;AI)</td>
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


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#a0f9426840a4215cc87afb6e93ede9c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; SIArgumentInfo &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; YamlIO, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo">SIArgumentInfo</a> &amp; AI)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a5d66404dbaa77294b81fb71ab6e9f2fa">llvm::yaml::SIArgumentInfo::DispatchID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a51a96ea8e2bce5933cefe7036c1bbfb8">llvm::yaml::SIArgumentInfo::DispatchPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a4af476884b5c20aff875bfd795311a82">llvm::yaml::SIArgumentInfo::FlatScratchInit</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a73c408dbdc8c66c16cf4470ed757dc0d">llvm::yaml::SIArgumentInfo::ImplicitArgPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a9e9e627cbc58f005c9700fad6dba44c8">llvm::yaml::SIArgumentInfo::ImplicitBufferPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ad8363f7760da238bb3cfdfac8c6c4b1e">llvm::yaml::SIArgumentInfo::KernargSegmentPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a98bcda097f96f762a3434c7af027a28f">llvm::yaml::SIArgumentInfo::LDSKernelId</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ae4215850b2039396d9d74fbff0338c73">llvm::yaml::SIArgumentInfo::PrivateSegmentBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ae416904af24a6e327a9753d56fe823df">llvm::yaml::SIArgumentInfo::PrivateSegmentSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a15a48fa21d3f8f742377af427cf0ee5b">llvm::yaml::SIArgumentInfo::PrivateSegmentWaveByteOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a803d6f6f03b46f9c067d597646038fe2">llvm::yaml::SIArgumentInfo::QueuePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a6970047063845d652bfefd629aa9fcd7">llvm::yaml::SIArgumentInfo::WorkGroupIDX</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a307994d74df71358c89e0cfde00bbfa6">llvm::yaml::SIArgumentInfo::WorkGroupIDY</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#af6104f43042e18823465bd004224f4c0">llvm::yaml::SIArgumentInfo::WorkGroupIDZ</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a88cb82a772743739bbd017585a6f1a73">llvm::yaml::SIArgumentInfo::WorkGroupInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ad4a62c3bd12c696f954f911be1203a20">llvm::yaml::SIArgumentInfo::WorkItemIDX</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a5ee4ff91ef2a74105cd4d7ae4a241f9b">llvm::yaml::SIArgumentInfo::WorkItemIDY</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ae10fad23e7a89515721e9dd05fd398df">llvm::yaml::SIArgumentInfo::WorkItemIDZ</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
