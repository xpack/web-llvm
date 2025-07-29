---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/vliwmachinescheduler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `VLIWMachineScheduler.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">llvm/CodeGen/VLIWMachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">llvm/CodeGen/DFAPacketizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerclassinfo-h">llvm/CodeGen/RegisterClassInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">llvm/CodeGen/ScheduleDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulehazardrecognizer-h">llvm/CodeGen/ScheduleHazardRecognizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">llvm/CodeGen/TargetSchedule.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;iomanip&gt;
#include &lt;limits&gt;
#include &lt;memory&gt;
#include &lt;sstream&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cd4ba9b3cd1a7ff745d0238726dab6">isSingleUnscheduledPred</a> (SUnit *SU, SUnit *SU2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSingleUnscheduledPred - If SU2 is the only unscheduled predecessor of SU, return true (we may have duplicates) <a href="#a07cd4ba9b3cd1a7ff745d0238726dab6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85e209f5c4b8b0b4f804222439bc5ee">isSingleUnscheduledSucc</a> (SUnit *SU, SUnit *SU2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSingleUnscheduledSucc - If SU2 is the only unscheduled successor of SU, return true (we may have duplicates) <a href="#ad85e209f5c4b8b0b4f804222439bc5ee">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4721361efd8675d16257e7e8542bbe">IgnoreBBRegPressure</a>("ignore-bb-reg-pressure", cl::Hidden, cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2400ea611460a68f3cff3456cbb4ae">UseNewerCandidate</a>("use-newer-candidate", cl::Hidden, cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae505c7154e8681f73259461496fbc7fa">SchedDebugVerboseLevel</a>("misched-verbose-level", cl::Hidden, cl::init(1))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fda5b03c9cb06d554d7368694ee9a56">CheckEarlyAvail</a>("check-early-avail", cl::Hidden, cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a896b704353a0944b794b7793550ccf96">RPThreshold</a>("vliw-misched-reg-pressure", cl::Hidden, cl::init(0.75f), cl::desc("High register pressure threhold."))</td>
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
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### isSingleUnscheduledPred() {#a07cd4ba9b3cd1a7ff745d0238726dab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSingleUnscheduledPred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSingleUnscheduledPred - If SU2 is the only unscheduled predecessor of SU, return true (we may have duplicates)</p>

<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a94f78042fbba3ea4cd1004353daa46aa">llvm::SUnit::NumPredsLeft</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### isSingleUnscheduledSucc() {#ad85e209f5c4b8b0b4f804222439bc5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSingleUnscheduledSucc (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSingleUnscheduledSucc - If SU2 is the only unscheduled successor of SU, return true (we may have duplicates)</p>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a40c2dfbd170941dd4d20ee9b60c9d49d">llvm::SUnit::NumSuccsLeft</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CheckEarlyAvail {#a6fda5b03c9cb06d554d7368694ee9a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; CheckEarlyAvail("check-early-avail", cl::Hidden, cl::init(true))</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### IgnoreBBRegPressure {#a7b4721361efd8675d16257e7e8542bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; IgnoreBBRegPressure("ignore-bb-reg-pressure", cl::Hidden, cl::init(false))</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### RPThreshold {#a896b704353a0944b794b7793550ccf96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; RPThreshold("vliw-misched-reg-pressure", cl::Hidden, cl::init(0.75f), cl::desc("High register pressure threhold."))</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aef655ef720977fd68fbd4bf24b5ab3d8">llvm::ConvergingVLIWScheduler::initialize</a>.</p>

</div>
</div>

### SchedDebugVerboseLevel {#ae505c7154e8681f73259461496fbc7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SchedDebugVerboseLevel("misched-verbose-level", cl::Hidden, cl::init(1))</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>.</p>

</div>
</div>

### UseNewerCandidate {#a8d2400ea611460a68f3cff3456cbb4ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseNewerCandidate("use-newer-candidate", cl::Hidden, cl::init(true))</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>.</p>

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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
