---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/branchfolder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BranchFolder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::BranchFolder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">CodeGen/BranchFolding.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5032dc7ee5f0a594dbf9665be3800b8e">MPIterator</a> = std::vector&lt; MergePotentialsElt &gt;::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1adbbf741128687beee153521c3318">BranchFolder</a> (bool DefaultEnableTailMerge, bool CommonHoist, MBFIWrapper &amp;FreqInfo, const MachineBranchProbabilityInfo &amp;ProbInfo, ProfileSummaryInfo *PSI, unsigned MinTailLength=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d50fee4d0d41ccf591e29de109786f">OptimizeFunction</a> (MachineFunction &amp;MF, const TargetInstrInfo *tii, const TargetRegisterInfo *tri, MachineLoopInfo *mli=nullptr, bool AfterPlacement=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perhaps branch folding, tail merging and other CFG optimizations on the given function. <a href="#aa0d50fee4d0d41ccf591e29de109786f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95bc0bb858b1c2a366d7f274b6144af2">TailMergeBlocks</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324d73f3fb0c08e1ee7d4f8e75df3762">TryTailMergeBlocks</a> (MachineBasicBlock *SuccBB, MachineBasicBlock *PredBB, unsigned MinCommonTailLength)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0235e11af8de64dd309b3752244556c2">setCommonTailEdgeWeights</a> (MachineBasicBlock &amp;TailMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa136ca23fe4f7556c93c9c94ab9c2ab4">replaceTailWithBranchTo</a> (MachineBasicBlock::iterator OldInst, MachineBasicBlock &amp;NewDest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the instruction OldInst and everything after it, replacing it with an unconditional branch to NewDest. <a href="#aa136ca23fe4f7556c93c9c94ab9c2ab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099fe69a19df662adcc320a2f261cda5">SplitMBBAt</a> (MachineBasicBlock &amp;CurMBB, MachineBasicBlock::iterator BBI1, const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a machine basic block and an iterator into it, split the MBB so that the part before the iterator falls into the part starting at the iterator. <a href="#a099fe69a19df662adcc320a2f261cda5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad186c4ee71ad0df3a205364aa9165cb6">ComputeSameTails</a> (unsigned CurHash, unsigned minCommonTailLength, MachineBasicBlock *SuccBB, MachineBasicBlock *PredBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look through all the blocks in MergePotentials that have hash CurHash (guaranteed to match the last element). <a href="#ad186c4ee71ad0df3a205364aa9165cb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa508be704409a874b2f10484764b228b">RemoveBlocksWithHash</a> (unsigned CurHash, MachineBasicBlock *SuccBB, MachineBasicBlock *PredBB, const DebugLoc &amp;BranchDL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all blocks with hash CurHash from MergePotentials, restoring branches at ends of blocks as appropriate. <a href="#aa508be704409a874b2f10484764b228b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e7b78443bf2ff7fcc0063e11db34a1">CreateCommonTailOnlyBlock</a> (MachineBasicBlock *&amp;PredBB, MachineBasicBlock *SuccBB, unsigned maxCommonTailLength, unsigned &amp;commonTailIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>None of the blocks to be tail-merged consist only of the common tail. <a href="#ae1e7b78443bf2ff7fcc0063e11db34a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7300d213b9cfcf8b11c8e733848e4b">mergeCommonTails</a> (unsigned commonTailIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create merged DebugLocs of identical instructions across SameTails and assign it to the instruction in common tail; merge MMOs and undef flags. <a href="#a7c7300d213b9cfcf8b11c8e733848e4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049e89ea0f4677d14ac181d3f6b2785c">OptimizeBranches</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4d278656e7fa6ad21f02e32e99e577">OptimizeBlock</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze and optimize control flow related to the specified block. <a href="#aba4d278656e7fa6ad21f02e32e99e577">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9014a13a9c23df95aa56bc094f80a8c9">RemoveDeadBlock</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified dead machine basic block from the function, updating the CFG. <a href="#a9014a13a9c23df95aa56bc094f80a8c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c32a92b590c0414b041cabe00a4cbb0">HoistCommonCode</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hoist common instruction sequences at the start of basic blocks to their common predecessor. <a href="#a1c32a92b590c0414b041cabe00a4cbb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba24911a0f7e8ee167b8e3816ca453d">HoistCommonCodeInSuccs</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the successors of MBB has common instruction sequence at the start of the function, move the instructions before MBB terminator if it's legal. <a href="#a2ba24911a0f7e8ee167b8e3816ca453d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; MergePotentialsElt &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e878e98e6d772cf2ef21e14fab45971">MergePotentials</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32313ebde0d0b7162a90b12628b06f4">TriedMerging</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb3393226355ff1b329201a85efaf0b">EHScopeMembership</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; SameTailElt &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a7b562e71ba28a15b2f1f2251f97fb">SameTails</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc7c24ca698713b244575ba86706943">AfterBlockPlacement</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3567149b3e5bac53145d96a4f4dff59">EnableTailMerge</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae08d297cc6c155672a598262a82ba4c1">EnableHoistCommonCode</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b2c94b73b04f035d97a21fb8166449">UpdateLiveIns</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185d3d72e3f7a90feb89e80d07ea70b4">MinCommonTailLength</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa353388470cfc66ce071957127dbea">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041332df6a0e5853c3a48f3af99e01b4">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a374176ed65c181b7123ff067bbf804ab">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb059989dc36c036444abed798df0985">MLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livephysregs">LivePhysRegs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765b1ca67a35c2d5615b1aabb12cfc59">LiveRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mbfiwrapper">MBFIWrapper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7940dc05a7fc28d9766dc76596d373">MBBFreqInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c00280b2372faa4703acd48510cb787">MBPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937f91fc3784941c5c5393146bef4b27">PSI</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MPIterator {#a5032dc7ee5f0a594dbf9665be3800b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BranchFolder::MPIterator =  std::vector&lt;MergePotentialsElt&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BranchFolder() {#acd1adbbf741128687beee153521c3318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchFolder::BranchFolder (bool DefaultEnableTailMerge, bool CommonHoist, <a href="/web-llvm/docs/api/classes/llvm/mbfiwrapper">MBFIWrapper</a> &amp; FreqInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> &amp; ProbInfo, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, unsigned MinTailLength=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44a4e55599a5b5277382b14e6e8eb1f63ef">llvm::cl::BOU_FALSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44ad7c4bd83c337c86d34f6c2d8eba1e736">llvm::cl::BOU_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a6b557e923cdf31251289c0e07e382143">FlagEnableTailMerge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### OptimizeFunction() {#aa0d50fee4d0d41ccf591e29de109786f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::OptimizeFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * tii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * tri, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> * mli=nullptr, bool AfterPlacement=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perhaps branch folding, tail merging and other CFG optimizations on the given function.</p>


<p>Block placement changes the layout and may create new tail merging opportunities.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afa141935f9c9a1ad9c785d7b6200b119">llvm::getEHScopeMembership</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad828deab7de3b5f4d03fac86e26adae9">llvm::MachineFunction::getJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#af9c60f4a0193375a5dd205fb945107a8">llvm::MachineJumpTableInfo::getJumpTables</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#a4884f00bcde9528a64e1c18adc789641">llvm::MachineJumpTableInfo::RemoveJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#abf86e1383aec181a5a2d9967eb8070fd">llvm::BitVector::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a73423bf857429f170a6355ae20e1d798">TailMergeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a> and <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a218bf4a49a8808ebb854ec9b89907904">llvm::MachineRegisterInfo::tracksLiveness</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a504736d0c95e44bc01df5707be6f7ab7">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-ifconversion-cpp-/ifconverter/#abff4179252123a7710b2fa134be3f9d6">anonymous{IfConversion.cpp}::IfConverter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ComputeSameTails() {#ad186c4ee71ad0df3a205364aa9165cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BranchFolder::ComputeSameTails (unsigned CurHash, unsigned minCommonTailLength, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PredBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look through all the blocks in MergePotentials that have hash CurHash (guaranteed to match the last element).</p>


<p>Build the vector SameTails of all those that have the (same) largest number of instructions in common of any pair of these blocks. SameTails entries contain an iterator into MergePotentials (from which the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> can be found) and a <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> into that MBB indicating the instruction where the matching code sequence begins. Order of elements in SameTails is the reverse of the order in which those blocks appear in MergePotentials (where they are not necessarily consecutive).</p>


<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### CreateCommonTailOnlyBlock() {#ae1e7b78443bf2ff7fcc0063e11db34a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::CreateCommonTailOnlyBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; PredBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccBB, unsigned maxCommonTailLength, unsigned &amp; commonTailIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>None of the blocks to be tail-merged consist only of the common tail.</p>


<p>Create a block that does by splitting one.</p>


<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### HoistCommonCode() {#a1c32a92b590c0414b041cabe00a4cbb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::HoistCommonCode (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hoist common instruction sequences at the start of basic blocks to their common predecessor.</p>

<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 1779 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### HoistCommonCodeInSuccs() {#a2ba24911a0f7e8ee167b8e3816ca453d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::HoistCommonCodeInSuccs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the successors of MBB has common instruction sequence at the start of the function, move the instructions before MBB terminator if it's legal.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### mergeCommonTails() {#a7c7300d213b9cfcf8b11c8e733848e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchFolder::mergeCommonTails (unsigned commonTailIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create merged DebugLocs of identical instructions across SameTails and assign it to the instruction in common tail; merge MMOs and undef flags.</p>

<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 810 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### OptimizeBlock() {#aba4d278656e7fa6ad21f02e32e99e577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::OptimizeBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze and optimize control flow related to the specified block.</p>


<p>This is never called on the entry block.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### OptimizeBranches() {#a049e89ea0f4677d14ac181d3f6b2785c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::OptimizeBranches (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### RemoveBlocksWithHash() {#aa508be704409a874b2f10484764b228b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchFolder::RemoveBlocksWithHash (unsigned CurHash, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; BranchDL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all blocks with hash CurHash from MergePotentials, restoring branches at ends of blocks as appropriate.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### RemoveDeadBlock() {#a9014a13a9c23df95aa56bc094f80a8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchFolder::RemoveDeadBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified dead machine basic block from the function, updating the CFG.</p>

<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### replaceTailWithBranchTo() {#aa136ca23fe4f7556c93c9c94ab9c2ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchFolder::replaceTailWithBranchTo (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> OldInst, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; NewDest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete the instruction OldInst and everything after it, replacing it with an unconditional branch to NewDest.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### setCommonTailEdgeWeights() {#a0235e11af8de64dd309b3752244556c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchFolder::setCommonTailEdgeWeights (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TailMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### SplitMBBAt() {#a099fe69a19df662adcc320a2f261cda5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * BranchFolder::SplitMBBAt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; CurMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> BBI1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a machine basic block and an iterator into it, split the MBB so that the part before the iterator falls into the part starting at the iterator.</p>


<p>This returns the new MBB.</p>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### TailMergeBlocks() {#a95bc0bb858b1c2a366d7f274b6144af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::TailMergeBlocks (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

### TryTailMergeBlocks() {#a324d73f3fb0c08e1ee7d4f8e75df3762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchFolder::TryTailMergeBlocks (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PredBB, unsigned MinCommonTailLength)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>, definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AfterBlockPlacement {#a6bc7c24ca698713b244575ba86706943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchFolder::AfterBlockPlacement = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### EHScopeMembership {#a3bb3393226355ff1b329201a85efaf0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, int&gt; llvm::BranchFolder::EHScopeMembership</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### EnableHoistCommonCode {#ae08d297cc6c155672a598262a82ba4c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchFolder::EnableHoistCommonCode = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### EnableTailMerge {#aa3567149b3e5bac53145d96a4f4dff59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchFolder::EnableTailMerge = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### LiveRegs {#a765b1ca67a35c2d5615b1aabb12cfc59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LivePhysRegs llvm::BranchFolder::LiveRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### MBBFreqInfo {#a0c7940dc05a7fc28d9766dc76596d373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBFIWrapper&amp; llvm::BranchFolder::MBBFreqInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### MBPI {#a0c00280b2372faa4703acd48510cb787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo&amp; llvm::BranchFolder::MBPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### MergePotentials {#a5e878e98e6d772cf2ef21e14fab45971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MergePotentialsElt&gt; llvm::BranchFolder::MergePotentials</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### MinCommonTailLength {#a185d3d72e3f7a90feb89e80d07ea70b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BranchFolder::MinCommonTailLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### MLI {#acb059989dc36c036444abed798df0985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* llvm::BranchFolder::MLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### MRI {#a041332df6a0e5853c3a48f3af99e01b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* llvm::BranchFolder::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### PSI {#a937f91fc3784941c5c5393146bef4b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::BranchFolder::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### SameTails {#a52a7b562e71ba28a15b2f1f2251f97fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SameTailElt&gt; llvm::BranchFolder::SameTails</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### TII {#acaa353388470cfc66ce071957127dbea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::BranchFolder::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### TRI {#a374176ed65c181b7123ff067bbf804ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::BranchFolder::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### TriedMerging {#af32313ebde0d0b7162a90b12628b06f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const MachineBasicBlock*, 2&gt; llvm::BranchFolder::TriedMerging</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

### UpdateLiveIns {#a18b2c94b73b04f035d97a21fb8166449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchFolder::UpdateLiveIns = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp">BranchFolding.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
