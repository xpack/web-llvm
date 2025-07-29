---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMConstantIslands` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands">ARMConstantIslands</a> - Due to limited PC-relative displacements, <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> requires constant pool entries to be scattered among the instructions inside a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87abe235fd0b4caa9549a01f250b10d2">water_iterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab5453e9f3f4ed83c6bb9e4ebd68b20">ARMConstantIslands</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf4297850ccff6052205f45bc2ba2f87">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#aaf4297850ccff6052205f45bc2ba2f87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225e3a366286304012ebb04ca6aee82d">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a225e3a366286304012ebb04ca6aee82d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e87361befd343a840e87d2ef988269e">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadaa10dcef3fe4481b60ff1fb9c34780">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#aadaa10dcef3fe4481b60ff1fb9c34780">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472523a060d0c5f613fdaf2edf880f5e">doInitialConstPlacement</a> (std::vector&lt; MachineInstr * &gt; &amp;CPEMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the initial placement of the regular constant pool entries. <a href="#a472523a060d0c5f613fdaf2edf880f5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d08a0032243809d891261111e6c4747">doInitialJumpTablePlacement</a> (std::vector&lt; MachineInstr * &gt; &amp;CPEMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do initial placement of the jump tables. <a href="#a0d08a0032243809d891261111e6c4747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab648cc5da37b64781455162df55dd006">BBHasFallthrough</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BBHasFallthrough - Return true if the specified basic block can fallthrough into the block immediately after it. <a href="#ab648cc5da37b64781455162df55dd006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">CPEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a29aeb2c25d3927e53dbcdec7531fc2">findConstPoolEntry</a> (unsigned CPI, const MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findConstPoolEntry - Given the constpool index and CONSTPOOL_ENTRY MI, look up the corresponding CPEntry. <a href="#a7a29aeb2c25d3927e53dbcdec7531fc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58eb0c9489392e69edfdab54bb9a2fba">getCPEAlign</a> (const MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCPEAlign - Returns the required alignment of the constant pool entry represented by CPEMI. <a href="#a58eb0c9489392e69edfdab54bb9a2fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4995445c7a400cc68dc2e59587e68b7d">scanFunctionJumpTables</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>scanFunctionJumpTables - Do a scan of the function, building up information about the sizes of each block and the locations of all the jump tables. <a href="#a4995445c7a400cc68dc2e59587e68b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed78d2699a9d157c7ad08ae78fc48e14">initializeFunctionInfo</a> (const std::vector&lt; MachineInstr * &gt; &amp;CPEMIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>initializeFunctionInfo - Do the initial scan of the function, building up information about the sizes of each block, the location of all the water, and finding all of the constant pool users. <a href="#aed78d2699a9d157c7ad08ae78fc48e14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0ff01e9af545b83667a6f3b1a309a3">splitBlockBeforeInstr</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the basic block containing MI into two blocks, which are joined by an unconditional branch. <a href="#a2d0ff01e9af545b83667a6f3b1a309a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9ee57208388fce44d1de2773ba04f75">updateForInsertedWaterBlock</a> (MachineBasicBlock *NewBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateForInsertedWaterBlock - When a block is newly inserted into the machine function, it upsets all of the block numbers. <a href="#ae9ee57208388fce44d1de2773ba04f75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1132d26053b7c6b6945d4d05957cca6f">decrementCPEReferenceCount</a> (unsigned CPI, MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>decrementCPEReferenceCount - find the constant pool entry with index CPI and instruction CPEMI, and decrement its refcount. <a href="#a1132d26053b7c6b6945d4d05957cca6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab524260c1fdfc45ca8c2b7ade897fafe">getCombinedIndex</a> (const MachineInstr *CPEMI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0be587caca37c8589d2a60c6e59f24">findInRangeCPEntry</a> (CPUser &amp;U, unsigned UserOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; if not, see if an in-range clone of the CPE is in range, and if so, change the data structures so the user references the clone. <a href="#abf0be587caca37c8589d2a60c6e59f24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a35b64e8ecf993c780868342ebc1f8">findAvailableWater</a> (CPUser &amp;U, unsigned UserOffset, water_iterator &amp;WaterIter, bool CloserWater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findAvailableWater - Look for an existing entry in the WaterList in which we can place the CPE referenced from U so it's within range of U's MI. <a href="#a36a35b64e8ecf993c780868342ebc1f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4d3fe25445806bc4392836a75db579">createNewWater</a> (unsigned CPUserIndex, unsigned UserOffset, MachineBasicBlock *&amp;NewMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createNewWater - No existing WaterList entry will work for CPUsers[CPUserIndex], so create a place to put the CPE. <a href="#a9e4d3fe25445806bc4392836a75db579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd480ce7b8dd317463fd4c3a73316fb">handleConstantPoolUser</a> (unsigned CPUserIndex, bool CloserWater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handleConstantPoolUser - Analyze the specified user, checking to see if it is out-of-range. <a href="#abdd480ce7b8dd317463fd4c3a73316fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2fe1bbc38cd8de84461690fab233e9e">removeDeadCPEMI</a> (MachineInstr *CPEMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeDeadCPEMI - Remove a dead constant pool entry instruction. <a href="#aa2fe1bbc38cd8de84461690fab233e9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bda926b4776787d25d7b0a0112f0dfc">removeUnusedCPEntries</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeUnusedCPEntries - Remove constant pool entries whose refcounts are zero. <a href="#a8bda926b4776787d25d7b0a0112f0dfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a015406c9be05ba875b6a6607a7b0d33f">isCPEntryInRange</a> (MachineInstr *MI, unsigned UserOffset, MachineInstr *CPEMI, unsigned Disp, bool NegOk, bool DoDump=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCPEntryInRange - Returns true if the distance between specific MI and specific ConstPool entry instruction can fit in MI's displacement field. <a href="#a015406c9be05ba875b6a6607a7b0d33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a6249ea0ff228890a3b2e326f8fe71">isWaterInRange</a> (unsigned UserOffset, MachineBasicBlock *Water, CPUser &amp;U, unsigned &amp;Growth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isWaterInRange - Returns true if a CPE placed after the specified Water (a basic block) will be in range for the specific MI. <a href="#a22a6249ea0ff228890a3b2e326f8fe71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5daae5ba9c59db3b92c4311b5d37473">fixupImmediateBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupImmediateBr - Fix up an immediate branch whose destination is too far away to fit in its displacement field. <a href="#aa5daae5ba9c59db3b92c4311b5d37473">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831aa146b4f1dccd62bcd565a6eaa80f">fixupConditionalBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupConditionalBr - Fix up a conditional branch whose destination is too far away to fit in its displacement field. <a href="#a831aa146b4f1dccd62bcd565a6eaa80f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ecba595e94ff061660c8b22e8716f07">fixupUnconditionalBr</a> (ImmBranch &amp;Br)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupUnconditionalBr - Fix up an unconditional branch whose destination is too far away to fit in its displacement field. <a href="#a1ecba595e94ff061660c8b22e8716f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9beafe176b49d8fd46daab6faca8ef02">optimizeThumb2Instructions</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dcb1f3b15c4c0e6501c2a28d78908cf">optimizeThumb2Branches</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e9766216f49ba8b940fbb7c91abb78">reorderThumb2JumpTables</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reorderThumb2JumpTables - Adjust the function's block layout to ensure that jump tables always branch forwards, since that's what tbb and tbh need. <a href="#a44e9766216f49ba8b940fbb7c91abb78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5a435a047ef3f277eec100c1ecf031">preserveBaseRegister</a> (MachineInstr *JumpMI, MachineInstr *LEAMI, unsigned &amp;DeadSize, bool &amp;CanDeleteLEA, bool &amp;BaseRegKill)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>While trying to form a TBB/TBH instruction, we may (if the table doesn't immediately follow the BR_JT) need access to the start of the jump-table. <a href="#a0e5a435a047ef3f277eec100c1ecf031">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad3b14f15be6b5e8dc1b4826f119696">optimizeThumb2JumpTables</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>optimizeThumb2JumpTables - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> tbb / tbh instructions to generate smaller jumptables when it's possible. <a href="#abad3b14f15be6b5e8dc1b4826f119696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6bc8ba7bb705dba758eb13c5c08408">adjustJTTargetBlockForward</a> (unsigned JTI, MachineBasicBlock *BB, MachineBasicBlock *JTBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7146125ff6a881a6b19fab8690e0091">getUserOffset</a> (CPUser &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUserOffset - Compute the offset of U.MI as seen by the hardware displacement computation. <a href="#af7146125ff6a881a6b19fab8690e0091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97f3dc8c8f9649142b128882c6d68554">dumpBBs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print block size and offset information - debugging <a href="#a97f3dc8c8f9649142b128882c6d68554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf72e81e912fc9c1a2d7913ac48d670">verify</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>verify - check BBOffsets, BBSizes, alignment of islands <a href="#afaf72e81e912fc9c1a2d7913ac48d670">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9276d20e7ad345d71593d7995720afae">isOffsetInRange</a> (unsigned UserOffset, unsigned TrialOffset, unsigned Disp, bool NegativeOK, bool IsSoImm=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98229bab8b53875bace6cdd43c0525fe">isOffsetInRange</a> (unsigned UserOffset, unsigned TrialOffset, const CPUser &amp;U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils">ARMBasicBlockUtils</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb99cca93ab051541c42391046d9daf">BBUtils</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610f64f4d5215f773f3604360c5c3639">WaterList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WaterList - A sorted list of basic blocks where islands could be placed (i.e. <a href="#a610f64f4d5215f773f3604360c5c3639">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcaaefb0325dd55841218c2b401a430">NewWaterList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NewWaterList - The subset of WaterList that was created since the previous iteration by inserting unconditional branches. <a href="#a5bcaaefb0325dd55841218c2b401a430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; CPUser &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d4c5e9c9ef1d2abbb92300b5be8c38">CPUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPUsers - Keep track of all of the machine instructions that use various constant pools and their max displacement. <a href="#a26d4c5e9c9ef1d2abbb92300b5be8c38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; CPEntry &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a03308500573324cb3619b9e8f567d">CPEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPEntries - Keep track of all of the constant pool entry machine instructions. <a href="#a58a03308500573324cb3619b9e8f567d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a2f6500d0e72e0bc875c66ab426533">JumpTableEntryIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a JT index to the offset in CPEntries containing copies of that table. <a href="#a28a2f6500d0e72e0bc875c66ab426533">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae272594f35c002c85edb799023a3245">JumpTableUserIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a JT index to the LEA that actually uses the index to calculate its base address. <a href="#aae272594f35c002c85edb799023a3245">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ed371a9d5e8b194d6402fe0c699cdc">BlockJumpTableRefCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; ImmBranch &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3dee94f255a59ef39503608f99c8a7">ImmBranches</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ImmBranches - Keep track of all the immediate branch instructions. <a href="#abd3dee94f255a59ef39503608f99c8a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8d08e657e6ed9c0c3ca1b1c179ac2c">PushPopMIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PushPopMIs - Keep track of all the Thumb push / pop instructions. <a href="#aff8d08e657e6ed9c0c3ca1b1c179ac2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52de6115c0eb43c179e676c824715ac">T2JumpTables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>T2JumpTables - Keep track of all the Thumb2 jumptable instructions. <a href="#ab52de6115c0eb43c179e676c824715ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7514c1eca73b9986376c81388f147e90">MF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0dbb8974ac506fa487d4dde50a93a3e">MCP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcf2a90f5b140ee4022487e495223bb">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b3557c0c6fb8199fc5aba0e0c95005">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo">ARMFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42aca0a2345c49cd96313d23761c915e">AFI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72802551596a33d2c23777777622bbb6">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38178ec34aae8177faa51ec6fcc3fa3c">isThumb</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ca62ffd88a506f49d21cbac3f02015">isThumb1</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7404870660d9bb7680f20e6a9d94313">isThumb2</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceff4ac3539f2c9850610445e7176758">isPositionIndependentOrROPI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4809f4638bc964aa757bd1b47fff3f2c">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands">ARMConstantIslands</a> - Due to limited PC-relative displacements, <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> requires constant pool entries to be scattered among the instructions inside a function.</p>


<p>To do this, it completely ignores the normal LLVM constant pool; instead, it places constants wherever it feels like with special instructions.</p>


<p>The terminology used in this pass includes: Islands - Clumps of constants placed in the function. Water - Potential places where an island could be formed. CPE - A constant pool entry that has been placed somewhere, which tracks a list of users.</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### water\_iterator {#a87abe235fd0b4caa9549a01f250b10d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::water_iterator =  std::vector&lt;MachineBasicBlock *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ARMConstantIslands() {#a6ab5453e9f3f4ed83c6bb9e4ebd68b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ARMConstantIslands ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<p>References <a href="#a4809f4638bc964aa757bd1b47fff3f2c">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab26ecc37dfb0700afd44f8648a34ab82">llvm::createARMConstantIslandPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a225e3a366286304012ebb04ca6aee82d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#aadaa10dcef3fe4481b60ff1fb9c34780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::getPassName ()</td>
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


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#af26b9cf82b47b3091a8d554edabaf714">ARM_CP_ISLANDS_OPT_NAME</a>.</p>

</div>
</div>

### getRequiredProperties() {#a8e87361befd343a840e87d2ef988269e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::getRequiredProperties ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### runOnMachineFunction() {#aaf4297850ccff6052205f45bc2ba2f87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#adc09bbb30c18788e0bc6ee68ad36a2e6">AdjustJumpTableBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#aa71d343a68eaa436458cd76f349f399a">AlignBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a15898f9a72ea6bb8b53d6695dac7f419">CPMaxIteration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a29e1a46e82adb0b55dc3fa6dd15c8984">llvm::ARMSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5b401e780c5eed0aca1cfbf44d36a545">llvm::MachineOperand::isCPI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#aac48e345c32279414b627382d349edd6">SynthesizeThumb1TBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### adjustJTTargetBlockForward() {#a5d6bc8ba7bb705dba758eb13c5c08408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * ARMConstantIslands::adjustJTTargetBlockForward (unsigned JTI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * JTBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### BBHasFallthrough() {#ab648cc5da37b64781455162df55dd006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::BBHasFallthrough (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BBHasFallthrough - Return true if the specified basic block can fallthrough into the block immediately after it.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### createNewWater() {#a9e4d3fe25445806bc4392836a75db579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::createNewWater (unsigned CPUserIndex, unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; NewMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createNewWater - No existing WaterList entry will work for CPUsers[CPUserIndex], so create a place to put the CPE.</p>


<p>The end of the block is used if in range, and the conditional branch munged so control flow is correct. Otherwise the block is split to create a hole with an unconditional branch around it. In either case NewMBB is set to a block following which the new island can be inserted (the WaterList is not adjusted).</p>


<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### decrementCPEReferenceCount() {#a1132d26053b7c6b6945d4d05957cca6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::decrementCPEReferenceCount (unsigned CPI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>decrementCPEReferenceCount - find the constant pool entry with index CPI and instruction CPEMI, and decrement its refcount.</p>


<p>If the refcount becomes 0 remove the entry and instruction. Returns true if we removed the entry, false if we didn't.</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### doInitialConstPlacement() {#a472523a060d0c5f613fdaf2edf880f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::doInitialConstPlacement (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CPEMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the initial placement of the regular constant pool entries.</p>


<p>To start with, we put them all at the end of the function.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### doInitialJumpTablePlacement() {#a0d08a0032243809d891261111e6c4747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::doInitialJumpTablePlacement (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CPEMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do initial placement of the jump tables.</p>


<p>Because Thumb2's TBB and TBH instructions can be made more efficient if the jump table immediately follows the instruction, it's best to place them immediately next to their jumps to begin with. In almost all cases they'll never be moved from that position.</p>


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### dumpBBs() {#a97f3dc8c8f9649142b128882c6d68554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ARMConstantIslands::dumpBBs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>print block size and offset information - debugging</p>

<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### findAvailableWater() {#a36a35b64e8ecf993c780868342ebc1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::findAvailableWater (CPUser &amp; U, unsigned UserOffset, water_iterator &amp; WaterIter, bool CloserWater)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findAvailableWater - Look for an existing entry in the WaterList in which we can place the CPE referenced from U so it's within range of U's MI.</p>


<p>Returns true if found, false if not. If it returns true, WaterIter is set to the WaterList entry. For Thumb, prefer water that will not introduce padding to water that will. To ensure that this pass terminates, the CPE location for a particular CPUser is only allowed to move to a lower address, so search backward from the end of the list and prefer the first water that is in range.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### findConstPoolEntry() {#a7a29aeb2c25d3927e53dbcdec7531fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantIslands::CPEntry * ARMConstantIslands::findConstPoolEntry (unsigned CPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findConstPoolEntry - Given the constpool index and CONSTPOOL_ENTRY MI, look up the corresponding CPEntry.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### findInRangeCPEntry() {#abf0be587caca37c8589d2a60c6e59f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ARMConstantIslands::findInRangeCPEntry (CPUser &amp; U, unsigned UserOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LookForCPEntryInRange - see if the currently referenced CPE is in range; if not, see if an in-range clone of the CPE is in range, and if so, change the data structures so the user references the clone.</p>


<p>Returns: 0 = no existing entry found 1 = entry found, and there were no code insertions or deletions 2 = entry found, and there were code insertions or deletions</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### fixupConditionalBr() {#a831aa146b4f1dccd62bcd565a6eaa80f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::fixupConditionalBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupConditionalBr - Fix up a conditional branch whose destination is too far away to fit in its displacement field.</p>


<p>It is converted to an inverse conditional branch + an unconditional branch to the destination.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### fixupImmediateBr() {#aa5daae5ba9c59db3b92c4311b5d37473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::fixupImmediateBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupImmediateBr - Fix up an immediate branch whose destination is too far away to fit in its displacement field.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### fixupUnconditionalBr() {#a1ecba595e94ff061660c8b22e8716f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::fixupUnconditionalBr (ImmBranch &amp; Br)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fixupUnconditionalBr - Fix up an unconditional branch whose destination is too far away to fit in its displacement field.</p>


<p>If the LR register has been spilled in the epilogue, then we can use BL to implement a far jump. Otherwise, add an intermediate branch instruction to a branch.</p>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### getCombinedIndex() {#ab524260c1fdfc45ca8c2b7ade897fafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMConstantIslands::getCombinedIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### getCPEAlign() {#a58eb0c9489392e69edfdab54bb9a2fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align ARMConstantIslands::getCPEAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getCPEAlign - Returns the required alignment of the constant pool entry represented by CPEMI.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### getUserOffset() {#af7146125ff6a881a6b19fab8690e0091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMConstantIslands::getUserOffset (CPUser &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getUserOffset - Compute the offset of U.MI as seen by the hardware displacement computation.</p>


<p>Update U.KnownAlignment to match its current basic block location.</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### handleConstantPoolUser() {#abdd480ce7b8dd317463fd4c3a73316fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::handleConstantPoolUser (unsigned CPUserIndex, bool CloserWater)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handleConstantPoolUser - Analyze the specified user, checking to see if it is out-of-range.</p>


<p>If so, pick up the constant pool value and move it some place in-range. Return true if we changed any addresses (thus must run another pass of branch lengthening), false otherwise.</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### initializeFunctionInfo() {#aed78d2699a9d157c7ad08ae78fc48e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::initializeFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CPEMIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>initializeFunctionInfo - Do the initial scan of the function, building up information about the sizes of each block, the location of all the water, and finding all of the constant pool users.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isCPEntryInRange() {#a015406c9be05ba875b6a6607a7b0d33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::isCPEntryInRange (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI, unsigned Disp, bool NegOk, bool DoDump=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isCPEntryInRange - Returns true if the distance between specific MI and specific ConstPool entry instruction can fit in MI's displacement field.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isOffsetInRange() {#a9276d20e7ad345d71593d7995720afae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::isOffsetInRange (unsigned UserOffset, unsigned TrialOffset, unsigned Disp, bool NegativeOK, bool IsSoImm=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isOffsetInRange() {#a98229bab8b53875bace6cdd43c0525fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::isOffsetInRange (unsigned UserOffset, unsigned TrialOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CPUser &amp; U)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isWaterInRange() {#a22a6249ea0ff228890a3b2e326f8fe71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::isWaterInRange (unsigned UserOffset, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Water, CPUser &amp; U, unsigned &amp; Growth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isWaterInRange - Returns true if a CPE placed after the specified Water (a basic block) will be in range for the specific MI.</p>


<p>Compute how much the function will grow by inserting a CPE after Water.</p>


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### optimizeThumb2Branches() {#a7dcb1f3b15c4c0e6501c2a28d78908cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::optimizeThumb2Branches ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### optimizeThumb2Instructions() {#a9beafe176b49d8fd46daab6faca8ef02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::optimizeThumb2Instructions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### optimizeThumb2JumpTables() {#abad3b14f15be6b5e8dc1b4826f119696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::optimizeThumb2JumpTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>optimizeThumb2JumpTables - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> tbb / tbh instructions to generate smaller jumptables when it's possible.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### preserveBaseRegister() {#a0e5a435a047ef3f277eec100c1ecf031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::preserveBaseRegister (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * JumpMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * LEAMI, unsigned &amp; DeadSize, bool &amp; CanDeleteLEA, bool &amp; BaseRegKill)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>While trying to form a TBB/TBH instruction, we may (if the table doesn't immediately follow the BR_JT) need access to the start of the jump-table.</p>


<p>We know one instruction that produces such a register; this function works out whether that definition can be preserved to the BR_JT, possibly by removing an intervening addition (which is usually needed to calculate the actual entry to jump to).</p>


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### removeDeadCPEMI() {#aa2fe1bbc38cd8de84461690fab233e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::removeDeadCPEMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CPEMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeDeadCPEMI - Remove a dead constant pool entry instruction.</p>


<p>Update sizes and offsets of impacted basic blocks.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### removeUnusedCPEntries() {#a8bda926b4776787d25d7b0a0112f0dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::removeUnusedCPEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeUnusedCPEntries - Remove constant pool entries whose refcounts are zero.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### reorderThumb2JumpTables() {#a44e9766216f49ba8b940fbb7c91abb78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantIslands::reorderThumb2JumpTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reorderThumb2JumpTables - Adjust the function's block layout to ensure that jump tables always branch forwards, since that's what tbb and tbh need.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### scanFunctionJumpTables() {#a4995445c7a400cc68dc2e59587e68b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::scanFunctionJumpTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>scanFunctionJumpTables - Do a scan of the function, building up information about the sizes of each block and the locations of all the jump tables.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### splitBlockBeforeInstr() {#a2d0ff01e9af545b83667a6f3b1a309a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * ARMConstantIslands::splitBlockBeforeInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split the basic block containing MI into two blocks, which are joined by an unconditional branch.</p>


<p>Update data structures and renumber blocks to account for this change and returns the newly created block.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### updateForInsertedWaterBlock() {#ae9ee57208388fce44d1de2773ba04f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::updateForInsertedWaterBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>updateForInsertedWaterBlock - When a block is newly inserted into the machine function, it upsets all of the block numbers.</p>


<p>Renumber the blocks and update the arrays that parallel this numbering.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### verify() {#afaf72e81e912fc9c1a2d7913ac48d670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantIslands::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>verify - check BBOffsets, BBSizes, alignment of islands</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AFI {#a42aca0a2345c49cd96313d23761c915e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMFunctionInfo* anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::AFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### BBUtils {#a9eb99cca93ab051541c42391046d9daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ARMBasicBlockUtils&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::BBUtils = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### BlockJumpTableRefCount {#a16ed371a9d5e8b194d6402fe0c699cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, int&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::BlockJumpTableRefCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### CPEntries {#a58a03308500573324cb3619b9e8f567d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;CPEntry&gt; &gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::CPEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CPEntries - Keep track of all of the constant pool entry machine instructions.</p>


<p>For each original constpool index (i.e. those that existed upon entry to this pass), it keeps a vector of entries. Original elements are cloned as we go along; the clones are put in the vector of the original element, but have distinct CPIs.</p>


<p>The first half of CPEntries contains generic constants, the second half contains jump tables. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getCombinedIndex on a generic CPEMI to look up which vector it will be in here.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### CPUsers {#a26d4c5e9c9ef1d2abbb92300b5be8c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CPUser&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::CPUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CPUsers - Keep track of all of the machine instructions that use various constant pools and their max displacement.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### DT {#a72802551596a33d2c23777777622bbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### ImmBranches {#abd3dee94f255a59ef39503608f99c8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ImmBranch&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ImmBranches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ImmBranches - Keep track of all the immediate branch instructions.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isPositionIndependentOrROPI {#aceff4ac3539f2c9850610445e7176758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::isPositionIndependentOrROPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isThumb {#a38178ec34aae8177faa51ec6fcc3fa3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::isThumb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isThumb1 {#ab5ca62ffd88a506f49d21cbac3f02015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::isThumb1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### isThumb2 {#aa7404870660d9bb7680f20e6a9d94313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::isThumb2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### JumpTableEntryIndices {#a28a2f6500d0e72e0bc875c66ab426533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;int, int&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::JumpTableEntryIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a JT index to the offset in CPEntries containing copies of that table.</p>


<p>The equivalent map for a CONSTPOOL_ENTRY is the identity.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### JumpTableUserIndices {#aae272594f35c002c85edb799023a3245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;int, int&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::JumpTableUserIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a JT index to the LEA that actually uses the index to calculate its base address.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MCP {#ab0dbb8974ac506fa487d4dde50a93a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineConstantPool* anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::MCP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MF {#a7514c1eca73b9986376c81388f147e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### NewWaterList {#a5bcaaefb0325dd55841218c2b401a430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;MachineBasicBlock*, 4&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::NewWaterList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NewWaterList - The subset of WaterList that was created since the previous iteration by inserting unconditional branches.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### PushPopMIs {#aff8d08e657e6ed9c0c3ca1b1c179ac2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 4&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::PushPopMIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PushPopMIs - Keep track of all the Thumb push / pop instructions.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### STI {#a17b3557c0c6fb8199fc5aba0e0c95005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget* anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### T2JumpTables {#ab52de6115c0eb43c179e676c824715ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 4&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::T2JumpTables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>T2JumpTables - Keep track of all the Thumb2 jumptable instructions.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### TII {#a3bcf2a90f5b140ee4022487e495223bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMBaseInstrInfo* anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### WaterList {#a610f64f4d5215f773f3604360c5c3639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineBasicBlock*&gt; anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::WaterList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WaterList - A sorted list of basic blocks where islands could be placed (i.e.</p>


<p>blocks that don't fall through to the following block, due to a return, unreachable, or unconditional branch).</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a4809f4638bc964aa757bd1b47fff3f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char ARMConstantIslands::ID = 0</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<p>Referenced by <a href="#a6ab5453e9f3f4ed83c6bb9e4ebd68b20">ARMConstantIslands</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
