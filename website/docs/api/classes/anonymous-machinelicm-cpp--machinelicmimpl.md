---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machinelicm-cpp-/machinelicmimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineLICMImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MachineLICM.cpp}::MachineLICMImpl { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ac2316ff6765e5486dcc97bfc96e4f7dc">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0247333b7a49c261421926416fcaa3c7">MachineLICMImpl</a> (bool PreRegAlloc, Pass *LegacyPass, MachineFunctionAnalysisManager *MFAM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91e4daed2453931a75ea961f1dce12ad">run</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2684af865d4dac2c8f7f90dce136eef1">releaseMemory</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaccf0e32fa2cf707949d599fae0caf6">isExitBlock</a> (MachineLoop *CurLoop, const MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702b8c235f13bea0373c0739683037e4">HoistRegionPostRA</a> (MachineLoop *CurLoop, MachineBasicBlock *CurPreheader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk the specified region of the CFG and hoist loop invariants out to the preheader. <a href="#a702b8c235f13bea0373c0739683037e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1654d9d2243ce0d110ae6664a4c78e38">HoistPostRA</a> (MachineInstr *MI, unsigned Def, MachineLoop *CurLoop, MachineBasicBlock *CurPreheader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When an instruction is found to only use loop invariant operands that is safe to hoist, this instruction is called to do the dirty work. <a href="#a1654d9d2243ce0d110ae6664a4c78e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796cd5bb01fca33a4c821c2583e2e4a7">ProcessMI</a> (MachineInstr *MI, BitVector &amp;RUDefs, BitVector &amp;RUClobbers, SmallDenseSet&lt; int &gt; &amp;StoredFIs, SmallVectorImpl&lt; CandidateInfo &gt; &amp;Candidates, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine the instruction for potential LICM candidate. <a href="#a796cd5bb01fca33a4c821c2583e2e4a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c857381732a0b57fe99106903841756">AddToLiveIns</a> (MCRegister Reg, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add register 'Reg' to the livein sets of BBs in the current loop, and make sure it is not killed by any instructions in the loop. <a href="#a8c857381732a0b57fe99106903841756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7343922bf2b3bf96c3c5660e263c123">IsLICMCandidate</a> (MachineInstr &amp;I, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction may be a suitable candidate for LICM. <a href="#aa7343922bf2b3bf96c3c5660e263c123">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5346fe5b0bc093bdc8dd5a966874139">IsLoopInvariantInst</a> (MachineInstr &amp;I, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction is loop invariant. <a href="#aa5346fe5b0bc093bdc8dd5a966874139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9752d3131b5d26a1eaa260326f1904">HasLoopPHIUse</a> (const MachineInstr *MI, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified instruction is used by a phi node and hoisting it could cause a copy to be inserted. <a href="#adc9752d3131b5d26a1eaa260326f1904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1098abd6e8d12bc16e312f6b6f7e92e9">HasHighOperandLatency</a> (MachineInstr &amp;MI, unsigned DefIdx, Register Reg, MachineLoop *CurLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute operand latency between a def of 'Reg' and an use in the current loop, return true if the target considered it high. <a href="#a1098abd6e8d12bc16e312f6b6f7e92e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe5a98a17441879f7dbd2bb27dbb9b4">IsCheapInstruction</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is marked "cheap" or the operand latency between its def and a use is one or less. <a href="#abbe5a98a17441879f7dbd2bb27dbb9b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75dd891e73221e88576960c4e078ab6a">CanCauseHighRegPressure</a> (const SmallDenseMap&lt; unsigned, int &gt; &amp;Cost, bool Cheap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit BBs from header to current BB, check if hoisting an instruction of the given cost matrix can cause high register pressure. <a href="#a75dd891e73221e88576960c4e078ab6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11353822e71e5daeb8474a8f4552a8e6">UpdateBackTraceRegPressure</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverse the back trace from header to the current block and update their register pressures to reflect the effect of hoisting MI from the current block to the preheader. <a href="#a11353822e71e5daeb8474a8f4552a8e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83d8b46f30fe4c28b3bdf896a3f0b98f">IsProfitableToHoist</a> (MachineInstr &amp;MI, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is potentially profitable to hoist the given loop invariant. <a href="#a83d8b46f30fe4c28b3bdf896a3f0b98f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4a936a3486839f59eefeb2ffc3c532">IsGuaranteedToExecute</a> (MachineBasicBlock *BB, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if this mbb is guaranteed to execute. <a href="#a6b4a936a3486839f59eefeb2ffc3c532">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb99175a283ce062bb2291aa786c756">isTriviallyReMaterializable</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">MI</span> is trivially remateralizable and if it does not have any virtual register uses. <a href="#aecb99175a283ce062bb2291aa786c756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8edd3f19c2ff7830dc9c4aad01517334">EnterScope</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b6fbfb510ee76f81b0422fbd00a5346">ExitScope</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965d416e66d43721ccf95105d8c52b1e">ExitScopeIfDone</a> (MachineDomTreeNode *Node, DenseMap&lt; MachineDomTreeNode *, unsigned &gt; &amp;OpenChildren, const DenseMap&lt; MachineDomTreeNode *, MachineDomTreeNode * &gt; &amp;ParentMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy scope for the MBB that corresponds to the given dominator tree node if its a leaf or all of its children are done. <a href="#a965d416e66d43721ccf95105d8c52b1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f0ad361c882876dee6b7abfe7e8c9f">HoistOutOfLoop</a> (MachineDomTreeNode *HeaderN, MachineLoop *CurLoop, MachineBasicBlock *CurPreheader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk the specified loop in the CFG (defined by all blocks dominated by the specified header block, and that are in the current loop) in depth first order w.r.t the <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a>. <a href="#a69f0ad361c882876dee6b7abfe7e8c9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cd12604fa81b0edbbb0d249a452f3e">InitRegPressure</a> (MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all virtual register references that are liveout of the preheader to initialize the starting "register pressure". <a href="#a52cd12604fa81b0edbbb0d249a452f3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb72483ed8bd83fcd2c748b0200dc826">calcRegisterCost</a> (const MachineInstr *MI, bool ConsiderSeen, bool ConsiderUnseenAsDef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the additional register pressure that the registers used in MI cause. <a href="#abb72483ed8bd83fcd2c748b0200dc826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ee52ec45a36b67231eb9f3d8ab8767">UpdateRegPressure</a> (const MachineInstr *MI, bool ConsiderUnseenAsDef=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update estimate of register pressure after the specified instruction. <a href="#aa6ee52ec45a36b67231eb9f3d8ab8767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a0b0e496c48d5fb81059d80d27dd8c">ExtractHoistableLoad</a> (MachineInstr *MI, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unfold a load from the given machineinstr if the load itself could be hoisted. <a href="#a99a0b0e496c48d5fb81059d80d27dd8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d61d964ad01b6e1f3bced6e16166b6">LookForDuplicate</a> (const MachineInstr *MI, std::vector&lt; MachineInstr * &gt; &amp;PrevMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find an instruction amount PrevMIs that is a duplicate of MI. <a href="#ab0d61d964ad01b6e1f3bced6e16166b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70d8a0398db513ef915137f18c3d191">EliminateCSE</a> (MachineInstr *MI, DenseMap&lt; unsigned, std::vector&lt; MachineInstr * &gt; &gt;::iterator &amp;CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a LICM'ed instruction, look for an instruction on the preheader that computes the same value. <a href="#af70d8a0398db513ef915137f18c3d191">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60334303487ce2d3c610ae328835a358">MayCSE</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given instruction will be CSE'd if it's hoisted out of the loop. <a href="#a60334303487ce2d3c610ae328835a358">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add14e464d3ade123009b5e6bbe3d4ca7">Hoist</a> (MachineInstr *MI, MachineBasicBlock *Preheader, MachineLoop *CurLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When an instruction is found to use only loop invariant operands that are safe to hoist, this instruction is called to do the dirty work. <a href="#add14e464d3ade123009b5e6bbe3d4ca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca571c998471a7c9e397b7d1defa55c">InitCSEMap</a> (MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the CSE map with instructions that are in the current loop preheader that may become duplicates of instructions that are hoisted out of the loop. <a href="#adca571c998471a7c9e397b7d1defa55c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2cef320d6e6e0d7b50ef50daf0efb9e">InitializeLoadsHoistableLoops</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize AllowedToHoistLoads with information about whether invariant loads can be moved outside a given loop. <a href="#ab2cef320d6e6e0d7b50ef50daf0efb9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b64891ef77cf227e7314b28edf367cf">isTgtHotterThanSrc</a> (MachineBasicBlock *SrcBlock, MachineBasicBlock *TgtBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the target basic block at least "BlockFrequencyRatioThreshold" times hotter than the source basic block. <a href="#a1b64891ef77cf227e7314b28edf367cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aae646ac9feef3a32db02fcb3d1e8e7">getCurPreheader</a> (MachineLoop *CurLoop, MachineBasicBlock *CurPreheader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the preheader for the current loop, splitting a critical edge if needed. <a href="#a5aae646ac9feef3a32db02fcb3d1e8e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312c874214965baf20e667dfc3de09c3">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase">TargetLoweringBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4090815d463c52e5f35d3f770358dc">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d20e1168e8ced0478f4e95f67f93b89">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57c663e40528865f8d8e624bc22ceaf">MFI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff53593c166560b504bd365d52e6c791">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486e4cb3ff424de7d66e8efa457bdd84">SchedModel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f438bf350ac435667f061c315eceb1">PreRegAlloc</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352c3b26b9c906ccae923758d998b868">HasProfileData</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d67b2e011b59e33eb918838d1b593b">LegacyPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f2c09f9c5774aeacc8c2952e3ed93f">MFAM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a07d0c2c1dab05a3fc12889577d778f">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f8c707bf43eab787452e5c3006f8fa3">MBFI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d320a45d3805dc1f6f0894e6ef804c">MLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedomtreeupdater">MachineDomTreeUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac744619f3debc3c281bc079847afe5ff">MDTU</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779f27074fe9bc5124a75738a267d002">Changed</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952f0c3c10c188595142551e7921dfe3">FirstInLoop</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3acbeedc8c3687d6f264814bb776b40">AllowedToHoistLoads</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 8 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb03c1e9133b11cb79139d175a2eb03">ExitBlockMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f478099d177160f4f49e2e6b38de958">RegSeen</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7174ede8999d34743e44a75d8a9104">RegPressure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d61e76fe6c88ae1b95210473f591f2">RegLimit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0a4b4031ab50d4a5572c285c6657a1">BackTrace</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7813831d5b9f978712ffc91ab6c08ed0">CSEMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a2e7034dc3b46b0bc3c93061936935">SpeculationState</a> = SpeculateUnknown</td>
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


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ac2316ff6765e5486dcc97bfc96e4f7dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">SpeculateFalse<a id="ac2316ff6765e5486dcc97bfc96e4f7dca15ad7b25b3414aee0faaa402c80b8c13"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SpeculateTrue<a id="ac2316ff6765e5486dcc97bfc96e4f7dca4a5f08d0dc6a1dde3ba3198e5cbf1c3e"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SpeculateUnknown<a id="ac2316ff6765e5486dcc97bfc96e4f7dcaf2842a0c011097d25284f73acf7d646b"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineLICMImpl() {#a0247333b7a49c261421926416fcaa3c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineLICM.cpp}::MachineLICMImpl::MachineLICMImpl (bool PreRegAlloc, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * LegacyPass, <a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> * MFAM)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinelicmbasepass/#a32a6c3c28482b75adeee98d1abf60ff9">llvm::MachineLICMBasePass&lt; DerivedT, PreRegAlloc &gt;::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### releaseMemory() {#a2684af865d4dac2c8f7f90dce136eef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineLICM.cpp}::MachineLICMImpl::releaseMemory ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>


<p>Referenced by <a href="#a91e4daed2453931a75ea961f1dce12ad">run</a>.</p>

</div>
</div>

### run() {#a91e4daed2453931a75ea961f1dce12ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a2d693e123c2899d7944b0180099ce116">DisableHoistingToHotterBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a25976fc86125d38cce05518bf65c9792">GET_RESULT</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9084ce2576fad285c1c0dc1e165dd4b6">llvm::Function::hasProfileData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a4fbc052b34762d6255d86806a81e5009">HoistConstLoads</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a600fe222d8c18b039644ab85c091b407a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="#a2684af865d4dac2c8f7f90dce136eef1">releaseMemory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicmbase/#a958bbc11c0ba4671d3995938dc471fba">anonymous{MachineLICM.cpp}::MachineLICMBase::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddToLiveIns() {#a8c857381732a0b57fe99106903841756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::AddToLiveIns (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add register 'Reg' to the livein sets of BBs in the current loop, and make sure it is not killed by any instructions in the loop.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### calcRegisterCost() {#abb72483ed8bd83fcd2c748b0200dc826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt; unsigned, int &gt; MachineLICMImpl::calcRegisterCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, bool ConsiderSeen, bool ConsiderUnseenAsDef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the additional register pressure that the registers used in MI cause.</p>


<p>If 'ConsiderSeen' is true, updates 'RegSeen' and uses the information to figure out which usages are live-ins. FIXME: Figure out a way to consider 'RegSeen' from all code paths.</p>


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### CanCauseHighRegPressure() {#a75dd891e73221e88576960c4e078ab6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::CanCauseHighRegPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, int &gt; &amp; Cost, bool Cheap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit BBs from header to current BB, check if hoisting an instruction of the given cost matrix can cause high register pressure.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### EliminateCSE() {#af70d8a0398db513ef915137f18c3d191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::EliminateCSE (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &amp; CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a LICM'ed instruction, look for an instruction on the preheader that computes the same value.</p>


<p>If it's found, do a RAU on with the definition of the existing instruction rather than hoisting the instruction to the preheader.</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### EnterScope() {#a8edd3f19c2ff7830dc9c4aad01517334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::EnterScope (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### ExitScope() {#a5b6fbfb510ee76f81b0422fbd00a5346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::ExitScope (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### ExitScopeIfDone() {#a965d416e66d43721ccf95105d8c52b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::ExitScopeIfDone (<a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> *, unsigned &gt; &amp; OpenChildren, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> * &gt; &amp; ParentMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy scope for the MBB that corresponds to the given dominator tree node if its a leaf or all of its children are done.</p>


<p>Walk up the dominator tree to destroy ancestors which are now done.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### ExtractHoistableLoad() {#a99a0b0e496c48d5fb81059d80d27dd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineLICMImpl::ExtractHoistableLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unfold a load from the given machineinstr if the load itself could be hoisted.</p>


<p>Return the unfolded and hoistable load, or null if the load couldn't be unfolded or if it wouldn't be hoistable.</p>


<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### getCurPreheader() {#a5aae646ac9feef3a32db02fcb3d1e8e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineLICMImpl::getCurPreheader (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * CurPreheader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the preheader for the current loop, splitting a critical edge if needed.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### HasHighOperandLatency() {#a1098abd6e8d12bc16e312f6b6f7e92e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::HasHighOperandLatency (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute operand latency between a def of 'Reg' and an use in the current loop, return true if the target considered it high.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### HasLoopPHIUse() {#adc9752d3131b5d26a1eaa260326f1904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::HasLoopPHIUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified instruction is used by a phi node and hoisting it could cause a copy to be inserted.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### Hoist() {#add14e464d3ade123009b5e6bbe3d4ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineLICMImpl::Hoist (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Preheader, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When an instruction is found to use only loop invariant operands that are safe to hoist, this instruction is called to do the dirty work.</p>


<p>It returns true if the instruction is hoisted.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### HoistOutOfLoop() {#a69f0ad361c882876dee6b7abfe7e8c9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::HoistOutOfLoop (<a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> * HeaderN, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * CurPreheader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walk the specified loop in the CFG (defined by all blocks dominated by the specified header block, and that are in the current loop) in depth first order w.r.t the <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a>.</p>


<p>This allows us to visit definitions before uses, allowing us to hoist a loop body in one pass without iteration.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### HoistPostRA() {#a1654d9d2243ce0d110ae6664a4c78e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::HoistPostRA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Def, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * CurPreheader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When an instruction is found to only use loop invariant operands that is safe to hoist, this instruction is called to do the dirty work.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### HoistRegionPostRA() {#a702b8c235f13bea0373c0739683037e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::HoistRegionPostRA (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * CurPreheader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walk the specified region of the CFG and hoist loop invariants out to the preheader.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### InitCSEMap() {#adca571c998471a7c9e397b7d1defa55c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::InitCSEMap (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the CSE map with instructions that are in the current loop preheader that may become duplicates of instructions that are hoisted out of the loop.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### InitializeLoadsHoistableLoops() {#ab2cef320d6e6e0d7b50ef50daf0efb9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::InitializeLoadsHoistableLoops ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize AllowedToHoistLoads with information about whether invariant loads can be moved outside a given loop.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### InitRegPressure() {#a52cd12604fa81b0edbbb0d249a452f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::InitRegPressure (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all virtual register references that are liveout of the preheader to initialize the starting "register pressure".</p>


<p>Note this does not count live through (livein but not used) registers.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### IsCheapInstruction() {#abbe5a98a17441879f7dbd2bb27dbb9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::IsCheapInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is marked "cheap" or the operand latency between its def and a use is one or less.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### isExitBlock() {#adaccf0e32fa2cf707949d599fae0caf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineLICM.cpp}::MachineLICMImpl::isExitBlock (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### IsGuaranteedToExecute() {#a6b4a936a3486839f59eefeb2ffc3c532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::IsGuaranteedToExecute (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if this mbb is guaranteed to execute.</p>


<p>If not then a load from this mbb may not be safe to hoist.</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### IsLICMCandidate() {#aa7343922bf2b3bf96c3c5660e263c123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::IsLICMCandidate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the instruction may be a suitable candidate for LICM.</p>


<p>e.g. If the instruction is a call, then it's obviously not safe to hoist it.</p>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### IsLoopInvariantInst() {#aa5346fe5b0bc093bdc8dd5a966874139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::IsLoopInvariantInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the instruction is loop invariant.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### IsProfitableToHoist() {#a83d8b46f30fe4c28b3bdf896a3f0b98f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::IsProfitableToHoist (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is potentially profitable to hoist the given loop invariant.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### isTgtHotterThanSrc() {#a1b64891ef77cf227e7314b28edf367cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::isTgtHotterThanSrc (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SrcBlock, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TgtBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is the target basic block at least "BlockFrequencyRatioThreshold" times hotter than the source basic block.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### isTriviallyReMaterializable() {#aecb99175a283ce062bb2291aa786c756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::isTriviallyReMaterializable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if <span class="doxyComputerOutput">MI</span> is trivially remateralizable and if it does not have any virtual register uses.</p>


<p>Even though rematerializable RA might not actually rematerialize it in this scenario. In that case we do not want to hoist such instruction out of the loop in a belief RA will sink it back if needed.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### LookForDuplicate() {#ab0d61d964ad01b6e1f3bced6e16166b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineLICMImpl::LookForDuplicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; PrevMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find an instruction amount PrevMIs that is a duplicate of MI.</p>


<p>Return this instruction if it's found.</p>


<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### MayCSE() {#a60334303487ce2d3c610ae328835a358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLICMImpl::MayCSE (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given instruction will be CSE'd if it's hoisted out of the loop.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### ProcessMI() {#a796cd5bb01fca33a4c821c2583e2e4a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::ProcessMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RUDefs, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RUClobbers, <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; int &gt; &amp; StoredFIs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; CandidateInfo &gt; &amp; Candidates, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examine the instruction for potential LICM candidate.</p>


<p>Also gather register def and frame object update information.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### UpdateBackTraceRegPressure() {#a11353822e71e5daeb8474a8f4552a8e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::UpdateBackTraceRegPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Traverse the back trace from header to the current block and update their register pressures to reflect the effect of hoisting MI from the current block to the preheader.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### UpdateRegPressure() {#aa6ee52ec45a36b67231eb9f3d8ab8767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineLICMImpl::UpdateRegPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, bool ConsiderUnseenAsDef=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update estimate of register pressure after the specified instruction.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a9a07d0c2c1dab05a3fc12889577d778f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{MachineLICM.cpp}::MachineLICMImpl::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### AllowedToHoistLoads {#ac3acbeedc8c3687d6f264814bb776b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;MachineLoop *, bool&gt; anonymous{MachineLICM.cpp}::MachineLICMImpl::AllowedToHoistLoads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### BackTrace {#afc0a4b4031ab50d4a5572c285c6657a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SmallVector&lt;unsigned, 8&gt;, 16&gt; anonymous{MachineLICM.cpp}::MachineLICMImpl::BackTrace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### Changed {#a779f27074fe9bc5124a75738a267d002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineLICM.cpp}::MachineLICMImpl::Changed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### CSEMap {#a7813831d5b9f978712ffc91ab6c08ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, DenseMap&lt;unsigned, std::vector&lt;MachineInstr *&gt; &gt; &gt; anonymous{MachineLICM.cpp}::MachineLICMImpl::CSEMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### ExitBlockMap {#a4cb03c1e9133b11cb79139d175a2eb03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineLoop *, SmallVector&lt;MachineBasicBlock *, 8&gt; &gt; anonymous{MachineLICM.cpp}::MachineLICMImpl::ExitBlockMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### FirstInLoop {#a952f0c3c10c188595142551e7921dfe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineLICM.cpp}::MachineLICMImpl::FirstInLoop = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### HasProfileData {#a352c3b26b9c906ccae923758d998b868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineLICM.cpp}::MachineLICMImpl::HasProfileData = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### LegacyPass {#ae1d67b2e011b59e33eb918838d1b593b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass* anonymous{MachineLICM.cpp}::MachineLICMImpl::LegacyPass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### MBFI {#a8f8c707bf43eab787452e5c3006f8fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo* anonymous{MachineLICM.cpp}::MachineLICMImpl::MBFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### MDTU {#ac744619f3debc3c281bc079847afe5ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDomTreeUpdater* anonymous{MachineLICM.cpp}::MachineLICMImpl::MDTU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### MFAM {#a14f2c09f9c5774aeacc8c2952e3ed93f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionAnalysisManager* anonymous{MachineLICM.cpp}::MachineLICMImpl::MFAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### MFI {#ae57c663e40528865f8d8e624bc22ceaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFrameInfo* anonymous{MachineLICM.cpp}::MachineLICMImpl::MFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### MLI {#af5d320a45d3805dc1f6f0894e6ef804c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* anonymous{MachineLICM.cpp}::MachineLICMImpl::MLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### MRI {#aff53593c166560b504bd365d52e6c791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{MachineLICM.cpp}::MachineLICMImpl::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### PreRegAlloc {#a84f438bf350ac435667f061c315eceb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineLICM.cpp}::MachineLICMImpl::PreRegAlloc = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### RegLimit {#a45d61e76fe6c88ae1b95210473f591f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; anonymous{MachineLICM.cpp}::MachineLICMImpl::RegLimit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### RegPressure {#a5a7174ede8999d34743e44a75d8a9104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; anonymous{MachineLICM.cpp}::MachineLICMImpl::RegPressure</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### RegSeen {#a3f478099d177160f4f49e2e6b38de958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;Register&gt; anonymous{MachineLICM.cpp}::MachineLICMImpl::RegSeen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### SchedModel {#a486e4cb3ff424de7d66e8efa457bdd84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSchedModel anonymous{MachineLICM.cpp}::MachineLICMImpl::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### SpeculationState {#a59a2e7034dc3b46b0bc3c93061936935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineLICM.cpp}::MachineLICMImpl::SpeculationState = SpeculateUnknown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### TII {#a312c874214965baf20e667dfc3de09c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{MachineLICM.cpp}::MachineLICMImpl::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### TLI {#a7f4090815d463c52e5f35d3f770358dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLoweringBase* anonymous{MachineLICM.cpp}::MachineLICMImpl::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

### TRI {#a5d20e1168e8ced0478f4e95f67f93b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{MachineLICM.cpp}::MachineLICMImpl::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp">MachineLICM.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
