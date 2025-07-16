---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/liveintervals/hmeditor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HMEditor` Class Reference

<p>Toolkit used by handleMove to trim or extend live intervals. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LiveIntervals::HMEditor { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7506c455b7a216d91ccb3b6dbb977e94">HMEditor</a> (LiveIntervals &amp;LIS, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI, SlotIndex OldIdx, SlotIndex NewIdx, bool UpdateFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfcc50b70f6178f16b549d1779cd03db">getRegUnitLI</a> (unsigned Unit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa060d1bdca0620ff13d49456dccf9303">updateAllRanges</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update all live ranges touched by MI, assuming a move from OldIdx to NewIdx. <a href="#aa060d1bdca0620ff13d49456dccf9303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7c095e08536ee51ac0b41836d813d3">updateRange</a> (LiveRange &amp;LR, VirtRegOrUnit VRegOrUnit, LaneBitmask LaneMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update a single live range, assuming an instruction has been moved from OldIdx to NewIdx. <a href="#a4b7c095e08536ee51ac0b41836d813d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf89243a2de25e1febd8bd9b673769af">handleMoveDown</a> (LiveRange &amp;LR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update LR to reflect an instruction has been moved downwards from OldIdx to NewIdx (OldIdx &lt; NewIdx). <a href="#adf89243a2de25e1febd8bd9b673769af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4002597d5f3ba77ac5f9bbb2e78cb72">handleMoveUp</a> (LiveRange &amp;LR, VirtRegOrUnit VRegOrUnit, LaneBitmask LaneMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update LR to reflect an instruction has been moved upwards from OldIdx to NewIdx (NewIdx &lt; OldIdx). <a href="#ae4002597d5f3ba77ac5f9bbb2e78cb72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4612997cd517714006f860e066f22a9">updateRegMaskSlots</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e45bd4ae2cc5ce92bec637c8e95acb0">findLastUseBefore</a> (SlotIndex Before, VirtRegOrUnit VRegOrUnit, LaneBitmask LaneMask)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68feb74c46211524be0c698ed60d1e59">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e532ce16a8bc38e25c5a1ab932edc55">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23eca0bc22b88df015859fd6144879f9">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a423bd1b7a2bea0842e64460bf99c4">OldIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa27de1dd6d20ca521a4e64a0bd17e3">NewIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91c6a4449cdfb8fac74428070968275">Updated</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ae5f16520abf7e60118359c9f4c2e9">UpdateFlags</a></td>
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

<p>Toolkit used by handleMove to trim or extend live intervals.</p>

<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HMEditor() {#a7506c455b7a216d91ccb3b6dbb977e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervals::HMEditor::HMEditor (<a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> OldIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> NewIdx, bool UpdateFlags)</td>
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



<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRegUnitLI() {#abfcc50b70f6178f16b549d1779cd03db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange * llvm::LiveIntervals::HMEditor::getRegUnitLI (unsigned Unit)</td>
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



<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>Referenced by <a href="#aa060d1bdca0620ff13d49456dccf9303">llvm::LiveIntervals::HMEditor::updateAllRanges</a>.</p>

</div>
</div>

### updateAllRanges() {#aa060d1bdca0620ff13d49456dccf9303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::HMEditor::updateAllRanges (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Update all live ranges touched by MI, assuming a move from OldIdx to NewIdx.</p>

<p>Definition at line 1054 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#aa1555194b9f176612b04fbd38f49b40d">llvm::LiveRange::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a5c2526062a291ca7d78fe98bbf66edb7">llvm::LiveRange::covers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="#abfcc50b70f6178f16b549d1779cd03db">llvm::LiveIntervals::HMEditor::getRegUnitLI</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a29d12c5a65b3940bfac7b5aa1121ac70">llvm::LiveIntervals::handleMove</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa1a6fbdf0a3311c7b9602dd67e46fef9">llvm::LiveIntervals::handleMoveIntoNewBundle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findLastUseBefore() {#a8e45bd4ae2cc5ce92bec637c8e95acb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::HMEditor::findLastUseBefore (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Before, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
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



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### handleMoveDown() {#adf89243a2de25e1febd8bd9b673769af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::HMEditor::handleMoveDown (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR)</td>
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

<p>Update LR to reflect an instruction has been moved downwards from OldIdx to NewIdx (OldIdx &lt; NewIdx).</p>

<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### handleMoveUp() {#ae4002597d5f3ba77ac5f9bbb2e78cb72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::HMEditor::handleMoveUp (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
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

<p>Update LR to reflect an instruction has been moved upwards from OldIdx to NewIdx (NewIdx &lt; OldIdx).</p>

<p>Definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### updateRange() {#a4b7c095e08536ee51ac0b41836d813d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::HMEditor::updateRange (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
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

<p>Update a single live range, assuming an instruction has been moved from OldIdx to NewIdx.</p>

<p>Definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### updateRegMaskSlots() {#ab4612997cd517714006f860e066f22a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::HMEditor::updateRegMaskSlots ()</td>
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



<p>Definition at line 1488 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LIS {#a68feb74c46211524be0c698ed60d1e59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; llvm::LiveIntervals::HMEditor::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### MRI {#a3e532ce16a8bc38e25c5a1ab932edc55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo&amp; llvm::LiveIntervals::HMEditor::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### NewIdx {#a4fa27de1dd6d20ca521a4e64a0bd17e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::HMEditor::NewIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### OldIdx {#a16a423bd1b7a2bea0842e64460bf99c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::HMEditor::OldIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### TRI {#a23eca0bc22b88df015859fd6144879f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::LiveIntervals::HMEditor::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### Updated {#ac91c6a4449cdfb8fac74428070968275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;LiveRange*, 8&gt; llvm::LiveIntervals::HMEditor::Updated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### UpdateFlags {#ae2ae5f16520abf7e60118359c9f4c2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervals::HMEditor::UpdateFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1033 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
