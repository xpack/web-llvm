---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/registeroperands
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegisterOperands` Class

<p>List of registers defined and used by a machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegisterOperands { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e0a918c9705f23a1e5b66f68cc97e9">collect</a> (const MachineInstr &amp;MI, const TargetRegisterInfo &amp;TRI, const MachineRegisterInfo &amp;MRI, bool TrackLaneMasks, bool IgnoreDead)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the given instruction <span class="doxyComputerOutput">MI</span> and fill in the Uses, Defs and DeadDefs list based on the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> flags. <a href="#a74e0a918c9705f23a1e5b66f68cc97e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee6dacd4d30da478f3ad67f7fc27142">detectDeadDefs</a> (const MachineInstr &amp;MI, const LiveIntervals &amp;LIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> liveness information to find dead defs not marked with a dead flag and move them to the DeadDefs vector. <a href="#acee6dacd4d30da478f3ad67f7fc27142">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8affa4b2a934ff08aa04e63253a00126">adjustLaneLiveness</a> (const LiveIntervals &amp;LIS, const MachineRegisterInfo &amp;MRI, SlotIndex Pos, MachineInstr *AddFlagsMI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> liveness information to find out which uses/defs are partially undefined/dead and adjust the VRegMaskOrUnits accordingly. <a href="#a8affa4b2a934ff08aa04e63253a00126">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9cb57c0c3b81e758a2af8aca736842">Uses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of virtual registers and register units read by the instruction. <a href="#acf9cb57c0c3b81e758a2af8aca736842">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b640124aa4a430ee67d5409120e4deb">Defs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of virtual registers and register units defined by the instruction which are not dead. <a href="#a2b640124aa4a430ee67d5409120e4deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797ecc0909ee51516d50dd74698515b5">DeadDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of virtual registers and register units defined by the instruction but dead. <a href="#a797ecc0909ee51516d50dd74698515b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>List of registers defined and used by a machine instruction.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### adjustLaneLiveness() {#a8affa4b2a934ff08aa04e63253a00126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterOperands::adjustLaneLiveness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * AddFlagsMI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> liveness information to find out which uses/defs are partially undefined/dead and adjust the VRegMaskOrUnits accordingly.</p>


<p>If <span class="doxyComputerOutput">AddFlagsMI</span> is given then missing read-undef and dead flags will be added to the instruction.</p>


<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#a797ecc0909ee51516d50dd74698515b5">DeadDefs</a>, <a href="#a2b640124aa4a430ee67d5409120e4deb">Defs</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a11bad3e34d11ffb7b0412de6bbd294b3">llvm::SlotIndex::getDeadSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a9a34eb3ae4410e27d2af2562436e6734">getLiveLanesAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a05427132a2cb380432ed752b5f2dea6b">llvm::MachineInstr::setRegisterDefReadUndef</a> and <a href="#acf9cb57c0c3b81e758a2af8aca736842">Uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a99487c5b550882cba98d817d47cc3fc0">llvm::RegPressureTracker::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a2b8b6196a7458b6a84480f03e2f1355d">llvm::RegPressureTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ab0885ecf357ddad3594c9a2a5a9527f2">llvm::RegPressureTracker::bumpUpwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a20a8136fbbb55939ae03e734232ce942">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a3d32369a2a741e4657a7f65cfc32dcdf">llvm::GCNSchedStage::revertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a> and <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>.</p>

</div>
</div>

### collect() {#a74e0a918c9705f23a1e5b66f68cc97e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterOperands::collect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, bool TrackLaneMasks, bool IgnoreDead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the given instruction <span class="doxyComputerOutput">MI</span> and fill in the Uses, Defs and DeadDefs list based on the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> flags.</p>

<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regusageinfocollector-cpp/#a56152063c87e42d184c62fab1f3b0481">Collector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a99487c5b550882cba98d817d47cc3fc0">llvm::RegPressureTracker::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a2b8b6196a7458b6a84480f03e2f1355d">llvm::RegPressureTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ab0885ecf357ddad3594c9a2a5a9527f2">llvm::RegPressureTracker::bumpUpwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a20a8136fbbb55939ae03e734232ce942">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a3d32369a2a741e4657a7f65cfc32dcdf">llvm::GCNSchedStage::revertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

### detectDeadDefs() {#acee6dacd4d30da478f3ad67f7fc27142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterOperands::detectDeadDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> liveness information to find dead defs not marked with a dead flag and move them to the DeadDefs vector.</p>

<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#a797ecc0909ee51516d50dd74698515b5">DeadDefs</a>, <a href="#a2b640124aa4a430ee67d5409120e4deb">Defs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6f3043b29023d270fc4bc5062dff7cee">llvm::LiveIntervals::getInstructionIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a923798c288aeebf99a43eb7191492fe2">getLiveRange</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a149e4cda329019551bbb27fe3159eca6">llvm::LiveQueryResult::isDeadDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ab0885ecf357ddad3594c9a2a5a9527f2">llvm::RegPressureTracker::bumpUpwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a20a8136fbbb55939ae03e734232ce942">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a3d32369a2a741e4657a7f65cfc32dcdf">llvm::GCNSchedStage::revertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DeadDefs {#a797ecc0909ee51516d50dd74698515b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VRegMaskOrUnit, 8&gt; llvm::RegisterOperands::DeadDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of virtual registers and register units defined by the instruction but dead.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#a8affa4b2a934ff08aa04e63253a00126">adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a147da0e049b6b53046afe6825447eeaa">llvm::RegPressureTracker::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a2b8b6196a7458b6a84480f03e2f1355d">llvm::RegPressureTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ab0885ecf357ddad3594c9a2a5a9527f2">llvm::RegPressureTracker::bumpUpwardPressure</a>, <a href="#acee6dacd4d30da478f3ad67f7fc27142">detectDeadDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a126f33e8085746e4f69b4411b61102dc">llvm::RegPressureTracker::recede</a>.</p>

</div>
</div>

### Defs {#a2b640124aa4a430ee67d5409120e4deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VRegMaskOrUnit, 8&gt; llvm::RegisterOperands::Defs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of virtual registers and register units defined by the instruction which are not dead.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pressurediffs/#aa61bffce687c1adbbd0a96f292496128">llvm::PressureDiffs::addInstruction</a>, <a href="#a8affa4b2a934ff08aa04e63253a00126">adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a147da0e049b6b53046afe6825447eeaa">llvm::RegPressureTracker::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a2b8b6196a7458b6a84480f03e2f1355d">llvm::RegPressureTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ab0885ecf357ddad3594c9a2a5a9527f2">llvm::RegPressureTracker::bumpUpwardPressure</a>, <a href="#acee6dacd4d30da478f3ad67f7fc27142">detectDeadDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a126f33e8085746e4f69b4411b61102dc">llvm::RegPressureTracker::recede</a>.</p>

</div>
</div>

### Uses {#acf9cb57c0c3b81e758a2af8aca736842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VRegMaskOrUnit, 8&gt; llvm::RegisterOperands::Uses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of virtual registers and register units read by the instruction.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pressurediffs/#aa61bffce687c1adbbd0a96f292496128">llvm::PressureDiffs::addInstruction</a>, <a href="#a8affa4b2a934ff08aa04e63253a00126">adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a147da0e049b6b53046afe6825447eeaa">llvm::RegPressureTracker::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a2b8b6196a7458b6a84480f03e2f1355d">llvm::RegPressureTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ab0885ecf357ddad3594c9a2a5a9527f2">llvm::RegPressureTracker::bumpUpwardPressure</a> and <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a126f33e8085746e4f69b4411b61102dc">llvm::RegPressureTracker::recede</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
