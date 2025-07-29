---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liveintervals
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveIntervals` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LiveIntervals { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e3081cd90fed5d5de7fce572e7d764e">ShrinkToUsesWorkList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt;, 16 &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3787dc94544cbab03e18b792bb9483">LiveIntervalsAnalysis</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd0a6513ebfbd0dc547bace9e7b987c">LiveIntervalsWrapperPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a271d514325b600fdc2c97e0604850656">LiveIntervals</a> (LiveIntervals &amp;&amp;)=default</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d6df564e04ebadb068d0c97973264f">LiveIntervals</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b13b503ee826cb3304437bbeac05dfb">LiveIntervals</a> (MachineFunction &amp;MF, SlotIndexes &amp;SI, MachineDominatorTree &amp;DT)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051abd547aad728ae7aeb43f0a7b25bf">~LiveIntervals</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7006961215ea5d215922af0f7b169a13">invalidate</a> (MachineFunction &amp;MF, const PreservedAnalyses &amp;PA, MachineFunctionAnalysisManager::Invalidator &amp;Inv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd4eee1caa18a946143934b4d0220b1">getInterval</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11cd70de340f310acc70781d57a00136">hasInterval</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffbb09726d9e1a3af9ef69fcbbf0a24">createEmptyInterval</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> creation. <a href="#acffbb09726d9e1a3af9ef69fcbbf0a24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb762c1cdb87a67e41a3ba53d47ceb45">createAndComputeVirtRegInterval</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c18df693b93ed807e1d6852cc20f3e">getOrCreateEmptyInterval</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an existing interval for <span class="doxyComputerOutput">Reg</span>. <a href="#a62c18df693b93ed807e1d6852cc20f3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07c0db20cf93bf2f558d00af34a6cb6">removeInterval</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> removal. <a href="#aa07c0db20cf93bf2f558d00af34a6cb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/liverange/segment">LiveInterval::Segment</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d33d3a8e2cf3bdc2932450f90f078f">addSegmentToEndOfBlock</a> (Register Reg, MachineInstr &amp;startInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a register and an instruction, adds a live segment from that instruction to the end of its MBB. <a href="#ac3d33d3a8e2cf3bdc2932450f90f078f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7446b2819c44bf459763351b5bcc29b">shrinkToUses</a> (LiveInterval *li, SmallVectorImpl&lt; MachineInstr * &gt; *dead=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After removing some uses of a register, shrink its live range to just the remaining uses. <a href="#ac7446b2819c44bf459763351b5bcc29b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42083019e0bdb164e55da49ab9f4d717">shrinkToUses</a> (LiveInterval::SubRange &amp;SR, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of shrinkToUses(<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> <em>li, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt;<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></em>&gt; *dead) that works on a subregister live range and only looks at uses matching the lane mask of the subregister range. <a href="#a42083019e0bdb164e55da49ab9f4d717">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2333ffb94572756f96dcad39de8bbcb">extendToIndices</a> (LiveRange &amp;LR, ArrayRef&lt; SlotIndex &gt; Indices, ArrayRef&lt; SlotIndex &gt; Undefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extend the live range <span class="doxyComputerOutput">LR</span> to reach all points in <span class="doxyComputerOutput">Indices</span>. <a href="#ae2333ffb94572756f96dcad39de8bbcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60987483a38746f0d6d90dca2b65284">extendToIndices</a> (LiveRange &amp;LR, ArrayRef&lt; SlotIndex &gt; Indices)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94cf1c59ca73ea330872deb639013cb9">pruneValue</a> (LiveRange &amp;LR, SlotIndex Kill, SmallVectorImpl&lt; SlotIndex &gt; *EndPoints)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">LR</span> has a live value at <span class="doxyComputerOutput">Kill</span>, prune its live range by removing any liveness reachable from Kill. <a href="#a94cf1c59ca73ea330872deb639013cb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae927868d9b86954520b923345a3d4762">pruneValue</a> (LiveInterval &amp;, SlotIndex, SmallVectorImpl&lt; SlotIndex &gt; *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should not be used. <a href="#ae927868d9b86954520b923345a3d4762">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334e584aeef0fcf744450fdf41fe8a84">getSlotIndexes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1818a17984c50c7190464f3a04c0f3b">isNotInMIMap</a> (const MachineInstr &amp;Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified machine instr has been removed or was never entered in the map. <a href="#aa1818a17984c50c7190464f3a04c0f3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f3043b29023d270fc4bc5062dff7cee">getInstructionIndex</a> (const MachineInstr &amp;Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base index of the given instruction. <a href="#a6f3043b29023d270fc4bc5062dff7cee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1882fe2a570964e4c6abb0eac322beab">getInstructionFromIndex</a> (SlotIndex index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the instruction associated with the given index. <a href="#a1882fe2a570964e4c6abb0eac322beab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17bd0f1ec8263f735f29dd8840b7188f">getMBBStartIdx</a> (const MachineBasicBlock *mbb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first index in the given basic block. <a href="#a17bd0f1ec8263f735f29dd8840b7188f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76163707e71807054d87648aa5e00dd7">getMBBEndIdx</a> (const MachineBasicBlock *mbb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last index in the given basic block. <a href="#a76163707e71807054d87648aa5e00dd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47f5ea0e633ac96943c6937e724ae4a">isLiveInToMBB</a> (const LiveRange &amp;LR, const MachineBasicBlock *mbb) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7bb8fbc54f0001e556e3ab13a5b6ba5">isLiveOutOfMBB</a> (const LiveRange &amp;LR, const MachineBasicBlock *mbb) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3fe68c1ef3d401833b3d37cc222ead2">getMBBFromIndex</a> (SlotIndex index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6f72816801c63516c4b25f3b6544b0">insertMBBInMaps</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2035620c14bf7bdedfa4e2655f88d114">InsertMachineInstrInMaps</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b097de2261d68334195870a03412b9">InsertMachineInstrRangeInMaps</a> (MachineBasicBlock::iterator B, MachineBasicBlock::iterator E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f605751be73f0a910a586bb1b5d869">RemoveMachineInstrFromMaps</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbdfb2cc5decd8f22ea3ccc1ecea4028">ReplaceMachineInstrInMaps</a> (MachineInstr &amp;MI, MachineInstr &amp;NewMI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e3f6df25478faef0095e526847f713">getVNInfoAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cde99972870aa99be89218096b3ccf">print</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement the dump method. <a href="#ae7cde99972870aa99be89218096b3ccf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b2788f458f4763a2fa43457af4f597">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66928037b669a15589743dc46947ef0d">reanalyze</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dca6a95f0921bc90d88adfddd44e304">getDomTree</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc913cf0bab81b94548cd3c8eeb33117">intervalIsInOneMBB</a> (const LiveInterval &amp;LI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If LI is confined to a single basic block, return a pointer to that block. <a href="#abc913cf0bab81b94548cd3c8eeb33117">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6e5f6033c80dff3f9b4c6fb40499c2">hasPHIKill</a> (const LiveInterval &amp;LI, const VNInfo *VNI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if VNI is killed by any PHI-def values in LI. <a href="#a1b6e5f6033c80dff3f9b4c6fb40499c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3886e9084257e74b5db4a8951d36e0">addKillFlags</a> (const VirtRegMap *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add kill flags to any instruction that kills a virtual register. <a href="#a6e3886e9084257e74b5db4a8951d36e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d12c5a65b3940bfac7b5aa1121ac70">handleMove</a> (MachineInstr &amp;MI, bool UpdateFlags=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call this method to notify <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> that instruction <span class="doxyComputerOutput">MI</span> has been moved within a basic block. <a href="#a29d12c5a65b3940bfac7b5aa1121ac70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a6fbdf0a3311c7b9602dd67e46fef9">handleMoveIntoNewBundle</a> (MachineInstr &amp;BundleStart, bool UpdateFlags=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update intervals of operands of all instructions in the newly created bundle specified by <span class="doxyComputerOutput">BundleStart</span>. <a href="#aa1a6fbdf0a3311c7b9602dd67e46fef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, ArrayRef&lt; Register &gt; OrigRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update live intervals for instructions in a range of iterators. <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7893ae3dbb60325251e33fc093531040">getRegMaskSlots</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a sorted array of slot indices of all instructions with register mask operands. <a href="#a7893ae3dbb60325251e33fc093531040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8106d8c7d47010fe3a2201e7205ef087">getRegMaskSlotsInBlock</a> (unsigned MBBNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a sorted array of slot indices of all instructions with register mask operands in the basic block numbered <span class="doxyComputerOutput">MBBNum</span>. <a href="#a8106d8c7d47010fe3a2201e7205ef087">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dfb831efc211b21625503f9798a06fa">getRegMaskBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an array of register mask pointers corresponding to <a href="#a7893ae3dbb60325251e33fc093531040">getRegMaskSlots()</a>. <a href="#a5dfb831efc211b21625503f9798a06fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755264b66316aa1a280e5aa47ce89f2a">getRegMaskBitsInBlock</a> (unsigned MBBNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an array of mask pointers corresponding to getRegMaskSlotsInBlock(MBBNum). <a href="#a755264b66316aa1a280e5aa47ce89f2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c99fa2411ae509e9eb030f8aefb4e8">checkRegMaskInterference</a> (const LiveInterval &amp;LI, BitVector &amp;UsableRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if <span class="doxyComputerOutput">LI</span> is live across any register mask instructions, and compute a bit mask of physical registers that are not clobbered by any of them. <a href="#a26c99fa2411ae509e9eb030f8aefb4e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2ec2588cc48710e468563a0e71d24a">getRegUnit</a> (unsigned Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the live range for register unit <span class="doxyComputerOutput">Unit</span>. <a href="#a7b2ec2588cc48710e468563a0e71d24a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8158b31061f0231adcf53e160386914d">getCachedRegUnit</a> (unsigned Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the live range for register unit <span class="doxyComputerOutput">Unit</span> if it has already been computed, or nullptr if it hasn't been computed yet. <a href="#a8158b31061f0231adcf53e160386914d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b2244e53914a5143b3a89ae3afb4e4">getCachedRegUnit</a> (unsigned Unit) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac443b437e7b2899ab42f450c061dd964">removeRegUnit</a> (unsigned Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove computed live range for register unit <span class="doxyComputerOutput">Unit</span>. <a href="#ac443b437e7b2899ab42f450c061dd964">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dbecb97d916d10bb623cf46c199e0ae">removeAllRegUnitsForPhysReg</a> (MCRegister Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove associated live ranges for the register units associated with <span class="doxyComputerOutput">Reg</span>. <a href="#a0dbecb97d916d10bb623cf46c199e0ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f0ff5f13bf6cb4567247a39f7756e3">removePhysRegDefAt</a> (MCRegister Reg, SlotIndex Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove value numbers and related live segments starting at position <span class="doxyComputerOutput">Pos</span> that are part of any liverange of physical register <span class="doxyComputerOutput">Reg</span> or one of its subregisters. <a href="#ae9f0ff5f13bf6cb4567247a39f7756e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac332ca27d85adc8d21edd708be55dfe3">removeVRegDefAt</a> (LiveInterval &amp;LI, SlotIndex Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove value number and related live segments of <span class="doxyComputerOutput">LI</span> and its subranges that start at position <span class="doxyComputerOutput">Pos</span>. <a href="#ac332ca27d85adc8d21edd708be55dfe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffc1bb4ebe64a8ad3478e1253683847">splitSeparateComponents</a> (LiveInterval &amp;LI, SmallVectorImpl&lt; LiveInterval * &gt; &amp;SplitLIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split separate components in <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> <span class="doxyComputerOutput">LI</span> into separate intervals. <a href="#aeffc1bb4ebe64a8ad3478e1253683847">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a9ba0bac237cd374e2a88f9c21696f">constructMainRangeFromSubranges</a> (LiveInterval &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For live interval <span class="doxyComputerOutput">LI</span> with correct SubRanges construct matching information for the main live range. <a href="#ac7a9ba0bac237cd374e2a88f9c21696f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d6150f2c3166e88d84a8ce0cde9e1d">analyze</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06378a7903188167e2d9470e6b877723">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47691f48084ae6fba396a96c271f3d0">computeVirtRegs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute live intervals for all virtual registers. <a href="#ad47691f48084ae6fba396a96c271f3d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c918b11b7cd3403b77f10f8e7ef93f3">computeRegMasks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute RegMaskSlots and RegMaskBits. <a href="#a8c918b11b7cd3403b77f10f8e7ef93f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2cdbc3b3669b3393c03a55064e0bd68">computeDeadValues</a> (LiveInterval &amp;LI, SmallVectorImpl&lt; MachineInstr * &gt; *dead)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk the values in <span class="doxyComputerOutput">LI</span> and check for dead values: <a href="#ad2cdbc3b3669b3393c03a55064e0bd68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a429b7dee18c5e8f1b5d960fb6a43c6e7">printInstrs</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cebd21b69e072c53cf9ab88afb9ce7e">dumpInstrs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825f2b1fc1906c249dee248aace94254">computeLiveInRegUnits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Precompute the live ranges of any register units that are live-in to an ABI block somewhere. <a href="#a825f2b1fc1906c249dee248aace94254">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc456e60336939415e89abfafc29a1d4">computeRegUnitRange</a> (LiveRange &amp;, unsigned Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the live range of a register unit, based on the uses and defs of aliasing registers. <a href="#acc456e60336939415e89abfafc29a1d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a90bf719eda6cf3dccd561c6024be0f">computeVirtRegInterval</a> (LiveInterval &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the live interval of a virtual register, based on defs and uses. <a href="#a9a90bf719eda6cf3dccd561c6024be0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe33a94897b85e4da8b43633a090f344">extendSegmentsToUses</a> (LiveRange &amp;Segments, ShrinkToUsesWorkList &amp;WorkList, Register Reg, LaneBitmask LaneMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1280e184c944167b5c0660b4f4f63667">repairOldRegInRange</a> (MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, const SlotIndex endIdx, LiveRange &amp;LR, Register Reg, LaneBitmask LaneMask=LaneBitmask::getAll())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange()</a>, walks backwards and creates/modifies live segments in <span class="doxyComputerOutput">LR</span> to match the operands found. <a href="#a1280e184c944167b5c0660b4f4f63667">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f5b68a222203af313a09fad7077f80">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf8ac3f1d1f84b57cb1cc44e19faea3e">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4097425617c59bdaa096c3e3726eab2">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e87975da7c3bcaddd395250c2c63f6f">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4311b5acbda37d3154ce4a77605923">Indexes</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce4ff27f2d921a430c45b61560a7b87">DomTree</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc">LiveIntervalCalc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad118815ac16bfe313590411303f998ca">LICalc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d31cdd6245e74afec89e8dc252c18d3">VNInfoAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special pool allocator for <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a>'s (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> val#). <a href="#a0d31cdd6245e74afec89e8dc252c18d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53fa716d6346d30cae455aa3cb1635d2">VirtRegIntervals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Live interval pointers for all the virtual registers. <a href="#a53fa716d6346d30cae455aa3cb1635d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71884229210a07ad4c1b936ace250c2d">RegMaskSlots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sorted list of instructions with register mask operands. <a href="#a71884229210a07ad4c1b936ace250c2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bc92765bd418fcb4058aa63bf3ea6c">RegMaskBits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This vector is parallel to RegMaskSlots, it holds a pointer to the corresponding register mask. <a href="#a64bc92765bd418fcb4058aa63bf3ea6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, unsigned &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821f9a9ca1a3567068bdb90b644a22e3">RegMaskBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each basic block number, keep (begin, size) pairs indexing into the RegMaskSlots and RegMaskBits arrays. <a href="#a821f9a9ca1a3567068bdb90b644a22e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69db7eb851f20a647c407c5d04eebdd9">RegUnitRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps a live range set for each register unit to track fixed physreg interference. <a href="#a69db7eb851f20a647c407c5d04eebdd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7645b48e30da2e9ae644b6ade5663dbb">getSpillWeight</a> (bool isDef, bool isUse, const MachineBlockFrequencyInfo *MBFI, const MachineInstr &amp;MI, ProfileSummaryInfo *PSI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the spill weight to assign to a single instruction. <a href="#a7645b48e30da2e9ae644b6ade5663dbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9477f951deaab56a096380fc549d602c">getSpillWeight</a> (bool isDef, bool isUse, const MachineBlockFrequencyInfo *MBFI, const MachineBasicBlock *MBB, ProfileSummaryInfo *PSI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the spill weight to assign to a single instruction. <a href="#a9477f951deaab56a096380fc549d602c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd283ab20d6ce458f6f7efc5ecd6c1b">createInterval</a> (Register Reg)</td>
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


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ShrinkToUsesWorkList {#a5e3081cd90fed5d5de7fce572e7d764e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveIntervals::ShrinkToUsesWorkList =  SmallVector&lt;std::pair&lt;SlotIndex, VNInfo *&gt;, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LiveIntervalsAnalysis {#a8b3787dc94544cbab03e18b792bb9483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/liveintervalsanalysis">LiveIntervalsAnalysis</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="#a8b3787dc94544cbab03e18b792bb9483">LiveIntervalsAnalysis</a>.</p>


<p>Referenced by <a href="#a7006961215ea5d215922af0f7b169a13">invalidate</a> and <a href="#a8b3787dc94544cbab03e18b792bb9483">LiveIntervalsAnalysis</a>.</p>

</div>
</div>

### LiveIntervalsWrapperPass {#a7fd0a6513ebfbd0dc547bace9e7b987c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass">LiveIntervalsWrapperPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="#a7fd0a6513ebfbd0dc547bace9e7b987c">LiveIntervalsWrapperPass</a>.</p>


<p>Referenced by <a href="#a7fd0a6513ebfbd0dc547bace9e7b987c">LiveIntervalsWrapperPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveIntervals() {#a271d514325b600fdc2c97e0604850656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervals::LiveIntervals (<a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;&amp;)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LiveIntervals() {#ad9d6df564e04ebadb068d0c97973264f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervals::LiveIntervals ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### LiveIntervals() {#a8b13b503ee826cb3304437bbeac05dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervals::LiveIntervals (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp; DT)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LiveIntervals() {#a051abd547aad728ae7aeb43f0a7b25bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals::~LiveIntervals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addKillFlags() {#a6e3886e9084257e74b5db4a8951d36e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::addKillFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add kill flags to any instruction that kills a virtual register.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a60203ad10397a7340f8a0e44ac25368d">llvm::LiveRange::advanceTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9a5e7c523f12f9f164b786769de1ca47">llvm::LiveRange::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afeb00b9049a2391c990df15692caef63">llvm::LiveRange::find</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="#a1882fe2a570964e4c6abb0eac322beab">getInstructionFromIndex</a>, <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a785a4e2daf4e5bf3f0836adbc4fb7e65">llvm::VirtRegMap::getPhys</a>, <a href="#a7b2ec2588cc48710e468563a0e71d24a">getRegUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### addSegmentToEndOfBlock() {#ac3d33d3a8e2cf3bdc2932450f90f078f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::Segment LiveIntervals::addSegmentToEndOfBlock (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; startInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a register and an instruction, adds a live segment from that instruction to the end of its MBB.</p>

<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="#a6f3043b29023d270fc4bc5062dff7cee">getInstructionIndex</a>, <a href="#a76163707e71807054d87648aa5e00dd7">getMBBEndIdx</a>, <a href="#a62c18df693b93ed807e1d6852cc20f3e">getOrCreateEmptyInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a> and <a href="#a74e3f6df25478faef0095e526847f713">getVNInfoAllocator</a>.</p>

</div>
</div>

### checkRegMaskInterference() {#a26c99fa2411ae509e9eb030f8aefb4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveIntervals::checkRegMaskInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; UsableRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if <span class="doxyComputerOutput">LI</span> is live across any register mask instructions, and compute a bit mask of physical registers that are not clobbered by any of them.</p>


<p>Returns false if <span class="doxyComputerOutput">LI</span> doesn't cross any register mask instructions. In that case, the bit vector is not filled in.</p>


<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9a5e7c523f12f9f164b786769de1ca47">llvm::LiveRange::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a35bbc237e4a675c5332103ac6e7dcce1">llvm::BitVector::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a51711ad960e294ac064a578ebfae0de7">llvm::BitVector::clearBitsNotInMask</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aa1bc5510e870a77ebe055b1524d9fd26">llvm::LiveRange::endIndex</a>, <a href="#a1882fe2a570964e4c6abb0eac322beab">getInstructionFromIndex</a>, <a href="#a5dfb831efc211b21625503f9798a06fa">getRegMaskBits</a>, <a href="#a755264b66316aa1a280e5aa47ce89f2a">getRegMaskBitsInBlock</a>, <a href="#a7893ae3dbb60325251e33fc093531040">getRegMaskSlots</a>, <a href="#a8106d8c7d47010fe3a2201e7205ef087">getRegMaskSlotsInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#a801fcd2cb84f0d0292a77e675c7c492c">hasLiveThroughUse</a>, <a href="#abc913cf0bab81b94548cd3c8eeb33117">intervalIsInOneMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a32859a24aa7a3be269855b989d92a4b4">llvm::BitVector::resize</a>.</p>

</div>
</div>

### constructMainRangeFromSubranges() {#ac7a9ba0bac237cd374e2a88f9c21696f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::constructMainRangeFromSubranges (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For live interval <span class="doxyComputerOutput">LI</span> with correct SubRanges construct matching information for the main live range.</p>


<p>Expects the main live range to not have any segments or value numbers.</p>


<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1818 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a334e584aeef0fcf744450fdf41fe8a84">getSlotIndexes</a> and <a href="#a74e3f6df25478faef0095e526847f713">getVNInfoAllocator</a>.</p>

</div>
</div>

### createAndComputeVirtRegInterval() {#afb762c1cdb87a67e41a3ba53d47ceb45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval &amp; llvm::LiveIntervals::createAndComputeVirtRegInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#acffbb09726d9e1a3af9ef69fcbbf0a24">createEmptyInterval</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9317ef8571eae8a49591ed8912c4d102">moveForSingleUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a> and <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange</a>.</p>

</div>
</div>

### createEmptyInterval() {#acffbb09726d9e1a3af9ef69fcbbf0a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval &amp; llvm::LiveIntervals::createEmptyInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> creation.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a11cd70de340f310acc70781d57a00136">hasInterval</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#afb762c1cdb87a67e41a3ba53d47ceb45">createAndComputeVirtRegInterval</a>, <a href="#a62c18df693b93ed807e1d6852cc20f3e">getOrCreateEmptyInterval</a> and <a href="#aeffc1bb4ebe64a8ad3478e1253683847">splitSeparateComponents</a>.</p>

</div>
</div>

### dump() {#ae5b2788f458f4763a2fa43457af4f597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveIntervals::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ae7cde99972870aa99be89218096b3ccf">print</a>.</p>

</div>
</div>

### extendToIndices() {#ae2333ffb94572756f96dcad39de8bbcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::extendToIndices (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Indices, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extend the live range <span class="doxyComputerOutput">LR</span> to reach all points in <span class="doxyComputerOutput">Indices</span>.</p>


<p>The points in the <span class="doxyComputerOutput">Indices</span> array must be jointly dominated by the union of the existing defs in <span class="doxyComputerOutput">LR</span> and points in <span class="doxyComputerOutput">Undefs</span>.</p>


<p>PHI-defs are added as needed to maintain SSA form.</p>


<p>If a <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> in <span class="doxyComputerOutput">Indices</span> is the end index of a basic block, <span class="doxyComputerOutput">LR</span> will be extended to be live out of the basic block. If a <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> in <span class="doxyComputerOutput">Indices</span> is jointy dominated only by points in <span class="doxyComputerOutput">Undefs</span>, the live range will not be extended to that point.</p>


<p>See also <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#ad445a5028efdf094173a202811f003e3">LiveRangeCalc::extend()</a>.</p>


<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a334e584aeef0fcf744450fdf41fe8a84">getSlotIndexes</a> and <a href="#a74e3f6df25478faef0095e526847f713">getVNInfoAllocator</a>.</p>


<p>Referenced by <a href="#ae60987483a38746f0d6d90dca2b65284">extendToIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>.</p>

</div>
</div>

### extendToIndices() {#ae60987483a38746f0d6d90dca2b65284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::extendToIndices (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Indices)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="#ae2333ffb94572756f96dcad39de8bbcb">extendToIndices</a>.</p>

</div>
</div>

### getCachedRegUnit() {#a8158b31061f0231adcf53e160386914d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange * llvm::LiveIntervals::getCachedRegUnit (unsigned Unit)</td>
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

<p>Return the live range for register unit <span class="doxyComputerOutput">Unit</span> if it has already been computed, or nullptr if it hasn't been computed yet.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ad17df702dc2863df688cbe4b9d7fe0ba">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a923798c288aeebf99a43eb7191492fe2">getLiveRange</a> and <a href="#ae9f0ff5f13bf6cb4567247a39f7756e3">removePhysRegDefAt</a>.</p>

</div>
</div>

### getCachedRegUnit() {#a07b2244e53914a5143b3a89ae3afb4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveRange * llvm::LiveIntervals::getCachedRegUnit (unsigned Unit)</td>
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



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### getDomTree() {#a6dca6a95f0921bc90d88adfddd44e304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree &amp; llvm::LiveIntervals::getDomTree ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>.</p>

</div>
</div>

### getInstructionFromIndex() {#a1882fe2a570964e4c6abb0eac322beab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::LiveIntervals::getInstructionFromIndex (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> index)</td>
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

<p>Returns the instruction associated with the given index.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="#a6e3886e9084257e74b5db4a8951d36e0">addKillFlags</a>, <a href="#a26c99fa2411ae509e9eb030f8aefb4e8">checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a73c2c11c6c943efa25ec3a0802c4ac52">findInsertLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a58659e9d9d29818cd6d0ad0d4abbd107">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getAVLDefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a43d14ce45443d02b378ac4aab0dec9d4">getVRegDef</a> and <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>.</p>

</div>
</div>

### getInstructionIndex() {#a6f3043b29023d270fc4bc5062dff7cee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::getInstructionIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Instr)</td>
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

<p>Returns the base index of the given instruction.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="#ac3d33d3a8e2cf3bdc2932450f90f078f">addSegmentToEndOfBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a08414c5d48fed44354cf4c4ea6ca464c">collectVirtualRegUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acee6dacd4d30da478f3ad67f7fc27142">llvm::RegisterOperands::detectDeadDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a3a62b5d1e83ec172369441613b538fce">dumpMachineInstrRangeWithSlotIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a8b1a8fc118e74550d4d11d8740ae10eb">findNextInsertLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ab457e04adca93e5cb81989a2414b1a49">findUseBetween</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62c28bacc64f2e1f9c9296f9314d6c75">llvm::getLiveRegsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb88334dcf6976de300fb1e3667430d7">llvm::getLiveRegsBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a43d14ce45443d02b378ac4aab0dec9d4">getVRegDef</a>, <a href="#aa1a6fbdf0a3311c7b9602dd67e46fef9">handleMoveIntoNewBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a881b49c730ea9d71536df2bf6847f4d0">hasOneNonDBGUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp/#a9dbfc6f968f0d6cbfd77760b62a9b552">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9317ef8571eae8a49591ed8912c4d102">moveForSingleUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#aee855b0219feb9c43b2f228481a9a010">printRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pbqpregalloc-cpp/#ae89b6939795782712cc032bf425fd584">regJustKilledBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="#ac7446b2819c44bf459763351b5bcc29b">shrinkToUses</a> and <a href="#a42083019e0bdb164e55da49ab9f4d717">shrinkToUses</a>.</p>

</div>
</div>

### getInterval() {#a8208eacaf02c9742c8ed7f09ec0837f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval &amp; llvm::LiveIntervals::getInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#afb762c1cdb87a67e41a3ba53d47ceb45">createAndComputeVirtRegInterval</a>, <a href="#a11cd70de340f310acc70781d57a00136">hasInterval</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="#a6e3886e9084257e74b5db4a8951d36e0">addKillFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/interference/#a1fe585bae928f642b4e3b2de11d717b4">anonymous{RegAllocPBQP.cpp}::Interference::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/spillcosts/#a24a1e3c936c56e8a7424d8bd2f4265cb">anonymous{RegAllocPBQP.cpp}::SpillCosts::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a08414c5d48fed44354cf4c4ea6ca464c">collectVirtualRegUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="#a5cd4eee1caa18a946143934b4d0220b1">getInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ad17df702dc2863df688cbe4b9d7fe0ba">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a04f8912e1eb95ec53dcd326cac74b8b9">llvm::getLiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a923798c288aeebf99a43eb7191492fe2">getLiveRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaa1b5dff8de1c3bc2e3e9fee3ef7459">llvm::getLiveRegMap</a>, <a href="#a62c18df693b93ed807e1d6852cc20f3e">getOrCreateEmptyInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#ac370c41caa198ae51b35d5b35f9b8c81">getVDefInterval</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#a6bdc7e7c639e6ec0018642b921042036">anonymous{RISCVInsertVSETVLI.cpp}::getVNInfoFromReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a43d14ce45443d02b378ac4aab0dec9d4">getVRegDef</a>, <a href="#aa1a6fbdf0a3311c7b9602dd67e46fef9">handleMoveIntoNewBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a881b49c730ea9d71536df2bf6847f4d0">hasOneNonDBGUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a272a95f31ec948e680a3c7dffd3c7f80">isLocalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9317ef8571eae8a49591ed8912c4d102">moveForSingleUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="#ae7cde99972870aa99be89218096b3ccf">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pbqpregalloc-cpp/#ae89b6939795782712cc032bf425fd584">regJustKilledBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8a7cb54f8347286b106be184c8c125e1">llvm::HexagonRegisterInfo::shouldCoalesce</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### getInterval() {#a5cd4eee1caa18a946143934b4d0220b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval &amp; llvm::LiveIntervals::getInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getMBBEndIdx() {#a76163707e71807054d87648aa5e00dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::getMBBEndIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb)</td>
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

<p>Return the last index in the given basic block.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="#ac3d33d3a8e2cf3bdc2932450f90f078f">addSegmentToEndOfBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a38c76eebc11caaa9225a4bfe146585a6">anonymous{LiveDebugVariables.cpp}::UserValue::emitDebugValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a1066c542d3ccd99d3e740ad91aed49de">anonymous{LiveDebugVariables.cpp}::UserValue::extendDef</a>, <a href="#a29d12c5a65b3940bfac7b5aa1121ac70">handleMove</a>, <a href="#ae7bb8fbc54f0001e556e3ab13a5b6ba5">isLiveOutOfMBB</a> and <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange</a>.</p>

</div>
</div>

### getMBBFromIndex() {#af3fe68c1ef3d401833b3d37cc222ead2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::LiveIntervals::getMBBFromIndex (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> index)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel/#ada0f64f2cd5510902725c8a47d5bf56d">anonymous{LiveDebugVariables.cpp}::UserLabel::emitDebugLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a38c76eebc11caaa9225a4bfe146585a6">anonymous{LiveDebugVariables.cpp}::UserValue::emitDebugValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a1066c542d3ccd99d3e740ad91aed49de">anonymous{LiveDebugVariables.cpp}::UserValue::extendDef</a> and <a href="#a1b6e5f6033c80dff3f9b4c6fb40499c2">hasPHIKill</a>.</p>

</div>
</div>

### getMBBStartIdx() {#a17bd0f1ec8263f735f29dd8840b7188f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::getMBBStartIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb)</td>
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

<p>Return the first index in the given basic block.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a73c2c11c6c943efa25ec3a0802c4ac52">findInsertLocation</a>, <a href="#a29d12c5a65b3940bfac7b5aa1121ac70">handleMove</a>, <a href="#af47f5ea0e633ac96943c6937e724ae4a">isLiveInToMBB</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### getOrCreateEmptyInterval() {#a62c18df693b93ed807e1d6852cc20f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval &amp; llvm::LiveIntervals::getOrCreateEmptyInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return an existing interval for <span class="doxyComputerOutput">Reg</span>.</p>


<p>If <span class="doxyComputerOutput">Reg</span> has no interval then this creates a new empty one instead. Note: does not trigger interval computation.</p>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#acffbb09726d9e1a3af9ef69fcbbf0a24">createEmptyInterval</a>, <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a>, <a href="#a11cd70de340f310acc70781d57a00136">hasInterval</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ac3d33d3a8e2cf3bdc2932450f90f078f">addSegmentToEndOfBlock</a>.</p>

</div>
</div>

### getRegMaskBits() {#a5dfb831efc211b21625503f9798a06fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const uint32_t * &gt; llvm::LiveIntervals::getRegMaskBits ()</td>
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

<p>Returns an array of register mask pointers corresponding to <a href="#a7893ae3dbb60325251e33fc093531040">getRegMaskSlots()</a>.</p>

<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="#a26c99fa2411ae509e9eb030f8aefb4e8">checkRegMaskInterference</a> and <a href="#a755264b66316aa1a280e5aa47ce89f2a">getRegMaskBitsInBlock</a>.</p>

</div>
</div>

### getRegMaskBitsInBlock() {#a755264b66316aa1a280e5aa47ce89f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const uint32_t * &gt; llvm::LiveIntervals::getRegMaskBitsInBlock (unsigned MBBNum)</td>
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

<p>Returns an array of mask pointers corresponding to getRegMaskSlotsInBlock(MBBNum).</p>

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#a5dfb831efc211b21625503f9798a06fa">getRegMaskBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a26c99fa2411ae509e9eb030f8aefb4e8">checkRegMaskInterference</a>.</p>

</div>
</div>

### getRegMaskSlots() {#a7893ae3dbb60325251e33fc093531040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SlotIndex &gt; llvm::LiveIntervals::getRegMaskSlots ()</td>
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

<p>Returns a sorted array of slot indices of all instructions with register mask operands.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="#a26c99fa2411ae509e9eb030f8aefb4e8">checkRegMaskInterference</a> and <a href="#a8106d8c7d47010fe3a2201e7205ef087">getRegMaskSlotsInBlock</a>.</p>

</div>
</div>

### getRegMaskSlotsInBlock() {#a8106d8c7d47010fe3a2201e7205ef087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SlotIndex &gt; llvm::LiveIntervals::getRegMaskSlotsInBlock (unsigned MBBNum)</td>
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

<p>Returns a sorted array of slot indices of all instructions with register mask operands in the basic block numbered <span class="doxyComputerOutput">MBBNum</span>.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#a7893ae3dbb60325251e33fc093531040">getRegMaskSlots</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a26c99fa2411ae509e9eb030f8aefb4e8">checkRegMaskInterference</a>.</p>

</div>
</div>

### getRegUnit() {#a7b2ec2588cc48710e468563a0e71d24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange &amp; llvm::LiveIntervals::getRegUnit (unsigned Unit)</td>
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

<p>Return the live range for register unit <span class="doxyComputerOutput">Unit</span>.</p>


<p>It will be computed if it doesn't exist.</p>


<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp/#acc192e3e53887e1d6fa56abbe10530e6">LiveRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e97c305b7876914dc3663bf51d72bc">llvm::UseSegmentSetForPhysRegs</a>.</p>


<p>Referenced by <a href="#a6e3886e9084257e74b5db4a8951d36e0">addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a>.</p>

</div>
</div>

### getSlotIndexes() {#a334e584aeef0fcf744450fdf41fe8a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes * llvm::LiveIntervals::getSlotIndexes ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#a363e3f71faf094bba68a16bb32f43cff">buildVRegToDbgValueMap</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="#ac7a9ba0bac237cd374e2a88f9c21696f">constructMainRangeFromSubranges</a>, <a href="#ae2333ffb94572756f96dcad39de8bbcb">extendToIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaa1b5dff8de1c3bc2e3e9fee3ef7459">llvm::getLiveRegMap</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#a6bdc7e7c639e6ec0018642b921042036">anonymous{RISCVInsertVSETVLI.cpp}::getVNInfoFromReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a50a95c05ee7d95c49a8c65c49046e3ec">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8a7cb54f8347286b106be184c8c125e1">llvm::HexagonRegisterInfo::shouldCoalesce</a>.</p>

</div>
</div>

### getVNInfoAllocator() {#a74e3f6df25478faef0095e526847f713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo::Allocator &amp; llvm::LiveIntervals::getVNInfoAllocator ()</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="#ac3d33d3a8e2cf3bdc2932450f90f078f">addSegmentToEndOfBlock</a>, <a href="#ac7a9ba0bac237cd374e2a88f9c21696f">constructMainRangeFromSubranges</a>, <a href="#ae2333ffb94572756f96dcad39de8bbcb">extendToIndices</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>.</p>

</div>
</div>

### handleMove() {#a29d12c5a65b3940bfac7b5aa1121ac70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::handleMove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool UpdateFlags=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call this method to notify <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> that instruction <span class="doxyComputerOutput">MI</span> has been moved within a basic block.</p>


<p>This will update the live intervals for all operands of <span class="doxyComputerOutput">MI</span>. Moves between basic blocks are not supported.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateFlags</td>
<td class="doxyParamItemDescription"><p>Update live intervals for nonallocatable physregs.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a76163707e71807054d87648aa5e00dd7">getMBBEndIdx</a>, <a href="#a17bd0f1ec8263f735f29dd8840b7188f">getMBBStartIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/liveintervals/hmeditor/#aa060d1bdca0620ff13d49456dccf9303">llvm::LiveIntervals::HMEditor::updateAllRanges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9317ef8571eae8a49591ed8912c4d102">moveForSingleUse</a>.</p>

</div>
</div>

### handleMoveIntoNewBundle() {#aa1a6fbdf0a3311c7b9602dd67e46fef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::handleMoveIntoNewBundle (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BundleStart, bool UpdateFlags=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update intervals of operands of all instructions in the newly created bundle specified by <span class="doxyComputerOutput">BundleStart</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateFlags</td>
<td class="doxyParamItemDescription"><p>Update live intervals for nonallocatable physregs.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Assumes existing liveness is accurate.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>BundleStart should be the first instruction in the Bundle.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>BundleStart should not have a have <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> as one will be assigned.</p></dd>
</dl>


<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2b7ecbdbe9013ca2794761934d2bd9">llvm::getBundleEnd</a>, <a href="#a6f3043b29023d270fc4bc5062dff7cee">getInstructionIndex</a>, <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a11cd70de340f310acc70781d57a00136">hasInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a149e4cda329019551bbb27fe3159eca6">llvm::LiveQueryResult::isDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a> and <a href="/web-llvm/docs/api/classes/liveintervals/hmeditor/#aa060d1bdca0620ff13d49456dccf9303">llvm::LiveIntervals::HMEditor::updateAllRanges</a>.</p>

</div>
</div>

### hasInterval() {#a11cd70de340f310acc70781d57a00136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervals::hasInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="#acffbb09726d9e1a3af9ef69fcbbf0a24">createEmptyInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaa1b5dff8de1c3bc2e3e9fee3ef7459">llvm::getLiveRegMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ab92d2e2752422a6a0995188d64b77">llvm::getLiveRegs</a>, <a href="#a62c18df693b93ed807e1d6852cc20f3e">getOrCreateEmptyInterval</a>, <a href="#aa1a6fbdf0a3311c7b9602dd67e46fef9">handleMoveIntoNewBundle</a>, <a href="#ae7cde99972870aa99be89218096b3ccf">print</a>, <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### hasPHIKill() {#a1b6e5f6033c80dff3f9b4c6fb40499c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveIntervals::hasPHIKill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if VNI is killed by any PHI-def values in LI.</p>


<p>This may conservatively return true to avoid expensive computations.</p>


<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="#af3fe68c1ef3d401833b3d37cc222ead2">getMBBFromIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a7e1ec6260b229b2f5913405b758bc146">llvm::LiveRange::getVNInfoBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#addd80df79ba902914c7d8a52e3896b79">llvm::MachineBasicBlock::predecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9eb4aa155c41e60dff42f4e741a0dcf0">llvm::LiveRange::valnos</a>.</p>

</div>
</div>

### InsertMachineInstrInMaps() {#a2035620c14bf7bdedfa4e2655f88d114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::InsertMachineInstrInMaps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>.</p>

</div>
</div>

### InsertMachineInstrRangeInMaps() {#a87b097de2261d68334195870a03412b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::InsertMachineInstrRangeInMaps (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> B, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> E)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### insertMBBInMaps() {#a2b6f72816801c63516c4b25f3b6544b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::insertMBBInMaps (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac0bfa894f538166cb476b439a2cb0aea">llvm::MachineBasicBlock::splitAt</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### intervalIsInOneMBB() {#abc913cf0bab81b94548cd3c8eeb33117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * LiveIntervals::intervalIsInOneMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If LI is confined to a single basic block, return a pointer to that block.</p>


<p>If LI is live in to or out of any block, return NULL.</p>


<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9b4b2c1bb443279588bd6582ad6a86b2">llvm::LiveRange::beginIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aa1bc5510e870a77ebe055b1524d9fd26">llvm::LiveRange::endIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0c74422518b3479395817926489e9eec">llvm::SlotIndex::isBlock</a>.</p>


<p>Referenced by <a href="#a26c99fa2411ae509e9eb030f8aefb4e8">checkRegMaskInterference</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a272a95f31ec948e680a3c7dffd3c7f80">isLocalCopy</a>.</p>

</div>
</div>

### invalidate() {#a7006961215ea5d215922af0f7b169a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveIntervals::invalidate (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, MachineFunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>Reference <a href="#a8b3787dc94544cbab03e18b792bb9483">LiveIntervalsAnalysis</a>.</p>

</div>
</div>

### isLiveInToMBB() {#af47f5ea0e633ac96943c6937e724ae4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervals::isLiveInToMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#a17bd0f1ec8263f735f29dd8840b7188f">getMBBStartIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a400c0b88110521ad1de258a7885d9038">llvm::LiveRange::liveAt</a>.</p>

</div>
</div>

### isLiveOutOfMBB() {#ae7bb8fbc54f0001e556e3ab13a5b6ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervals::isLiveOutOfMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="#a76163707e71807054d87648aa5e00dd7">getMBBEndIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a400c0b88110521ad1de258a7885d9038">llvm::LiveRange::liveAt</a>.</p>

</div>
</div>

### isNotInMIMap() {#aa1818a17984c50c7190464f3a04c0f3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervals::isNotInMIMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Instr)</td>
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

<p>Returns true if the specified machine instr has been removed or was never entered in the map.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a8b1a8fc118e74550d4d11d8740ae10eb">findNextInsertLocation</a>.</p>

</div>
</div>

### print() {#ae7cde99972870aa99be89218096b3ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement the dump method.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a>, <a href="#a11cd70de340f310acc70781d57a00136">hasInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a34302b557354b8a09796c30b9f7408ab">llvm::printRegUnit</a>.</p>


<p>Referenced by <a href="#ae5b2788f458f4763a2fa43457af4f597">dump</a>.</p>

</div>
</div>

### pruneValue() {#a94cf1c59ca73ea330872deb639013cb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::pruneValue (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Kill, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; * EndPoints)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">LR</span> has a live value at <span class="doxyComputerOutput">Kill</span>, prune its live range by removing any liveness reachable from Kill.</p>


<p>Add live range end points to EndPoints such that extendToIndices(LI, EndPoints) will reconstruct the value's live range.</p>


<p>Calling <a href="#a94cf1c59ca73ea330872deb639013cb9">pruneValue()</a> and <a href="#ae2333ffb94572756f96dcad39de8bbcb">extendToIndices()</a> can be used to reconstruct SSA form after adding defs to a virtual register.</p>


<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7ca9174266d6241bed1ff75961249393">llvm::df_ext_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12f5ac004bb20214c37ec85406cea83">llvm::df_ext_end</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#accf3c068536d27391a38eaec0db05eec">llvm::LiveQueryResult::endPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae8bd4b098d55a431c12cfba2a11c94bb">llvm::LiveRange::removeSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a> and <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a001d69b0b75e2841cc109cbe8729ba87">llvm::LiveQueryResult::valueOutOrDead</a>.</p>

</div>
</div>

### pruneValue() {#ae927868d9b86954520b923345a3d4762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_UNUSED void llvm::LiveIntervals::pruneValue (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; *)</td>
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

<p>This function should not be used.</p>


<p>Its intent is to tell you that you are doing something wrong if you call pruneValue directly on a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a>. Indeed, you are supposed to call pruneValue on the main <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> and all the LiveRanges of the subranges if any.</p>


<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### reanalyze() {#a66928037b669a15589743dc46947ef0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::reanalyze (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a50a95c05ee7d95c49a8c65c49046e3ec">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::runOnMachineFunction</a>.</p>

</div>
</div>

### removeAllRegUnitsForPhysReg() {#a0dbecb97d916d10bb623cf46c199e0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::removeAllRegUnitsForPhysReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Remove associated live ranges for the register units associated with <span class="doxyComputerOutput">Reg</span>.</p>


<p>Subsequent uses should rely on on-demand recomputation.</p>



:::info
<p>This method can result in inconsistent liveness tracking if multiple phyical registers share a regunit, and should be used cautiously.</p>
:::


<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="#ac443b437e7b2899ab42f450c061dd964">removeRegUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### removeInterval() {#aa07c0db20cf93bf2f558d00af34a6cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::removeInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> removal.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>.</p>

</div>
</div>

### RemoveMachineInstrFromMaps() {#a73f605751be73f0a910a586bb1b5d869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::RemoveMachineInstrFromMaps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a2070b3e24d132c4508d4e6ff22dc9ff3">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::disposed</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstrinfo-cpp-/ppcpipelinerloopinfo/#aa57744a6bd6fcdea3620989a258437d1">anonymous{PPCInstrInfo.cpp}::PPCPipelinerLoopInfo::disposed</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-moduloschedule-cpp-/#af97e2949b56d1bb9fd46f389909d8788">anonymous{ModuloSchedule.cpp}::EliminateDeadPhis</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>.</p>

</div>
</div>

### removePhysRegDefAt() {#ae9f0ff5f13bf6cb4567247a39f7756e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::removePhysRegDefAt (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove value numbers and related live segments starting at position <span class="doxyComputerOutput">Pos</span> that are part of any liverange of physical register <span class="doxyComputerOutput">Reg</span> or one of its subregisters.</p>

<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="#a8158b31061f0231adcf53e160386914d">getCachedRegUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a63176e601338dbe403676b86e78c7203">llvm::LiveRange::removeValNo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>.</p>

</div>
</div>

### removeRegUnit() {#ac443b437e7b2899ab42f450c061dd964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervals::removeRegUnit (unsigned Unit)</td>
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

<p>Remove computed live range for register unit <span class="doxyComputerOutput">Unit</span>.</p>


<p>Subsequent uses should rely on on-demand recomputation.</p>


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Referenced by <a href="#a0dbecb97d916d10bb623cf46c199e0ae">removeAllRegUnitsForPhysReg</a>.</p>

</div>
</div>

### removeVRegDefAt() {#ac332ca27d85adc8d21edd708be55dfe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::removeVRegDefAt (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove value number and related live segments of <span class="doxyComputerOutput">LI</span> and its subranges that start at position <span class="doxyComputerOutput">Pos</span>.</p>

<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0aac3ef1eadaa206a70b767730ef3c5b">llvm::LiveInterval::removeEmptySubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a63176e601338dbe403676b86e78c7203">llvm::LiveRange::removeValNo</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>.</p>

</div>
</div>

### repairIntervalsInRange() {#a0d7e0d23a0453390a4c1e9a61afccdca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::repairIntervalsInRange (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; OrigRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update live intervals for instructions in a range of iterators.</p>


<p>It is intended for use after target hooks that may insert or remove instructions, and is only efficient for a small number of instructions.</p>


<p>OrigRegs is a vector of registers that were originally used by the instructions in the range between the two iterators.</p>


<p>Currently, the only changes that are supported are simple removal and addition of uses.</p>


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1700 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="#afb762c1cdb87a67e41a3ba53d47ceb45">createAndComputeVirtRegInterval</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="#a6f3043b29023d270fc4bc5062dff7cee">getInstructionIndex</a>, <a href="#a8208eacaf02c9742c8ed7f09ec0837f3">getInterval</a>, <a href="#a76163707e71807054d87648aa5e00dd7">getMBBEndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac832da130f4d71a4533a69d98315fb19">llvm::SlotIndex::getPrevSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ace8519cea9fa2e688a052df670afe41e">llvm::LiveRange::hasAtLeastOneValue</a>, <a href="#a11cd70de340f310acc70781d57a00136">hasInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0aac3ef1eadaa206a70b767730ef3c5b">llvm::LiveInterval::removeEmptySubRanges</a>, <a href="#aa07c0db20cf93bf2f558d00af34a6cb6">removeInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### ReplaceMachineInstrInMaps() {#afbdfb2cc5decd8f22ea3ccc1ecea4028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervals::ReplaceMachineInstrInMaps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; NewMI)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a414af156e6dae8024f5321babf41afb2">llvm::SystemZInstrInfo::convertToThreeAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>.</p>

</div>
</div>

### shrinkToUses() {#ac7446b2819c44bf459763351b5bcc29b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveIntervals::shrinkToUses (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * li, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; * dead=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After removing some uses of a register, shrink its live range to just the remaining uses.</p>


<p>This method does not compute reaching defs for new uses, and it doesn't remove dead defs. Dead PHIDef values are marked as unused. New dead machine instructions are added to the dead vector. Returns true if the interval may have been separated into multiple connected components.</p>


<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#ac46976013d5526a5d1430256b4007b6b">createSegmentsForValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6f3043b29023d270fc4bc5062dff7cee">getInstructionIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0aac3ef1eadaa206a70b767730ef3c5b">llvm::LiveInterval::removeEmptySubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9c628b400be67b6adb4fa07e84a96a82">llvm::LiveRange::segments</a>, <a href="#ac7446b2819c44bf459763351b5bcc29b">shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#aaae33cfd0a31e453deec40b2d5274e70">llvm::LiveQueryResult::valueDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a3524c5585af87a1c875f60fe849d241f">llvm::LiveRange::vnis</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="#ac7446b2819c44bf459763351b5bcc29b">shrinkToUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ab4c68b8293672c79332578b06398c27a">shrinkToUses</a>.</p>

</div>
</div>

### shrinkToUses() {#a42083019e0bdb164e55da49ab9f4d717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::shrinkToUses (<a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">LiveInterval::SubRange</a> &amp; SR, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of shrinkToUses(<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> <em>li, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt;<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></em>&gt; *dead) that works on a subregister live range and only looks at uses matching the lane mask of the subregister range.</p>


<p>This may leave the subrange empty which needs to be cleaned up with LiveInterval::removeEmptySubranges() afterwards.</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#ac46976013d5526a5d1430256b4007b6b">createSegmentsForValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a11bad3e34d11ffb7b0412de6bbd294b3">llvm::SlotIndex::getDeadSlot</a>, <a href="#a6f3043b29023d270fc4bc5062dff7cee">getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a1cde3a312b39ac23baecfce5fee662f7">llvm::LiveRange::getSegmentContaining</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange/#a8dab9096ed829f13c573a282e5723f62">llvm::LiveInterval::SubRange::LaneMask</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#a81775e4a3dbcbc42d828c3e4becd9190">llvm::VNInfo::markUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae8bd4b098d55a431c12cfba2a11c94bb">llvm::LiveRange::removeSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9c628b400be67b6adb4fa07e84a96a82">llvm::LiveRange::segments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9eb4aa155c41e60dff42f4e741a0dcf0">llvm::LiveRange::valnos</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#aaae33cfd0a31e453deec40b2d5274e70">llvm::LiveQueryResult::valueDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a3524c5585af87a1c875f60fe849d241f">llvm::LiveRange::vnis</a>.</p>

</div>
</div>

### splitSeparateComponents() {#aeffc1bb4ebe64a8ad3478e1253683847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::splitSeparateComponents (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * &gt; &amp; SplitLIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split separate components in <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> <span class="doxyComputerOutput">LI</span> into separate intervals.</p>

<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1802 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="#acffbb09726d9e1a3af9ef69fcbbf0a24">createEmptyInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ab4c68b8293672c79332578b06398c27a">shrinkToUses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyze() {#a52d6150f2c3166e88d84a8ce0cde9e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::analyze (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### clear() {#a06378a7903188167e2d9470e6b877723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### computeDeadValues() {#ad2cdbc3b3669b3393c03a55064e0bd68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveIntervals::computeDeadValues (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; * dead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walk the values in <span class="doxyComputerOutput">LI</span> and check for dead values:</p>


<ul class="doxyList ">
<li>Dead PHIDef values are marked as unused.</li>
<li>Dead operands are marked as such.</li>
<li>Completely dead machine instructions are added to the <span class="doxyComputerOutput">dead</span> vector if it is not nullptr. Returns true if any PHI value numbers have been removed which may have separated the interval into multiple connected components.</li>
</ul>

<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### computeLiveInRegUnits() {#a825f2b1fc1906c249dee248aace94254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::computeLiveInRegUnits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Precompute the live ranges of any register units that are live-in to an ABI block somewhere.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> values can appear without a corresponding def when entering the entry block or a landing pad.</p>


<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### computeRegMasks() {#a8c918b11b7cd3403b77f10f8e7ef93f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::computeRegMasks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute RegMaskSlots and RegMaskBits.</p>

<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### computeRegUnitRange() {#acc456e60336939415e89abfafc29a1d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::computeRegUnitRange (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, unsigned Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the live range of a register unit, based on the uses and defs of aliasing registers.</p>


<p>The range should be empty, or contain only dead phi-defs from ABI blocks.</p>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### computeVirtRegInterval() {#a9a90bf719eda6cf3dccd561c6024be0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveIntervals::computeVirtRegInterval (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the live interval of a virtual register, based on defs and uses.</p>

<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### computeVirtRegs() {#ad47691f48084ae6fba396a96c271f3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::computeVirtRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute live intervals for all virtual registers.</p>

<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### dumpInstrs() {#a5cebd21b69e072c53cf9ab88afb9ce7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveIntervals::dumpInstrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### extendSegmentsToUses() {#afe33a94897b85e4da8b43633a090f344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::extendSegmentsToUses (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Segments, <a href="/web-llvm/docs/api/classes/llvm/smallvector">ShrinkToUsesWorkList</a> &amp; WorkList, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### printInstrs() {#a429b7dee18c5e8f1b5d960fb6a43c6e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::printInstrs (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

### repairOldRegInRange() {#a1280e184c944167b5c0660b4f4f63667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervals::repairOldRegInRange (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> endIdx, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=<a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">LaneBitmask::getAll</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for <a href="#a0d7e0d23a0453390a4c1e9a61afccdca">repairIntervalsInRange()</a>, walks backwards and creates/modifies live segments in <span class="doxyComputerOutput">LR</span> to match the operands found.</p>


<p>Only full operands or operands with subregisters matching <span class="doxyComputerOutput">LaneMask</span> are considered.</p>


<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DomTree {#a1ce4ff27f2d921a430c45b61560a7b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* llvm::LiveIntervals::DomTree = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### Indexes {#a8d4311b5acbda37d3154ce4a77605923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* llvm::LiveIntervals::Indexes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### LICalc {#ad118815ac16bfe313590411303f998ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LiveIntervalCalc&gt; llvm::LiveIntervals::LICalc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### MF {#ad3f5b68a222203af313a09fad7077f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::LiveIntervals::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### MRI {#acf8ac3f1d1f84b57cb1cc44e19faea3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::LiveIntervals::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### RegMaskBits {#a64bc92765bd418fcb4058aa63bf3ea6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const uint32_t *, 8&gt; llvm::LiveIntervals::RegMaskBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This vector is parallel to RegMaskSlots, it holds a pointer to the corresponding register mask.</p>


<p>This pointer can be recomputed as:</p>


<p>MI = Indexes-&gt;getInstructionFromIndex(RegMaskSlot[N]); unsigned OpNum = findRegMaskOperand(MI); RegMaskBits[N] = MI-&gt;getOperand(OpNum).getRegMask();</p>


<p>This is kept in a separate vector partly because some standard libraries don't support <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">lower_bound()</a> with mixed objects, partly to improve locality when searching in RegMaskSlots. Also see the comment in <a href="/web-llvm/docs/api/classes/llvm/liverange/#afeb00b9049a2391c990df15692caef63">LiveInterval::find()</a>.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### RegMaskBlocks {#a821f9a9ca1a3567068bdb90b644a22e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;unsigned, unsigned&gt;, 8&gt; llvm::LiveIntervals::RegMaskBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each basic block number, keep (begin, size) pairs indexing into the RegMaskSlots and RegMaskBits arrays.</p>


<p>Note that basic block numbers may not be layout contiguous, that's why we can't just keep track of the first register mask in each basic block.</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### RegMaskSlots {#a71884229210a07ad4c1b936ace250c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SlotIndex, 8&gt; llvm::LiveIntervals::RegMaskSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sorted list of instructions with register mask operands.</p>


<p>Always use the 'r' slot, RegMasks are normal clobbers, not early clobbers.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### RegUnitRanges {#a69db7eb851f20a647c407c5d04eebdd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LiveRange *, 0&gt; llvm::LiveIntervals::RegUnitRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps a live range set for each register unit to track fixed physreg interference.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### TII {#a8e87975da7c3bcaddd395250c2c63f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::LiveIntervals::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### TRI {#af4097425617c59bdaa096c3e3726eab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::LiveIntervals::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### VirtRegIntervals {#a53fa716d6346d30cae455aa3cb1635d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;LiveInterval *, VirtReg2IndexFunctor&gt; llvm::LiveIntervals::VirtRegIntervals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Live interval pointers for all the virtual registers.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

### VNInfoAllocator {#a0d31cdd6245e74afec89e8dc252c18d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo::Allocator llvm::LiveIntervals::VNInfoAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special pool allocator for <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a>'s (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> val#).</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSpillWeight() {#a7645b48e30da2e9ae644b6ade5663dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float LiveIntervals::getSpillWeight (bool isDef, bool isUse, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * MBFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI=nullptr)</td>
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

<p>Calculate the spill weight to assign to a single instruction.</p>


<p>If <span class="doxyComputerOutput">PSI</span> is provided the calculation is altered for optsize functions.</p>


<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="#a7645b48e30da2e9ae644b6ade5663dbb">getSpillWeight</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#ad673e763773e7c633a36c65e793ea862">computeWeight</a>, <a href="#a7645b48e30da2e9ae644b6ade5663dbb">getSpillWeight</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### getSpillWeight() {#a9477f951deaab56a096380fc549d602c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float LiveIntervals::getSpillWeight (bool isDef, bool isUse, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * MBFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI=nullptr)</td>
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

<p>Calculate the spill weight to assign to a single instruction.</p>


<p>If <span class="doxyComputerOutput">PSI</span> is provided the calculation is altered for optsize functions.</p>


<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#a9be2cffeaf9bda65c4c49eeebaa5458f">llvm::MachineBlockFrequencyInfo::getBlockFreqRelativeToEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createInterval() {#a0cd283ab20d6ce458f6f7efc5ecd6c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval * LiveIntervals::createInterval (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">LiveIntervals.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp">LiveIntervals.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
