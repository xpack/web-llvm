---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/ldsusesinfoty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LDSUsesInfoTy` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::LDSUsesInfoTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumemoryutils-h">Target/AMDGPU/AMDGPUMemoryUtils.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a91adb9ce33ec5b4ca2f7cd5920aee3be">FunctionVariableMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742870ecab7687d09d889034c6695ee8">direct_access</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a91adb9ce33ec5b4ca2f7cd5920aee3be">FunctionVariableMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbbf7703905ba9107c6b20bf87e4095a">indirect_access</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad071163a75cc2d817e98c1c65545e3f3">HasSpecialGVs</a> = false</td>
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


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumemoryutils-h">AMDGPUMemoryUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### direct\_access {#a742870ecab7687d09d889034c6695ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionVariableMap llvm::AMDGPU::LDSUsesInfoTy::direct_access</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumemoryutils-h">AMDGPUMemoryUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad6c0f52a75bef49176db797774e8dc2c">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildRepresentativeDynamicLDSInstance</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#aced21833345ccf6ab7f595b6952ed165">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerKernelScopeStructVariables</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a5d35bdf8fd7ab1b1854b23c27795d6e4">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerSpecialLDSVariables</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a0633351128ad7c6f0e5bf0522edeef79">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::run</a>.</p>

</div>
</div>

### HasSpecialGVs {#ad071163a75cc2d817e98c1c65545e3f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::LDSUsesInfoTy::HasSpecialGVs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumemoryutils-h">AMDGPUMemoryUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad30c8bb172d913f5fb4a3d850bb7a4d2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::runOnModule</a>.</p>

</div>
</div>

### indirect\_access {#abbbf7703905ba9107c6b20bf87e4095a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionVariableMap llvm::AMDGPU::LDSUsesInfoTy::indirect_access</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumemoryutils-h">AMDGPUMemoryUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad6c0f52a75bef49176db797774e8dc2c">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildRepresentativeDynamicLDSInstance</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#aee78a99678b1d9cc244ec52ad2f2ba16">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::kernelsThatIndirectlyAccessAnyOfPassedVariables</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#aced21833345ccf6ab7f595b6952ed165">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerKernelScopeStructVariables</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a5d35bdf8fd7ab1b1854b23c27795d6e4">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerSpecialLDSVariables</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a0633351128ad7c6f0e5bf0522edeef79">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad30c8bb172d913f5fb4a3d850bb7a4d2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::runOnModule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumemoryutils-h">AMDGPUMemoryUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
