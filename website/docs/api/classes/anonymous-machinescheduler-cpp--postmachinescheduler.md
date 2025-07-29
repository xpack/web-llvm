---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PostMachineScheduler` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler">PostMachineScheduler</a> runs after shortly before code emission. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MachineScheduler.cpp}::PostMachineScheduler { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95ac78157333c863b9fb682756477f6e">PostMachineScheduler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065b9f9c1b17415e3e76fb115be4f7b4">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a065b9f9c1b17415e3e76fb115be4f7b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1dc85fd08ff7aa2a4057683e7a4dc8f">runOnMachineFunction</a> (MachineFunction &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#ab1dc85fd08ff7aa2a4057683e7a4dc8f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b741fadafc61d8c2e6409af2fc24e35">createPostMachineScheduler</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiate a <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> for PostRA scheduling that will be owned by the caller. <a href="#a5b741fadafc61d8c2e6409af2fc24e35">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b05199064ffa4992b9874f2470dad1a">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler">PostMachineScheduler</a> runs after shortly before code emission.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PostMachineScheduler() {#a95ac78157333c863b9fb682756477f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostRA Machine Instruction false PostMachineScheduler::PostMachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a5b05199064ffa4992b9874f2470dad1a">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4620b31befc2e9df66eeb669568332c6">llvm::initializePostMachineSchedulerPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase/#abed31a5bcff83980a1e38c534031aae8">anonymous{MachineScheduler.cpp}::MachineSchedulerBase::MachineSchedulerBase</a> and <a href="#a95ac78157333c863b9fb682756477f6e">PostMachineScheduler</a>.</p>


<p>Referenced by <a href="#a95ac78157333c863b9fb682756477f6e">PostMachineScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a065b9f9c1b17415e3e76fb115be4f7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PostMachineScheduler::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### runOnMachineFunction() {#ab1dc85fd08ff7aa2a4057683e7a4dc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PostMachineScheduler::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a55290be59c885ea01c412fa6926b61cf">llvm::MachineSchedContext::AA</a>, <a href="#a5b741fadafc61d8c2e6409af2fc24e35">createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#ad6a82628c5bb536ea7591cc3d51ba235">EnablePostRAMachineSched</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ab4787adecfc77e72db225098a27e902f">llvm::TargetSubtargetInfo::enablePostRAMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a07525563cb9c2a3cb6d64e3f885f038e">llvm::MachineSchedContext::MF</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a9334842806d97bee74af8752ebe19fbe">llvm::MachineSchedContext::MLI</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a3c04bf922b53ed32316b9725a99a5b2f">llvm::MachineSchedContext::PassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c735bd46fe1e1b5f6f85a710d99e149">Scheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase/#a5d9f088a58ed26977308b92dba6c50f6">anonymous{MachineScheduler.cpp}::MachineSchedulerBase::scheduleRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d101d816188a045c0b595a6a2c5d3a3">llvm::VerifyScheduling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createPostMachineScheduler() {#a5b741fadafc61d8c2e6409af2fc24e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * PostMachineScheduler::createPostMachineScheduler ()</td>
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

<p>Instantiate a <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> for PostRA scheduling that will be owned by the caller.</p>


<p>We don't have a command line option to override the postRA scheduler. The <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> must configure it.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa2f0c2f2a077d67dc0bcb24bc31e3b05">llvm::createGenericSchedPostRA</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a3c04bf922b53ed32316b9725a99a5b2f">llvm::MachineSchedContext::PassConfig</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c735bd46fe1e1b5f6f85a710d99e149">Scheduler</a>.</p>


<p>Referenced by <a href="#ab1dc85fd08ff7aa2a4057683e7a4dc8f">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a5b05199064ffa4992b9874f2470dad1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char PostMachineScheduler::ID = 0</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="#a95ac78157333c863b9fb682756477f6e">PostMachineScheduler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
