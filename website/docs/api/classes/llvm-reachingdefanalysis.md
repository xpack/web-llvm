---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/reachingdefanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ReachingDefAnalysis` Class

<p>This class provides the reaching def analysis. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ReachingDefAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">llvm/CodeGen/ReachingDefAnalysis.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6823b697832f797208d6fa083f6d71">LiveRegsDefInfo</a> = std::vector&lt; int &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that defined each register, relative to the beginning of the current basic block. <a href="#a2a6823b697832f797208d6fa083f6d71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f81e54ba908c24cd4889533e6f558f">OutRegsInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LiveRegsDefInfo, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps clearance information for all registers. <a href="#a40f81e54ba908c24cd4889533e6f558f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af006c287439f2f408b6ee5ebb951b738">InstSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24d904aaeee62f20d15371bd78c88bb">BlockSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0413c573fa106fd0977f9992a0b9e4">ReachingDefAnalysis</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299fef476019ab8771773d7d4e664f2d">releaseMemory</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a299fef476019ab8771773d7d4e664f2d">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed. <a href="#a299fef476019ab8771773d7d4e664f2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b5dbb2a8d0bc48a7867741fb7bdebd">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a55b5dbb2a8d0bc48a7867741fb7bdebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d89916d0369e37e6cbfbca7219cbb6">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#af7d89916d0369e37e6cbfbca7219cbb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96c8d05f6a14c1009a4db5a7e710f8b">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39c852d6cd394007a2af6cc47012f295">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Re-run the analysis. <a href="#a39c852d6cd394007a2af6cc47012f295">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5418eaa6c605a696a952bf86c829fe71">init</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize data structures. <a href="#a5418eaa6c605a696a952bf86c829fe71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b847f56e0b64fc3d3f0bc89a876e8f">traverse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverse the machine function, mapping definitions. <a href="#a07b847f56e0b64fc3d3f0bc89a876e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides the instruction id of the closest reaching def instruction of Reg that reaches MI, relative to the begining of MI's basic block. <a href="#a4d88bf4454485733ba7b4c725a9ccf51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c18d22cd9c352cea5a957c89cf3f7c">hasSameReachingDef</a> (MachineInstr *A, MachineInstr *B, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether A and B use the same def of Reg. <a href="#ad1c18d22cd9c352cea5a957c89cf3f7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8aeae4e97e230dfac7bb530acd16eb0">isReachingDefLiveOut</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the reaching def for MI also is live out of its parent block. <a href="#ab8aeae4e97e230dfac7bb530acd16eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063cf42159fd59dccd371d78ceff4a01">getLocalLiveOutMIDef</a> (MachineBasicBlock *MBB, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the local MI that produces the live out value for Reg, or nullptr for a non-live out or non-local def. <a href="#a063cf42159fd59dccd371d78ceff4a01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf38674f9ee35a7d177066a78027aa56">getUniqueReachingMIDef</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a single <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> creates the reaching definition, then return it. <a href="#adf38674f9ee35a7d177066a78027aa56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f4fc1556edfb50cca3fe85fcc05e93">getMIOperand</a> (MachineInstr *MI, unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a single <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> creates the reaching definition, for MIs operand at Idx, then return it. <a href="#a36f4fc1556edfb50cca3fe85fcc05e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d350086d0170ad8429e57516ba5a17">getMIOperand</a> (MachineInstr *MI, MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a single <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> creates the reaching definition, for MIs MO, then return it. <a href="#ad0d350086d0170ad8429e57516ba5a17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e75c05a36cfe323cef8d3cceeb63c0b">hasLocalDefBefore</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide whether the register has been defined in the same basic block as, and before, MI. <a href="#a9e75c05a36cfe323cef8d3cceeb63c0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11578546fb4cd061fedf4838313d1f97">isRegUsedAfter</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the given register is used after MI, whether it's a local use or a live out. <a href="#a11578546fb4cd061fedf4838313d1f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74018294c98676ea265ee12521fb7e7">isRegDefinedAfter</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the given register is defined after MI. <a href="#ad74018294c98676ea265ee12521fb7e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95984ce0fa3263ce9a7c7992245a5e2c">getClearance</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides the clearance - the number of instructions since the closest reaching def instuction of Reg that reaches MI. <a href="#a95984ce0fa3263ce9a7c7992245a5e2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad474bae3c06f9ecee664f61b236e2ffb">getReachingLocalUses</a> (MachineInstr *MI, Register Reg, InstSet &amp;Uses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides the uses, in the same block as MI, of register that MI defines. <a href="#ad474bae3c06f9ecee664f61b236e2ffb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">getLiveOuts</a> (MachineBasicBlock *MBB, Register Reg, InstSet &amp;Defs, BlockSet &amp;VisitedBBs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search MBB for a definition of Reg and insert it into Defs. <a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e73391b90930eb7a6e346ca07a570b4">getLiveOuts</a> (MachineBasicBlock *MBB, Register Reg, InstSet &amp;Defs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbea737b469ca04dfced1aa6c87d55c8">getLiveInUses</a> (MachineBasicBlock *MBB, Register Reg, InstSet &amp;Uses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the given block, collect the instructions that use the live-in value of the provided register. <a href="#abbea737b469ca04dfced1aa6c87d55c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5594932b56f2e0629b440a3c14de9eda">getGlobalUses</a> (MachineInstr *MI, Register Reg, InstSet &amp;Uses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect the users of the value stored in Reg, which is defined by MI. <a href="#a5594932b56f2e0629b440a3c14de9eda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53ede66334f07735b415d87d177ff38">getGlobalReachingDefs</a> (MachineInstr *MI, Register Reg, InstSet &amp;Defs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all possible definitions of the value stored in Reg, which is used by MI. <a href="#ae53ede66334f07735b415d87d177ff38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e2271431de53cc4cc5057148c18c93">isSafeToMoveForwards</a> (MachineInstr *From, MachineInstr *To) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether From can be moved forwards to just before To. <a href="#a09e2271431de53cc4cc5057148c18c93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc46cb4bc77e9715066c204bd98e309">isSafeToMoveBackwards</a> (MachineInstr *From, MachineInstr *To) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether From can be moved backwards to just after To. <a href="#a7bc46cb4bc77e9715066c204bd98e309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67391278875db8d144d4b6bb6e6a09b8">collectKilledOperands</a> (MachineInstr *MI, InstSet &amp;Dead) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming MI is dead, recursively search the incoming operands which are killed by MI and collect those that would become dead. <a href="#a67391278875db8d144d4b6bb6e6a09b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f90013f33dac170acc9c62907d99e44">isSafeToRemove</a> (MachineInstr *MI, InstSet &amp;ToRemove) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether removing this instruction will have no effect on the program, returning the redundant use-def chain. <a href="#a2f90013f33dac170acc9c62907d99e44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90cebb38d9bd176e0efbc97c9bf33c2d">isSafeToRemove</a> (MachineInstr *MI, InstSet &amp;ToRemove, InstSet &amp;Ignore) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether removing this instruction will have no effect on the program, ignoring the possible effects on some instructions, returning the redundant use-def chain. <a href="#a90cebb38d9bd176e0efbc97c9bf33c2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1c3cbea21aa15aed845a4c163fe62c">isSafeToDefRegAt</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> could be inserted at MI and safely define the given register without affecting the program. <a href="#abd1c3cbea21aa15aed845a4c163fe62c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac153a9af74f3b0bb72e5f95a7654574e">isSafeToDefRegAt</a> (MachineInstr *MI, Register Reg, InstSet &amp;Ignore) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> could be inserted at MI and safely define the given register without affecting the program, ignoring any effects on the provided instructions. <a href="#ac153a9af74f3b0bb72e5f95a7654574e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43859808ee99bdb8b2cc6e5b8c7a1020">enterBasicBlock</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up LiveRegs by merging predecessor live-out values. <a href="#a43859808ee99bdb8b2cc6e5b8c7a1020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63eb401f65fa9655642cb865cc7a2f8c">leaveBasicBlock</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update live-out values. <a href="#a63eb401f65fa9655642cb865cc7a2f8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad922e9ce9738b3aa693664971d9d81a1">processBasicBlock</a> (const LoopTraversal::TraversedMBBInfo &amp;TraversedMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> he given basic block. <a href="#ad922e9ce9738b3aa693664971d9d81a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1618ce4ec28ec3239ac8d57a0f7cc534">reprocessBasicBlock</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> block that is part of a loop again. <a href="#a1618ce4ec28ec3239ac8d57a0f7cc534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6193dc3adc4e2b2779876e31f9e8bed8">processDefs</a> (MachineInstr *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update def-ages for registers defined by MI. <a href="#a6193dc3adc4e2b2779876e31f9e8bed8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Iterator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab3100c944028d50dacdc41f3e725c2d9">isSafeToMove</a> (MachineInstr *From, MachineInstr *To) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function for isSafeToMoveForwards/Backwards. <a href="#ab3100c944028d50dacdc41f3e725c2d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef608e89623bd7646435888a07446aa">isSafeToRemove</a> (MachineInstr *MI, InstSet &amp;Visited, InstSet &amp;ToRemove, InstSet &amp;Ignore) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether removing this instruction will have no effect on the program, ignoring the possible effects on some instructions, returning the redundant use-def chain. <a href="#afef608e89623bd7646435888a07446aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac218cd2bc1d3011f05b88f60588d843c">getInstFromId</a> (MachineBasicBlock *MBB, int InstId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides the MI, from the given block, corresponding to the Id or a nullptr if the id does not refer to the block. <a href="#ac218cd2bc1d3011f05b88f60588d843c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e31fd43bdb706d29716a5bb5365a446">getReachingLocalMIDef</a> (MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides the instruction of the closest reaching def instruction of Reg that reaches MI, relative to the begining of MI's basic block. <a href="#a6e31fd43bdb706d29716a5bb5365a446">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12043721f3b4b96fb4648f1e48e4137c">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a988bfa3400feab20b9001ca3503f2ae4">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/looptraversal/#adb30e4144436f66defa2ce2454e0fde8">LoopTraversal::TraversalOrder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc99fb880e4e52108eaac241b762219f">TraversedMBBOrder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc196ee7f67a649431e57267cdd3271">NumRegUnits</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LiveRegsDefInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496734e38cf07444333f80cda0163e7d">LiveRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">OutRegsInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1bfc0bd7379333aada63e1be5f629b">MBBOutRegsInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6a5bd3420fafb5f6eec4981748aa63">CurInstr</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current instruction number. <a href="#a1e6a5bd3420fafb5f6eec4981748aa63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a070111b5a9015acf139de4212e169">InstIds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps instructions to their instruction Ids, relative to the beginning of their basic blocks. <a href="#a38a070111b5a9015acf139de4212e169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mbbreachingdefsinfo">MBBReachingDefsInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45dc3370cadeca5b66fc7ee14864983e">MBBReachingDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8336a52f50f8bd8a78041ac57f863e64">ReachingDefDefaultVal</a> = -(1 &lt;&lt; 21)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default values are 'nothing happened a long time ago'. <a href="#a8336a52f50f8bd8a78041ac57f863e64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a818bf37052162dd21baf91ecd2ffd4b6">ID</a> = 0</td>
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

<p>This class provides the reaching def analysis.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BlockSet {#af24d904aaeee62f20d15371bd78c88bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ReachingDefAnalysis::BlockSet =  SmallPtrSetImpl&lt;MachineBasicBlock*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### InstSet {#af006c287439f2f408b6ee5ebb951b738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ReachingDefAnalysis::InstSet =  SmallPtrSetImpl&lt;MachineInstr*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### LiveRegsDefInfo {#a2a6823b697832f797208d6fa083f6d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ReachingDefAnalysis::LiveRegsDefInfo =  std::vector&lt;int&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that defined each register, relative to the beginning of the current basic block.</p>


<p>When a LiveRegsDefInfo is used to represent a live-out register, this value is relative to the end of the basic block, so it will be a negative number.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### OutRegsInfoMap {#a40f81e54ba908c24cd4889533e6f558f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ReachingDefAnalysis::OutRegsInfoMap =  SmallVector&lt;LiveRegsDefInfo, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps clearance information for all registers.</p>


<p>Note that this is different from the usual definition notion of liveness. The CPU doesn't care whether or not we consider a register killed.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ReachingDefAnalysis() {#a8f0413c573fa106fd0977f9992a0b9e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ReachingDefAnalysis::ReachingDefAnalysis ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a818bf37052162dd21baf91ecd2ffd4b6">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53c222c021b25ea32d7b52979d709bfb">llvm::initializeReachingDefAnalysisPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectKilledOperands() {#a67391278875db8d144d4b6bb6e6a09b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::collectKilledOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Dead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assuming MI is dead, recursively search the incoming operands which are killed by MI and collect those that would become dead.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a67391278875db8d144d4b6bb6e6a09b8">collectKilledOperands</a>, <a href="#a5594932b56f2e0629b440a3c14de9eda">getGlobalUses</a>, <a href="#a36f4fc1556edfb50cca3fe85fcc05e93">getMIOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a979659ec464cee64a84df219494fc2ea">IsDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a8710828eaf6aafddaeb91b5bcdc236da">isValidRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#ac3b2a46d9d056196ea4b3d2be7b1dcb8">isValidRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a460ee2e3823cbcd577daa94230fb17a8">mayHaveSideEffects</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38740a7e3fde66312240ec2cbf003fc2">llvm::set_is_subset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#a67391278875db8d144d4b6bb6e6a09b8">collectKilledOperands</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a55b5dbb2a8d0bc48a7867741fb7bdebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ReachingDefAnalysis::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> CFG.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### getClearance() {#a95984ce0fa3263ce9a7c7992245a5e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ReachingDefAnalysis::getClearance (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provides the clearance - the number of instructions since the closest reaching def instuction of Reg that reaches MI.</p>

<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getGlobalReachingDefs() {#ae53ede66334f07735b415d87d177ff38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::getGlobalReachingDefs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Defs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all possible definitions of the value stored in Reg, which is used by MI.</p>

<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">getLiveOuts</a>, <a href="#adf38674f9ee35a7d177066a78027aa56">getUniqueReachingMIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getGlobalUses() {#a5594932b56f2e0629b440a3c14de9eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::getGlobalUses (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Uses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect the users of the value stored in Reg, which is defined by MI.</p>

<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#abbea737b469ca04dfced1aa6c87d55c8">getLiveInUses</a>, <a href="#a063cf42159fd59dccd371d78ceff4a01">getLocalLiveOutMIDef</a>, <a href="#ad474bae3c06f9ecee664f61b236e2ffb">getReachingLocalUses</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#a67391278875db8d144d4b6bb6e6a09b8">collectKilledOperands</a> and <a href="#ac153a9af74f3b0bb72e5f95a7654574e">isSafeToDefRegAt</a>.</p>

</div>
</div>

### getLiveInUses() {#abbea737b469ca04dfced1aa6c87d55c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::getLiveInUses (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Uses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the given block, collect the instructions that use the live-in value of the provided register.</p>


<p>Return whether the value is still live on exit.</p>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90f68a1fc5d44bb06164dc2188b8e486">llvm::instructionsWithoutDebug</a>, <a href="#ab8aeae4e97e230dfac7bb530acd16eb0">isReachingDefLiveOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a0ca5780a94eb690d0ccf6cdda9c16df9">isValidRegUseOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#a5594932b56f2e0629b440a3c14de9eda">getGlobalUses</a>.</p>

</div>
</div>

### getLiveOuts() {#a8a6fbbe8151eaf22fac6f748d6d55b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::getLiveOuts (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Defs, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">BlockSet</a> &amp; VisitedBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search MBB for a definition of Reg and insert it into Defs.</p>


<p>If no definition is found, recursively search the predecessor blocks for them.</p>


<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">getLiveOuts</a>, <a href="#a063cf42159fd59dccd371d78ceff4a01">getLocalLiveOutMIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#ae53ede66334f07735b415d87d177ff38">getGlobalReachingDefs</a>, <a href="#a1e73391b90930eb7a6e346ca07a570b4">getLiveOuts</a>, <a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">getLiveOuts</a> and <a href="#adf38674f9ee35a7d177066a78027aa56">getUniqueReachingMIDef</a>.</p>

</div>
</div>

### getLiveOuts() {#a1e73391b90930eb7a6e346ca07a570b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::getLiveOuts (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Defs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">getLiveOuts</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### getLocalLiveOutMIDef() {#a063cf42159fd59dccd371d78ceff4a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ReachingDefAnalysis::getLocalLiveOutMIDef (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the local MI that produces the live out value for Reg, or nullptr for a non-live out or non-local def.</p>

<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#aa524a697f0c6f94cef4d7a1f48f856e9">isValidRegDefOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a5594932b56f2e0629b440a3c14de9eda">getGlobalUses</a>, <a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">getLiveOuts</a> and <a href="#ad74018294c98676ea265ee12521fb7e7">isRegDefinedAfter</a>.</p>

</div>
</div>

### getMIOperand() {#a36f4fc1556edfb50cca3fe85fcc05e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ReachingDefAnalysis::getMIOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a single <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> creates the reaching definition, for MIs operand at Idx, then return it.</p>


<p>Otherwise return null.</p>


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adf38674f9ee35a7d177066a78027aa56">getUniqueReachingMIDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a67391278875db8d144d4b6bb6e6a09b8">collectKilledOperands</a>.</p>

</div>
</div>

### getMIOperand() {#ad0d350086d0170ad8429e57516ba5a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ReachingDefAnalysis::getMIOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a single <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> creates the reaching definition, for MIs MO, then return it.</p>


<p>Otherwise return null.</p>


<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#adf38674f9ee35a7d177066a78027aa56">getUniqueReachingMIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getReachingDef() {#a4d88bf4454485733ba7b4c725a9ccf51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ReachingDefAnalysis::getReachingDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provides the instruction id of the closest reaching def instruction of Reg that reaches MI, relative to the begining of MI's basic block.</p>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a95984ce0fa3263ce9a7c7992245a5e2c">getClearance</a>, <a href="#abbea737b469ca04dfced1aa6c87d55c8">getLiveInUses</a>, <a href="#a063cf42159fd59dccd371d78ceff4a01">getLocalLiveOutMIDef</a>, <a href="#a9e75c05a36cfe323cef8d3cceeb63c0b">hasLocalDefBefore</a>, <a href="#ad1c18d22cd9c352cea5a957c89cf3f7c">hasSameReachingDef</a>, <a href="#ab8aeae4e97e230dfac7bb530acd16eb0">isReachingDefLiveOut</a> and <a href="#ad74018294c98676ea265ee12521fb7e7">isRegDefinedAfter</a>.</p>

</div>
</div>

### getReachingLocalUses() {#ad474bae3c06f9ecee664f61b236e2ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::getReachingLocalUses (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Uses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provides the uses, in the same block as MI, of register that MI defines.</p>


<p>This does not consider live-outs.</p>


<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a0ca5780a94eb690d0ccf6cdda9c16df9">isValidRegUseOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#a5594932b56f2e0629b440a3c14de9eda">getGlobalUses</a>.</p>

</div>
</div>

### getRequiredProperties() {#ad96c8d05f6a14c1009a4db5a7e710f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::ReachingDefAnalysis::getRequiredProperties ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a">llvm::MachineFunctionProperties::TracksLiveness</a>.</p>

</div>
</div>

### getUniqueReachingMIDef() {#adf38674f9ee35a7d177066a78027aa56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ReachingDefAnalysis::getUniqueReachingMIDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a single <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> creates the reaching definition, then return it.</p>


<p>Otherwise return null.</p>


<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a8a6fbbe8151eaf22fac6f748d6d55b6e">getLiveOuts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#addd80df79ba902914c7d8a52e3896b79">llvm::MachineBasicBlock::predecessors</a>.</p>


<p>Referenced by <a href="#ae53ede66334f07735b415d87d177ff38">getGlobalReachingDefs</a>, <a href="#ad0d350086d0170ad8429e57516ba5a17">getMIOperand</a> and <a href="#a36f4fc1556edfb50cca3fe85fcc05e93">getMIOperand</a>.</p>

</div>
</div>

### hasLocalDefBefore() {#a9e75c05a36cfe323cef8d3cceeb63c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::hasLocalDefBefore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide whether the register has been defined in the same basic block as, and before, MI.</p>

<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### hasSameReachingDef() {#ad1c18d22cd9c352cea5a957c89cf3f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::hasSameReachingDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * A, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether A and B use the same def of Reg.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a>.</p>

</div>
</div>

### init() {#a5418eaa6c605a696a952bf86c829fe71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::init ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize data structures.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/looptraversal/#a87cd9704fc800af5dddb87f26badfb3a">llvm::LoopTraversal::traverse</a>.</p>


<p>Referenced by <a href="#a39c852d6cd394007a2af6cc47012f295">reset</a> and <a href="#af7d89916d0369e37e6cbfbca7219cbb6">runOnMachineFunction</a>.</p>

</div>
</div>

### isReachingDefLiveOut() {#ab8aeae4e97e230dfac7bb530acd16eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isReachingDefLiveOut (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the reaching def for MI also is live out of its parent block.</p>

<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#aa524a697f0c6f94cef4d7a1f48f856e9">isValidRegDefOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#abbea737b469ca04dfced1aa6c87d55c8">getLiveInUses</a>.</p>

</div>
</div>

### isRegDefinedAfter() {#ad74018294c98676ea265ee12521fb7e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isRegDefinedAfter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the given register is defined after MI.</p>

<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a063cf42159fd59dccd371d78ceff4a01">getLocalLiveOutMIDef</a>, <a href="#a4d88bf4454485733ba7b4c725a9ccf51">getReachingDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ac153a9af74f3b0bb72e5f95a7654574e">isSafeToDefRegAt</a>.</p>

</div>
</div>

### isRegUsedAfter() {#a11578546fb4cd061fedf4838313d1f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isRegUsedAfter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the given register is used after MI, whether it's a local use or a live out.</p>

<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a90f68a1fc5d44bb06164dc2188b8e486">llvm::instructionsWithoutDebug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ac153a9af74f3b0bb72e5f95a7654574e">isSafeToDefRegAt</a>.</p>

</div>
</div>

### isSafeToDefRegAt() {#abd1c3cbea21aa15aed845a4c163fe62c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToDefRegAt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> could be inserted at MI and safely define the given register without affecting the program.</p>

<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a>, <a href="#abd1c3cbea21aa15aed845a4c163fe62c">isSafeToDefRegAt</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#abd1c3cbea21aa15aed845a4c163fe62c">isSafeToDefRegAt</a>.</p>

</div>
</div>

### isSafeToDefRegAt() {#ac153a9af74f3b0bb72e5f95a7654574e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToDefRegAt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Ignore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> could be inserted at MI and safely define the given register without affecting the program, ignoring any effects on the provided instructions.</p>

<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a5594932b56f2e0629b440a3c14de9eda">getGlobalUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a>, <a href="#ad74018294c98676ea265ee12521fb7e7">isRegDefinedAfter</a>, <a href="#a11578546fb4cd061fedf4838313d1f97">isRegUsedAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#aa524a697f0c6f94cef4d7a1f48f856e9">isValidRegDefOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38740a7e3fde66312240ec2cbf003fc2">llvm::set_is_subset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>

</div>
</div>

### isSafeToMoveBackwards() {#a7bc46cb4bc77e9715066c204bd98e309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToMoveBackwards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * From, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether From can be moved backwards to just after To.</p>

<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a2a25c462b91ac5da41f4ab7edc32b650">llvm::MachineBasicBlock::rend</a>.</p>

</div>
</div>

### isSafeToMoveForwards() {#a09e2271431de53cc4cc5057148c18c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToMoveForwards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * From, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether From can be moved forwards to just before To.</p>

<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isSafeToRemove() {#a2f90013f33dac170acc9c62907d99e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToRemove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; ToRemove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether removing this instruction will have no effect on the program, returning the redundant use-def chain.</p>

<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a>, <a href="#a2f90013f33dac170acc9c62907d99e44">isSafeToRemove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>.</p>


<p>Referenced by <a href="#a2f90013f33dac170acc9c62907d99e44">isSafeToRemove</a> and <a href="#a90cebb38d9bd176e0efbc97c9bf33c2d">isSafeToRemove</a>.</p>

</div>
</div>

### isSafeToRemove() {#a90cebb38d9bd176e0efbc97c9bf33c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToRemove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; ToRemove, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Ignore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether removing this instruction will have no effect on the program, ignoring the possible effects on some instructions, returning the redundant use-def chain.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a>, <a href="#a2f90013f33dac170acc9c62907d99e44">isSafeToRemove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>.</p>

</div>
</div>

### releaseMemory() {#a299fef476019ab8771773d7d4e664f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::releaseMemory ()</td>
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

<p><a href="#a299fef476019ab8771773d7d4e664f2d">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed.</p>


<p>The default behavior of passes is to hold onto memory for the entire duration of their lifetime (which is the entire compile time). For pipelined passes, this is not a big deal because that memory gets recycled every time the pass is invoked on another program unit. For IP passes, it is more important to free memory when it is unused.</p>


<p>Optionally implement this function to release pass memory when it is no longer used.</p>


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a39c852d6cd394007a2af6cc47012f295">reset</a>.</p>

</div>
</div>

### reset() {#a39c852d6cd394007a2af6cc47012f295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Re-run the analysis.</p>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="#a5418eaa6c605a696a952bf86c829fe71">init</a>, <a href="#a299fef476019ab8771773d7d4e664f2d">releaseMemory</a> and <a href="#a07b847f56e0b64fc3d3f0bc89a876e8f">traverse</a>.</p>

</div>
</div>

### runOnMachineFunction() {#af7d89916d0369e37e6cbfbca7219cbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a5418eaa6c605a696a952bf86c829fe71">init</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a07b847f56e0b64fc3d3f0bc89a876e8f">traverse</a>.</p>

</div>
</div>

### traverse() {#a07b847f56e0b64fc3d3f0bc89a876e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::traverse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Traverse the machine function, mapping definitions.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a39c852d6cd394007a2af6cc47012f295">reset</a> and <a href="#af7d89916d0369e37e6cbfbca7219cbb6">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### enterBasicBlock() {#a43859808ee99bdb8b2cc6e5b8c7a1020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::enterBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up LiveRegs by merging predecessor live-out values.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### getInstFromId() {#ac218cd2bc1d3011f05b88f60588d843c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ReachingDefAnalysis::getInstFromId (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, int InstId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provides the MI, from the given block, corresponding to the Id or a nullptr if the id does not refer to the block.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### getReachingLocalMIDef() {#a6e31fd43bdb706d29716a5bb5365a446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ReachingDefAnalysis::getReachingLocalMIDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provides the instruction of the closest reaching def instruction of Reg that reaches MI, relative to the begining of MI's basic block.</p>

<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### isSafeToMove() {#ab3100c944028d50dacdc41f3e725c2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToMove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * From, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility function for isSafeToMoveForwards/Backwards.</p>

<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### isSafeToRemove() {#afef608e89623bd7646435888a07446aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReachingDefAnalysis::isSafeToRemove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; ToRemove, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">InstSet</a> &amp; Ignore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether removing this instruction will have no effect on the program, ignoring the possible effects on some instructions, returning the redundant use-def chain.</p>

<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### leaveBasicBlock() {#a63eb401f65fa9655642cb865cc7a2f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::leaveBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update live-out values.</p>

<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### processBasicBlock() {#ad922e9ce9738b3aa693664971d9d81a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::processBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/looptraversal/traversedmbbinfo">LoopTraversal::TraversedMBBInfo</a> &amp; TraversedMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> he given basic block.</p>

<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### processDefs() {#a6193dc3adc4e2b2779876e31f9e8bed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::processDefs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update def-ages for registers defined by MI.</p>


<p>Also break dependencies on partial defs and undef uses.</p>


<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

### reprocessBasicBlock() {#a1618ce4ec28ec3239ac8d57a0f7cc534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReachingDefAnalysis::reprocessBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> block that is part of a loop again.</p>

<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurInstr {#a1e6a5bd3420fafb5f6eec4981748aa63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ReachingDefAnalysis::CurInstr = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current instruction number.</p>


<p>The first instruction in each basic block is 0.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### InstIds {#a38a070111b5a9015acf139de4212e169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr *, int&gt; llvm::ReachingDefAnalysis::InstIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps instructions to their instruction Ids, relative to the beginning of their basic blocks.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### LiveRegs {#a496734e38cf07444333f80cda0163e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegsDefInfo llvm::ReachingDefAnalysis::LiveRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### MBBOutRegsInfos {#afd1bfc0bd7379333aada63e1be5f629b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutRegsInfoMap llvm::ReachingDefAnalysis::MBBOutRegsInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### MBBReachingDefs {#a45dc3370cadeca5b66fc7ee14864983e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBReachingDefsInfo llvm::ReachingDefAnalysis::MBBReachingDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### MF {#a12043721f3b4b96fb4648f1e48e4137c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::ReachingDefAnalysis::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### NumRegUnits {#a5dc196ee7f67a649431e57267cdd3271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ReachingDefAnalysis::NumRegUnits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### ReachingDefDefaultVal {#a8336a52f50f8bd8a78041ac57f863e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::ReachingDefAnalysis::ReachingDefDefaultVal = -(1 &lt;&lt; 21)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default values are 'nothing happened a long time ago'.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### TraversedMBBOrder {#afc99fb880e4e52108eaac241b762219f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopTraversal::TraversalOrder llvm::ReachingDefAnalysis::TraversedMBBOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

### TRI {#a988bfa3400feab20b9001ca3503f2ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::ReachingDefAnalysis::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a818bf37052162dd21baf91ecd2ffd4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char ReachingDefAnalysis::ID = 0</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a>.</p>


<p>Referenced by <a href="#a8f0413c573fa106fd0977f9992a0b9e4">ReachingDefAnalysis</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">ReachingDefAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp">ReachingDefAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
