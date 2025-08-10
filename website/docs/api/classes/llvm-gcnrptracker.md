---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnrptracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCNRPTracker` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GCNRPTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">Target/AMDGPU/GCNRegPressure.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker">GCNDownwardRPTracker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker">GCNUpwardRPTracker</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> &gt;</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e68c28afd52433cfe5de2743a051ad2">GCNRPTracker</a> (const LiveIntervals &amp;LIS_)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> decltype(<a href="#a0a547786ee2b51d087a8d47077a0a7de">LiveRegs</a>) &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f66c7653ea1f0ac33bfcf4006aef57">getLiveRegs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc2a1b43bcca0b856673c25a18d26f6f">getLastTrackedMI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5932338fae1a5ca6e58ddea0cabe7aba">clearMaxPressure</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e57238eeb231fb02499568087b29559">getPressure</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">decltype(<a href="#a0a547786ee2b51d087a8d47077a0a7de">LiveRegs</a>)</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d28441bc3b75c43f388ae3f9b4e2445">moveLiveRegs</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abef249629d52833a3c5c7e99799bae22">bumpDeadDefs</a> (ArrayRef&lt; VRegMaskOrUnit &gt; DeadDefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mostly copy/paste from <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">CodeGen/RegisterPressure.cpp</a>. <a href="#abef249629d52833a3c5c7e99799bae22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe36a4a2c040ff3e4a6040a900b0997">getLastUsedLanes</a> (Register RegUnit, SlotIndex Pos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mostly copy/paste from <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">CodeGen/RegisterPressure.cpp</a>. <a href="#abbe36a4a2c040ff3e4a6040a900b0997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6b5ab2740ab258cfa190c2a5acf8f5">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a547786ee2b51d087a8d47077a0a7de">LiveRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b82ba049ec10e292e11bc79bd56bfd">CurPressure</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76f3a5de6758b1c12c3bfaa80ee0879">MaxPressure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a9972194d5c04aaa9366c010e9dabe">LastTrackedMI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98cf5d6dde476f24e8221f34a918deb">MRI</a> = nullptr</td>
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


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LiveRegSet {#a48c9e1114fb048675cd2d7174dfcc999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCNRPTracker::LiveRegSet =  DenseMap&lt;unsigned, LaneBitmask&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### GCNRPTracker() {#a9e68c28afd52433cfe5de2743a051ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCNRPTracker::GCNRPTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS_)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="#ada6b5ab2740ab258cfa190c2a5acf8f5">LIS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a87e281cc5ec2888ede3051a3f5688e13">llvm::GCNDownwardRPTracker::GCNDownwardRPTracker</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a06083fa20560c5a1ca1354cfd7481701">llvm::GCNUpwardRPTracker::GCNUpwardRPTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearMaxPressure() {#a5932338fae1a5ca6e58ddea0cabe7aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNRPTracker::clearMaxPressure ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="#aa76f3a5de6758b1c12c3bfaa80ee0879">MaxPressure</a>.</p>

</div>
</div>

### getLastTrackedMI() {#acc2a1b43bcca0b856673c25a18d26f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * llvm::GCNRPTracker::getLastTrackedMI ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="#a17a9972194d5c04aaa9366c010e9dabe">LastTrackedMI</a>.</p>

</div>
</div>

### getLiveRegs() {#a14f66c7653ea1f0ac33bfcf4006aef57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const decltype(LiveRegs) &amp; llvm::GCNRPTracker::getLiveRegs ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="#a0a547786ee2b51d087a8d47077a0a7de">LiveRegs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### getPressure() {#a0e57238eeb231fb02499568087b29559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNRPTracker::getPressure ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="#a41b82ba049ec10e292e11bc79bd56bfd">CurPressure</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### moveLiveRegs() {#a2d28441bc3b75c43f388ae3f9b4e2445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(LiveRegs) llvm::GCNRPTracker::moveLiveRegs ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="#a0a547786ee2b51d087a8d47077a0a7de">LiveRegs</a>.</p>

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
<td class="doxyMemberName">void GCNRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> &amp; LiveRegs_)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="#a41b82ba049ec10e292e11bc79bd56bfd">CurPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ec9d4a470ecb7362abd00438e9b26">llvm::getRegPressure</a>, <a href="#a17a9972194d5c04aaa9366c010e9dabe">LastTrackedMI</a>, <a href="#a0a547786ee2b51d087a8d47077a0a7de">LiveRegs</a>, <a href="#aa76f3a5de6758b1c12c3bfaa80ee0879">MaxPressure</a> and <a href="#ad98cf5d6dde476f24e8221f34a918deb">MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### bumpDeadDefs() {#abef249629d52833a3c5c7e99799bae22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNRPTracker::bumpDeadDefs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> &gt; DeadDefs)</td>
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

<p>Mostly copy/paste from <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">CodeGen/RegisterPressure.cpp</a>.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>

</div>
</div>

### getLastUsedLanes() {#abbe36a4a2c040ff3e4a6040a900b0997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask GCNRPTracker::getLastUsedLanes (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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

<p>Mostly copy/paste from <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">CodeGen/RegisterPressure.cpp</a>.</p>

<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="#ada6b5ab2740ab258cfa190c2a5acf8f5">LIS</a> and <a href="#ad98cf5d6dde476f24e8221f34a918deb">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>.</p>

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
<td class="doxyMemberName">void GCNRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> * LiveRegsCopy, bool After)</td>
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



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="#a41b82ba049ec10e292e11bc79bd56bfd">CurPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62c28bacc64f2e1f9c9296f9314d6c75">llvm::getLiveRegsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb88334dcf6976de300fb1e3667430d7">llvm::getLiveRegsBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ec9d4a470ecb7362abd00438e9b26">llvm::getRegPressure</a>, <a href="#ada6b5ab2740ab258cfa190c2a5acf8f5">LIS</a>, <a href="#a0a547786ee2b51d087a8d47077a0a7de">LiveRegs</a>, <a href="#aa76f3a5de6758b1c12c3bfaa80ee0879">MaxPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ad98cf5d6dde476f24e8221f34a918deb">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a95cb78cfa1044889fefc65225f611e33">llvm::GCNDownwardRPTracker::reset</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a548b7703f8bbf29d5782c5bcfbe0cb5c">llvm::GCNUpwardRPTracker::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CurPressure {#a41b82ba049ec10e292e11bc79bd56bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNRPTracker::CurPressure</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#adda01c47a26407d9bf35e27efc904136">llvm::GCNDownwardRPTracker::advanceToNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="#a0e57238eeb231fb02499568087b29559">getPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#af4a0a6fb23f45e187a7295c5e3cc52bc">llvm::GCNUpwardRPTracker::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>, <a href="#ab5392b4136b981c481ff22a58958aced">reset</a>, <a href="#a4a0da90b9f153963f1b241afe67d4096">reset</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#aba3d281c877c68f0361b70beff7c0c23">llvm::GCNUpwardRPTracker::resetMaxPressure</a>.</p>

</div>
</div>

### LastTrackedMI {#a17a9972194d5c04aaa9366c010e9dabe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* llvm::GCNRPTracker::LastTrackedMI = nullptr</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#adda01c47a26407d9bf35e27efc904136">llvm::GCNDownwardRPTracker::advanceToNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="#acc2a1b43bcca0b856673c25a18d26f6f">getLastTrackedMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a95cb78cfa1044889fefc65225f611e33">llvm::GCNDownwardRPTracker::reset</a> and <a href="#a4a0da90b9f153963f1b241afe67d4096">reset</a>.</p>

</div>
</div>

### LIS {#ada6b5ab2740ab258cfa190c2a5acf8f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveIntervals&amp; llvm::GCNRPTracker::LIS</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="#a9e68c28afd52433cfe5de2743a051ad2">GCNRPTracker</a>, <a href="#abbe36a4a2c040ff3e4a6040a900b0997">getLastUsedLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#af4a0a6fb23f45e187a7295c5e3cc52bc">llvm::GCNUpwardRPTracker::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>, <a href="#ab5392b4136b981c481ff22a58958aced">reset</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#af3ef3f3b0d49ba56d10e3d4aeeb89021">llvm::GCNUpwardRPTracker::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#af698ff81af883153517bcf51d3cdebd2">llvm::GCNUpwardRPTracker::reset</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a548b7703f8bbf29d5782c5bcfbe0cb5c">llvm::GCNUpwardRPTracker::reset</a>.</p>

</div>
</div>

### LiveRegs {#a0a547786ee2b51d087a8d47077a0a7de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegSet llvm::GCNRPTracker::LiveRegs</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#adda01c47a26407d9bf35e27efc904136">llvm::GCNDownwardRPTracker::advanceToNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="#a14f66c7653ea1f0ac33bfcf4006aef57">getLiveRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#af4a0a6fb23f45e187a7295c5e3cc52bc">llvm::GCNUpwardRPTracker::isValid</a>, <a href="#a2d28441bc3b75c43f388ae3f9b4e2445">moveLiveRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>, <a href="#ab5392b4136b981c481ff22a58958aced">reset</a> and <a href="#a4a0da90b9f153963f1b241afe67d4096">reset</a>.</p>

</div>
</div>

### MaxPressure {#aa76f3a5de6758b1c12c3bfaa80ee0879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNRPTracker::MaxPressure</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#adda01c47a26407d9bf35e27efc904136">llvm::GCNDownwardRPTracker::advanceToNext</a>, <a href="#a5932338fae1a5ca6e58ddea0cabe7aba">clearMaxPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#aa8aa539949578dbd4e8abca2b4732cdd">llvm::GCNUpwardRPTracker::getMaxPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a5045b9f0b7a798f55c03b21d5eb5092b">llvm::GCNUpwardRPTracker::getMaxPressureAndReset</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a194c6037c4a80778db65e013496a0f76">llvm::GCNDownwardRPTracker::moveMaxPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>, <a href="#ab5392b4136b981c481ff22a58958aced">reset</a>, <a href="#a4a0da90b9f153963f1b241afe67d4096">reset</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#aba3d281c877c68f0361b70beff7c0c23">llvm::GCNUpwardRPTracker::resetMaxPressure</a>.</p>

</div>
</div>

### MRI {#ad98cf5d6dde476f24e8221f34a918deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* llvm::GCNRPTracker::MRI = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#adda01c47a26407d9bf35e27efc904136">llvm::GCNDownwardRPTracker::advanceToNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="#abbe36a4a2c040ff3e4a6040a900b0997">getLastUsedLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#af4a0a6fb23f45e187a7295c5e3cc52bc">llvm::GCNUpwardRPTracker::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a95cb78cfa1044889fefc65225f611e33">llvm::GCNDownwardRPTracker::reset</a>, <a href="#ab5392b4136b981c481ff22a58958aced">reset</a>, <a href="#a4a0da90b9f153963f1b241afe67d4096">reset</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a548b7703f8bbf29d5782c5bcfbe0cb5c">llvm::GCNUpwardRPTracker::reset</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
