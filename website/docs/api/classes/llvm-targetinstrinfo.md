---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetinstrinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TargetInstrInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> - Interface to description of machine instruction set. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetInstrInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to description of machine instruction set. <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ea1fe6f61d0e861ed2be7632a270bb">TargetInstrInfo</a> (unsigned CFSetupOpcode=~0u, unsigned CFDestroyOpcode=~0u, unsigned CatchRetOpcode=~0u, unsigned ReturnOpcode=~0u)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc72b67ab4a799ac5472bb3ca3250fc">TargetInstrInfo</a> (const TargetInstrInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c402f5f405a15e3356949d3d1900c3">~TargetInstrInfo</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b4dd0611f4e9b708e1940a945581e9">operator=</a> (const TargetInstrInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81ceec76ff4ca95f29b037c28a54ba7">getRegClass</a> (const MCInstrDesc &amp;MCID, unsigned OpNum, const TargetRegisterInfo *TRI, const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a machine instruction descriptor, returns the register class constraint for OpNum, or NULL. <a href="#af81ceec76ff4ca95f29b037c28a54ba7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae46a80302699b257d06337de4b804a17">isGlobalMemoryObject</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if MI is an instruction we are unable to reason about (like a call or something with unmodeled side effects). <a href="#ae46a80302699b257d06337de4b804a17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d142d4718ca758481e0b49ad9d8ea97">isTriviallyReMaterializable</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is trivially rematerializable, meaning it has no side effects and requires no operands that aren't always available. <a href="#a1d142d4718ca758481e0b49ad9d8ea97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6832cbbc9c9e128eed4484026c539781">isIgnorableUse</a> (const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given <span class="doxyComputerOutput">MO</span> is a PhysReg use return if it can be ignored for the purpose of instruction rematerialization or sinking. <a href="#a6832cbbc9c9e128eed4484026c539781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104cb332d459987fabfe9d7073150287">isSafeToSink</a> (MachineInstr &amp;MI, MachineBasicBlock *SuccToSinkTo, MachineCycleInfo *CI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8e648b771ac836d613da033447a78b">shouldBreakCriticalEdgeToSink</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a "cheap" instruction which doesn't enable additional sinking, should MachineSink break a critical edge to sink it anyways? <a href="#a5f8e648b771ac836d613da033447a78b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83870b05e73f275887a1e20baa621475">getCallFrameSetupOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These methods return the opcode of the frame setup/destroy instructions if they exist (-1 otherwise). <a href="#a83870b05e73f275887a1e20baa621475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a18bb895aa0c46d5de27c4ad046aee">getCallFrameDestroyOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a524001439888743cdddb9b79c45911d9">isFrameInstr</a> (const MachineInstr &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the argument is a frame pseudo instruction. <a href="#a524001439888743cdddb9b79c45911d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9cc48fa5e52de97bef32acbb6f76ddc">isFrameSetup</a> (const MachineInstr &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the argument is a frame setup pseudo instruction. <a href="#ac9cc48fa5e52de97bef32acbb6f76ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c5ed9e614110e7cbdd8a4ab957ec06">getFrameSize</a> (const MachineInstr &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of the frame associated with the given frame instruction. <a href="#ab5c5ed9e614110e7cbdd8a4ab957ec06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b59f9d1912a25fc5c03ae9b2ff960d">getFrameTotalSize</a> (const MachineInstr &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the total frame size, which is made up of the space set up inside the pair of frame start-stop instructions and the space that is set up prior to the pair. <a href="#aa0b59f9d1912a25fc5c03ae9b2ff960d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a831626be0c6e512d6d95246891c84">getCatchReturnOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6150cd07e9535b7e02d53953a1a54cdb">getReturnOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4f8b28a8543924e7e3e566a847e691">getSPAdjust</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the actual stack pointer adjustment made by an instruction as part of a call sequence. <a href="#a1e4f8b28a8543924e7e3e566a847e691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236fc00ef404f232dcd8b88bbf3a2251">isCoalescableExtInstr</a> (const MachineInstr &amp;MI, Register &amp;SrcReg, Register &amp;DstReg, unsigned &amp;SubIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a "coalescable" extension instruction. <a href="#a236fc00ef404f232dcd8b88bbf3a2251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6922ec50633977be02ab221c2de2adc1">isLoadFromStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified machine instruction is a direct load from a stack slot, return the virtual or physical register number of the destination along with the FrameIndex of the loaded stack slot. <a href="#a6922ec50633977be02ab221c2de2adc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb62c4d3c76506ef7a31dc75f98000db">isLoadFromStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex, unsigned &amp;MemBytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional extension of isLoadFromStackSlot that returns the number of bytes loaded from the stack. <a href="#afb62c4d3c76506ef7a31dc75f98000db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dad862e186c4263edb6f7583754efcc">isLoadFromStackSlotPostFE</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for post-frame ptr elimination stack locations as well. <a href="#a8dad862e186c4263edb6f7583754efcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c237cad94f54f0d82a18a131709d41">hasLoadFromStackSlot</a> (const MachineInstr &amp;MI, SmallVectorImpl&lt; const MachineMemOperand * &gt; &amp;Accesses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified machine instruction has a load from a stack slot, return true along with the FrameIndices of the loaded stack slot and the machine mem operands containing the reference. <a href="#ae3c237cad94f54f0d82a18a131709d41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa095ffe13f7029e833f37e346f5fa5b0">isStoreToStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified machine instruction is a direct store to a stack slot, return the virtual or physical register number of the source reg along with the FrameIndex of the loaded stack slot. <a href="#aa095ffe13f7029e833f37e346f5fa5b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a5b1227d7622151c06029e84d67ade">isStoreToStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex, unsigned &amp;MemBytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional extension of isStoreToStackSlot that returns the number of bytes stored to the stack. <a href="#af4a5b1227d7622151c06029e84d67ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4598ec7bb2753593259420bff01427">isStoreToStackSlotPostFE</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for post-frame ptr elimination stack locations as well. <a href="#a8d4598ec7bb2753593259420bff01427">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df2834716ee814af9f2555897ecb932">hasStoreToStackSlot</a> (const MachineInstr &amp;MI, SmallVectorImpl&lt; const MachineMemOperand * &gt; &amp;Accesses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified machine instruction has a store to a stack slot, return true along with the FrameIndices of the loaded stack slot and the machine mem operands containing the reference. <a href="#a5df2834716ee814af9f2555897ecb932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51770f677efd652c55498dc472bec14">isStackSlotCopy</a> (const MachineInstr &amp;MI, int &amp;DestFrameIndex, int &amp;SrcFrameIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified machine instruction is a copy of one stack slot to another and has no other effect. <a href="#aa51770f677efd652c55498dc472bec14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cf58df95b00905950bdfee515cd5e9d">getStackSlotRange</a> (const TargetRegisterClass *RC, unsigned SubIdx, unsigned &amp;Size, unsigned &amp;Offset, const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the size in bytes and offset within a stack slot of a spilled register or subregister. <a href="#a5cf58df95b00905950bdfee515cd5e9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bdf5a92f1195b3543b9412758c58106">isUnspillableTerminator</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given instruction is terminator that is unspillable, according to isUnspillableTerminatorImpl. <a href="#a4bdf5a92f1195b3543b9412758c58106">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c95e145de31fbd3c6269ebe1b615f7">getInstSizeInBytes</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size in bytes of the specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, or ~0U when this function is not implemented by a target. <a href="#ad5c95e145de31fbd3c6269ebe1b615f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5e9ccab2a323465af64b3661172af2">isAsCheapAsAMove</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is as cheap as a move instruction. <a href="#a9c5e9ccab2a323465af64b3661172af2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b2151fcd1d9e2cec1689aec6e5ed8a">shouldSink</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction should be sunk by MachineSink. <a href="#ad9b2151fcd1d9e2cec1689aec6e5ed8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc848c0953b9a49b09c0ef3a577a34f">shouldHoist</a> (const MachineInstr &amp;MI, const MachineLoop *FromLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return false if the instruction should not be hoisted by MachineLICM. <a href="#aefc848c0953b9a49b09c0ef3a577a34f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadcfe8906a95ad57f3f7a7d433f47204">reMaterialize</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register DestReg, unsigned SubIdx, const MachineInstr &amp;Orig, const TargetRegisterInfo &amp;TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Re-issue the specified 'original' instruction at the specific location targeting a new destination register. <a href="#aadcfe8906a95ad57f3f7a7d433f47204">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5210bd68a86582390a6fbf1f57e319">duplicate</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertBefore, const MachineInstr &amp;Orig) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clones instruction or the whole instruction bundle <span class="doxyComputerOutput">Orig</span> and insert into <span class="doxyComputerOutput">MBB</span> before <span class="doxyComputerOutput">InsertBefore</span>. <a href="#a8d5210bd68a86582390a6fbf1f57e319">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0a8cb9a764d058a63b77d50e9c0787">convertToThreeAddress</a> (MachineInstr &amp;MI, LiveVariables *LV, LiveIntervals *LIS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method must be implemented by targets that set the M_CONVERTIBLE_TO_3_ADDR flag. <a href="#ada0a8cb9a764d058a63b77d50e9c0787">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41720cc33b0511709c92abcb164a59d">commuteInstruction</a> (MachineInstr &amp;MI, bool NewMI=false, unsigned OpIdx1=CommuteAnyOperandIndex, unsigned OpIdx2=CommuteAnyOperandIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method commutes the operands of the given machine instruction MI. <a href="#aa41720cc33b0511709c92abcb164a59d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422b844cc7e3db360908c008cb651f96">findCommutedOpIndices</a> (const MachineInstr &amp;MI, unsigned &amp;SrcOpIdx1, unsigned &amp;SrcOpIdx2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the routine could find two commutable operands in the given machine instruction. <a href="#a422b844cc7e3db360908c008cb651f96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae698a81cf1a8b23582f2964f57581dc2">hasCommutePreference</a> (MachineInstr &amp;MI, bool &amp;Commute) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target has a preference on the operands order of the given machine instruction. <a href="#ae698a81cf1a8b23582f2964f57581dc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae26cac7943070f09b4d7fa667d1adf95">getRegSequenceInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, SmallVectorImpl&lt; RegSubRegPairAndIdx &gt; &amp;InputRegs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the equivalent inputs of a REG_SEQUENCE for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>. <a href="#ae26cac7943070f09b4d7fa667d1adf95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1743a67877bf4ba56d53b235d3573e0">getExtractSubregInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, RegSubRegPairAndIdx &amp;InputReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the equivalent inputs of a EXTRACT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>. <a href="#af1743a67877bf4ba56d53b235d3573e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea536f043de7994bc9b67c634a7c879">getInsertSubregInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, RegSubRegPair &amp;BaseReg, RegSubRegPairAndIdx &amp;InsertedReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the equivalent inputs of a INSERT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>. <a href="#abea536f043de7994bc9b67c634a7c879">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66abaa28810e0bb35ab77012a3ea997">produceSameValue</a> (const MachineInstr &amp;MI0, const MachineInstr &amp;MI1, const MachineRegisterInfo *MRI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if two machine instructions would produce identical values. <a href="#ac66abaa28810e0bb35ab77012a3ea997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6073542a939859dd8831f4cf9d710393">isBranchOffsetInRange</a> (unsigned BranchOpc, int64_t BrOffset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ab946af55bc208ded5c21c11ff71c2">getBranchDestBlock</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b07e0819e160f78c33a67838dea35c">insertIndirectBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock &amp;NewDestBB, MachineBasicBlock &amp;RestoreBB, const DebugLoc &amp;DL, int64_t BrOffset=0, RegScavenger *RS=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unconditional indirect branch at the end of <span class="doxyComputerOutput">MBB</span> to <span class="doxyComputerOutput">NewDestBB</span>. <a href="#a25b07e0819e160f78c33a67838dea35c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dfb0c744373d4b6112eb343a5b07fc7">analyzeBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *&amp;TBB, MachineBasicBlock *&amp;FBB, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, bool AllowModify=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the branching code at the end of MBB, returning true if it cannot be understood (e.g. <a href="#a0dfb0c744373d4b6112eb343a5b07fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b3f813a206819029043906eedccc502">analyzeBranchPredicate</a> (MachineBasicBlock &amp;MBB, MachineBranchPredicate &amp;MBP, bool AllowModify=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the branching code at the end of MBB and parse it into the <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/machinebranchpredicate">MachineBranchPredicate</a> structure if possible. <a href="#a2b3f813a206819029043906eedccc502">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0317b8d1d0eb9aaf9af9d636f5f66e8d">removeBranch</a> (MachineBasicBlock &amp;MBB, int *BytesRemoved=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the branching code at the end of the specific MBB. <a href="#a0317b8d1d0eb9aaf9af9d636f5f66e8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762db1f75e789783b689f22cda71bad4">insertBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *TBB, MachineBasicBlock *FBB, ArrayRef&lt; MachineOperand &gt; Cond, const DebugLoc &amp;DL, int *BytesAdded=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert branch code into the end of the specified <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#a762db1f75e789783b689f22cda71bad4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af382bec94f69d7c5fba1e67e62e6e6da">insertUnconditionalBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *DestBB, const DebugLoc &amp;DL, int *BytesAdded=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo">PipelinerLoopInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047bd8fdcc19cf2047e947ca565ff8fc">analyzeLoopForPipelining</a> (MachineBasicBlock *LoopBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze loop L, which must be a single-basic-block loop, and if the conditions can be understood enough produce a <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo">PipelinerLoopInfo</a> object. <a href="#a047bd8fdcc19cf2047e947ca565ff8fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951ed5729e865521d99c1b7bf2e4e4a2">analyzeLoop</a> (MachineLoop &amp;L, MachineInstr *&amp;IndVarInst, MachineInstr *&amp;CmpInst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the loop code, return true if it cannot be understood. <a href="#a951ed5729e865521d99c1b7bf2e4e4a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18927162b9131e79e1ee778c7ae4a4e2">reduceLoopCount</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock &amp;PreHeader, MachineInstr *IndVar, MachineInstr &amp;Cmp, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, SmallVectorImpl&lt; MachineInstr * &gt; &amp;PrevInsts, unsigned Iter, unsigned MaxIter) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate code to reduce the loop iteration by one and check if the loop is finished. <a href="#a18927162b9131e79e1ee778c7ae4a4e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26e9655e762686aff18772a15139df27">ReplaceTailWithBranchTo</a> (MachineBasicBlock::iterator Tail, MachineBasicBlock *NewDest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the instruction OldInst and everything after it, replacing it with an unconditional branch to NewDest. <a href="#a26e9655e762686aff18772a15139df27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8e907121203db549a15f70f615ef50">isLegalToSplitMBBAt</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's legal to split the given basic block at the specified instruction (i.e. <a href="#afa8e907121203db549a15f70f615ef50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b5a36b4d498deae0da42cab63b6b65">isProfitableToIfCvt</a> (MachineBasicBlock &amp;MBB, unsigned NumCycles, unsigned ExtraPredCycles, BranchProbability Probability) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's profitable to predicate instructions with accumulated instruction latency of "NumCycles" of the specified basic block, where the probability of the instructions being executed is given by Probability, and Confidence is a measure of our confidence that it will be properly predicted. <a href="#a00b5a36b4d498deae0da42cab63b6b65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558a9e2bb84251c5a3dc6fbc2abf6b62">isProfitableToIfCvt</a> (MachineBasicBlock &amp;TMBB, unsigned NumTCycles, unsigned ExtraTCycles, MachineBasicBlock &amp;FMBB, unsigned NumFCycles, unsigned ExtraFCycles, BranchProbability Probability) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Second variant of isProfitableToIfCvt. <a href="#a558a9e2bb84251c5a3dc6fbc2abf6b62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5db14e4eee47b5fb139bf333d7f1516">isProfitableToDupForIfCvt</a> (MachineBasicBlock &amp;MBB, unsigned NumCycles, BranchProbability Probability) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's profitable for if-converter to duplicate instructions of specified accumulated instruction latencies in the specified MBB to enable if-conversion. <a href="#ad5db14e4eee47b5fb139bf333d7f1516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1d5ead030ed9216dedce5a9cc304ec">extraSizeToPredicateInstructions</a> (const MachineFunction &amp;MF, unsigned NumInsts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the increase in code size needed to predicate a contiguous run of NumInsts instructions. <a href="#acc1d5ead030ed9216dedce5a9cc304ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0eb74bb20ce93168ed6fc663d997c30">predictBranchSizeForIfCvt</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an estimate for the code size reduction (in bytes) which will be caused by removing the given branch instruction during if-conversion. <a href="#ac0eb74bb20ce93168ed6fc663d997c30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c46c756d842143ad24a09a2723be290">isProfitableToUnpredicate</a> (MachineBasicBlock &amp;TMBB, MachineBasicBlock &amp;FMBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's profitable to unpredicate one side of a 'diamond', i.e. <a href="#a4c46c756d842143ad24a09a2723be290">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0990ac346653cb1c820f391ffbf5ed5">canInsertSelect</a> (const MachineBasicBlock &amp;MBB, ArrayRef&lt; MachineOperand &gt; Cond, Register DstReg, Register TrueReg, Register FalseReg, int &amp;CondCycles, int &amp;TrueCycles, int &amp;FalseCycles) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is possible to insert a select instruction that chooses between TrueReg and FalseReg based on the condition code in Cond. <a href="#ae0990ac346653cb1c820f391ffbf5ed5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57cd943142f3f93cebdab2134714793b">insertSelect</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register DstReg, ArrayRef&lt; MachineOperand &gt; Cond, Register TrueReg, Register FalseReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a select instruction into MBB before I that will copy TrueReg to DstReg when Cond is true, and FalseReg to DstReg when Cond is false. <a href="#a57cd943142f3f93cebdab2134714793b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e13c52b664b67847a458ba5e6f9009">analyzeSelect</a> (const MachineInstr &amp;MI, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, unsigned &amp;TrueOp, unsigned &amp;FalseOp, bool &amp;Optimizable) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the given select instruction, returning true if it cannot be understood. <a href="#ad0e13c52b664b67847a458ba5e6f9009">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b099a7de1dfef1561ec6f7df09da47">optimizeSelect</a> (MachineInstr &amp;MI, SmallPtrSetImpl&lt; MachineInstr * &gt; &amp;NewMIs, bool PreferFalse=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a select instruction that was understood by analyzeSelect and returned Optimizable = true, attempt to optimize MI by merging it with one of its operands. <a href="#a31b099a7de1dfef1561ec6f7df09da47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61db491bd5855c30926453db6401958">copyPhysReg</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, const DebugLoc &amp;DL, MCRegister DestReg, MCRegister SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit instructions to copy a pair of physical registers. <a href="#ad61db491bd5855c30926453db6401958">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaccc261e5cc19c2d41a1ab9fb361cde8">isPCRelRegisterOperandLegal</a> (const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow targets to tell MachineVerifier whether a specific register <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> can be used as part of PC-relative addressing. <a href="#aaccc261e5cc19c2d41a1ab9fb361cde8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67b6d0847ff336198e7b56ecf022a3a">getJumpTableIndex</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an index for <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo">MachineJumpTableInfo</a> if <span class="doxyComputerOutput">insn</span> is an indirect jump using a jump table, otherwise -1. <a href="#aa67b6d0847ff336198e7b56ecf022a3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5bb5eb8d13b5726f90e7f38df45d60">isCopyInstr</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specific machine instruction is a instruction that moves/copies value from one register to another register return destination and source registers as machine operands. <a href="#ace5bb5eb8d13b5726f90e7f38df45d60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82dd4c26bf1be527376323f5c9889fbd">isCopyLikeInstr</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407338aee0ea958defdef5cb3993f1da">isFullCopyInstr</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/regimmpair">RegImmPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ac5c3f21740cf8f3f63e50de016209">isAddImmediate</a> (const MachineInstr &amp;MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specific machine instruction is an instruction that adds an immediate value and a register, and stores the result in the given register <span class="doxyComputerOutput">Reg</span>, return a pair of the source register and the offset which has been added. <a href="#ae4ac5c3f21740cf8f3f63e50de016209">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820eea71d5b67cf63757e49e3c55736d">getConstValDefinedInReg</a> (const MachineInstr &amp;MI, const Register Reg, int64_t &amp;ImmVal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if MI is an instruction that defines Reg to have a constant value and the value is recorded in ImmVal. <a href="#a820eea71d5b67cf63757e49e3c55736d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3df2a0837fb3b75b9a0ac8f0923843">storeRegToStackSlot</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register SrcReg, bool isKill, int FrameIndex, const TargetRegisterClass *RC, const TargetRegisterInfo *TRI, Register VReg, MachineInstr::MIFlag Flags=MachineInstr::NoFlags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store the specified register of the given register class to the specified stack frame index. <a href="#a6d3df2a0837fb3b75b9a0ac8f0923843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1710394413e85110e485ec260c6a91">loadRegFromStackSlot</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register DestReg, int FrameIndex, const TargetRegisterClass *RC, const TargetRegisterInfo *TRI, Register VReg, MachineInstr::MIFlag Flags=MachineInstr::NoFlags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load the specified register of the given register class from the specified stack frame index. <a href="#a9b1710394413e85110e485ec260c6a91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeb52dce7ed6b6e3abc562031782d77d">expandPostRAPseudo</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is called for all pseudo instructions that remain after register allocation. <a href="#aeeb52dce7ed6b6e3abc562031782d77d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838a9048864ddaea932c974de0e8ce1a">isSubregFoldable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the target can fold a load that feeds a subreg operand (or a subreg operand that feeds a store). <a href="#a838a9048864ddaea932c974de0e8ce1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a028c45f323009b51ef27c5f5814a2">getPatchpointUnfoldableRange</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a patchpoint, stackmap, or statepoint intrinsic, return the range of operands which can't be folded into stack references. <a href="#a34a028c45f323009b51ef27c5f5814a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a733ae5364b0de2225af33223f383a5">foldMemoryOperand</a> (MachineInstr &amp;MI, ArrayRef&lt; unsigned &gt; Ops, int FI, LiveIntervals *LIS=nullptr, VirtRegMap *VRM=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to fold a load or store of the specified stack slot into the specified machine instruction for the specified operand(s). <a href="#a6a733ae5364b0de2225af33223f383a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2432d0bb09d9fe3b6bb004d8dbf77a99">foldMemoryOperand</a> (MachineInstr &amp;MI, ArrayRef&lt; unsigned &gt; Ops, MachineInstr &amp;LoadMI, LiveIntervals *LIS=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as the previous version except it allows folding of any load and store from / to any address, not just from a specific stack slot. <a href="#a2432d0bb09d9fe3b6bb004d8dbf77a99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68b7b9c491045c788173e83be1ba5d2b">lowerCopy</a> (MachineInstr *MI, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function defines the logic to lower COPY instruction to target specific instruction(s). <a href="#a68b7b9c491045c788173e83be1ba5d2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a861381cad67866e249c6330631ac0742">getMachineCombinerPatterns</a> (MachineInstr &amp;Root, SmallVectorImpl&lt; unsigned &gt; &amp;Patterns, bool DoRegPressureReduce) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when there is potentially a faster code sequence for an instruction chain ending in <span class="doxyComputerOutput">Root</span>. <a href="#a861381cad67866e249c6330631ac0742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8cfc1d0bd78872b33f4669f9a18927">shouldReduceRegisterPressure</a> (const MachineBasicBlock *MBB, const RegisterClassInfo *RegClassInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if target supports reassociation of instructions in machine combiner pass to reduce register pressure for a given BB. <a href="#a3b8cfc1d0bd78872b33f4669f9a18927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494876c94cb3dba51694356488a996dd">finalizeInsInstrs</a> (MachineInstr &amp;Root, unsigned &amp;Pattern, SmallVectorImpl&lt; MachineInstr * &gt; &amp;InsInstrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix up the placeholder we may add in <a href="#a6875e5a149ffdf299b10e8f969d379d4">genAlternativeCodeSequence()</a>. <a href="#a494876c94cb3dba51694356488a996dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321a2b25fab981c6d834e3d0df610921">isThroughputPattern</a> (unsigned Pattern) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when a code sequence can improve throughput. <a href="#a321a2b25fab981c6d834e3d0df610921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a878ef42ed9660dc3a739a37e056f845d">CombinerObjective</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf4712d0ec5fc344aa14efa9e5392b2">getCombinerObjective</a> (unsigned Pattern) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the objective of a combiner pattern. <a href="#adcf4712d0ec5fc344aa14efa9e5392b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9f804c4f1407df72588bb00db16deb">isReassociationCandidate</a> (const MachineInstr &amp;Inst, bool &amp;Commuted) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the input \P Inst is part of a chain of dependent ops that are suitable for reassociation, otherwise return false. <a href="#ace9f804c4f1407df72588bb00db16deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa792b566fb2d8e29af95aea690e33201">isAssociativeAndCommutative</a> (const MachineInstr &amp;Inst, bool Invert=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when \P Inst is both associative and commutative. <a href="#aa792b566fb2d8e29af95aea690e33201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0568ec903d0544ec11e0fb013d2fbe2">getInverseOpcode</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the inverse operation opcode if it exists for \P Opcode (e.g. <a href="#ab0568ec903d0544ec11e0fb013d2fbe2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e545675db8b534aec8eccb7bedb2ee">areOpcodesEqualOrInverse</a> (unsigned Opcode1, unsigned Opcode2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when \P Opcode1 or its inversion is equal to \P Opcode2. <a href="#a29e545675db8b534aec8eccb7bedb2ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6034cfb230c4698caa60bdc3a9bf209b">hasReassociableOperands</a> (const MachineInstr &amp;Inst, const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when \P Inst has reassociable operands in the same \P MBB. <a href="#a6034cfb230c4698caa60bdc3a9bf209b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea784a4f9e9aba7792c23484e2498e8d">hasReassociableSibling</a> (const MachineInstr &amp;Inst, bool &amp;Commuted) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when \P Inst has reassociable sibling. <a href="#aea784a4f9e9aba7792c23484e2498e8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6875e5a149ffdf299b10e8f969d379d4">genAlternativeCodeSequence</a> (MachineInstr &amp;Root, unsigned Pattern, SmallVectorImpl&lt; MachineInstr * &gt; &amp;InsInstrs, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DelInstrs, DenseMap&lt; unsigned, unsigned &gt; &amp;InstIdxForVirtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When <a href="#a861381cad67866e249c6330631ac0742">getMachineCombinerPatterns()</a> finds patterns, this function generates the instructions that could replace the original code sequence. <a href="#a6875e5a149ffdf299b10e8f969d379d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6b72b3ba59a29cb680b5f00831a7b6">accumulateInstrSeqToRootLatency</a> (MachineInstr &amp;Root) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When calculate the latency of the root instruction, accumulate the latency of the sequence to the root latency. <a href="#acd6b72b3ba59a29cb680b5f00831a7b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ccb406a2c930b241430e6b7b3d1a4f">getReassociateOperandIndices</a> (const MachineInstr &amp;Root, unsigned Pattern, std::array&lt; unsigned, 5 &gt; &amp;OperandIndices) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The returned array encodes the operand index for each parameter because the operands may be commuted; the operand indices for associative operations might also be target-specific. <a href="#a99ccb406a2c930b241430e6b7b3d1a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e0c947b38bdebad23286c7764b5249">reassociateOps</a> (MachineInstr &amp;Root, MachineInstr &amp;Prev, unsigned Pattern, SmallVectorImpl&lt; MachineInstr * &gt; &amp;InsInstrs, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DelInstrs, ArrayRef&lt; unsigned &gt; OperandIndices, DenseMap&lt; unsigned, unsigned &gt; &amp;InstrIdxForVirtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to reassociate \P Root and \P Prev according to \P <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> to reduce critical path length. <a href="#ae5e0c947b38bdebad23286c7764b5249">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a903e4ccbdb00b36a08f5e84a8010c3cd">getReassociationOpcodes</a> (unsigned Pattern, const MachineInstr &amp;Root, const MachineInstr &amp;Prev) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassociation of some instructions requires inverse operations (e.g. <a href="#a903e4ccbdb00b36a08f5e84a8010c3cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55912dd5bde1306ca2642c4aebca197b">getExtendResourceLenLimit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The limit on resource length extension we accept in MachineCombiner <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>. <a href="#a55912dd5bde1306ca2642c4aebca197b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b63f89d9653388354a58218932dc2f8">setSpecialOperandAttr</a> (MachineInstr &amp;OldMI1, MachineInstr &amp;OldMI2, MachineInstr &amp;NewMI1, MachineInstr &amp;NewMI2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an architecture-specific helper function of reassociateOps. <a href="#a0b63f89d9653388354a58218932dc2f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb5569c23b5e1ed52164d9ec0496c05">useMachineCombiner</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when a target supports MachineCombiner. <a href="#a4cb5569c23b5e1ed52164d9ec0496c05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a08fc515218c080e73909645fecb41ed0">MachineTraceStrategy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1778172912b443f67ccb9ee1af22776">getMachineCombinerTraceStrategy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a strategy that MachineCombiner must use when creating traces. <a href="#ae1778172912b443f67ccb9ee1af22776">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8003a932104a6adf3ddbf4435a49f0">canCopyGluedNodeDuringSchedule</a> (SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> can be copied during scheduling even if it has glue. <a href="#a7b8003a932104a6adf3ddbf4435a49f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa44220d7a83b114a21ca2d23ffed03b2">unfoldMemoryOperand</a> (MachineFunction &amp;MF, MachineInstr &amp;MI, unsigned Reg, bool UnfoldLoad, bool UnfoldStore, SmallVectorImpl&lt; MachineInstr * &gt; &amp;NewMIs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>unfoldMemoryOperand - Separate a single instruction which folded a load or a store or a load and a store into two or more instruction. <a href="#aa44220d7a83b114a21ca2d23ffed03b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7a82bf89bd98729150cebde60be9dfd">unfoldMemoryOperand</a> (SelectionDAG &amp;DAG, SDNode *N, SmallVectorImpl&lt; SDNode * &gt; &amp;NewNodes) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b6d3fde7f1a20c72a6a7b4eeb4164f">getOpcodeAfterMemoryUnfold</a> (unsigned Opc, bool UnfoldLoad, bool UnfoldStore, unsigned *LoadRegIndex=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the opcode of the would be new instruction after load / store are unfolded from an instruction of the specified opcode. <a href="#a29b6d3fde7f1a20c72a6a7b4eeb4164f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ae1d6ce8dc191d8300c25b3e287961">areLoadsFromSameBasePtr</a> (SDNode *Load1, SDNode *Load2, int64_t &amp;Offset1, int64_t &amp;Offset2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used by the pre-regalloc scheduler to determine if two loads are loading from the same base address. <a href="#af6ae1d6ce8dc191d8300c25b3e287961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7613f5f7e38ac5338a58172dd6429370">shouldScheduleLoadsNear</a> (SDNode *Load1, SDNode *Load2, int64_t Offset1, int64_t Offset2, unsigned NumLoads) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a used by the pre-regalloc scheduler to determine (in conjunction with areLoadsFromSameBasePtr) if two loads should be scheduled together. <a href="#a7613f5f7e38ac5338a58172dd6429370">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbbc2492f83b9a1b2b2b850283240272">getMemOperandWithOffset</a> (const MachineInstr &amp;MI, const MachineOperand *&amp;BaseOp, int64_t &amp;Offset, bool &amp;OffsetIsScalable, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the base operand and byte offset of an instruction that reads/writes memory. <a href="#afbbc2492f83b9a1b2b2b850283240272">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad562f15f35ef21a4965d1b9f522a360c">getMemOperandsWithOffsetWidth</a> (const MachineInstr &amp;MI, SmallVectorImpl&lt; const MachineOperand * &gt; &amp;BaseOps, int64_t &amp;Offset, bool &amp;OffsetIsScalable, LocationSize &amp;Width, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get zero or more base operands and the byte offset of an instruction that reads/writes memory. <a href="#ad562f15f35ef21a4965d1b9f522a360c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28d18d91f58682d65e97e9c386064b5b">getBaseAndOffsetPosition</a> (const MachineInstr &amp;MI, unsigned &amp;BasePos, unsigned &amp;OffsetPos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction contains a base register and offset. <a href="#a28d18d91f58682d65e97e9c386064b5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/extaddrmode">ExtAddrMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ea0602dc926bed4a92bc63ae99e7cc9">getAddrModeFromMemoryOp</a> (const MachineInstr &amp;MemI, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> dependent implementation to get the values constituting the address <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> that is accessing memory. <a href="#a7ea0602dc926bed4a92bc63ae99e7cc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32583e70bd8c1b6ccb45a21129efac24">canFoldIntoAddrMode</a> (const MachineInstr &amp;MemI, Register Reg, const MachineInstr &amp;AddrI, ExtAddrMode &amp;AM) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it's possible and beneficial to fold the addressing computation <span class="doxyComputerOutput">AddrI</span> into the addressing mode of the load/store instruction <span class="doxyComputerOutput">MemI</span>. <a href="#a32583e70bd8c1b6ccb45a21129efac24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed830dc2b930795e75691f1efa942b12">emitLdStWithAddr</a> (MachineInstr &amp;MemI, const ExtAddrMode &amp;AM) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a load/store instruction with the same value register as <span class="doxyComputerOutput">MemI</span>, but using the address from <span class="doxyComputerOutput">AM</span>. <a href="#aed830dc2b930795e75691f1efa942b12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45aa2763f52ee7bb3f41393d1d4ba079">preservesZeroValueInReg</a> (const MachineInstr *MI, const Register NullValueReg, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if MI's Def is NullValueReg, and the MI does not change the Zero value. <a href="#a45aa2763f52ee7bb3f41393d1d4ba079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af454ffcb2775e8a8abf663da93a0a438">getIncrementValue</a> (const MachineInstr &amp;MI, int &amp;Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the instruction is an increment of a constant value, return the amount. <a href="#af454ffcb2775e8a8abf663da93a0a438">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c56f769334913401fe67e9e123b3d59">shouldClusterMemOps</a> (ArrayRef&lt; const MachineOperand * &gt; BaseOps1, int64_t Offset1, bool OffsetIsScalable1, ArrayRef&lt; const MachineOperand * &gt; BaseOps2, int64_t Offset2, bool OffsetIsScalable2, unsigned ClusterSize, unsigned NumBytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the two given memory operations should be scheduled adjacent. <a href="#a6c56f769334913401fe67e9e123b3d59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013a36a3a8a5acbdb9bcf1d3c6fede83">reverseBranchCondition</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverses the branch condition of the specified condition list, returning false on success and true if it cannot be reversed. <a href="#a013a36a3a8a5acbdb9bcf1d3c6fede83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee57d5d6295dfeb44f3b55301b20020">insertNoop</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a noop into the instruction stream at the specified point. <a href="#a4ee57d5d6295dfeb44f3b55301b20020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c15ac4d0e9521ba7225f100f657639">insertNoops</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, unsigned Quantity) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert noops into the instruction stream at the specified point. <a href="#ab2c15ac4d0e9521ba7225f100f657639">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8999c1de8a33ab1a9029e4852342e579">getNop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the noop instruction to use for a noop. <a href="#a8999c1de8a33ab1a9029e4852342e579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb223b29cc4acffa9ffd03d134b2a1e">isPostIncrement</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for post-incremented instructions. <a href="#a1cb223b29cc4acffa9ffd03d134b2a1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda2e966ced4c77ce8a78e5e063e07cd">isPredicated</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction is already predicated. <a href="#abda2e966ced4c77ce8a78e5e063e07cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a593a2fa65858fcd920bd782108c999">canPredicatePredicatedInstr</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assumes the instruction is already predicated and returns true if the instruction can be predicated again. <a href="#a0a593a2fa65858fcd920bd782108c999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea7fb8b18a37883f51af73238e47dea4">createMIROperandComment</a> (const MachineInstr &amp;MI, const MachineOperand &amp;Op, unsigned OpIdx, const TargetRegisterInfo *TRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4993b49c4db728d9669c0f6a08daae2e">isUnpredicatedTerminator</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction is a terminator instruction that has not been predicated. <a href="#a4993b49c4db728d9669c0f6a08daae2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49711da0a9e246f5960bf2816b0d8aa3">isUnconditionalTailCall</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if MI is an unconditional tail call. <a href="#a49711da0a9e246f5960bf2816b0d8aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163e14d44765e368d3a79ceea6d00eaa">canMakeTailCallConditional</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, const MachineInstr &amp;TailCall) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the tail call can be made conditional on BranchCond. <a href="#a163e14d44765e368d3a79ceea6d00eaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee18da5b03753cdb0cd484b2a4e2c35">replaceBranchWithTailCall</a> (MachineBasicBlock &amp;MBB, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, const MachineInstr &amp;TailCall) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the conditional branch in MBB with a conditional tail call. <a href="#abee18da5b03753cdb0cd484b2a4e2c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29513f18e551370b1b438f95403efc04">PredicateInstruction</a> (MachineInstr &amp;MI, ArrayRef&lt; MachineOperand &gt; Pred) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the instruction into a predicated instruction. <a href="#a29513f18e551370b1b438f95403efc04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ba312c2d730acd131fccc2cc787498">SubsumesPredicate</a> (ArrayRef&lt; MachineOperand &gt; Pred1, ArrayRef&lt; MachineOperand &gt; Pred2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the first specified predicate subsumes the second, e.g. <a href="#a51ba312c2d730acd131fccc2cc787498">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0695148f396023fb3cf404a5447a2412">ClobbersPredicate</a> (MachineInstr &amp;MI, std::vector&lt; MachineOperand &gt; &amp;Pred, bool SkipDead) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified instruction defines any predicate or condition code register(s) used for predication, returns true as well as the definition predicate(s) by reference. <a href="#a0695148f396023fb3cf404a5447a2412">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf401885b0d39da5774814718bc889c8">isPredicable</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified instruction can be predicated. <a href="#adf401885b0d39da5774814718bc889c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf676347c6bf8157f319dac9e601f168">isSafeToMoveRegClassDefs</a> (const TargetRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's safe to move a machine instruction that defines the specified register class. <a href="#adf676347c6bf8157f319dac9e601f168">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad071e937f4986e51fd3fd54b10888894">isSchedulingBoundary</a> (const MachineInstr &amp;MI, const MachineBasicBlock *MBB, const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given instruction should be considered a scheduling boundary. <a href="#ad071e937f4986e51fd3fd54b10888894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65168b27efceb92102521e2bc82b8d49">getInlineAsmLength</a> (const char *Str, const MCAsmInfo &amp;MAI, const TargetSubtargetInfo *STI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Measure the specified inline asm to determine an approximation of its length. <a href="#a65168b27efceb92102521e2bc82b8d49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7242b69b2f705111801d717e2ea243b5">CreateTargetHazardRecognizer</a> (const TargetSubtargetInfo *STI, const ScheduleDAG *DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a hazard recognizer to use for this target when scheduling the machine instructions before register allocation. <a href="#a7242b69b2f705111801d717e2ea243b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da941cb7cfe3ae9b3dae1f5caac8b78">CreateTargetMIHazardRecognizer</a> (const InstrItineraryData *, const ScheduleDAGMI *DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a hazard recognizer to use for this target when scheduling the machine instructions before register allocation. <a href="#a5da941cb7cfe3ae9b3dae1f5caac8b78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000bd55721d30de4fee9eb3d812714ea">CreateTargetPostRAHazardRecognizer</a> (const InstrItineraryData *, const ScheduleDAG *DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a hazard recognizer to use for this target when scheduling the machine instructions after register allocation. <a href="#a000bd55721d30de4fee9eb3d812714ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d2e824f1b036f45b51519f2844720b">CreateTargetPostRAHazardRecognizer</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a hazard recognizer to use for by non-scheduling passes. <a href="#a55d2e824f1b036f45b51519f2844720b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af286c176e38f876d4f56a34cb9ee319a">usePreRAHazardRecognizer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a global flag for disabling the PreRA hazard recognizer that targets may choose to honor. <a href="#af286c176e38f876d4f56a34cb9ee319a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af90a0ce256d5ae1e1181b032da5d2779">analyzeCompare</a> (const MachineInstr &amp;MI, Register &amp;SrcReg, Register &amp;SrcReg2, int64_t &amp;Mask, int64_t &amp;Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a comparison instruction, return the source registers in SrcReg and SrcReg2 if having two register operands, and the value it compares against in CmpValue. <a href="#af90a0ce256d5ae1e1181b032da5d2779">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d95382897959324602ecb63f7392fda">optimizeCompareInstr</a> (MachineInstr &amp;CmpInstr, Register SrcReg, Register SrcReg2, int64_t Mask, int64_t Value, const MachineRegisterInfo *MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if the comparison instruction can be converted into something more efficient. <a href="#a6d95382897959324602ecb63f7392fda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9414061830d845a2b79363614cf5b5db">optimizeCondBranch</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01961400ab1186ac9f849cf0e738447f">optimizeLoadInstr</a> (MachineInstr &amp;MI, const MachineRegisterInfo *MRI, Register &amp;FoldAsLoadDefReg, MachineInstr *&amp;DefMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to remove the load by folding it to a register operand at the use. <a href="#a01961400ab1186ac9f849cf0e738447f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41c45a69f227ee71e5ced4e6e3fde18">foldImmediate</a> (MachineInstr &amp;UseMI, MachineInstr &amp;DefMI, Register Reg, MachineRegisterInfo *MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'Reg' is known to be defined by a move immediate instruction, try to fold the immediate into the use instruction. <a href="#aa41c45a69f227ee71e5ced4e6e3fde18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bf43322793449e23ced7810ac16ecb">getNumMicroOps</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of u-operations the given machine instruction will be decoded to on the target cpu. <a href="#a16bf43322793449e23ced7810ac16ecb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba282dba26451dcfbbc938444595d7e">isZeroCost</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for pseudo instructions that don't consume any machine resources in their current form. <a href="#a0ba282dba26451dcfbbc938444595d7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65c4a19ddc8ce7ddec084e5a1a4a62a">getOperandLatency</a> (const InstrItineraryData *ItinData, SDNode *DefNode, unsigned DefIdx, SDNode *UseNode, unsigned UseIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1e693dee703f46fd28221e99d4acff">getOperandLatency</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;DefMI, unsigned DefIdx, const MachineInstr &amp;UseMI, unsigned UseIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and return the use operand latency of a given pair of def and use. <a href="#a9b1e693dee703f46fd28221e99d4acff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45af359a246cde99ce09578e3998985">getInstrLatency</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;MI, unsigned *PredCost=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the instruction latency of a given instruction. <a href="#ac45af359a246cde99ce09578e3998985">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89d6efd5d16c7e44f26ef26296e13aa">getPredicationCost</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86ea143f1ea40632ba851badcf377101">getInstrLatency</a> (const InstrItineraryData *ItinData, SDNode *Node) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5424d7c9e608bd5b2087f1021908a08">defaultDefLatency</a> (const MCSchedModel &amp;SchedModel, const MachineInstr &amp;DefMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the default expected latency for a def based on its opcode. <a href="#ae5424d7c9e608bd5b2087f1021908a08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebbd8a676ca4d2926a87022815a5015d">isHighLatencyDef</a> (int opc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this opcode has high latency to its result. <a href="#aebbd8a676ca4d2926a87022815a5015d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4993bfe73a55f4fcc5d02d09c410ddaf">hasHighOperandLatency</a> (const TargetSchedModel &amp;SchedModel, const MachineRegisterInfo *MRI, const MachineInstr &amp;DefMI, unsigned DefIdx, const MachineInstr &amp;UseMI, unsigned UseIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute operand latency between a def of 'Reg' and a use in the current loop. <a href="#a4993bfe73a55f4fcc5d02d09c410ddaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa73253579dd1c4acde85953454e838">hasLowDefLatency</a> (const TargetSchedModel &amp;SchedModel, const MachineInstr &amp;DefMI, unsigned DefIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute operand latency of a def of 'Reg'. <a href="#a0aa73253579dd1c4acde85953454e838">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a490afb5ecb8232428c7ce7b87ef24b43">verifyInstruction</a> (const MachineInstr &amp;MI, StringRef &amp;ErrInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform target-specific instruction verification. <a href="#a490afb5ecb8232428c7ce7b87ef24b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint16_t, uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907019eb40cf2db5f3a35cb0bc456347">getExecutionDomain</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current execution domain and bit mask of possible domains for instruction. <a href="#a907019eb40cf2db5f3a35cb0bc456347">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcfa8a45f569feb4562cff3567163ef">setExecutionDomain</a> (MachineInstr &amp;MI, unsigned Domain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the opcode of MI to execute in <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a>. <a href="#adbcfa8a45f569feb4562cff3567163ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14308e147ea57526f7fd1198ab551a9a">getPartialRegUpdateClearance</a> (const MachineInstr &amp;MI, unsigned OpNum, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the preferred minimum clearance before an instruction with an unwanted partial register update. <a href="#a14308e147ea57526f7fd1198ab551a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4159fd0062dd97fe920f738c776a7356">getUndefRegClearance</a> (const MachineInstr &amp;MI, unsigned OpNum, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimum clearance before an instruction that reads an unused register. <a href="#a4159fd0062dd97fe920f738c776a7356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525a9aaabc1362deb245b0099ea5538e">breakPartialRegDependency</a> (MachineInstr &amp;MI, unsigned OpNum, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a dependency-breaking instruction before MI to eliminate an unwanted dependency on OpNum. <a href="#a525a9aaabc1362deb245b0099ea5538e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dfapacketizer">DFAPacketizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186f383639b8c8fe141b55411d1121a9">CreateTargetScheduleState</a> (const TargetSubtargetInfo &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create machine specific model for scheduling. <a href="#a186f383639b8c8fe141b55411d1121a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8ea6535c262fbc8a16177783020314">areMemAccessesTriviallyDisjoint</a> (const MachineInstr &amp;MIa, const MachineInstr &amp;MIb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sometimes, it is possible for the target to tell, even without aliasing information, that two MIs access different memory addresses. <a href="#a5f8ea6535c262fbc8a16177783020314">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3c5e05e3b2eb5e8dd9c763efbdca4b">getMachineCSELookAheadLimit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value to use for the MachineCSE's LookAheadLimit, which is a heuristic used for CSE'ing phys reg defs. <a href="#afa3c5e05e3b2eb5e8dd9c763efbdca4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f67bce035b491e5e6d95286ffe20da1">getMemOperandAACheckLimit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximal number of alias checks on memory operands. <a href="#a6f67bce035b491e5e6d95286ffe20da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; int, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3166a8e59fbea4a6f27fefd6a8fea1">getSerializableTargetIndices</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an array that contains the ids of the target indices (used for the TargetIndex machine operand) and their names. <a href="#a3d3166a8e59fbea4a6f27fefd6a8fea1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf55430291b4f35540c9c7dfc28fedaa">decomposeMachineOperandsTargetFlags</a> (unsigned) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decompose the machine operand's target flags into two values - the direct target flag value and any of bit flags that are applied. <a href="#adf55430291b4f35540c9c7dfc28fedaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb630da1cbdfc0d8425933e20b37a73">getSerializableDirectMachineOperandTargetFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an array that contains the direct target flag values and their names. <a href="#aefb630da1cbdfc0d8425933e20b37a73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ef2aeaba3f310827d58a0a3b16cfd8">getSerializableBitmaskMachineOperandTargetFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an array that contains the bitmask target flag values and their names. <a href="#a82ef2aeaba3f310827d58a0a3b16cfd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e0bf9b6a35f938342ed56dfcfe7786">getSerializableMachineMemOperandTargetFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an array that contains the MMO target flag values and their names. <a href="#a27e0bf9b6a35f938342ed56dfcfe7786">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d33681dd1899a420e4b30bf11f4b58e">isTailCall</a> (const MachineInstr &amp;Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines whether <span class="doxyComputerOutput">Inst</span> is a tail call instruction. <a href="#a9d33681dd1899a420e4b30bf11f4b58e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0138c08492e75b8b22f8fe0764b95853">isBasicBlockPrologue</a> (const MachineInstr &amp;MI, Register Reg=Register()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the instruction is bound to the top of its basic block and no other instructions shall be inserted before it. <a href="#a0138c08492e75b8b22f8fe0764b95853">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf855363122e65fd4e6f2df1d16aba0">getLiveRangeSplitOpcode</a> (Register Reg, const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows targets to use appropriate copy instruction while spilitting live range of a register in register allocation. <a href="#a6cf855363122e65fd4e6f2df1d16aba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a804530332064e8450f5c01c1291e3ec8">createPHIDestinationCopy</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsPt, const DebugLoc &amp;DL, Register Src, Register Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>During PHI eleimination lets target to make necessary checks and insert the copy to the PHI destination register in a target specific manner. <a href="#a804530332064e8450f5c01c1291e3ec8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf9cd5e2258e984d377933b695ccf39b">createPHISourceCopy</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsPt, const DebugLoc &amp;DL, Register Src, unsigned SrcSubReg, Register Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>During PHI eleimination lets target to make necessary checks and insert the copy to the PHI destination register in a target specific manner. <a href="#aaf9cd5e2258e984d377933b695ccf39b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">outliner::OutlinedFunction</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4e1b8b82113ab0848fe7e4e3a2574f">getOutliningCandidateInfo</a> (const MachineModuleInfo &amp;MMI, std::vector&lt; outliner::Candidate &gt; &amp;RepeatedSequenceLocs, unsigned MinRepeats) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">outliner::OutlinedFunction</a></span> struct containing target-specific information for a set of outlining candidates. <a href="#aae4e1b8b82113ab0848fe7e4e3a2574f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4253df7a10e437a01d42c223e196c0b8">mergeOutliningCandidateAttributes</a> (Function &amp;F, std::vector&lt; outliner::Candidate &gt; &amp;Candidates) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional target hook to create the LLVM IR attributes for the outlined function. <a href="#a4253df7a10e437a01d42c223e196c0b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52">outliner::InstrType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3034fb1c96df7c2c8f52f11c8fc82467">getOutliningType</a> (const MachineModuleInfo &amp;MMI, MachineBasicBlock::iterator &amp;MIT, unsigned Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how or if <span class="doxyComputerOutput">MIT</span> should be outlined. <a href="#a3034fb1c96df7c2c8f52f11c8fc82467">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952e245a616622682cd83b1291314660">isMBBSafeToOutlineFrom</a> (MachineBasicBlock &amp;MBB, unsigned &amp;Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional target hook that returns true if <span class="doxyComputerOutput">MBB</span> is safe to outline from, and returns any target-specific information in <span class="doxyComputerOutput">Flags</span>. <a href="#a952e245a616622682cd83b1291314660">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0028f0ee9f737ba5290254b7924accbb">getOutlinableRanges</a> (MachineBasicBlock &amp;MBB, unsigned &amp;Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional target hook which partitions <span class="doxyComputerOutput">MBB</span> into outlinable ranges for instruction mapping purposes. <a href="#a0028f0ee9f737ba5290254b7924accbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e2b33837925c6898584bc1118f2f2a">buildOutlinedFrame</a> (MachineBasicBlock &amp;MBB, MachineFunction &amp;MF, const outliner::OutlinedFunction &amp;OF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a custom frame for outlined functions. <a href="#a73e2b33837925c6898584bc1118f2f2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00242d76e808398358fa1e46e9a6885">insertOutlinedCall</a> (Module &amp;M, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;It, MachineFunction &amp;MF, outliner::Candidate &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a call to an outlined function into the program. <a href="#ab00242d76e808398358fa1e46e9a6885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5b9f0e5e1e90caa9c8def3d230ddbf">buildClearRegister</a> (Register Reg, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator Iter, DebugLoc &amp;DL, bool AllowSideEffects=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an architecture-specific instruction to clear a register. <a href="#a0c5b9f0e5e1e90caa9c8def3d230ddbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd9a0614742c8f6c8523b0c34b984ee">isFunctionSafeToOutlineFrom</a> (MachineFunction &amp;MF, bool OutlineFromLinkOnceODRs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function can safely be outlined from. <a href="#a6fd9a0614742c8f6c8523b0c34b984ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2de90c613673f0815ee6aa406f67390a">shouldOutlineFromFunctionByDefault</a> (MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function should be outlined from by default. <a href="#a2de90c613673f0815ee6aa406f67390a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b0cbf92a3dd0f5cab9d5d3067c2003">isFunctionSafeToSplit</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function is a viable candidate for machine function splitting. <a href="#ae0b0cbf92a3dd0f5cab9d5d3067c2003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726928467271e18f3d17b2942cd04984">isMBBSafeToSplitToCold</a> (const MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> can safely be split to the cold section. <a href="#a726928467271e18f3d17b2942cd04984">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ad81cebfbef0742380b0227ae7000e0a3">ParamLoadedValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6885e40448874565521daac98e11f50d">describeLoadedValue</a> (const MachineInstr &amp;MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the expression describing the <span class="doxyComputerOutput">MI</span> loading a value into the physical register <span class="doxyComputerOutput">Reg</span>. <a href="#a6885e40448874565521daac98e11f50d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec0a63c3d6d45dd9fee9c1115816e0b">isExtendLikelyToBeFolded</a> (MachineInstr &amp;ExtMI, MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the generic extension instruction <span class="doxyComputerOutput">ExtMI</span>, returns true if this extension is a likely candidate for being folded into an another instruction. <a href="#a0ec0a63c3d6d45dd9fee9c1115816e0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mirformatter">MIRFormatter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3492aff3468d2d229f1a093379fbdcf7">getMIRFormatter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return MIR formatter to format/parse MIR operands. <a href="#a3492aff3468d2d229f1a093379fbdcf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1fbe2cfd4ac1e373cdaba16ec4a70b4">getTailDuplicateSize</a> (CodeGenOptLevel OptLevel) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target-specific default value for tail duplication. <a href="#af1fbe2cfd4ac1e373cdaba16ec4a70b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9acee94fe64ebb7dc672f6e5697fbe6b">getTailMergeSize</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target-specific default value for tail merging. <a href="#a9acee94fe64ebb7dc672f6e5697fbe6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8b374c12bde7a8aa400ae5e34e6956">getCalleeOperand</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the callee operand from the given <span class="doxyComputerOutput">MI</span>. <a href="#a9e8b374c12bde7a8aa400ae5e34e6956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25f">InstructionUniformity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b400bea2e0c5c1d17478053b5acdd3e">getInstructionUniformity</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the uniformity behavior of the given instruction. <a href="#a9b400bea2e0c5c1d17478053b5acdd3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87a4a6ef69b65a33d072718a8e0e25e">isExplicitTargetIndexDef</a> (const MachineInstr &amp;MI, int &amp;Index, int64_t &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given <span class="doxyComputerOutput">MI</span> defines a TargetIndex operand that can be tracked by their offset, can have values, and can have debug info associated with it. <a href="#aa87a4a6ef69b65a33d072718a8e0e25e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e324da740d76918b3f2b2ecf807e49">getCallFrameSizeAt</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d10b938465726d85e01bbb669e184d0">getFrameIndexOperands</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;Ops, int FI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fills in the necessary MachineOperands to refer to a frame index. <a href="#a0d10b938465726d85e01bbb669e184d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab671544f7af287b25a5e612f6e919975">isReallyTriviallyReMaterializable</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For instructions with opcodes for which the M_REMATERIALIZABLE flag is set, this hook lets the target specify whether the instruction is actually trivially rematerializable, taking into consideration its operands. <a href="#ab671544f7af287b25a5e612f6e919975">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4d05c8ea2fc82ae12300ef5fb48951">commuteInstructionImpl</a> (MachineInstr &amp;MI, bool NewMI, unsigned OpIdx1, unsigned OpIdx2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method commutes the operands of the given machine instruction MI. <a href="#adf4d05c8ea2fc82ae12300ef5fb48951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb5f369839e0987506e72b0ffc1b982">isCopyInstrImpl</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-dependent implementation for IsCopyInstr. <a href="#a7eb5f369839e0987506e72b0ffc1b982">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13cf72d93ee18d693c7a74f0c1307cea">isCopyLikeInstrImpl</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47bacdac90d2744684f980e1ad40594">isUnspillableTerminatorImpl</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given terminator MI is not expected to spill. <a href="#ae47bacdac90d2744684f980e1ad40594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a1e73b39957ad3da60cb9d3a690df89">foldMemoryOperandImpl</a> (MachineFunction &amp;MF, MachineInstr &amp;MI, ArrayRef&lt; unsigned &gt; Ops, MachineBasicBlock::iterator InsertPt, int FrameIndex, LiveIntervals *LIS=nullptr, VirtRegMap *VRM=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-dependent implementation for foldMemoryOperand. <a href="#a0a1e73b39957ad3da60cb9d3a690df89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f87b0480bb0e4d689f7b3cf2aa88a1">foldMemoryOperandImpl</a> (MachineFunction &amp;MF, MachineInstr &amp;MI, ArrayRef&lt; unsigned &gt; Ops, MachineBasicBlock::iterator InsertPt, MachineInstr &amp;LoadMI, LiveIntervals *LIS=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-dependent implementation for foldMemoryOperand. <a href="#af4f87b0480bb0e4d689f7b3cf2aa88a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52e026925b73de52f7a563693ebff007">getRegSequenceLikeInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, SmallVectorImpl&lt; RegSubRegPairAndIdx &gt; &amp;InputRegs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-dependent implementation of getRegSequenceInputs. <a href="#a52e026925b73de52f7a563693ebff007">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c44734f854fb7f620d16097f2af637">getExtractSubregLikeInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, RegSubRegPairAndIdx &amp;InputReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-dependent implementation of getExtractSubregInputs. <a href="#af1c44734f854fb7f620d16097f2af637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b51d2dd19b3859797509c03d5f451f1">getInsertSubregLikeInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, RegSubRegPair &amp;BaseReg, RegSubRegPairAndIdx &amp;InsertedReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-dependent implementation of getInsertSubregInputs. <a href="#a2b51d2dd19b3859797509c03d5f451f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52">outliner::InstrType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af67652d97de393fd3208c625cea6b1">getOutliningTypeImpl</a> (const MachineModuleInfo &amp;MMI, MachineBasicBlock::iterator &amp;MIT, unsigned Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-dependent implementation for getOutliningTypeImpl. <a href="#a2af67652d97de393fd3208c625cea6b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mirformatter">MIRFormatter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae021517c1f7eba6dbb68ae02eb5383e3">Formatter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4029cf1b9edf2988c2fc5a0cc5b5f766">CallFrameSetupOpcode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78223000912a8a9aa3443a60a1d0e9e7">CallFrameDestroyOpcode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc11af84e38e8e4c664c69ed7d6ab78">CatchRetOpcode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8047b6543112b3c755cedc67707dc6db">ReturnOpcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a499274493eca235e684f82ee54b70">isGenericOpcode</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60fd4c7626ec53d75182d6f54743745">isGenericAtomicRMWOpcode</a> (unsigned Opc)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5b8db7ddf8b00b66e4f64711a053cd">fixCommutedOpIndices</a> (unsigned &amp;ResultIdx1, unsigned &amp;ResultIdx2, unsigned CommutableOpIdx1, unsigned CommutableOpIdx2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns the (CommutableOpIdx1, CommutableOpIdx2) pair of commutable operand indices to (ResultIdx1, ResultIdx2). <a href="#aef5b8db7ddf8b00b66e4f64711a053cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73e2be2b66dc9e4f2f90d56076d7ea9">CommuteAnyOperandIndex</a> = ~0U</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> - Interface to description of machine instruction set.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetInstrInfo() {#ab0ea1fe6f61d0e861ed2be7632a270bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetInstrInfo::TargetInstrInfo (unsigned CFSetupOpcode=~0u, unsigned CFDestroyOpcode=~0u, unsigned CatchRetOpcode=~0u, unsigned ReturnOpcode=~0u)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a82b4dd0611f4e9b708e1940a945581e9">operator=</a>, <a href="#ae5e0c947b38bdebad23286c7764b5249">reassociateOps</a> and <a href="#abfc72b67ab4a799ac5472bb3ca3250fc">TargetInstrInfo</a>.</p>

</div>
</div>

### TargetInstrInfo() {#abfc72b67ab4a799ac5472bb3ca3250fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetInstrInfo::TargetInstrInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="#ab0ea1fe6f61d0e861ed2be7632a270bb">TargetInstrInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TargetInstrInfo() {#ac2c402f5f405a15e3356949d3d1900c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetInstrInfo::~TargetInstrInfo ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a82b4dd0611f4e9b708e1940a945581e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetInstrInfo &amp; llvm::TargetInstrInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="#ab0ea1fe6f61d0e861ed2be7632a270bb">TargetInstrInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accumulateInstrSeqToRootLatency() {#acd6b72b3ba59a29cb680b5f00831a7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::accumulateInstrSeqToRootLatency (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root)</td>
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

<p>When calculate the latency of the root instruction, accumulate the latency of the sequence to the root latency.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Root</td>
<td class="doxyParamItemDescription"><p>- <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that could be combined with one of its operands</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### analyzeBranch() {#a0dfb0c744373d4b6112eb343a5b07fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::analyzeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; FBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, bool AllowModify=false)</td>
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

<p>Analyze the branching code at the end of MBB, returning true if it cannot be understood (e.g.</p>


<p>it's a switch dispatch or isn't implemented for a target). Upon success, this returns false and returns with the following information in various cases:</p>


<ol class="doxyList" type="1">
<li>If this block ends with no branches (it just falls through to its succ) just return false, leaving TBB/FBB null.</li>
<li>If this block ends with only an unconditional branch, it sets TBB to be the destination block.</li>
<li>If this block ends with a conditional branch and it falls through to a successor block, it sets TBB to be the branch destination block and a list of operands that evaluate the condition. These operands can be passed to other <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> methods to create new branches.</li>
<li>If this block ends with a conditional branch followed by an unconditional branch, it returns the 'true' destination in TBB, the 'false' destination in FBB, and a list of operands that evaluate the condition. These operands can be passed to other <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> methods to create new branches.</li>
</ol>

<p>Note that removeBranch and insertBranch must be implemented to support cases where this method returns success.</p>


<p>If AllowModify is true, then this routine is allowed to modify the basic block (e.g. delete instructions after the unconditional branch).</p>


<p>The CFG information in MBB.Predecessors and MBB.Successors must be valid before calling this function.</p>


<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### analyzeBranchPredicate() {#a2b3f813a206819029043906eedccc502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::analyzeBranchPredicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/machinebranchpredicate">MachineBranchPredicate</a> &amp; MBP, bool AllowModify=false)</td>
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

<p>Analyze the branching code at the end of MBB and parse it into the <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/machinebranchpredicate">MachineBranchPredicate</a> structure if possible.</p>


<p>Returns false on success and true on failure.</p>


<p>If AllowModify is true, then this routine is allowed to modify the basic block (e.g. delete instructions after the unconditional branch).</p>


<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### analyzeCompare() {#af90a0ce256d5ae1e1181b032da5d2779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::analyzeCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg2, int64_t &amp; Mask, int64_t &amp; Value)</td>
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

<p>For a comparison instruction, return the source registers in SrcReg and SrcReg2 if having two register operands, and the value it compares against in CmpValue.</p>


<p>Return true if the comparison instruction can be analyzed.</p>


<p>Definition at line 1731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### analyzeLoop() {#a951ed5729e865521d99c1b7bf2e4e4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::analyzeLoop (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; IndVarInst, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; CmpInst)</td>
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

<p>Analyze the loop code, return true if it cannot be understood.</p>


<p>Upon success, this function returns false and returns information about the induction variable and compare instruction used at the end.</p>


<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### analyzeLoopForPipelining() {#a047bd8fdcc19cf2047e947ca565ff8fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; PipelinerLoopInfo &gt; llvm::TargetInstrInfo::analyzeLoopForPipelining (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LoopBB)</td>
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

<p>Analyze loop L, which must be a single-basic-block loop, and if the conditions can be understood enough produce a <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo">PipelinerLoopInfo</a> object.</p>

<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### analyzeSelect() {#ad0e13c52b664b67847a458ba5e6f9009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::analyzeSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, unsigned &amp; TrueOp, unsigned &amp; FalseOp, bool &amp; Optimizable)</td>
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

<p>Analyze the given select instruction, returning true if it cannot be understood.</p>


<p>It is assumed that MI-&gt;isSelect() is true.</p>


<p>When successful, return the controlling condition and the operands that determine the true and false result values.</p>


<p>Result = SELECT Cond, TrueOp, FalseOp</p>


<p>Some targets can optimize select instructions, for example by predicating the instruction defining one of the operands. Such targets should set Optimizable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p>Select instruction to analyze.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Cond</td>
<td class="doxyParamItemDescription"><p>Condition controlling the select.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TrueOp</td>
<td class="doxyParamItemDescription"><p>Operand number of the value selected when Cond is true.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FalseOp</td>
<td class="doxyParamItemDescription"><p>Operand number of the value selected when Cond is false.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Optimizable</td>
<td class="doxyParamItemDescription"><p>Returned as true if MI is optimizable.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>False on success.</p></dd>
</dl>


<p>Definition at line 993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### areLoadsFromSameBasePtr() {#af6ae1d6ce8dc191d8300c25b3e287961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::areLoadsFromSameBasePtr (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load1, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load2, int64_t &amp; Offset1, int64_t &amp; Offset2)</td>
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

<p>This is used by the pre-regalloc scheduler to determine if two loads are loading from the same base address.</p>


<p>It should only return true if the base pointers are the same and the only differences between the two addresses are the offset. It also returns the offsets by reference.</p>


<p>Definition at line 1463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### areMemAccessesTriviallyDisjoint() {#a5f8ea6535c262fbc8a16177783020314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::areMemAccessesTriviallyDisjoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MIa, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MIb)</td>
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

<p>Sometimes, it is possible for the target to tell, even without aliasing information, that two MIs access different memory addresses.</p>


<p>This function returns true if two MIs access different memory addresses and false otherwise.</p>


<p>Assumes any physical registers used to compute addresses have the same value for both instructions. (This is the most useful assumption for post-RA scheduling.)</p>


<p>See also <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3da773a37ef4e3325379dd6718317b74">MachineInstr::mayAlias</a>, which is implemented on top of this function.</p>


<p>Definition at line 1983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a17f5d15a7320dec2cfefb6617f711ab7">llvm::MachineInstr::mayLoadOrStore</a>.</p>

</div>
</div>

### areOpcodesEqualOrInverse() {#a29e545675db8b534aec8eccb7bedb2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::areOpcodesEqualOrInverse (unsigned Opcode1, unsigned Opcode2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true when \P Opcode1 or its inversion is equal to \P Opcode2.</p>

<p>Declaration at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="#ab0568ec903d0544ec11e0fb013d2fbe2">getInverseOpcode</a>.</p>


<p>Referenced by <a href="#a903e4ccbdb00b36a08f5e84a8010c3cd">getReassociationOpcodes</a> and <a href="#aea784a4f9e9aba7792c23484e2498e8d">hasReassociableSibling</a>.</p>

</div>
</div>

### breakPartialRegDependency() {#a525a9aaabc1362deb245b0099ea5538e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::breakPartialRegDependency (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Insert a dependency-breaking instruction before MI to eliminate an unwanted dependency on OpNum.</p>


<p>If it wasn't possible to avoid a def in the last N instructions before MI (see getPartialRegUpdateClearance), this hook will be called to break the unwanted dependency.</p>


<p>On x86, an xorps instruction can be used as a dependency breaker:</p>


<p>addps xmm1, xmm0 movaps xmm0, (rax) xorps xmm0, xmm0 cvtsi2ss rbx, xmm0</p>


<p>An &lt;imp-kill&gt; operand should be added to MI if an instruction was inserted. This ties the instructions together in the post-ra scheduler.</p>


<p>Definition at line 1962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### buildClearRegister() {#a0c5b9f0e5e1e90caa9c8def3d230ddbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::buildClearRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Iter, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool AllowSideEffects=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Insert an architecture-specific instruction to clear a register.</p>


<p>If you need to avoid sideeffects (e.g. avoid XOR on x86, which sets EFLAGS), set <span class="doxyComputerOutput">AllowSideEffects</span> to <span class="doxyComputerOutput">false</span>.</p>


<p>Definition at line 2187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### buildOutlinedFrame() {#a73e2b33837925c6898584bc1118f2f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::buildOutlinedFrame (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">outliner::OutlinedFunction</a> &amp; OF)</td>
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

<p>Insert a custom frame for outlined functions.</p>

<p>Definition at line 2167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### canCopyGluedNodeDuringSchedule() {#a7b8003a932104a6adf3ddbf4435a49f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::canCopyGluedNodeDuringSchedule (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Return true if the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> can be copied during scheduling even if it has glue.</p>

<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### canFoldIntoAddrMode() {#a32583e70bd8c1b6ccb45a21129efac24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::canFoldIntoAddrMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MemI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; AddrI, <a href="/web-llvm/docs/api/structs/llvm/extaddrmode">ExtAddrMode</a> &amp; AM)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it's possible and beneficial to fold the addressing computation <span class="doxyComputerOutput">AddrI</span> into the addressing mode of the load/store instruction <span class="doxyComputerOutput">MemI</span>.</p>


<p>The memory instruction is a user of the virtual register <span class="doxyComputerOutput">Reg</span>, which in turn is the ultimate destination of zero or more COPY instructions from the output register of <span class="doxyComputerOutput">AddrI</span>. Return the adddressing mode after folding in <span class="doxyComputerOutput">AM</span>.</p>


<p>Definition at line 1534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### canInsertSelect() {#ae0990ac346653cb1c820f391ffbf5ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::canInsertSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TrueReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FalseReg, int &amp; CondCycles, int &amp; TrueCycles, int &amp; FalseCycles)</td>
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

<p>Return true if it is possible to insert a select instruction that chooses between TrueReg and FalseReg based on the condition code in Cond.</p>


<p>When successful, also return the latency in cycles from TrueReg, FalseReg, and Cond to the destination register. In most cases, a select instruction will be 1 cycle, so CondCycles = TrueCycles = FalseCycles = 1</p>


<p>Some x86 implementations have 2-cycle cmov instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBB</td>
<td class="doxyParamItemDescription"><p>Block where select instruction would be inserted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Cond</td>
<td class="doxyParamItemDescription"><p>Condition returned by analyzeBranch.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DstReg</td>
<td class="doxyParamItemDescription"><p>Virtual dest register that the result should write to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TrueReg</td>
<td class="doxyParamItemDescription"><p>Virtual register to select when Cond is true.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FalseReg</td>
<td class="doxyParamItemDescription"><p>Virtual register to select when Cond is false.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CondCycles</td>
<td class="doxyParamItemDescription"><p>Latency from Cond+Branch to select output.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TrueCycles</td>
<td class="doxyParamItemDescription"><p>Latency from TrueReg to select output.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FalseCycles</td>
<td class="doxyParamItemDescription"><p>Latency from FalseReg to select output.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### canMakeTailCallConditional() {#a163e14d44765e368d3a79ceea6d00eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::canMakeTailCallConditional (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; TailCall)</td>
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

<p>Returns true if the tail call can be made conditional on BranchCond.</p>

<p>Definition at line 1636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>.</p>

</div>
</div>

### canPredicatePredicatedInstr() {#a0a593a2fa65858fcd920bd782108c999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::canPredicatePredicatedInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Assumes the instruction is already predicated and returns true if the instruction can be predicated again.</p>

<p>Definition at line 1616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abda2e966ced4c77ce8a78e5e063e07cd">isPredicated</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### ClobbersPredicate() {#a0695148f396023fb3cf404a5447a2412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::ClobbersPredicate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Pred, bool SkipDead)</td>
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

<p>If the specified instruction defines any predicate or condition code register(s) used for predication, returns true as well as the definition predicate(s) by reference.</p>


<p>SkipDead should be set to false at any point that dead predicate instructions should be considered as being defined. A dead predicate instruction is one that is guaranteed to be removed after a call to PredicateInstruction.</p>


<p>Definition at line 1667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### commuteInstruction() {#aa41720cc33b0511709c92abcb164a59d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * TargetInstrInfo::commuteInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool NewMI=false, unsigned OpIdx1=<a href="#ae73e2be2b66dc9e4f2f90d56076d7ea9">CommuteAnyOperandIndex</a>, unsigned OpIdx2=<a href="#ae73e2be2b66dc9e4f2f90d56076d7ea9">CommuteAnyOperandIndex</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method commutes the operands of the given machine instruction MI.</p>


<p>The operands to be commuted are specified by their indices OpIdx1 and OpIdx2. OpIdx1 and OpIdx2 arguments may be set to a special value 'CommuteAnyOperandIndex', which means that the method is free to choose any arbitrarily chosen commutable operand. If both arguments are set to 'CommuteAnyOperandIndex' then the method looks for 2 different commutable operands; then commutes them if such operands could be found.</p>


<p>If NewMI is false, MI is modified in place and returned; otherwise, a new machine instruction is created and returned.</p>


<p>Do not call this method for a non-commutable instruction or for non-commuable operands. Even though the instruction is commutable, the method may still fail to commute the operands, null pointer is returned in such cases.</p>


<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae73e2be2b66dc9e4f2f90d56076d7ea9">CommuteAnyOperandIndex</a>, <a href="#adf4d05c8ea2fc82ae12300ef5fb48951">commuteInstructionImpl</a>, <a href="#a422b844cc7e3db360908c008cb651f96">findCommutedOpIndices</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### convertToThreeAddress() {#ada0a8cb9a764d058a63b77d50e9c0787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::convertToThreeAddress (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/livevariables">LiveVariables</a> * LV, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
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

<p>This method must be implemented by targets that set the M_CONVERTIBLE_TO_3_ADDR flag.</p>


<p>When this flag is set, the target may be able to convert a two-address instruction into one or more true three-address instructions on demand. This allows the <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> target (for example) to convert ADD and SHL instructions into LEA instructions if they would require register copies due to two-addressness.</p>


<p>This method returns a null pointer if the transformation cannot be performed, otherwise it returns the last new instruction.</p>


<p>If <span class="doxyComputerOutput">LIS</span> is not nullptr, the <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> info should be updated for replacing <span class="doxyComputerOutput">MI</span> with new instructions, even though this function does not remove MI.</p>


<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### copyPhysReg() {#ad61db491bd5855c30926453db6401958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::copyPhysReg (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> DestReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false)</td>
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

<p>Emit instructions to copy a pair of physical registers.</p>


<p>This function should support copies within any legal register class as well as any cross-class copies created during instruction selection.</p>


<p>The source and destination registers may overlap, which may require a careful implementation when multiple copy instructions are required for large registers. See for example the <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> target.</p>


<p>If RenamableDest is true, the copy instruction's destination operand is marked renamable. If RenamableSrc is true, the copy instruction's source operand is marked renamable.</p>


<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a68b7b9c491045c788173e83be1ba5d2b">lowerCopy</a>.</p>

</div>
</div>

### createMIROperandComment() {#aea7fb8b18a37883f51af73238e47dea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string TargetInstrInfo::createMIROperandComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op, unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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



<p>Declaration at line 1623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1734 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a71b4b44c1ad06ba84d21d0be6c5c2276">llvm::InlineAsm::getExtraInfoNames</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#ade110db5cd02d02d8d11534fa679b52b">llvm::InlineAsm::getMemConstraintName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81895310467818e56fd11bbcbb64ee59">llvm::ARMBaseInstrInfo::createMIROperandComment</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#abe6772bd0f8b4b1bc3186473a7205dfe">llvm::RISCVInstrInfo::createMIROperandComment</a>.</p>

</div>
</div>

### createPHIDestinationCopy() {#a804530332064e8450f5c01c1291e3ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::createPHIDestinationCopy (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst)</td>
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

<p>During PHI eleimination lets target to make necessary checks and insert the copy to the PHI destination register in a target specific manner.</p>

<p>Definition at line 2088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aea3489e1fa192776df90b3f6b8e66511">llvm::SIInstrInfo::createPHIDestinationCopy</a>.</p>

</div>
</div>

### createPHISourceCopy() {#aaf9cd5e2258e984d377933b695ccf39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::createPHISourceCopy (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, unsigned SrcSubReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst)</td>
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

<p>During PHI eleimination lets target to make necessary checks and insert the copy to the PHI destination register in a target specific manner.</p>

<p>Definition at line 2098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a454f04c1cce23ff2b87305df8909ab33">llvm::SIInstrInfo::createPHISourceCopy</a>.</p>

</div>
</div>

### CreateTargetHazardRecognizer() {#a7242b69b2f705111801d717e2ea243b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * TargetInstrInfo::CreateTargetHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * DAG)</td>
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

<p>Allocate and return a hazard recognizer to use for this target when scheduling the machine instructions before register allocation.</p>

<p>Declaration at line 1701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1406 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a1b4105078d9414276e67bb58a5f27306">llvm::ARMBaseInstrInfo::CreateTargetHazardRecognizer</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8abe69762bb82834b786c78b35015734">llvm::PPCInstrInfo::CreateTargetHazardRecognizer</a>.</p>

</div>
</div>

### CreateTargetMIHazardRecognizer() {#a5da941cb7cfe3ae9b3dae1f5caac8b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * TargetInstrInfo::CreateTargetMIHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
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

<p>Allocate and return a hazard recognizer to use for this target when scheduling the machine instructions before register allocation.</p>

<p>Declaration at line 1707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7e340b4e4b4412f6808ff4270bfa6999">llvm::ARMBaseInstrInfo::CreateTargetMIHazardRecognizer</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a4ab6232188433548694ea1a9a98d542f">llvm::SIInstrInfo::CreateTargetMIHazardRecognizer</a>.</p>

</div>
</div>

### CreateTargetPostRAHazardRecognizer() {#a000bd55721d30de4fee9eb3d812714ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * TargetInstrInfo::CreateTargetPostRAHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * DAG)</td>
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

<p>Allocate and return a hazard recognizer to use for this target when scheduling the machine instructions after register allocation.</p>

<p>Declaration at line 1713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1420 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a624af1a09f6ec191f88dfd2b26c3e54a">llvm::ARMBaseInstrInfo::CreateTargetPostRAHazardRecognizer</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a1e16bf8c145a399b6a1b21015fecfd66">llvm::HexagonInstrInfo::CreateTargetPostRAHazardRecognizer</a>.</p>

</div>
</div>

### CreateTargetPostRAHazardRecognizer() {#a55d2e824f1b036f45b51519f2844720b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ScheduleHazardRecognizer * llvm::TargetInstrInfo::CreateTargetPostRAHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Allocate and return a hazard recognizer to use for by non-scheduling passes.</p>

<p>Definition at line 1719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### CreateTargetScheduleState() {#a186f383639b8c8fe141b55411d1121a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual DFAPacketizer * llvm::TargetInstrInfo::CreateTargetScheduleState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp;)</td>
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

<p>Create machine specific model for scheduling.</p>

<p>Definition at line 1967 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel/#a63d0e9315e9e0aba0008b5028a6c2044">llvm::VLIWResourceModel::createPacketizer</a>.</p>

</div>
</div>

### decomposeMachineOperandsTargetFlags() {#adf55430291b4f35540c9c7dfc28fedaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::pair&lt; unsigned, unsigned &gt; llvm::TargetInstrInfo::decomposeMachineOperandsTargetFlags (unsigned)</td>
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

<p>Decompose the machine operand's target flags into two values - the direct target flag value and any of bit flags that are applied.</p>

<p>Definition at line 2028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### defaultDefLatency() {#ae5424d7c9e608bd5b2087f1021908a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetInstrInfo::defaultDefLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SchedModel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the default expected latency for a def based on its opcode.</p>


<p>Return the default expected latency for a def based on it's opcode.</p>


<p>Declaration at line 1818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a26358cf24f3d0a23e6dee0bf807061be">llvm::MCSchedModel::HighLatency</a>, <a href="#aebbd8a676ca4d2926a87022815a5015d">isHighLatencyDef</a> and <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a077ff8557ccaf81471558635ca37f7a3">llvm::MCSchedModel::LoadLatency</a>.</p>

</div>
</div>

### describeLoadedValue() {#a6885e40448874565521daac98e11f50d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ParamLoadedValue &gt; TargetInstrInfo::describeLoadedValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Produce the expression describing the <span class="doxyComputerOutput">MI</span> loading a value into the physical register <span class="doxyComputerOutput">Reg</span>.</p>


<p>This hook should only be used with <span class="doxyComputerOutput">MIs</span> belonging to VReg-less functions.</p>


<p>Declaration at line 2229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a272fe723d8c234f2137d34621a5cef78">llvm::DIExpression::appendOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a6472489551b8960cc115a93d95eef9f6a4ce0a0358c0de36a6ea4413d7abcbca8">llvm::DIExpression::ApplyOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a308f77ae6a78f1164adfe7e1047cc25c">llvm::MachineMemOperand::getPseudoValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aacef05f16d3e71703f08bb4677e1d7a2">llvm::MachineFunctionProperties::hasProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a0b0401973fc9567440717a5d32a8eb8d">llvm::LocationSize::hasValue</a>, <a href="#ae4ac5c3f21740cf8f3f63e50de016209">isAddImmediate</a>, <a href="#ace5bb5eb8d13b5726f90e7f38df45d60">isCopyInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a6d4765e998667e7535ec89edbf0ff321">llvm::PseudoSourceValue::mayAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab804b15bb92ff685d7c1464b2816d608">llvm::DIExpression::prepend</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#af3a48df3735933cf1621760019e5fd8c">llvm::DIExpression::prependOpcodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7a1bb4352b705901de9836f44ad326f4">llvm::AArch64InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a9623871230b3a4317f06f55c576c404e">llvm::ARMBaseInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#ac9fa612919367a702574336b92a242d2">llvm::MipsInstrInfo::describeLoadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>.</p>

</div>
</div>

### duplicate() {#a8d5210bd68a86582390a6fbf1f57e319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; TargetInstrInfo::duplicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertBefore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Orig)</td>
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

<p>Clones instruction or the whole instruction bundle <span class="doxyComputerOutput">Orig</span> and insert into <span class="doxyComputerOutput">MBB</span> before <span class="doxyComputerOutput">InsertBefore</span>.</p>


<p>The target may update operands that are required to be unique.</p>


<p><span class="doxyComputerOutput">Orig</span> must not return true for <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a7ffc14f594434308433335d6b62ded60">MachineInstr::isNotDuplicable()</a>.</p>


<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3c50b05be0be83e693f50b87284c76d6">llvm::MachineFunction::cloneMachineInstrBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75489f444c9e3bdc12cb985c54d84a37">llvm::MachineInstr::isCFIInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a7ffc14f594434308433335d6b62ded60">llvm::MachineInstr::isNotDuplicable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab6fdf9b428bc3d57837022121c155cbf">llvm::Triple::isOSDarwin</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7a4e4e4a8fa157eb9945d44717359bb1">llvm::ARMBaseInstrInfo::duplicate</a>.</p>

</div>
</div>

### emitLdStWithAddr() {#aed830dc2b930795e75691f1efa942b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::emitLdStWithAddr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MemI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/extaddrmode">ExtAddrMode</a> &amp; AM)</td>
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

<p>Emit a load/store instruction with the same value register as <span class="doxyComputerOutput">MemI</span>, but using the address from <span class="doxyComputerOutput">AM</span>.</p>


<p>The addressing mode must have been obtained from <span class="doxyComputerOutput">canFoldIntoAddr</span> for the same memory instruction.</p>


<p>Definition at line 1543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### expandPostRAPseudo() {#aeeb52dce7ed6b6e3abc562031782d77d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::expandPostRAPseudo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>This function is called for all pseudo instructions that remain after register allocation.</p>


<p>Many pseudo instructions are created to help register allocation. This is the place to convert them into real instructions. The target can edit MI in place, or it can insert new instructions and erase MI. The function should return true if anything was changed.</p>


<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>.</p>

</div>
</div>

### extraSizeToPredicateInstructions() {#acc1d5ead030ed9216dedce5a9cc304ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::extraSizeToPredicateInstructions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned NumInsts)</td>
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

<p>Return the increase in code size needed to predicate a contiguous run of NumInsts instructions.</p>

<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### finalizeInsInstrs() {#a494876c94cb3dba51694356488a996dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::finalizeInsInstrs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, unsigned &amp; Pattern, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; InsInstrs)</td>
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

<p>Fix up the placeholder we may add in <a href="#a6875e5a149ffdf299b10e8f969d379d4">genAlternativeCodeSequence()</a>.</p>

<p>Definition at line 1252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### findCommutedOpIndices() {#a422b844cc7e3db360908c008cb651f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::findCommutedOpIndices (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; SrcOpIdx1, unsigned &amp; SrcOpIdx2)</td>
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

<p>Returns true iff the routine could find two commutable operands in the given machine instruction.</p>


<p>The 'SrcOpIdx1' and 'SrcOpIdx2' are INPUT and OUTPUT arguments. If any of the INPUT values is set to the special value 'CommuteAnyOperandIndex' then the method arbitrarily picks a commutable operand, then returns its index in the corresponding argument. If both of INPUT values are set to 'CommuteAnyOperandIndex' then method looks for 2 commutable operands. If INPUT values refer to some operands of MI, then the method simply returns true if the corresponding operands are commutable and returns false otherwise.</p>


<p>For example, calling this method this way: unsigned Op1 = 1, Op2 = CommuteAnyOperandIndex; findCommutedOpIndices(MI, Op1, Op2); can be interpreted as a query asking to find an operand that would be commutable with the operand#1.</p>


<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aef5b8db7ddf8b00b66e4f64711a053cd">fixCommutedOpIndices</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa41720cc33b0511709c92abcb164a59d">commuteInstruction</a>, <a href="#adf4d05c8ea2fc82ae12300ef5fb48951">commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#ac96f8a3940634f98f183e23e6ff35f7e">llvm::MipsInstrInfo::findCommutedOpIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#afadf8e95969c146a28e22d91218db770">llvm::PPCInstrInfo::findCommutedOpIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a2c3415ef8f310c64d20ff8772825e0b5">llvm::X86InstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### foldImmediate() {#aa41c45a69f227ee71e5ced4e6e3fde18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::foldImmediate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
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

<p>'Reg' is known to be defined by a move immediate instruction, try to fold the immediate into the use instruction.</p>


<p>If MRI-&gt;hasOneNonDBGUse(Reg) is true, and this function returns true, then the caller may assume that DefMI has been erased from its parent block. The caller may assume that it will not be erased by this function otherwise.</p>


<p>Definition at line 1768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### foldMemoryOperand() {#a6a733ae5364b0de2225af33223f383a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * TargetInstrInfo::foldMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Ops, int FI, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to fold a load or store of the specified stack slot into the specified machine instruction for the specified operand(s).</p>


<p>If this is possible, a new instruction is returned with the specified operand folded, otherwise NULL is returned. The new instruction is inserted before MI, and the client is responsible for removing the old instruction. If VRM is passed, the assigned physregs can be inspected by target to decide on using an opcode (note that those assignments can still change).</p>


<p>Declaration at line 1216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc4107c92fd8d37e8d0cb596f2a25d98">llvm::MachineInstr::addMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a848f5b2d82a5d809fe4785b96e6bdb95">canFoldCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa63ab5e3e1630ddb53a1a0def539a34c">llvm::MachineInstr::cloneInstrSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a9fcd68a333f3123b4b1cfb871ef3d89a">foldInlineAsmMemOperand</a>, <a href="#a0a1e73b39957ad3da60cb9d3a690df89">foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#ace5bb5eb8d13b5726f90e7f38df45d60">isCopyInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="#a9b1710394413e85110e485ec260c6a91">loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5981137a17cad3d9b2276ad63e15ee40">llvm::MachineInstr::setMemRefs</a>, <a href="#a6d3df2a0837fb3b75b9a0ac8f0923843">storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### foldMemoryOperand() {#a2432d0bb09d9fe3b6bb004d8dbf77a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * TargetInstrInfo::foldMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; LoadMI, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as the previous version except it allows folding of any load and store from / to any address, not just from a specific stack slot.</p>

<p>Declaration at line 1223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc4107c92fd8d37e8d0cb596f2a25d98">llvm::MachineInstr::addMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af1b9443e375680a7b849d56ab42e19d6">llvm::MachineInstr::canFoldAsLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a9fcd68a333f3123b4b1cfb871ef3d89a">foldInlineAsmMemOperand</a>, <a href="#a0a1e73b39957ad3da60cb9d3a690df89">foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a6922ec50633977be02ab221c2de2adc1">isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab37075d621acbbfc96ef2662f2e29883">llvm::MachineInstr::memoperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa5ff177bc1498508696aaf27235db3fc">llvm::MachineInstr::memoperands_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a4e9ab7e4e59e6a558a5b17757c1f17e9">llvm::MachineInstr::memoperands_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5981137a17cad3d9b2276ad63e15ee40">llvm::MachineInstr::setMemRefs</a>.</p>

</div>
</div>

### genAlternativeCodeSequence() {#a6875e5a149ffdf299b10e8f969d379d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::genAlternativeCodeSequence (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, unsigned Pattern, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; InsInstrs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DelInstrs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt; &amp; InstIdxForVirtReg)</td>
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

<p>When <a href="#a861381cad67866e249c6330631ac0742">getMachineCombinerPatterns()</a> finds patterns, this function generates the instructions that could replace the original code sequence.</p>


<p>The client has to decide whether the actual replacement is beneficial or not.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Root</td>
<td class="doxyParamItemDescription"><p>- <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that could be combined with one of its operands</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/pattern"&gt;Pattern&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- Combination pattern for Root</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsInstrs</td>
<td class="doxyParamItemDescription"><p>- Vector of new instructions that implement P</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DelInstrs</td>
<td class="doxyParamItemDescription"><p>- Old instructions, including Root, that could be replaced by InsInstr</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InstIdxForVirtReg</td>
<td class="doxyParamItemDescription"><p>- map of virtual register to instruction in InsInstr that defines it</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="#a99ccb406a2c930b241430e6b7b3d1a4f">getReassociateOperandIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#ae5e0c947b38bdebad23286c7764b5249">reassociateOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4e9ec39f5237e4efa0bc7bb0844c3867">llvm::PPCInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a4862e12e65a868264ab84a2252104dda">llvm::RISCVInstrInfo::genAlternativeCodeSequence</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a89e6ebae873e493658df7402f3e08a60">llvm::X86InstrInfo::genAlternativeCodeSequence</a>.</p>

</div>
</div>

### getAddrModeFromMemoryOp() {#a7ea0602dc926bed4a92bc63ae99e7cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; ExtAddrMode &gt; llvm::TargetInstrInfo::getAddrModeFromMemoryOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MemI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> dependent implementation to get the values constituting the address <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> that is accessing memory.</p>


<p>These values are returned as a struct <a href="/web-llvm/docs/api/structs/llvm/extaddrmode">ExtAddrMode</a> which contains all relevant information to make up the address.</p>


<p>Definition at line 1523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getBaseAndOffsetPosition() {#a28d18d91f58682d65e97e9c386064b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::getBaseAndOffsetPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; BasePos, unsigned &amp; OffsetPos)</td>
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

<p>Return true if the instruction contains a base register and offset.</p>


<p>If true, the function also sets the operand position in the instruction for the base register and offset.</p>


<p>Definition at line 1512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getBranchDestBlock() {#ab8ab946af55bc208ded5c21c11ff71c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineBasicBlock * llvm::TargetInstrInfo::getBranchDestBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The block that branch instruction <span class="doxyComputerOutput">MI</span> jumps to.</p></dd>
</dl>


<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getCalleeOperand() {#a9e8b374c12bde7a8aa400ae5e34e6956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MachineOperand &amp; llvm::TargetInstrInfo::getCalleeOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Returns the callee operand from the given <span class="doxyComputerOutput">MI</span>.</p>

<p>Definition at line 2261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getCallFrameDestroyOpcode() {#ab5a18bb895aa0c46d5de27c4ad046aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::getCallFrameDestroyOpcode ()</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a89e324da740d76918b3f2b2ecf807e49">getCallFrameSizeAt</a>, <a href="#a1e4f8b28a8543924e7e3e566a847e691">getSPAdjust</a> and <a href="#a524001439888743cdddb9b79c45911d9">isFrameInstr</a>.</p>

</div>
</div>

### getCallFrameSetupOpcode() {#a83870b05e73f275887a1e20baa621475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::getCallFrameSetupOpcode ()</td>
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

<p>These methods return the opcode of the frame setup/destroy instructions if they exist (-1 otherwise).</p>


<p>Some targets use pseudo instructions in order to abstract away the difference between operating with a frame pointer and operating without, through the use of these two instructions. A FrameSetup MI in MF implies MFI::AdjustsStack.</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a89e324da740d76918b3f2b2ecf807e49">getCallFrameSizeAt</a>, <a href="#a1e4f8b28a8543924e7e3e566a847e691">getSPAdjust</a>, <a href="#a524001439888743cdddb9b79c45911d9">isFrameInstr</a> and <a href="#ac9cc48fa5e52de97bef32acbb6f76ddc">isFrameSetup</a>.</p>

</div>
</div>

### getCallFrameSizeAt() {#a89e324da740d76918b3f2b2ecf807e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetInstrInfo::getCallFrameSizeAt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="#ab5a18bb895aa0c46d5de27c4ad046aee">getCallFrameDestroyOpcode</a>, <a href="#a83870b05e73f275887a1e20baa621475">getCallFrameSetupOpcode</a>, <a href="#aa0b59f9d1912a25fc5c03ae9b2ff960d">getFrameTotalSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

### getCatchReturnOpcode() {#a98a831626be0c6e512d6d95246891c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::getCatchReturnOpcode ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getCombinerObjective() {#adcf4712d0ec5fc344aa14efa9e5392b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CombinerObjective TargetInstrInfo::getCombinerObjective (unsigned Pattern)</td>
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

<p>Return the objective of a combiner pattern.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/pattern"&gt;Pattern&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- combiner pattern</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a878ef42ed9660dc3a739a37e056f845da7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ad35ff7ef57d009f7562e0b34d2148fc3">llvm::AArch64InstrInfo::getCombinerObjective</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4858f4a6ad5394064b204fd7f4550201">llvm::PPCInstrInfo::getCombinerObjective</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ae2e2455f0d0815c45beb6d1d36875cee">llvm::RISCVInstrInfo::getCombinerObjective</a>.</p>

</div>
</div>

### getConstValDefinedInReg() {#a820eea71d5b67cf63757e49e3c55736d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::getConstValDefinedInReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, int64_t &amp; ImmVal)</td>
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

<p>Returns true if MI is an instruction that defines Reg to have a constant value and the value is recorded in ImmVal.</p>


<p>The ImmVal is a result that should be interpreted as modulo size of Reg.</p>


<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getExecutionDomain() {#a907019eb40cf2db5f3a35cb0bc456347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::pair&lt; uint16_t, uint16_t &gt; llvm::TargetInstrInfo::getExecutionDomain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return the current execution domain and bit mask of possible domains for instruction.</p>


<p>Some micro-architectures have multiple execution domains, and multiple opcodes that perform the same operation in different domains. For example, the x86 architecture provides the por, orps, and orpd instructions that all do the same thing. There is a latency penalty if a register is written in one domain and read in another.</p>


<p>This function returns a pair (domain, mask) containing the execution domain of MI, and a bit mask of possible domains. The setExecutionDomain function can be used to change the opcode to one of the domains in the bit mask. Instructions whose execution domain can't be changed should return a 0 mask.</p>


<p>The execution domain numbers don't have any special meaning except domain 0 is used for instructions that are not associated with any interesting execution domain.</p>


<p>Definition at line 1869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getExtendResourceLenLimit() {#a55912dd5bde1306ca2642c4aebca197b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int llvm::TargetInstrInfo::getExtendResourceLenLimit ()</td>
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

<p>The limit on resource length extension we accept in MachineCombiner <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>.</p>

<p>Definition at line 1343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getExtractSubregInputs() {#af1743a67877bf4ba56d53b235d3573e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::getExtractSubregInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx">RegSubRegPairAndIdx</a> &amp; InputReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build the equivalent inputs of a EXTRACT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>.</p>


<p><span class="doxyComputerOutput"></span>[out] InputReg of the equivalent EXTRACT_SUBREG. E.g., EXTRACT_SUBREG %1:sub1, sub0, sub1 would produce:</p>


<ul class="doxyList ">
<li>%1:sub1, sub0</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build such an input sequence with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span> and the operand has no undef flag set. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isExtractSubreg() or MI.isExtractSubregLike().</p></dd>
</dl>



:::info
<p>The generic implementation does not provide any support for MI.isExtractSubregLike(). In other words, one has to override getExtractSubregLikeInputs for target specific instructions.</p>
:::


<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1680 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af1c44734f854fb7f620d16097f2af637">getExtractSubregLikeInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#aad7e848e562b1368d6ee4794d84957c6">llvm::TargetInstrInfo::RegSubRegPair::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#a7f62bad8eb5dce2e4a7d7518fc5c21ac">llvm::TargetInstrInfo::RegSubRegPairAndIdx::SubIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#a66f92cf2247d7b3c3a351ff48dd42d7d">llvm::TargetInstrInfo::RegSubRegPair::SubReg</a>.</p>

</div>
</div>

### getFrameIndexOperands() {#a0d10b938465726d85e01bbb669e184d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::getFrameIndexOperands (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Ops, int FI)</td>
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

<p>Fills in the necessary MachineOperands to refer to a frame index.</p>


<p>The best way to understand this is to print <span class="doxyComputerOutput">asm(""::"m"(x));</span> after finalize-isel. Example: INLINEASM ... 262190 /* mem:m *‍/, stack.0.x.addr, 1, $noreg, 0, $noreg we would add placeholders for: ^ ^ ^ ^</p>


<p>Definition at line 2288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getFrameSize() {#ab5c5ed9e614110e7cbdd8a4ab957ec06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TargetInstrInfo::getFrameSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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

<p>Returns size of the frame associated with the given frame instruction.</p>


<p>For frame setup instruction this is frame that is set up space set up after the instruction. For frame destroy instruction this is the frame freed by the caller. Note, in some cases a call frame (or a part of it) may be prepared prior to the frame setup instruction. It occurs in the calls that involve inalloca arguments. This function reports only the size of the frame part that is set up between the frame setup and destroy pseudo instructions.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a524001439888743cdddb9b79c45911d9">isFrameInstr</a>.</p>


<p>Referenced by <a href="#aa0b59f9d1912a25fc5c03ae9b2ff960d">getFrameTotalSize</a> and <a href="#a1e4f8b28a8543924e7e3e566a847e691">getSPAdjust</a>.</p>

</div>
</div>

### getFrameTotalSize() {#aa0b59f9d1912a25fc5c03ae9b2ff960d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TargetInstrInfo::getFrameTotalSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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

<p>Returns the total frame size, which is made up of the space set up inside the pair of frame start-stop instructions and the space that is set up prior to the pair.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab5c5ed9e614110e7cbdd8a4ab957ec06">getFrameSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ac9cc48fa5e52de97bef32acbb6f76ddc">isFrameSetup</a>.</p>


<p>Referenced by <a href="#a89e324da740d76918b3f2b2ecf807e49">getCallFrameSizeAt</a>.</p>

</div>
</div>

### getIncrementValue() {#af454ffcb2775e8a8abf663da93a0a438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::getIncrementValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; Value)</td>
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

<p>If the instruction is an increment of a constant value, return the amount.</p>

<p>Definition at line 1560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getInlineAsmLength() {#a65168b27efceb92102521e2bc82b8d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetInstrInfo::getInlineAsmLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI=nullptr)</td>
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

<p>Measure the specified inline asm to determine an approximation of its length.</p>


<p>Comments (which run till the next SeparatorString or newline) do not count as an instruction. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> other non-whitespace text is considered an instruction, with multiple instructions separated by SeparatorString or newlines. Variable-length instructions are not handled here; this function may be overloaded in the target code to do that. We implement a special case of the .space directive which takes only a single integer argument in base 10 that is the size in bytes. This is a restricted form of the GAS directive in that we only interpret simple–i.e. not a logical or arithmetic expression–size values without the optional fill value. This is primarily used for creating arbitrary sized inline asm blocks for testing purposes.</p>


<p>Declaration at line 1694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a2b7e615b4225eacdea39c80b2babfcf0">llvm::MCAsmInfo::getMaxInstLength</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aa37738ea69f4a3dc986397be99c66f24">llvm::MCAsmInfo::getSeparatorString</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a068e377306e2029f1a5e24504c1f9cb7">isAsmComment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

### getInsertSubregInputs() {#abea536f043de7994bc9b67c634a7c879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::getInsertSubregInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &amp; BaseReg, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx">RegSubRegPairAndIdx</a> &amp; InsertedReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build the equivalent inputs of a INSERT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>.</p>


<p><span class="doxyComputerOutput"></span>[out] BaseReg and <span class="doxyComputerOutput"></span>[out] InsertedReg contain the equivalent inputs of INSERT_SUBREG. E.g., INSERT_SUBREG %0:sub0, %1:sub1, sub3 would produce:</p>


<ul class="doxyList ">
<li>BaseReg: %0:sub0</li>
<li>InsertedReg: %1:sub1, sub3</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build such an input sequence with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span> and the operand has no undef flag set. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isInsertSubreg() or MI.isInsertSubregLike().</p></dd>
</dl>



:::info
<p>The generic implementation does not provide any support for MI.isInsertSubregLike(). In other words, one has to override getInsertSubregLikeInputs for target specific instructions.</p>
:::


<p>Declaration at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1705 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a2b51d2dd19b3859797509c03d5f451f1">getInsertSubregLikeInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#aad7e848e562b1368d6ee4794d84957c6">llvm::TargetInstrInfo::RegSubRegPair::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#a7f62bad8eb5dce2e4a7d7518fc5c21ac">llvm::TargetInstrInfo::RegSubRegPairAndIdx::SubIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#a66f92cf2247d7b3c3a351ff48dd42d7d">llvm::TargetInstrInfo::RegSubRegPair::SubReg</a>.</p>

</div>
</div>

### getInstrLatency() {#ac45af359a246cde99ce09578e3998985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetInstrInfo::getInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned * PredCost=nullptr)</td>
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

<p>Compute the instruction latency of a given instruction.</p>


<p>If the instruction has higher cost when predicated, it's returned via PredCost.</p>


<p>Declaration at line 1808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1506 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a51623c0621a7c092ac9210065f861a33">llvm::InstrItineraryData::getStageLatency</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getInstrLatency() {#a86ea143f1ea40632ba851badcf377101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetInstrInfo::getInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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



<p>Declaration at line 1814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a51623c0621a7c092ac9210065f861a33">llvm::InstrItineraryData::getStageLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#affe6bc9136f849e9b46fbccf620b3409">llvm::InstrItineraryData::isEmpty</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getInstructionUniformity() {#a9b400bea2e0c5c1d17478053b5acdd3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual InstructionUniformity llvm::TargetInstrInfo::getInstructionUniformity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return the uniformity behavior of the given instruction.</p>

<p>Definition at line 2267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getInstSizeInBytes() {#ad5c95e145de31fbd3c6269ebe1b615f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getInstSizeInBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Returns the size in bytes of the specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, or ~0U when this function is not implemented by a target.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ac0eb74bb20ce93168ed6fc663d997c30">predictBranchSizeForIfCvt</a>.</p>

</div>
</div>

### getInverseOpcode() {#ab0568ec903d0544ec11e0fb013d2fbe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; unsigned &gt; llvm::TargetInstrInfo::getInverseOpcode (unsigned Opcode)</td>
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

<p>Return the inverse operation opcode if it exists for \P Opcode (e.g.</p>


<p>add for sub and vice versa).</p>


<p>Definition at line 1280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a29e545675db8b534aec8eccb7bedb2ee">areOpcodesEqualOrInverse</a> and <a href="#a903e4ccbdb00b36a08f5e84a8010c3cd">getReassociationOpcodes</a>.</p>

</div>
</div>

### getJumpTableIndex() {#aa67b6d0847ff336198e7b56ecf022a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int llvm::TargetInstrInfo::getJumpTableIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return an index for <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo">MachineJumpTableInfo</a> if <span class="doxyComputerOutput">insn</span> is an indirect jump using a jump table, otherwise -1.</p>

<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getLiveRangeSplitOpcode() {#a6cf855363122e65fd4e6f2df1d16aba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getLiveRangeSplitOpcode (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Allows targets to use appropriate copy instruction while spilitting live range of a register in register allocation.</p>

<p>Definition at line 2080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getMachineCombinerPatterns() {#a861381cad67866e249c6330631ac0742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::getMachineCombinerPatterns (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Patterns, bool DoRegPressureReduce)</td>
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

<p>Return true when there is potentially a faster code sequence for an instruction chain ending in <span class="doxyComputerOutput">Root</span>.</p>


<p>All potential patterns are returned in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a></span> vector. <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> should be sorted in priority order since the pattern evaluator stops checking as soon as it finds a faster sequence.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Root</td>
<td class="doxyParamItemDescription"><p>- <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that could be combined with one of its operands</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Patterns</td>
<td class="doxyParamItemDescription"><p>- Vector of possible combination patterns</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="#ace9f804c4f1407df72588bb00db16deb">isReassociationCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da9b77519dc201611a2d982ef32b0c71f2">llvm::REASSOC_AX_BY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4dafd129ea7c5159e885a926375eb1e8de3">llvm::REASSOC_AX_YB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da651595de1269df92d8ab8fd174c000c8">llvm::REASSOC_XA_BY</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4daea1070ab8a6a63fd5d8957ed142e7f21">llvm::REASSOC_XA_YB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a2b3b6bff91628c24b2539a2733b3c292">llvm::AArch64InstrInfo::getMachineCombinerPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aea29efd6193842d296829d058dcd107a">llvm::PPCInstrInfo::getMachineCombinerPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ae92946bff8cb4ef04b71f5f6360e832e">llvm::RISCVInstrInfo::getMachineCombinerPatterns</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a0efa4ac98b741f2ab0520ab1d2f8a115">llvm::X86InstrInfo::getMachineCombinerPatterns</a>.</p>

</div>
</div>

### getMachineCombinerTraceStrategy() {#ae1778172912b443f67ccb9ee1af22776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTraceStrategy TargetInstrInfo::getMachineCombinerTraceStrategy ()</td>
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

<p>Return a strategy that MachineCombiner must use when creating traces.</p>

<p>Declaration at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a08fc515218c080e73909645fecb41ed0ab5435d2dc82cf75225dd888985989f5a">llvm::TS_MinInstrCount</a>.</p>

</div>
</div>

### getMachineCSELookAheadLimit() {#afa3c5e05e3b2eb5e8dd9c763efbdca4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getMachineCSELookAheadLimit ()</td>
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

<p>Return the value to use for the MachineCSE's LookAheadLimit, which is a heuristic used for CSE'ing phys reg defs.</p>

<p>Definition at line 1994 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getMemOperandAACheckLimit() {#a6f67bce035b491e5e6d95286ffe20da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getMemOperandAACheckLimit ()</td>
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

<p>Return the maximal number of alias checks on memory operands.</p>


<p>For instructions with more than one memory operands, the alias check on a single <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> pair has quadratic overhead and results in unacceptable performance in the worst case. The limit here is to clamp that maximal checks performed. Usually, that's the product of memory operand numbers from that pair of <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> to be checked. For instance, with two MachineInstrs with 4 and 5 memory operands correspondingly, a total of 20 checks are required. With this limit set to 16, their alias check is skipped. We choose to limit the product instead of the individual instruction as targets may have special MachineInstrs with a considerably high number of memory operands, such as <span class="doxyComputerOutput">ldm</span> in <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>. Setting this limit per <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> would result in either too high overhead or too rigid restriction.</p>


<p>Definition at line 2013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getMemOperandsWithOffsetWidth() {#ad562f15f35ef21a4965d1b9f522a360c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::getMemOperandsWithOffsetWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; &amp; BaseOps, int64_t &amp; Offset, bool &amp; OffsetIsScalable, <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &amp; Width, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Get zero or more base operands and the byte offset of an instruction that reads/writes memory.</p>


<p>Note that there may be zero base operands if the instruction accesses a constant address. It returns false if MI does not read/write memory. It returns false if base operands and offset could not be determined. It is not guaranteed to always recognize base operands and offsets in all cases. FIXME: Move Offset and OffsetIsScalable to some ElementCount-style abstraction that supports negative offsets.</p>


<p>Definition at line 1502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#afbbc2492f83b9a1b2b2b850283240272">getMemOperandWithOffset</a>.</p>

</div>
</div>

### getMemOperandWithOffset() {#afbbc2492f83b9a1b2b2b850283240272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::getMemOperandWithOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *&amp; BaseOp, int64_t &amp; Offset, bool &amp; OffsetIsScalable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the base operand and byte offset of an instruction that reads/writes memory.</p>


<p>This is a convenience function for callers that are only prepared to handle a single base operand. FIXME: Move Offset and OffsetIsScalable to some ElementCount-style abstraction that supports negative offsets.</p>


<p>Declaration at line 1488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="#ad562f15f35ef21a4965d1b9f522a360c">getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getMIRFormatter() {#a3492aff3468d2d229f1a093379fbdcf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MIRFormatter * llvm::TargetInstrInfo::getMIRFormatter ()</td>
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

<p>Return MIR formatter to format/parse MIR operands.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> can override this virtual function and return target specific MIR formatter.</p>


<p>Definition at line 2241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getNop() {#a8999c1de8a33ab1a9029e4852342e579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst TargetInstrInfo::getNop ()</td>
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

<p>Return the noop instruction to use for a noop.</p>

<p>Declaration at line 1606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getNumMicroOps() {#a16bf43322793449e23ced7810ac16ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetInstrInfo::getNumMicroOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return the number of u-operations the given machine instruction will be decoded to on the target cpu.</p>


<p>The itinerary's IssueWidth is the number of microops that can be dispatched each cycle. An instruction with zero microops takes no dispatch resources.</p>


<p>Declaration at line 1777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1475 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#affe6bc9136f849e9b46fbccf620b3409">llvm::InstrItineraryData::isEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#af1bc954cd72ba2c13fd0d00fd47343a9">llvm::InstrItineraryData::Itineraries</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/structs/llvm/instritinerary/#ab5722223e783802fc7c3cfb7cdd98025">llvm::InstrItinerary::NumMicroOps</a>.</p>

</div>
</div>

### getOpcodeAfterMemoryUnfold() {#a29b6d3fde7f1a20c72a6a7b4eeb4164f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getOpcodeAfterMemoryUnfold (unsigned Opc, bool UnfoldLoad, bool UnfoldStore, unsigned * LoadRegIndex=nullptr)</td>
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

<p>Returns the opcode of the would be new instruction after load / store are unfolded from an instruction of the specified opcode.</p>


<p>It returns zero if the specified unfolding is not possible. If LoadRegIndex is non-null, it is filled in with the operand index of the operand which will hold the register holding the loaded value.</p>


<p>Definition at line 1454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getOperandLatency() {#aa65c4a19ddc8ce7ddec084e5a1a4a62a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; TargetInstrInfo::getOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * DefNode, unsigned DefIdx, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * UseNode, unsigned UseIdx)</td>
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



<p>Declaration at line 1789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1444 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f96a3399d86d6f136aaa121de4217a3">llvm::SDNode::getMachineOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a0fb39c8a77b3091e6a569fe24055e06f">llvm::InstrItineraryData::getOperandCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a702e147674b97e4ec87922e263e1ca73">llvm::InstrItineraryData::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#affe6bc9136f849e9b46fbccf620b3409">llvm::InstrItineraryData::isEmpty</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1223d6e9a7dfb6e51299b894beccc679">llvm::SDNode::isMachineOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4cbbdd3795a958b1e24bd85cf48a0519">llvm::HexagonInstrInfo::getOperandLatency</a>.</p>

</div>
</div>

### getOperandLatency() {#a9b1e693dee703f46fd28221e99d4acff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; TargetInstrInfo::getOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, unsigned DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, unsigned UseIdx)</td>
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

<p>Compute and return the use operand latency of a given pair of def and use.</p>


<p>Both DefMI and UseMI must be valid.</p>


<p>In most cases, the static scheduling itinerary was enough to determine the operand latency. But it may not be possible for instructions with variable number of defs / uses.</p>


<p>This is a raw interface to the itinerary that may be directly overridden by a target. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> computeOperandLatency to get the best estimate of latency.</p>


<p>By default, call directly to the itinerary. This may be overriden by the target.</p>


<p>Declaration at line 1801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a702e147674b97e4ec87922e263e1ca73">llvm::InstrItineraryData::getOperandLatency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### getOutlinableRanges() {#a0028f0ee9f737ba5290254b7924accbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SmallVector&lt; std::pair&lt; MachineBasicBlock::iterator, MachineBasicBlock::iterator &gt; &gt; llvm::TargetInstrInfo::getOutlinableRanges (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned &amp; Flags)</td>
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

<p>Optional target hook which partitions <span class="doxyComputerOutput">MBB</span> into outlinable ranges for instruction mapping purposes.</p>


<p>Each range is defined by two iterators: [start, end).</p>


<p>Ranges are expected to be ordered top-down. That is, ranges closer to the top of the block should come before ranges closer to the end of the block.</p>


<p>Ranges cannot overlap.</p>


<p>If an entire block is mappable, then its range is [MBB.begin(), MBB.end())</p>


<p>All instructions not present in an outlinable range are considered illegal.</p>


<p>Definition at line 2162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### getOutliningCandidateInfo() {#aae4e1b8b82113ab0848fe7e4e3a2574f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; std::unique_ptr&lt; outliner::OutlinedFunction &gt; &gt; llvm::TargetInstrInfo::getOutliningCandidateInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &gt; &amp; RepeatedSequenceLocs, unsigned MinRepeats)</td>
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

<p>Returns a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">outliner::OutlinedFunction</a></span> struct containing target-specific information for a set of outlining candidates.</p>


<p>Returns std::nullopt if the candidates are not suitable for outlining. <span class="doxyComputerOutput">MinRepeats</span> is the minimum number of times the instruction sequence must be repeated.</p>


<p>Definition at line 2112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getOutliningType() {#a3034fb1c96df7c2c8f52f11c8fc82467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">outliner::InstrType TargetInstrInfo::getOutliningType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MIT, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns how or if <span class="doxyComputerOutput">MIT</span> should be outlined.</p>


<p><span class="doxyComputerOutput">Flags</span> is the target-specific information returned by isMBBSafeToOutlineFrom.</p>


<p>Declaration at line 2138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1815 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2af67652d97de393fd3208c625cea6b1">getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52a795f5ad85ed392b65a70b46dacaeef34">llvm::outliner::Illegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52add798e74afcdf046a9a39e477261ab0e">llvm::outliner::Invisible</a>, <a href="#abda2e966ced4c77ce8a78e5e063e07cd">isPredicated</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getPartialRegUpdateClearance() {#a14308e147ea57526f7fd1198ab551a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getPartialRegUpdateClearance (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Returns the preferred minimum clearance before an instruction with an unwanted partial register update.</p>


<p>Some instructions only write part of a register, and implicitly need to read the other parts of the register. This may cause unwanted stalls preventing otherwise unrelated instructions from executing in parallel in an out-of-order CPU.</p>


<p>For example, the x86 instruction cvtsi2ss writes its result to bits [31:0] of the destination xmm register. Bits [127:32] are unaffected, so the instruction needs to wait for the old value of the register to become available:</p>


<p>addps xmm1, xmm0 movaps xmm0, (rax) cvtsi2ss rbx, xmm0</p>


<p>In the code above, the cvtsi2ss instruction needs to wait for the addps instruction before it can issue, even though the high bits of xmm0 probably aren't needed.</p>


<p>This hook returns the preferred clearance before MI, measured in instructions. Other defs of MI's operand OpNum are avoided in the last N instructions before MI. It should only return a positive value for unwanted dependencies. If the old bits of the defined register have useful values, or if MI is determined to otherwise read the dependency, the hook should return 0.</p>


<p>The unwanted dependency may be handled by:</p>


<ol class="doxyList" type="1">
<li>Allocating the same register for an MI def and use. That makes the unwanted dependency identical to a required dependency.</li>
<li>Allocating a register for the def that has no defs in the previous N instructions.</li>
<li>Calling <a href="#a525a9aaabc1362deb245b0099ea5538e">breakPartialRegDependency()</a> with the same arguments. This allows the target to insert a dependency breaking instruction.</li>
</ol>

<p>Definition at line 1919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getPatchpointUnfoldableRange() {#a34a028c45f323009b51ef27c5f5814a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; TargetInstrInfo::getPatchpointUnfoldableRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>For a patchpoint, stackmap, or statepoint intrinsic, return the range of operands which can't be folded into stack references.</p>


<p>Operands outside of the range are most likely foldable but it is not guaranteed. These instructions are unique in that stack references for some operands have the same execution cost (e.g. none) as the unfolded register forms. The ranged return is guaranteed to include all operands which can't be folded at zero cost.</p>


<p>Declaration at line 1206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getPredicationCost() {#ad89d6efd5d16c7e44f26ef26296e13aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetInstrInfo::getPredicationCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 1812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>

</div>
</div>

### getReassociateOperandIndices() {#a99ccb406a2c930b241430e6b7b3d1a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::getReassociateOperandIndices (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, unsigned Pattern, std::array&lt; unsigned, 5 &gt; &amp; OperandIndices)</td>
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

<p>The returned array encodes the operand index for each parameter because the operands may be commuted; the operand indices for associative operations might also be target-specific.</p>


<p>Each element specifies the index of {Prev, A, B, X, Y}.</p>


<p>Declaration at line 1323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da9b77519dc201611a2d982ef32b0c71f2">llvm::REASSOC_AX_BY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4dafd129ea7c5159e885a926375eb1e8de3">llvm::REASSOC_AX_YB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da651595de1269df92d8ab8fd174c000c8">llvm::REASSOC_XA_BY</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4daea1070ab8a6a63fd5d8957ed142e7f21">llvm::REASSOC_XA_YB</a>.</p>


<p>Referenced by <a href="#a6875e5a149ffdf299b10e8f969d379d4">genAlternativeCodeSequence</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6c14f246ebdc035b01f2c56df0b7ce89">llvm::RISCVInstrInfo::getReassociateOperandIndices</a>.</p>

</div>
</div>

### getReassociationOpcodes() {#a903e4ccbdb00b36a08f5e84a8010c3cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; TargetInstrInfo::getReassociationOpcodes (unsigned Pattern, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Prev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reassociation of some instructions requires inverse operations (e.g.</p>


<p>(X + A) - Y =&gt; (X - Y) + A). This method returns a pair of new opcodes (new root opcode, new prev opcode) that must be used to reassociate \P Root and \P Prev accoring to \P <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a>.</p>


<p>Declaration at line 1339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="#a29e545675db8b534aec8eccb7bedb2ee">areOpcodesEqualOrInverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab0568ec903d0544ec11e0fb013d2fbe2">getInverseOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#aa792b566fb2d8e29af95aea690e33201">isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da9b77519dc201611a2d982ef32b0c71f2">llvm::REASSOC_AX_BY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4dafd129ea7c5159e885a926375eb1e8de3">llvm::REASSOC_AX_YB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da651595de1269df92d8ab8fd174c000c8">llvm::REASSOC_XA_BY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4daea1070ab8a6a63fd5d8957ed142e7f21">llvm::REASSOC_XA_YB</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#ae5e0c947b38bdebad23286c7764b5249">reassociateOps</a>.</p>

</div>
</div>

### getRegClass() {#af81ceec76ff4ca95f29b037c28a54ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * TargetInstrInfo::getRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; MCID, unsigned OpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Given a machine instruction descriptor, returns the register class constraint for OpNum, or NULL.</p>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a1829580bbe3650b4649ba6094604e0fb">llvm::X86InstrInfo::getRegClass</a>.</p>

</div>
</div>

### getRegSequenceInputs() {#ae26cac7943070f09b4d7fa667d1adf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::getRegSequenceInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx">RegSubRegPairAndIdx</a> &gt; &amp; InputRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build the equivalent inputs of a REG_SEQUENCE for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>.</p>


<p><span class="doxyComputerOutput"></span>[out] InputRegs of the equivalent REG_SEQUENCE. Each element of the list is modeled as &lt;Reg:SubReg, SubIdx&gt;. Operands with the undef flag are not added to this list. E.g., REG_SEQUENCE %1:sub1, sub0, %2, sub1 would produce two elements:</p>


<ul class="doxyList ">
<li>%1:sub1, sub0</li>
<li>%2&lt;:0&gt;, sub1</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build such an input sequence with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span>. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isRegSequence() or MI.isRegSequenceLike().</p></dd>
</dl>



:::info
<p>The generic implementation does not provide any support for MI.isRegSequenceLike(). In other words, one has to override getRegSequenceLikeInputs for target specific instructions.</p>
:::


<p>Declaration at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a52e026925b73de52f7a563693ebff007">getRegSequenceLikeInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getReturnOpcode() {#a6150cd07e9535b7e02d53953a1a54cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::getReturnOpcode ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getSerializableBitmaskMachineOperandTargetFlags() {#a82ef2aeaba3f310827d58a0a3b16cfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArrayRef&lt; std::pair&lt; unsigned, const char * &gt; &gt; llvm::TargetInstrInfo::getSerializableBitmaskMachineOperandTargetFlags ()</td>
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

<p>Return an array that contains the bitmask target flag values and their names.</p>


<p>MIR Serialization is able to serialize only the target flags that are defined by this method.</p>


<p>Definition at line 2048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getSerializableDirectMachineOperandTargetFlags() {#aefb630da1cbdfc0d8425933e20b37a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArrayRef&lt; std::pair&lt; unsigned, const char * &gt; &gt; llvm::TargetInstrInfo::getSerializableDirectMachineOperandTargetFlags ()</td>
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

<p>Return an array that contains the direct target flag values and their names.</p>


<p>MIR Serialization is able to serialize only the target flags that are defined by this method.</p>


<p>Definition at line 2038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getSerializableMachineMemOperandTargetFlags() {#a27e0bf9b6a35f938342ed56dfcfe7786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArrayRef&lt; std::pair&lt; MachineMemOperand::Flags, const char * &gt; &gt; llvm::TargetInstrInfo::getSerializableMachineMemOperandTargetFlags ()</td>
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

<p>Return an array that contains the MMO target flag values and their names.</p>


<p>MIR Serialization is able to serialize only the MMO target flags that are defined by this method.</p>


<p>Definition at line 2058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getSerializableTargetIndices() {#a3d3166a8e59fbea4a6f27fefd6a8fea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArrayRef&lt; std::pair&lt; int, const char * &gt; &gt; llvm::TargetInstrInfo::getSerializableTargetIndices ()</td>
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

<p>Return an array that contains the ids of the target indices (used for the TargetIndex machine operand) and their names.</p>


<p>MIR Serialization is able to serialize only the target indices that are defined by this method.</p>


<p>Definition at line 2021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getSPAdjust() {#a1e4f8b28a8543924e7e3e566a847e691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int TargetInstrInfo::getSPAdjust (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Returns the actual stack pointer adjustment made by an instruction as part of a call sequence.</p>


<p>By default, only call frame setup/destroy instructions adjust the stack, but targets may want to override this to enable more fine-grained adjustment, or adjust by a different value.</p>


<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#ac54cd9ae6b849b3a2fd1fe982f9d09e2">llvm::TargetFrameLowering::alignSPAdjust</a>, <a href="#ab5a18bb895aa0c46d5de27c4ad046aee">getCallFrameDestroyOpcode</a>, <a href="#a83870b05e73f275887a1e20baa621475">getCallFrameSetupOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ac83b44e69c9f9f4f9d60be2d72f4a5df">llvm::TargetSubtargetInfo::getFrameLowering</a>, <a href="#ab5c5ed9e614110e7cbdd8a4ab957ec06">getFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#aa76eab97e3072a1ebd4bf1ff00d19423">llvm::TargetFrameLowering::getStackGrowthDirection</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a524001439888743cdddb9b79c45911d9">isFrameInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a>.</p>

</div>
</div>

### getStackSlotRange() {#a5cf58df95b00905950bdfee515cd5e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::getStackSlotRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned SubIdx, unsigned &amp; Size, unsigned &amp; Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Compute the size in bytes and offset within a stack slot of a spilled register or subregister.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Size</td>
<td class="doxyParamItemDescription"><p>in bytes of the spilled value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Offset</td>
<td class="doxyParamItemDescription"><p>in bytes within the stack slot.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if both Size and Offset are successfully computed.</p></dd>
</dl>


<p>Not all subregisters have computable spill slots. For example, subregisters registers may not be byte-sized, and a pair of discontiguous subregisters has no single offset.</p>


<p>Targets with nontrivial bigendian implementations may need to override this, particularly to support spilled vector registers.</p>


<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getTailDuplicateSize() {#af1fbe2cfd4ac1e373cdaba16ec4a70b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getTailDuplicateSize (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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

<p>Returns the target-specific default value for tail duplication.</p>


<p>This value will be used if the tail-dup-placement-threshold argument is not provided.</p>


<p>Definition at line 2250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>.</p>

</div>
</div>

### getTailMergeSize() {#a9acee94fe64ebb7dc672f6e5697fbe6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getTailMergeSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Returns the target-specific default value for tail merging.</p>


<p>This value will be used if the tail-merge-size argument is not provided.</p>


<p>Definition at line 2256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getUndefRegClearance() {#a4159fd0062dd97fe920f738c776a7356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::getUndefRegClearance (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Return the minimum clearance before an instruction that reads an unused register.</p>


<p>For example, AVX instructions may copy part of a register operand into the unused high bits of the destination register.</p>


<p>vcvtsi2sdq rax, undef xmm0, xmm14</p>


<p>In the code above, vcvtsi2sdq copies xmm0[127:64] into xmm14 creating a false dependence on any previous write to xmm0.</p>


<p>This hook works similarly to getPartialRegUpdateClearance, except that it does not take an operand index. Instead sets <span class="doxyComputerOutput">OpNum</span> to the index of the unused register.</p>


<p>Definition at line 1939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### hasCommutePreference() {#ae698a81cf1a8b23582f2964f57581dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::hasCommutePreference (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool &amp; Commute)</td>
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

<p>Returns true if the target has a preference on the operands order of the given machine instruction.</p>


<p>And specify if <span class="doxyComputerOutput">Commute</span> is required to get the desired operands order.</p>


<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### hasHighOperandLatency() {#a4993bfe73a55f4fcc5d02d09c410ddaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::hasHighOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> &amp; SchedModel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, unsigned DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, unsigned UseIdx)</td>
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

<p>Compute operand latency between a def of 'Reg' and a use in the current loop.</p>


<p>Return true if the target considered it 'high'. This is used by optimization passes such as machine LICM to determine whether it makes sense to hoist an instruction out even in a high register pressure situation.</p>


<p>Definition at line 1829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### hasLoadFromStackSlot() {#ae3c237cad94f54f0d82a18a131709d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::hasLoadFromStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt; &amp; Accesses)</td>
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

<p>If the specified machine instruction has a load from a stack slot, return true along with the FrameIndices of the loaded stack slot and the machine mem operands containing the reference.</p>


<p>If not, return false. Unlike isLoadFromStackSlot, this returns true for any instructions that loads from the stack. This is just a hint, as some cases may be missed.</p>


<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ae5a58b66599853918ad0f91f8b5baf11">llvm::HexagonInstrInfo::hasLoadFromStackSlot</a>.</p>

</div>
</div>

### hasLowDefLatency() {#a0aa73253579dd1c4acde85953454e838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::hasLowDefLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> &amp; SchedModel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, unsigned DefIdx)</td>
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

<p>Compute operand latency of a def of 'Reg'.</p>


<p>Return true if the target considered it 'low'.</p>


<p>Declaration at line 1839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#af1cd45c8a7d602373b7da7b5e00527d1">llvm::TargetSchedModel::getInstrItineraries</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a0fb39c8a77b3091e6a569fe24055e06f">llvm::InstrItineraryData::getOperandCycle</a> and <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#affe6bc9136f849e9b46fbccf620b3409">llvm::InstrItineraryData::isEmpty</a>.</p>

</div>
</div>

### hasReassociableOperands() {#a6034cfb230c4698caa60bdc3a9bf209b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::hasReassociableOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Return true when \P Inst has reassociable operands in the same \P MBB.</p>

<p>Declaration at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab7919507c578187e698ff01a1f204478">llvm::RISCVInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf735f22db2a6cb417e73392e0934bb1">llvm::X86InstrInfo::hasReassociableOperands</a>, <a href="#aea784a4f9e9aba7792c23484e2498e8d">hasReassociableSibling</a> and <a href="#ace9f804c4f1407df72588bb00db16deb">isReassociationCandidate</a>.</p>

</div>
</div>

### hasReassociableSibling() {#aea784a4f9e9aba7792c23484e2498e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::hasReassociableSibling (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, bool &amp; Commuted)</td>
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

<p>Return true when \P Inst has reassociable sibling.</p>

<p>Declaration at line 1292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="#a29e545675db8b534aec8eccb7bedb2ee">areOpcodesEqualOrInverse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a6034cfb230c4698caa60bdc3a9bf209b">hasReassociableOperands</a>, <a href="#aa792b566fb2d8e29af95aea690e33201">isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2f1cfe9c040112cbf97a025655d3595e">llvm::RISCVInstrInfo::hasReassociableSibling</a> and <a href="#ace9f804c4f1407df72588bb00db16deb">isReassociationCandidate</a>.</p>

</div>
</div>

### hasStoreToStackSlot() {#a5df2834716ee814af9f2555897ecb932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::hasStoreToStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt; &amp; Accesses)</td>
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

<p>If the specified machine instruction has a store to a stack slot, return true along with the FrameIndices of the loaded stack slot and the machine mem operands containing the reference.</p>


<p>If not, return false. Unlike isStoreToStackSlot, this returns true for any instructions that stores to the stack. This is just a hint, as some cases may be missed.</p>


<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6298fe18896dd895703bad238f9ad632">llvm::HexagonInstrInfo::hasStoreToStackSlot</a>.</p>

</div>
</div>

### insertBranch() {#a762db1f75e789783b689f22cda71bad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::insertBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int * BytesAdded=nullptr)</td>
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

<p>Insert branch code into the end of the specified <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>The operands to this method are the same as those returned by analyzeBranch. This is only invoked in cases where analyzeBranch returns success. It returns the number of instructions inserted. If <span class="doxyComputerOutput">BytesAdded</span> is non-null, report the change in code size from the added instructions.</p>


<p>It is also invoked by tail merging to add unconditional branches in cases where analyzeBranch doesn't apply because there was no original branch to analyze. At least this much must be implemented, else tail merging needs to be disabled.</p>


<p>The CFG information in MBB.Predecessors and MBB.Successors must be valid before calling this function.</p>


<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>


<p>Referenced by <a href="#af382bec94f69d7c5fba1e67e62e6e6da">insertUnconditionalBranch</a> and <a href="#a26e9655e762686aff18772a15139df27">ReplaceTailWithBranchTo</a>.</p>

</div>
</div>

### insertIndirectBranch() {#a25b07e0819e160f78c33a67838dea35c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::insertIndirectBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; NewDestBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; RestoreBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int64_t BrOffset=0, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
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

<p>Insert an unconditional indirect branch at the end of <span class="doxyComputerOutput">MBB</span> to <span class="doxyComputerOutput">NewDestBB</span>.</p>


<p>Optionally, insert the clobbered register restoring in <span class="doxyComputerOutput">RestoreBB</span>. <span class="doxyComputerOutput">BrOffset</span> indicates the offset of <span class="doxyComputerOutput">NewDestBB</span> relative to the offset of the position to insert the new branch.</p>


<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### insertNoop() {#a4ee57d5d6295dfeb44f3b55301b20020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::insertNoop (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
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

<p>Insert a noop into the instruction stream at the specified point.</p>


<p>insertNoop - Insert a noop into the instruction stream at the specified point.</p>


<p>Declaration at line 1597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad42ea8aa2115313dc7f1b793b049e0b1">llvm::avoidZeroOffsetLandingPad</a> and <a href="#ab2c15ac4d0e9521ba7225f100f657639">insertNoops</a>.</p>

</div>
</div>

### insertNoops() {#ab2c15ac4d0e9521ba7225f100f657639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::insertNoops (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, unsigned Quantity)</td>
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

<p>Insert noops into the instruction stream at the specified point.</p>


<p>insertNoops - Insert noops into the instruction stream at the specified point.</p>


<p>Declaration at line 1601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="#a4ee57d5d6295dfeb44f3b55301b20020">insertNoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### insertOutlinedCall() {#ab00242d76e808398358fa1e46e9a6885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineBasicBlock::iterator llvm::TargetInstrInfo::insertOutlinedCall (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; It, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &amp; C)</td>
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

<p>Insert a call to an outlined function into the program.</p>


<p>Returns an iterator to the spot where we inserted the call. This must be implemented by the target.</p>


<p>Definition at line 2177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### insertSelect() {#a57cd943142f3f93cebdab2134714793b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::insertSelect (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TrueReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FalseReg)</td>
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

<p>Insert a select instruction into MBB before I that will copy TrueReg to DstReg when Cond is true, and FalseReg to DstReg when Cond is false.</p>


<p>This function can only be called after <a href="#ae0990ac346653cb1c820f391ffbf5ed5">canInsertSelect()</a> returned true. The condition in Cond comes from analyzeBranch, and it can be assumed that the same flags or registers required by Cond are available at the insertion point.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBB</td>
<td class="doxyParamItemDescription"><p>Block where select instruction should be inserted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>Insertion point.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Source location for debugging.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DstReg</td>
<td class="doxyParamItemDescription"><p>Virtual register to be defined by select instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Cond</td>
<td class="doxyParamItemDescription"><p>Condition as computed by analyzeBranch.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TrueReg</td>
<td class="doxyParamItemDescription"><p>Virtual register to copy when Cond is true.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FalseReg</td>
<td class="doxyParamItemDescription"><p>Virtual register to copy when Cons is false.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### insertUnconditionalBranch() {#af382bec94f69d7c5fba1e67e62e6e6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::insertUnconditionalBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DestBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int * BytesAdded=nullptr)</td>
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



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a762db1f75e789783b689f22cda71bad4">insertBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### isAddImmediate() {#ae4ac5c3f21740cf8f3f63e50de016209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; RegImmPair &gt; llvm::TargetInstrInfo::isAddImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>If the specific machine instruction is an instruction that adds an immediate value and a register, and stores the result in the given register <span class="doxyComputerOutput">Reg</span>, return a pair of the source register and the offset which has been added.</p>

<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a6885e40448874565521daac98e11f50d">describeLoadedValue</a>.</p>

</div>
</div>

### isAsCheapAsAMove() {#a9c5e9ccab2a323465af64b3661172af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isAsCheapAsAMove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true if the instruction is as cheap as a move instruction.</p>


<p>Targets for different archs need to override this, and different micro-architectures can also be finely tuned inside.</p>


<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isAssociativeAndCommutative() {#aa792b566fb2d8e29af95aea690e33201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isAssociativeAndCommutative (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, bool Invert=false)</td>
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

<p>Return true when \P Inst is both associative and commutative.</p>


<p>If \P Invert is true, then the inverse of \P Inst operation must be tested.</p>


<p>Definition at line 1273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a903e4ccbdb00b36a08f5e84a8010c3cd">getReassociationOpcodes</a>, <a href="#aea784a4f9e9aba7792c23484e2498e8d">hasReassociableSibling</a> and <a href="#ace9f804c4f1407df72588bb00db16deb">isReassociationCandidate</a>.</p>

</div>
</div>

### isBasicBlockPrologue() {#a0138c08492e75b8b22f8fe0764b95853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isBasicBlockPrologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>())</td>
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

<p>True if the instruction is bound to the top of its basic block and no other instructions shall be inserted before it.</p>


<p>This can be implemented to prevent register allocator to insert spills for <span class="doxyComputerOutput">Reg</span> before such instructions.</p>


<p>Definition at line 2073 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### isBranchOffsetInRange() {#a6073542a939859dd8831f4cf9d710393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isBranchOffsetInRange (unsigned BranchOpc, int64_t BrOffset)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a branch from an instruction with opcode <span class="doxyComputerOutput">BranchOpc</span> bytes is capable of jumping to a position <span class="doxyComputerOutput">BrOffset</span> bytes away.</p></dd>
</dl>


<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isCoalescableExtInstr() {#a236fc00ef404f232dcd8b88bbf3a2251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isCoalescableExtInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; DstReg, unsigned &amp; SubIdx)</td>
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

<p>Return true if the instruction is a "coalescable" extension instruction.</p>


<p>That is, it's like a copy where it's legal for the source to overlap the destination. e.g. X86::MOVSX64rr32. If this returns true, then it's expected the pre-extension value is available as a subreg of the result register. This also returns the sub-register index in SubIdx.</p>


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isCopyInstr() {#ace5bb5eb8d13b5726f90e7f38df45d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DestSourcePair &gt; llvm::TargetInstrInfo::isCopyInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>If the specific machine instruction is a instruction that moves/copies value from one register to another register return destination and source registers as machine operands.</p>


<p>For COPY-instruction the method naturally returns destination and source registers as machine operands, for all other instructions the method calls target-dependent implementation.</p>


<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#a7eb5f369839e0987506e72b0ffc1b982">isCopyInstrImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a6885e40448874565521daac98e11f50d">describeLoadedValue</a>, <a href="#a6a733ae5364b0de2225af33223f383a5">foldMemoryOperand</a>, <a href="#a82dd4c26bf1be527376323f5c9889fbd">isCopyLikeInstr</a> and <a href="#a407338aee0ea958defdef5cb3993f1da">isFullCopyInstr</a>.</p>

</div>
</div>

### isCopyLikeInstr() {#a82dd4c26bf1be527376323f5c9889fbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DestSourcePair &gt; llvm::TargetInstrInfo::isCopyLikeInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#ace5bb5eb8d13b5726f90e7f38df45d60">isCopyInstr</a>, <a href="#a13cf72d93ee18d693c7a74f0c1307cea">isCopyLikeInstrImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isExplicitTargetIndexDef() {#aa87a4a6ef69b65a33d072718a8e0e25e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isExplicitTargetIndexDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; Index, int64_t &amp; Offset)</td>
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

<p>Returns true if the given <span class="doxyComputerOutput">MI</span> defines a TargetIndex operand that can be tracked by their offset, can have values, and can have debug info associated with it.</p>


<p>If so, sets <span class="doxyComputerOutput">Index</span> and <span class="doxyComputerOutput">Offset</span> of the target index operand.</p>


<p>Definition at line 2275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### isExtendLikelyToBeFolded() {#a0ec0a63c3d6d45dd9fee9c1115816e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isExtendLikelyToBeFolded (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; ExtMI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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

<p>Given the generic extension instruction <span class="doxyComputerOutput">ExtMI</span>, returns true if this extension is a likely candidate for being folded into an another instruction.</p>

<p>Definition at line 2234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isFrameInstr() {#a524001439888743cdddb9b79c45911d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isFrameInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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

<p>Returns true if the argument is a frame pseudo instruction.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#ab5a18bb895aa0c46d5de27c4ad046aee">getCallFrameDestroyOpcode</a>, <a href="#a83870b05e73f275887a1e20baa621475">getCallFrameSetupOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ab5c5ed9e614110e7cbdd8a4ab957ec06">getFrameSize</a> and <a href="#a1e4f8b28a8543924e7e3e566a847e691">getSPAdjust</a>.</p>

</div>
</div>

### isFrameSetup() {#ac9cc48fa5e52de97bef32acbb6f76ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isFrameSetup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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

<p>Returns true if the argument is a frame setup pseudo instruction.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#a83870b05e73f275887a1e20baa621475">getCallFrameSetupOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aa0b59f9d1912a25fc5c03ae9b2ff960d">getFrameTotalSize</a>.</p>

</div>
</div>

### isFullCopyInstr() {#a407338aee0ea958defdef5cb3993f1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isFullCopyInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="#ace5bb5eb8d13b5726f90e7f38df45d60">isCopyInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isFunctionSafeToOutlineFrom() {#a6fd9a0614742c8f6c8523b0c34b984ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isFunctionSafeToOutlineFrom (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool OutlineFromLinkOnceODRs)</td>
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

<p>Return true if the function can safely be outlined from.</p>


<p>A function <span class="doxyComputerOutput">MF</span> is considered safe for outlining if an outlined function produced from instructions in F will produce a program which produces the same output for any set of given inputs.</p>


<p>Definition at line 2203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isFunctionSafeToSplit() {#ae0b0cbf92a3dd0f5cab9d5d3067c2003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isFunctionSafeToSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return true if the function is a viable candidate for machine function splitting.</p>


<p>The criteria for if a function can be split may vary by target.</p>


<p>Declaration at line 2216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1530 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a11ab3c8bd6ff4445d7cb45a62806353b">llvm::Function::getSectionPrefix</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ade7dc7510e950cd1c1181138b390f965">llvm::GlobalObject::hasSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aab2bb29af5f95ecde069091fc13e0dd9">llvm::AArch64InstrInfo::isFunctionSafeToSplit</a>.</p>

</div>
</div>

### isGlobalMemoryObject() {#ae46a80302699b257d06337de4b804a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isGlobalMemoryObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Returns true if MI is an instruction we are unable to reason about (like a call or something with unmodeled side effects).</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1921 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6b8aa29292db7fc2337041ca50f795ed">llvm::SIInstrInfo::isGlobalMemoryObject</a>.</p>

</div>
</div>

### isHighLatencyDef() {#aebbd8a676ca4d2926a87022815a5015d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isHighLatencyDef (int opc)</td>
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

<p>Return true if this opcode has high latency to its result.</p>

<p>Definition at line 1822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#ae5424d7c9e608bd5b2087f1021908a08">defaultDefLatency</a>.</p>

</div>
</div>

### isIgnorableUse() {#a6832cbbc9c9e128eed4484026c539781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isIgnorableUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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

<p>Given <span class="doxyComputerOutput">MO</span> is a PhysReg use return if it can be ignored for the purpose of instruction rematerialization or sinking.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isLegalToSplitMBBAt() {#afa8e907121203db549a15f70f615ef50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isLegalToSplitMBBAt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI)</td>
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

<p>Return true if it's legal to split the given basic block at the specified instruction (i.e.</p>


<p>instruction would be the start of a new basic block).</p>


<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>.</p>

</div>
</div>

### isLoadFromStackSlot() {#a6922ec50633977be02ab221c2de2adc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::TargetInstrInfo::isLoadFromStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
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

<p>If the specified machine instruction is a direct load from a stack slot, return the virtual or physical register number of the destination along with the FrameIndex of the loaded stack slot.</p>


<p>If not, return 0. This predicate must return 0 if the instruction has any side effects other than loading from the stack slot.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2432d0bb09d9fe3b6bb004d8dbf77a99">foldMemoryOperand</a>, <a href="#afb62c4d3c76506ef7a31dc75f98000db">isLoadFromStackSlot</a> and <a href="#ab671544f7af287b25a5e612f6e919975">isReallyTriviallyReMaterializable</a>.</p>

</div>
</div>

### isLoadFromStackSlot() {#afb62c4d3c76506ef7a31dc75f98000db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::TargetInstrInfo::isLoadFromStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex, unsigned &amp; MemBytes)</td>
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

<p>Optional extension of isLoadFromStackSlot that returns the number of bytes loaded from the stack.</p>


<p>This must be implemented if a backend supports partial stack slot spills/loads to further disambiguate what the load does.</p>


<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#a6922ec50633977be02ab221c2de2adc1">isLoadFromStackSlot</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isLoadFromStackSlotPostFE() {#a8dad862e186c4263edb6f7583754efcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::TargetInstrInfo::isLoadFromStackSlotPostFE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for post-frame ptr elimination stack locations as well.</p>


<p>This uses a heuristic so it isn't reliable for correctness.</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isMBBSafeToOutlineFrom() {#a952e245a616622682cd83b1291314660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isMBBSafeToOutlineFrom (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned &amp; Flags)</td>
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

<p>Optional target hook that returns true if <span class="doxyComputerOutput">MBB</span> is safe to outline from, and returns any target-specific information in <span class="doxyComputerOutput">Flags</span>.</p>

<p>Declaration at line 2144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a9e0f1068be127e44f7350a2481e21a9c">llvm::RISCVInstrInfo::isMBBSafeToOutlineFrom</a>.</p>

</div>
</div>

### isMBBSafeToSplitToCold() {#a726928467271e18f3d17b2942cd04984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isMBBSafeToSplitToCold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> can safely be split to the cold section.</p>


<p>On <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a>, certain instructions may cause a block to be unsafe to split to the cold section.</p>


<p>Definition at line 2221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### isPCRelRegisterOperandLegal() {#aaccc261e5cc19c2d41a1ab9fb361cde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isPCRelRegisterOperandLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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

<p>Allow targets to tell MachineVerifier whether a specific register <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> can be used as part of PC-relative addressing.</p>


<p>PC-relative addressing modes in many CISC architectures contain (non-PC) registers as offsets or scaling values, which inherently tags the corresponding <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> with OPERAND_PCREL.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MO</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> in question. MO.isReg() should always be true.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Whether this operand is allowed to be used PC-relatively.</p></dd>
</dl>


<p>Definition at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isPostIncrement() {#a1cb223b29cc4acffa9ffd03d134b2a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isPostIncrement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true for post-incremented instructions.</p>

<p>Definition at line 1609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isPredicable() {#adf401885b0d39da5774814718bc889c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isPredicable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true if the specified instruction can be predicated.</p>


<p>By default, this returns true for every instruction with a PredicateOperand.</p>


<p>Definition at line 1676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ab334b6a433595c3b14311e50ed433119">llvm::R600InstrInfo::isPredicable</a>.</p>

</div>
</div>

### isPredicated() {#abda2e966ced4c77ce8a78e5e063e07cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isPredicated (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Returns true if the instruction is already predicated.</p>

<p>Definition at line 1612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a0a593a2fa65858fcd920bd782108c999">canPredicatePredicatedInstr</a>, <a href="#a3034fb1c96df7c2c8f52f11c8fc82467">getOutliningType</a> and <a href="#a4993b49c4db728d9669c0f6a08daae2e">isUnpredicatedTerminator</a>.</p>

</div>
</div>

### isProfitableToDupForIfCvt() {#ad5db14e4eee47b5fb139bf333d7f1516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isProfitableToDupForIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned NumCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
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

<p>Return true if it's profitable for if-converter to duplicate instructions of specified accumulated instruction latencies in the specified MBB to enable if-conversion.</p>


<p>The probability of the instructions being executed is given by Probability, and Confidence is a measure of our confidence that it will be properly predicted.</p>


<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### isProfitableToIfCvt() {#a00b5a36b4d498deae0da42cab63b6b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isProfitableToIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned NumCycles, unsigned ExtraPredCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
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

<p>Return true if it's profitable to predicate instructions with accumulated instruction latency of "NumCycles" of the specified basic block, where the probability of the instructions being executed is given by Probability, and Confidence is a measure of our confidence that it will be properly predicted.</p>

<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### isProfitableToIfCvt() {#a558a9e2bb84251c5a3dc6fbc2abf6b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isProfitableToIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TMBB, unsigned NumTCycles, unsigned ExtraTCycles, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; FMBB, unsigned NumFCycles, unsigned ExtraFCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
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

<p>Second variant of isProfitableToIfCvt.</p>


<p>This one checks for the case where two basic blocks from true and false path of a if-then-else (diamond) are predicated on mutually exclusive predicates, where the probability of the true path being taken is given by Probability, and Confidence is a measure of our confidence that it will be properly predicted.</p>


<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isProfitableToUnpredicate() {#a4c46c756d842143ad24a09a2723be290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isProfitableToUnpredicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; FMBB)</td>
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

<p>Return true if it's profitable to unpredicate one side of a 'diamond', i.e.</p>


<p>two sides of if-else predicated on mutually exclusive predicates. e.g. subeq r0, r1, #1 addne r0, r1, #1 =&gt; sub r0, r1, #1 addne r0, r1, #1</p>


<p>This may be profitable is conditional instructions are always executed.</p>


<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isReassociationCandidate() {#ace9f804c4f1407df72588bb00db16deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isReassociationCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, bool &amp; Commuted)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the input \P Inst is part of a chain of dependent ops that are suitable for reassociation, otherwise return false.</p>


<p>If the instruction's operands must be commuted to have a previous instruction of the same type define the first source operand, \P Commuted will be set to true.</p>


<p>Declaration at line 1269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="#a6034cfb230c4698caa60bdc3a9bf209b">hasReassociableOperands</a>, <a href="#aea784a4f9e9aba7792c23484e2498e8d">hasReassociableSibling</a> and <a href="#aa792b566fb2d8e29af95aea690e33201">isAssociativeAndCommutative</a>.</p>


<p>Referenced by <a href="#a861381cad67866e249c6330631ac0742">getMachineCombinerPatterns</a>.</p>

</div>
</div>

### isSafeToMoveRegClassDefs() {#adf676347c6bf8157f319dac9e601f168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isSafeToMoveRegClassDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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

<p>Return true if it's safe to move a machine instruction that defines the specified register class.</p>

<p>Definition at line 1682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isSafeToSink() {#a104cb332d459987fabfe9d7073150287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isSafeToSink (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccToSinkTo, <a href="/web-llvm/docs/api/namespaces/llvm/#aee433bfa58b17266f2cff728e02fba26">MachineCycleInfo</a> * CI)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isSchedulingBoundary() {#ad071e937f4986e51fd3fd54b10888894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isSchedulingBoundary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Test if the given instruction should be considered a scheduling boundary.</p>


<p>isSchedulingBoundary - Test if the given instruction should be considered a scheduling boundary.</p>


<p>This primarily includes labels and terminators.</p>


<p>Declaration at line 1688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1377 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5de0162fac7c57cab62e5bb81f0b5542">llvm::TargetLoweringBase::getStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab46fe6f7eb24fe0268c273a28452ecba">llvm::AArch64InstrInfo::isSchedulingBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aa7bdfd429f78e266cde062d9adf4a155">llvm::LoongArchInstrInfo::isSchedulingBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstrinfo/#a71d3ade87a14c00cb676e0ff96f8dc2e">llvm::NVPTXInstrInfo::isSchedulingBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a082a8593849ab4e2d9d2b0019de167c3">llvm::PPCInstrInfo::isSchedulingBoundary</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a1349e02190639b9dd3c8563ab8cf7f8e">llvm::X86InstrInfo::isSchedulingBoundary</a>.</p>

</div>
</div>

### isStackSlotCopy() {#aa51770f677efd652c55498dc472bec14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isStackSlotCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; DestFrameIndex, int &amp; SrcFrameIndex)</td>
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

<p>Return true if the specified machine instruction is a copy of one stack slot to another and has no other effect.</p>


<p>Provide the identity of the two frame indices.</p>


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isStoreToStackSlot() {#aa095ffe13f7029e833f37e346f5fa5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::TargetInstrInfo::isStoreToStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
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

<p>If the specified machine instruction is a direct store to a stack slot, return the virtual or physical register number of the source reg along with the FrameIndex of the loaded stack slot.</p>


<p>If not, return 0. This predicate must return 0 if the instruction has any side effects other than storing to the stack slot.</p>


<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af4a5b1227d7622151c06029e84d67ade">isStoreToStackSlot</a>.</p>

</div>
</div>

### isStoreToStackSlot() {#af4a5b1227d7622151c06029e84d67ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::TargetInstrInfo::isStoreToStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex, unsigned &amp; MemBytes)</td>
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

<p>Optional extension of isStoreToStackSlot that returns the number of bytes stored to the stack.</p>


<p>This must be implemented if a backend supports partial stack slot spills/loads to further disambiguate what the store does.</p>


<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#aa095ffe13f7029e833f37e346f5fa5b0">isStoreToStackSlot</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isStoreToStackSlotPostFE() {#a8d4598ec7bb2753593259420bff01427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::TargetInstrInfo::isStoreToStackSlotPostFE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for post-frame ptr elimination stack locations as well.</p>


<p>This uses a heuristic, so it isn't reliable for correctness.</p>


<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isSubregFoldable() {#a838a9048864ddaea932c974de0e8ce1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isSubregFoldable ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the target can fold a load that feeds a subreg operand (or a subreg operand that feeds a store).</p>


<p>For example, <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> may want to return true if it can fold movl (esp), eax subb, al, ... Into: subb (esp), ...</p>


<p>Ideally, we'd like the target implementation of <a href="#a6a733ae5364b0de2225af33223f383a5">foldMemoryOperand()</a> to reject subregs - but since this behavior used to be enforced in the target-independent code, moving this responsibility to the targets has the potential of causing nasty silent breakage in out-of-tree targets.</p>


<p>Definition at line 1196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isTailCall() {#a9d33681dd1899a420e4b30bf11f4b58e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
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

<p>Determines whether <span class="doxyComputerOutput">Inst</span> is a tail call instruction.</p>


<p>Override this method on targets that do not properly set <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a5416d9f1bd5f533efddadf17d713e469">MCID::Return</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a463baf545246fea9718664d933ffe66f">MCID::Call</a> on tail call instructions."</p>


<p>Definition at line 2065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a04af1d639a21e7ef4357facd283b42c4">llvm::MachineInstr::isReturn</a>.</p>

</div>
</div>

### isThroughputPattern() {#a321a2b25fab981c6d834e3d0df610921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isThroughputPattern (unsigned Pattern)</td>
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

<p>Return true when a code sequence can improve throughput.</p>


<p>Return true when a code sequence can improve loop throughput.</p>


<p>It should be called only for instructions in loops.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/pattern"&gt;Pattern&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- combiner pattern</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>

</div>
</div>

### isTriviallyReMaterializable() {#a1d142d4718ca758481e0b49ad9d8ea97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isTriviallyReMaterializable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true if the instruction is trivially rematerializable, meaning it has no side effects and requires no operands that aren't always available.</p>


<p>This means the only allowed uses are constants and unallocatable physical registers so that the instructions result is independent of the place in the function.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#ab671544f7af287b25a5e612f6e919975">isReallyTriviallyReMaterializable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5d3e4802f0929af81173430c0786d52a">llvm::calculateRegAllocScore</a>.</p>

</div>
</div>

### isUnconditionalTailCall() {#a49711da0a9e246f5960bf2816b0d8aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isUnconditionalTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Returns true if MI is an unconditional tail call.</p>

<p>Definition at line 1631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isUnpredicatedTerminator() {#a4993b49c4db728d9669c0f6a08daae2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isUnpredicatedTerminator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the instruction is a terminator instruction that has not been predicated.</p>

<p>Declaration at line 1628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="#abda2e966ced4c77ce8a78e5e063e07cd">isPredicated</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isUnspillableTerminator() {#a4bdf5a92f1195b3543b9412758c58106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isUnspillableTerminator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Return true if the given instruction is terminator that is unspillable, according to isUnspillableTerminatorImpl.</p>

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#ae47bacdac90d2744684f980e1ad40594">isUnspillableTerminatorImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isZeroCost() {#a0ba282dba26451dcfbbc938444595d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isZeroCost (unsigned Opcode)</td>
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

<p>Return true for pseudo instructions that don't consume any machine resources in their current form.</p>


<p>These are common cases that the scheduler should consider free, rather than conservatively handling them as instructions with no itinerary.</p>


<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### loadRegFromStackSlot() {#a9b1710394413e85110e485ec260c6a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::loadRegFromStackSlot (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, int FrameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
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

<p>Load the specified register of the given register class from the specified stack frame index.</p>


<p>The load instruction is to be added to the given machine basic block before the specified machine instruction. If <span class="doxyComputerOutput">DestReg</span> is being directly reloaded as part of assigning a virtual register, <span class="doxyComputerOutput">VReg</span> is the register being assigned. This additional register argument is needed for certain targets when invoked from RegAllocFast to map the loaded physical register to its virtual register. A null register can be passed elsewhere. The <span class="doxyComputerOutput">Flags</span> is used to set appropriate machine flags on the spill instruction e.g. FrameDestroy flag on a callee saved register reload instruction, part of epilogue, during the frame lowering.</p>


<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">llvm::MachineInstr::NoFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a6a733ae5364b0de2225af33223f383a5">foldMemoryOperand</a>.</p>

</div>
</div>

### lowerCopy() {#a68b7b9c491045c788173e83be1ba5d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::lowerCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function defines the logic to lower COPY instruction to target specific instruction(s).</p>

<p>Declaration at line 1229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="#ad61db491bd5855c30926453db6401958">copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8be49bc86b5d01b52b90baf1b4477667">llvm::MachineOperand::isRenamable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a0992d70176e7dfe68ee15af73be3f948">transferImplicitOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### mergeOutliningCandidateAttributes() {#a4253df7a10e437a01d42c223e196c0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::mergeOutliningCandidateAttributes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &gt; &amp; Candidates)</td>
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

<p>Optional target hook to create the LLVM IR attributes for the outlined function.</p>


<p>If overridden, the overriding function must call the default implementation.</p>


<p>Declaration at line 2123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1794 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#a71a2623cadc4c0ef543d25d1c6f2a07a">llvm::outliner::Candidate::getMF</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>

</div>
</div>

### optimizeCompareInstr() {#a6d95382897959324602ecb63f7392fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::optimizeCompareInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CmpInstr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg2, int64_t Mask, int64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
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

<p>See if the comparison instruction can be converted into something more efficient.</p>


<p>E.g., on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> most instructions can set the flags register, obviating the need for a separate CMP.</p>


<p>Definition at line 1740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### optimizeCondBranch() {#a9414061830d845a2b79363614cf5b5db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::optimizeCondBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 1746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### optimizeLoadInstr() {#a01961400ab1186ac9f849cf0e738447f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::optimizeLoadInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; FoldAsLoadDefReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; DefMI)</td>
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

<p>Try to remove the load by folding it to a register operand at the use.</p>


<p>We fold the load instructions if and only if the def and use are in the same BB. We only look at one load and see whether it can be folded into MI. FoldAsLoadDefReg is the virtual register defined by the load we are trying to fold. DefMI returns the machine instruction that defines FoldAsLoadDefReg, and the function returns the machine instruction generated due to folding.</p>


<p>Definition at line 1755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### optimizeSelect() {#a31b099a7de1dfef1561ec6f7df09da47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::optimizeSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; NewMIs, bool PreferFalse=false)</td>
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

<p>Given a select instruction that was understood by analyzeSelect and returned Optimizable = true, attempt to optimize MI by merging it with one of its operands.</p>


<p>Returns NULL on failure.</p>


<p>When successful, returns the new select instruction. The client is responsible for deleting MI.</p>


<p>If both sides of the select can be optimized, PreferFalse is used to pick a side.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p>Optimizable select instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewMIs</td>
<td class="doxyParamItemDescription"><p>Set that record all MIs in the basic block up to <span class="doxyComputerOutput">MI</span>. Has to be updated with any newly created MI or deleted ones.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PreferFalse</td>
<td class="doxyParamItemDescription"><p>Try to optimize FalseOp instead of TrueOp.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Optimized instruction or NULL.</p></dd>
</dl>


<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### PredicateInstruction() {#a29513f18e551370b1b438f95403efc04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::PredicateInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Pred)</td>
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

<p>Convert the instruction into a predicated instruction.</p>


<p>It returns true if the operation was successful.</p>


<p>Declaration at line 1650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afe1784e242ce66da6029b3a681896bd2">llvm::MachineOperand::isMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a98e9c9e8ef7cbb6c4aa89a38f21decfa">llvm::MachineOperand::setMBB</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>

</div>
</div>

### predictBranchSizeForIfCvt() {#ac0eb74bb20ce93168ed6fc663d997c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::predictBranchSizeForIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return an estimate for the code size reduction (in bytes) which will be caused by removing the given branch instruction during if-conversion.</p>

<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#ad5c95e145de31fbd3c6269ebe1b615f7">getInstSizeInBytes</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### preservesZeroValueInReg() {#a45aa2763f52ee7bb3f41393d1d4ba079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::preservesZeroValueInReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NullValueReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Returns true if MI's Def is NullValueReg, and the MI does not change the Zero value.</p>


<p>i.e. cases such as rax = shr rax, X where NullValueReg = rax. Note that if the NullValueReg is non-zero, this function can return true even if becomes zero. Specifically cases such as NullValueReg = shl NullValueReg, 63.</p>


<p>Definition at line 1553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### produceSameValue() {#ac66abaa28810e0bb35ab77012a3ea997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::produceSameValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI=nullptr)</td>
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

<p>Return true if two machine instructions would produce identical values.</p>


<p>By default, this is only true when the two instructions are deemed identical except for defs. If this function is called when the IR is still in SSA form, the caller can pass the <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> for aggressive checks.</p>


<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab7650f958c093f7c5faf8c69dbc8c462a5f3288f908142ddad3dd5d8a95cfa364">llvm::MachineInstr::IgnoreVRegDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### reassociateOps() {#ae5e0c947b38bdebad23286c7764b5249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::reassociateOps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Prev, unsigned Pattern, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; InsInstrs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DelInstrs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; OperandIndices, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt; &amp; InstrIdxForVirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to reassociate \P Root and \P Prev according to \P <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> to reduce critical path length.</p>


<p>Attempt the reassociation transformation to reduce critical path length.</p>


<p>See the above comments before <a href="#a861381cad67866e249c6330631ac0742">getMachineCombinerPatterns()</a>.</p>


<p>Declaration at line 1328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a859897c8a9706acd4c065d857254d58c">llvm::MachineInstr::clearFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae4cfeb86ad3780d71eb022485e91d211">llvm::MachineInstrBuilder::copyImplicitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a418c87b57626e29b332b6ffafca9f1af">llvm::MachineFunction::CreateMachineInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a51f1fa9d5384d3b9c157a8216fef671d">llvm::MachineInstr::explicit_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad73e18478cd951f76d35a88c4d43ef5a">llvm::MachineInstr::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af066b2b6a1013299bfca84fe8b798a0b">llvm::MachineInstrBuilder::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a903e4ccbdb00b36a08f5e84a8010c3cd">getReassociationOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af551bfe7ee8756cbe50de3bb97478723">llvm::MachineInstr::getRegClassConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">llvm::MachineInstr::IsExact</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a839473cb5602736027190655f7db7e9d">mustSwapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">llvm::MachineInstr::NoSWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">llvm::MachineInstr::NoUWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a524f9c8ad90631347eeaa311ba919b8f">llvm::MachineInstr::peekDebugInstrNum</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da9b77519dc201611a2d982ef32b0c71f2">llvm::REASSOC_AX_BY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4dafd129ea7c5159e885a926375eb1e8de3">llvm::REASSOC_AX_YB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4da651595de1269df92d8ab8fd174c000c8">llvm::REASSOC_XA_BY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72fae53189574086169c907fd3ce8a4daea1070ab8a6a63fd5d8957ed142e7f21">llvm::REASSOC_XA_YB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a443787beae18cf65517b239aa15d74e4">llvm::MachineInstr::setDebugInstrNum</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a264402282f599b6181b6415278fbf849">llvm::MachineInstr::setFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abdda4cba7788bae87378a6cbdc81dbe2">llvm::MachineInstrBuilder::setPCSections</a>, <a href="#a0b63f89d9653388354a58218932dc2f8">setSpecialOperandAttr</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#ab0ea1fe6f61d0e861ed2be7632a270bb">TargetInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a6875e5a149ffdf299b10e8f969d379d4">genAlternativeCodeSequence</a>.</p>

</div>
</div>

### reduceLoopCount() {#a18927162b9131e79e1ee778c7ae4a4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::reduceLoopCount (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PreHeader, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * IndVar, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Cmp, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; PrevInsts, unsigned Iter, unsigned MaxIter)</td>
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

<p>Generate code to reduce the loop iteration by one and check if the loop is finished.</p>


<p>Return the value/register of the new loop count. We need this function when peeling off one or more iterations of a loop. This function assumes the nth iteration is peeled first.</p>


<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### reMaterialize() {#aadcfe8906a95ad57f3f7a7d433f47204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::reMaterialize (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Orig, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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

<p>Re-issue the specified 'original' instruction at the specific location targeting a new destination register.</p>


<p>The register in Orig-&gt;getOperand(0).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg()</a> will be substituted by DestReg:SubIdx. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> existing subreg index is preserved or composed with SubIdx.</p>


<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>.</p>

</div>
</div>

### removeBranch() {#a0317b8d1d0eb9aaf9af9d636f5f66e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetInstrInfo::removeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, int * BytesRemoved=nullptr)</td>
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

<p>Remove the branching code at the end of the specific MBB.</p>


<p>This is only invoked in cases where analyzeBranch returns success. It returns the number of instructions that were removed. If <span class="doxyComputerOutput">BytesRemoved</span> is non-null, report the change in code size from the removed instructions.</p>


<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### replaceBranchWithTailCall() {#abee18da5b03753cdb0cd484b2a4e2c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::replaceBranchWithTailCall (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; TailCall)</td>
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

<p>Replace the conditional branch in MBB with a conditional tail call.</p>

<p>Definition at line 1642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### ReplaceTailWithBranchTo() {#a26e9655e762686aff18772a15139df27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetInstrInfo::ReplaceTailWithBranchTo (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Tail, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewDest)</td>
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

<p>Delete the instruction OldInst and everything after it, replacing it with an unconditional branch to NewDest.</p>


<p>ReplaceTailWithBranchTo - Delete the instruction OldInst and everything after it, replacing it with an unconditional branch to NewDest.</p>


<p>This is used by the tail merging pass.</p>


<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a762db1f75e789783b689f22cda71bad4">insertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a5d4594ba9cc5dade7f685316cc9c2e96">llvm::Thumb2InstrInfo::ReplaceTailWithBranchTo</a>.</p>

</div>
</div>

### reverseBranchCondition() {#a013a36a3a8a5acbdb9bcf1d3c6fede83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::reverseBranchCondition (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond)</td>
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

<p>Reverses the branch condition of the specified condition list, returning false on success and true if it cannot be reversed.</p>

<p>Definition at line 1592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>.</p>

</div>
</div>

### setExecutionDomain() {#adbcfa8a45f569feb4562cff3567163ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::setExecutionDomain (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Domain)</td>
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

<p>Change the opcode of MI to execute in <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a>.</p>


<p>The bit (1 &lt;&lt; <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a>) must be set in the mask returned from getExecutionDomain(MI).</p>


<p>Definition at line 1877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### setSpecialOperandAttr() {#a0b63f89d9653388354a58218932dc2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::setSpecialOperandAttr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OldMI1, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OldMI2, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; NewMI1, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; NewMI2)</td>
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

<p>This is an architecture-specific helper function of reassociateOps.</p>


<p>Set special operand attributes for new instructions after reassociation.</p>


<p>Definition at line 1347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#ae5e0c947b38bdebad23286c7764b5249">reassociateOps</a>.</p>

</div>
</div>

### shouldBreakCriticalEdgeToSink() {#a5f8e648b771ac836d613da033447a78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::shouldBreakCriticalEdgeToSink (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>For a "cheap" instruction which doesn't enable additional sinking, should MachineSink break a critical edge to sink it anyways?</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### shouldClusterMemOps() {#a6c56f769334913401fe67e9e123b3d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::shouldClusterMemOps (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; BaseOps1, int64_t Offset1, bool OffsetIsScalable1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; BaseOps2, int64_t Offset2, bool OffsetIsScalable2, unsigned ClusterSize, unsigned NumBytes)</td>
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

<p>Returns true if the two given memory operations should be scheduled adjacent.</p>


<p>Note that you have to add: DAG-&gt;addMutation(createLoadClusterDAGMutation(DAG-&gt;TII, DAG-&gt;TRI)); or DAG-&gt;addMutation(createStoreClusterDAGMutation(DAG-&gt;TII, DAG-&gt;TRI)); to <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a76f0f9b7aba8cb8682c8b60f24cce1ae">TargetPassConfig::createMachineScheduler()</a> to have an effect.</p>


<p><span class="doxyComputerOutput">BaseOps1</span> and <span class="doxyComputerOutput">BaseOps2</span> are memory operands of two memory operations. <span class="doxyComputerOutput">Offset1</span> and <span class="doxyComputerOutput">Offset2</span> are the byte offsets for the memory operations. <span class="doxyComputerOutput">OffsetIsScalable1</span> and <span class="doxyComputerOutput">OffsetIsScalable2</span> indicate if the offset is scaled by a runtime quantity. <span class="doxyComputerOutput">ClusterSize</span> is the number of operations in the resulting load/store cluster if this hook returns true. <span class="doxyComputerOutput">NumBytes</span> is the number of bytes that will be loaded from all the clustered loads if this hook returns true.</p>


<p>Definition at line 1580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### shouldHoist() {#aefc848c0953b9a49b09c0ef3a577a34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::shouldHoist (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * FromLoop)</td>
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

<p>Return false if the instruction should not be hoisted by MachineLICM.</p>


<p>MachineLICM determines on its own whether the instruction is safe to hoist; this gives the target a hook to extend this assessment and prevent an instruction being hoisted from a given loop for target specific reasons.</p>


<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### shouldOutlineFromFunctionByDefault() {#a2de90c613673f0815ee6aa406f67390a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::shouldOutlineFromFunctionByDefault (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return true if the function should be outlined from by default.</p>

<p>Definition at line 2210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### shouldReduceRegisterPressure() {#a3b8cfc1d0bd78872b33f4669f9a18927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::shouldReduceRegisterPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> * RegClassInfo)</td>
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

<p>Return true if target supports reassociation of instructions in machine combiner pass to reduce register pressure for a given BB.</p>

<p>Definition at line 1245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### shouldScheduleLoadsNear() {#a7613f5f7e38ac5338a58172dd6429370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::shouldScheduleLoadsNear (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load1, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load2, int64_t Offset1, int64_t Offset2, unsigned NumLoads)</td>
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

<p>This is a used by the pre-regalloc scheduler to determine (in conjunction with areLoadsFromSameBasePtr) if two loads should be scheduled together.</p>


<p>On some targets if two loads are loading from addresses in the same cache line, it's better if they are scheduled together. This function takes two integers that represent the load offsets from the common base address. It returns true if it decides it's desirable to schedule the two loads together. "NumLoads" is the number of loads that have already been scheduled after Load1.</p>


<p>Definition at line 1477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### shouldSink() {#ad9b2151fcd1d9e2cec1689aec6e5ed8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::shouldSink (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true if the instruction should be sunk by MachineSink.</p>


<p>MachineSink determines on its own whether the instruction is safe to sink; this gives the target a hook to override the default behavior with regards to which instructions should be sunk.</p>


<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### storeRegToStackSlot() {#a6d3df2a0837fb3b75b9a0ac8f0923843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetInstrInfo::storeRegToStackSlot (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, bool isKill, int FrameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
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

<p>Store the specified register of the given register class to the specified stack frame index.</p>


<p>The store instruction is to be added to the given machine basic block before the specified machine instruction. If isKill is true, the register operand is the last use and must be marked kill. If <span class="doxyComputerOutput">SrcReg</span> is being directly spilled as part of assigning a virtual register, <span class="doxyComputerOutput">VReg</span> is the register being assigned. This additional register argument is needed for certain targets when invoked from RegAllocFast to map the spilled physical register to its virtual register. A null register can be passed elsewhere. The <span class="doxyComputerOutput">Flags</span> is used to set appropriate machine flags on the spill instruction e.g. FrameSetup flag on a callee saved register spill instruction, part of prologue, during the frame lowering.</p>


<p>Definition at line 1148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">llvm::MachineInstr::NoFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a6a733ae5364b0de2225af33223f383a5">foldMemoryOperand</a>.</p>

</div>
</div>

### SubsumesPredicate() {#a51ba312c2d730acd131fccc2cc787498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::SubsumesPredicate (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Pred1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Pred2)</td>
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

<p>Returns true if the first specified predicate subsumes the second, e.g.</p>


<p>GE subsumes GT.</p>


<p>Definition at line 1655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### unfoldMemoryOperand() {#aa44220d7a83b114a21ca2d23ffed03b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::unfoldMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Reg, bool UnfoldLoad, bool UnfoldStore, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; NewMIs)</td>
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

<p>unfoldMemoryOperand - Separate a single instruction which folded a load or a store or a load and a store into two or more instruction.</p>


<p>If this is possible, returns true as well as the new instructions by reference.</p>


<p>Definition at line 1436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### unfoldMemoryOperand() {#af7a82bf89bd98729150cebde60be9dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::unfoldMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; NewNodes)</td>
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



<p>Definition at line 1442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### useMachineCombiner() {#a4cb5569c23b5e1ed52164d9ec0496c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::useMachineCombiner ()</td>
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

<p>Return true when a target supports MachineCombiner.</p>

<p>Definition at line 1352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### usePreRAHazardRecognizer() {#af286c176e38f876d4f56a34cb9ee319a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::usePreRAHazardRecognizer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide a global flag for disabling the PreRA hazard recognizer that targets may choose to honor.</p>

<p>Declaration at line 1725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#aeb921abaab57f35917a459316dc1b8b0">DisableHazardRecognizer</a>.</p>

</div>
</div>

### verifyInstruction() {#a490afb5ecb8232428c7ce7b87ef24b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::verifyInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ErrInfo)</td>
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

<p>Perform target-specific instruction verification.</p>

<p>Definition at line 1844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### commuteInstructionImpl() {#adf4d05c8ea2fc82ae12300ef5fb48951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * TargetInstrInfo::commuteInstructionImpl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool NewMI, unsigned OpIdx1, unsigned OpIdx2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method commutes the operands of the given machine instruction MI.</p>


<p>The operands to be commuted are specified by their indices OpIdx1 and OpIdx2.</p>


<p>If a target has any instructions that are commutable but require converting to different instructions or making non-trivial changes to commute them, this method can be overloaded to do that. The default implementation simply swaps the commutable operands.</p>


<p>If NewMI is false, MI is modified in place and returned; otherwise, a new machine instruction is created and returned.</p>


<p>Do not call this method for a non-commutable instruction. Even though the instruction is commutable, the method may still fail to commute the operands, null pointer is returned in such cases.</p>


<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac485421b5fcb9454ea64e74f6396a810">llvm::MachineFunction::CloneMachineInstr</a>, <a href="#a422b844cc7e3db360908c008cb651f96">findCommutedOpIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a133a1aff6f7f6a9ea4f641adc88a120d">llvm::MachineOperand::setIsInternalRead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a48bcf9eb66f880de8e7f4d0fcc8af320">llvm::MachineOperand::setIsRenamable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab979122f21b7fa46d3d2d9b21983068b">llvm::MachineOperand::setIsUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a001d31fcea92be51d2999826b806606f">llvm::MachineOperand::setSubReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>.</p>


<p>Referenced by <a href="#aa41720cc33b0511709c92abcb164a59d">commuteInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#af76e71e7ea189719baa6f8819724fac5">llvm::ARMBaseInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a3ea2369e6bcfa35889cf566047e3ca3f">llvm::PPCInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adf5d3b4379e4e570f14f6700d6e87467">llvm::SIInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a89d302e9b09c832b934b98dc4885913d">llvm::SystemZInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#ac4ddbe6be77b7002804ccc21c5603e55">llvm::WebAssemblyInstrInfo::commuteInstructionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### foldMemoryOperandImpl() {#a0a1e73b39957ad3da60cb9d3a690df89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::foldMemoryOperandImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, int FrameIndex, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-dependent implementation for foldMemoryOperand.</p>


<p>Target-independent code in foldMemoryOperand will take care of adding a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> to the newly created instruction. The instruction and any auxiliary instructions necessary will be inserted at InsertPt.</p>


<p>Definition at line 1368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a6a733ae5364b0de2225af33223f383a5">foldMemoryOperand</a> and <a href="#a2432d0bb09d9fe3b6bb004d8dbf77a99">foldMemoryOperand</a>.</p>

</div>
</div>

### foldMemoryOperandImpl() {#af4f87b0480bb0e4d689f7b3cf2aa88a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineInstr * llvm::TargetInstrInfo::foldMemoryOperandImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; LoadMI, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-dependent implementation for foldMemoryOperand.</p>


<p>Target-independent code in foldMemoryOperand will take care of adding a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> to the newly created instruction. The instruction and any auxiliary instructions necessary will be inserted at InsertPt.</p>


<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getExtractSubregLikeInputs() {#af1c44734f854fb7f620d16097f2af637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::getExtractSubregLikeInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx">RegSubRegPairAndIdx</a> &amp; InputReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-dependent implementation of getExtractSubregInputs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build the equivalent EXTRACT_SUBREG inputs with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span>. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isExtractSubregLike().</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#af1743a67877bf4ba56d53b235d3573e0">TargetInstrInfo::getExtractSubregInputs</a>.</p></dd>
</dl>


<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af1743a67877bf4ba56d53b235d3573e0">getExtractSubregInputs</a>.</p>

</div>
</div>

### getInsertSubregLikeInputs() {#a2b51d2dd19b3859797509c03d5f451f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::getInsertSubregLikeInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &amp; BaseReg, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx">RegSubRegPairAndIdx</a> &amp; InsertedReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-dependent implementation of getInsertSubregInputs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build the equivalent INSERT_SUBREG inputs with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span>. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isInsertSubregLike().</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#abea536f043de7994bc9b67c634a7c879">TargetInstrInfo::getInsertSubregInputs</a>.</p></dd>
</dl>


<p>Definition at line 1425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#abea536f043de7994bc9b67c634a7c879">getInsertSubregInputs</a>.</p>

</div>
</div>

### getOutliningTypeImpl() {#a2af67652d97de393fd3208c625cea6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual outliner::InstrType llvm::TargetInstrInfo::getOutliningTypeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MIT, unsigned Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-dependent implementation for getOutliningTypeImpl.</p>

<p>Definition at line 2129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a3034fb1c96df7c2c8f52f11c8fc82467">getOutliningType</a>.</p>

</div>
</div>

### getRegSequenceLikeInputs() {#a52e026925b73de52f7a563693ebff007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::getRegSequenceLikeInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx">RegSubRegPairAndIdx</a> &gt; &amp; InputRegs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-dependent implementation of getRegSequenceInputs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build the equivalent REG_SEQUENCE inputs with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span>. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isRegSequenceLike().</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#ae26cac7943070f09b4d7fa667d1adf95">TargetInstrInfo::getRegSequenceInputs</a>.</p></dd>
</dl>


<p>Definition at line 1396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ae26cac7943070f09b4d7fa667d1adf95">getRegSequenceInputs</a>.</p>

</div>
</div>

### isCopyInstrImpl() {#a7eb5f369839e0987506e72b0ffc1b982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; DestSourcePair &gt; llvm::TargetInstrInfo::isCopyInstrImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-dependent implementation for IsCopyInstr.</p>


<p>If the specific machine instruction is a instruction that moves/copies value from one register to another register return destination and source registers as machine operands.</p>


<p>Definition at line 1067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ace5bb5eb8d13b5726f90e7f38df45d60">isCopyInstr</a>.</p>

</div>
</div>

### isCopyLikeInstrImpl() {#a13cf72d93ee18d693c7a74f0c1307cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; DestSourcePair &gt; llvm::TargetInstrInfo::isCopyLikeInstrImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a82dd4c26bf1be527376323f5c9889fbd">isCopyLikeInstr</a>.</p>

</div>
</div>

### isReallyTriviallyReMaterializable() {#ab671544f7af287b25a5e612f6e919975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::isReallyTriviallyReMaterializable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For instructions with opcodes for which the M_REMATERIALIZABLE flag is set, this hook lets the target specify whether the instruction is actually trivially rematerializable, taking into consideration its operands.</p>


<p>This predicate must return false if the instruction has any side effects other than producing a value, or if it requres any address registers that are not always available.</p>


<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 1274 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5eab840dac82571e53cc5f1c05643e2a">llvm::MachineFrameInfo::isImmutableObjectIndex</a>, <a href="#a6922ec50633977be02ab221c2de2adc1">isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0f34e95d290dc051294ec47023d90ca7">llvm::PPCInstrInfo::isReallyTriviallyReMaterializable</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a1c2309d0cd4e9423ee76a1f39b3308e9">llvm::RISCVInstrInfo::isReallyTriviallyReMaterializable</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a64e3c3928f613445e6a6c1f3b1073744">llvm::SIInstrInfo::isReallyTriviallyReMaterializable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a2e51e4a802125fe4a41dd336d75f5f21">llvm::WebAssemblyInstrInfo::isReallyTriviallyReMaterializable</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a3b066a53bb36252b44604bb3573a5ae3">llvm::X86InstrInfo::isReallyTriviallyReMaterializable</a> and <a href="#a1d142d4718ca758481e0b49ad9d8ea97">isTriviallyReMaterializable</a>.</p>

</div>
</div>

### isUnspillableTerminatorImpl() {#ae47bacdac90d2744684f980e1ad40594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetInstrInfo::isUnspillableTerminatorImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given terminator MI is not expected to spill.</p>


<p>This sets the live interval as not spillable and adjusts phi node lowering to not introduce copies after the terminator. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> with care, these are currently used for hardware loop intrinsics in very controlled situations, created prior to registry allocation in loops that only have single phi users for the terminators value. They may run out of registers if not used carefully.</p>


<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a4bdf5a92f1195b3543b9412758c58106">isUnspillableTerminator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallFrameDestroyOpcode {#a78223000912a8a9aa3443a60a1d0e9e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::CallFrameDestroyOpcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### CallFrameSetupOpcode {#a4029cf1b9edf2988c2fc5a0cc5b5f766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::CallFrameSetupOpcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### CatchRetOpcode {#aecc11af84e38e8e4c664c69ed7d6ab78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::CatchRetOpcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### Formatter {#ae021517c1f7eba6dbb68ae02eb5383e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MIRFormatter&gt; llvm::TargetInstrInfo::Formatter</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### ReturnOpcode {#a8047b6543112b3c755cedc67707dc6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::ReturnOpcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isGenericAtomicRMWOpcode() {#ae60fd4c7626ec53d75182d6f54743745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isGenericAtomicRMWOpcode (unsigned Opc)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isGenericOpcode() {#a82a499274493eca235e684f82ee54b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::isGenericOpcode (unsigned Opc)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### fixCommutedOpIndices() {#aef5b8db7ddf8b00b66e4f64711a053cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetInstrInfo::fixCommutedOpIndices (unsigned &amp; ResultIdx1, unsigned &amp; ResultIdx2, unsigned CommutableOpIdx1, unsigned CommutableOpIdx2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assigns the (CommutableOpIdx1, CommutableOpIdx2) pair of commutable operand indices to (ResultIdx1, ResultIdx2).</p>


<p>One or both input values of the pair: (ResultIdx1, ResultIdx2) may be predefined to some indices or be undefined (designated by the special value 'CommuteAnyOperandIndex'). The predefined result indices cannot be re-defined. The function returns true iff after the result pair redefinition the fixed result pair is equal to or equivalent to the source pair of indices: (CommutableOpIdx1, CommutableOpIdx2). It is assumed here that the pairs (x,y) and (y,x) are equivalent.</p>


<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a>.</p>


<p>Reference <a href="#ae73e2be2b66dc9e4f2f90d56076d7ea9">CommuteAnyOperandIndex</a>.</p>


<p>Referenced by <a href="#a422b844cc7e3db360908c008cb651f96">findCommutedOpIndices</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### CommuteAnyOperandIndex {#ae73e2be2b66dc9e4f2f90d56076d7ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::TargetInstrInfo::CommuteAnyOperandIndex = ~0U</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="#aa41720cc33b0511709c92abcb164a59d">commuteInstruction</a>, <a href="#aef5b8db7ddf8b00b66e4f64711a053cd">fixCommutedOpIndices</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregstackify-cpp-/commutingstate/#a4ea15ac34bc701369f48c52d1c9a3adf">anonymous{WebAssemblyRegStackify.cpp}::CommutingState::maybeCommute</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp">TargetInstrInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
