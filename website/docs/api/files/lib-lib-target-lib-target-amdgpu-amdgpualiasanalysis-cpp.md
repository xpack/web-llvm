---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPUAliasAnalysis.cpp` File Reference

<p>This is the AMGPU address space based alias analysis pass. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-h">AMDGPUAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0515065c3dda393f7f50d4001c05abd">INITIALIZE_PASS</a> (AMDGPUAAWrapperPass, "amdgpu-aa", "AMDGPU Address space based Alias Analysis", false, true) INITIALIZE_PASS(AMDGPUExternalAAWrapper</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">amdgpu <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae516ea75555373b0b369a3d1b3cd41e2">wrapper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">amdgpu <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a> AMDGPU <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> space based Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f565f28385a6f2c7a4756ff6f3fa16">Wrapper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">amdgpu <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a> AMDGPU <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> space based Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8be48ebedcc3462ba559097546318d">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-aa"</td>
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

<p>This is the AMGPU address space based alias analysis pass.</p>

<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS() {#ae0515065c3dda393f7f50d4001c05abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/amdgpuaawrapperpass">AMDGPUAAWrapperPass</a>, "amdgpu-aa", "AMDGPU <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> space based Alias Analysis", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp">AMDGPUAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#abf8be48ebedcc3462ba559097546318d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">amdgpu aa AMDGPU Address space based Alias Analysis false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp">AMDGPUAliasAnalysis.cpp</a>.</p>

</div>
</div>

### wrapper {#ae516ea75555373b0b369a3d1b3cd41e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">amdgpu aa wrapper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp">AMDGPUAliasAnalysis.cpp</a>.</p>

</div>
</div>

### Wrapper {#a63f565f28385a6f2c7a4756ff6f3fa16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">amdgpu aa AMDGPU Address space based Alias Analysis Wrapper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp">AMDGPUAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/dyldelfobject/#ab3faa1531d64f96344a842d1bc4c2870">anonymous{RuntimeDyldELF.cpp}::DyldELFObject&lt; ELFT &gt;::create</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inteljiteventlistener-cpp-/#a6914f5f9e02468ebb7278d069dc68129">anonymous{IntelJITEventListener.cpp}::FunctionDescToIntelJITFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a5ccaa648716b2c4c8e0687f36e6c9fa2">llvm::MipsTargetLowering::getAddrGlobalLargeGOT</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab3547e3af4263fb24bac33b211aa07fb">llvm::X86TargetLowering::getTargetNodeName</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a8b89004d6a1586a674970b6a4c398d72">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::IntelIttnotifyInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/raiimfobsdelinstaller/#a00c6f51c9467d75562e53ebddec49d7b">llvm::RAIIMFObsDelInstaller::RAIIMFObsDelInstaller</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#ad1210df2e489436f417f18f10180ea44">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#abceb824dea15a0f50ab19fc7126f618f">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-aa"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp">AMDGPUAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
