---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpucodegenpassbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUCodeGenPassBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUCodeGenPassBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">Target/AMDGPU/AMDGPUTargetMachine.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a7c7c6bbfd71961bde7ce21a2935c77">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder">CodeGenPassBuilder</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/amdgpucodegenpassbuilder">AMDGPUCodeGenPassBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine">GCNTargetMachine</a> &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be4e155bde9eb2f302e410873a622df">AMDGPUCodeGenPassBuilder</a> (GCNTargetMachine &amp;TM, const CGPassBuilderOption &amp;Opts, PassInstrumentationCallbacks *PIC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f1bc059bf60b514a7341609ac61f06">addIRPasses</a> (AddIRPass &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b26a2c75ccb8a98adc75f9c50ce1a8">addCodeGenPrepare</a> (AddIRPass &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aee5c5440e6804e83ca860abc1ab33e">addPreISel</a> (AddIRPass &amp;addPass) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c3d4837ac7e391cd0243717b32b3b1">addILPOpts</a> (AddMachinePass &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c1a850e0e73781b9c78aea357791a1">addAsmPrinter</a> (AddMachinePass &amp;, CreateMCStreamer) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16180e143d7be2ba583e5d9903361415">addInstSelector</a> (AddMachinePass &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2114a650c4496b5ffb99ef2203bdfb15">addMachineSSAOptimization</a> (AddMachinePass &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada817a3e188aee5b74d50154382fc6ee">addPostRegAlloc</a> (AddMachinePass &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee664c21a9659d262c33bc98eeeba042">isPassEnabled</a> (const cl::opt&lt; bool &gt; &amp;Opt, CodeGenOptLevel Level=CodeGenOptLevel::Default) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a pass is enabled given <span class="doxyComputerOutput">Opt</span> option. <a href="#aee664c21a9659d262c33bc98eeeba042">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4153a018914eefcde71d2d9dde72c296">addEarlyCSEOrGVNPass</a> (AddIRPass &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a6c4b146a083c65a6e7bf912693dab">addStraightLineScalarOptimizationPasses</a> (AddIRPass &amp;) const</td>
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


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a4a7c7c6bbfd71961bde7ce21a2935c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPUCodeGenPassBuilder::Base =  CodeGenPassBuilder&lt;AMDGPUCodeGenPassBuilder, GCNTargetMachine&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AMDGPUCodeGenPassBuilder() {#a5be4e155bde9eb2f302e410873a622df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUCodeGenPassBuilder::AMDGPUCodeGenPassBuilder (<a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine">GCNTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/cgpassbuilderoption">CGPassBuilderOption</a> &amp; Opts, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> * PIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a94d7ce2e38cb6acae735d6edb74c8fa7">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::CodeGenPassBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#abf8928310db68013b2d547df352d9345">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::disablePass</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::Opt</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a8b37f13bb1431bc3965bbdfc110a5fb1">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::PIC</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAsmPrinter() {#aa6c1a850e0e73781b9c78aea357791a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addAsmPrinter (AddMachinePass &amp; addPass, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a738a8c97344f7d78bfb36623251608ad">CreateMCStreamer</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2082 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### addCodeGenPrepare() {#ab0b26a2c75ccb8a98adc75f9c50ce1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addCodeGenPrepare (AddIRPass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2001 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a9e1385ad22d85a41207f9c1e158788ea">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::addCodeGenPrepare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#aa7674f1c87a00bb297f95d82ab2a4d34">EnableLoadStoreVectorizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a2c744b9ce60caa4eca00a83b3d09a0f6">EnableLowerKernelArguments</a>, <a href="#aee664c21a9659d262c33bc98eeeba042">isPassEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>

</div>
</div>

### addEarlyCSEOrGVNPass() {#a4153a018914eefcde71d2d9dde72c296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addEarlyCSEOrGVNPass (AddIRPass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>


<p>Referenced by <a href="#a68f1bc059bf60b514a7341609ac61f06">addIRPasses</a> and <a href="#a46a6c4b146a083c65a6e7bf912693dab">addStraightLineScalarOptimizationPasses</a>.</p>

</div>
</div>

### addILPOpts() {#ab8c3d4837ac7e391cd0243717b32b3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addILPOpts (AddMachinePass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2075 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a2d618dbbb3180d74c19249f3419cb54f">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::addILPOpts</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ad406e3834655b047b66b1ff9cb4b43c8">EnableEarlyIfConversion</a>.</p>

</div>
</div>

### addInstSelector() {#a16180e143d7be2ba583e5d9903361415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error AMDGPUCodeGenPassBuilder::addInstSelector (AddMachinePass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2087 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>

</div>
</div>

### addIRPasses() {#a68f1bc059bf60b514a7341609ac61f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addIRPasses (AddIRPass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1933 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="#a4153a018914eefcde71d2d9dde72c296">addEarlyCSEOrGVNPass</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#ad6d8ab9f89af9e5c0329a300b3dfd7ab">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::addIRPasses</a>, <a href="#a46a6c4b146a083c65a6e7bf912693dab">addStraightLineScalarOptimizationPasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ae18dc569224d0d427aa4f6492414afd7">AMDGPUAtomicOptimizerStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a4666f73765be78d7dddd8b90072ceebe">EnableImageIntrinsicOptimizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a03c9aa0c85dac0e1b72a3e3f2a91b569">EnableLowerModuleLDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#abf6ff331b4916398a8ca064fb26dd7dd">EnableScalarIRPasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a27a9bf5df1e9bac5d7d23128b6a4e9b7">EnableSwLowerLDS</a>, <a href="#aee664c21a9659d262c33bc98eeeba042">isPassEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a6dcde25571ce05ae09b3acb968fbd9b1">LowerCtorDtor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76a29d4416121b20dd5ccd9ffca40c05524">llvm::Lowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#abf5a8d526d96551c07ff875293def295">RemoveIncompatibleFunctions</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#a2114a650c4496b5ffb99ef2203bdfb15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addMachineSSAOptimization (AddMachinePass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a920cca6ac99ee512714d624a25a90d34">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::addMachineSSAOptimization</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a6ac4f65ba5b4b6a993c6971af337d862">EnableDPPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a382dac520bb7468263680ea0013387aa">EnableSDWAPeephole</a> and <a href="#aee664c21a9659d262c33bc98eeeba042">isPassEnabled</a>.</p>

</div>
</div>

### addPostRegAlloc() {#ada817a3e188aee5b74d50154382fc6ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addPostRegAlloc (AddMachinePass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a049e7f55b396434a1455d53aba79c259">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::addPostRegAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>

</div>
</div>

### addPreISel() {#a7aee5c5440e6804e83ca860abc1ab33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addPreISel (AddIRPass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>

</div>
</div>

### addStraightLineScalarOptimizationPasses() {#a46a6c4b146a083c65a6e7bf912693dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPassBuilder::addStraightLineScalarOptimizationPasses (AddIRPass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="#a4153a018914eefcde71d2d9dde72c296">addEarlyCSEOrGVNPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#aaf7b119415eac8f2fe46bb4d78d85f5f">EnableLoopPrefetch</a> and <a href="#aee664c21a9659d262c33bc98eeeba042">isPassEnabled</a>.</p>


<p>Referenced by <a href="#a68f1bc059bf60b514a7341609ac61f06">addIRPasses</a>.</p>

</div>
</div>

### isPassEnabled() {#aee664c21a9659d262c33bc98eeeba042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPassBuilder::isPassEnabled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt; &amp; Opt, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> Level=<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a pass is enabled given <span class="doxyComputerOutput">Opt</span> option.</p>


<p>The option always overrides defaults if explicitly used. Otherwise its default will be used given that a pass shall work at an optimization <span class="doxyComputerOutput">Level</span> minimum.</p>


<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 2120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::Opt</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::TM</a>.</p>


<p>Referenced by <a href="#ab0b26a2c75ccb8a98adc75f9c50ce1a8">addCodeGenPrepare</a>, <a href="#a68f1bc059bf60b514a7341609ac61f06">addIRPasses</a>, <a href="#a2114a650c4496b5ffb99ef2203bdfb15">addMachineSSAOptimization</a> and <a href="#a46a6c4b146a083c65a6e7bf912693dab">addStraightLineScalarOptimizationPasses</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
