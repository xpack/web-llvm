---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/jitlink/aarch32/armconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ArmConfig` Struct

<p>JITLink sub-arch configuration for Arm CPU models. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::jitlink::aarch32::ArmConfig { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">llvm/ExecutionEngine/JITLink/aarch32.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e039f3a3b52cf453593a0b7be7e9615">J1J2BranchEncoding</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a66abed31cc3dfac01c8ed560eb6db1c5">StubsFlavor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f7625d1cdc07c59d18a80819e999b3">Stubs</a> = <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a66abed31cc3dfac01c8ed560eb6db1c5aec0fc0100c4fc1ce4eea230c3dc10360">StubsFlavor::Undefined</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c93aeabb0423a1bee02fe9a81677d8">Target1Rel</a> = false</td>
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

## Description {#details}

<p>JITLink sub-arch configuration for Arm CPU models.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### J1J2BranchEncoding {#a5e039f3a3b52cf453593a0b7be7e9615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch32::ArmConfig::J1J2BranchEncoding = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a183363f7e8482b2c1e193956dea835ee">llvm::jitlink::aarch32::applyFixupThumb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a3a95b507182908470f226c73349e0f15">llvm::jitlink::aarch32::getArmConfigForCPUArch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#aa6cf2c07bc856d1cb198de49c5523317">llvm::jitlink::aarch32::readAddendThumb</a>.</p>

</div>
</div>

### Stubs {#a88f7625d1cdc07c59d18a80819e999b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StubsFlavor llvm::jitlink::aarch32::ArmConfig::Stubs = <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a66abed31cc3dfac01c8ed560eb6db1c5aec0fc0100c4fc1ce4eea230c3dc10360">StubsFlavor::Undefined</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a3a95b507182908470f226c73349e0f15">llvm::jitlink::aarch32::getArmConfigForCPUArch</a>.</p>

</div>
</div>

### Target1Rel {#a37c93aeabb0423a1bee02fe9a81677d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch32::ArmConfig::Target1Rel = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af93c9f4d8fbbc1d26112d46de850c11a">llvm::jitlink::getJITLinkEdgeKind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
