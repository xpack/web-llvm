---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/r600codegenpassbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `R600CodeGenPassBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::R600CodeGenPassBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-h">Target/AMDGPU/R600TargetMachine.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder">CodeGenPassBuilder&lt;DerivedT, TargetMachineT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides access to building LLVM's passes. <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11222005f0328f5e170a2f5cf192016">R600CodeGenPassBuilder</a> (R600TargetMachine &amp;TM, const CGPassBuilderOption &amp;Opts, PassInstrumentationCallbacks *PIC)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4857ce3ba6cee3635e50703864bd4ff6">addPreISel</a> (AddIRPass &amp;addPass) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae18e0b40f7eb65cfab4b07cd12399e5f">addAsmPrinter</a> (AddMachinePass &amp;, CreateMCStreamer) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02d63f3a8a5bf73ae45123521411860">addInstSelector</a> (AddMachinePass &amp;) const</td>
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


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-h">R600TargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### R600CodeGenPassBuilder() {#ad11222005f0328f5e170a2f5cf192016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R600CodeGenPassBuilder::R600CodeGenPassBuilder (<a href="/web-llvm/docs/api/classes/llvm/r600targetmachine">R600TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/cgpassbuilderoption">CGPassBuilderOption</a> &amp; Opts, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> * PIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-h">R600TargetMachine.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-cpp">R600TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a94d7ce2e38cb6acae735d6edb74c8fa7">llvm::CodeGenPassBuilder&lt; R600CodeGenPassBuilder, R600TargetMachine &gt;::CodeGenPassBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; R600CodeGenPassBuilder, R600TargetMachine &gt;::Opt</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a8b37f13bb1431bc3965bbdfc110a5fb1">llvm::CodeGenPassBuilder&lt; R600CodeGenPassBuilder, R600TargetMachine &gt;::PIC</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; R600CodeGenPassBuilder, R600TargetMachine &gt;::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAsmPrinter() {#ae18e0b40f7eb65cfab4b07cd12399e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600CodeGenPassBuilder::addAsmPrinter (AddMachinePass &amp; addPass, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a738a8c97344f7d78bfb36623251608ad">CreateMCStreamer</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-h">R600TargetMachine.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-cpp">R600TargetMachine.cpp</a>.</p>

</div>
</div>

### addInstSelector() {#af02d63f3a8a5bf73ae45123521411860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error R600CodeGenPassBuilder::addInstSelector (AddMachinePass &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-h">R600TargetMachine.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-cpp">R600TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### addPreISel() {#a4857ce3ba6cee3635e50703864bd4ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600CodeGenPassBuilder::addPreISel (AddIRPass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-h">R600TargetMachine.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-cpp">R600TargetMachine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-cpp">R600TargetMachine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targetmachine-h">R600TargetMachine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
