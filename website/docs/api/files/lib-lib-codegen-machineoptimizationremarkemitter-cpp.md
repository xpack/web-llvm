---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachineOptimizationRemarkEmitter.cpp` File Reference

<p>===- <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp">MachineOptimizationRemarkEmitter.cpp</a> - Opt Diagnostic -*- C++ -*—===// <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">llvm/CodeGen/MachineOptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lazymachineblockfrequencyinfo-h">llvm/CodeGen/LazyMachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad092d1a418629cb8fbdbd309b7f5e0b">INITIALIZE_PASS_BEGIN</a> (MachineOptimizationRemarkEmitterPass, ORE_NAME, ore_name, true, true) INITIALIZE_PASS_END(MachineOptimizationRemarkEmitterPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31de376808b461270c4c5df8d265063d">ore_name</a>[] = "Machine <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmipeephole-cpp/#a2fe1d201770f2584dbb2a26cd39bb556">Optimization</a> Remark Emitter"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa78e7d20d1f8e08eb24f3a250f74dca">ORE_NAME</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a24fc2eb8c1af6d06ac15bcec47f088">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a7590cc0b4f935e47df493032866a4">ORE_NAME</a>&nbsp;&nbsp;&nbsp;"machine-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">opt</a>-remark-emitter"</td>
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

<p>===- <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp">MachineOptimizationRemarkEmitter.cpp</a> - Opt Diagnostic -*- C++ -*—===//</p>


<p>Part of the LLVM Project, under the Apache License v2.0 with LLVM Exceptions. See <a href="https://llvm.org/LICENSE.txt">https://llvm.org/LICENSE.txt</a> for license information. SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception</p>


<p>===------------------------------------------------------------------—===//</p>


<p>Optimization diagnostic interfaces for machine passes. It's packaged as an analysis pass so that by using this service passes become dependent on MBFI as well. MBFI is used to compute the "hotness" of the diagnostic message.</p>


<p>===------------------------------------------------------------------—===//</p>


<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS\_BEGIN() {#aad092d1a418629cb8fbdbd309b7f5e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitterpass">MachineOptimizationRemarkEmitterPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp/#a54a7590cc0b4f935e47df493032866a4">ORE_NAME</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp/#a31de376808b461270c4c5df8d265063d">ore_name</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp">MachineOptimizationRemarkEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp/#a54a7590cc0b4f935e47df493032866a4">ORE_NAME</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp/#a31de376808b461270c4c5df8d265063d">ore_name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ore\_name {#a31de376808b461270c4c5df8d265063d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ore_name = "Machine <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmipeephole-cpp/#a2fe1d201770f2584dbb2a26cd39bb556">Optimization</a> Remark Emitter"</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp">MachineOptimizationRemarkEmitter.cpp</a>.</p>

</div>
</div>

### ORE\_NAME {#afa78e7d20d1f8e08eb24f3a250f74dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ORE_NAME</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp">MachineOptimizationRemarkEmitter.cpp</a>.</p>

</div>
</div>

### true {#a1a24fc2eb8c1af6d06ac15bcec47f088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp">MachineOptimizationRemarkEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ORE\_NAME {#a54a7590cc0b4f935e47df493032866a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ORE_NAME&nbsp;&nbsp;&nbsp;"machine-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">opt</a>-remark-emitter"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoptimizationremarkemitter-cpp">MachineOptimizationRemarkEmitter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
