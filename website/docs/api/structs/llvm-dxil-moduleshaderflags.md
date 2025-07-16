---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dxil/moduleshaderflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ModuleShaderFlags` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::dxil::ModuleShaderFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">Target/DirectX/DXILShaderFlags.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa992db5c16c5e03bacbeefcae61b8bda">initialize</a> (Module &amp;, DXILResourceTypeMap &amp;DRTM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct <a href="/web-llvm/docs/api/structs/llvm/dxil/moduleshaderflags">ModuleShaderFlags</a> for module <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M. <a href="#aa992db5c16c5e03bacbeefcae61b8bda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/computedshaderflags">ComputedShaderFlags</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8c288b42e10147c8d6a7b007cbffd7">getFunctionFlags</a> (const Function *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the shader flags mask of the specified function Func. <a href="#a3c8c288b42e10147c8d6a7b007cbffd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/computedshaderflags">ComputedShaderFlags</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4f101b30074a95c86be6991752c5c3">getCombinedFlags</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ea8bd37a7dc11c39279e67e1385a7d">updateFunctionFlags</a> (ComputedShaderFlags &amp;, const Instruction &amp;, DXILResourceTypeMap &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the shader flags mask based on the given instruction. <a href="#ad9ea8bd37a7dc11c39279e67e1385a7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/structs/llvm/dxil/computedshaderflags">ComputedShaderFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8cf3b9d35842aadd655b022f356e38d">FunctionFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of Function-Shader Flag Mask pairs representing properties of each of the functions in the module. <a href="#ac8cf3b9d35842aadd655b022f356e38d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dxil/computedshaderflags">ComputedShaderFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c07c36c4fdf88732affb1b557a9fa81">CombinedSFMask</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combined Shader Flag Mask of all functions of the module. <a href="#a4c07c36c4fdf88732affb1b557a9fa81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getCombinedFlags() {#adf4f101b30074a95c86be6991752c5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ComputedShaderFlags &amp; llvm::dxil::ModuleShaderFlags::getCombinedFlags ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysisprinter/#a0784c57dc0671927404b56c94ec983c8">llvm::dxil::ShaderFlagsAnalysisPrinter::run</a>.</p>

</div>
</div>

### getFunctionFlags() {#a3c8c288b42e10147c8d6a7b007cbffd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ComputedShaderFlags &amp; ModuleShaderFlags::getFunctionFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the shader flags mask of the specified function Func.</p>

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-cpp">DXILShaderFlags.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysisprinter/#a0784c57dc0671927404b56c94ec983c8">llvm::dxil::ShaderFlagsAnalysisPrinter::run</a>.</p>

</div>
</div>

### initialize() {#aa992db5c16c5e03bacbeefcae61b8bda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleShaderFlags::initialize (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct <a href="/web-llvm/docs/api/structs/llvm/dxil/moduleshaderflags">ModuleShaderFlags</a> for module <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-cpp">DXILShaderFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/scc-iterator/#a7d6ec03718a5e48f3ec7ce22fefcb91d">llvm::scc_iterator&lt; GraphT, GT &gt;::isAtEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/computedshaderflags/#a6118b92eeded01ec4ff9d4c162b41a2f">llvm::dxil::ComputedShaderFlags::merge</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3c1a67796e24a843db8a6766baa54c21">llvm::scc_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysis/#aac5850fcb98ccf20d9a084c65b224df9">llvm::dxil::ShaderFlagsAnalysis::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### updateFunctionFlags() {#ad9ea8bd37a7dc11c39279e67e1385a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleShaderFlags::updateFunctionFlags (<a href="/web-llvm/docs/api/structs/llvm/dxil/computedshaderflags">ComputedShaderFlags</a> &amp; CSF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the shader flags mask based on the given instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CSF</td>
<td class="doxyParamItemDescription"><p>Shader flags mask to update.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to check.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-cpp">DXILShaderFlags.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CombinedSFMask {#a4c07c36c4fdf88732affb1b557a9fa81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComputedShaderFlags llvm::dxil::ModuleShaderFlags::CombinedSFMask {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combined Shader Flag Mask of all functions of the module.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>.</p>

</div>
</div>

### FunctionFlags {#ac8cf3b9d35842aadd655b022f356e38d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, ComputedShaderFlags&gt; llvm::dxil::ModuleShaderFlags::FunctionFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of Function-Shader Flag Mask pairs representing properties of each of the functions in the module.</p>


<p>Shader Flags of each function represent both module-level and function-level flags</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-cpp">DXILShaderFlags.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
