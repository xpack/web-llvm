---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-regallocfast-cpp-/regallocfastimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegAllocFastImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{RegAllocFast.cpp}::RegAllocFastImpl { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1cc2e41ca3cb2a3d0acd7e1cdf7a5f7">LiveRegMap</a> = <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; LiveReg, <a href="/web-llvm/docs/api/structs/llvm/identity">identity</a>&lt; unsigned &gt;, uint16_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">RegUnitState { <a href="#aa63abd7ad9529a970db489adffa96ef3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State of a register unit. <a href="#aa63abd7ad9529a970db489adffa96ef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#abaf34405b12224d464b30dcf0da22ff9">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031240ad13338dc7e24d587d040781a8">RegAllocFastImpl</a> (const RegAllocFilterFunc F=nullptr, bool ClearVirtRegs_=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7ba17c073b2d0a80ca229f3166b6a9">runOnMachineFunction</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5644ab844a01048a9bbc7fb96ead372">setPhysRegState</a> (MCRegister PhysReg, unsigned NewState)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abdb788a4a19279967a9cae1037b947">isPhysRegFree</a> (MCPhysReg PhysReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809b7fd311fae596fa8c6ea7881db596">markRegUsedInInstr</a> (MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark a physreg as used in this instruction. <a href="#a809b7fd311fae596fa8c6ea7881db596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a384db7e0b19119ec8d812c4c6d981520">isClobberedByRegMasks</a> (MCPhysReg PhysReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6c633cc28f2091d2ff1bdc3ff20583">isRegUsedInInstr</a> (MCPhysReg PhysReg, bool LookAtPhysRegUses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if a physreg or any of its aliases are used in this instruction. <a href="#ada6c633cc28f2091d2ff1bdc3ff20583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5475c0fcc42029689825a4858fe8c0c">markPhysRegUsedInInstr</a> (MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark physical register as being used in a register use operand. <a href="#ab5475c0fcc42029689825a4858fe8c0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ccad68acf8ce4b6af06ce5481d26302">unmarkRegUsedInInstr</a> (MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove mark of physical register being used in the instruction. <a href="#a5ccad68acf8ce4b6af06ce5481d26302">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3f8f6daf8bccdbabf00341fd6222f4">allocateBasicBlock</a> (MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae777723ecd7c67e403f297a626170c5f">addRegClassDefCounts</a> (MutableArrayRef&lt; unsigned &gt; RegClassDefCounts, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count number of defs consumed from each register class by <span class="doxyComputerOutput">Reg</span>. <a href="#ae777723ecd7c67e403f297a626170c5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae956237ad0d01e8ef492cb23a99277ef">findAndSortDefOperandIndexes</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute DefOperandIndexes so it contains the indices of "def" operands that are to be allocated. <a href="#ae956237ad0d01e8ef492cb23a99277ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b85173f70b3e9ffe3636e5b6a648be">allocateInstruction</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ffbb2e34f3a0d85c3b6c4e9b974e311">handleDebugValue</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d566810b4163f0ffc83dc17376c0c1">handleBundle</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d36bad425a81d7bc8c047258c3ec3d4">usePhysReg</a> (MachineInstr &amp;MI, MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle the direct use of a physical register. <a href="#a1d36bad425a81d7bc8c047258c3ec3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8495a76b4ae9d2a55b35d33b2718efc2">definePhysReg</a> (MachineInstr &amp;MI, MCPhysReg PhysReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65978b2b5f53b012bab341133582c3d">displacePhysReg</a> (MachineInstr &amp;MI, MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark PhysReg as reserved or free after spilling any virtregs. <a href="#ac65978b2b5f53b012bab341133582c3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26814c72c082867fa6c6de02ae3cfbc4">freePhysReg</a> (MCPhysReg PhysReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1073ea39561cfa8a50b7dfe215d70893">calcSpillCost</a> (MCPhysReg PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of spilling clearing out PhysReg and aliases so it is free for allocation. <a href="#a1073ea39561cfa8a50b7dfe215d70893">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset/#a9dd9e59619f2ce3f425abb29690ff88d">LiveRegMap::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d5cff8acd419898ee18a9ab51fc281">findLiveVirtReg</a> (Register VirtReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset/#adcffed9f9e28c03e4b254b733dd9a9d1">LiveRegMap::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb6b7200803d79fcd0eaf3c6f2105e0">findLiveVirtReg</a> (Register VirtReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d33a60b2f24edcaa138079ddadcc2d4">assignVirtToPhysReg</a> (MachineInstr &amp;MI, LiveReg &amp;, MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method updates local state so that we know that PhysReg is the proper container for VirtReg now. <a href="#a1d33a60b2f24edcaa138079ddadcc2d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fce57472f231b4a9bb43494cbf82a8e">allocVirtReg</a> (MachineInstr &amp;MI, LiveReg &amp;LR, Register Hint, bool LookAtPhysRegUses=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates a physical register for VirtReg. <a href="#a9fce57472f231b4a9bb43494cbf82a8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8711f2bf7f22256b9f2350a094bfd2fb">allocVirtRegUndef</a> (MachineOperand &amp;MO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1dfcd66b9597ffffdf947620c136bc">assignDanglingDebugValues</a> (MachineInstr &amp;Def, Register VirtReg, MCPhysReg Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089933cbfcc685d258c18fbbb14bdf4a">defineLiveThroughVirtReg</a> (MachineInstr &amp;MI, unsigned OpNum, Register VirtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variation of defineVirtReg() with special handling for livethrough regs (tied or earlyclobber) that may interfere with preassigned uses. <a href="#a089933cbfcc685d258c18fbbb14bdf4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6746be2a18b75a4ae1b6105f3ce8cda">defineVirtReg</a> (MachineInstr &amp;MI, unsigned OpNum, Register VirtReg, bool LookAtPhysRegUses=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates a register for VirtReg definition. <a href="#aa6746be2a18b75a4ae1b6105f3ce8cda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9405629c9047907677a00235d54a3ca">useVirtReg</a> (MachineInstr &amp;MI, MachineOperand &amp;MO, Register VirtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates a register for a VirtReg use. <a href="#ab9405629c9047907677a00235d54a3ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c76c34aba8142537d9851152f28314a">getErrorAssignment</a> (const LiveReg &amp;LR, MachineInstr &amp;MI, const TargetRegisterClass &amp;RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query a physical register to use as a filler in contexts where the allocation has failed. <a href="#a1c76c34aba8142537d9851152f28314a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502c898eeac950d667f330a0aecb1c87">getMBBBeginInsertionPoint</a> (MachineBasicBlock &amp;MBB, SmallSet&lt; Register, 2 &gt; &amp;PrologLiveIns) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get basic block begin insertion point. <a href="#a502c898eeac950d667f330a0aecb1c87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a09537c187f2785a4b28cd0a8b8f1e4">reloadAtBegin</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reload all currently assigned virtual registers. <a href="#a2a09537c187f2785a4b28cd0a8b8f1e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16925e9ab666c7df9c4763c18c66592d">setPhysReg</a> (MachineInstr &amp;MI, MachineOperand &amp;MO, MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Changes operand OpNum in MI the refer the PhysReg, considering subregs. <a href="#a16925e9ab666c7df9c4763c18c66592d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc48ddf1fcef0122a466969eb008e1de">traceCopies</a> (Register VirtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if any of <span class="doxyComputerOutput">VirtReg's</span> definitions is a copy. <a href="#acc48ddf1fcef0122a466969eb008e1de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65189b14b4d7ee62799c271648d568ae">traceCopyChain</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a127a666595b0a02350dd97bf35384d92">shouldAllocateRegister</a> (const Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292781887605b4560482cfcb599ab35d">getStackSpaceFor</a> (Register VirtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This allocates space for the specified virtual register to be held on the stack. <a href="#a292781887605b4560482cfcb599ab35d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767e653113fcad05b575f98901106af8">spill</a> (MachineBasicBlock::iterator Before, Register VirtReg, MCPhysReg AssignedReg, bool Kill, bool LiveOut)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert spill instruction for <span class="doxyComputerOutput">AssignedReg</span> before <span class="doxyComputerOutput">Before</span>. <a href="#a767e653113fcad05b575f98901106af8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0594fecdc7f6b9b4021422e3baa1162">reload</a> (MachineBasicBlock::iterator Before, Register VirtReg, MCPhysReg PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert reload instruction for <span class="doxyComputerOutput">PhysReg</span> before <span class="doxyComputerOutput">Before</span>. <a href="#ac0594fecdc7f6b9b4021422e3baa1162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293bc88ed331a85b94fc103cd94e4b74">mayLiveOut</a> (Register VirtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns false if <span class="doxyComputerOutput">VirtReg</span> is known to not live out of the current block. <a href="#a293bc88ed331a85b94fc103cd94e4b74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23045931899133c161a17ca999b10e0">mayLiveIn</a> (Register VirtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns false if <span class="doxyComputerOutput">VirtReg</span> is known to not be live into the current block. <a href="#ae23045931899133c161a17ca999b10e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7704dd7662107307e30c5c5d587724b8">dumpState</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1082edd3a979e58af7ab50a68c83ae20">ClearVirtRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc12ec1a31239d49167e05336c01768c">MFI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3231b0f880a1b7f30e4e3985e454555">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf943abb9e3947f71a2d08b6da091bbf">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3a64638da21704affce53cf30b3f61">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c71da83274294fb1810f4c67c26f75">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4e7265a1321b278ff1f10bbe4c93fe">ShouldAllocateRegisterImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefafa1ab55335f5ce4f1d2fdc717fefc">MBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic block currently being allocated. <a href="#aefafa1ab55335f5ce4f1d2fdc717fefc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; int, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a4c966cbbd5d45a765f9a12aa8b83c">StackSlotForVirtReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps virtual regs to the frame index where these values are spilled. <a href="#ac0a4c966cbbd5d45a765f9a12aa8b83c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset">LiveRegMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfcdb2e05546d88462c73b2ff66ed8a">LiveVirtRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This map contains entries for each virtual register that is currently available in a physical register. <a href="#a4bfcdb2e05546d88462c73b2ff66ed8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ea713485f282f9ecfda102a5948e22">BundleVirtRegsMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores assigned virtual registers present in the bundle MI. <a href="#a33ea713485f282f9ecfda102a5948e22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6138f7b4d26419264942a829914ad916">LiveDbgValueMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c739cb1a09da2b746eafe13134766a">DanglingDbgValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of DBG_VALUE that we encountered without the vreg being assigned because they were placed after the last use of the vreg. <a href="#a02c739cb1a09da2b746eafe13134766a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625bf122ca23dfe2a4c7bf15d8005967">MayLiveAcrossBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has a bit set for every virtual register for which it was determined that it is alive across blocks. <a href="#a625bf122ca23dfe2a4c7bf15d8005967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea9ce7da3ab9cc05674a678b2432738">RegUnitStates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps each physical register to a RegUnitState enum or virtual register. <a href="#a2ea9ce7da3ab9cc05674a678b2432738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799c5ed4b5fa932d90e0230903645d73">Coalesced</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da1b458e56a0ca18b9262df223bfaf5">InstrGen</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track register units that are used in the current instruction, and so cannot be allocated. <a href="#a3da1b458e56a0ca18b9262df223bfaf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab96369ff42bae07d596d7a47249584fd">UsedInInstr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a159019ad49af6e01f62f57b2a68da0ad">DefOperandIndexes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0fddf1d50ea570d6fb4a768c77b8a4">RegMasks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/instrposindexes">InstrPosIndexes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d1e12ec181365b6079a29b3c64eda6">PosIndexes</a></td>
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


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LiveRegMap {#ac1cc2e41ca3cb2a3d0acd7e1cdf7a5f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{RegAllocFast.cpp}::RegAllocFastImpl::LiveRegMap =  SparseSet&lt;LiveReg, identity&lt;unsigned&gt;, uint16_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#abaf34405b12224d464b30dcf0da22ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
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
<td class="doxyEnumItemName">spillClean<a id="abaf34405b12224d464b30dcf0da22ff9a82cf687d3789ec254e2a312569784443"></a></td>
<td class="doxyEnumItemDescription"> (= 50)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spillDirty<a id="abaf34405b12224d464b30dcf0da22ff9a0431070d94d4728220cb94c82616be47"></a></td>
<td class="doxyEnumItemDescription"> (= 100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spillPrefBonus<a id="abaf34405b12224d464b30dcf0da22ff9a2552e7e9ac4d10f4d74a64f82ce18227"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spillImpossible<a id="abaf34405b12224d464b30dcf0da22ff9aa695b0a5c285cb40861077310a1e586e"></a></td>
<td class="doxyEnumItemDescription"> (= ~0u)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### RegUnitState {#aa63abd7ad9529a970db489adffa96ef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{RegAllocFast.cpp}::RegAllocFastImpl::RegUnitState </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State of a register unit.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">regFree<a id="aa63abd7ad9529a970db489adffa96ef3acf14924a9033568a11b9292354f2ffda"></a></td>
<td class="doxyEnumItemDescription">A free register is not currently in use and can be allocated immediately without checking aliases</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">regPreAssigned<a id="aa63abd7ad9529a970db489adffa96ef3afaa43b4a8da660f49b16e68b65d7f4a2"></a></td>
<td class="doxyEnumItemDescription">A pre-assigned register has been assigned before register allocation (e.g., setting up a call parameter)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">regLiveIn<a id="aa63abd7ad9529a970db489adffa96ef3a874c16143d308fbe223017b2fa259363"></a></td>
<td class="doxyEnumItemDescription">Used temporarily in reloadAtBegin() to mark register units that are live-in to the basic block</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegAllocFastImpl() {#a031240ad13338dc7e24d587d040781a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RegAllocFast.cpp}::RegAllocFastImpl::RegAllocFastImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a> F=nullptr, bool ClearVirtRegs_=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>


<p>References <a href="#a1082edd3a979e58af7ab50a68c83ae20">ClearVirtRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnMachineFunction() {#acc7ba17c073b2d0a80ca229f3166b6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>


<p>References <a href="#a1082edd3a979e58af7ab50a68c83ae20">ClearVirtRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRegClassDefCounts() {#ae777723ecd7c67e403f297a626170c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::addRegClassDefCounts (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; unsigned &gt; RegClassDefCounts, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Count number of defs consumed from each register class by <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### allocateBasicBlock() {#a1e3f8f6daf8bccdbabf00341fd6222f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::allocateBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### allocateInstruction() {#ae0b85173f70b3e9ffe3636e5b6a648be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::allocateInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### allocVirtReg() {#a9fce57472f231b4a9bb43494cbf82a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::allocVirtReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, LiveReg &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Hint, bool LookAtPhysRegUses=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocates a physical register for VirtReg.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### allocVirtRegUndef() {#a8711f2bf7f22256b9f2350a094bfd2fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::allocVirtRegUndef (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### assignDanglingDebugValues() {#afe1dfcd66b9597ffffdf947620c136bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::assignDanglingDebugValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Def, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### assignVirtToPhysReg() {#a1d33a60b2f24edcaa138079ddadcc2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::assignVirtToPhysReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; AtMI, LiveReg &amp; LR, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method updates local state so that we know that PhysReg is the proper container for VirtReg now.</p>


<p>The physical register must not be used for anything else when this is called.</p>


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### calcSpillCost() {#a1073ea39561cfa8a50b7dfe215d70893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RegAllocFastImpl::calcSpillCost (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of spilling clearing out PhysReg and aliases so it is free for allocation.</p>


<p>Returns 0 when PhysReg is free or disabled with all aliases disabled - it can be allocated directly.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>spillImpossible when PhysReg or an alias can't be spilled.</p></dd>
</dl>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### defineLiveThroughVirtReg() {#a089933cbfcc685d258c18fbbb14bdf4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::defineLiveThroughVirtReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNum, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Variation of defineVirtReg() with special handling for livethrough regs (tied or earlyclobber) that may interfere with preassigned uses.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI's MachineOperands were re-arranged/invalidated.</p></dd>
</dl>


<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### definePhysReg() {#a8495a76b4ae9d2a55b35d33b2718efc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::definePhysReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### defineVirtReg() {#aa6746be2a18b75a4ae1b6105f3ce8cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::defineVirtReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNum, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, bool LookAtPhysRegUses=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocates a register for VirtReg definition.</p>


<p>Typically the register is already assigned from a use of the virtreg, however we still need to perform an allocation if:</p>


<ul class="doxyList ">
<li>It is a dead definition without any uses.</li>
<li>The value is live out and all uses are in different basic blocks.</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI's MachineOperands were re-arranged/invalidated.</p></dd>
</dl>


<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### displacePhysReg() {#ac65978b2b5f53b012bab341133582c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::displacePhysReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark PhysReg as reserved or free after spilling any virtregs.</p>


<p>This is very similar to defineVirtReg except the physreg is reserved instead of allocated.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### dumpState() {#a7704dd7662107307e30c5c5d587724b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::dumpState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### findAndSortDefOperandIndexes() {#ae956237ad0d01e8ef492cb23a99277ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::findAndSortDefOperandIndexes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute DefOperandIndexes so it contains the indices of "def" operands that are to be allocated.</p>


<p>Those are ordered in a way that small classes, early clobbers and livethroughs are allocated first.</p>


<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### findLiveVirtReg() {#a51d5cff8acd419898ee18a9ab51fc281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegMap::iterator anonymous{RegAllocFast.cpp}::RegAllocFastImpl::findLiveVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### findLiveVirtReg() {#a6eb6b7200803d79fcd0eaf3c6f2105e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegMap::const_iterator anonymous{RegAllocFast.cpp}::RegAllocFastImpl::findLiveVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### freePhysReg() {#a26814c72c082867fa6c6de02ae3cfbc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::freePhysReg (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### getErrorAssignment() {#a1c76c34aba8142537d9851152f28314a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPhysReg RegAllocFastImpl::getErrorAssignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LiveReg &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query a physical register to use as a filler in contexts where the allocation has failed.</p>


<p>This will raise an error, but not abort the compilation.</p>


<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### getMBBBeginInsertionPoint() {#a502c898eeac950d667f330a0aecb1c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator RegAllocFastImpl::getMBBBeginInsertionPoint (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 2 &gt; &amp; PrologLiveIns)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get basic block begin insertion point.</p>


<p>This is not just MBB.begin() because surprisingly we have EH_LABEL instructions marking the begin of a basic block. This means we must insert new instructions after such labels...</p>


<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### getStackSpaceFor() {#a292781887605b4560482cfcb599ab35d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int RegAllocFastImpl::getStackSpaceFor (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This allocates space for the specified virtual register to be held on the stack.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### handleBundle() {#a30d566810b4163f0ffc83dc17376c0c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::handleBundle (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### handleDebugValue() {#a5ffbb2e34f3a0d85c3b6c4e9b974e311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::handleDebugValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### isClobberedByRegMasks() {#a384db7e0b19119ec8d812c4c6d981520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegAllocFast.cpp}::RegAllocFastImpl::isClobberedByRegMasks (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### isPhysRegFree() {#a7abdb788a4a19279967a9cae1037b947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::isPhysRegFree (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### isRegUsedInInstr() {#ada6c633cc28f2091d2ff1bdc3ff20583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegAllocFast.cpp}::RegAllocFastImpl::isRegUsedInInstr (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg, bool LookAtPhysRegUses)</td>
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

<p>Check if a physreg or any of its aliases are used in this instruction.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### markPhysRegUsedInInstr() {#ab5475c0fcc42029689825a4858fe8c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegAllocFast.cpp}::RegAllocFastImpl::markPhysRegUsedInInstr (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
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

<p>Mark physical register as being used in a register use operand.</p>


<p>This is only used by the special livethrough handling code.</p>


<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### markRegUsedInInstr() {#a809b7fd311fae596fa8c6ea7881db596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegAllocFast.cpp}::RegAllocFastImpl::markRegUsedInInstr (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
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

<p>Mark a physreg as used in this instruction.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### mayLiveIn() {#ae23045931899133c161a17ca999b10e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::mayLiveIn (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns false if <span class="doxyComputerOutput">VirtReg</span> is known to not be live into the current block.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### mayLiveOut() {#a293bc88ed331a85b94fc103cd94e4b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::mayLiveOut (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns false if <span class="doxyComputerOutput">VirtReg</span> is known to not live out of the current block.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### reload() {#ac0594fecdc7f6b9b4021422e3baa1162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::reload (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Before, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert reload instruction for <span class="doxyComputerOutput">PhysReg</span> before <span class="doxyComputerOutput">Before</span>.</p>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### reloadAtBegin() {#a2a09537c187f2785a4b28cd0a8b8f1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::reloadAtBegin (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reload all currently assigned virtual registers.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### setPhysReg() {#a16925e9ab666c7df9c4763c18c66592d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::setPhysReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Changes operand OpNum in MI the refer the PhysReg, considering subregs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI's MachineOperands were re-arranged/invalidated.</p></dd>
</dl>


<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### setPhysRegState() {#ab5644ab844a01048a9bbc7fb96ead372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegAllocFast.cpp}::RegAllocFastImpl::setPhysRegState (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, unsigned NewState)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### shouldAllocateRegister() {#a127a666595b0a02350dd97bf35384d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegAllocFast.cpp}::RegAllocFastImpl::shouldAllocateRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### spill() {#a767e653113fcad05b575f98901106af8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocFastImpl::spill (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Before, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> AssignedReg, bool Kill, bool LiveOut)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert spill instruction for <span class="doxyComputerOutput">AssignedReg</span> before <span class="doxyComputerOutput">Before</span>.</p>


<p>Update DBG_VALUEs with <span class="doxyComputerOutput">VirtReg</span> operands with the stack slot.</p>


<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### traceCopies() {#acc48ddf1fcef0122a466969eb008e1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register RegAllocFastImpl::traceCopies (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if any of <span class="doxyComputerOutput">VirtReg's</span> definitions is a copy.</p>


<p>If it is follow the chain of copies to check whether we reach a physical register we can coalesce with.</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### traceCopyChain() {#a65189b14b4d7ee62799c271648d568ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register RegAllocFastImpl::traceCopyChain (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### unmarkRegUsedInInstr() {#a5ccad68acf8ce4b6af06ce5481d26302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegAllocFast.cpp}::RegAllocFastImpl::unmarkRegUsedInInstr (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
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

<p>Remove mark of physical register being used in the instruction.</p>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### usePhysReg() {#a1d36bad425a81d7bc8c047258c3ec3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::usePhysReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle the direct use of a physical register.</p>


<p>Check that the register is not used by a virtreg. Kill the physreg, marking it free. This may add implicit kills to MO-&gt;<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent()</a> and invalidate MO.</p>


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### useVirtReg() {#ab9405629c9047907677a00235d54a3ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocFastImpl::useVirtReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocates a register for a VirtReg use.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI's MachineOperands were re-arranged/invalidated.</p></dd>
</dl>


<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ClearVirtRegs {#a1082edd3a979e58af7ab50a68c83ae20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegAllocFast.cpp}::RegAllocFastImpl::ClearVirtRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>


<p>Referenced by <a href="#a031240ad13338dc7e24d587d040781a8">RegAllocFastImpl</a> and <a href="#acc7ba17c073b2d0a80ca229f3166b6a9">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BundleVirtRegsMap {#a33ea713485f282f9ecfda102a5948e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, MCPhysReg&gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::BundleVirtRegsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores assigned virtual registers present in the bundle MI.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### Coalesced {#a799c5ed4b5fa932d90e0230903645d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *, 32&gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::Coalesced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### DanglingDbgValues {#a02c739cb1a09da2b746eafe13134766a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, SmallVector&lt;MachineInstr *, 1&gt; &gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::DanglingDbgValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of DBG_VALUE that we encountered without the vreg being assigned because they were placed after the last use of the vreg.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### DefOperandIndexes {#a159019ad49af6e01f62f57b2a68da0ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::DefOperandIndexes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### InstrGen {#a3da1b458e56a0ca18b9262df223bfaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{RegAllocFast.cpp}::RegAllocFastImpl::InstrGen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track register units that are used in the current instruction, and so cannot be allocated.</p>


<p>In the first phase (tied defs/early clobber), we consider also physical uses, afterwards, we don't. If the lowest bit isn't set, it's a solely physical use (markPhysRegUsedInInstr), otherwise, it's a normal use. To avoid resetting the entire vector after every instruction, we track the instruction "generation" in the remaining 31 bits – this means, that if UsedInInstr[Idx] &lt; InstrGen, the register unit is unused. InstrGen is never zero and always incremented by two.</p>


<p>Don't allocate inline storage: the number of register units is typically quite large (e.g., <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> &gt; 100, <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> &gt; 200, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> &gt; 1000).</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### LiveDbgValueMap {#a6138f7b4d26419264942a829914ad916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, SmallVector&lt;MachineOperand *, 2&gt; &gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::LiveDbgValueMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### LiveVirtRegs {#a4bfcdb2e05546d88462c73b2ff66ed8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegMap anonymous{RegAllocFast.cpp}::RegAllocFastImpl::LiveVirtRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This map contains entries for each virtual register that is currently available in a physical register.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### MayLiveAcrossBlocks {#a625bf122ca23dfe2a4c7bf15d8005967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{RegAllocFast.cpp}::RegAllocFastImpl::MayLiveAcrossBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has a bit set for every virtual register for which it was determined that it is alive across blocks.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### MBB {#aefafa1ab55335f5ce4f1d2fdc717fefc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{RegAllocFast.cpp}::RegAllocFastImpl::MBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Basic block currently being allocated.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### MFI {#afc12ec1a31239d49167e05336c01768c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFrameInfo* anonymous{RegAllocFast.cpp}::RegAllocFastImpl::MFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### MRI {#af3231b0f880a1b7f30e4e3985e454555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{RegAllocFast.cpp}::RegAllocFastImpl::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### PosIndexes {#a64d1e12ec181365b6079a29b3c64eda6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrPosIndexes anonymous{RegAllocFast.cpp}::RegAllocFastImpl::PosIndexes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### RegClassInfo {#ac8c71da83274294fb1810f4c67c26f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterClassInfo anonymous{RegAllocFast.cpp}::RegAllocFastImpl::RegClassInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### RegMasks {#a1f0fddf1d50ea570d6fb4a768c77b8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const uint32_t *&gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::RegMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### RegUnitStates {#a2ea9ce7da3ab9cc05674a678b2432738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::RegUnitStates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps each physical register to a RegUnitState enum or virtual register.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### ShouldAllocateRegisterImpl {#a2d4e7265a1321b278ff1f10bbe4c93fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegAllocFilterFunc anonymous{RegAllocFast.cpp}::RegAllocFastImpl::ShouldAllocateRegisterImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### StackSlotForVirtReg {#ac0a4c966cbbd5d45a765f9a12aa8b83c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;int, VirtReg2IndexFunctor&gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::StackSlotForVirtReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps virtual regs to the frame index where these values are spilled.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### TII {#aac3a64638da21704affce53cf30b3f61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{RegAllocFast.cpp}::RegAllocFastImpl::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### TRI {#abf943abb9e3947f71a2d08b6da091bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{RegAllocFast.cpp}::RegAllocFastImpl::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

### UsedInInstr {#ab96369ff42bae07d596d7a47249584fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 0&gt; anonymous{RegAllocFast.cpp}::RegAllocFastImpl::UsedInInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp">RegAllocFast.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
