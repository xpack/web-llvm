---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-registercoalescer-cpp-/registercoalescer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegisterCoalescer` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{RegisterCoalescer.cpp}::RegisterCoalescer { ... }
</div>

## Base classes

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate">Delegate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback methods for <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> owners. <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7dfc993f06b8bc1aee810a92dbf2c2">DbgValueLoc</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug variable location tracking – for each VReg, maintain an ordered-by-slot-index set of DBG_VALUEs, to help quick identification of whether coalescing may change location validity. <a href="#a8c7dfc993f06b8bc1aee810a92dbf2c2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0969ad06eb530c7fc3a7d2b8b9911fa6">RegisterCoalescer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae96d8cb445f62aa68d962e73704705">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a3ae96d8cb445f62aa68d962e73704705">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6fd0a43420aacdcb844afc48c3b9cb">getClearedProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55edcac6ac25614b341d7c34c5a2926c">releaseMemory</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a55edcac6ac25614b341d7c34c5a2926c">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed. <a href="#a55edcac6ac25614b341d7c34c5a2926c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa408ab9747b8ce0bd0a81465c10e8f29">runOnMachineFunction</a> (MachineFunction &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the pass entry point. <a href="#aa408ab9747b8ce0bd0a81465c10e8f29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef281c7441a224dc5d5e31f795ff2e1">print</a> (raw_ostream &amp;O, const Module *=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement the dump method. <a href="#a4ef281c7441a224dc5d5e31f795ff2e1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4075764a012dafe047446c03ddff98">eliminateDeadDefs</a> (LiveRangeEdit *Edit=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively eliminate dead defs in DeadDefs. <a href="#a7a4075764a012dafe047446c03ddff98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b36d2af0621e232ba88ed398a23f00">LRE_WillEraseInstruction</a> (MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> callback for eliminateDeadDefs(). <a href="#a01b36d2af0621e232ba88ed398a23f00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf26f147cca7787d6a6714a4c0f42101">coalesceLocals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Coalesce the LocalWorkList. <a href="#abf26f147cca7787d6a6714a4c0f42101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9102fe3c500cef03dd5936b5c65b697">joinAllIntervals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Join compatible live intervals. <a href="#ae9102fe3c500cef03dd5936b5c65b697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74e0121710281929f61cb3a21886391">copyCoalesceInMBB</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Coalesce copies in the specified MBB, putting copies that cannot yet be coalesced into WorkList. <a href="#ab74e0121710281929f61cb3a21886391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c520bdcf7ee37905ffcbadfa13a386">copyCoalesceWorkList</a> (MutableArrayRef&lt; MachineInstr * &gt; CurrList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to coalesce all copies in CurrList. <a href="#a21c520bdcf7ee37905ffcbadfa13a386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ebe5b7afa42a06d3ddc7658287d4124">lateLiveIntervalUpdate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If one def has many copy like uses, and those copy uses are all rematerialized, the live interval update needed for those rematerializations will be delayed and done all at once instead of being done multiple times. <a href="#a4ebe5b7afa42a06d3ddc7658287d4124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a655c1b576fce35cbf83af011c1d37ef5">copyValueUndefInPredecessors</a> (LiveRange &amp;S, const MachineBasicBlock *MBB, LiveQueryResult SLRQ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the incoming value defined by a COPY at <span class="doxyComputerOutput">SLRQ</span> in the subrange has no value defined in the predecessors. <a href="#a655c1b576fce35cbf83af011c1d37ef5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c81ce82e07a9c465584cab9ee4101a3">setUndefOnPrunedSubRegUses</a> (LiveInterval &amp;LI, Register Reg, LaneBitmask PrunedLanes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set necessary undef flags on subregister uses after pruning out undef lane segments from the subrange. <a href="#a2c81ce82e07a9c465584cab9ee4101a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2e2f179365b6d94d7c352fb96cd12e">joinCopy</a> (MachineInstr *CopyMI, bool &amp;Again, SmallPtrSetImpl&lt; MachineInstr * &gt; &amp;CurrentErasedInstrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to join intervals corresponding to SrcReg/DstReg, which are the src/dst of the copy instruction CopyMI. <a href="#a2d2e2f179365b6d94d7c352fb96cd12e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aae63029f26808ab075291fd04b5d6d">joinIntervals</a> (CoalescerPair &amp;CP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to join these two intervals. <a href="#a8aae63029f26808ab075291fd04b5d6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fce080efda7d42c6666d5c511c6f9b9">joinVirtRegs</a> (CoalescerPair &amp;CP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt joining two virtual registers. Return true on success. <a href="#a8fce080efda7d42c6666d5c511c6f9b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda4553af4bdd4a58a9c697f5b7bb1b6">isHighCostLiveInterval</a> (LiveInterval &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a live interval has many valnos and is coalesced with other live intervals many times, we regard such live interval as having high compile time cost. <a href="#acda4553af4bdd4a58a9c697f5b7bb1b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5577f2b5142dcc2a326d22ea625cd95b">joinReservedPhysReg</a> (CoalescerPair &amp;CP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt joining with a reserved physreg. <a href="#a5577f2b5142dcc2a326d22ea625cd95b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa594927fd89d6ab71047198e5cc65748">mergeSubRangeInto</a> (LiveInterval &amp;LI, const LiveRange &amp;ToMerge, LaneBitmask LaneMask, CoalescerPair &amp;CP, unsigned DstIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> <span class="doxyComputerOutput">ToMerge</span> as a subregister liverange of <span class="doxyComputerOutput">LI</span>. <a href="#aa594927fd89d6ab71047198e5cc65748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7da43b43fa0bc3ddc12a6845c640fa">joinSubRegRanges</a> (LiveRange &amp;LRange, LiveRange &amp;RRange, LaneBitmask LaneMask, const CoalescerPair &amp;CP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Join the liveranges of two subregisters. <a href="#a0a7da43b43fa0bc3ddc12a6845c640fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd9b114350c1510e31adb543bacba61">adjustCopiesBackFrom</a> (const CoalescerPair &amp;CP, MachineInstr *CopyMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We found a non-trivially-coalescable copy. <a href="#aabd9b114350c1510e31adb543bacba61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab78146ade2cca09d093a09e646487922">hasOtherReachingDefs</a> (LiveInterval &amp;IntA, LiveInterval &amp;IntB, VNInfo *AValNo, VNInfo *BValNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are definitions of IntB other than BValNo val# that can reach uses of AValno val# of IntA. <a href="#ab78146ade2cca09d093a09e646487922">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013343bf430b98ca00397d521c24f8d3">removeCopyByCommutingDef</a> (const CoalescerPair &amp;CP, MachineInstr *CopyMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We found a non-trivially-coalescable copy. <a href="#a013343bf430b98ca00397d521c24f8d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af401ae3181b375370da57f82242977ad">removePartialRedundancy</a> (const CoalescerPair &amp;CP, MachineInstr &amp;CopyMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We found a copy which can be moved to its less frequent predecessor. <a href="#af401ae3181b375370da57f82242977ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f67ac5c76b42c9305070ba09f20d65">reMaterializeTrivialDef</a> (const CoalescerPair &amp;CP, MachineInstr *CopyMI, bool &amp;IsDefCopy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the source of a copy is defined by a trivial computation, replace the copy by rematerialize the definition. <a href="#a29f67ac5c76b42c9305070ba09f20d65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2358cdf7dd5c20ff7467363643607f12">canJoinPhys</a> (const CoalescerPair &amp;CP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a copy involving a physreg should be joined. <a href="#a2358cdf7dd5c20ff7467363643607f12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d9dfec4217cd95bf74dac69799d65d">updateRegDefsUses</a> (Register SrcReg, Register DstReg, unsigned SubIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all defs and uses of SrcReg to DstReg and update the subregister number if it is not zero. <a href="#a39d9dfec4217cd95bf74dac69799d65d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7094b4d51c802f98996727d6f0b0122a">addUndefFlag</a> (const LiveInterval &amp;Int, SlotIndex UseIdx, MachineOperand &amp;MO, unsigned SubRegIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given machine operand reads only undefined lanes add an undef flag. <a href="#a7094b4d51c802f98996727d6f0b0122a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba20b7c32f0906249d6977543d4b64e">eliminateUndefCopy</a> (MachineInstr *CopyMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle copies of undef values. <a href="#a7ba20b7c32f0906249d6977543d4b64e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d891694cb295affbd9c105fec7294ae">applyTerminalRule</a> (const MachineInstr &amp;Copy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether or not we should apply the terminal rule on the destination (Dst) of <span class="doxyComputerOutput">Copy</span>. <a href="#a4d891694cb295affbd9c105fec7294ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab757d2f8e3c7b7f5dd03521a3545fbc1">shrinkToUses</a> (LiveInterval *LI, SmallVectorImpl&lt; MachineInstr * &gt; *Dead=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper method for. <a href="#ab757d2f8e3c7b7f5dd03521a3545fbc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5add2193b55fa2b5f4865ba846ea3914">deleteInstr</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper Method to do all the necessary work when an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is deleted. <a href="#a5add2193b55fa2b5f4865ba846ea3914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd287e6b0f450d939995f5bc7a9f04f">buildVRegToDbgValueMap</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk over function and initialize the DbgVRegToValues map. <a href="#abcd287e6b0f450d939995f5bc7a9f04f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2eddaecf92f0b6359eaccae3eac808">checkMergingChangesDbgValues</a> (CoalescerPair &amp;CP, LiveRange &amp;LHS, JoinVals &amp;LHSVals, LiveRange &amp;RHS, JoinVals &amp;RHSVals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether, after merging, any DBG_VALUEs would refer to a different value number than before merging, and whether this can be resolved. <a href="#aaf2eddaecf92f0b6359eaccae3eac808">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb2800a5cfdd0733cbe24dc5f8c513c">checkMergingChangesDbgValuesImpl</a> (Register Reg, LiveRange &amp;OtherRange, LiveRange &amp;RegRange, JoinVals &amp;Vals2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff13ab4950e391dfc5d9526a2c64f4b">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133af1aee00d04d460f113d4286af07e">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23bddc5607b97be15c45e8ff7ca93430">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e661ae415777c0318a647cbc9b3e05">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a4b5b483eeeebf19e0454f9c40b0b8">LIS</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927a3f7048bd00c71cf87c9b99715231">Loops</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8b177ea40e2001f49aa1eef67fe40c">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea455db969a62961ded94f9767bfaf24">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, PHIValPos &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3dde739e9157b469aefb9bf531ff8e">PHIValToPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from debug instruction number to PHI position during coalescing. <a href="#adf3dde739e9157b469aefb9bf531ff8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971e9d8c308f19e71e34c87a436c9419">RegToPHIIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of, for each VReg, which debug instruction numbers and corresponding PHIs are sensitive to coalescing. <a href="#a971e9d8c308f19e71e34c87a436c9419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, std::vector&lt; DbgValueLoc &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1f32e8fffd36820b4a57305cc01830">DbgVRegToValues</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9242333d474321e6f60fed88a40ce16">ShrinkMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A LaneMask to remember on which subregister live ranges we need to call shrinkToUses() later. <a href="#ac9242333d474321e6f60fed88a40ce16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13f0f5fe7caa69f5fbcb192ec17aba5b">ShrinkMainRange</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the main range of the currently coalesced intervals should be checked for smaller live intervals. <a href="#a13f0f5fe7caa69f5fbcb192ec17aba5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6696022731c214a613616632829ccc90">JoinGlobalCopies</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the coalescer should aggressively coalesce global copies in favor of keeping local copies. <a href="#a6696022731c214a613616632829ccc90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad359f59eafb8cc883a28bca77f9d3d2e">JoinSplitEdges</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the coalescer should aggressively coalesce fall-thru blocks exclusively containing copies. <a href="#ad359f59eafb8cc883a28bca77f9d3d2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82fd73dcac70e457c3b681845df9dfce">WorkList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy instructions yet to be coalesced. <a href="#a82fd73dcac70e457c3b681845df9dfce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4083e50440e8341167a6eae1607fe57">LocalWorkList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b2edb3abf228413d150024b583ce7d">ErasedInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of instruction pointers that have been erased, and that may be present in WorkList. <a href="#ad2b2edb3abf228413d150024b583ce7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835f4171022ebabafe78a4e6d550ca78">DeadDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dead instructions that are about to be deleted. <a href="#a835f4171022ebabafe78a4e6d550ca78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1102dc198e6c38e28e6e918251870439">InflateRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual registers to be considered for register class inflation. <a href="#a1102dc198e6c38e28e6e918251870439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1669b7b4f17e18b2593c9ad4c687ef0">ToBeUpdated</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The collection of live intervals which should have been updated immediately after rematerialiation but delayed until lateLiveIntervalUpdate is called. <a href="#ad1669b7b4f17e18b2593c9ad4c687ef0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, unsigned long &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768beb6bcdff869fc8d4883c591d3ce5">LargeLIVisitCounter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> how many times the large live interval with many valnos has been tried to join with other live interval. <a href="#a768beb6bcdff869fc8d4883c591d3ce5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4199b9116f012d49b3ea0ef0dee730fa">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class identification, replacement for typeinfo. <a href="#a4199b9116f012d49b3ea0ef0dee730fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### DbgValueLoc {#a8c7dfc993f06b8bc1aee810a92dbf2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::DbgValueLoc =  std::pair&lt;SlotIndex, MachineInstr *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug variable location tracking – for each VReg, maintain an ordered-by-slot-index set of DBG_VALUEs, to help quick identification of whether coalescing may change location validity.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegisterCoalescer() {#a0969ad06eb530c7fc3a7d2b8b9911fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::RegisterCoalescer ()</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a4199b9116f012d49b3ea0ef0dee730fa">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a238eae485eb747cb1ca649ea599b5c82">llvm::initializeRegisterCoalescerPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a3ae96d8cb445f62aa68d962e73704705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#a573df5c9c3024ebb646e15cc7450bf91">llvm::AnalysisUsage::addPreservedID</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a311f0d695e161f1c86664c796d6cfea0">llvm::MachineDominatorsID</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getClearedProperties() {#a7d6fd0a43420aacdcb844afc48c3b9cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::getClearedProperties ()</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### print() {#a4ef281c7441a224dc5d5e31f795ff2e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * m=nullptr)</td>
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

<p>Implement the dump method.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### releaseMemory() {#a55edcac6ac25614b341d7c34c5a2926c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::releaseMemory ()</td>
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

<p><a href="#a55edcac6ac25614b341d7c34c5a2926c">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed.</p>


<p>The default behavior of passes is to hold onto memory for the entire duration of their lifetime (which is the entire compile time). For pipelined passes, this is not a big deal because that memory gets recycled every time the pass is invoked on another program unit. For IP passes, it is more important to free memory when it is unused.</p>


<p>Optionally implement this function to release pass memory when it is no longer used.</p>


<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### runOnMachineFunction() {#aa408ab9747b8ce0bd0a81465c10e8f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; fn)</td>
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

<p>This is the pass entry point.</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44ad7c4bd83c337c86d34f6c2d8eba1e736">llvm::cl::BOU_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#a363e3f71faf094bba68a16bb32f43cff">buildVRegToDbgValueMap</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#afbdcbb3187e46987286c59c4963e21ae">llvm::LiveInterval::clearSubRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a233a6770a940d2da877cafd1263f9dc8">EnableGlobalCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a1322687bebc99c66aa3e9ed55b4e384d">llvm::TargetSubtargetInfo::enableJoinGlobalCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#ab8ef19815a62704144427de2c79d058e">EnableJoining</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#ab3861763540aea165ffd7a63a0bc2f06">EnableJoinSplits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4b94e0ca517e149914aa0c34ee06c9fa">llvm::MachineFunction::exposesReturnsTwice</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#aaf0c07cc1cdb9c78c6dfdfdd5913420a">llvm::SlotIndexes::getMBBStartIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#aa8b58294e993b77e8215298b1ef440a6">VerifyCoalescing</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addUndefFlag() {#a7094b4d51c802f98996727d6f0b0122a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::addUndefFlag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; Int, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> UseIdx, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, unsigned SubRegIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the given machine operand reads only undefined lanes add an undef flag.</p>


<p>This can happen when undef uses were previously concealed by a copy which we coalesced. Example: %0:sub0&lt;def,read-undef&gt; = ... %1 = COPY %0 &lt;– Coalescing COPY reveals undef = use %1:sub1 &lt;– hidden undef use</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### adjustCopiesBackFrom() {#aabd9b114350c1510e31adb543bacba61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::adjustCopiesBackFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CopyMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We found a non-trivially-coalescable copy.</p>


<p>If the source value number is defined by a copy from the destination reg see if we can merge these two destination reg valno# into a single value number, eliminating a copy. This returns true if an interval was modified.</p>


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### applyTerminalRule() {#a4d891694cb295affbd9c105fec7294ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::applyTerminalRule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Copy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether or not we should apply the terminal rule on the destination (Dst) of <span class="doxyComputerOutput">Copy</span>.</p>


<p>When the terminal rule applies, Copy is not profitable to coalesce. Dst is terminal if it has exactly one affinity (Dst, Src) and at least one interference (Dst, Dst2). If Dst is terminal, the terminal rule consists in checking that at least one of interfering node, say Dst2, has an affinity of equal or greater weight with Src. In that case, Dst2 and Dst will not be able to be both coalesced with Src. Since Dst2 exposes more coalescing opportunities than Dst, we can drop <span class="doxyComputerOutput">Copy</span>.</p>


<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### buildVRegToDbgValueMap() {#abcd287e6b0f450d939995f5bc7a9f04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::buildVRegToDbgValueMap (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walk over function and initialize the DbgVRegToValues map.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### canJoinPhys() {#a2358cdf7dd5c20ff7467363643607f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::canJoinPhys (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a copy involving a physreg should be joined.</p>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### checkMergingChangesDbgValues() {#aaf2eddaecf92f0b6359eaccae3eac808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::checkMergingChangesDbgValues (<a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; LHSVals, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; RHSVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether, after merging, any DBG_VALUEs would refer to a different value number than before merging, and whether this can be resolved.</p>


<p>If not, mark the DBG_VALUE as being undef.</p>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### checkMergingChangesDbgValuesImpl() {#afbb2800a5cfdd0733cbe24dc5f8c513c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::checkMergingChangesDbgValuesImpl (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; OtherRange, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; RegRange, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Vals2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### coalesceLocals() {#abf26f147cca7787d6a6714a4c0f42101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::coalesceLocals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Coalesce the LocalWorkList.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### copyCoalesceInMBB() {#ab74e0121710281929f61cb3a21886391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::copyCoalesceInMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Coalesce copies in the specified MBB, putting copies that cannot yet be coalesced into WorkList.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### copyCoalesceWorkList() {#a21c520bdcf7ee37905ffcbadfa13a386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::copyCoalesceWorkList (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; CurrList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to coalesce all copies in CurrList.</p>


<p>Returns true if any progress was made.</p>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### copyValueUndefInPredecessors() {#a655c1b576fce35cbf83af011c1d37ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::copyValueUndefInPredecessors (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult">LiveQueryResult</a> SLRQ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the incoming value defined by a COPY at <span class="doxyComputerOutput">SLRQ</span> in the subrange has no value defined in the predecessors.</p>


<p>If the incoming value is the same as defined by the copy itself, the value is considered undefined.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### deleteInstr() {#a5add2193b55fa2b5f4865ba846ea3914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::deleteInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Wrapper Method to do all the necessary work when an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is deleted.</p>


<p>Optimizations should use this to make sure that deleted instructions are always accounted for.</p>


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### eliminateDeadDefs() {#a7a4075764a012dafe047446c03ddff98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::eliminateDeadDefs (<a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> * Edit=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively eliminate dead defs in DeadDefs.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### eliminateUndefCopy() {#a7ba20b7c32f0906249d6977543d4b64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * RegisterCoalescer::eliminateUndefCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CopyMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle copies of undef values.</p>


<p>If the undef value is an incoming PHI value, it will convert <span class="doxyComputerOutput">CopyMI</span> to an IMPLICIT_DEF. Returns nullptr if <span class="doxyComputerOutput">CopyMI</span> was not in any way eliminable. Otherwise, it returns <span class="doxyComputerOutput">CopyMI</span> (which could be an IMPLICIT_DEF at this point).</p>


<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### hasOtherReachingDefs() {#ab78146ade2cca09d093a09e646487922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::hasOtherReachingDefs (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; IntA, <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; IntB, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * AValNo, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * BValNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there are definitions of IntB other than BValNo val# that can reach uses of AValno val# of IntA.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### isHighCostLiveInterval() {#acda4553af4bdd4a58a9c697f5b7bb1b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::isHighCostLiveInterval (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a live interval has many valnos and is coalesced with other live intervals many times, we regard such live interval as having high compile time cost.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### joinAllIntervals() {#ae9102fe3c500cef03dd5936b5c65b697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::joinAllIntervals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Join compatible live intervals.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### joinCopy() {#a2d2e2f179365b6d94d7c352fb96cd12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::joinCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CopyMI, bool &amp; Again, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CurrentErasedInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to join intervals corresponding to SrcReg/DstReg, which are the src/dst of the copy instruction CopyMI.</p>


<p>This returns true if the copy was successfully coalesced away. If it is not currently possible to coalesce this interval, but it may be possible if other things get coalesced, then it returns true by reference in 'Again'.</p>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### joinIntervals() {#a8aae63029f26808ab075291fd04b5d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::joinIntervals (<a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to join these two intervals.</p>


<p>On failure, this returns false. The output "SrcInt" will not have been modified, so we can use this information below to update aliases.</p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### joinReservedPhysReg() {#a5577f2b5142dcc2a326d22ea625cd95b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::joinReservedPhysReg (<a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt joining with a reserved physreg.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### joinSubRegRanges() {#a0a7da43b43fa0bc3ddc12a6845c640fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::joinSubRegRanges (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LRange, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; RRange, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Join the liveranges of two subregisters.</p>


<p>Joins <span class="doxyComputerOutput">RRange</span> into <span class="doxyComputerOutput">LRange</span>, <span class="doxyComputerOutput">RRange</span> may be invalid afterwards.</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### joinVirtRegs() {#a8fce080efda7d42c6666d5c511c6f9b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::joinVirtRegs (<a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt joining two virtual registers. Return true on success.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### lateLiveIntervalUpdate() {#a4ebe5b7afa42a06d3ddc7658287d4124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::lateLiveIntervalUpdate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If one def has many copy like uses, and those copy uses are all rematerialized, the live interval update needed for those rematerializations will be delayed and done all at once instead of being done multiple times.</p>


<p>This is to save compile cost because live interval update is costly.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### LRE\_WillEraseInstruction() {#a01b36d2af0621e232ba88ed398a23f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::LRE_WillEraseInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> callback for eliminateDeadDefs().</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### mergeSubRangeInto() {#aa594927fd89d6ab71047198e5cc65748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::mergeSubRangeInto (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; ToMerge, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP, unsigned DstIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> <span class="doxyComputerOutput">ToMerge</span> as a subregister liverange of <span class="doxyComputerOutput">LI</span>.</p>


<p>Subranges in <span class="doxyComputerOutput">LI</span> which only partially interfere with the desired LaneMask are split as necessary. <span class="doxyComputerOutput">LaneMask</span> are the lanes that <span class="doxyComputerOutput">ToMerge</span> will occupy in the coalescer register. <span class="doxyComputerOutput">LI</span> has its subrange lanemasks already adjusted to the coalesced register.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### reMaterializeTrivialDef() {#a29f67ac5c76b42c9305070ba09f20d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::reMaterializeTrivialDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CopyMI, bool &amp; IsDefCopy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the source of a copy is defined by a trivial computation, replace the copy by rematerialize the definition.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### removeCopyByCommutingDef() {#a013343bf430b98ca00397d521c24f8d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; RegisterCoalescer::removeCopyByCommutingDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CopyMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We found a non-trivially-coalescable copy.</p>


<p>If the source value number is defined by a commutable instruction and its other operand is coalesced to the copy dest register, see if we can transform the copy into a noop by commuting the definition. This returns a pair of two flags:</p>


<ul class="doxyList ">
<li>the first element is true if an interval was modified,</li>
<li>the second element is true if the destination interval needs to be shrunk after deleting the copy.</li>
</ul>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### removePartialRedundancy() {#af401ae3181b375370da57f82242977ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterCoalescer::removePartialRedundancy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CopyMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We found a copy which can be moved to its less frequent predecessor.</p>


<p>For copy B = A in BB2, if A is defined by A = B in BB0 which is a predecessor of BB2, and if B is not redefined on the way from A = B in BB0 to B = A in BB2, B = A in BB2 is partially redundant if the execution goes through the path from BB0 to BB2.</p>


<p>We may move B = A to the predecessor without such reversed copy. So we will transform the program from: BB0: A = B; BB1: ... ... / \ / BB2: ... B = A;</p>


<p>to:</p>


<p>BB0: BB1: A = B; ... ... B = A; / \ / BB2: ...</p>


<p>A special case is when BB0 and BB2 are the same BB which is the only BB in a loop: BB1: ... BB0/BB2: -— B = A; | ... | A = B; | |----— | We may hoist B = A from BB0/BB2 to BB1.</p>


<p>The major preconditions for correctness to remove such partial redundancy include:</p>


<ol class="doxyList" type="1">
<li>A in B = A in BB2 is defined by a PHI in BB2, and one operand of the PHI is defined by the reversed copy A = B in BB0.</li>
<li>No B is referenced from the start of BB2 to B = A.</li>
<li>No B is defined from A = B to the end of BB0.</li>
<li>BB1 has only one successor.</li>
</ol>

<p>2 and 4 implicitly ensure B is not live at the end of BB1. 4 guarantees BB2 is hotter than BB1, so we can only move a copy to a colder place, which not only prevent endless loop, but also make sure the movement of copy is beneficial.</p>


<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### setUndefOnPrunedSubRegUses() {#a2c81ce82e07a9c465584cab9ee4101a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::setUndefOnPrunedSubRegUses (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> PrunedLanes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set necessary undef flags on subregister uses after pruning out undef lane segments from the subrange.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### shrinkToUses() {#ab757d2f8e3c7b7f5dd03521a3545fbc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::shrinkToUses (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; * Dead=nullptr)</td>
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

<p>Wrapper method for.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">LiveIntervals::shrinkToUses</a>. This method does the proper fixing of the live-ranges when the afore mentioned method returns <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p></dd>
</dl>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### updateRegDefsUses() {#a39d9dfec4217cd95bf74dac69799d65d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterCoalescer::updateRegDefsUses (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, unsigned SubIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace all defs and uses of SrcReg to DstReg and update the subregister number if it is not zero.</p>


<p>If DstReg is a physical register and the existing subregister number of the def / use being updated is not zero, make sure to set it to the correct physical subregister.</p>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a9e8b177ea40e2001f49aa1eef67fe40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### DbgVRegToValues {#a3a1f32e8fffd36820b4a57305cc01830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, std::vector&lt;DbgValueLoc&gt; &gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::DbgVRegToValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### DeadDefs {#a835f4171022ebabafe78a4e6d550ca78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *, 8&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::DeadDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dead instructions that are about to be deleted.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### ErasedInstrs {#ad2b2edb3abf228413d150024b583ce7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 8&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::ErasedInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of instruction pointers that have been erased, and that may be present in WorkList.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### InflateRegs {#a1102dc198e6c38e28e6e918251870439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 8&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::InflateRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virtual registers to be considered for register class inflation.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### JoinGlobalCopies {#a6696022731c214a613616632829ccc90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::JoinGlobalCopies = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the coalescer should aggressively coalesce global copies in favor of keeping local copies.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### JoinSplitEdges {#ad359f59eafb8cc883a28bca77f9d3d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::JoinSplitEdges = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the coalescer should aggressively coalesce fall-thru blocks exclusively containing copies.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### LargeLIVisitCounter {#a768beb6bcdff869fc8d4883c591d3ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, unsigned long&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::LargeLIVisitCounter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> how many times the large live interval with many valnos has been tried to join with other live interval.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### LIS {#a94a4b5b483eeeebf19e0454f9c40b0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::LIS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### LocalWorkList {#ac4083e50440e8341167a6eae1607fe57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *, 8&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::LocalWorkList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### Loops {#a927a3f7048bd00c71cf87c9b99715231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoopInfo* anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::Loops = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### MF {#a0ff13ab4950e391dfc5d9526a2c64f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### MRI {#a133af1aee00d04d460f113d4286af07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### PHIValToPos {#adf3dde739e9157b469aefb9bf531ff8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, PHIValPos&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::PHIValToPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from debug instruction number to PHI position during coalescing.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### RegClassInfo {#aea455db969a62961ded94f9767bfaf24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterClassInfo anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::RegClassInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### RegToPHIIdx {#a971e9d8c308f19e71e34c87a436c9419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, SmallVector&lt;unsigned, 2&gt; &gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::RegToPHIIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of, for each VReg, which debug instruction numbers and corresponding PHIs are sensitive to coalescing.</p>


<p>Each VReg may have multiple PHI defs, at different positions.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### ShrinkMainRange {#a13f0f5fe7caa69f5fbcb192ec17aba5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::ShrinkMainRange = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the main range of the currently coalesced intervals should be checked for smaller live intervals.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### ShrinkMask {#ac9242333d474321e6f60fed88a40ce16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::ShrinkMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A LaneMask to remember on which subregister live ranges we need to call shrinkToUses() later.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### TII {#a16e661ae415777c0318a647cbc9b3e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### ToBeUpdated {#ad1669b7b4f17e18b2593c9ad4c687ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Register&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::ToBeUpdated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The collection of live intervals which should have been updated immediately after rematerialiation but delayed until lateLiveIntervalUpdate is called.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### TRI {#a23bddc5607b97be15c45e8ff7ca93430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### WorkList {#a82fd73dcac70e457c3b681845df9dfce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *, 8&gt; anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::WorkList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy instructions yet to be coalesced.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a4199b9116f012d49b3ea0ef0dee730fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char RegisterCoalescer::ID = 0</td>
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

<p>Class identification, replacement for typeinfo.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>Referenced by <a href="#a0969ad06eb530c7fc3a7d2b8b9911fa6">RegisterCoalescer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
