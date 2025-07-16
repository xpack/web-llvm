---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-varlocbasedimpl-cpp-/varlocbasedldv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VarLocBasedLDV` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/ldvimpl">LDVImpl</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0d4f44429c510dcd89444a05613353">FragmentInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a28966a47fd907002c2568cc007e29">OptFragmentInfo</a> = std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d58a08726c9371aad80b1e1a977cddf">VarVec</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; VarLoc, 32 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c410ae60fd204cda0ad1cde964117a">VarLocInMBB</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa04e5ffbaaf08041a6ac7cea00a226f5">TransferMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; TransferDebugPair, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c10af2e313797964c4a4cc25252cb6">InstToEntryLocMap</a> = std::multimap&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/locindex">LocIndex</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4554e15d37294d1b98c815fee88ed9">RegDefToInstMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af706f4e5e81aff9ea9863d907498e7dd">FragmentOfVar</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a208c04e0c008d99c764780e7ce6038f5">OverlapMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; FragmentOfVar, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a>, 1 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1beba4275ae33f5c968b0ffec24b6f0">VarToFragments</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo">FragmentInfo</a>, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TransferKind { <a href="#a58849a6ea041fbc19647a6f03c0507e2">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3801e99c12be5fdd89d47237f657e81c">VarLocBasedLDV</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default construct and initialize the pass. <a href="#a3801e99c12be5fdd89d47237f657e81c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad89446f66962cef8f8cd30c7c51902">~VarLocBasedLDV</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51da336f90b0b7ff7c2a7b72b6a43ccf">printVarLocInMBB</a> (const MachineFunction &amp;MF, const VarLocInMBB &amp;V, const VarLocMap &amp;VarLocIDs, const char *msg, raw_ostream &amp;Out) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print to ostream with a message. <a href="#a51da336f90b0b7ff7c2a7b72b6a43ccf">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4177b39e80e61b049697236c420eb0">getUsedRegs</a> (const VarLocSet &amp;CollectFrom, SmallVectorImpl&lt; Register &gt; &amp;UsedRegs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the registers which are used by VarLocs of kind RegisterKind tracked by <span class="doxyComputerOutput">CollectFrom</span>. <a href="#a4f4177b39e80e61b049697236c420eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75fd788b7fb8cc35f13a2fa77494732c">getVarLocsInMBB</a> (const MachineBasicBlock *MBB, VarLocInMBB &amp;Locs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21e04cb27c2ce9dea9e7eff2110bd8a">getVarLocsInMBB</a> (const MachineBasicBlock *MBB, const VarLocInMBB &amp;Locs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55365f705b741ed7cce62e2a23a41a98">isSpillInstruction</a> (const MachineInstr &amp;MI, MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether this instruction is a spill to a stack location. <a href="#a55365f705b741ed7cce62e2a23a41a98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c448361f7ab2e7e44f0754b221d1428">isLocationSpill</a> (const MachineInstr &amp;MI, MachineFunction *MF, Register &amp;Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decide if @MI is a spill instruction and return true if it is. <a href="#a7c448361f7ab2e7e44f0754b221d1428">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa009ea374f1faca2c4b93c7183487493">isEntryValueCandidate</a> (const MachineInstr &amp;MI, const DefinedRegsSet &amp;Regs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given machine instruction is a debug value which we can emit entry values for. <a href="#aa009ea374f1faca2c4b93c7183487493">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/spillloc">VarLoc::SpillLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae5a1e0dc6d8a2bbb101d4e1df44fe60">isRestoreInstruction</a> (const MachineInstr &amp;MI, MachineFunction *MF, Register &amp;Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a given instruction is identified as a spill, return the spill location and set <span class="doxyComputerOutput">Reg</span> to the spilled register. <a href="#aae5a1e0dc6d8a2bbb101d4e1df44fe60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/spillloc">VarLoc::SpillLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c71e7a6df5c7c6836fdaa5f9fddae0">extractSpillBaseRegAndOffset</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a spill instruction, extract the register and offset used to address the spill location in a target independent way. <a href="#aa5c71e7a6df5c7c6836fdaa5f9fddae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c19ce1031675f6e20c68fc31b77c68">insertTransferDebugPair</a> (MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, TransferMap &amp;Transfers, VarLocMap &amp;VarLocIDs, LocIndex OldVarID, TransferKind Kind, const VarLoc::MachineLoc &amp;OldLoc, Register NewReg=Register())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create new TransferDebugPair and insert it in <span class="doxyComputerOutput">Transfers</span>. <a href="#a72c19ce1031675f6e20c68fc31b77c68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e000c43e1dc807a15bea1cc09443cc">transferDebugValue</a> (const MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, InstToEntryLocMap &amp;EntryValTransfers, RegDefToInstMap &amp;RegSetInstrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>End all previous ranges related to @MI and start a new range from @MI if it is a DBG_VALUE instr. <a href="#a00e000c43e1dc807a15bea1cc09443cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf45901cb1b75b061ca31e7400201794">transferSpillOrRestoreInst</a> (MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, TransferMap &amp;Transfers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A spilled register may indicate that we have to end the current range of a variable and create a new one for the spill location. <a href="#adf45901cb1b75b061ca31e7400201794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d402cc8cc72ef137e3936daa06d976">cleanupEntryValueTransfers</a> (const MachineInstr *MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, const VarLoc &amp;EntryVL, InstToEntryLocMap &amp;EntryValTransfers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do cleanup of <span class="doxyComputerOutput">EntryValTransfers</span> created by <span class="doxyComputerOutput">TRInst</span>, by removing the Transfer, which uses the to-be-deleted <span class="doxyComputerOutput">EntryVL</span>. <a href="#a10d402cc8cc72ef137e3936daa06d976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19887b7d36628c9e37591b1a261f5240">removeEntryValue</a> (const MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, const VarLoc &amp;EntryVL, InstToEntryLocMap &amp;EntryValTransfers, RegDefToInstMap &amp;RegSetInstrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to salvage the debug entry value if we encounter a new debug value describing the same parameter, otherwise stop tracking the value. <a href="#a19887b7d36628c9e37591b1a261f5240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8ac3333ee6ea67a2a6c3ed502614e8">emitEntryValues</a> (MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, InstToEntryLocMap &amp;EntryValTransfers, VarLocsInRange &amp;KillSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn the entry value backup locations into primary locations. <a href="#aab8ac3333ee6ea67a2a6c3ed502614e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d55af7093ace84c7ce59becc55ad960">recordEntryValue</a> (const MachineInstr &amp;MI, const DefinedRegsSet &amp;DefinedRegs, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This routine records the entry values of function parameters. <a href="#a8d55af7093ace84c7ce59becc55ad960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f1de0daed7be5d1970130f9fd9818b">transferRegisterCopy</a> (MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, TransferMap &amp;Transfers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">MI</span> is a register copy instruction, that copies a previously tracked value from one register to another register that is callee saved, we create new DBG_VALUE instruction described with copy destination register. <a href="#a56f1de0daed7be5d1970130f9fd9818b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add378b522680657478283a44435148cd">transferRegisterDef</a> (MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, InstToEntryLocMap &amp;EntryValTransfers, RegDefToInstMap &amp;RegSetInstrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A definition of a register may mark the end of a range. <a href="#add378b522680657478283a44435148cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c94df6b28155425a71d81895a9183fe">transferWasmDef</a> (MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89186b2feeaf687e83450b97d582580">transferTerminator</a> (MachineBasicBlock *MBB, OpenRangesSet &amp;OpenRanges, VarLocInMBB &amp;OutLocs, const VarLocMap &amp;VarLocIDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Terminate all open ranges at the end of the current basic block. <a href="#aa89186b2feeaf687e83450b97d582580">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af482fd093958c2f80ba9800198f0c1f0">process</a> (MachineInstr &amp;MI, OpenRangesSet &amp;OpenRanges, VarLocMap &amp;VarLocIDs, TransferMap &amp;Transfers, InstToEntryLocMap &amp;EntryValTransfers, RegDefToInstMap &amp;RegSetInstrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This routine creates OpenRanges. <a href="#af482fd093958c2f80ba9800198f0c1f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19898e8b80be6d8fd29f7c668193759c">accumulateFragmentMap</a> (MachineInstr &amp;MI, VarToFragments &amp;SeenFragments, OverlapMap &amp;OLapMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulate a mapping between each <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> fragment and other fragments of that <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> which overlap. <a href="#a19898e8b80be6d8fd29f7c668193759c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac9a2706ce453587bef424727736da2">join</a> (MachineBasicBlock &amp;MBB, VarLocInMBB &amp;OutLocs, VarLocInMBB &amp;InLocs, const VarLocMap &amp;VarLocIDs, SmallPtrSet&lt; const MachineBasicBlock *, 16 &gt; &amp;Visited, SmallPtrSetImpl&lt; const MachineBasicBlock * &gt; &amp;ArtificialBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This routine joins the analysis results of all incoming edges in @MBB by inserting a new DBG_VALUE instruction at the start of the @MBB - if the same source variable in all the predecessors of @MBB reside in the same location. <a href="#afac9a2706ce453587bef424727736da2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47d8e8957c8b8c699a8a46228ad8e8c">flushPendingLocs</a> (VarLocInMBB &amp;PendingInLocs, VarLocMap &amp;VarLocIDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create DBG_VALUE insts for inlocs that have been propagated but had their instruction creation deferred. <a href="#ad47d8e8957c8b8c699a8a46228ad8e8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb0c97701f714fa24e0031b0a850811">ExtendRanges</a> (MachineFunction &amp;MF, MachineDominatorTree *DomTree, TargetPassConfig *TPC, unsigned InputBBLimit, unsigned InputDbgValLimit) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the liveness information for the given machine function and extend ranges across basic blocks. <a href="#afcb0c97701f714fa24e0031b0a850811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c7085d5c2b5de00a8b6857d5b7c6bb">TRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a0069e09f941a5ece8110b10a6e2ec">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadeb6957c662bbfa8de61d9e6d9f05e2">TFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85dd1fba4a79969af3cace49126419c">TPC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accdebd9a6874f98c70f682b58bc0fce2">CalleeSavedRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6069c587a240d620162d87a56a0fd92c">LS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coalescingbitvector/#a56416744b3c83246a55d0890507b0654">VarLocSet::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ffdbfca68c0db120b8d07c1369fd50">Alloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a631b022d9578d2e5c47ff080402c89">LastNonDbgMI</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab188a0682518f5e9a492c6502d645d3f">collectAllVarLocs</a> (SmallVectorImpl&lt; VarLoc &gt; &amp;Collected, const VarLocSet &amp;CollectFrom, const VarLocMap &amp;VarLocIDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects all VarLocs from <span class="doxyComputerOutput">CollectFrom</span>. <a href="#ab188a0682518f5e9a492c6502d645d3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37bd55a4124dc7a5d984af2652e6b542">collectIDsForRegs</a> (VarLocsInRange &amp;Collected, const DefinedRegsSet &amp;Regs, const VarLocSet &amp;CollectFrom, const VarLocMap &amp;VarLocIDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all VarLoc IDs from <span class="doxyComputerOutput">CollectFrom</span> for VarLocs with MLs of kind RegisterKind which are located in any reg in <span class="doxyComputerOutput">Regs</span>. <a href="#a37bd55a4124dc7a5d984af2652e6b542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FragmentInfo {#a0a0d4f44429c510dcd89444a05613353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::FragmentInfo =  DIExpression::FragmentInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### FragmentOfVar {#af706f4e5e81aff9ea9863d907498e7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::FragmentOfVar = 
      std::pair&lt;const DILocalVariable *, DIExpression::FragmentInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### InstToEntryLocMap {#a08c10af2e313797964c4a4cc25252cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::InstToEntryLocMap =  std::multimap&lt;const MachineInstr *, LocIndex&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### OptFragmentInfo {#ae7a28966a47fd907002c2568cc007e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OptFragmentInfo =  std::optional&lt;DIExpression::FragmentInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### OverlapMap {#a208c04e0c008d99c764780e7ce6038f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OverlapMap = 
      DenseMap&lt;FragmentOfVar, SmallVector&lt;DIExpression::FragmentInfo, 1&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### RegDefToInstMap {#a5c4554e15d37294d1b98c815fee88ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::RegDefToInstMap =  DenseMap&lt;Register, MachineInstr *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### TransferMap {#aa04e5ffbaaf08041a6ac7cea00a226f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::TransferMap =  SmallVector&lt;TransferDebugPair, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### VarLocInMBB {#a30c410ae60fd204cda0ad1cde964117a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLocInMBB = 
      SmallDenseMap&lt;const MachineBasicBlock *, std::unique_ptr&lt;VarLocSet&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### VarToFragments {#af1beba4275ae33f5c968b0ffec24b6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarToFragments = 
      DenseMap&lt;const DILocalVariable *, SmallSet&lt;FragmentInfo, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### VarVec {#a4d58a08726c9371aad80b1e1a977cddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarVec =  SmallVector&lt;VarLoc, 32&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### TransferKind {#a58849a6ea041fbc19647a6f03c0507e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::TransferKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">TransferCopy<a id="a58849a6ea041fbc19647a6f03c0507e2aefa2a1ecfccaf48030f4c781e34ed992"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TransferSpill<a id="a58849a6ea041fbc19647a6f03c0507e2a58b34ab6b393af00686635a85fe22c53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TransferRestore<a id="a58849a6ea041fbc19647a6f03c0507e2a371c16d22b14d49aec7e39efd8d28b33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VarLocBasedLDV() {#a3801e99c12be5fdd89d47237f657e81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLocBasedLDV::VarLocBasedLDV ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default construct and initialize the pass.</p>

<p>Definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a973dd94f5caf94978aab68dc386b0c24">llvm::makeVarLocBasedLiveDebugValues</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VarLocBasedLDV() {#a2ad89446f66962cef8f8cd30c7c51902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLocBasedLDV::~VarLocBasedLDV ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1098 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>Reference <a href="#a51da336f90b0b7ff7c2a7b72b6a43ccf">printVarLocInMBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printVarLocInMBB() {#a51da336f90b0b7ff7c2a7b72b6a43ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::printVarLocInMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">VarLocInMBB</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * msg, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print to ostream with a message.</p>

<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a2ad89446f66962cef8f8cd30c7c51902">~VarLocBasedLDV</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### accumulateFragmentMap() {#a19898e8b80be6d8fd29f7c668193759c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::accumulateFragmentMap (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/densemap">VarToFragments</a> &amp; SeenFragments, <a href="/web-llvm/docs/api/classes/llvm/densemap">OverlapMap</a> &amp; OverlappingFragments)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accumulate a mapping between each <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> fragment and other fragments of that <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> which overlap.</p>


<p>This reduces work during the data-flow stage from "Find any overlapping fragments" to "Check if the
known-to-overlap fragments are present".</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p>A previously unprocessed DEBUG_VALUE instruction to analyze for fragment usage.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SeenFragments</td>
<td class="doxyParamItemDescription"><p>Map from <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> to all fragments of that Variable which are known to exist.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OverlappingFragments</td>
<td class="doxyParamItemDescription"><p>The overlap map being constructed, from one Var/Fragment pair to a vector of fragments known to overlap.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### cleanupEntryValueTransfers() {#a10d402cc8cc72ef137e3936daa06d976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::cleanupEntryValueTransfers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; EntryVL, InstToEntryLocMap &amp; EntryValTransfers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do cleanup of <span class="doxyComputerOutput">EntryValTransfers</span> created by <span class="doxyComputerOutput">TRInst</span>, by removing the Transfer, which uses the to-be-deleted <span class="doxyComputerOutput">EntryVL</span>.</p>

<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### emitEntryValues() {#aab8ac3333ee6ea67a2a6c3ed502614e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::emitEntryValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, InstToEntryLocMap &amp; EntryValTransfers, <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#ad2d1326e7d856e0dd89105bec90546b2">VarLocsInRange</a> &amp; KillSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turn the entry value backup locations into primary locations.</p>

<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### ExtendRanges() {#afcb0c97701f714fa24e0031b0a850811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VarLocBasedLDV::ExtendRanges (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * DomTree, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> * TPC, unsigned InputBBLimit, unsigned InputDbgValLimit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the liveness information for the given machine function and extend ranges across basic blocks.</p>

<p>Definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### extractSpillBaseRegAndOffset() {#aa5c71e7a6df5c7c6836fdaa5f9fddae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLocBasedLDV::VarLoc::SpillLoc VarLocBasedLDV::extractSpillBaseRegAndOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a spill instruction, extract the register and offset used to address the spill location in a target independent way.</p>

<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### flushPendingLocs() {#ad47d8e8957c8b8c699a8a46228ad8e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::flushPendingLocs (<a href="/web-llvm/docs/api/classes/llvm/smalldensemap">VarLocInMBB</a> &amp; PendingInLocs, VarLocMap &amp; VarLocIDs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create DBG_VALUE insts for inlocs that have been propagated but had their instruction creation deferred.</p>

<p>Definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getUsedRegs() {#a4f4177b39e80e61b049697236c420eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::getUsedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp; CollectFrom, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UsedRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the registers which are used by VarLocs of kind RegisterKind tracked by <span class="doxyComputerOutput">CollectFrom</span>.</p>

<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getVarLocsInMBB() {#a75fd788b7fb8cc35f13a2fa77494732c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLocSet &amp; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::getVarLocsInMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">VarLocInMBB</a> &amp; Locs)</td>
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



<p>Definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getVarLocsInMBB() {#ab21e04cb27c2ce9dea9e7eff2110bd8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarLocSet &amp; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::getVarLocsInMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">VarLocInMBB</a> &amp; Locs)</td>
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



<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### insertTransferDebugPair() {#a72c19ce1031675f6e20c68fc31b77c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::insertTransferDebugPair (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, <a href="/web-llvm/docs/api/classes/llvm/smallvector">TransferMap</a> &amp; Transfers, VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/locindex">LocIndex</a> OldVarID, TransferKind Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/machineloc">VarLoc::MachineLoc</a> &amp; OldLoc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create new TransferDebugPair and insert it in <span class="doxyComputerOutput">Transfers</span>.</p>


<p>The VarLoc with <span class="doxyComputerOutput">OldVarID</span> should be deleted form <span class="doxyComputerOutput">OpenRanges</span> and replaced with new VarLoc. If <span class="doxyComputerOutput">NewReg</span> is different than default zero value then the new location will be register location created by the copy like instruction, otherwise it is variable's location on the stack.</p>


<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isEntryValueCandidate() {#aa009ea374f1faca2c4b93c7183487493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VarLocBasedLDV::isEntryValueCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#ae78037ed6d495b5340e490d48b4a731a">DefinedRegsSet</a> &amp; Regs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the given machine instruction is a debug value which we can emit entry values for.</p>


<p>Currently, we generate debug entry values only for parameters that are unmodified throughout the function and located in a register.</p>


<p>Definition at line 1024 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isLocationSpill() {#a7c448361f7ab2e7e44f0754b221d1428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VarLocBasedLDV::isLocationSpill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decide if @MI is a spill instruction and return true if it is.</p>


<p>We use 2 criteria to make this decision:</p>


<ul class="doxyList ">
<li>Is this instruction a store to a spill slot?</li>
<li>Is there a register operand that is both used and killed? TODO: Store optimization can fold spills into other stores (including other spills). We do not handle this yet (more than one memory operand).</li>
</ul>

<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isRestoreInstruction() {#aae5a1e0dc6d8a2bbb101d4e1df44fe60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; VarLocBasedLDV::VarLoc::SpillLoc &gt; VarLocBasedLDV::isRestoreInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a given instruction is identified as a spill, return the spill location and set <span class="doxyComputerOutput">Reg</span> to the spilled register.</p>

<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isSpillInstruction() {#a55365f705b741ed7cce62e2a23a41a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VarLocBasedLDV::isSpillInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tests whether this instruction is a spill to a stack location.</p>

<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### join() {#afac9a2706ce453587bef424727736da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VarLocBasedLDV::join (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">VarLocInMBB</a> &amp; OutLocs, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">VarLocInMBB</a> &amp; InLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 16 &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; ArtificialBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This routine joins the analysis results of all incoming edges in @MBB by inserting a new DBG_VALUE instruction at the start of the @MBB - if the same source variable in all the predecessors of @MBB reside in the same location.</p>

<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### process() {#af482fd093958c2f80ba9800198f0c1f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::process (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/classes/llvm/smallvector">TransferMap</a> &amp; Transfers, InstToEntryLocMap &amp; EntryValTransfers, <a href="/web-llvm/docs/api/classes/llvm/densemap">RegDefToInstMap</a> &amp; RegSetInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This routine creates OpenRanges.</p>

<p>Definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### recordEntryValue() {#a8d55af7093ace84c7ce59becc55ad960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::recordEntryValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#ae78037ed6d495b5340e490d48b4a731a">DefinedRegsSet</a> &amp; DefinedRegs, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This routine records the entry values of function parameters.</p>


<p>The values could be used as backup values. If we loose the track of some unmodified parameters, the backup values will be used as a primary locations.</p>


<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### removeEntryValue() {#a19887b7d36628c9e37591b1a261f5240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::removeEntryValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; EntryVL, InstToEntryLocMap &amp; EntryValTransfers, <a href="/web-llvm/docs/api/classes/llvm/densemap">RegDefToInstMap</a> &amp; RegSetInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to salvage the debug entry value if we encounter a new debug value describing the same parameter, otherwise stop tracking the value.</p>


<p>Return true if we should stop tracking the entry value and do the cleanup of emitted Entry <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Transfers, otherwise return false.</p>


<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### transferDebugValue() {#a00e000c43e1dc807a15bea1cc09443cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::transferDebugValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, InstToEntryLocMap &amp; EntryValTransfers, <a href="/web-llvm/docs/api/classes/llvm/densemap">RegDefToInstMap</a> &amp; RegSetInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>End all previous ranges related to @MI and start a new range from @MI if it is a DBG_VALUE instr.</p>

<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### transferRegisterCopy() {#a56f1de0daed7be5d1970130f9fd9818b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::transferRegisterCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/classes/llvm/smallvector">TransferMap</a> &amp; Transfers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">MI</span> is a register copy instruction, that copies a previously tracked value from one register to another register that is callee saved, we create new DBG_VALUE instruction described with copy destination register.</p>

<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### transferRegisterDef() {#add378b522680657478283a44435148cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::transferRegisterDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, InstToEntryLocMap &amp; EntryValTransfers, <a href="/web-llvm/docs/api/classes/llvm/densemap">RegDefToInstMap</a> &amp; RegSetInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A definition of a register may mark the end of a range.</p>

<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### transferSpillOrRestoreInst() {#adf45901cb1b75b061ca31e7400201794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::transferSpillOrRestoreInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/classes/llvm/smallvector">TransferMap</a> &amp; Transfers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A spilled register may indicate that we have to end the current range of a variable and create a new one for the spill location.</p>


<p>A restored register may indicate the reverse situation. We don't want to insert any instructions in process(), so we just create the DBG_VALUE without inserting it and keep track of it in <span class="doxyComputerOutput">Transfers</span>. It will be inserted into the BB when we're done iterating over the instructions.</p>


<p>Definition at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### transferTerminator() {#aa89186b2feeaf687e83450b97d582580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VarLocBasedLDV::transferTerminator (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, OpenRangesSet &amp; OpenRanges, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">VarLocInMBB</a> &amp; OutLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; VarLocIDs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Terminate all open ranges at the end of the current basic block.</p>

<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### transferWasmDef() {#a0c94df6b28155425a71d81895a9183fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::transferWasmDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, OpenRangesSet &amp; OpenRanges, VarLocMap &amp; VarLocIDs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#a81ffdbfca68c0db120b8d07c1369fd50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLocSet::Allocator anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### CalleeSavedRegs {#accdebd9a6874f98c70f682b58bc0fce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::CalleeSavedRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### LastNonDbgMI {#a3a631b022d9578d2e5c47ff080402c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::LastNonDbgMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### LS {#a6069c587a240d620162d87a56a0fd92c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScopes anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::LS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### TFI {#aadeb6957c662bbfa8de61d9e6d9f05e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering* anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::TFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### TII {#a05a0069e09f941a5ece8110b10a6e2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### TPC {#ad85dd1fba4a79969af3cace49126419c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig* anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::TPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### TRI {#a14c7085d5c2b5de00a8b6857d5b7c6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### collectAllVarLocs() {#ab188a0682518f5e9a492c6502d645d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::collectAllVarLocs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; VarLoc &gt; &amp; Collected, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp; CollectFrom, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; VarLocIDs)</td>
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

<p>Collects all VarLocs from <span class="doxyComputerOutput">CollectFrom</span>.</p>


<p>Each unique VarLoc is added to <span class="doxyComputerOutput">Collected</span> once, in order of insertion into <span class="doxyComputerOutput">VarLocIDs</span>.</p>


<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### collectIDsForRegs() {#a37bd55a4124dc7a5d984af2652e6b542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::collectIDsForRegs (<a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#ad2d1326e7d856e0dd89105bec90546b2">VarLocsInRange</a> &amp; Collected, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#ae78037ed6d495b5340e490d48b4a731a">DefinedRegsSet</a> &amp; Regs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp; CollectFrom, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; VarLocIDs)</td>
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

<p>Collect all VarLoc IDs from <span class="doxyComputerOutput">CollectFrom</span> for VarLocs with MLs of kind RegisterKind which are located in any reg in <span class="doxyComputerOutput">Regs</span>.</p>


<p>The IDs for each VarLoc correspond to entries in the universal location bucket, which every VarLoc has exactly 1 entry for. Insert collected IDs into <span class="doxyComputerOutput">Collected</span>.</p>


<p>Definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
