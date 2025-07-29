---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/regbanklltmapping
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RegBankLLTMapping` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::RegBankLLTMapping { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">Target/AMDGPU/AMDGPURegBankLegalizeRules.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6faef83b6349e9d53a4c816cd468fef6">RegBankLLTMapping</a> (std::initializer_list&lt; RegBankLLTMappingApplyID &gt; DstOpMappingList, std::initializer_list&lt; RegBankLLTMappingApplyID &gt; SrcOpMappingList, LoweringMethodID LoweringMethod=DoNotLower)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dc">RegBankLLTMappingApplyID</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a61a55768d62591ce1e7568064d5215">DstOpMapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dc">RegBankLLTMappingApplyID</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82f302eac56f69e29146affd3c29a02d">SrcOpMapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0">LoweringMethodID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2517f9239d09d0d47fd75f929fd6b974">LoweringMethod</a></td>
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


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegBankLLTMapping() {#a6faef83b6349e9d53a4c816cd468fef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegBankLLTMapping::RegBankLLTMapping (std::initializer_list&lt; <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dc">RegBankLLTMappingApplyID</a> &gt; DstOpMappingList, std::initializer_list&lt; <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dc">RegBankLLTMappingApplyID</a> &gt; SrcOpMappingList, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0">LoweringMethodID</a> LoweringMethod=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0a843e6d9959a36713400d3649dff4ccb5">DoNotLower</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>


<p>References <a href="#a7a61a55768d62591ce1e7568064d5215">DstOpMapping</a>, <a href="#a2517f9239d09d0d47fd75f929fd6b974">LoweringMethod</a> and <a href="#a82f302eac56f69e29146affd3c29a02d">SrcOpMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DstOpMapping {#a7a61a55768d62591ce1e7568064d5215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RegBankLLTMappingApplyID, 2&gt; llvm::AMDGPU::RegBankLLTMapping::DstOpMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizehelper/#ae520a3c8f4f3de236034665deae793cf">llvm::AMDGPU::RegBankLegalizeHelper::findRuleAndApplyMapping</a> and <a href="#a6faef83b6349e9d53a4c816cd468fef6">RegBankLLTMapping</a>.</p>

</div>
</div>

### LoweringMethod {#a2517f9239d09d0d47fd75f929fd6b974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoweringMethodID llvm::AMDGPU::RegBankLLTMapping::LoweringMethod</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>


<p>Referenced by <a href="#a6faef83b6349e9d53a4c816cd468fef6">RegBankLLTMapping</a>.</p>

</div>
</div>

### SrcOpMapping {#a82f302eac56f69e29146affd3c29a02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RegBankLLTMappingApplyID, 4&gt; llvm::AMDGPU::RegBankLLTMapping::SrcOpMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizehelper/#ae520a3c8f4f3de236034665deae793cf">llvm::AMDGPU::RegBankLegalizeHelper::findRuleAndApplyMapping</a> and <a href="#a6faef83b6349e9d53a4c816cd468fef6">RegBankLLTMapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
