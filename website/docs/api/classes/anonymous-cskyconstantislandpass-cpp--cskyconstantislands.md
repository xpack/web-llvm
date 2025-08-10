---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CSKYConstantIslands` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands">CSKYConstantIslands</a> - Due to limited PC-relative displacements, <a href="/web-llvm/docs/api/namespaces/llvm/csky">CSKY</a> requires constant pool entries to be scattered among the instructions inside a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93be04db74349a2313b5b98d4417110">water_iterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c45f2e455446584aceb11cdeec58440">CSKYConstantIslands</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff885f0970b91511053b6c150c9e17fb">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#aff885f0970b91511053b6c150c9e17fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b801eba10402b4228f1623ce5ceb871">runOnMachineFunction</a> (MachineFunction &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a8b801eba10402b4228f1623ce5ceb871">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7f4adf2824a37fb41489767a871fcc">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6159cb24e3496f5b8bd5e830e052aba1">doInitialPlacement</a> (std::vector&lt; MachineInstr * &gt; &amp;CPEMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialPlacement - Perform the initial placement of the constant pool entries. <a href="#a6159cb24e3496f5b8bd5e830e052aba1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">CPEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f8243193a930d0f06eb4e6e694165f">findConstPoolEntry</a> (unsigned CPI, const MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findConstPoolEntry - Given the constpool index and CONSTPOOL_ENTRY MI, look up the corresponding CPEntry. <a href="#ac9f8243193a930d0f06eb4e6e694165f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4dfdd596d675a34ee339b581424255">getCPEAlign</a> (const MachineInstr &amp;CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCPEAlign - Returns the required alignment of the constant pool entry represented by CPEMI. <a href="#a7b4dfdd596d675a34ee339b581424255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a288be25d1bc5cf01068ce4dbc091a5f8">initializeFunctionInfo</a> (const std::vector&lt; MachineInstr * &gt; &amp;CPEMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>initializeFunctionInfo - Do the initial scan of the function, building up information about the sizes of each block, the location of all the water, and finding all of the constant pool users. <a href="#a288be25d1bc5cf01068ce4dbc091a5f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0daa44e7ce506555db204876c480f657">getOffsetOf</a> (MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOffsetOf - Return the current offset of the specified machine instruction from the start of the function. <a href="#a0daa44e7ce506555db204876c480f657">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f75a6f1f9e24915627364dc171aeb23">getUserOffset</a> (CPUser &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9bfa833198bca98db6ff7bb76c1f71d">dumpBBs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print block size and offset information - debugging <a href="#ae9bfa833198bca98db6ff7bb76c1f71d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a> (unsigned UserOffset, unsigned TrialOffset, unsigned Disp, bool NegativeOK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8944493843f5bc5f183784463c301f54">isOffsetInRange</a> (unsigned UserOffset, unsigned TrialOffset, const CPUser &amp;U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a288bac1f9b76bdcac5aff851aa744aa1">computeBlockSize</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>computeBlockSize - Compute the size and some alignment information for MBB. <a href="#a288bac1f9b76bdcac5aff851aa744aa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae708a0dc9c80038ba6d971c94eb9db5c">splitBlockBeforeInstr</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the basic block containing MI into two blocks, which are joined by an unconditional branch. <a href="#ae708a0dc9c80038ba6d971c94eb9db5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83a38fd680014ffab61e69579bb7c36">updateForInsertedWaterBlock</a> (MachineBasicBlock *NewBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateForInsertedWaterBlock - When a block is newly inserted into the machine function, it upsets all of the block numbers. <a href="#ab83a38fd680014ffab61e69579bb7c36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a> (MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade449e1f08656cef186933b3a1bdd621">decrementCPEReferenceCount</a> (unsigned CPI, MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>decrementCPEReferenceCount - find the constant pool entry with index CPI and instruction CPEMI, and decrement its refcount. <a href="#ade449e1f08656cef186933b3a1bdd621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977522c71b9c7099aa74222cc12bbf17">findInRangeCPEntry</a> (CPUser &amp;U, unsigned UserOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; if not, see if an in-range clone of the CPE is in range, and if so, change the data structures so the user references the clone. <a href="#a977522c71b9c7099aa74222cc12bbf17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a94570a6a2a0044a7e4e959f414b317">findAvailableWater</a> (CPUser &amp;U, unsigned UserOffset, water_iterator &amp;WaterIter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findAvailableWater - Look for an existing entry in the WaterList in which we can place the CPE referenced from U so it's within range of U's MI. <a href="#a4a94570a6a2a0044a7e4e959f414b317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee171a94c094d78c3744e68795791b8d">createNewWater</a> (unsigned CPUserIndex, unsigned UserOffset, MachineBasicBlock *&amp;NewMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createNewWater - No existing WaterList entry will work for CPUsers[CPUserIndex], so create a place to put the CPE. <a href="#aee171a94c094d78c3744e68795791b8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a> (unsigned CPUserIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handleConstantPoolUser - Analyze the specified user, checking to see if it is out-of-range. <a href="#a800f62f10fe1fafc076ae4002371ba45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a260e4fa04b4392ed7de8a9202292a2ca">removeDeadCPEMI</a> (MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeDeadCPEMI - Remove a dead constant pool entry instruction. <a href="#a260e4fa04b4392ed7de8a9202292a2ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6672890784945b1489131dc6894b5e40">removeUnusedCPEntries</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeUnusedCPEntries - Remove constant pool entries whose refcounts are zero. <a href="#a6672890784945b1489131dc6894b5e40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c6e08944b4fbe61244afe2ca4b113d">isCPEntryInRange</a> (MachineInstr *MI, unsigned UserOffset, MachineInstr *CPEMI, unsigned Disp, bool NegOk, bool DoDump=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCPEntryInRange - Returns true if the distance between specific MI and specific ConstPool entry instruction can fit in MI's displacement field. <a href="#ad1c6e08944b4fbe61244afe2ca4b113d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31dc649eb968f53e71376a708b40333f">isWaterInRange</a> (unsigned UserOffset, MachineBasicBlock *Water, CPUser &amp;U, unsigned &amp;Growth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isWaterInRange - Returns true if a CPE placed after the specified Water (a basic block) will be in range for the specific MI. <a href="#a31dc649eb968f53e71376a708b40333f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32cee73e5a706eff3a8fc0b655f3ad93">isBBInRange</a> (MachineInstr *MI, MachineBasicBlock *BB, unsigned Disp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isBBInRange - Returns true if the distance between specific MI and specific BB can fit in MI's displacement field. <a href="#a32cee73e5a706eff3a8fc0b655f3ad93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5648beaeee682a37c2c01b7a7439db6e">fixupImmediateBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupImmediateBr - Fix up an immediate branch whose destination is too far away to fit in its displacement field. <a href="#a5648beaeee682a37c2c01b7a7439db6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222d82bcc0b1cb30a36ed1bf3bbeac63">fixupConditionalBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupConditionalBr - Fix up a conditional branch whose destination is too far away to fit in its displacement field. <a href="#a222d82bcc0b1cb30a36ed1bf3bbeac63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18197c3f531ddd266aa561369145a16d">fixupUnconditionalBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupUnconditionalBr - Fix up an unconditional branch whose destination is too far away to fit in its displacement field. <a href="#a18197c3f531ddd266aa561369145a16d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16751ce70ea59361531918891088fd7f">initPICLabelUId</a> (unsigned UId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe64db154ac991cb59cbd0a91a9c655e">createPICLabelUId</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; BasicBlockInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af292616f0f4e969fef2e46519880c4dc">BBInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b44fcfeb5d3ee0d87843f2b153480d8">WaterList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WaterList - A sorted list of basic blocks where islands could be placed (i.e. <a href="#a1b44fcfeb5d3ee0d87843f2b153480d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ebb8e065959c56131929923b790e4d">NewWaterList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NewWaterList - The subset of WaterList that was created since the previous iteration by inserting unconditional branches. <a href="#a41ebb8e065959c56131929923b790e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; CPUser &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68df402ec0e1495cb28c4ff7951b918c">CPUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPUsers - Keep track of all of the machine instructions that use various constant pools and their max displacement. <a href="#a68df402ec0e1495cb28c4ff7951b918c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; CPEntry &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83104a7b1db171f4aa5a90f71895da2">CPEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPEntries - Keep track of all of the constant pool entry machine instructions. <a href="#ab83104a7b1db171f4aa5a90f71895da2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; ImmBranch &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772ff7f87a7e3078b7ce900ab36226eb">ImmBranches</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ImmBranches - Keep track of all the immediate branch instructions. <a href="#a772ff7f87a7e3078b7ce900ab36226eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskysubtarget">CSKYSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3d1fc38ef543199e48b460c0dba5e9">STI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo">CSKYInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b90b76e2a41f15d51a3e6931c79ee89">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskymachinefunctioninfo">CSKYMachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d009de0deb443aed28870efbeb221d">MFI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33cfaa1eca37c1a6930e7a2bfb98ced3">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afabf4fb29fc0dccd216bd656a389fe63">MCP</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027b306e7c0aad1f21e946a8757c0089">PICLabelUId</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff00ea41ead523def4f011c420a4101">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands">CSKYConstantIslands</a> - Due to limited PC-relative displacements, <a href="/web-llvm/docs/api/namespaces/llvm/csky">CSKY</a> requires constant pool entries to be scattered among the instructions inside a function.</p>


<p>To do this, it completely ignores the normal LLVM constant pool; instead, it places constants wherever it feels like with special instructions.</p>


<p>The terminology used in this pass includes: Islands - Clumps of constants placed in the function. Water - Potential places where an island could be formed. CPE - A constant pool entry that has been placed somewhere, which tracks a list of users.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### water\_iterator {#af93be04db74349a2313b5b98d4417110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::water_iterator =  std::vector&lt;MachineBasicBlock *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CSKYConstantIslands() {#a5c45f2e455446584aceb11cdeec58440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::CSKYConstantIslands ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="#adff00ea41ead523def4f011c420a4101">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab3048fe42c5af7707fe9d438d8c527c5">llvm::createCSKYConstantIslandPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustBBOffsetsAfter() {#a3384fc522b23fa07500bd151eee9fed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantIslands::adjustBBOffsetsAfter (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#aee171a94c094d78c3744e68795791b8d">createNewWater</a>, <a href="#a222d82bcc0b1cb30a36ed1bf3bbeac63">fixupConditionalBr</a>, <a href="#a18197c3f531ddd266aa561369145a16d">fixupUnconditionalBr</a>, <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a>, <a href="#a288be25d1bc5cf01068ce4dbc091a5f8">initializeFunctionInfo</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>, <a href="#a260e4fa04b4392ed7de8a9202292a2ca">removeDeadCPEMI</a> and <a href="#ae708a0dc9c80038ba6d971c94eb9db5c">splitBlockBeforeInstr</a>.</p>

</div>
</div>

### computeBlockSize() {#a288bac1f9b76bdcac5aff851aa744aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantIslands::computeBlockSize (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>computeBlockSize - Compute the size and some alignment information for MBB.</p>


<p>This function updates BBInfo directly.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a288be25d1bc5cf01068ce4dbc091a5f8">initializeFunctionInfo</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a> and <a href="#ae708a0dc9c80038ba6d971c94eb9db5c">splitBlockBeforeInstr</a>.</p>

</div>
</div>

### createNewWater() {#aee171a94c094d78c3744e68795791b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantIslands::createNewWater (unsigned CPUserIndex, unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; NewMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createNewWater - No existing WaterList entry will work for CPUsers[CPUserIndex], so create a place to put the CPE.</p>


<p>The end of the block is used if in range, and the conditional branch munged so control flow is correct. Otherwise the block is split to create a hole with an unconditional branch around it. In either case NewMBB is set to a block following which the new island can be inserted (the WaterList is not adjusted).</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf35424231192c6b4a3e22d711f50b1e">llvm::MachineBasicBlock::back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a64267a385738a1aa6a110071d05ff207">bbHasFallthrough</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af066b2b6a1013299bfca84fe8b798a0b">llvm::MachineInstrBuilder::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a2e62a3c07e3b7d0f0591b2d80bd20967">getUnconditionalBrDisp</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#ae708a0dc9c80038ba6d971c94eb9db5c">splitBlockBeforeInstr</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### decrementCPEReferenceCount() {#ade449e1f08656cef186933b3a1bdd621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::decrementCPEReferenceCount (unsigned CPI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>decrementCPEReferenceCount - find the constant pool entry with index CPI and instruction CPEMI, and decrement its refcount.</p>


<p>If the refcount becomes 0 remove the entry and instruction. Returns true if we removed the entry, false if we didn't.</p>


<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac9f8243193a930d0f06eb4e6e694165f">findConstPoolEntry</a> and <a href="#a260e4fa04b4392ed7de8a9202292a2ca">removeDeadCPEMI</a>.</p>


<p>Referenced by <a href="#a977522c71b9c7099aa74222cc12bbf17">findInRangeCPEntry</a>, <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### doInitialPlacement() {#a6159cb24e3496f5b8bd5e830e052aba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantIslands::doInitialPlacement (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CPEMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>doInitialPlacement - Perform the initial placement of the constant pool entries.</p>


<p>To start with, we put them all at the end of the function.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cec41e65c7ebf7da3e9d41f2317065e">llvm::MachineBasicBlock::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae13575403de0e7d005f1b5905053f3ea">llvm::MachineBasicBlock::getAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3b1dce1f3354a357fb9061bb7568a84e">llvm::MachineBasicBlock::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cb665c210dc8e43f537cf4c9b84e2c7">llvm::MachineBasicBlock::setAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a8b801eba10402b4228f1623ce5ceb871">runOnMachineFunction</a>.</p>

</div>
</div>

### dumpBBs() {#ae9bfa833198bca98db6ff7bb76c1f71d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void CSKYConstantIslands::dumpBBs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>print block size and offset information - debugging</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a8b801eba10402b4228f1623ce5ceb871">runOnMachineFunction</a>.</p>

</div>
</div>

### findAvailableWater() {#a4a94570a6a2a0044a7e4e959f414b317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::findAvailableWater (CPUser &amp; U, unsigned UserOffset, water_iterator &amp; WaterIter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findAvailableWater - Look for an existing entry in the WaterList in which we can place the CPE referenced from U so it's within range of U's MI.</p>


<p>Returns true if found, false if not. If it returns true, WaterIter is set to the WaterList entry. To ensure that this pass terminates, the CPE location for a particular CPUser is only allowed to move to a lower address, so search backward from the end of the list and prefer the first water that is in range.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a31dc649eb968f53e71376a708b40333f">isWaterInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### findConstPoolEntry() {#ac9f8243193a930d0f06eb4e6e694165f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYConstantIslands::CPEntry * CSKYConstantIslands::findConstPoolEntry (unsigned CPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findConstPoolEntry - Given the constpool index and CONSTPOOL_ENTRY MI, look up the corresponding CPEntry.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ade449e1f08656cef186933b3a1bdd621">decrementCPEReferenceCount</a> and <a href="#a288be25d1bc5cf01068ce4dbc091a5f8">initializeFunctionInfo</a>.</p>

</div>
</div>

### findInRangeCPEntry() {#a977522c71b9c7099aa74222cc12bbf17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CSKYConstantIslands::findInRangeCPEntry (CPUser &amp; U, unsigned UserOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; if not, see if an in-range clone of the CPE is in range, and if so, change the data structures so the user references the clone.</p>


<p>Returns: 0 = no existing entry found 1 = entry found, and there were no code insertions or deletions 2 = entry found, and there were code insertions or deletions</p>


<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ade449e1f08656cef186933b3a1bdd621">decrementCPEReferenceCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad1c6e08944b4fbe61244afe2ca4b113d">isCPEntryInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5b401e780c5eed0aca1cfbf44d36a545">llvm::MachineOperand::isCPI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aebc99c3c37896879abad49e7254a2fb8">llvm::MachineOperand::setIndex</a>.</p>


<p>Referenced by <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### fixupConditionalBr() {#a222d82bcc0b1cb30a36ed1bf3bbeac63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::fixupConditionalBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupConditionalBr - Fix up a conditional branch whose destination is too far away to fit in its displacement field.</p>


<p>It is converted to an inverse conditional branch + an unconditional branch to the destination.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a64267a385738a1aa6a110071d05ff207">bbHasFallthrough</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a56b7fed94faeb5bc67ee2b71608d2665">llvm::MachineInstr::getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a2e62a3c07e3b7d0f0591b2d80bd20967">getUnconditionalBrDisp</a>, <a href="#a32cee73e5a706eff3a8fc0b655f3ad93">isBBInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a91c590e8191655a6739eb4df9c443896">llvm::MachineInstr::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a98e9c9e8ef7cbb6c4aa89a38f21decfa">llvm::MachineOperand::setMBB</a> and <a href="#ae708a0dc9c80038ba6d971c94eb9db5c">splitBlockBeforeInstr</a>.</p>


<p>Referenced by <a href="#a5648beaeee682a37c2c01b7a7439db6e">fixupImmediateBr</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### fixupImmediateBr() {#a5648beaeee682a37c2c01b7a7439db6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::fixupImmediateBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupImmediateBr - Fix up an immediate branch whose destination is too far away to fit in its displacement field.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a222d82bcc0b1cb30a36ed1bf3bbeac63">fixupConditionalBr</a>, <a href="#a18197c3f531ddd266aa561369145a16d">fixupUnconditionalBr</a>, <a href="#a32cee73e5a706eff3a8fc0b655f3ad93">isBBInRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a> and <a href="#a8b801eba10402b4228f1623ce5ceb871">runOnMachineFunction</a>.</p>

</div>
</div>

### fixupUnconditionalBr() {#a18197c3f531ddd266aa561369145a16d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::fixupUnconditionalBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupUnconditionalBr - Fix up an unconditional branch whose destination is too far away to fit in its displacement field.</p>


<p>If the LR register has been spilled in the epilogue, then we can use BSR to implement a far jump. Otherwise, add an intermediate branch instruction to a branch.</p>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a5648beaeee682a37c2c01b7a7439db6e">fixupImmediateBr</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### getCPEAlign() {#a7b4dfdd596d675a34ee339b581424255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align CSKYConstantIslands::getCPEAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getCPEAlign - Returns the required alignment of the constant pool entry represented by CPEMI.</p>


<p>Alignment is measured in log2(bytes) units.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a> and <a href="#a260e4fa04b4392ed7de8a9202292a2ca">removeDeadCPEMI</a>.</p>

</div>
</div>

### getOffsetOf() {#a0daa44e7ce506555db204876c480f657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CSKYConstantIslands::getOffsetOf (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOffsetOf - Return the current offset of the specified machine instruction from the start of the function.</p>


<p>This offset changes as stuff is moved around inside the function.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a0f75a6f1f9e24915627364dc171aeb23">getUserOffset</a>, <a href="#a32cee73e5a706eff3a8fc0b655f3ad93">isBBInRange</a> and <a href="#ad1c6e08944b4fbe61244afe2ca4b113d">isCPEntryInRange</a>.</p>

</div>
</div>

### getPassName() {#aff885f0970b91511053b6c150c9e17fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::getPassName ()</td>
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


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### getRequiredProperties() {#a1c7f4adf2824a37fb41489767a871fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::getRequiredProperties ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### getUserOffset() {#a0f75a6f1f9e24915627364dc171aeb23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CSKYConstantIslands::getUserOffset (CPUser &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>Reference <a href="#a0daa44e7ce506555db204876c480f657">getOffsetOf</a>.</p>


<p>Referenced by <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a>.</p>

</div>
</div>

### handleConstantPoolUser() {#a800f62f10fe1fafc076ae4002371ba45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::handleConstantPoolUser (unsigned CPUserIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handleConstantPoolUser - Analyze the specified user, checking to see if it is out-of-range.</p>


<p>If so, pick up the constant pool value and move it some place in-range. Return true if we changed any addresses (thus must run another pass of branch lengthening), false otherwise.</p>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#aee171a94c094d78c3744e68795791b8d">createNewWater</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="#ade449e1f08656cef186933b3a1bdd621">decrementCPEReferenceCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad26bff839257f220557ce812b2159c72">llvm::MachineBasicBlock::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="#a4a94570a6a2a0044a7e4e959f414b317">findAvailableWater</a>, <a href="#a977522c71b9c7099aa74222cc12bbf17">findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a7b4dfdd596d675a34ee339b581424255">getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a0f75a6f1f9e24915627364dc171aeb23">getUserOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#adff00ea41ead523def4f011c420a4101">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5b401e780c5eed0aca1cfbf44d36a545">llvm::MachineOperand::isCPI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cb665c210dc8e43f537cf4c9b84e2c7">llvm::MachineBasicBlock::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aebc99c3c37896879abad49e7254a2fb8">llvm::MachineOperand::setIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ab83a38fd680014ffab61e69579bb7c36">updateForInsertedWaterBlock</a>.</p>


<p>Referenced by <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a> and <a href="#a8b801eba10402b4228f1623ce5ceb871">runOnMachineFunction</a>.</p>

</div>
</div>

### initializeFunctionInfo() {#a288be25d1bc5cf01068ce4dbc091a5f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantIslands::initializeFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CPEMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>initializeFunctionInfo - Do the initial scan of the function, building up information about the sizes of each block, the location of all the water, and finding all of the constant pool users.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a64267a385738a1aa6a110071d05ff207">bbHasFallthrough</a>, <a href="#a288bac1f9b76bdcac5aff851aa744aa1">computeBlockSize</a>, <a href="#ac9f8243193a930d0f06eb4e6e694165f">findConstPoolEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8b801eba10402b4228f1623ce5ceb871">runOnMachineFunction</a>.</p>

</div>
</div>

### isBBInRange() {#a32cee73e5a706eff3a8fc0b655f3ad93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::isBBInRange (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned Disp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isBBInRange - Returns true if the distance between specific MI and specific BB can fit in MI's displacement field.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a0daa44e7ce506555db204876c480f657">getOffsetOf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#a222d82bcc0b1cb30a36ed1bf3bbeac63">fixupConditionalBr</a>, <a href="#a5648beaeee682a37c2c01b7a7439db6e">fixupImmediateBr</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### isCPEntryInRange() {#ad1c6e08944b4fbe61244afe2ca4b113d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::isCPEntryInRange (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI, unsigned Disp, bool NegOk, bool DoDump=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isCPEntryInRange - Returns true if the distance between specific MI and specific ConstPool entry instruction can fit in MI's displacement field.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a0daa44e7ce506555db204876c480f657">getOffsetOf</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#a977522c71b9c7099aa74222cc12bbf17">findInRangeCPEntry</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### isOffsetInRange() {#a8ed9829c73ee2b346eefc344633ef122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::isOffsetInRange (unsigned UserOffset, unsigned TrialOffset, unsigned Disp, bool NegativeOK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="#a288bac1f9b76bdcac5aff851aa744aa1">computeBlockSize</a>, <a href="#aee171a94c094d78c3744e68795791b8d">createNewWater</a>, <a href="#ade449e1f08656cef186933b3a1bdd621">decrementCPEReferenceCount</a>, <a href="#a4a94570a6a2a0044a7e4e959f414b317">findAvailableWater</a>, <a href="#a977522c71b9c7099aa74222cc12bbf17">findInRangeCPEntry</a>, <a href="#a222d82bcc0b1cb30a36ed1bf3bbeac63">fixupConditionalBr</a>, <a href="#a5648beaeee682a37c2c01b7a7439db6e">fixupImmediateBr</a>, <a href="#a18197c3f531ddd266aa561369145a16d">fixupUnconditionalBr</a>, <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a>, <a href="#a32cee73e5a706eff3a8fc0b655f3ad93">isBBInRange</a>, <a href="#ad1c6e08944b4fbe61244afe2ca4b113d">isCPEntryInRange</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>, <a href="#a31dc649eb968f53e71376a708b40333f">isWaterInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a260e4fa04b4392ed7de8a9202292a2ca">removeDeadCPEMI</a>, <a href="#a6672890784945b1489131dc6894b5e40">removeUnusedCPEntries</a>, <a href="#ae708a0dc9c80038ba6d971c94eb9db5c">splitBlockBeforeInstr</a> and <a href="#ab83a38fd680014ffab61e69579bb7c36">updateForInsertedWaterBlock</a>.</p>


<p>Referenced by <a href="#aee171a94c094d78c3744e68795791b8d">createNewWater</a>, <a href="#ad1c6e08944b4fbe61244afe2ca4b113d">isCPEntryInRange</a>, <a href="#a8944493843f5bc5f183784463c301f54">isOffsetInRange</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a> and <a href="#a31dc649eb968f53e71376a708b40333f">isWaterInRange</a>.</p>

</div>
</div>

### isOffsetInRange() {#a8944493843f5bc5f183784463c301f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::isOffsetInRange (unsigned UserOffset, unsigned TrialOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CPUser &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>Reference <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### isWaterInRange() {#a31dc649eb968f53e71376a708b40333f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::isWaterInRange (unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Water, CPUser &amp; U, unsigned &amp; Growth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isWaterInRange - Returns true if a CPE placed after the specified Water (a basic block) will be in range for the specific MI.</p>


<p>Compute how much the function will grow by inserting a CPE after Water.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a4a94570a6a2a0044a7e4e959f414b317">findAvailableWater</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### removeDeadCPEMI() {#a260e4fa04b4392ed7de8a9202292a2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantIslands::removeDeadCPEMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeDeadCPEMI - Remove a dead constant pool entry instruction.</p>


<p>Update sizes and offsets of impacted basic blocks.</p>


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a69f0bf266f1e42f9d65ec549a6481ba6">bbIsJumpedOver</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="#a7b4dfdd596d675a34ee339b581424255">getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cb665c210dc8e43f537cf4c9b84e2c7">llvm::MachineBasicBlock::setAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ade449e1f08656cef186933b3a1bdd621">decrementCPEReferenceCount</a>, <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a> and <a href="#a6672890784945b1489131dc6894b5e40">removeUnusedCPEntries</a>.</p>

</div>
</div>

### removeUnusedCPEntries() {#a6672890784945b1489131dc6894b5e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::removeUnusedCPEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeUnusedCPEntries - Remove constant pool entries whose refcounts are zero.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a260e4fa04b4392ed7de8a9202292a2ca">removeDeadCPEMI</a>.</p>


<p>Referenced by <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a> and <a href="#a8b801eba10402b4228f1623ce5ceb871">runOnMachineFunction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a8b801eba10402b4228f1623ce5ceb871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantIslands::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6159cb24e3496f5b8bd5e830e052aba1">doInitialPlacement</a>, <a href="#ae9bfa833198bca98db6ff7bb76c1f71d">dumpBBs</a>, <a href="#a5648beaeee682a37c2c01b7a7439db6e">fixupImmediateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a288be25d1bc5cf01068ce4dbc091a5f8">initializeFunctionInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a6672890784945b1489131dc6894b5e40">removeUnusedCPEntries</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### splitBlockBeforeInstr() {#ae708a0dc9c80038ba6d971c94eb9db5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * CSKYConstantIslands::splitBlockBeforeInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split the basic block containing MI into two blocks, which are joined by an unconditional branch.</p>


<p>Update data structures and renumber blocks to account for this change and returns the newly created block.</p>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="#a3384fc522b23fa07500bd151eee9fed5">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#ad11e5fb888cddb54cbf9f2ab1d513653">compareMbbNumbers</a>, <a href="#a288bac1f9b76bdcac5aff851aa744aa1">computeBlockSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a31e57b158a17c459f0dc34b0e602ecc6">llvm::MachineBasicBlock::transferSuccessors</a>.</p>


<p>Referenced by <a href="#aee171a94c094d78c3744e68795791b8d">createNewWater</a>, <a href="#a222d82bcc0b1cb30a36ed1bf3bbeac63">fixupConditionalBr</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

### updateForInsertedWaterBlock() {#ab83a38fd680014ffab61e69579bb7c36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantIslands::updateForInsertedWaterBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>updateForInsertedWaterBlock - When a block is newly inserted into the machine function, it upsets all of the block numbers.</p>


<p>Renumber the blocks and update the arrays that parallel this numbering.</p>


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#ad11e5fb888cddb54cbf9f2ab1d513653">compareMbbNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac85349aab432e6b7d8b2e8926048a6de">llvm::MachineFunction::RenumberBlocks</a>.</p>


<p>Referenced by <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a> and <a href="#a8ed9829c73ee2b346eefc344633ef122">isOffsetInRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createPICLabelUId() {#afe64db154ac991cb59cbd0a91a9c655e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createPICLabelUId ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### initPICLabelUId() {#a16751ce70ea59361531918891088fd7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::initPICLabelUId (unsigned UId)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BBInfo {#af292616f0f4e969fef2e46519880c4dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BasicBlockInfo&gt; anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::BBInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### CPEntries {#ab83104a7b1db171f4aa5a90f71895da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;CPEntry&gt; &gt; anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::CPEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CPEntries - Keep track of all of the constant pool entry machine instructions.</p>


<p>For each original constpool index (i.e. those that existed upon entry to this pass), it keeps a vector of entries. Original elements are cloned as we go along; the clones are put in the vector of the original element, but have distinct CPIs.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### CPUsers {#a68df402ec0e1495cb28c4ff7951b918c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CPUser&gt; anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::CPUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CPUsers - Keep track of all of the machine instructions that use various constant pools and their max displacement.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### ImmBranches {#a772ff7f87a7e3078b7ce900ab36226eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ImmBranch&gt; anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::ImmBranches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ImmBranches - Keep track of all the immediate branch instructions.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MCP {#afabf4fb29fc0dccd216bd656a389fe63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineConstantPool* anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::MCP = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MF {#a33cfaa1eca37c1a6930e7a2bfb98ced3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MFI {#ad9d009de0deb443aed28870efbeb221d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYMachineFunctionInfo* anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::MFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### NewWaterList {#a41ebb8e065959c56131929923b790e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;MachineBasicBlock *, 4&gt; anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::NewWaterList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NewWaterList - The subset of WaterList that was created since the previous iteration by inserting unconditional branches.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### PICLabelUId {#a027b306e7c0aad1f21e946a8757c0089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::PICLabelUId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### STI {#aeb3d1fc38ef543199e48b460c0dba5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CSKYSubtarget* anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::STI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### TII {#a1b90b76e2a41f15d51a3e6931c79ee89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CSKYInstrInfo* anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

### WaterList {#a1b44fcfeb5d3ee0d87843f2b153480d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineBasicBlock *&gt; anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::WaterList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WaterList - A sorted list of basic blocks where islands could be placed (i.e.</p>


<p>blocks that don't fall through to the following block, due to a return, unreachable, or unconditional branch).</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#adff00ea41ead523def4f011c420a4101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char CSKYConstantIslands::ID = 0</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a>.</p>


<p>Referenced by <a href="#a5c45f2e455446584aceb11cdeec58440">CSKYConstantIslands</a> and <a href="#a800f62f10fe1fafc076ae4002371ba45">handleConstantPoolUser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp">CSKYConstantIslandPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
