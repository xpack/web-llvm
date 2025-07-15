---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-gcniterativescheduler-cpp-/schedstrategystub
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SchedStrategyStub` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> - Interface to the scheduling algorithm used by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>. <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a376803a4832fd696122afd9f644e862b">shouldTrackPressure</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if pressure tracking is needed before building the DAG and initializing this strategy. <a href="#a376803a4832fd696122afd9f644e862b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a714e2456d7b9d278c7bf71fbf0a29a24">shouldTrackLaneMasks</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if lanemasks should be tracked. <a href="#a714e2456d7b9d278c7bf71fbf0a29a24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f3847d5a3b54301af88fb61831b7d4">initialize</a> (ScheduleDAGMI *DAG) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the strategy after building the DAG for a new region. <a href="#ab6f3847d5a3b54301af88fb61831b7d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25dcd4c29d28fbdc0d457e7da5e6ee75">pickNode</a> (bool &amp;IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the next node to schedule, or return NULL. <a href="#a25dcd4c29d28fbdc0d457e7da5e6ee75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bb7ba3a13c6f476e281e51681f0749">schedNode</a> (SUnit *SU, bool IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify MachineSchedStrategy that ScheduleDAGMI has scheduled an instruction and updated scheduled/remaining flags in the DAG nodes. <a href="#ad1bb7ba3a13c6f476e281e51681f0749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a8278fb2c7ee302ba0211ebeb34f78">releaseTopNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all predecessor dependencies have been resolved, free this node for top-down scheduling. <a href="#a06a8278fb2c7ee302ba0211ebeb34f78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b3922506ec0d3510eec71e9e705186">releaseBottomNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all successor dependencies have been resolved, free this node for bottom-up scheduling. <a href="#aa7b3922506ec0d3510eec71e9e705186">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### initialize() {#ab6f3847d5a3b54301af88fb61831b7d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub::initialize (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the strategy after building the DAG for a new region.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>

</div>
</div>

### pickNode() {#a25dcd4c29d28fbdc0d457e7da5e6ee75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub::pickNode (bool &amp; IsTopNode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pick the next node to schedule, or return NULL.</p>


<p>Set IsTopNode to true to schedule the node at the top of the unscheduled region. Otherwise it will be scheduled at the bottom.</p>


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>

</div>
</div>

### releaseBottomNode() {#aa7b3922506ec0d3510eec71e9e705186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub::releaseBottomNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When all successor dependencies have been resolved, free this node for bottom-up scheduling.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>

</div>
</div>

### releaseTopNode() {#a06a8278fb2c7ee302ba0211ebeb34f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub::releaseTopNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When all predecessor dependencies have been resolved, free this node for top-down scheduling.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>

</div>
</div>

### schedNode() {#ad1bb7ba3a13c6f476e281e51681f0749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub::schedNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notify MachineSchedStrategy that ScheduleDAGMI has scheduled an instruction and updated scheduled/remaining flags in the DAG nodes.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>

</div>
</div>

### shouldTrackLaneMasks() {#a714e2456d7b9d278c7bf71fbf0a29a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub::shouldTrackLaneMasks ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if lanemasks should be tracked.</p>


<p>LaneMask tracking is necessary to reorder independent subregister defs for the same vreg. This has to be enabled in combination with <a href="#a376803a4832fd696122afd9f644e862b">shouldTrackPressure()</a>.</p>


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>

</div>
</div>

### shouldTrackPressure() {#a376803a4832fd696122afd9f644e862b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GCNIterativeScheduler.cpp}::SchedStrategyStub::shouldTrackPressure ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if pressure tracking is needed before building the DAG and initializing this strategy.</p>


<p>Called after initPolicy.</p>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
