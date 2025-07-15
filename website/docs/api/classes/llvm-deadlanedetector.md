---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/deadlanedetector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DeadLaneDetector` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DeadLaneDetector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">llvm/CodeGen/DetectDeadLanes.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ad46a86e98bacc679085d4dde19c09">DeadLaneDetector</a> (const MachineRegisterInfo *MRI, const TargetRegisterInfo *TRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a88b4246b710c6aa48b42fe8c912fd3">computeSubRegisterLaneBitInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the <span class="doxyComputerOutput">DefinedLanes</span> and the <span class="doxyComputerOutput">UsedLanes</span> for all virtual registers. <a href="#a1a88b4246b710c6aa48b42fe8c912fd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/deadlanedetector/vreginfo">VRegInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad455392b3cc88b5fd25c9169bac734cc">getVRegInfo</a> (unsigned RegIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec138de3b8b6deaf4b31745f3019339">isDefinedByCopy</a> (unsigned RegIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa77e90c3a572d0523249dc6b27e6f10a">transferDefinedLanes</a> (const MachineOperand &amp;Def, unsigned OpNum, LaneBitmask DefinedLanes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a mask <span class="doxyComputerOutput">DefinedLanes</span> of lanes defined at operand <span class="doxyComputerOutput">OpNum</span> of COPY-like instruction, determine which lanes are defined at the output operand <span class="doxyComputerOutput">Def</span>. <a href="#aa77e90c3a572d0523249dc6b27e6f10a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0507a9e0fb3ad8b5cbe21a6f19c8714c">transferUsedLanes</a> (const MachineInstr &amp;MI, LaneBitmask UsedLanes, const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a mask <span class="doxyComputerOutput">UsedLanes</span> used from the output of instruction <span class="doxyComputerOutput">MI</span> determine which lanes are used from operand <span class="doxyComputerOutput">MO</span> of this instruction. <a href="#a0507a9e0fb3ad8b5cbe21a6f19c8714c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c7997dcb59120654aae6e591d6b6e9">addUsedLanesOnOperand</a> (const MachineOperand &amp;MO, LaneBitmask UsedLanes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add used lane bits on the register used by operand <span class="doxyComputerOutput">MO</span>. <a href="#a84c7997dcb59120654aae6e591d6b6e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3706e4bf2a5257c5965bb0d386934d8d">transferUsedLanesStep</a> (const MachineInstr &amp;MI, LaneBitmask UsedLanes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a bitmask <span class="doxyComputerOutput">UsedLanes</span> for the used lanes on a def output of a COPY-like instruction determine the lanes used on the use operands and call addUsedLanesOnOperand() for them. <a href="#a3706e4bf2a5257c5965bb0d386934d8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56b1da500a44e5704f6ace3ac8d7950">transferDefinedLanesStep</a> (const MachineOperand &amp;Use, LaneBitmask DefinedLanes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a use regiser operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> and a mask of defined lanes, check if the operand belongs to a <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#af79ff100b421c4477f89f3ab21a862de">lowersToCopies()</a> instruction, transfer the mask to the def and put the instruction into the worklist. <a href="#af56b1da500a44e5704f6ace3ac8d7950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683cd8151047d30fc9f5568ea39080d7">determineInitialDefinedLanes</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e971e91f58e554bd5a14b65fa2b96e">determineInitialUsedLanes</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461a46f7ba5a679e9d211367f0029934">PutInWorklist</a> (unsigned RegIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b15b372569132080a18f8245bd20f7b">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa743a63d11ea2710580bae0884055c20">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/deadlanedetector/vreginfo">VRegInfo</a>[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fb441ed91571816f68eea455d8e958">VRegInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443650f1f5ee4c198772e692bfc2dc46">Worklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Worklist containing virtreg indexes. <a href="#a443650f1f5ee4c198772e692bfc2dc46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11997276354619216b1dd53f9ca2e1c6">WorklistMembers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a72197168da51a34a3d49df165136b">DefinedByCopy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This bitvector is set for each vreg index where the vreg is defined by an instruction where <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#af79ff100b421c4477f89f3ab21a862de">lowersToCopies()</a>==true. <a href="#a24a72197168da51a34a3d49df165136b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DeadLaneDetector() {#a56ad46a86e98bacc679085d4dde19c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeadLaneDetector::DeadLaneDetector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeSubRegisterLaneBitInfo() {#a1a88b4246b710c6aa48b42fe8c912fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadLaneDetector::computeSubRegisterLaneBitInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the <span class="doxyComputerOutput">DefinedLanes</span> and the <span class="doxyComputerOutput">UsedLanes</span> for all virtual registers.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/deadlanedetector/vreginfo/#ab5cc16c5db0dad4323f6fe4f60d7eb86">llvm::DeadLaneDetector::VRegInfo::DefinedLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-detectdeadlanes-cpp-/detectdeadlanes/#ab75c3fd209b61d1137b0b8d70aa25a75">anonymous{DetectDeadLanes.cpp}::DetectDeadLanes::runOnMachineFunction</a>.</p>

</div>
</div>

### getVRegInfo() {#ad455392b3cc88b5fd25c9169bac734cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VRegInfo &amp; llvm::DeadLaneDetector::getVRegInfo (unsigned RegIdx)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### isDefinedByCopy() {#a9ec138de3b8b6deaf4b31745f3019339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DeadLaneDetector::isDefinedByCopy (unsigned RegIdx)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### transferDefinedLanes() {#aa77e90c3a572d0523249dc6b27e6f10a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask DeadLaneDetector::transferDefinedLanes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Def, unsigned OpNum, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> DefinedLanes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a mask <span class="doxyComputerOutput">DefinedLanes</span> of lanes defined at operand <span class="doxyComputerOutput">OpNum</span> of COPY-like instruction, determine which lanes are defined at the output operand <span class="doxyComputerOutput">Def</span>.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### transferUsedLanes() {#a0507a9e0fb3ad8b5cbe21a6f19c8714c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask DeadLaneDetector::transferUsedLanes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> UsedLanes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a mask <span class="doxyComputerOutput">UsedLanes</span> used from the output of instruction <span class="doxyComputerOutput">MI</span> determine which lanes are used from operand <span class="doxyComputerOutput">MO</span> of this instruction.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#abf30ddf5feeccddcf0e890fc9022ec4d">llvm::TargetRegisterClass::CoveredBySubRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0c893675dfd5d1b1e4aea1e8211217c7">llvm::MachineOperand::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a0363c6cc08fe464f66f9e53239bb35e3">llvm::TargetRegisterClass::LaneMask</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#af79ff100b421c4477f89f3ab21a862de">lowersToCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#a4df23dddc646b6a4b36ff483063a4ff8">llvm::Register::virtReg2Index</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addUsedLanesOnOperand() {#a84c7997dcb59120654aae6e591d6b6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadLaneDetector::addUsedLanesOnOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> UsedLanes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add used lane bits on the register used by operand <span class="doxyComputerOutput">MO</span>.</p>


<p>This translates the bitmask based on the operands subregister, and puts the register into the worklist if any new bits were added.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>

</div>
</div>

### determineInitialDefinedLanes() {#a683cd8151047d30fc9f5568ea39080d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask DeadLaneDetector::determineInitialDefinedLanes (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>

</div>
</div>

### determineInitialUsedLanes() {#ac9e971e91f58e554bd5a14b65fa2b96e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask DeadLaneDetector::determineInitialUsedLanes (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>

</div>
</div>

### PutInWorklist() {#a461a46f7ba5a679e9d211367f0029934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DeadLaneDetector::PutInWorklist (unsigned RegIdx)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### transferDefinedLanesStep() {#af56b1da500a44e5704f6ace3ac8d7950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadLaneDetector::transferDefinedLanesStep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Use, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> DefinedLanes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a use regiser operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> and a mask of defined lanes, check if the operand belongs to a <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#af79ff100b421c4477f89f3ab21a862de">lowersToCopies()</a> instruction, transfer the mask to the def and put the instruction into the worklist.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>

</div>
</div>

### transferUsedLanesStep() {#a3706e4bf2a5257c5965bb0d386934d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadLaneDetector::transferUsedLanesStep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> UsedLanes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a bitmask <span class="doxyComputerOutput">UsedLanes</span> for the used lanes on a def output of a COPY-like instruction determine the lanes used on the use operands and call addUsedLanesOnOperand() for them.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DefinedByCopy {#a24a72197168da51a34a3d49df165136b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::DeadLaneDetector::DefinedByCopy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This bitvector is set for each vreg index where the vreg is defined by an instruction where <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#af79ff100b421c4477f89f3ab21a862de">lowersToCopies()</a>==true.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### MRI {#a2b15b372569132080a18f8245bd20f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* llvm::DeadLaneDetector::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### TRI {#aa743a63d11ea2710580bae0884055c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::DeadLaneDetector::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### VRegInfos {#a09fb441ed91571816f68eea455d8e958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;VRegInfo[]&gt; llvm::DeadLaneDetector::VRegInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### Worklist {#a443650f1f5ee4c198772e692bfc2dc46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;unsigned&gt; llvm::DeadLaneDetector::Worklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Worklist containing virtreg indexes.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

### WorklistMembers {#a11997276354619216b1dd53f9ca2e1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::DeadLaneDetector::WorklistMembers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/detectdeadlanes-h">DetectDeadLanes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp">DetectDeadLanes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
