---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsConstantIslands` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands">MipsConstantIslands</a> - Due to limited PC-relative displacements, <a href="/web-llvm/docs/api/namespaces/llvm/mips">Mips</a> requires constant pool entries to be scattered among the instructions inside a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f2076a28018c3bfc723f8e050d47f1">water_iterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5de99ed1dd179bee53f782e65658825">MipsConstantIslands</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d4287d21f67efdb4195c66923f5a522">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a4d4287d21f67efdb4195c66923f5a522">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a> (MachineFunction &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a3bce3734199ffc400a2172acaaf616d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed0ecac46a557ab2e45f837ad079795">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3068d2fa3c2556694ca3db57b7c197dd">doInitialPlacement</a> (std::vector&lt; MachineInstr * &gt; &amp;CPEMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialPlacement - Perform the initial placement of the constant pool entries. <a href="#a3068d2fa3c2556694ca3db57b7c197dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">CPEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a421414700d8d58b412a7e067cb02ad">findConstPoolEntry</a> (unsigned CPI, const MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findConstPoolEntry - Given the constpool index and CONSTPOOL_ENTRY MI, look up the corresponding CPEntry. <a href="#a1a421414700d8d58b412a7e067cb02ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5077615197d034930b58d221032e96f0">getCPEAlign</a> (const MachineInstr &amp;CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCPEAlign - Returns the required alignment of the constant pool entry represented by CPEMI. <a href="#a5077615197d034930b58d221032e96f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f59896e3d3eccc7cae863ff29642896">initializeFunctionInfo</a> (const std::vector&lt; MachineInstr * &gt; &amp;CPEMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>initializeFunctionInfo - Do the initial scan of the function, building up information about the sizes of each block, the location of all the water, and finding all of the constant pool users. <a href="#a5f59896e3d3eccc7cae863ff29642896">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf67bdb496306b9cd4fd8bfed5c5a58">getOffsetOf</a> (MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOffsetOf - Return the current offset of the specified machine instruction from the start of the function. <a href="#acdf67bdb496306b9cd4fd8bfed5c5a58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a834ed21b1c7973122c01bd42928af333">getUserOffset</a> (CPUser &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e6938d2a62e2461cc8809a568a2d431">dumpBBs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print block size and offset information - debugging <a href="#a6e6938d2a62e2461cc8809a568a2d431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> (unsigned UserOffset, unsigned TrialOffset, unsigned Disp, bool NegativeOK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a0a6a8c8eaf928c2362effb37e73ab">isOffsetInRange</a> (unsigned UserOffset, unsigned TrialOffset, const CPUser &amp;U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b47e627bb837517308b9541f97f6b5">computeBlockSize</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>computeBlockSize - Compute the size and some alignment information for MBB. <a href="#a77b47e627bb837517308b9541f97f6b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747abf73a79323919b62fb98e61aeaf2">splitBlockBeforeInstr</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the basic block containing MI into two blocks, which are joined by an unconditional branch. <a href="#a747abf73a79323919b62fb98e61aeaf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2810208a226ed8b333882063153be2e0">updateForInsertedWaterBlock</a> (MachineBasicBlock *NewBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateForInsertedWaterBlock - When a block is newly inserted into the machine function, it upsets all of the block numbers. <a href="#a2810208a226ed8b333882063153be2e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a> (MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">decrementCPEReferenceCount</a> (unsigned CPI, MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>decrementCPEReferenceCount - find the constant pool entry with index CPI and instruction CPEMI, and decrement its refcount. <a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85299a5742cf6712729343b973727ab7">findInRangeCPEntry</a> (CPUser &amp;U, unsigned UserOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; if not, see if an in-range clone of the CPE is in range, and if so, change the data structures so the user references the clone. <a href="#a85299a5742cf6712729343b973727ab7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">findLongFormInRangeCPEntry</a> (CPUser &amp;U, unsigned UserOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; This version checks if the longer form of the instruction can be used to to satisfy things. <a href="#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909a324ed32517aaca69fb2e87f41bca">findAvailableWater</a> (CPUser &amp;U, unsigned UserOffset, water_iterator &amp;WaterIter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findAvailableWater - Look for an existing entry in the WaterList in which we can place the CPE referenced from U so it's within range of U's MI. <a href="#a909a324ed32517aaca69fb2e87f41bca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac438bed7ae6afbb9ff9e0be02099ad0f">createNewWater</a> (unsigned CPUserIndex, unsigned UserOffset, MachineBasicBlock *&amp;NewMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createNewWater - No existing WaterList entry will work for CPUsers[CPUserIndex], so create a place to put the CPE. <a href="#ac438bed7ae6afbb9ff9e0be02099ad0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> (unsigned CPUserIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handleConstantPoolUser - Analyze the specified user, checking to see if it is out-of-range. <a href="#a4d3a04a082a7dd5b285cddb7feef368c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbda87d0f5c41ed3eca00b354a53417d">removeDeadCPEMI</a> (MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeDeadCPEMI - Remove a dead constant pool entry instruction. <a href="#abbda87d0f5c41ed3eca00b354a53417d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1b9c7bc8345561b60f6d942c5a16126">removeUnusedCPEntries</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeUnusedCPEntries - Remove constant pool entries whose refcounts are zero. <a href="#aa1b9c7bc8345561b60f6d942c5a16126">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31eb3e86e2c774c4c03267a7368cadf0">isCPEntryInRange</a> (MachineInstr *MI, unsigned UserOffset, MachineInstr *CPEMI, unsigned Disp, bool NegOk, bool DoDump=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCPEntryInRange - Returns true if the distance between specific MI and specific ConstPool entry instruction can fit in MI's displacement field. <a href="#a31eb3e86e2c774c4c03267a7368cadf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ee101062ec8079d8d7fadafb29c511">isWaterInRange</a> (unsigned UserOffset, MachineBasicBlock *Water, CPUser &amp;U, unsigned &amp;Growth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isWaterInRange - Returns true if a CPE placed after the specified Water (a basic block) will be in range for the specific MI. <a href="#a54ee101062ec8079d8d7fadafb29c511">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab686eff61461eaac81cf87ba84143a0a">isBBInRange</a> (MachineInstr *MI, MachineBasicBlock *BB, unsigned Disp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isBBInRange - Returns true if the distance between specific MI and specific BB can fit in MI's displacement field. <a href="#ab686eff61461eaac81cf87ba84143a0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9afd9876c042dc602d1eea614b13129">fixupImmediateBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupImmediateBr - Fix up an immediate branch whose destination is too far away to fit in its displacement field. <a href="#ac9afd9876c042dc602d1eea614b13129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e3daf4218b791b2796b808627b7f864">fixupConditionalBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupConditionalBr - Fix up a conditional branch whose destination is too far away to fit in its displacement field. <a href="#a3e3daf4218b791b2796b808627b7f864">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7faaededab3b537edc011e168876a92b">fixupUnconditionalBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupUnconditionalBr - Fix up an unconditional branch whose destination is too far away to fit in its displacement field. <a href="#a7faaededab3b537edc011e168876a92b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657c17735f988deb12c8067e40be44d4">prescanForConstants</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891b9ad6b0a73dce910ef9e1288b9589">initPICLabelUId</a> (unsigned UId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1da0e648d3236347558f8ec47e5d9541">createPICLabelUId</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58771c042bdfa919ec8bcbb1d31c16f6">BBInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10dcf6f9c47bb7108021a53309a7d7e4">WaterList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WaterList - A sorted list of basic blocks where islands could be placed (i.e. <a href="#a10dcf6f9c47bb7108021a53309a7d7e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1742c7abbffe2e7c8f52ddf471134d2d">NewWaterList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NewWaterList - The subset of WaterList that was created since the previous iteration by inserting unconditional branches. <a href="#a1742c7abbffe2e7c8f52ddf471134d2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; CPUser &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe46c27f7de9e1bda02f4e600d7e7956">CPUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPUsers - Keep track of all of the machine instructions that use various constant pools and their max displacement. <a href="#afe46c27f7de9e1bda02f4e600d7e7956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; CPEntry &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada86103c0d8df9f57ccd95c8b05b4edf">CPEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPEntries - Keep track of all of the constant pool entry machine instructions. <a href="#ada86103c0d8df9f57ccd95c8b05b4edf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; ImmBranch &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e290b3a199b1b4442e0813699c419d">ImmBranches</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ImmBranches - Keep track of all the immediate branch instructions. <a href="#a08e290b3a199b1b4442e0813699c419d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0c3b7629352c1badf160b5c543f300">HasFarJump</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasFarJump - True if any far jump instruction has been emitted during the branch fix up pass. <a href="#a0c0c3b7629352c1badf160b5c543f300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aede378370907852a8b71a3736f9bb3e8">STI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo">Mips16InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd28ae71ea74a61c09836e32e327a8d">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo">MipsFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a270a74a5b73411acc138319b5c95b400">MFI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f99b0f4c14da5268d3cc55189cf0abe">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a410843c5d1fd2a31cbc8f4e8b3a5fc83">MCP</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a5194141e8f78dd727b7e25c22e0ee">PICLabelUId</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc48aa9316247959c8b794508778bb13">PrescannedForConstants</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0890e6f8c439d468daf1459997d306f">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands">MipsConstantIslands</a> - Due to limited PC-relative displacements, <a href="/web-llvm/docs/api/namespaces/llvm/mips">Mips</a> requires constant pool entries to be scattered among the instructions inside a function.</p>


<p>To do this, it completely ignores the normal LLVM constant pool; instead, it places constants wherever it feels like with special instructions.</p>


<p>The terminology used in this pass includes: Islands - Clumps of constants placed in the function. Water - Potential places where an island could be formed. CPE - A constant pool entry that has been placed somewhere, which tracks a list of users.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### water\_iterator {#a00f2076a28018c3bfc723f8e050d47f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::water_iterator =  std::vector&lt;MachineBasicBlock *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MipsConstantIslands() {#aa5de99ed1dd179bee53f782e65658825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::MipsConstantIslands ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="#aa0890e6f8c439d468daf1459997d306f">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a270ba817659def3d8dae62b9f3d45098">llvm::createMipsConstantIslandPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustBBOffsetsAfter() {#a94b3ade7f05777308f0695ef6eb5da19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::adjustBBOffsetsAfter (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ac438bed7ae6afbb9ff9e0be02099ad0f">createNewWater</a>, <a href="#a3e3daf4218b791b2796b808627b7f864">fixupConditionalBr</a>, <a href="#a7faaededab3b537edc011e168876a92b">fixupUnconditionalBr</a>, <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a>, <a href="#a5f59896e3d3eccc7cae863ff29642896">initializeFunctionInfo</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>, <a href="#abbda87d0f5c41ed3eca00b354a53417d">removeDeadCPEMI</a> and <a href="#a747abf73a79323919b62fb98e61aeaf2">splitBlockBeforeInstr</a>.</p>

</div>
</div>

### computeBlockSize() {#a77b47e627bb837517308b9541f97f6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::computeBlockSize (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>computeBlockSize - Compute the size and some alignment information for MBB.</p>


<p>This function updates BBInfo directly.</p>


<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a5f59896e3d3eccc7cae863ff29642896">initializeFunctionInfo</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> and <a href="#a747abf73a79323919b62fb98e61aeaf2">splitBlockBeforeInstr</a>.</p>

</div>
</div>

### createNewWater() {#ac438bed7ae6afbb9ff9e0be02099ad0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::createNewWater (unsigned CPUserIndex, unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; NewMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createNewWater - No existing WaterList entry will work for CPUsers[CPUserIndex], so create a place to put the CPE.</p>


<p>The end of the block is used if in range, and the conditional branch munged so control flow is correct. Otherwise the block is split to create a hole with an unconditional branch around it. In either case NewMBB is set to a block following which the new island can be inserted (the WaterList is not adjusted).</p>


<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf35424231192c6b4a3e22d711f50b1e">llvm::MachineBasicBlock::back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a2591f82337ce78f51703e6b3382eec3c">BBHasFallthrough</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a2e62a3c07e3b7d0f0591b2d80bd20967">getUnconditionalBrDisp</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#a747abf73a79323919b62fb98e61aeaf2">splitBlockBeforeInstr</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### decrementCPEReferenceCount() {#a1a9eb61d7398e8effdbe50e72ed69b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::decrementCPEReferenceCount (unsigned CPI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>decrementCPEReferenceCount - find the constant pool entry with index CPI and instruction CPEMI, and decrement its refcount.</p>


<p>If the refcount becomes 0 remove the entry and instruction. Returns true if we removed the entry, false if we didn't.</p>


<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1a421414700d8d58b412a7e067cb02ad">findConstPoolEntry</a> and <a href="#abbda87d0f5c41ed3eca00b354a53417d">removeDeadCPEMI</a>.</p>


<p>Referenced by <a href="#a85299a5742cf6712729343b973727ab7">findInRangeCPEntry</a>, <a href="#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">findLongFormInRangeCPEntry</a>, <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### doInitialPlacement() {#a3068d2fa3c2556694ca3db57b7c197dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::doInitialPlacement (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CPEMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>doInitialPlacement - Perform the initial placement of the constant pool entries.</p>


<p>To start with, we put them all at the end of the function.</p>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#ac0982c4457626f028f88f7031a6e42db">AlignConstantIslands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cec41e65c7ebf7da3e9d41f2317065e">llvm::MachineBasicBlock::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae13575403de0e7d005f1b5905053f3ea">llvm::MachineBasicBlock::getAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3b1dce1f3354a357fb9061bb7568a84e">llvm::MachineBasicBlock::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cb665c210dc8e43f537cf4c9b84e2c7">llvm::MachineBasicBlock::setAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a>.</p>

</div>
</div>

### dumpBBs() {#a6e6938d2a62e2461cc8809a568a2d431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MipsConstantIslands::dumpBBs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>print block size and offset information - debugging</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a>.</p>

</div>
</div>

### findAvailableWater() {#a909a324ed32517aaca69fb2e87f41bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::findAvailableWater (CPUser &amp; U, unsigned UserOffset, water_iterator &amp; WaterIter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findAvailableWater - Look for an existing entry in the WaterList in which we can place the CPE referenced from U so it's within range of U's MI.</p>


<p>Returns true if found, false if not. If it returns true, WaterIter is set to the WaterList entry. To ensure that this pass terminates, the CPE location for a particular CPUser is only allowed to move to a lower address, so search backward from the end of the list and prefer the first water that is in range.</p>


<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#a54ee101062ec8079d8d7fadafb29c511">isWaterInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### findConstPoolEntry() {#a1a421414700d8d58b412a7e067cb02ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsConstantIslands::CPEntry * MipsConstantIslands::findConstPoolEntry (unsigned CPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findConstPoolEntry - Given the constpool index and CONSTPOOL_ENTRY MI, look up the corresponding CPEntry.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>Referenced by <a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">decrementCPEReferenceCount</a> and <a href="#a5f59896e3d3eccc7cae863ff29642896">initializeFunctionInfo</a>.</p>

</div>
</div>

### findInRangeCPEntry() {#a85299a5742cf6712729343b973727ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsConstantIslands::findInRangeCPEntry (CPUser &amp; U, unsigned UserOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; if not, see if an in-range clone of the CPE is in range, and if so, change the data structures so the user references the clone.</p>


<p>Returns: 0 = no existing entry found 1 = entry found, and there were no code insertions or deletions 2 = entry found, and there were code insertions or deletions</p>


<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">decrementCPEReferenceCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a31eb3e86e2c774c4c03267a7368cadf0">isCPEntryInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### findLongFormInRangeCPEntry() {#ab5cf6bcc5a1eea788ee5fcc95ea36a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsConstantIslands::findLongFormInRangeCPEntry (CPUser &amp; U, unsigned UserOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; This version checks if the longer form of the instruction can be used to to satisfy things.</p>


<p>if not, see if an in-range clone of the CPE is in range, and if so, change the data structures so the user references the clone. Returns: 0 = no existing entry found 1 = entry found, and there were no code insertions or deletions 2 = entry found, and there were code insertions or deletions</p>


<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">decrementCPEReferenceCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a31eb3e86e2c774c4c03267a7368cadf0">isCPEntryInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### fixupConditionalBr() {#a3e3daf4218b791b2796b808627b7f864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::fixupConditionalBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupConditionalBr - Fix up a conditional branch whose destination is too far away to fit in its displacement field.</p>


<p>It is converted to an inverse conditional branch + an unconditional branch to the destination.</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a2591f82337ce78f51703e6b3382eec3c">BBHasFallthrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a4ed70b091d984638ade40c36b700db3a">branchMaxOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#aebe2f39320b8f7f94354d4a19091d4fe">branchTargetOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a2e62a3c07e3b7d0f0591b2d80bd20967">getUnconditionalBrDisp</a>, <a href="#ab686eff61461eaac81cf87ba84143a0a">isBBInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a91c590e8191655a6739eb4df9c443896">llvm::MachineInstr::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a4d0addd716a1fc273a5b43e0e850f376">longformBranchOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a98e9c9e8ef7cbb6c4aa89a38f21decfa">llvm::MachineOperand::setMBB</a> and <a href="#a747abf73a79323919b62fb98e61aeaf2">splitBlockBeforeInstr</a>.</p>


<p>Referenced by <a href="#ac9afd9876c042dc602d1eea614b13129">fixupImmediateBr</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### fixupImmediateBr() {#ac9afd9876c042dc602d1eea614b13129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::fixupImmediateBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupImmediateBr - Fix up an immediate branch whose destination is too far away to fit in its displacement field.</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#aebe2f39320b8f7f94354d4a19091d4fe">branchTargetOperand</a>, <a href="#a3e3daf4218b791b2796b808627b7f864">fixupConditionalBr</a>, <a href="#a7faaededab3b537edc011e168876a92b">fixupUnconditionalBr</a>, <a href="#ab686eff61461eaac81cf87ba84143a0a">isBBInRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> and <a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a>.</p>

</div>
</div>

### fixupUnconditionalBr() {#a7faaededab3b537edc011e168876a92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::fixupUnconditionalBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupUnconditionalBr - Fix up an unconditional branch whose destination is too far away to fit in its displacement field.</p>


<p>If the LR register has been spilled in the epilogue, then we can use BL to implement a far jump. Otherwise, add an intermediate branch instruction to a branch.</p>


<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab686eff61461eaac81cf87ba84143a0a">isBBInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cb665c210dc8e43f537cf4c9b84e2c7">llvm::MachineBasicBlock::setAlignment</a>.</p>


<p>Referenced by <a href="#ac9afd9876c042dc602d1eea614b13129">fixupImmediateBr</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### getCPEAlign() {#a5077615197d034930b58d221032e96f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align MipsConstantIslands::getCPEAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getCPEAlign - Returns the required alignment of the constant pool entry represented by CPEMI.</p>


<p>Alignment is measured in log2(bytes) units.</p>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#ac0982c4457626f028f88f7031a6e42db">AlignConstantIslands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#abbda87d0f5c41ed3eca00b354a53417d">removeDeadCPEMI</a>.</p>

</div>
</div>

### getOffsetOf() {#acdf67bdb496306b9cd4fd8bfed5c5a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsConstantIslands::getOffsetOf (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOffsetOf - Return the current offset of the specified machine instruction from the start of the function.</p>


<p>This offset changes as stuff is moved around inside the function.</p>


<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a834ed21b1c7973122c01bd42928af333">getUserOffset</a>, <a href="#ab686eff61461eaac81cf87ba84143a0a">isBBInRange</a> and <a href="#a31eb3e86e2c774c4c03267a7368cadf0">isCPEntryInRange</a>.</p>

</div>
</div>

### getPassName() {#a4d4287d21f67efdb4195c66923f5a522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::getPassName ()</td>
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


<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### getRequiredProperties() {#aeed0ecac46a557ab2e45f837ad079795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::getRequiredProperties ()</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### getUserOffset() {#a834ed21b1c7973122c01bd42928af333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsConstantIslands::getUserOffset (CPUser &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>Reference <a href="#acdf67bdb496306b9cd4fd8bfed5c5a58">getOffsetOf</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a>.</p>

</div>
</div>

### handleConstantPoolUser() {#a4d3a04a082a7dd5b285cddb7feef368c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::handleConstantPoolUser (unsigned CPUserIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handleConstantPoolUser - Analyze the specified user, checking to see if it is out-of-range.</p>


<p>If so, pick up the constant pool value and move it some place in-range. Return true if we changed any addresses (thus must run another pass of branch lengthening), false otherwise.</p>


<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#ac438bed7ae6afbb9ff9e0be02099ad0f">createNewWater</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">decrementCPEReferenceCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad26bff839257f220557ce812b2159c72">llvm::MachineBasicBlock::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="#a909a324ed32517aaca69fb2e87f41bca">findAvailableWater</a>, <a href="#a85299a5742cf6712729343b973727ab7">findInRangeCPEntry</a>, <a href="#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">findLongFormInRangeCPEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a5077615197d034930b58d221032e96f0">getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a834ed21b1c7973122c01bd42928af333">getUserOffset</a>, <a href="#aa0890e6f8c439d468daf1459997d306f">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a64b4c652c8d686f935a8ea55c4b19420">NoLoadRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cb665c210dc8e43f537cf4c9b84e2c7">llvm::MachineBasicBlock::setAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a2810208a226ed8b333882063153be2e0">updateForInsertedWaterBlock</a>.</p>


<p>Referenced by <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> and <a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a>.</p>

</div>
</div>

### initializeFunctionInfo() {#a5f59896e3d3eccc7cae863ff29642896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::initializeFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CPEMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>initializeFunctionInfo - Do the initial scan of the function, building up information about the sizes of each block, the location of all the water, and finding all of the constant pool users.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#a2591f82337ce78f51703e6b3382eec3c">BBHasFallthrough</a>, <a href="#a77b47e627bb837517308b9541f97f6b5">computeBlockSize</a>, <a href="#a1a421414700d8d58b412a7e067cb02ad">findConstPoolEntry</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a>.</p>

</div>
</div>

### isBBInRange() {#ab686eff61461eaac81cf87ba84143a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::isBBInRange (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned Disp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isBBInRange - Returns true if the distance between specific MI and specific BB can fit in MI's displacement field.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#acdf67bdb496306b9cd4fd8bfed5c5a58">getOffsetOf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#a3e3daf4218b791b2796b808627b7f864">fixupConditionalBr</a>, <a href="#ac9afd9876c042dc602d1eea614b13129">fixupImmediateBr</a>, <a href="#a7faaededab3b537edc011e168876a92b">fixupUnconditionalBr</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### isCPEntryInRange() {#a31eb3e86e2c774c4c03267a7368cadf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::isCPEntryInRange (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI, unsigned Disp, bool NegOk, bool DoDump=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isCPEntryInRange - Returns true if the distance between specific MI and specific ConstPool entry instruction can fit in MI's displacement field.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#acdf67bdb496306b9cd4fd8bfed5c5a58">getOffsetOf</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#a85299a5742cf6712729343b973727ab7">findInRangeCPEntry</a>, <a href="#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">findLongFormInRangeCPEntry</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### isOffsetInRange() {#af8551cd00faa264bb137701056f6f3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::isOffsetInRange (unsigned UserOffset, unsigned TrialOffset, unsigned Disp, bool NegativeOK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="#a77b47e627bb837517308b9541f97f6b5">computeBlockSize</a>, <a href="#ac438bed7ae6afbb9ff9e0be02099ad0f">createNewWater</a>, <a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">decrementCPEReferenceCount</a>, <a href="#a909a324ed32517aaca69fb2e87f41bca">findAvailableWater</a>, <a href="#a85299a5742cf6712729343b973727ab7">findInRangeCPEntry</a>, <a href="#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">findLongFormInRangeCPEntry</a>, <a href="#a3e3daf4218b791b2796b808627b7f864">fixupConditionalBr</a>, <a href="#ac9afd9876c042dc602d1eea614b13129">fixupImmediateBr</a>, <a href="#a7faaededab3b537edc011e168876a92b">fixupUnconditionalBr</a>, <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a>, <a href="#ab686eff61461eaac81cf87ba84143a0a">isBBInRange</a>, <a href="#a31eb3e86e2c774c4c03267a7368cadf0">isCPEntryInRange</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>, <a href="#a54ee101062ec8079d8d7fadafb29c511">isWaterInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a657c17735f988deb12c8067e40be44d4">prescanForConstants</a>, <a href="#abbda87d0f5c41ed3eca00b354a53417d">removeDeadCPEMI</a>, <a href="#aa1b9c7bc8345561b60f6d942c5a16126">removeUnusedCPEntries</a>, <a href="#a747abf73a79323919b62fb98e61aeaf2">splitBlockBeforeInstr</a> and <a href="#a2810208a226ed8b333882063153be2e0">updateForInsertedWaterBlock</a>.</p>


<p>Referenced by <a href="#ac438bed7ae6afbb9ff9e0be02099ad0f">createNewWater</a>, <a href="#a31eb3e86e2c774c4c03267a7368cadf0">isCPEntryInRange</a>, <a href="#a13a0a6a8c8eaf928c2362effb37e73ab">isOffsetInRange</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> and <a href="#a54ee101062ec8079d8d7fadafb29c511">isWaterInRange</a>.</p>

</div>
</div>

### isOffsetInRange() {#a13a0a6a8c8eaf928c2362effb37e73ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::isOffsetInRange (unsigned UserOffset, unsigned TrialOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CPUser &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>Reference <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### isWaterInRange() {#a54ee101062ec8079d8d7fadafb29c511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::isWaterInRange (unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Water, CPUser &amp; U, unsigned &amp; Growth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isWaterInRange - Returns true if a CPE placed after the specified Water (a basic block) will be in range for the specific MI.</p>


<p>Compute how much the function will grow by inserting a CPE after Water.</p>


<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a909a324ed32517aaca69fb2e87f41bca">findAvailableWater</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### prescanForConstants() {#a657c17735f988deb12c8067e40be44d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::prescanForConstants ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aebe6fe7948d0ae093aba94381c73ed67">llvm::MachineOperand::CreateCPI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3ad7da1b76e5799f53a399b7a96ba67437">llvm::Literal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> and <a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a>.</p>

</div>
</div>

### removeDeadCPEMI() {#abbda87d0f5c41ed3eca00b354a53417d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::removeDeadCPEMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeDeadCPEMI - Remove a dead constant pool entry instruction.</p>


<p>Update sizes and offsets of impacted basic blocks.</p>


<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#af6522321d1fc294742102bbee0779b62">BBIsJumpedOver</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="#a5077615197d034930b58d221032e96f0">getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cb665c210dc8e43f537cf4c9b84e2c7">llvm::MachineBasicBlock::setAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a1a9eb61d7398e8effdbe50e72ed69b1d">decrementCPEReferenceCount</a>, <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> and <a href="#aa1b9c7bc8345561b60f6d942c5a16126">removeUnusedCPEntries</a>.</p>

</div>
</div>

### removeUnusedCPEntries() {#aa1b9c7bc8345561b60f6d942c5a16126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::removeUnusedCPEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeUnusedCPEntries - Remove constant pool entries whose refcounts are zero.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>Reference <a href="#abbda87d0f5c41ed3eca00b354a53417d">removeDeadCPEMI</a>.</p>


<p>Referenced by <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a> and <a href="#a3bce3734199ffc400a2172acaaf616d0">runOnMachineFunction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a3bce3734199ffc400a2172acaaf616d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsConstantIslands::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3068d2fa3c2556694ca3db57b7c197dd">doInitialPlacement</a>, <a href="#a6e6938d2a62e2461cc8809a568a2d431">dumpBBs</a>, <a href="#ac9afd9876c042dc602d1eea614b13129">fixupImmediateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a>, <a href="#a5f59896e3d3eccc7cae863ff29642896">initializeFunctionInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a657c17735f988deb12c8067e40be44d4">prescanForConstants</a>, <a href="#aa1b9c7bc8345561b60f6d942c5a16126">removeUnusedCPEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a056776ea56d64939bb6cf447b0e24e3c">llvm::MipsSubtarget::useConstantIslands</a>.</p>

</div>
</div>

### splitBlockBeforeInstr() {#a747abf73a79323919b62fb98e61aeaf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsConstantIslands::splitBlockBeforeInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split the basic block containing MI into two blocks, which are joined by an unconditional branch.</p>


<p>Update data structures and renumber blocks to account for this change and returns the newly created block.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="#a94b3ade7f05777308f0695ef6eb5da19">adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a29885c784cdf6c08d6952699d790c8c4">CompareMBBNumbers</a>, <a href="#a77b47e627bb837517308b9541f97f6b5">computeBlockSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a31e57b158a17c459f0dc34b0e602ecc6">llvm::MachineBasicBlock::transferSuccessors</a>.</p>


<p>Referenced by <a href="#ac438bed7ae6afbb9ff9e0be02099ad0f">createNewWater</a>, <a href="#a3e3daf4218b791b2796b808627b7f864">fixupConditionalBr</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

### updateForInsertedWaterBlock() {#a2810208a226ed8b333882063153be2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsConstantIslands::updateForInsertedWaterBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>updateForInsertedWaterBlock - When a block is newly inserted into the machine function, it upsets all of the block numbers.</p>


<p>Renumber the blocks and update the arrays that parallel this numbering.</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a29885c784cdf6c08d6952699d790c8c4">CompareMBBNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac85349aab432e6b7d8b2e8926048a6de">llvm::MachineFunction::RenumberBlocks</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#af8551cd00faa264bb137701056f6f3d0">isOffsetInRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createPICLabelUId() {#a1da0e648d3236347558f8ec47e5d9541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createPICLabelUId ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### initPICLabelUId() {#a891b9ad6b0a73dce910ef9e1288b9589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::initPICLabelUId (unsigned UId)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BBInfo {#a58771c042bdfa919ec8bcbb1d31c16f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BasicBlockInfo&gt; anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::BBInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### CPEntries {#ada86103c0d8df9f57ccd95c8b05b4edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;CPEntry&gt; &gt; anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::CPEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CPEntries - Keep track of all of the constant pool entry machine instructions.</p>


<p>For each original constpool index (i.e. those that existed upon entry to this pass), it keeps a vector of entries. Original elements are cloned as we go along; the clones are put in the vector of the original element, but have distinct CPIs.</p>


<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### CPUsers {#afe46c27f7de9e1bda02f4e600d7e7956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CPUser&gt; anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::CPUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CPUsers - Keep track of all of the machine instructions that use various constant pools and their max displacement.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### HasFarJump {#a0c0c3b7629352c1badf160b5c543f300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::HasFarJump</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasFarJump - True if any far jump instruction has been emitted during the branch fix up pass.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### ImmBranches {#a08e290b3a199b1b4442e0813699c419d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ImmBranch&gt; anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::ImmBranches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ImmBranches - Keep track of all the immediate branch instructions.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MCP {#a410843c5d1fd2a31cbc8f4e8b3a5fc83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineConstantPool* anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::MCP = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MF {#a4f99b0f4c14da5268d3cc55189cf0abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MFI {#a270a74a5b73411acc138319b5c95b400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsFunctionInfo* anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::MFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### NewWaterList {#a1742c7abbffe2e7c8f52ddf471134d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;MachineBasicBlock*, 4&gt; anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::NewWaterList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NewWaterList - The subset of WaterList that was created since the previous iteration by inserting unconditional branches.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### PICLabelUId {#a76a5194141e8f78dd727b7e25c22e0ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::PICLabelUId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### PrescannedForConstants {#adc48aa9316247959c8b794508778bb13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::PrescannedForConstants = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### STI {#aede378370907852a8b71a3736f9bb3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsSubtarget* anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::STI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### TII {#accd28ae71ea74a61c09836e32e327a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Mips16InstrInfo* anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

### WaterList {#a10dcf6f9c47bb7108021a53309a7d7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineBasicBlock*&gt; anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::WaterList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WaterList - A sorted list of basic blocks where islands could be placed (i.e.</p>


<p>blocks that don't fall through to the following block, due to a return, unreachable, or unconditional branch).</p>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#aa0890e6f8c439d468daf1459997d306f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char MipsConstantIslands::ID = 0</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a>.</p>


<p>Referenced by <a href="#a4d3a04a082a7dd5b285cddb7feef368c">handleConstantPoolUser</a> and <a href="#aa5de99ed1dd179bee53f782e65658825">MipsConstantIslands</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp">MipsConstantIslandPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
