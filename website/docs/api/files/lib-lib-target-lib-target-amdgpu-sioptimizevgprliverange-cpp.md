---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SIOptimizeVGPRLiveRange.cpp` File Reference

<p>This pass tries to remove unnecessary VGPR live ranges in divergent if-else structures and waterfall loops. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-h">SIOptimizeVGPRLiveRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-h">MCTargetDesc/AMDGPUMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">llvm/CodeGen/LiveVariables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-sioptimizevgprliverange-cpp-">anonymous{SIOptimizeVGPRLiveRange.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange">SIOptimizeVGPRLiveRange</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverangelegacy">SIOptimizeVGPRLiveRangeLegacy</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad745a4d895a366bdfc3486d667aaa3b2">INITIALIZE_PASS_BEGIN</a> (SIOptimizeVGPRLiveRangeLegacy, DEBUG_TYPE, "SI Optimize VGPR LiveRange", false, false) INITIALIZE_PASS_END(SIOptimizeVGPRLiveRangeLegacy</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a10fde6bea2f819ef87db20d8fe3085c7">SI</a> Optimize VGPR</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc192e3e53887e1d6fa56abbe10530e6">LiveRange</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a10fde6bea2f819ef87db20d8fe3085c7">SI</a> Optimize VGPR</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8ae3038974369df91a2df8bf131749">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"si-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">opt</a>-vgpr-liverange"</td>
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

<p>This pass tries to remove unnecessary VGPR live ranges in divergent if-else structures and waterfall loops.</p>


<p>When we do structurization, we usually transform an if-else into two successive if-then (with a flow block to do predicate inversion). Consider a simple case after structurization: A divergent value a was defined before if-else and used in both THEN (use in THEN is optional) and ELSE part: bb.if: a = ... ... bb.then: ... = op a ... // a can be dead here bb.flow: ... bb.else: ... = a ... bb.endif</p>


<p>As register allocator has no idea of the thread-control-flow, it will just assume a would be alive in the whole range of bb.then because of a later use in bb.else. On <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> architecture, the VGPR is accessed with respect to exec mask. For this if-else case, the lanes active in bb.then will be inactive in bb.else, and vice-versa. So we are safe to say that a was dead after the last use in bb.then until the end of the block. The reason is the instructions in bb.then will only overwrite lanes that will never be accessed in bb.else.</p>


<p>This pass aims to tell register allocator that a is in-fact dead, through inserting a phi-node in bb.flow saying that a is undef when coming from bb.then, and then replace the uses in the bb.else with the result of newly inserted phi.</p>


<p>Two key conditions must be met to ensure correctness: 1.) The def-point should be in the same loop-level as if-else-endif to make sure the second loop iteration still get correct data. 2.) There should be no further uses after the IF-ELSE region.</p>


<p>Waterfall loops get inserted around instructions that use divergent values but can only be executed with a uniform value. For example an indirect call to a divergent address: bb.start: a = ... fun = ... ... bb.loop: call fun (a) ... // a can be dead here loop bb.loop</p>


<p>The loop block is executed multiple times, but it is run exactly once for each active lane. Similar to the if-else case, the register allocator assumes that a is live throughout the loop as it is used again in the next iteration. If a is a VGPR that is unused after the loop, it does not need to be live after its last use in the loop block. By inserting a phi-node at the start of bb.loop that is undef when coming from bb.loop, the register allocation knows that the value of a does not need to be preserved through iterations of the loop.</p>


<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS\_BEGIN() {#ad745a4d895a366bdfc3486d667aaa3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (SIOptimizeVGPRLiveRangeLegacy, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "SI Optimize VGPR LiveRange", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp">SIOptimizeVGPRLiveRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp">SIOptimizeVGPRLiveRange.cpp</a>.</p>

</div>
</div>

### false {#a3f8ae3038974369df91a2df8bf131749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SI Optimize VGPR false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp">SIOptimizeVGPRLiveRange.cpp</a>.</p>

</div>
</div>

### LiveRange {#acc192e3e53887e1d6fa56abbe10530e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SI Optimize VGPR LiveRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp">SIOptimizeVGPRLiveRange.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stacklifetime/#a81507dd38799f96ad855b5b264959e83">llvm::StackLifetime::getFullLiveRange</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a7b2ec2588cc48710e468563a0e71d24a">llvm::LiveIntervals::getRegUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/stacklifetime/#a25fa11bd51d7c0fde33cc3534f68abda">llvm::StackLifetime::run</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"si-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">opt</a>-vgpr-liverange"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp">SIOptimizeVGPRLiveRange.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
