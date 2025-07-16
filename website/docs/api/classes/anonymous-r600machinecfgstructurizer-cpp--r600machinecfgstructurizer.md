---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `R600MachineCFGStructurizer` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer { ... }
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0009df8487e92d910d815f6b6e5c63bc">MBBVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 32 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c45f49343f589007a3fccdfcce0207">MBBInfoMap</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/blockinformation">BlockInformation</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa355f0a3d6838f8550e3a8f418e54de8">LoopLandInfoMap</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PathToKind { <a href="#a71749ba4b31c340ca06fe1bab875d798">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998f23f119e9621929d4b4733038330c">R600MachineCFGStructurizer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dda63cfe783295cfca017dda6eeba3c">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a0dda63cfe783295cfca017dda6eeba3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c3c4b8d8ffa687c62ee01b4095ca8b">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a21c3c4b8d8ffa687c62ee01b4095ca8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e759f21490690f9162f74e250d73857">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the CFG structurization. <a href="#a5e759f21490690f9162f74e250d73857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0804b0846b504f0556a8085204f1127b">prepare</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the CFG preparation This step will remove every unconditionnal/dead jump instructions and make sure all loops have an exit block. <a href="#a0804b0846b504f0556a8085204f1127b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d11407984f3a71442a04a5e619b6524">printOrderedBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the ordered Blocks. <a href="#a5d11407984f3a71442a04a5e619b6524">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ebb54e025596f580bf6d56712a574a1">getSCCNum</a> (MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a611142121c7c2f7505e490784ac949b1">getLoopLandInfo</a> (MachineLoop *LoopRep) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad1ad05191dcc842acb7c84422494a5">hasBackEdge</a> (MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf95e3d94f7d3fdaa233d736db960b6">isRetiredBlock</a> (MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68fba9e05f782a97df84dff26ef5abfa">isActiveLoophead</a> (MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a71749ba4b31c340ca06fe1bab875d798">PathToKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac393ff87a496a67dae4ba9430b816263">singlePathTo</a> (MachineBasicBlock *SrcMBB, MachineBasicBlock *DstMBB, bool AllowSideEntry=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8cab61cc41f1322ee1747504d3dff9">countActiveBlock</a> (MBBVector::const_iterator It, MBBVector::const_iterator E) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a901c595cf2030662702d96c1ae1d3">needMigrateBlock</a> (MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39887a32773197d7e0b998204868263">reversePredicateSetter</a> (MachineBasicBlock::iterator I, MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75612e4710d7d73f6df2086ffc21334a">orderBlocks</a> (MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the reversed DFS post order of Blocks. <a href="#a75612e4710d7d73f6df2086ffc21334a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebef2fa97bc3b381ec5e9cb8c82abcd5">insertInstrEnd</a> (MachineBasicBlock *MBB, int NewOpcode, const DebugLoc &amp;DL=DebugLoc())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bdc8239201deba8ba0b0520cd7206cb">insertInstrBefore</a> (MachineBasicBlock *MBB, int NewOpcode, const DebugLoc &amp;DL=DebugLoc())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb10bbe55466736b6d97ce923f4c973">insertInstrBefore</a> (MachineBasicBlock::iterator I, int NewOpcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa859694dc733dcc4def80843314a9666">insertCondBranchBefore</a> (MachineBasicBlock::iterator I, int NewOpcode, const DebugLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, int NewOpcode, int RegNum, const DebugLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The correct naming for this is getPossibleLoopendBlockBranchInstr. <a href="#a1e5913a75e260c91dab2c7edcb71868a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">replaceInstrUseOfBlockWith</a> (MachineBasicBlock *SrcMBB, MachineBasicBlock *OldMBB, MachineBasicBlock *NewBlk)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab9a54fdc7456ee97cb54ff30d625b6b7">MachineBasicBlock::ReplaceUsesOfBlockWith</a> doesn't serve the purpose because the <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> instruction is not recognized as terminator fix this and retire this routine. <a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa148c60a3af1c31e9b15172889ef665">patternMatch</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053aad9dc034ec2f71167e05ec1800f5">patternMatchGroup</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df2f5237587b9555efb489278d3b73d">loopendPatternMatch</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a> (MachineLoop *LoopRep)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c501f2f094f555ee3dbe0a1970d300">isSameloopDetachedContbreak</a> (MachineBasicBlock *Src1MBB, MachineBasicBlock *Src2MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>return true iff src1Blk-&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a126a78caf2176eb39d879c899bdd749c">succ_empty()</a> &amp;&amp; src1Blk and src2Blk are in the same loop with LoopLandInfo without explicitly keeping track of loopContBlks and loopBreakBlks, this is a method to get the information. <a href="#a34c501f2f094f555ee3dbe0a1970d300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e59431f88bf9267aa3917ed77527a5">handleJumpintoIf</a> (MachineBasicBlock *HeadMBB, MachineBasicBlock *TrueMBB, MachineBasicBlock *FalseMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d20136077641cd8689ad93587230228">handleJumpintoIfImp</a> (MachineBasicBlock *HeadMBB, MachineBasicBlock *TrueMBB, MachineBasicBlock *FalseMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a> (MachineBasicBlock *HeadMBB, MachineBasicBlock *TrueMBB, MachineBasicBlock *FalseMBB, MachineBasicBlock **LandMBBPtr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac471c55917cb9e3fdc7674e300260d9f">showImproveSimpleJumpintoIf</a> (MachineBasicBlock *HeadMBB, MachineBasicBlock *TrueMBB, MachineBasicBlock *FalseMBB, MachineBasicBlock *LandMBB, bool Detail=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab90cb03c7501b031fa63735cc9391a5f">cloneOnSideEntryTo</a> (MachineBasicBlock *PreMBB, MachineBasicBlock *SrcMBB, MachineBasicBlock *DstMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fec9aab7a2ff820c3c372f3cda87c25">mergeSerialBlock</a> (MachineBasicBlock *DstMBB, MachineBasicBlock *SrcMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a> (MachineInstr *BranchMI, MachineBasicBlock *MBB, MachineBasicBlock *TrueMBB, MachineBasicBlock *FalseMBB, MachineBasicBlock *LandMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38ab4f331b754f58147aaa7a86febb1">mergeLooplandBlock</a> (MachineBasicBlock *DstMBB, MachineBasicBlock *LandMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a> (MachineBasicBlock *ExitingMBB, MachineBasicBlock *LandMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a> (MachineBasicBlock *ContingMBB, MachineBasicBlock *ContMBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d3fe2699745c950168939ee8f0d5cb">normalizeInfiniteLoopExit</a> (MachineLoop *LoopRep)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>normalizeInfiniteLoopExit change B1: uncond_br LoopHeader <a href="#a43d3fe2699745c950168939ee8f0d5cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892f776a360693f609ef055a45a6f6a8">removeUnconditionalBranch</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9608ee656bad26eae3b7188510f43d1">removeRedundantConditionalBranch</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove duplicate branches instructions in a block. <a href="#ac9608ee656bad26eae3b7188510f43d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41dd7655c0a468a74784440f2a65bdb8">addDummyExitBlock</a> (SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;RetMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768d00a2a1c079d1da7719341caadd1a">removeSuccessor</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8945ac962ff2d369b77ff9ab927529a4">cloneBlockForPredecessor</a> (MachineBasicBlock *MBB, MachineBasicBlock *PredMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b11aa12929fbf594b75074a35dc9c2">migrateInstruction</a> (MachineBasicBlock *SrcMBB, MachineBasicBlock *DstMBB, MachineBasicBlock::iterator I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac1bbcd1976f0888cd8084dddc59fb3c">recordSccnum</a> (MachineBasicBlock *MBB, int SCCNum)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16b8b98cfbc579a4227f3f79bcfef44">retireBlock</a> (MachineBasicBlock *MBB)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3824f7a9afb2ff602a01b2a0c11318cc">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3599a755479b17015844a0b485c648c">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b61445c5e090342270032cf9447b67">MLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo">R600InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c715c7f8205486cf9debd5cce6d8088">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/r600registerinfo">R600RegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc03d00e143160f0abceb251a028ad2e">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a99c45f49343f589007a3fccdfcce0207">MBBInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a516d256022db88eb0404520c832d3be2">BlockInfoMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa355f0a3d6838f8550e3a8f418e54de8">LoopLandInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf7d333061ecb2204e2edaa6e93edc67">LLInfoMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae2140b9584026c0e1dbeed1226fb53">Visited</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d16c576c8dffadc466326d8f39f4f60">FuncRep</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a76a4df9e61675ad0d77fbd023aa60670a3761d84b2bbd04b89adb865894d86e59">DEFAULT_VEC_SLOTS</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6079c7b25f387791bb85d4c59c64498">OrderedBlks</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d385e0a55206f23f585f4bd59934224">PrintLoopinfo</a> (const MachineLoopInfo &amp;LoopInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49ab69e09d83cb77901ff2d50f6d24e3">getBranchNzeroOpcode</a> (int OldOpcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b1031662a9845abf2a38a9c72ba50ad">getBranchZeroOpcode</a> (int OldOpcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35eea839c370d75908b9948a7c967c09">getContinueNzeroOpcode</a> (int OldOpcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8275e1cc93bf70e016f77edcf56eb4">getContinueZeroOpcode</a> (int OldOpcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b50498b11eadf18d8de24481deae37e">getTrueBranch</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f6a458f01fa327f1acfac4d97dd252">setTrueBranch</a> (MachineInstr *MI, MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812611158870a1016b5b51a1aed54862">getFalseBranch</a> (MachineBasicBlock *MBB, MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53aaaaa28342f1e9a4c82022818afab">isUncondBranch</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4e796f7259afad7cc9a7d24a8720ae">getLastDebugLocInBB</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7310f956774ef6e2886820c1120b5727">getNormalBlockBranchInstr</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c91f131b10e9fe99f49069a1f725e19">getReturnInstr</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7c192b3a055baeefd28beb0ab1cfbfd">isReturnBlock</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5698213d6d250e814ed909311751be">cloneSuccessorList</a> (MachineBasicBlock *DstMBB, MachineBasicBlock *SrcMBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3312930671bb8ba4a3e685149c8f4e43">clone</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b20ed1597d31f0d73ce282f0db4db6">wrapup</a> (MachineBasicBlock *MBB)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6ffaab1cd70c950b35d0c83850476f">ID</a> = 0</td>
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


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LoopLandInfoMap {#aa355f0a3d6838f8550e3a8f418e54de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::LoopLandInfoMap =  std::map&lt;MachineLoop *, MachineBasicBlock *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

### MBBInfoMap {#a99c45f49343f589007a3fccdfcce0207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::MBBInfoMap =  std::map&lt;MachineBasicBlock *, BlockInformation *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

### MBBVector {#a0009df8487e92d910d815f6b6e5c63bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::MBBVector =  SmallVector&lt;MachineBasicBlock *, 32&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### PathToKind {#a71749ba4b31c340ca06fe1bab875d798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::PathToKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Not_SinglePath<a id="a71749ba4b31c340ca06fe1bab875d798aa47fdb9a1e206a39e39dc57375a0d32b"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SinglePath_InPath<a id="a71749ba4b31c340ca06fe1bab875d798a63fed8fc4b455c2f92fdfb0011901cb7"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SinglePath_NotInPath<a id="a71749ba4b31c340ca06fe1bab875d798a9be6a253bf8ef1967089447de889c4e1"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### R600MachineCFGStructurizer() {#a998f23f119e9621929d4b4733038330c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::R600MachineCFGStructurizer ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a9b6ffaab1cd70c950b35d0c83850476f">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a732d42280154ec2eef87cf1300835889">llvm::initializeR600MachineCFGStructurizerPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aebe3e6ec9d51261e6cc4f8dafdfae01c">llvm::createR600MachineCFGStructurizerPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a21c3c4b8d8ffa687c62ee01b4095ca8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#a0dda63cfe783295cfca017dda6eeba3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

### prepare() {#a0804b0846b504f0556a8085204f1127b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::prepare ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the CFG preparation This step will remove every unconditionnal/dead jump instructions and make sure all loops have an exit block.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="#a41dd7655c0a468a74784440f2a65bdb8">addDummyExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad7c192b3a055baeefd28beb0ab1cfbfd">isReturnBlock</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>, <a href="#a43d3fe2699745c950168939ee8f0d5cb">normalizeInfiniteLoopExit</a>, <a href="#a75612e4710d7d73f6df2086ffc21334a">orderBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ac9608ee656bad26eae3b7188510f43d1">removeRedundantConditionalBranch</a>, <a href="#a892f776a360693f609ef055a45a6f6a8">removeUnconditionalBranch</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### run() {#a5e759f21490690f9162f74e250d73857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the CFG structurization.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abb8cab61cc41f1322ee1747504d3dff9">countActiveBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a2ebb54e025596f580bf6d56712a574a1">getSCCNum</a>, <a href="#aaaf95e3d94f7d3fdaa233d736db960b6">isRetiredBlock</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaa148c60a3af1c31e9b15172889ef665">patternMatch</a>, <a href="#a5d11407984f3a71442a04a5e619b6524">printOrderedBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa8d1d8d88835b75b05b14ab774785e8a">llvm::MachineBasicBlock::succ_empty</a> and <a href="#a23b20ed1597d31f0d73ce282f0db4db6">wrapup</a>.</p>


<p>Referenced by <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a18192ed7893e8738ddd38e7f75bb3bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d931af4280c80a837ee409eb85104f7">llvm::MachineFunction::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a006012900aff2102a22e6424f2994592">llvm::MachineFunctionProperties::FailsVerification</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a3824f7a9afb2ff602a01b2a0c11318cc">MDT</a>, <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>, <a href="#af3599a755479b17015844a0b485c648c">PDT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#acc01b07763ec8c4b7acd6ffaa69b1c0c">prepare</a>, <a href="#a7d385e0a55206f23f585f4bd59934224">PrintLoopinfo</a>, <a href="#a5e759f21490690f9162f74e250d73857">run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>, <a href="#a2c715c7f8205486cf9debd5cce6d8088">TII</a> and <a href="#abc03d00e143160f0abceb251a028ad2e">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addDummyExitBlock() {#a41dd7655c0a468a74784440f2a65bdb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::addDummyExitBlock (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; RetMBB)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5c91f131b10e9fe99f49069a1f725e19">getReturnInstr</a>, <a href="#aebef2fa97bc3b381ec5e9cb8c82abcd5">insertInstrEnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3b1dce1f3354a357fb9061bb7568a84e">llvm::MachineBasicBlock::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a0e4b8f56e1248ac6f0c93ab1212ed99c">SHOWNEWBLK</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a0804b0846b504f0556a8085204f1127b">prepare</a>.</p>

</div>
</div>

### cloneBlockForPredecessor() {#a8945ac962ff2d369b77ff9ab927529a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * R600MachineCFGStructurizer::cloneBlockForPredecessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PredMBB)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3312930671bb8ba4a3e685149c8f4e43">clone</a>, <a href="#a1e5698213d6d250e814ed909311751be">cloneSuccessorList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">replaceInstrUseOfBlockWith</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a2d4703c258359175d1c7840735bd77b6">llvm::MachineBasicBlock::replaceSuccessor</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a0e4b8f56e1248ac6f0c93ab1212ed99c">SHOWNEWBLK</a>.</p>


<p>Referenced by <a href="#ab90cb03c7501b031fa63735cc9391a5f">cloneOnSideEntryTo</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### cloneOnSideEntryTo() {#ab90cb03c7501b031fa63735cc9391a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::cloneOnSideEntryTo (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PreMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SrcMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8945ac962ff2d369b77ff9ab927529a4">cloneBlockForPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>.</p>


<p>Referenced by <a href="#a3d20136077641cd8689ad93587230228">handleJumpintoIfImp</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### countActiveBlock() {#abb8cab61cc41f1322ee1747504d3dff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::countActiveBlock (<a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">MBBVector::const_iterator</a> It, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">MBBVector::const_iterator</a> E)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="#aaaf95e3d94f7d3fdaa233d736db960b6">isRetiredBlock</a>.</p>


<p>Referenced by <a href="#a5e759f21490690f9162f74e250d73857">run</a>.</p>

</div>
</div>

### getLoopendBlockBranchInstr() {#a1e5913a75e260c91dab2c7edcb71868a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600MachineCFGStructurizer::getLoopendBlockBranchInstr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>The correct naming for this is getPossibleLoopendBlockBranchInstr.</p>


<p>BB with backward-edge could have move instructions after the branch instruction. Such move instruction "belong to" the loop backward-edge.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a>, <a href="#ae53aaaaa28342f1e9a4c82022818afab">isUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a2c715c7f8205486cf9debd5cce6d8088">TII</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a>, <a href="#a43d3fe2699745c950168939ee8f0d5cb">normalizeInfiniteLoopExit</a>, <a href="#a892f776a360693f609ef055a45a6f6a8">removeUnconditionalBranch</a>, <a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">replaceInstrUseOfBlockWith</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### getLoopLandInfo() {#a611142121c7c2f7505e490784ac949b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * R600MachineCFGStructurizer::getLoopLandInfo (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * LoopRep)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Referenced by <a href="#a68fba9e05f782a97df84dff26ef5abfa">isActiveLoophead</a>.</p>

</div>
</div>

### getSCCNum() {#a2ebb54e025596f580bf6d56712a574a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::getSCCNum (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#ad097d7496ddf0db2c2d2e34bdbe4d2e9">INVALIDSCCNUM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a75612e4710d7d73f6df2086ffc21334a">orderBlocks</a>, <a href="#a5d11407984f3a71442a04a5e619b6524">printOrderedBlocks</a> and <a href="#a5e759f21490690f9162f74e250d73857">run</a>.</p>

</div>
</div>

### handleJumpintoIf() {#a15e59431f88bf9267aa3917ed77527a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::handleJumpintoIf (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * HeadMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TrueMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FalseMBB)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3d20136077641cd8689ad93587230228">handleJumpintoIfImp</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### handleJumpintoIfImp() {#a3d20136077641cd8689ad93587230228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::handleJumpintoIfImp (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * HeadMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TrueMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FalseMBB)</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab90cb03c7501b031fa63735cc9391a5f">cloneOnSideEntryTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a>, <a href="#a71749ba4b31c340ca06fe1bab875d798a63fed8fc4b455c2f92fdfb0011901cb7">SinglePath_InPath</a>, <a href="#ac393ff87a496a67dae4ba9430b816263">singlePathTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>.</p>


<p>Referenced by <a href="#a15e59431f88bf9267aa3917ed77527a5">handleJumpintoIf</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### hasBackEdge() {#abad1ad05191dcc842acb7c84422494a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::hasBackEdge (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>.</p>

</div>
</div>

### ifPatternMatch() {#a55b3f01e91f974764d18a95d9e4b7ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::ifPatternMatch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8945ac962ff2d369b77ff9ab927529a4">cloneBlockForPredecessor</a>, <a href="#a812611158870a1016b5b51a1aed54862">getFalseBranch</a>, <a href="#a7310f956774ef6e2886820c1120b5727">getNormalBlockBranchInstr</a>, <a href="#a8b50498b11eadf18d8de24481deae37e">getTrueBranch</a>, <a href="#a15e59431f88bf9267aa3917ed77527a5">handleJumpintoIf</a>, <a href="#abad1ad05191dcc842acb7c84422494a5">hasBackEdge</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a>, <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a>, <a href="#a34c501f2f094f555ee3dbe0a1970d300">isSameloopDetachedContbreak</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="#ac39887a32773197d7e0b998204868263">reversePredicateSetter</a>, <a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa8d1d8d88835b75b05b14ab774785e8a">llvm::MachineBasicBlock::succ_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a3d20136077641cd8689ad93587230228">handleJumpintoIfImp</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a> and <a href="#a053aad9dc034ec2f71167e05ec1800f5">patternMatchGroup</a>.</p>

</div>
</div>

### improveSimpleJumpintoIf() {#ae27fd47ee099b4aba7fe2bc84be97ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::improveSimpleJumpintoIf (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * HeadMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TrueMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FalseMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> ** LandMBBPtr)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa859694dc733dcc4def80843314a9666">insertCondBranchBefore</a>, <a href="#a0bdc8239201deba8ba0b0520cd7206cb">insertInstrBefore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a34b11aa12929fbf594b75074a35dc9c2">migrateInstruction</a>, <a href="#a45a901c595cf2030662702d96c1ae1d3">needMigrateBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#addd80df79ba902914c7d8a52e3896b79">llvm::MachineBasicBlock::predecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#ac471c55917cb9e3fdc7674e300260d9f">showImproveSimpleJumpintoIf</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a> and <a href="#abc03d00e143160f0abceb251a028ad2e">TRI</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### insertCondBranchBefore() {#aa859694dc733dcc4def80843314a9666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::insertCondBranchBefore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, int NewOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a418c87b57626e29b332b6ffafca9f1af">llvm::MachineFunction::CreateMachineInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a5fb1acb0aa530c8e3ba68748469a34ee">SHOWNEWINSTR</a> and <a href="#a2c715c7f8205486cf9debd5cce6d8088">TII</a>.</p>


<p>Referenced by <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a>, <a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a>, <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### insertCondBranchBefore() {#a8935966af7f8278bc5aa4efe732e74f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::insertCondBranchBefore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, int NewOpcode, int RegNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="#a41dd7655c0a468a74784440f2a65bdb8">addDummyExitBlock</a>, <a href="#a3312930671bb8ba4a3e685149c8f4e43">clone</a>, <a href="#a8945ac962ff2d369b77ff9ab927529a4">cloneBlockForPredecessor</a>, <a href="#ab90cb03c7501b031fa63735cc9391a5f">cloneOnSideEntryTo</a>, <a href="#a1e5698213d6d250e814ed909311751be">cloneSuccessorList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a49ab69e09d83cb77901ff2d50f6d24e3">getBranchNzeroOpcode</a>, <a href="#a2b1031662a9845abf2a38a9c72ba50ad">getBranchZeroOpcode</a>, <a href="#a35eea839c370d75908b9948a7c967c09">getContinueNzeroOpcode</a>, <a href="#a5e8275e1cc93bf70e016f77edcf56eb4">getContinueZeroOpcode</a>, <a href="#a812611158870a1016b5b51a1aed54862">getFalseBranch</a>, <a href="#ada4e796f7259afad7cc9a7d24a8720ae">getLastDebugLocInBB</a>, <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="#a7310f956774ef6e2886820c1120b5727">getNormalBlockBranchInstr</a>, <a href="#a5c91f131b10e9fe99f49069a1f725e19">getReturnInstr</a>, <a href="#a8b50498b11eadf18d8de24481deae37e">getTrueBranch</a>, <a href="#a15e59431f88bf9267aa3917ed77527a5">handleJumpintoIf</a>, <a href="#a3d20136077641cd8689ad93587230228">handleJumpintoIfImp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a>, <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a>, <a href="#ad7c192b3a055baeefd28beb0ab1cfbfd">isReturnBlock</a>, <a href="#a34c501f2f094f555ee3dbe0a1970d300">isSameloopDetachedContbreak</a>, <a href="#ae53aaaaa28342f1e9a4c82022818afab">isUncondBranch</a>, <a href="#a7df2f5237587b9555efb489278d3b73d">loopendPatternMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a>, <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a>, <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a>, <a href="#ab38ab4f331b754f58147aaa7a86febb1">mergeLooplandBlock</a>, <a href="#a5fec9aab7a2ff820c3c372f3cda87c25">mergeSerialBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a34b11aa12929fbf594b75074a35dc9c2">migrateInstruction</a>, <a href="#a43d3fe2699745c950168939ee8f0d5cb">normalizeInfiniteLoopExit</a>, <a href="#aaa148c60a3af1c31e9b15172889ef665">patternMatch</a>, <a href="#a053aad9dc034ec2f71167e05ec1800f5">patternMatchGroup</a>, <a href="#aac1bbcd1976f0888cd8084dddc59fb3c">recordSccnum</a>, <a href="#ac9608ee656bad26eae3b7188510f43d1">removeRedundantConditionalBranch</a>, <a href="#a768d00a2a1c079d1da7719341caadd1a">removeSuccessor</a>, <a href="#a892f776a360693f609ef055a45a6f6a8">removeUnconditionalBranch</a>, <a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">replaceInstrUseOfBlockWith</a>, <a href="#ab16b8b98cfbc579a4227f3f79bcfef44">retireBlock</a>, <a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a>, <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>, <a href="#a74f6a458f01fa327f1acfac4d97dd252">setTrueBranch</a>, <a href="#ac471c55917cb9e3fdc7674e300260d9f">showImproveSimpleJumpintoIf</a> and <a href="#a23b20ed1597d31f0d73ce282f0db4db6">wrapup</a>.</p>

</div>
</div>

### insertInstrBefore() {#a0bdc8239201deba8ba0b0520cd7206cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600MachineCFGStructurizer::insertInstrBefore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, int NewOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL=<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>())</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a5fb1acb0aa530c8e3ba68748469a34ee">SHOWNEWINSTR</a> and <a href="#a2c715c7f8205486cf9debd5cce6d8088">TII</a>.</p>


<p>Referenced by <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a>, <a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a>, <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a> and <a href="#ab38ab4f331b754f58147aaa7a86febb1">mergeLooplandBlock</a>.</p>

</div>
</div>

### insertInstrBefore() {#a4eb10bbe55466736b6d97ce923f4c973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600MachineCFGStructurizer::insertInstrBefore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, int NewOpcode)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a5fb1acb0aa530c8e3ba68748469a34ee">SHOWNEWINSTR</a> and <a href="#a2c715c7f8205486cf9debd5cce6d8088">TII</a>.</p>

</div>
</div>

### insertInstrEnd() {#aebef2fa97bc3b381ec5e9cb8c82abcd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::insertInstrEnd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, int NewOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL=<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>())</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a5fb1acb0aa530c8e3ba68748469a34ee">SHOWNEWINSTR</a> and <a href="#a2c715c7f8205486cf9debd5cce6d8088">TII</a>.</p>


<p>Referenced by <a href="#a41dd7655c0a468a74784440f2a65bdb8">addDummyExitBlock</a>, <a href="#ab38ab4f331b754f58147aaa7a86febb1">mergeLooplandBlock</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### isActiveLoophead() {#a68fba9e05f782a97df84dff26ef5abfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::isActiveLoophead (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="#a611142121c7c2f7505e490784ac949b1">getLoopLandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="#aaaf95e3d94f7d3fdaa233d736db960b6">isRetiredBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>.</p>


<p>Referenced by <a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a>.</p>

</div>
</div>

### isRetiredBlock() {#aaaf95e3d94f7d3fdaa233d736db960b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::isRetiredBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#abb8cab61cc41f1322ee1747504d3dff9">countActiveBlock</a>, <a href="#a68fba9e05f782a97df84dff26ef5abfa">isActiveLoophead</a> and <a href="#a5e759f21490690f9162f74e250d73857">run</a>.</p>

</div>
</div>

### isSameloopDetachedContbreak() {#a34c501f2f094f555ee3dbe0a1970d300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::isSameloopDetachedContbreak (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src1MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src2MBB)</td>
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

<p>return true iff src1Blk-&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a126a78caf2176eb39d879c899bdd749c">succ_empty()</a> &amp;&amp; src1Blk and src2Blk are in the same loop with LoopLandInfo without explicitly keeping track of loopContBlks and loopBreakBlks, this is a method to get the information.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa8d1d8d88835b75b05b14ab774785e8a">llvm::MachineBasicBlock::succ_empty</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### loopendPatternMatch() {#a7df2f5237587b9555efb489278d3b73d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::loopendPatternMatch ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a> and <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a053aad9dc034ec2f71167e05ec1800f5">patternMatchGroup</a>.</p>

</div>
</div>

### mergeIfthenelseBlock() {#aa76d1bb8a35c5fe0c9c22df9cc0dba10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::mergeIfthenelseBlock (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * BranchMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TrueMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FalseMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LandMBB)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="#a49ab69e09d83cb77901ff2d50f6d24e3">getBranchNzeroOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa859694dc733dcc4def80843314a9666">insertCondBranchBefore</a>, <a href="#a0bdc8239201deba8ba0b0520cd7206cb">insertInstrBefore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7114bb360b922025e7a4fec442676db">llvm::MachineBasicBlock::removeSuccessor</a>, <a href="#ab16b8b98cfbc579a4227f3f79bcfef44">retireBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa8d1d8d88835b75b05b14ab774785e8a">llvm::MachineBasicBlock::succ_empty</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### mergeLoop() {#a6277ecb456c87743b292a5dd69542a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::mergeLoop (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * LoopRep)</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1d9238c61483c12dce660bae4c8cc2d2">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a46880fab7a9d5bd439725f2acc59b80d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a>, <a href="#ab38ab4f331b754f58147aaa7a86febb1">mergeLooplandBlock</a>, <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a>, <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a7df2f5237587b9555efb489278d3b73d">loopendPatternMatch</a>.</p>

</div>
</div>

### mergeLoopbreakBlock() {#ac1a085b3eb182136b9d98a7d6916421f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::mergeLoopbreakBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ExitingMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LandMBB)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a8b50498b11eadf18d8de24481deae37e">getTrueBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa859694dc733dcc4def80843314a9666">insertCondBranchBefore</a>, <a href="#a0bdc8239201deba8ba0b0520cd7206cb">insertInstrBefore</a>, <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7114bb360b922025e7a4fec442676db">llvm::MachineBasicBlock::removeSuccessor</a> and <a href="#ac39887a32773197d7e0b998204868263">reversePredicateSetter</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a>.</p>

</div>
</div>

### mergeLooplandBlock() {#ab38ab4f331b754f58147aaa7a86febb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::mergeLooplandBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LandMBB)</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a0bdc8239201deba8ba0b0520cd7206cb">insertInstrBefore</a>, <a href="#aebef2fa97bc3b381ec5e9cb8c82abcd5">insertInstrEnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a2d4703c258359175d1c7840735bd77b6">llvm::MachineBasicBlock::replaceSuccessor</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a>.</p>

</div>
</div>

### mergeSerialBlock() {#a5fec9aab7a2ff820c3c372f3cda87c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::mergeSerialBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SrcMBB)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="#a1e5698213d6d250e814ed909311751be">cloneSuccessorList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ae8b61445c5e090342270032cf9447b67">MLI</a>, <a href="#a768d00a2a1c079d1da7719341caadd1a">removeSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7114bb360b922025e7a4fec442676db">llvm::MachineBasicBlock::removeSuccessor</a>, <a href="#ab16b8b98cfbc579a4227f3f79bcfef44">retireBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a>.</p>

</div>
</div>

### migrateInstruction() {#a34b11aa12929fbf594b75074a35dc9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::migrateInstruction (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SrcMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="#a7310f956774ef6e2886820c1120b5727">getNormalBlockBranchInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adbff55f335d303816547f35eb6edb948">llvm::MachineBasicBlock::size</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>.</p>


<p>Referenced by <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### needMigrateBlock() {#a45a901c595cf2030662702d96c1ae1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::needMigrateBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a>.</p>

</div>
</div>

### normalizeInfiniteLoopExit() {#a43d3fe2699745c950168939ee8f0d5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * R600MachineCFGStructurizer::normalizeInfiniteLoopExit (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * LoopRep)</td>
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

<p>normalizeInfiniteLoopExit change B1: uncond_br LoopHeader</p>


<p>to B1: cond_br 1 LoopHeader dummyExit and return the newly added dummy exit block</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a4447dfc5ac5a8784a0a933a5be56bbf5">llvm::LLVMContext::emitError</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="#ae53aaaaa28342f1e9a4c82022818afab">isUncondBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3b1dce1f3354a357fb9061bb7568a84e">llvm::MachineBasicBlock::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a0e4b8f56e1248ac6f0c93ab1212ed99c">SHOWNEWBLK</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a0804b0846b504f0556a8085204f1127b">prepare</a>.</p>

</div>
</div>

### orderBlocks() {#a75612e4710d7d73f6df2086ffc21334a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::orderBlocks (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Compute the reversed DFS post order of Blocks.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a2ebb54e025596f580bf6d56712a574a1">getSCCNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#ad097d7496ddf0db2c2d2e34bdbe4d2e9">INVALIDSCCNUM</a>, <a href="/web-llvm/docs/api/classes/llvm/scc-iterator/#a7d6ec03718a5e48f3ec7ce22fefcb91d">llvm::scc_iterator&lt; GraphT, GT &gt;::isAtEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#aaa253dd3e56c37edd403113782c0ef94">nodes</a>, <a href="#aac1bbcd1976f0888cd8084dddc59fb3c">recordSccnum</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3c1a67796e24a843db8a6766baa54c21">llvm::scc_begin</a>.</p>


<p>Referenced by <a href="#a0804b0846b504f0556a8085204f1127b">prepare</a>.</p>

</div>
</div>

### patternMatch() {#aaa148c60a3af1c31e9b15172889ef665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::patternMatch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a053aad9dc034ec2f71167e05ec1800f5">patternMatchGroup</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a5e759f21490690f9162f74e250d73857">run</a>.</p>

</div>
</div>

### patternMatchGroup() {#a053aad9dc034ec2f71167e05ec1800f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::patternMatchGroup (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#a7df2f5237587b9555efb489278d3b73d">loopendPatternMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a2252dc7a91adc7d24397a4dddc25d3a6">serialPatternMatch</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#aaa148c60a3af1c31e9b15172889ef665">patternMatch</a>.</p>

</div>
</div>

### printOrderedBlocks() {#a5d11407984f3a71442a04a5e619b6524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::printOrderedBlocks ()</td>
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

<p>Print the ordered Blocks.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a2ebb54e025596f580bf6d56712a574a1">getSCCNum</a>.</p>


<p>Referenced by <a href="#a5e759f21490690f9162f74e250d73857">run</a>.</p>

</div>
</div>

### recordSccnum() {#aac1bbcd1976f0888cd8084dddc59fb3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::recordSccnum (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, int SCCNum)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/blockinformation/#aae5f8a8ceae57d057e0e78c2b7730ccc">anonymous{R600MachineCFGStructurizer.cpp}::BlockInformation::BlockInformation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/blockinformation/#a5b1c3862ed2aa5027ac5945ef2ddc12d">anonymous{R600MachineCFGStructurizer.cpp}::BlockInformation::SccNum</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a75612e4710d7d73f6df2086ffc21334a">orderBlocks</a>.</p>

</div>
</div>

### removeRedundantConditionalBranch() {#ac9608ee656bad26eae3b7188510f43d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::removeRedundantConditionalBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Remove duplicate branches instructions in a block.</p>


<p>For instance B0: cond_br X B1 B2 cond_br X B1 B2 is transformed to B0: cond_br X B1 B2</p>


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="#a7310f956774ef6e2886820c1120b5727">getNormalBlockBranchInstr</a>, <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp/#a0e4b8f56e1248ac6f0c93ab1212ed99c">SHOWNEWBLK</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a0804b0846b504f0556a8085204f1127b">prepare</a>.</p>

</div>
</div>

### removeSuccessor() {#a768d00a2a1c079d1da7719341caadd1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::removeSuccessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a5fec9aab7a2ff820c3c372f3cda87c25">mergeSerialBlock</a>.</p>

</div>
</div>

### removeUnconditionalBranch() {#a892f776a360693f609ef055a45a6f6a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::removeUnconditionalBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="#ae53aaaaa28342f1e9a4c82022818afab">isUncondBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a0804b0846b504f0556a8085204f1127b">prepare</a>.</p>

</div>
</div>

### replaceInstrUseOfBlockWith() {#a22c318a4aa3dc68ab17ce5256d7e2a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::replaceInstrUseOfBlockWith (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SrcMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * OldMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBlk)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab9a54fdc7456ee97cb54ff30d625b6b7">MachineBasicBlock::ReplaceUsesOfBlockWith</a> doesn't serve the purpose because the <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> instruction is not recognized as terminator fix this and retire this routine.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="#a8b50498b11eadf18d8de24481deae37e">getTrueBranch</a>, <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a> and <a href="#a74f6a458f01fa327f1acfac4d97dd252">setTrueBranch</a>.</p>


<p>Referenced by <a href="#a8945ac962ff2d369b77ff9ab927529a4">cloneBlockForPredecessor</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### retireBlock() {#ab16b8b98cfbc579a4227f3f79bcfef44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::retireBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/blockinformation/#aae5f8a8ceae57d057e0e78c2b7730ccc">anonymous{R600MachineCFGStructurizer.cpp}::BlockInformation::BlockInformation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/blockinformation/#a395a2178c83128bca1d4ecbf5493484e">anonymous{R600MachineCFGStructurizer.cpp}::BlockInformation::IsRetired</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a> and <a href="#a5fec9aab7a2ff820c3c372f3cda87c25">mergeSerialBlock</a>.</p>

</div>
</div>

### reversePredicateSetter() {#ac39887a32773197d7e0b998204868263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::reversePredicateSetter (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> and <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a>.</p>

</div>
</div>

### serialPatternMatch() {#a2252dc7a91adc7d24397a4dddc25d3a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::serialPatternMatch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="#a68fba9e05f782a97df84dff26ef5abfa">isActiveLoophead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a5fec9aab7a2ff820c3c372f3cda87c25">mergeSerialBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>.</p>


<p>Referenced by <a href="#a3d20136077641cd8689ad93587230228">handleJumpintoIfImp</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a> and <a href="#a053aad9dc034ec2f71167e05ec1800f5">patternMatchGroup</a>.</p>

</div>
</div>

### settleLoopcontBlock() {#a484a24399c195bf93535e18192b7cc94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::settleLoopcontBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ContingMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ContMBB)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a49ab69e09d83cb77901ff2d50f6d24e3">getBranchNzeroOpcode</a>, <a href="#a2b1031662a9845abf2a38a9c72ba50ad">getBranchZeroOpcode</a>, <a href="#a35eea839c370d75908b9948a7c967c09">getContinueNzeroOpcode</a>, <a href="#a5e8275e1cc93bf70e016f77edcf56eb4">getContinueZeroOpcode</a>, <a href="#ada4e796f7259afad7cc9a7d24a8720ae">getLastDebugLocInBB</a>, <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a8b50498b11eadf18d8de24481deae37e">getTrueBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa859694dc733dcc4def80843314a9666">insertCondBranchBefore</a>, <a href="#aebef2fa97bc3b381ec5e9cb8c82abcd5">insertInstrEnd</a>, <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad8c9657cfb03ef2ebf6364ba9d68c127">llvm::MachineBasicBlock::rbegin</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a>.</p>

</div>
</div>

### showImproveSimpleJumpintoIf() {#ac471c55917cb9e3fdc7674e300260d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::showImproveSimpleJumpintoIf (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * HeadMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TrueMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FalseMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LandMBB, bool Detail=false)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab3b62258d9bd41595674de878f37f8d8">llvm::MachineBasicBlock::print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adbff55f335d303816547f35eb6edb948">llvm::MachineBasicBlock::size</a>.</p>


<p>Referenced by <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### singlePathTo() {#ac393ff87a496a67dae4ba9430b816263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R600MachineCFGStructurizer::PathToKind R600MachineCFGStructurizer::singlePathTo (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SrcMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB, bool AllowSideEntry=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a71749ba4b31c340ca06fe1bab875d798aa47fdb9a1e206a39e39dc57375a0d32b">Not_SinglePath</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="#a71749ba4b31c340ca06fe1bab875d798a63fed8fc4b455c2f92fdfb0011901cb7">SinglePath_InPath</a>, <a href="#a71749ba4b31c340ca06fe1bab875d798a9be6a253bf8ef1967089447de889c4e1">SinglePath_NotInPath</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>.</p>


<p>Referenced by <a href="#a3d20136077641cd8689ad93587230228">handleJumpintoIfImp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MDT {#a3824f7a9afb2ff602a01b2a0c11318cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::MDT</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Referenced by <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a>.</p>

</div>
</div>

### MLI {#ae8b61445c5e090342270032cf9447b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::MLI</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Referenced by <a href="#abad1ad05191dcc842acb7c84422494a5">hasBackEdge</a>, <a href="#a68fba9e05f782a97df84dff26ef5abfa">isActiveLoophead</a>, <a href="#a34c501f2f094f555ee3dbe0a1970d300">isSameloopDetachedContbreak</a>, <a href="#a7df2f5237587b9555efb489278d3b73d">loopendPatternMatch</a>, <a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a>, <a href="#a6277ecb456c87743b292a5dd69542a4e">mergeLoop</a>, <a href="#a5fec9aab7a2ff820c3c372f3cda87c25">mergeSerialBlock</a>, <a href="#a0804b0846b504f0556a8085204f1127b">prepare</a> and <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a>.</p>

</div>
</div>

### PDT {#af3599a755479b17015844a0b485c648c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePostDominatorTree* anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::PDT</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Referenced by <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a>.</p>

</div>
</div>

### TII {#a2c715c7f8205486cf9debd5cce6d8088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600InstrInfo* anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::TII = nullptr</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Referenced by <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="#aa859694dc733dcc4def80843314a9666">insertCondBranchBefore</a>, <a href="#a0bdc8239201deba8ba0b0520cd7206cb">insertInstrBefore</a>, <a href="#a4eb10bbe55466736b6d97ce923f4c973">insertInstrBefore</a>, <a href="#aebef2fa97bc3b381ec5e9cb8c82abcd5">insertInstrEnd</a> and <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a>.</p>

</div>
</div>

### TRI {#abc03d00e143160f0abceb251a028ad2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600RegisterInfo* anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::TRI = nullptr</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Referenced by <a href="#ae27fd47ee099b4aba7fe2bc84be97ff8">improveSimpleJumpintoIf</a> and <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockInfoMap {#a516d256022db88eb0404520c832d3be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBInfoMap anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::BlockInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

### FuncRep {#a1d16c576c8dffadc466326d8f39f4f60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::FuncRep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

### LLInfoMap {#abf7d333061ecb2204e2edaa6e93edc67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopLandInfoMap anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::LLInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

### OrderedBlks {#af6079c7b25f387791bb85d4c59c64498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, DEFAULT_VEC_SLOTS&gt; anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::OrderedBlks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

### Visited {#a1ae2140b9584026c0e1dbeed1226fb53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;MachineLoop *, bool&gt; anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### clone() {#a3312930671bb8ba4a3e685149c8f4e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * R600MachineCFGStructurizer::clone (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3b1dce1f3354a357fb9061bb7568a84e">llvm::MachineBasicBlock::push_back</a>.</p>


<p>Referenced by <a href="#a8945ac962ff2d369b77ff9ab927529a4">cloneBlockForPredecessor</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### cloneSuccessorList() {#a1e5698213d6d250e814ed909311751be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::cloneSuccessorList (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SrcMBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a>.</p>


<p>Referenced by <a href="#a8945ac962ff2d369b77ff9ab927529a4">cloneBlockForPredecessor</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a5fec9aab7a2ff820c3c372f3cda87c25">mergeSerialBlock</a>.</p>

</div>
</div>

### getBranchNzeroOpcode() {#a49ab69e09d83cb77901ff2d50f6d24e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::getBranchNzeroOpcode (int OldOpcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#aa76d1bb8a35c5fe0c9c22df9cc0dba10">mergeIfthenelseBlock</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### getBranchZeroOpcode() {#a2b1031662a9845abf2a38a9c72ba50ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::getBranchZeroOpcode (int OldOpcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### getContinueNzeroOpcode() {#a35eea839c370d75908b9948a7c967c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::getContinueNzeroOpcode (int OldOpcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### getContinueZeroOpcode() {#a5e8275e1cc93bf70e016f77edcf56eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600MachineCFGStructurizer::getContinueZeroOpcode (int OldOpcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### getFalseBranch() {#a812611158870a1016b5b51a1aed54862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * R600MachineCFGStructurizer::getFalseBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8b50498b11eadf18d8de24481deae37e">getTrueBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a> and <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>.</p>

</div>
</div>

### getLastDebugLocInBB() {#ada4e796f7259afad7cc9a7d24a8720ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc R600MachineCFGStructurizer::getLastDebugLocInBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### getNormalBlockBranchInstr() {#a7310f956774ef6e2886820c1120b5727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600MachineCFGStructurizer::getNormalBlockBranchInstr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="#a65114ce8a8a940710f0ef9ce76c8498f">isCondBranch</a>, <a href="#ae53aaaaa28342f1e9a4c82022818afab">isUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#a34b11aa12929fbf594b75074a35dc9c2">migrateInstruction</a> and <a href="#ac9608ee656bad26eae3b7188510f43d1">removeRedundantConditionalBranch</a>.</p>

</div>
</div>

### getReturnInstr() {#a5c91f131b10e9fe99f49069a1f725e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600MachineCFGStructurizer::getReturnInstr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a8e818224d2d1de9b995783ff897b0083af12bc59169afda2918e9f23e3501c2b6">instr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a41dd7655c0a468a74784440f2a65bdb8">addDummyExitBlock</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#ad7c192b3a055baeefd28beb0ab1cfbfd">isReturnBlock</a>.</p>

</div>
</div>

### getTrueBranch() {#a8b50498b11eadf18d8de24481deae37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * R600MachineCFGStructurizer::getTrueBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a812611158870a1016b5b51a1aed54862">getFalseBranch</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a>, <a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">replaceInstrUseOfBlockWith</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### isCondBranch() {#a65114ce8a8a940710f0ef9ce76c8498f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::isCondBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="#a7310f956774ef6e2886820c1120b5727">getNormalBlockBranchInstr</a>, <a href="#a55b3f01e91f974764d18a95d9e4b7ec5">ifPatternMatch</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#ac1a085b3eb182136b9d98a7d6916421f">mergeLoopbreakBlock</a>, <a href="#ac9608ee656bad26eae3b7188510f43d1">removeRedundantConditionalBranch</a>, <a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">replaceInstrUseOfBlockWith</a> and <a href="#a484a24399c195bf93535e18192b7cc94">settleLoopcontBlock</a>.</p>

</div>
</div>

### isReturnBlock() {#ad7c192b3a055baeefd28beb0ab1cfbfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::isReturnBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5c91f131b10e9fe99f49069a1f725e19">getReturnInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a0804b0846b504f0556a8085204f1127b">prepare</a>.</p>

</div>
</div>

### isUncondBranch() {#ae53aaaaa28342f1e9a4c82022818afab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600MachineCFGStructurizer::isUncondBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a1e5913a75e260c91dab2c7edcb71868a">getLoopendBlockBranchInstr</a>, <a href="#a7310f956774ef6e2886820c1120b5727">getNormalBlockBranchInstr</a>, <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a>, <a href="#a43d3fe2699745c950168939ee8f0d5cb">normalizeInfiniteLoopExit</a> and <a href="#a892f776a360693f609ef055a45a6f6a8">removeUnconditionalBranch</a>.</p>

</div>
</div>

### PrintLoopinfo() {#a7d385e0a55206f23f585f4bd59934224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::PrintLoopinfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; LoopInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>


<p>Referenced by <a href="#a18192ed7893e8738ddd38e7f75bb3bf7">runOnMachineFunction</a>.</p>

</div>
</div>

### setTrueBranch() {#a74f6a458f01fa327f1acfac4d97dd252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::setTrueBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a22c318a4aa3dc68ab17ce5256d7e2a28">replaceInstrUseOfBlockWith</a>.</p>

</div>
</div>

### wrapup() {#a23b20ed1597d31f0d73ce282f0db4db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600MachineCFGStructurizer::wrapup (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a8935966af7f8278bc5aa4efe732e74f7">insertCondBranchBefore</a> and <a href="#a5e759f21490690f9162f74e250d73857">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a9b6ffaab1cd70c950b35d0c83850476f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char R600MachineCFGStructurizer::ID = 0</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a>.</p>


<p>Referenced by <a href="#a998f23f119e9621929d4b4733038330c">R600MachineCFGStructurizer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600machinecfgstructurizer-cpp">R600MachineCFGStructurizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
