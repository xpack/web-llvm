---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnupwardrptracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCNUpwardRPTracker` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GCNUpwardRPTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">Target/AMDGPU/GCNRegPressure.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnrptracker">GCNRPTracker</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06083fa20560c5a1ca1354cfd7481701">GCNUpwardRPTracker</a> (const LiveIntervals &amp;LIS_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548b7703f8bbf29d5782c5bcfbe0cb5c">reset</a> (const MachineRegisterInfo &amp;MRI, SlotIndex SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset tracker at the specified slot index <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span>. <a href="#a548b7703f8bbf29d5782c5bcfbe0cb5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ef3f3b0d49ba56d10e3d4aeeb89021">reset</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset tracker to the end of the <span class="doxyComputerOutput">MBB</span>. <a href="#af3ef3f3b0d49ba56d10e3d4aeeb89021">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af698ff81af883153517bcf51d3cdebd2">reset</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset tracker to the point just after <span class="doxyComputerOutput">MI</span> (in program order). <a href="#af698ff81af883153517bcf51d3cdebd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7838950673480bf3ece5ddf4f4fe0132">recede</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move to the state of RP just before the <span class="doxyComputerOutput">MI</span> . <a href="#a7838950673480bf3ece5ddf4f4fe0132">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a0a6fb23f45e187a7295c5e3cc52bc">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">returns</span> whether the tracker's state after receding MI corresponds to reported by LIS. <a href="#af4a0a6fb23f45e187a7295c5e3cc52bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8aa539949578dbd4e8abca2b4732cdd">getMaxPressure</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba3d281c877c68f0361b70beff7c0c23">resetMaxPressure</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5045b9f0b7a798f55c03b21d5eb5092b">getMaxPressureAndReset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5392b4136b981c481ff22a58958aced">reset</a> (const MachineInstr &amp;MI, const LiveRegSet *LiveRegsCopy, bool After)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0da90b9f153963f1b241afe67d4096">reset</a> (const MachineRegisterInfo &amp;MRI_, const LiveRegSet &amp;LiveRegs_)</td>
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


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNUpwardRPTracker() {#a06083fa20560c5a1ca1354cfd7481701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCNUpwardRPTracker::GCNUpwardRPTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS_)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a9e68c28afd52433cfe5de2743a051ad2">llvm::GCNRPTracker::GCNRPTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMaxPressure() {#aa8aa539949578dbd4e8abca2b4732cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNRegPressure &amp; llvm::GCNUpwardRPTracker::getMaxPressure ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#aa76f3a5de6758b1c12c3bfaa80ee0879">llvm::GCNRPTracker::MaxPressure</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### getMaxPressureAndReset() {#a5045b9f0b7a798f55c03b21d5eb5092b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNUpwardRPTracker::getMaxPressureAndReset ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#aa76f3a5de6758b1c12c3bfaa80ee0879">llvm::GCNRPTracker::MaxPressure</a> and <a href="#aba3d281c877c68f0361b70beff7c0c23">resetMaxPressure</a>.</p>

</div>
</div>

### isValid() {#af4a0a6fb23f45e187a7295c5e3cc52bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNUpwardRPTracker::isValid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">returns</span> whether the tracker's state after receding MI corresponds to reported by LIS.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a41b82ba049ec10e292e11bc79bd56bfd">llvm::GCNRPTracker::CurPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ab92d2e2752422a6a0995188d64b77">llvm::getLiveRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ec9d4a470ecb7362abd00438e9b26">llvm::getRegPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f0d66fa63bebb53ddd51f1cc4def0f8">llvm::isEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ada6b5ab2740ab258cfa190c2a5acf8f5">llvm::GCNRPTracker::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a0a547786ee2b51d087a8d47077a0a7de">llvm::GCNRPTracker::LiveRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ad98cf5d6dde476f24e8221f34a918deb">llvm::GCNRPTracker::MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af2b74085541381aa878e3cbad0cb7b71">llvm::reportMismatch</a>.</p>

</div>
</div>

### recede() {#a7838950673480bf3ece5ddf4f4fe0132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNUpwardRPTracker::recede (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move to the state of RP just before the <span class="doxyComputerOutput">MI</span> .</p>


<p>If <span class="doxyComputerOutput">UseInternalIterator</span> is set, also update the internal iterators. Setting <span class="doxyComputerOutput">UseInternalIterator</span> to false allows for an externally managed iterator / program order.</p>


<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a08414c5d48fed44354cf4c4ea6ca464c">collectVirtualRegUses</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a41b82ba049ec10e292e11bc79bd56bfd">llvm::GCNRPTracker::CurPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a827d52327fbe1bd7bf22242e7c18847d">getDefRegMask</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ec9d4a470ecb7362abd00438e9b26">llvm::getRegPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#a8a4c16c737c90f7de638e1ee724d4785">llvm::GCNRegPressure::inc</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a17a9972194d5c04aaa9366c010e9dabe">llvm::GCNRPTracker::LastTrackedMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ada6b5ab2740ab258cfa190c2a5acf8f5">llvm::GCNRPTracker::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a0a547786ee2b51d087a8d47077a0a7de">llvm::GCNRPTracker::LiveRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#aa76f3a5de6758b1c12c3bfaa80ee0879">llvm::GCNRPTracker::MaxPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ad98cf5d6dde476f24e8221f34a918deb">llvm::GCNRPTracker::MRI</a> and <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### reset() {#a548b7703f8bbf29d5782c5bcfbe0cb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNUpwardRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> SI)</td>
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

<p>reset tracker at the specified slot index <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span>.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a62ab92d2e2752422a6a0995188d64b77">llvm::getLiveRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ada6b5ab2740ab258cfa190c2a5acf8f5">llvm::GCNRPTracker::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ad98cf5d6dde476f24e8221f34a918deb">llvm::GCNRPTracker::MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ab5392b4136b981c481ff22a58958aced">llvm::GCNRPTracker::reset</a>.</p>


<p>Referenced by <a href="#af3ef3f3b0d49ba56d10e3d4aeeb89021">reset</a>, <a href="#af698ff81af883153517bcf51d3cdebd2">reset</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### reset() {#af3ef3f3b0d49ba56d10e3d4aeeb89021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNUpwardRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>reset tracker to the end of the <span class="doxyComputerOutput">MBB</span>.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ada6b5ab2740ab258cfa190c2a5acf8f5">llvm::GCNRPTracker::LIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a548b7703f8bbf29d5782c5bcfbe0cb5c">reset</a>.</p>

</div>
</div>

### reset() {#af698ff81af883153517bcf51d3cdebd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNUpwardRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>reset tracker to the point just after <span class="doxyComputerOutput">MI</span> (in program order).</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ada6b5ab2740ab258cfa190c2a5acf8f5">llvm::GCNRPTracker::LIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a548b7703f8bbf29d5782c5bcfbe0cb5c">reset</a>.</p>

</div>
</div>

### reset() {#ab5392b4136b981c481ff22a58958aced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> * LiveRegsCopy, bool After)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#a6b5acc4933b30383d7b31729281dacc3">llvm::GCNRegPressure::getVGPRNum</a>.</p>

</div>
</div>

### reset() {#a4a0da90b9f153963f1b241afe67d4096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> &amp; LiveRegs_)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>

</div>
</div>

### resetMaxPressure() {#aba3d281c877c68f0361b70beff7c0c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNUpwardRPTracker::resetMaxPressure ()</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a41b82ba049ec10e292e11bc79bd56bfd">llvm::GCNRPTracker::CurPressure</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#aa76f3a5de6758b1c12c3bfaa80ee0879">llvm::GCNRPTracker::MaxPressure</a>.</p>


<p>Referenced by <a href="#a5045b9f0b7a798f55c03b21d5eb5092b">getMaxPressureAndReset</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
