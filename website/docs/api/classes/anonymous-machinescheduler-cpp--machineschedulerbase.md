---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineSchedulerBase` Class

<p>Base class for a machine scheduler class that can run at any point. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MachineScheduler.cpp}::MachineSchedulerBase { ... }
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> provides enough context from the MachineScheduler pass for the target to instantiate a scheduler. <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a> runs after coalescing and before register allocation. <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler">PostMachineScheduler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler">PostMachineScheduler</a> runs after shortly before code emission. <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed31a5bcff83980a1e38c534031aae8">MachineSchedulerBase</a> (char &amp;ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03962eb8f2d1aae10915000f72a8b030">print</a> (raw_ostream &amp;O, const Module *=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print out the internal state of the pass. <a href="#a03962eb8f2d1aae10915000f72a8b030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d9f088a58ed26977308b92dba6c50f6">scheduleRegions</a> (ScheduleDAGInstrs &amp;Scheduler, bool FixKillFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main driver for both <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler">PostMachineScheduler</a>. <a href="#a5d9f088a58ed26977308b92dba6c50f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for a machine scheduler class that can run at any point.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineSchedulerBase() {#abed31a5bcff83980a1e38c534031aae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineScheduler.cpp}::MachineSchedulerBase::MachineSchedulerBase (char &amp; ID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a0107c12ed6aa7d7935b96015ef5b9ca4">anonymous{MachineScheduler.cpp}::MachineScheduler::MachineScheduler</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#a95ac78157333c863b9fb682756477f6e">anonymous{MachineScheduler.cpp}::PostMachineScheduler::PostMachineScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#a03962eb8f2d1aae10915000f72a8b030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineSchedulerBase::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
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

<p>print - Print out the internal state of the pass.</p>


<p>This is called by Analyze to print out the contents of an analysis. Otherwise it is not necessary to implement this method. Beware that the module pointer MAY be null. This automatically forwards to a virtual function that does not provide the Module* in case the analysis doesn't need it it can just be ignored.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### scheduleRegions() {#a5d9f088a58ed26977308b92dba6c50f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineSchedulerBase::scheduleRegions (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> &amp; Scheduler, bool FixKillFlags)</td>
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

<p>Main driver for both <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler">MachineScheduler</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler">PostMachineScheduler</a>.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82ab0315644106de03b36f143328179f">llvm::DumpCriticalPathLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#ae1be3a2fc5dfa3281d32b6fb4e4ea6dd">getSchedRegions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext/#a07525563cb9c2a3cb6d64e3f885f038e">llvm::MachineSchedContext::MF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a55fc025b3f9710787dfefd7a551c2568">SchedOnlyBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#aa9e9eecb42c6e825c279845f69f28aa2">SchedOnlyFunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c735bd46fe1e1b5f6f85a710d99e149">Scheduler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">anonymous{MachineScheduler.cpp}::PostMachineScheduler::runOnMachineFunction</a>.</p>

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
