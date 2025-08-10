---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/regallocpriorityadvisor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `RegAllocPriorityAdvisor.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">llvm/CodeGen/VirtRegMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4ccb1e3e3e40a5db92d467a97369c6">INITIALIZE_PASS</a> (RegAllocPriorityAdvisorAnalysis, "regalloc-priority", "Regalloc priority policy", false, true) namespace</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisoranalysis/#a1deddc62c2392976d25f8854e553266e">RegAllocPriorityAdvisorAnalysis::AdvisorMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03aa1778af59adfedc050da42fd4604">Mode</a>("regalloc-enable-priority-advisor", cl::Hidden, cl::init(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Default), cl::desc("Enable regalloc advisor mode"), cl::values(clEnumValN(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Default, "default", "Default"), clEnumValN(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Release, "release", "precompiled"), clEnumValN(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Development, "development", "for training"), clEnumValN(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Dummy, "dummy", "prioritize low virtual register numbers for test and debug")))</td>
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

## Functions

### INITIALIZE\_PASS() {#acb4ccb1e3e3e40a5db92d467a97369c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisoranalysis">RegAllocPriorityAdvisorAnalysis</a>, "regalloc-priority", "Regalloc priority policy", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp">RegAllocPriorityAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ab007d6c51634eb65e4f4f9dab4eb6a8c">llvm::Pass::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisoranalysis/#a7f4c9b6d8a72709c186c17043f62df58">llvm::RegAllocPriorityAdvisorAnalysis::getAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisoranalysis/#a8349e67bcda852a915644c9feb681d1e">llvm::RegAllocPriorityAdvisorAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisoranalysis/#a0a7d15aec3410da7d0d5d555aba98301">llvm::RegAllocPriorityAdvisorAnalysis::RegAllocPriorityAdvisorAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Mode {#ad03aa1778af59adfedc050da42fd4604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; RegAllocPriorityAdvisorAnalysis::AdvisorMode &gt; Mode("regalloc-enable-priority-advisor", cl::Hidden, cl::init(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Default), cl::desc("Enable regalloc advisor mode"), cl::values( clEnumValN(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Default, "default", "Default"), clEnumValN(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Release, "release", "precompiled"), clEnumValN(RegAllocPriorityAdvisorAnalysis::AdvisorMode::Development, "development", "for training"), clEnumValN( RegAllocPriorityAdvisorAnalysis::AdvisorMode::Dummy, "dummy", "prioritize low virtual register numbers for test and debug")))</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp">RegAllocPriorityAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
