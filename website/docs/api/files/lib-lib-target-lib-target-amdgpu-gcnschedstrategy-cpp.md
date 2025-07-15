---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `GCNSchedStrategy.cpp` File Reference

<p>This contains a <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for maximizing wave occupancy on GCN hardware. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-h">AMDGPUIGroupLP.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerclassinfo-h">llvm/CodeGen/RegisterClassInfo.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/earlierissuingcycle">EarlierIssuingCycle</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba393b0035b052e3477fc32a72643750">canUsePressureDiffs</a> (const SUnit &amp;SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks whether <span class="doxyComputerOutput">SU</span> can use the cached DAG pressure diffs to compute the current register pressure. <a href="#aba393b0035b052e3477fc32a72643750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a> (bool AtTop, const RegPressureTracker &amp;RPTracker, SUnit *SU, std::vector&lt; unsigned &gt; &amp;Pressure, std::vector&lt; unsigned &gt; &amp;MaxPressure, GCNDownwardRPTracker &amp;DownwardTracker, GCNUpwardRPTracker &amp;UpwardTracker, ScheduleDAGMI *DAG, const SIRegisterInfo *SRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eadfed0a19cd148a823630f4d480939">isIGLPMutationOnly</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a587fb6ab73f4bc9b53f42c4f67a498">getLastMIForRegion</a> (MachineBasicBlock::iterator RegionBegin, MachineBasicBlock::iterator RegionEnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76923341fddafb3d1ed56aef0569ee68">printScheduleModel</a> (std::set&lt; std::pair&lt; MachineInstr *, unsigned &gt;, EarlierIssuingCycle &gt; &amp;ReadyCycles)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9caea6f361f31119324b93999ad1028c">hasIGLPInstrs</a> (ScheduleDAGInstrs *DAG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae238df4eeb83d36a53d78f3f3e373d">DisableUnclusterHighRP</a>("amdgpu-disable-unclustered-high-rp-reschedule", cl::Hidden, cl::desc("Disable unclustered high register pressure " "reduction scheduling stage."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f0e3f43e034a5fa4dbeb6b1d4b5855">DisableClusteredLowOccupancy</a>("amdgpu-disable-clustered-low-occupancy-reschedule", cl::Hidden, cl::desc("Disable clustered low occupancy " "rescheduling for ILP scheduling stage."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af808ad46889f1cea7143a9e6a53c0872">ScheduleMetricBias</a>("amdgpu-schedule-metric-bias", cl::Hidden, cl::desc("Sets the bias which adds weight to occupancy vs latency. Set it to " "100 to chase the occupancy only."), cl::init(10))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598d5d447ded5b784ea021c159a58615">RelaxedOcc</a>("amdgpu-schedule-relaxed-occupancy", cl::Hidden, cl::desc("Relax occupancy targets for kernels which are memory " "bound (amdgpu-membound-threshold), or " "Wave Limited (amdgpu-limit-wave-threshold)."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00473ec6bae66ae8a3e6a0fe74ee1aaa">GCNTrackers</a>("amdgpu-use-amdgpu-trackers", cl::Hidden, cl::desc("Use the AMDGPU specific RPTrackers during scheduling"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"machine-scheduler"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generally, the reason for having multiple scheduling stages is to account for the kernel-wide effect of register usage on occupancy. <a href="#ad78e062f62e0d6e453941fb4ca843e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This contains a <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for maximizing wave occupancy on GCN hardware.</p>


<p>This pass will apply multiple scheduling stages to the same function. Regions are first recorded in <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive/#a3c1701146006f98eaa57e38932060160">GCNScheduleDAGMILive::schedule</a>. The actual entry point for the scheduling of those regions is GCNScheduleDAGMILive::runSchedStages.</p>


<div class="doxySectionDef">

## Functions

### canUsePressureDiffs() {#aba393b0035b052e3477fc32a72643750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canUsePressureDiffs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU)</td>
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

<p>Checks whether <span class="doxyComputerOutput">SU</span> can use the cached DAG pressure diffs to compute the current register pressure.</p>


<p>This works for the common case, but it has a few exceptions that have been observed through trial and error:</p>


<ul class="doxyList ">
<li>Explicit physical register operands</li>
<li>Subregister definitions</li>
</ul>

<p>In both of those cases, <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> doesn't represent the actual pressure, and querying <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> through the <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> is needed to get an accurate value.</p>


<p>We should eventually only use <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> for maximum performance, but this already allows 80% of SUs to take the fast path without changing scheduling at all. Further changes would either change scheduling, or require a lot more logic to recover an accurate pressure estimate from the <a href="/web-llvm/docs/api/classes/llvm/pressurediffs">PressureDiffs</a>.</p>


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a274909b1f31ad2d3d3379de55467d377">llvm::SUnit::isInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>.</p>

</div>
</div>

### getLastMIForRegion() {#a3a587fb6ab73f4bc9b53f42c4f67a498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * getLastMIForRegion (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> RegionBegin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> RegionEnd)</td>
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



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9256279285c60fce1b2eb1b928599461">llvm::skipDebugInstructionsBackward</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regionpressuremap/#a07ce1d74dca63e18274738509186df44">llvm::RegionPressureMap::buildLiveRegMap</a>.</p>

</div>
</div>

### getRegisterPressures() {#ad8dc903ae7dd7695e082f3d3fb80be92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getRegisterPressures (bool AtTop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &amp; Pressure, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &amp; MaxPressure, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker">GCNDownwardRPTracker</a> &amp; DownwardTracker, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker">GCNUpwardRPTracker</a> &amp; UpwardTracker, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> * SRI)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="#a00473ec6bae66ae8a3e6a0fe74ee1aaa">GCNTrackers</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#ab822633324180bbee7b05a0d2518c563">llvm::GCNRegPressure::getAGPRNum</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#ab44e40399c83c9b34c0e33c4870768fd">llvm::GCNRegPressure::getArchVGPRNum</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ac1bfd03ca8fa96ab674c7f7b620dd8a6">llvm::RegPressureTracker::getDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a0e57238eeb231fb02499568087b29559">llvm::GCNRPTracker::getPressure</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#abd577f5d55cd0fde5973c8c5a1cdb816">llvm::GCNRegPressure::getSGPRNum</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ad552b6e557acce957b3bd5a1960a53dd">llvm::RegPressureTracker::getUpwardPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>.</p>

</div>
</div>

### hasIGLPInstrs() {#a9caea6f361f31119324b93999ad1028c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasIGLPInstrs (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG)</td>
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



<p>Definition at line 1907 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a4eadfed0a19cd148a823630f4d480939">isIGLPMutationOnly</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#ab0fcaad7b05dc36681c5abeabca7991c">llvm::GCNPostScheduleDAGMILive::schedule</a>.</p>

</div>
</div>

### isIGLPMutationOnly() {#a4eadfed0a19cd148a823630f4d480939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIGLPMutationOnly (unsigned Opcode)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Referenced by <a href="#a9caea6f361f31119324b93999ad1028c">hasIGLPInstrs</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a02add63fe5ce109718dea7e87b1db3c1">llvm::GCNSchedStage::initGCNRegion</a>.</p>

</div>
</div>

### printScheduleModel() {#a76923341fddafb3d1ed56aef0569ee68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printScheduleModel (std::set&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt;, <a href="/web-llvm/docs/api/structs/earlierissuingcycle">EarlierIssuingCycle</a> &gt; &amp; ReadyCycles)</td>
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



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a35ad2560fecc16262b15e21c9375cf3d">llvm::GCNSchedStage::getScheduleMetrics</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a741c05e011507c0982568e68fa599a8c">llvm::GCNSchedStage::getScheduleMetrics</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableClusteredLowOccupancy {#a17f0e3f43e034a5fa4dbeb6b1d4b5855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableClusteredLowOccupancy("amdgpu-disable-clustered-low-occupancy-reschedule", cl::Hidden, cl::desc("Disable clustered low occupancy " "rescheduling for ILP scheduling stage."), cl::init(false))</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a0bdb7b684aa1f51dc79bf9b7f9bf079f">llvm::ClusteredLowOccStage::initGCNSchedStage</a>.</p>

</div>
</div>

### DisableUnclusterHighRP {#a6ae238df4eeb83d36a53d78f3f3e373d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableUnclusterHighRP("amdgpu-disable-unclustered-high-rp-reschedule", cl::Hidden, cl::desc("Disable unclustered high register pressure " "reduction scheduling stage."), cl::init(false))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2468e5cc789e17c8e2fb2b6102404e8f">llvm::UnclusteredHighRPStage::initGCNSchedStage</a>.</p>

</div>
</div>

### GCNTrackers {#a00473ec6bae66ae8a3e6a0fe74ee1aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; GCNTrackers("amdgpu-use-amdgpu-trackers", cl::Hidden, cl::desc("Use the AMDGPU specific RPTrackers during scheduling"), cl::init(false))</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnmaxoccupancyschedstrategy/#a1aaa47dd65d2e5e66930f7c3bdb2a6bd">llvm::GCNMaxOccupancySchedStrategy::GCNMaxOccupancySchedStrategy</a>, <a href="#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a886677d13d24c974e4cb3086df524e7b">llvm::GCNSchedStrategy::schedNode</a>.</p>

</div>
</div>

### RelaxedOcc {#a598d5d447ded5b784ea021c159a58615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RelaxedOcc("amdgpu-schedule-relaxed-occupancy", cl::Hidden, cl::desc("Relax occupancy targets for kernels which are memory " "bound (amdgpu-membound-threshold), or " "Wave Limited (amdgpu-limit-wave-threshold)."), cl::init(false))</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive/#a586d595322e6cb11cc1663b937d9aca7">llvm::GCNScheduleDAGMILive::GCNScheduleDAGMILive</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ab57c0b13438062a884d3e620300fbc03">llvm::GCNSchedStrategy::initialize</a>.</p>

</div>
</div>

### ScheduleMetricBias {#af808ad46889f1cea7143a9e6a53c0872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ScheduleMetricBias("amdgpu-schedule-metric-bias", cl::Hidden, cl::desc( "Sets the bias which adds weight to occupancy vs latency. Set it to " "100 to chase the occupancy only."), cl::init(10))</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"machine-scheduler"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generally, the reason for having multiple scheduling stages is to account for the kernel-wide effect of register usage on occupancy.</p>


<p>Usually, only a few scheduling regions will have register pressure high enough to limit occupancy for the kernel, so constraints can be relaxed to improve ILP in other regions.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
