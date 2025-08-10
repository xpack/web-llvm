---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machinescheduler-cpp-/machinescheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineScheduler` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a> runs after coalescing and before register allocation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MachineScheduler.cpp}::MachineScheduler { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase">MachineSchedulerBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for a machine scheduler class that can run at any point. <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0107c12ed6aa7d7935b96015ef5b9ca4">MachineScheduler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe823cc8d6d37bb30948aa5598ebbcd">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#acfe823cc8d6d37bb30948aa5598ebbcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8539983d1d0a8b07d92b91c16b9f7a5a">runOnMachineFunction</a> (MachineFunction &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Top-level <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a> pass driver. <a href="#a8539983d1d0a8b07d92b91c16b9f7a5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ba7babfe87314e8d1fe3db5a8dc805">createMachineScheduler</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiate a <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that will be owned by the caller. <a href="#a17ba7babfe87314e8d1fe3db5a8dc805">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a8e8efbbc1034741164545a4777749">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a> runs after coalescing and before register allocation.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineScheduler() {#a0107c12ed6aa7d7935b96015ef5b9ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Machine Instruction false MachineScheduler::MachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a54a8e8efbbc1034741164545a4777749">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b59b13f97bee321b57c23f4c0cb3ac2">llvm::initializeMachineSchedulerPass</a>, <a href="#a0107c12ed6aa7d7935b96015ef5b9ca4">MachineScheduler</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase/#abed31a5bcff83980a1e38c534031aae8">anonymous{MachineScheduler.cpp}::MachineSchedulerBase::MachineSchedulerBase</a>.</p>


<p>Referenced by <a href="#a0107c12ed6aa7d7935b96015ef5b9ca4">MachineScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#acfe823cc8d6d37bb30948aa5598ebbcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineScheduler::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a8539983d1d0a8b07d92b91c16b9f7a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineScheduler::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Top-level <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a> pass driver.</p>


<p>Visit blocks in function order. Divide each block into scheduling regions and visit them bottom-up. Visiting regions bottom-up is not required, but is consistent with the DAG builder, which traverses the interior of the scheduling regions bottom-up.</p>


<p>This design avoids exposing scheduling boundaries to the DAG builder, simplifying the DAG builder's support for "special" target instructions. At the same time the design allows target schedulers to operate across scheduling boundaries, for example to bundle the boundary instructions without reordering them. This creates complexity, because the target scheduler must update the RegionBegin and RegionEnd positions cached by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> whenever adding or removing instructions. A much simpler design would be to split blocks at scheduling boundaries, but LLVM has a general bias against block splitting purely for implementation simplicity.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a55290be59c885ea01c412fa6926b61cf">llvm::MachineSchedContext::AA</a>, <a href="#a17ba7babfe87314e8d1fe3db5a8dc805">createMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a4b2ef2249df68fd80eb12e019875a75c">EnableMachineSched</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a73d86eabd25d4e6a05310e1b0d445d0a">llvm::TargetSubtargetInfo::enableMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#aa604d18378910f87649c38841cc1531c">llvm::MachineSchedContext::LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a433a18eaf42c2038f519428e580cbc53">llvm::MachineSchedContext::MDT</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a07525563cb9c2a3cb6d64e3f885f038e">llvm::MachineSchedContext::MF</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a9334842806d97bee74af8752ebe19fbe">llvm::MachineSchedContext::MLI</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a3c04bf922b53ed32316b9725a99a5b2f">llvm::MachineSchedContext::PassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a510c29d57e9f0343df48b7c58cb89228">llvm::MachineSchedContext::RegClassInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c735bd46fe1e1b5f6f85a710d99e149">Scheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase/#a5d9f088a58ed26977308b92dba6c50f6">anonymous{MachineScheduler.cpp}::MachineSchedulerBase::scheduleRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d101d816188a045c0b595a6a2c5d3a3">llvm::VerifyScheduling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createMachineScheduler() {#a17ba7babfe87314e8d1fe3db5a8dc805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * MachineScheduler::createMachineScheduler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instantiate a <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that will be owned by the caller.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a46878327214ad358989afa9f97d835f6">MachineSchedOpt</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a3c04bf922b53ed32316b9725a99a5b2f">llvm::MachineSchedContext::PassConfig</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c735bd46fe1e1b5f6f85a710d99e149">Scheduler</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a7c2f26bf8531d7774d205e720a71d616">useDefaultMachineSched</a>.</p>


<p>Referenced by <a href="#a8539983d1d0a8b07d92b91c16b9f7a5a">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a54a8e8efbbc1034741164545a4777749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char MachineScheduler::ID = 0</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="#a0107c12ed6aa7d7935b96015ef5b9ca4">MachineScheduler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
