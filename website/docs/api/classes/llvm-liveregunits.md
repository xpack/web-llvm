---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liveregunits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LiveRegUnits` Class Reference

<p>A set of register units used to track register liveness. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LiveRegUnits { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">llvm/CodeGen/LiveRegUnits.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dfc69c592334589ab1606b8e0a86d90">LiveRegUnits</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a new empty <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> set. <a href="#a8dfc69c592334589ab1606b8e0a86d90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eecad44f69f89053e0330df2808241d">LiveRegUnits</a> (const TargetRegisterInfo &amp;TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs and initialize an empty <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> set. <a href="#a0eecad44f69f89053e0330df2808241d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7fb90824f599580585b3b5c5116614">init</a> (const TargetRegisterInfo &amp;TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize and clear the set. <a href="#a5e7fb90824f599580585b3b5c5116614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7e9f52f2a85f51a9c8e8d5f54238343">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears the set. <a href="#af7e9f52f2a85f51a9c8e8d5f54238343">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2b068a5463737a98c35840d5e87aca">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the set is empty. <a href="#adb2b068a5463737a98c35840d5e87aca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2909dfae74e60e8dfd886b92e5a33e3">addReg</a> (MCPhysReg Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds register units covered by physical register <span class="doxyComputerOutput">Reg</span>. <a href="#ab2909dfae74e60e8dfd886b92e5a33e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380627231bd554718dbc1e28f8875c49">addRegMasked</a> (MCPhysReg Reg, LaneBitmask Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds register units covered by physical register <span class="doxyComputerOutput">Reg</span> that are part of the lanemask <span class="doxyComputerOutput">Mask</span>. <a href="#a380627231bd554718dbc1e28f8875c49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27497ce6068478bb97765620191e351">removeReg</a> (MCPhysReg Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all register units covered by physical register <span class="doxyComputerOutput">Reg</span>. <a href="#af27497ce6068478bb97765620191e351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef64448ecc992aafc1321df93a30a824">removeRegsNotPreserved</a> (const uint32_t *RegMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes register units not preserved by the regmask <span class="doxyComputerOutput">RegMask</span>. <a href="#aef64448ecc992aafc1321df93a30a824">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4798468cafe0ab51df84370b1f0e288e">addRegsInMask</a> (const uint32_t *RegMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds register units not preserved by the regmask <span class="doxyComputerOutput">RegMask</span>. <a href="#a4798468cafe0ab51df84370b1f0e288e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3996f7c3774880bfe32422602fe34f9c">available</a> (MCPhysReg Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if no part of physical register <span class="doxyComputerOutput">Reg</span> is live. <a href="#a3996f7c3774880bfe32422602fe34f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5fb273566c37fdc7da88a0fec5a554c">stepBackward</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates liveness when stepping backwards over the instruction <span class="doxyComputerOutput">MI</span>. <a href="#aa5fb273566c37fdc7da88a0fec5a554c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ea64c95b144306f76693d958be9741">accumulate</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds all register units used, defined or clobbered in <span class="doxyComputerOutput">MI</span>. <a href="#af7ea64c95b144306f76693d958be9741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4fff7ad3de452b1b1d20de5afd986a3">addLiveOuts</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds registers living out of block <span class="doxyComputerOutput">MBB</span>. <a href="#ab4fff7ad3de452b1b1d20de5afd986a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06ac34235924f41c0072e7f895b3605">addLiveIns</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds registers living into block <span class="doxyComputerOutput">MBB</span>. <a href="#ae06ac34235924f41c0072e7f895b3605">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab89af6f077b0b0cd502dd2262aec6407">addUnits</a> (const BitVector &amp;RegUnits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds all register units marked in the bitvector <span class="doxyComputerOutput">RegUnits</span>. <a href="#ab89af6f077b0b0cd502dd2262aec6407">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd16b0ae4b91830b3fa4f4f0d3de8cf">removeUnits</a> (const BitVector &amp;RegUnits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all register units marked in the bitvector <span class="doxyComputerOutput">RegUnits</span>. <a href="#aecd16b0ae4b91830b3fa4f4f0d3de8cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35334c438622cf1bf9b46e8a010c6506">getBitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the internal bitvector representation of the set. <a href="#a35334c438622cf1bf9b46e8a010c6506">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b68639feabfee1c94d16d3d6a105bd">addPristines</a> (const MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds pristine registers. <a href="#a98b68639feabfee1c94d16d3d6a105bd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf00c107583c19c459a70f349d8b3e7">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80d418ca4fda72b9f962dd2872873870">Units</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c3c14971a6414e21bf3a0a2652de0f">accumulateUsedDefed</a> (const MachineInstr &amp;MI, LiveRegUnits &amp;ModifiedRegUnits, LiveRegUnits &amp;UsedRegUnits, const TargetRegisterInfo *TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a machine instruction <span class="doxyComputerOutput">MI</span>, adds all register units used in <span class="doxyComputerOutput">UsedRegUnits</span> and defined or clobbered in <span class="doxyComputerOutput">ModifiedRegUnits</span>. <a href="#a06c3c14971a6414e21bf3a0a2652de0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A set of register units used to track register liveness.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveRegUnits() {#a8dfc69c592334589ab1606b8e0a86d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRegUnits::LiveRegUnits ()</td>
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

<p>Constructs a new empty <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> set.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Referenced by <a href="#a06c3c14971a6414e21bf3a0a2652de0f">accumulateUsedDefed</a>.</p>

</div>
</div>

### LiveRegUnits() {#a0eecad44f69f89053e0330df2808241d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRegUnits::LiveRegUnits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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

<p>Constructs and initialize an empty <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> set.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Reference <a href="#a5e7fb90824f599580585b3b5c5116614">init</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accumulate() {#af7ea64c95b144306f76693d958be9741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegUnits::accumulate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds all register units used, defined or clobbered in <span class="doxyComputerOutput">MI</span>.</p>


<p>This is useful when walking over a range of instruction to find registers unused over the whole range.</p>


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a>.</p>


<p>References <a href="#ab2909dfae74e60e8dfd886b92e5a33e3">addReg</a>, <a href="#a4798468cafe0ab51df84370b1f0e288e">addRegsInMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a435084f5e140c85f72921239385f9edb">canRenameUntilSecondLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aedba2e5f9aa7cb803611f295ad04b865">llvm::ARMBaseInstrInfo::isMBBSafeToOutlineFrom</a>.</p>

</div>
</div>

### addLiveIns() {#ae06ac34235924f41c0072e7f895b3605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegUnits::addLiveIns (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds registers living into block <span class="doxyComputerOutput">MBB</span>.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp/#a7bf7b112a802239baee4a71a848de0f1">addBlockLiveIns</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a948a039c4649894649702b931539b368">initLiveUnits</a>.</p>

</div>
</div>

### addLiveOuts() {#ab4fff7ad3de452b1b1d20de5afd986a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegUnits::addLiveOuts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds registers living out of block <span class="doxyComputerOutput">MBB</span>.</p>


<p>Live out registers are the union of the live-in registers of the successor blocks and pristine registers. Live out registers of the end block are the callee saved registers.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp/#a7bf7b112a802239baee4a71a848de0f1">addBlockLiveIns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp/#a9934551ee94fac64bda9c5a9452a3040">addCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a81504f733d0491a446a16ef1ba0a5c2a">llvm::MachineFrameInfo::isCalleeSavedInfoValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a9dec32763bff61fb024d352592596f99">expandSMEPPRToZPRSpillPseudos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a948a039c4649894649702b931539b368">initLiveUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aedba2e5f9aa7cb803611f295ad04b865">llvm::ARMBaseInstrInfo::isMBBSafeToOutlineFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ae97bb6b91cff3e18475ab68012287cc2">llvm::SystemZInstrInfo::prepareCompareSwapOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelimcompare-cpp-/systemzelimcompare/#adc7ada58edab4877f99340bad212ecbf">anonymous{SystemZElimCompare.cpp}::SystemZElimCompare::processBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>.</p>

</div>
</div>

### addReg() {#ab2909dfae74e60e8dfd886b92e5a33e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::addReg (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
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

<p>Adds register units covered by physical register <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#af7ea64c95b144306f76693d958be9741">accumulate</a>, <a href="#a06c3c14971a6414e21bf3a0a2652de0f">accumulateUsedDefed</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp/#a09c3edd4c226f6af4965320fa45f574d">addCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a4e6b353116922112b1b470ce15adb2fd">buildPrologSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a544e5e38d5032dd862ab44953c2c173b">buildScratchExecCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a0ad5cb616fdce8d90db0927dbdf0533c">llvm::SIFrameLowering::determinePrologEpilogSGPRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a84c4c1518f3593f9c1d0b10f8364ebb8">llvm::SIFrameLowering::emitCSRSpillStores</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ace1de8acc8ac15962f04832273df87b1">llvm::SIFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#ab3ccfafbeec394fdd258288cec644ce9">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a233876a8dfa07f6566cbaa28f64d6e6f">getVGPRSpillLaneOrTempRegister</a>, <a href="#aa5fb273566c37fdc7da88a0fec5a554c">stepBackward</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a16297e722f8be82ffae1552bde33d061">toggleKills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a3254ec0c900f8e69d67ae32be83e801b">tryToFindRegisterToRename</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af5fcd8a3114504b21e5f08a08e4fa512">updateDefinedRegisters</a>.</p>

</div>
</div>

### addRegMasked() {#a380627231bd554718dbc1e28f8875c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::addRegMasked (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> Mask)</td>
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

<p>Adds register units covered by physical register <span class="doxyComputerOutput">Reg</span> that are part of the lanemask <span class="doxyComputerOutput">Mask</span>.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp/#a7bf7b112a802239baee4a71a848de0f1">addBlockLiveIns</a>.</p>

</div>
</div>

### addRegsInMask() {#a4798468cafe0ab51df84370b1f0e288e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegUnits::addRegsInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * RegMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds register units not preserved by the regmask <span class="doxyComputerOutput">RegMask</span>.</p>


<p>The regmask has the same format as the one in the RegMask machine operand.</p>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregunitrootiterator/#abd29ecab24058fdf823addcad29c6939">llvm::MCRegUnitRootIterator::isValid</a>.</p>


<p>Referenced by <a href="#af7ea64c95b144306f76693d958be9741">accumulate</a> and <a href="#a06c3c14971a6414e21bf3a0a2652de0f">accumulateUsedDefed</a>.</p>

</div>
</div>

### addUnits() {#ab89af6f077b0b0cd502dd2262aec6407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::addUnits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RegUnits)</td>
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

<p>Adds all register units marked in the bitvector <span class="doxyComputerOutput">RegUnits</span>.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>

</div>
</div>

### available() {#a3996f7c3774880bfe32422602fe34f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRegUnits::available (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
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

<p>Returns true if no part of physical register <span class="doxyComputerOutput">Reg</span> is live.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a084d504a7f8b42657e1c910ba098ad94">clearKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#ab3ccfafbeec394fdd258288cec644ce9">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a989e26280ba069ba20dd83144c3bd31a">findSurvivorBackwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#afb31367a4e0005968619f3418c0a03e1">findTemporariesForLR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#aba0076206670f37e37855c8421061a3c">findUnusedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aedba2e5f9aa7cb803611f295ad04b865">llvm::ARMBaseInstrInfo::isMBBSafeToOutlineFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ae97bb6b91cff3e18475ab68012287cc2">llvm::SystemZInstrInfo::prepareCompareSwapOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelimcompare-cpp-/systemzelimcompare/#adc7ada58edab4877f99340bad212ecbf">anonymous{SystemZElimCompare.cpp}::SystemZElimCompare::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a16297e722f8be82ffae1552bde33d061">toggleKills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0db542f5acb6d354f4c775a2279e2350">tryScavengeRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a3254ec0c900f8e69d67ae32be83e801b">tryToFindRegisterToRename</a>.</p>

</div>
</div>

### clear() {#af7e9f52f2a85f51a9c8e8d5f54238343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::clear ()</td>
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

<p>Clears the set.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>

</div>
</div>

### empty() {#adb2b068a5463737a98c35840d5e87aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRegUnits::empty ()</td>
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

<p>Returns true if the set is empty.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a84c4c1518f3593f9c1d0b10f8364ebb8">llvm::SIFrameLowering::emitCSRSpillStores</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a948a039c4649894649702b931539b368">initLiveUnits</a>.</p>

</div>
</div>

### getBitVector() {#a35334c438622cf1bf9b46e8a010c6506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::LiveRegUnits::getBitVector ()</td>
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

<p>Return the internal bitvector representation of the set.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>

</div>
</div>

### init() {#a5e7fb90824f599580585b3b5c5116614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::init (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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

<p>Initialize and clear the set.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a0ad5cb616fdce8d90db0927dbdf0533c">llvm::SIFrameLowering::determinePrologEpilogSGPRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a948a039c4649894649702b931539b368">initLiveUnits</a> and <a href="#a0eecad44f69f89053e0330df2808241d">LiveRegUnits</a>.</p>

</div>
</div>

### removeReg() {#af27497ce6068478bb97765620191e351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::removeReg (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
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

<p>Removes all register units covered by physical register <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a4e6b353116922112b1b470ce15adb2fd">buildPrologSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="#aa5fb273566c37fdc7da88a0fec5a554c">stepBackward</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af5fcd8a3114504b21e5f08a08e4fa512">updateDefinedRegisters</a>.</p>

</div>
</div>

### removeRegsNotPreserved() {#aef64448ecc992aafc1321df93a30a824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegUnits::removeRegsNotPreserved (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * RegMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes register units not preserved by the regmask <span class="doxyComputerOutput">RegMask</span>.</p>


<p>The regmask has the same format as the one in the RegMask machine operand.</p>


<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregunitrootiterator/#abd29ecab24058fdf823addcad29c6939">llvm::MCRegUnitRootIterator::isValid</a>.</p>


<p>Referenced by <a href="#aa5fb273566c37fdc7da88a0fec5a554c">stepBackward</a>.</p>

</div>
</div>

### removeUnits() {#aecd16b0ae4b91830b3fa4f4f0d3de8cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::removeUnits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RegUnits)</td>
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

<p>Removes all register units marked in the bitvector <span class="doxyComputerOutput">RegUnits</span>.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>

</div>
</div>

### stepBackward() {#aa5fb273566c37fdc7da88a0fec5a554c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegUnits::stepBackward (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates liveness when stepping backwards over the instruction <span class="doxyComputerOutput">MI</span>.</p>


<p>This removes all register units defined or clobbered in <span class="doxyComputerOutput">MI</span> and then adds the units used (as in use operands) in <span class="doxyComputerOutput">MI</span>.</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a>.</p>


<p>References <a href="#ab2909dfae74e60e8dfd886b92e5a33e3">addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#af27497ce6068478bb97765620191e351">removeReg</a> and <a href="#aef64448ecc992aafc1321df93a30a824">removeRegsNotPreserved</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a9dec32763bff61fb024d352592596f99">expandSMEPPRToZPRSpillPseudos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a948a039c4649894649702b931539b368">initLiveUnits</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addPristines() {#a98b68639feabfee1c94d16d3d6a105bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegUnits::addPristines (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds pristine registers.</p>


<p>Pristine registers are callee saved registers that are unused in the function.</p>


<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TRI {#a3bf00c107583c19c459a70f349d8b3e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::LiveRegUnits::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>

</div>
</div>

### Units {#a80d418ca4fda72b9f962dd2872873870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::LiveRegUnits::Units</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### accumulateUsedDefed() {#a06c3c14971a6414e21bf3a0a2652de0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegUnits::accumulateUsedDefed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> &amp; ModifiedRegUnits, <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> &amp; UsedRegUnits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a machine instruction <span class="doxyComputerOutput">MI</span>, adds all register units used in <span class="doxyComputerOutput">UsedRegUnits</span> and defined or clobbered in <span class="doxyComputerOutput">ModifiedRegUnits</span>.</p>


<p>This is useful when walking over a range of instructions to track registers used or defined separately.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a>.</p>


<p>References <a href="#ab2909dfae74e60e8dfd886b92e5a33e3">addReg</a>, <a href="#a4798468cafe0ab51df84370b1f0e288e">addRegsInMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8dfc69c592334589ab1606b8e0a86d90">LiveRegUnits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#ac6bfa516458b5082ed19852b929836f1">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::adjustRetVal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a9b60466dac10eaf9d8a8b4f955b77b24">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingConstOffsetBackward</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#a2c18d64812a6868d590fb3f27d938312">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::findMatchingInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b4a3c0105d0c1835725eaa33867b526">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a4ffd0a0399bead8c2759b5487ea997c6">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnBackward</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#afa5ee2f4a09f62ebe217673407877974">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnForward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64redundantcopyelimination-cpp/#af884214031cdb18344d85b5d4c422fef">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">LiveRegUnits.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp">LiveRegUnits.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
