---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/regpressuredelta
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegPressureDelta` Struct Reference

<p>Store the effects of a change in pressure on things that MI scheduler cares about. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegPressureDelta { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68dee6e705f814facf82816375bfac17">RegPressureDelta</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703cfab33f19158c32559b2c08695d4a">operator==</a> (const RegPressureDelta &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad199a5b91b10cf8fa9b7991ce507cbc1">operator!=</a> (const RegPressureDelta &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d20a585ffc9e9dd7bff5aa8ba38443">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9c3b403c6d4af795dd8be1c9612240">Excess</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277da5755f2b30ebcebdba51d0de1acf">CriticalMax</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a589e1a7e9a8a095d8d01ff8ba32b3d14">CurrentMax</a></td>
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

<p>Store the effects of a change in pressure on things that MI scheduler cares about.</p>


<p>Excess records the value of the largest difference in register units beyond the target's pressure limits across the affected pressure sets, where largest is defined as the absolute value of the difference. Negative ExcessUnits indicates a reduction in pressure that had already exceeded the target's limits.</p>


<p>CriticalMax records the largest increase in the tracker's max pressure that exceeds the critical limit for some pressure set determined by the client.</p>


<p>CurrentMax records the largest increase in the tracker's max pressure that exceeds the current limit for some pressure set determined by the client.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegPressureDelta() {#a68dee6e705f814facf82816375bfac17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegPressureDelta::RegPressureDelta ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#ad199a5b91b10cf8fa9b7991ce507cbc1">operator!=</a> and <a href="#a703cfab33f19158c32559b2c08695d4a">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ad199a5b91b10cf8fa9b7991ce507cbc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegPressureDelta::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; RHS)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="#a703cfab33f19158c32559b2c08695d4a">operator==</a>, <a href="#a68dee6e705f814facf82816375bfac17">RegPressureDelta</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a703cfab33f19158c32559b2c08695d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegPressureDelta::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; RHS)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="#a277da5755f2b30ebcebdba51d0de1acf">CriticalMax</a>, <a href="#a589e1a7e9a8a095d8d01ff8ba32b3d14">CurrentMax</a>, <a href="#aff9c3b403c6d4af795dd8be1c9612240">Excess</a>, <a href="#a68dee6e705f814facf82816375bfac17">RegPressureDelta</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#ad199a5b91b10cf8fa9b7991ce507cbc1">operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a85d20a585ffc9e9dd7bff5aa8ba38443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureDelta::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#a277da5755f2b30ebcebdba51d0de1acf">CriticalMax</a>, <a href="#a589e1a7e9a8a095d8d01ff8ba32b3d14">CurrentMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#aff9c3b403c6d4af795dd8be1c9612240">Excess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CriticalMax {#a277da5755f2b30ebcebdba51d0de1acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PressureChange llvm::RegPressureDelta::CriticalMax</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a822aec28298cd2dc8f346d4753a4154b">computeMaxPressureDelta</a>, <a href="#a85d20a585ffc9e9dd7bff5aa8ba38443">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a972fa38378a3d49a9bb48ca584621438">llvm::RegPressureTracker::getMaxDownwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a41a3118fb6bd46e397256b3c9794b61c">llvm::RegPressureTracker::getMaxUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#af7a0688faef62284ad684e70f342b3da">llvm::RegPressureTracker::getUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>, <a href="#a703cfab33f19158c32559b2c08695d4a">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### CurrentMax {#a589e1a7e9a8a095d8d01ff8ba32b3d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PressureChange llvm::RegPressureDelta::CurrentMax</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a822aec28298cd2dc8f346d4753a4154b">computeMaxPressureDelta</a>, <a href="#a85d20a585ffc9e9dd7bff5aa8ba38443">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a972fa38378a3d49a9bb48ca584621438">llvm::RegPressureTracker::getMaxDownwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a41a3118fb6bd46e397256b3c9794b61c">llvm::RegPressureTracker::getMaxUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#af7a0688faef62284ad684e70f342b3da">llvm::RegPressureTracker::getUpwardPressureDelta</a>, <a href="#a703cfab33f19158c32559b2c08695d4a">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### Excess {#aff9c3b403c6d4af795dd8be1c9612240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PressureChange llvm::RegPressureDelta::Excess</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a013f10c0323064cf28c1aed647c0b478">computeExcessPressureDelta</a>, <a href="#a85d20a585ffc9e9dd7bff5aa8ba38443">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a41a3118fb6bd46e397256b3c9794b61c">llvm::RegPressureTracker::getMaxUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#af7a0688faef62284ad684e70f342b3da">llvm::RegPressureTracker::getUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="#a703cfab33f19158c32559b2c08695d4a">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
