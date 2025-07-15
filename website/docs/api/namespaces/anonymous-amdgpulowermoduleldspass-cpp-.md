---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-amdgpulowermoduleldspass-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{AMDGPULowerModuleLDSPass.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{AMDGPULowerModuleLDSPass.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds">AMDGPULowerModuleLDS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermoduleldslegacy">AMDGPULowerModuleLDSLegacy</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LoweringKind { <a href="#a6e490c4b0bbf52b0bad2e040be385e02">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0a1078e388d9973135cc3cc8a872d5c1">sortByName</a> (std::vector&lt; T &gt; &amp;&amp;V) -&gt; std::vector&lt; T &gt;</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7eb9b2a69c1f49d21bd786f94771db3">SuperAlignLDSGlobals</a>("amdgpu-super-align-lds-globals", cl::desc("Increase alignment of LDS if it is not on align boundary"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#a6e490c4b0bbf52b0bad2e040be385e02">LoweringKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b1678dfbb7c0c7e5433e36618af00b">LoweringKindLoc</a>("amdgpu-lower-module-lds-strategy", cl::desc("Specify lowering strategy for function LDS access:"), cl::Hidden, cl::init(LoweringKind::hybrid), cl::values(clEnumValN(LoweringKind::table, "table", "Lower via table lookup"), clEnumValN(LoweringKind::module, "module", "Lower via module struct"), clEnumValN(LoweringKind::kernel, "kernel", "Lower variables reachable from one kernel, otherwise abort"), clEnumValN(LoweringKind::hybrid, "hybrid", "Lower via mixture of above strategies")))</td>
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


<div class="doxySectionDef">

## Enumerations

### LoweringKind {#a6e490c4b0bbf52b0bad2e040be385e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{AMDGPULowerModuleLDSPass.cpp}::LoweringKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">module<a id="a6e490c4b0bbf52b0bad2e040be385e02a22884db148f0ffb0d830ba431102b0b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">table<a id="a6e490c4b0bbf52b0bad2e040be385e02aaab9e1de16f38176f86d7a92ba337a8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kernel<a id="a6e490c4b0bbf52b0bad2e040be385e02a50484c19f1afdaf3841a0d821ed393d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">hybrid<a id="a6e490c4b0bbf52b0bad2e040be385e02af7befc67e4b1ddf3a03d496537760671"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp">AMDGPULowerModuleLDSPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### sortByName() {#a0a1078e388d9973135cc3cc8a872d5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; T &gt; anonymous{AMDGPULowerModuleLDSPass.cpp}::sortByName (std::vector&lt; T &gt; &amp;&amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp">AMDGPULowerModuleLDSPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9c260f0a51a4c6f936233261cda38455">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::assignLDSKernelIDToEachKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a5d35bdf8fd7ab1b1854b23c27795d6e4">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerSpecialLDSVariables</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad30c8bb172d913f5fb4a3d850bb7a4d2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### LoweringKindLoc {#a03b1678dfbb7c0c7e5433e36618af00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; LoweringKind &gt; anonymous{AMDGPULowerModuleLDSPass.cpp}::LoweringKindLoc("amdgpu-lower-module-lds-strategy", cl::desc("Specify lowering strategy for function LDS access:"), cl::Hidden, cl::init(LoweringKind::hybrid), cl::values( clEnumValN(LoweringKind::table, "table", "Lower via table lookup"), clEnumValN(LoweringKind::module, "module", "Lower via module struct"), clEnumValN( LoweringKind::kernel, "kernel", "Lower variables reachable from one kernel, otherwise abort"), clEnumValN(LoweringKind::hybrid, "hybrid", "Lower via mixture of above strategies")))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp">AMDGPULowerModuleLDSPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#af7de33f6a986de428d183da62c941f13">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::partitionVariablesIntoIndirectStrategies</a>.</p>

</div>
</div>

### SuperAlignLDSGlobals {#af7eb9b2a69c1f49d21bd786f94771db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{AMDGPULowerModuleLDSPass.cpp}::SuperAlignLDSGlobals("amdgpu-super-align-lds-globals", cl::desc("Increase alignment of LDS if it is not on align boundary"), cl::init(true), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp">AMDGPULowerModuleLDSPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp">AMDGPULowerModuleLDSPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
