---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machineschedcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineSchedContext` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> provides enough context from the MachineScheduler pass for the target to instantiate a scheduler. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MachineSchedContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
</div>

## Derived Structs

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8df817832c60969961bfb498488fc70">MachineSchedContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af839a40d46212c05a4bcacc90723dfa6">MachineSchedContext</a> (const MachineSchedContext &amp;other)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66a5fd1e8991685c46cfc1652bfeeaf">~MachineSchedContext</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7fa7afa53f16de2b5d8a584a8a353ee">operator=</a> (const MachineSchedContext &amp;other)=delete</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07525563cb9c2a3cb6d64e3f885f038e">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9334842806d97bee74af8752ebe19fbe">MLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433a18eaf42c2038f519428e580cbc53">MDT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c04bf922b53ed32316b9725a99a5b2f">PassConfig</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55290be59c885ea01c412fa6926b61cf">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa604d18378910f87649c38841cc1531c">LIS</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a510c29d57e9f0343df48b7c58cb89228">RegClassInfo</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> provides enough context from the MachineScheduler pass for the target to instantiate a scheduler.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineSchedContext() {#ac8df817832c60969961bfb498488fc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedContext::MachineSchedContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="#a510c29d57e9f0343df48b7c58cb89228">RegClassInfo</a>.</p>


<p>Referenced by <a href="#af839a40d46212c05a4bcacc90723dfa6">MachineSchedContext</a> and <a href="#ae7fa7afa53f16de2b5d8a584a8a353ee">operator=</a>.</p>

</div>
</div>

### MachineSchedContext() {#af839a40d46212c05a4bcacc90723dfa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineSchedContext::MachineSchedContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#ac8df817832c60969961bfb498488fc70">MachineSchedContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineSchedContext() {#ac66a5fd1e8991685c46cfc1652bfeeaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedContext::~MachineSchedContext ()</td>
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



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="#a510c29d57e9f0343df48b7c58cb89228">RegClassInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae7fa7afa53f16de2b5d8a584a8a353ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedContext &amp; llvm::MachineSchedContext::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#ac8df817832c60969961bfb498488fc70">MachineSchedContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AA {#a55290be59c885ea01c412fa6926b61cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::MachineSchedContext::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">anonymous{MachineScheduler.cpp}::PostMachineScheduler::runOnMachineFunction</a>.</p>

</div>
</div>

### LIS {#aa604d18378910f87649c38841cc1531c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* llvm::MachineSchedContext::LIS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a>.</p>

</div>
</div>

### MDT {#a433a18eaf42c2038f519428e580cbc53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominatorTree* llvm::MachineSchedContext::MDT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a>.</p>

</div>
</div>

### MF {#a07525563cb9c2a3cb6d64e3f885f038e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::MachineSchedContext::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">anonymous{MachineScheduler.cpp}::PostMachineScheduler::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase/#a5d9f088a58ed26977308b92dba6c50f6">anonymous{MachineScheduler.cpp}::MachineSchedulerBase::scheduleRegions</a>.</p>

</div>
</div>

### MLI {#a9334842806d97bee74af8752ebe19fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoopInfo* llvm::MachineSchedContext::MLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">anonymous{MachineScheduler.cpp}::PostMachineScheduler::runOnMachineFunction</a>.</p>

</div>
</div>

### PassConfig {#a3c04bf922b53ed32316b9725a99a5b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetPassConfig* llvm::MachineSchedContext::PassConfig = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a17ba7babfe87314e8d1fe3db5a8dc805">anonymous{MachineScheduler.cpp}::MachineScheduler::createMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#a5b741fadafc61d8c2e6409af2fc24e35">anonymous{MachineScheduler.cpp}::PostMachineScheduler::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">anonymous{MachineScheduler.cpp}::PostMachineScheduler::runOnMachineFunction</a>.</p>

</div>
</div>

### RegClassInfo {#a510c29d57e9f0343df48b7c58cb89228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterClassInfo* llvm::MachineSchedContext::RegClassInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ac8df817832c60969961bfb498488fc70">MachineSchedContext</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a> and <a href="#ac66a5fd1e8991685c46cfc1652bfeeaf">~MachineSchedContext</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
