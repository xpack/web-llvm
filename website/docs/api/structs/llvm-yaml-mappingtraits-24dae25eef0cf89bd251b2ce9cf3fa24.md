---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24
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
struct llvm::yaml::MappingTraits&lt;DXContainerYAML::PSVInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">llvm/ObjectYAML/DXContainerYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6808d9de67d634c84c6549cc53e365bb">mapping</a> (IO &amp;IO, DXContainerYAML::PSVInfo &amp;PSV)</td>
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


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#a6808d9de67d634c84c6549cc53e365bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo">DXContainerYAML::PSVInfo</a> &amp; PSV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33">llvm::Triple::Domain</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a9602206972cc02cc749acfca45487271">llvm::yaml::IO::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a5d85020f593c54f3045af36f2175aa24">llvm::dxbc::getShaderStage</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51">llvm::Triple::Hull</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#af0a15b7e97f396db8d6fa3ed8774d3b3">llvm::DXContainerYAML::PSVInfo::Info</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#a0c3bdcfa633042b5864d44c45a99ee23">llvm::DXContainerYAML::PSVInfo::InputOutputMap</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#af4e1583db6a1b5de4b8f41b09ca7f48f">llvm::DXContainerYAML::PSVInfo::InputPatchMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#aef40b4410af614b5a4771ef2dfc5df47">llvm::DXContainerYAML::PSVInfo::mapInfoForVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#af221e5ae1e7ead206496874a6d161098">llvm::DXContainerYAML::PSVInfo::OutputVectorMasks</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#a8c0982570296d296606f49dfb0d229c2">llvm::DXContainerYAML::PSVInfo::PatchOrPrimMasks</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#a21fe1d431c473d674350c2f216f197b0">llvm::DXContainerYAML::PSVInfo::PatchOutputMap</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#a9ca0d2b25c023e503b15a3d56480b6a8">llvm::DXContainerYAML::PSVInfo::Resources</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#ae8d643e482694699c73d917ae25d6efc">llvm::DXContainerYAML::PSVInfo::ResourceStride</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a13c50e14628f82f4e0853bfef8ebddd1">llvm::yaml::IO::setContext</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v1/runtimeinfo/#a430eb3bec0239c50afc09172dfb510b3">llvm::dxbc::PSV::v1::RuntimeInfo::ShaderStage</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#ade850344574d5f24343d9b8f7cac2a59">llvm::DXContainerYAML::PSVInfo::SigInputElements</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#a7f2b1d45c6da697cd4f7d29eb273f6b8">llvm::DXContainerYAML::PSVInfo::SigOutputElements</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#a8ce8a80cc6b5b21dc6b8961af4f033fe">llvm::DXContainerYAML::PSVInfo::SigPatchOrPrimElements</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v1/runtimeinfo/#a3505714b1fc766b259480fc91ecb9c08">llvm::dxbc::PSV::v1::RuntimeInfo::UsesViewID</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#a324c4bf6a0fd537c2738464a8ed2e0d1">llvm::DXContainerYAML::PSVInfo::Version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
