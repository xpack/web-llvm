---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonconvergingvliwscheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HexagonConvergingVLIWScheduler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonConvergingVLIWScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-h">Target/Hexagon/HexagonMachineScheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler">ConvergingVLIWScheduler</a></td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel">VLIWResourceModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311da7498b4505daad3a41b25a4315cf">createVLIWResourceModel</a> (const TargetSubtargetInfo &amp;STI, const TargetSchedModel *SchedModel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1da83188ad8ac357edfd719ce2680f">SchedulingCost</a> (ReadyQueue &amp;Q, SUnit *SU, SchedCandidate &amp;Candidate, RegPressureDelta &amp;Delta, bool verbose) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Single point to compute overall scheduling cost. <a href="#a5b1da83188ad8ac357edfd719ce2680f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-h">HexagonMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Functions

### createVLIWResourceModel() {#a311da7498b4505daad3a41b25a4315cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWResourceModel * HexagonConvergingVLIWScheduler::createVLIWResourceModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-h">HexagonMachineScheduler.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-cpp">HexagonMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aeeea464a2bbf5ddf0aadd356246ca08d">llvm::ConvergingVLIWScheduler::SchedModel</a>.</p>

</div>
</div>

### SchedulingCost() {#a5b1da83188ad8ac357edfd719ce2680f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HexagonConvergingVLIWScheduler::SchedulingCost (<a href="/web-llvm/docs/api/classes/llvm/readyqueue">ReadyQueue</a> &amp; Q, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate">SchedCandidate</a> &amp; Candidate, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; Delta, bool verbose)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Single point to compute overall scheduling cost.</p>


<p>TODO: More heuristics will be used soon.</p>


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-h">HexagonMachineScheduler.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-cpp">HexagonMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a9b1bc7ac4c6a5eb2974a5fe039a629d3">llvm::ConvergingVLIWScheduler::Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a8838d66fd452f7cdd09e825269ecbf1fa0644396ca457428e0f89e799f32a1906">llvm::ConvergingVLIWScheduler::BotQID</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a187af70a733b698fbe59b50ff1fa0073">llvm::ConvergingVLIWScheduler::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#afe1bde7001d7b6a70198dc827f4a28e2">llvm::ReadyQueue::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a21e692502cb75b1488e8b4047000ace6">llvm::HexagonSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a274909b1f31ad2d3d3379de55467d377">llvm::SUnit::isInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ae92e52d0090af0f8abe764f84b20fd98">llvm::ConvergingVLIWScheduler::PriorityTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a70cc4724751ac8752aacd038a455a1c9">llvm::ConvergingVLIWScheduler::Top</a> and <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a8838d66fd452f7cdd09e825269ecbf1fa40f7f0675083aaa0ae6f43946859c03b">llvm::ConvergingVLIWScheduler::TopQID</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-cpp">HexagonMachineScheduler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-h">HexagonMachineScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
