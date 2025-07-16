---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/sisched
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `SISched` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::SISched { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6bcd3ad1ec3f1be308048693474bd19">tryLess</a> (int TryVal, int CandVal, SISchedulerCandidate &amp;TryCand, SISchedulerCandidate &amp;Cand, SIScheduleCandReason Reason)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc548582a68bc6e9519f88a7484ab71">tryGreater</a> (int TryVal, int CandVal, SISchedulerCandidate &amp;TryCand, SISchedulerCandidate &amp;Cand, SIScheduleCandReason Reason)</td>
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

### tryGreater() {#a0fc548582a68bc6e9519f88a7484ab71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SISched::tryGreater (int TryVal, int CandVal, <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate">SISchedulerCandidate</a> &amp; TryCand, <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate">SISchedulerCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06">SIScheduleCandReason</a> Reason)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate/#aad4e6825e23d2c00e13507242d24bc63">llvm::SISchedulerCandidate::Reason</a> and <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate/#ad6034fabf889a5e1ac165bb89b95085e">llvm::SISchedulerCandidate::setRepeat</a>.</p>

</div>
</div>

### tryLess() {#ac6bcd3ad1ec3f1be308048693474bd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SISched::tryLess (int TryVal, int CandVal, <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate">SISchedulerCandidate</a> &amp; TryCand, <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate">SISchedulerCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06">SIScheduleCandReason</a> Reason)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate/#aad4e6825e23d2c00e13507242d24bc63">llvm::SISchedulerCandidate::Reason</a> and <a href="/web-llvm/docs/api/structs/llvm/sischedulercandidate/#ad6034fabf889a5e1ac165bb89b95085e">llvm::SISchedulerCandidate::setRepeat</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
