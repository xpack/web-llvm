---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnmaxoccupancyschedstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCNMaxOccupancySchedStrategy` Class Reference

<p>The goal of this scheduling strategy is to maximize kernel occupancy (i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCNMaxOccupancySchedStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">Target/AMDGPU/GCNSchedStrategy.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy">GCNSchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a minimal scheduler strategy. <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aaa47dd65d2e5e66930f7c3bdb2a6bd">GCNMaxOccupancySchedStrategy</a> (const MachineSchedContext *C, bool IsLegacyScheduler=false)</td>
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

<p>The goal of this scheduling strategy is to maximize kernel occupancy (i.e.</p>


<p>maximum number of waves per simd).</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNMaxOccupancySchedStrategy() {#a1aaa47dd65d2e5e66930f7c3bdb2a6bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNMaxOccupancySchedStrategy::GCNMaxOccupancySchedStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C, bool IsLegacyScheduler=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0aff2914ea67320c4b23b0c3bf909a201c">llvm::ClusteredLowOccupancyReschedule</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a14f3300bee7a18474eb2f103afa3ea22">llvm::GCNSchedStrategy::GCNSchedStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a00473ec6bae66ae8a3e6a0fe74ee1aaa">GCNTrackers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0afc7d208fa38407036d4d3dfc7ac1ccff">llvm::OccInitialSchedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0aa2def37e6bb76e915e4ae7cc4b47ae7a">llvm::PreRARematerialize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a1736ffcc1fcc46c9c47748d5a9a04c4b">llvm::GCNSchedStrategy::SchedStages</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a3199673fa17ebc25c0c9925028d225e0">llvm::UnclusteredHighRPReschedule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
