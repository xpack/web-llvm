---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armbaseregisterinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMBaseRegisterInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMBaseRegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">Target/ARM/ARMBaseRegisterInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/armgenregisterinfo">ARMGenRegisterInfo</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/armregisterinfo">ARMRegisterInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo">ThumbRegisterInfo</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab05262ecfea64a231a017677192927">ARMBaseRegisterInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae827683289cd88fddbe641f8608b9b">getCalleeSavedRegs</a> (const MachineFunction *MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code Generation virtual methods... <a href="#a8ae827683289cd88fddbe641f8608b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae538c50015c12adeb2477f4ee4b6d2f8">getCalleeSavedRegsViaCopy</a> (const MachineFunction *MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9d03a862069b7f3c4f446e0be8b826">getCallPreservedMask</a> (const MachineFunction &amp;MF, CallingConv::ID) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff75e03dd1389eb5ee642d134e15caf">getNoPreservedMask</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac429f32d6cfbb8ea856855221d7b0324">getTLSCallPreservedMask</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e55ddeb12d25d6b87b3237661967c62">getSjLjDispatchPreservedMask</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee22c8e9e9eb4ac9413ce2adf676379c">getThisReturnPreservedMask</a> (const MachineFunction &amp;MF, CallingConv::ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getThisReturnPreservedMask - Returns a call preserved mask specific to the case that 'returned' is on an i32 first argument if the calling convention is one that can (partially) model this attribute with a preserved mask (i.e. <a href="#aee22c8e9e9eb4ac9413ce2adf676379c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe29209cd2ac4c05d0f3739ec62d4fe">getIntraCallClobberedRegs</a> (const MachineFunction *MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185c9e3a52cfad64d466568e38c70308">getReservedRegs</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20d327887091b2623315d7154f115a2">isAsmClobberable</a> (const MachineFunction &amp;MF, MCRegister PhysReg) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3bbd8da3d2794c25c551a779fef663">isInlineAsmReadOnlyReg</a> (const MachineFunction &amp;MF, unsigned PhysReg) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac941eb7de76a190c2cf9c3957f716e46">getPointerRegClass</a> (const MachineFunction &amp;MF, unsigned Kind=0) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f82d201deb3b2ab7fc56508761c752">getCrossCopyRegClass</a> (const TargetRegisterClass *RC) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d9301f2db70078a258c683a1046f569">getLargestLegalSuperClass</a> (const TargetRegisterClass *RC, const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe522c5b4605ba12fa3167e7959b6645">getRegPressureLimit</a> (const TargetRegisterClass *RC, MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b81cc14aafd09d0e380b123cd06d51">getRegAllocationHints</a> (Register VirtReg, ArrayRef&lt; MCPhysReg &gt; Order, SmallVectorImpl&lt; MCPhysReg &gt; &amp;Hints, const MachineFunction &amp;MF, const VirtRegMap *VRM, const LiveRegMatrix *Matrix) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4e7b801f3b166aebe037d065fa6923">updateRegAllocHint</a> (Register Reg, Register NewReg, MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2ca33d941092c36d88209114f6fa8f">hasBasePointer</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee75d3e9f0900bee26680be79a90f9a3">canRealignStack</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235a0e236caca418542d097c0f0fca9c">getFrameIndexInstrOffset</a> (const MachineInstr *MI, int Idx) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7508374329448fb4210c15d9cc79ad7">needsFrameBaseReg</a> (MachineInstr *MI, int64_t Offset) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>needsFrameBaseReg - Returns true if the instruction's frame index reference would be better served by a base register other than FP or SP. <a href="#ae7508374329448fb4210c15d9cc79ad7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac02c01e89c0ac7acc53bb50aeac772ac">materializeFrameBaseRegister</a> (MachineBasicBlock *MBB, int FrameIdx, int64_t Offset) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>materializeFrameBaseRegister - Insert defining instruction(s) for BaseReg to be a pointer to FrameIdx at the beginning of the basic block. <a href="#ac02c01e89c0ac7acc53bb50aeac772ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69f26dc070e18750b9974aaa24565ed">resolveFrameIndex</a> (MachineInstr &amp;MI, Register BaseReg, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f78fc5fd7a7ad8a92ce3a0ba77aecf4">isFrameOffsetLegal</a> (const MachineInstr *MI, Register BaseReg, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0eb9ad617a055468d105965502662c5">cannotEliminateFrame</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab064b648d7048dcfa869dc4021c54859">getFrameRegister</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afffd40779f75bf01f506173853995976">getBaseRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4563cae7f10b41cdff9a61f1f6aaab">emitLoadConstPool</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;MBBI, const DebugLoc &amp;dl, Register DestReg, unsigned SubIdx, int Val, ARMCC::CondCodes Pred=ARMCC::AL, Register PredReg=Register(), unsigned MIFlags=MachineInstr::NoFlags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitLoadConstPool - Emits a load from constpool to materialize the specified immediate. <a href="#a5e4563cae7f10b41cdff9a61f1f6aaab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac25ab1983ee8331e6281acb26981712a">requiresRegisterScavenging</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code Generation virtual methods... <a href="#ac25ab1983ee8331e6281acb26981712a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff38ab5d18db335f91dd3fe93ff4014d">requiresFrameIndexScavenging</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab4194265d15e3af4f75a6630321156">requiresVirtualBaseRegisters</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f318a4b1d38e66b324c0748304e60de">eliminateFrameIndex</a> (MachineBasicBlock::iterator II, int SPAdj, unsigned FIOperandNum, RegScavenger *RS=nullptr) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc0ac22a4727eaf94ec9a2fff5fa8b5">shouldCoalesce</a> (MachineInstr *MI, const TargetRegisterClass *SrcRC, unsigned SubReg, const TargetRegisterClass *DstRC, unsigned DstSubReg, const TargetRegisterClass *NewRC, LiveIntervals &amp;LIS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SrcRC and DstRC will be morphed into NewRC if this returns true. <a href="#a0dc0ac22a4727eaf94ec9a2fff5fa8b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4360b9c445d8cc8fa2328c483241eff9">shouldRewriteCopySrc</a> (const TargetRegisterClass *DefRC, unsigned DefSubReg, const TargetRegisterClass *SrcRC, unsigned SrcSubReg) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a828dacf15247e4e01d0b7ca88a6db6c3">getSEHRegNum</a> (unsigned i) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d3d20d0e64bd376f5dd31b1ffc716f">BasePtr</a> = ARM::R6</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BasePtr - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> physical register used as a base ptr in complex stack frames. <a href="#ad7d3d20d0e64bd376f5dd31b1ffc716f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ARMBaseRegisterInfo() {#a2ab05262ecfea64a231a017677192927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMBaseRegisterInfo::ARMBaseRegisterInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/arm-mc/#ab566520d2c3ff7f259409c7dab96823b">llvm::ARM_MC::initLLVMToCVRegMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cannotEliminateFrame() {#aa0eb9ad617a055468d105965502662c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::cannotEliminateFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a19e260b3bbf8fad8480d151e11919836">llvm::MachineFrameInfo::adjustsStack</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>.</p>

</div>
</div>

### canRealignStack() {#aee75d3e9f0900bee26680be79a90f9a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::canRealignStack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="#ad7d3d20d0e64bd376f5dd31b1ffc716f">BasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a242c8591b53ef3b0846119dc1a70df2c">llvm::TargetRegisterInfo::canRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a3d0de6c30c8e5b1342e3f238e765221c">llvm::ARMSubtarget::getFramePointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a7d1c91b20625d31982210d6fc381104d">llvm::ARMFrameLowering::hasReservedCallFrame</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a12d8c4c294b19351dbee6ab588676012">checkNumAlignedDPRCS2Regs</a> and <a href="#ae7508374329448fb4210c15d9cc79ad7">needsFrameBaseReg</a>.</p>

</div>
</div>

### eliminateFrameIndex() {#a6f318a4b1d38e66b324c0748304e60de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::eliminateFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> II, int SPAdj, unsigned FIOperandNum, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a9dbb177d004cae6c3474b6aadc8ae07e">llvm::ARMII::AddrMode4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a8388bb748b26edbdb8bb5d5ab6f16853">llvm::ARMII::AddrMode6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4aeda154c828d692cd52ca6cce8765f9ae">llvm::ARMII::AddrModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a987c9c423c608a5f21f3a2c16bf9dff4">llvm::ARMII::AddrModeT2_i7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a686f044e7ff2a5ff778e03d30e7acacb">llvm::ARMII::AddrModeT2_i7s2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4aac7571d8c1b21260b02bd8b7d3bb637d">llvm::ARMII::AddrModeT2_i7s4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae917ff404aade469cb9d3780515660ad">llvm::emitARMRegPlusImmediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaee29fd8c447694396529bd6a468a6f">llvm::emitT2RegPlusImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a7d1c91b20625d31982210d6fc381104d">llvm::ARMFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a82a0ed0e83e8058a1594c9bb6e9678cc">llvm::RegScavenger::isScavengingFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a5638ad10fa6d78adda170a382dc7f75a">llvm::ARMFunctionInfo::isThumb1OnlyFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a0ca923fe17988bbe7dc155452c4b8253">llvm::ARMFunctionInfo::isThumb2Function</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a6c02973966a15241aedb2a1016de4ff3">llvm::ARMFunctionInfo::isThumbFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#ab4bf72d745b01eea298759754c9efeba">llvm::ARMFrameLowering::ResolveFrameIndexReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

### emitLoadConstPool() {#a5e4563cae7f10b41cdff9a61f1f6aaab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseRegisterInfo::emitLoadConstPool (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, unsigned SubIdx, int Val, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6">ARMCC::CondCodes</a> Pred=<a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">ARMCC::AL</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PredReg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>(), unsigned MIFlags=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
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

<p>emitLoadConstPool - Emits a load from constpool to materialize the specified immediate.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5e4d7acf58e87826a15b94d37144f2b">llvm::getDefRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getBaseRegister() {#afffd40779f75bf01f506173853995976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::ARMBaseRegisterInfo::getBaseRegister ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>.</p>


<p>Reference <a href="#ad7d3d20d0e64bd376f5dd31b1ffc716f">BasePtr</a>.</p>

</div>
</div>

### getCalleeSavedRegs() {#a8ae827683289cd88fddbe641f8608b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * ARMBaseRegisterInfo::getCalleeSavedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code Generation virtual methods...</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#aada6bb4af36a2736480f0c51fced2d58">llvm::ARMSubtarget::getPushPopSplitVariation</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a47487469642dbc444927b5e2f5f22ba2">llvm::ARMSubtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ae477aca96efeb96f5ad038393073a70c">llvm::ARMSubtarget::isMClass</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a60b8559634130214660d6f0270369838">llvm::ARMSubtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ab3f7c70dd539567001e35caea74ade4ba79139b30a7b6a6caf15fe7c26898cb1c">llvm::ARMSubtarget::SplitR11AAPCSSignRA</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ab3f7c70dd539567001e35caea74ade4ba2fba6120097ea9615c4a13a82fe8042d">llvm::ARMSubtarget::SplitR11WindowsSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ab3f7c70dd539567001e35caea74ade4ba5ba862e3a9b6eca2a66b539bd990761c">llvm::ARMSubtarget::SplitR7</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2f59b975114229e04efb87bbc8662224">llvm::ARMTargetLowering::supportSwiftError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>.</p>

</div>
</div>

### getCalleeSavedRegsViaCopy() {#ae538c50015c12adeb2477f4ee4b6d2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * ARMBaseRegisterInfo::getCalleeSavedRegsViaCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a2ae65435011d908ef30c57b5ad9cb479">llvm::ARMFunctionInfo::isSplitCSR</a>.</p>

</div>
</div>

### getCallPreservedMask() {#abb9d03a862069b7f3c4f446e0be8b826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * ARMBaseRegisterInfo::getCallPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a47487469642dbc444927b5e2f5f22ba2">llvm::ARMSubtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a60b8559634130214660d6f0270369838">llvm::ARMSubtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2f59b975114229e04efb87bbc8662224">llvm::ARMTargetLowering::supportSwiftError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>.</p>

</div>
</div>

### getCrossCopyRegClass() {#ae0f82d201deb3b2ab7fc56508761c752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * ARMBaseRegisterInfo::getCrossCopyRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>

</div>
</div>

### getFrameIndexInstrOffset() {#a235a0e236caca418542d097c0f0fca9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t ARMBaseRegisterInfo::getFrameIndexInstrOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a7d9742a01ea175053d76a714474d88a6">llvm::ARMII::AddrMode2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a3e943d975799a4c55333c54eac1a7991">llvm::ARMII::AddrMode3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a0209ae669364c237e24dbc0c4df6036e">llvm::ARMII::AddrMode5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a44874e651b75b372574cc861fee08896">llvm::ARMII::AddrMode_i12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4aeda154c828d692cd52ca6cce8765f9ae">llvm::ARMII::AddrModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a147ee44cd2b5425325839f5f0fa897ad">llvm::ARMII::AddrModeT1_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a4f27c00983ba7efdb7177e52c27584b9">llvm::ARMII::AddrModeT2_i12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a976ddbecac99af6819d058790e33e137">llvm::ARMII::AddrModeT2_i8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a8b4dc1a6ebdfa338bb66daa0dac9e6f5">llvm::ARMII::AddrModeT2_i8neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4aab60d264e38d6e79c407317e0524fcce">llvm::ARMII::AddrModeT2_i8pos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a29a2545f60f5e7f7cffd5e66b0d4cf87">llvm::ARM_AM::getAM2Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acda0e957b0c23c9beaa0d98238e140f3">llvm::ARM_AM::getAM2Op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a05a5f8eaf559ab55d1c8f7f9a7826a87">llvm::ARM_AM::getAM3Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acf54dffc0ef46cbffcaace8bcf2a3758">llvm::ARM_AM::getAM3Op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#abba23061634d5885171053eadb065aab">llvm::ARM_AM::getAM5Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a55a750d304cec7fccaa832e298b0ea23">llvm::ARM_AM::getAM5Op</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">llvm::ARM_AM::sub</a>.</p>


<p>Referenced by <a href="#a0f78fc5fd7a7ad8a92ce3a0ba77aecf4">isFrameOffsetLegal</a>.</p>

</div>
</div>

### getFrameRegister() {#ab064b648d7048dcfa869dc4021c54859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMBaseRegisterInfo::getFrameRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a3d0de6c30c8e5b1342e3f238e765221c">llvm::ARMSubtarget::getFramePointerReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="#ae7508374329448fb4210c15d9cc79ad7">needsFrameBaseReg</a>.</p>

</div>
</div>

### getIntraCallClobberedRegs() {#adfe29209cd2ac4c05d0f3739ec62d4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; ARMBaseRegisterInfo::getIntraCallClobberedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getLargestLegalSuperClass() {#a7d9301f2db70078a258c683a1046f569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * ARMBaseRegisterInfo::getLargestLegalSuperClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a7907102e3fee77f3105915033fa318a8">getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#ab0cdee375c69ef697e465bb73f9c1db3">llvm::TargetRegisterClass::superclasses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a9d1c3b55fe994ae967b25764ba0633cf">llvm::ThumbRegisterInfo::getLargestLegalSuperClass</a>.</p>

</div>
</div>

### getNoPreservedMask() {#a2ff75e03dd1389eb5ee642d134e15caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * ARMBaseRegisterInfo::getNoPreservedMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>

</div>
</div>

### getPointerRegClass() {#ac941eb7de76a190c2cf9c3957f716e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * ARMBaseRegisterInfo::getPointerRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Kind=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#aa10f0318d1d7bc44fb8df71b4e928124">llvm::ThumbRegisterInfo::getPointerRegClass</a>.</p>

</div>
</div>

### getRegAllocationHints() {#a77b81cc14aafd09d0e380b123cd06d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::getRegAllocationHints (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; &amp; Hints, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> * Matrix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp/#ac2221ad71323cfdfb9d5909e7d1f3775">getPairedGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a785a4e2daf4e5bf3f0836adbc4fb7e65">llvm::VirtRegMap::getPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ab28bf4ffd3e2223dab0527c9d7e18288">llvm::VirtRegMap::hasPhys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#a8989acb71bd355e02bcf3a930b5e54ea">Matrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armri/#a82ee67fc162fec9281be1b46631adcc2a450efd7bc999a24dcf0e793056da5958">llvm::ARMRI::RegLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armri/#a82ee67fc162fec9281be1b46631adcc2a2ae32bcb4cedddc631c44e40903546ec">llvm::ARMRI::RegPairEven</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armri/#a82ee67fc162fec9281be1b46631adcc2af83bd18d3419478667dd162f113dabb5">llvm::ARMRI::RegPairOdd</a>.</p>

</div>
</div>

### getRegPressureLimit() {#afe522c5b4605ba12fa3167e7959b6645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseRegisterInfo::getRegPressureLimit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a99cdf1b99c0f1b7e1bf2111aa7d2eaa3">llvm::MachineFrameInfo::isMaxCallFrameSizeComputed</a> and <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a90763d262e1a8ae31f254f901a105c06">llvm::ARMSubtarget::isR9Reserved</a>.</p>

</div>
</div>

### getReservedRegs() {#a185c9e3a52cfad64d466568e38c70308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector ARMBaseRegisterInfo::getReservedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad7d3d20d0e64bd376f5dd31b1ffc716f">BasePtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad67c067d2f90e51b2412f3c1117661b3a6fd9ec81643ee5a57f85a71951bfe13d">llvm::ARM::D16</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a3d0de6c30c8e5b1342e3f238e765221c">llvm::ARMSubtarget::getFramePointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a0e2ca33d941092c36d88209114f6fa8f">hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a90763d262e1a8ae31f254f901a105c06">llvm::ARMSubtarget::isR9Reserved</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a>.</p>


<p>Referenced by <a href="#ab20d327887091b2623315d7154f115a2">isAsmClobberable</a>.</p>

</div>
</div>

### getSEHRegNum() {#a828dacf15247e4e01d0b7ca88a6db6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARMBaseRegisterInfo::getSEHRegNum (unsigned i)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>.</p>

</div>
</div>

### getSjLjDispatchPreservedMask() {#a5e55ddeb12d25d6b87b3237661967c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * ARMBaseRegisterInfo::getSjLjDispatchPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a6a8b4e2c26c2c0aad751c5bf296858c6">llvm::ARMSubtarget::hasVFP2Base</a> and <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a2dc8447e2cf1376dbeebf919c0cddc9a">llvm::ARMSubtarget::isThumb1Only</a>.</p>

</div>
</div>

### getThisReturnPreservedMask() {#aee22c8e9e9eb4ac9413ce2adf676379c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * ARMBaseRegisterInfo::getThisReturnPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getThisReturnPreservedMask - Returns a call preserved mask specific to the case that 'returned' is on an i32 first argument if the calling convention is one that can (partially) model this attribute with a preserved mask (i.e.</p>


<p>it is a calling convention that uses the same register for the first i32 argument and an i32 return value)</p>


<p>Should return NULL in the case that the calling convention does not have this property</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a> and <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a60b8559634130214660d6f0270369838">llvm::ARMSubtarget::isTargetDarwin</a>.</p>

</div>
</div>

### getTLSCallPreservedMask() {#ac429f32d6cfbb8ea856855221d7b0324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * ARMBaseRegisterInfo::getTLSCallPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a60b8559634130214660d6f0270369838">llvm::ARMSubtarget::isTargetDarwin</a>.</p>

</div>
</div>

### hasBasePointer() {#a0e2ca33d941092c36d88209114f6fa8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::hasBasePointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa306e1d00f65a9bb1030e66e9d195a69">llvm::MachineFrameInfo::getLocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a5638ad10fa6d78adda170a382dc7f75a">llvm::ARMFunctionInfo::isThumb1OnlyFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a0ca923fe17988bbe7dc155452c4b8253">llvm::ARMFunctionInfo::isThumb2Function</a>.</p>


<p>Referenced by <a href="#a185c9e3a52cfad64d466568e38c70308">getReservedRegs</a> and <a href="#adb3bbd8da3d2794c25c551a779fef663">isInlineAsmReadOnlyReg</a>.</p>

</div>
</div>

### isAsmClobberable() {#ab20d327887091b2623315d7154f115a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::isAsmClobberable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="#a185c9e3a52cfad64d466568e38c70308">getReservedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>

</div>
</div>

### isFrameOffsetLegal() {#a0f78fc5fd7a7ad8a92ce3a0ba77aecf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::isFrameOffsetLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BaseReg, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a7d9742a01ea175053d76a714474d88a6">llvm::ARMII::AddrMode2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a3e943d975799a4c55333c54eac1a7991">llvm::ARMII::AddrMode3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a9dbb177d004cae6c3474b6aadc8ae07e">llvm::ARMII::AddrMode4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a0209ae669364c237e24dbc0c4df6036e">llvm::ARMII::AddrMode5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a8388bb748b26edbdb8bb5d5ab6f16853">llvm::ARMII::AddrMode6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a44874e651b75b372574cc861fee08896">llvm::ARMII::AddrMode_i12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4aeda154c828d692cd52ca6cce8765f9ae">llvm::ARMII::AddrModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a147ee44cd2b5425325839f5f0fa897ad">llvm::ARMII::AddrModeT1_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a4f27c00983ba7efdb7177e52c27584b9">llvm::ARMII::AddrModeT2_i12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a976ddbecac99af6819d058790e33e137">llvm::ARMII::AddrModeT2_i8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a8b4dc1a6ebdfa338bb66daa0dac9e6f5">llvm::ARMII::AddrModeT2_i8neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4aab60d264e38d6e79c407317e0524fcce">llvm::ARMII::AddrModeT2_i8pos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a235a0e236caca418542d097c0f0fca9c">getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ae7508374329448fb4210c15d9cc79ad7">needsFrameBaseReg</a>.</p>

</div>
</div>

### isInlineAsmReadOnlyReg() {#adb3bbd8da3d2794c25c551a779fef663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::isInlineAsmReadOnlyReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad7d3d20d0e64bd376f5dd31b1ffc716f">BasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a3d0de6c30c8e5b1342e3f238e765221c">llvm::ARMSubtarget::getFramePointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a0e2ca33d941092c36d88209114f6fa8f">hasBasePointer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a>.</p>

</div>
</div>

### materializeFrameBaseRegister() {#ac02c01e89c0ac7acc53bb50aeac772ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMBaseRegisterInfo::materializeFrameBaseRegister (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, int FrameIdx, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>materializeFrameBaseRegister - Insert defining instruction(s) for BaseReg to be a pointer to FrameIdx at the beginning of the basic block.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2c3e98260a6eb6daa3ba1da72a45e05">llvm::condCodeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a5638ad10fa6d78adda170a382dc7f75a">llvm::ARMFunctionInfo::isThumb1OnlyFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a6c02973966a15241aedb2a1016de4ff3">llvm::ARMFunctionInfo::isThumbFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### needsFrameBaseReg() {#ae7508374329448fb4210c15d9cc79ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::needsFrameBaseReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>needsFrameBaseReg - Returns true if the instruction's frame index reference would be better served by a base register other than FP or SP.</p>


<p>Used by LocalStackFrameAllocation to determine which frame index references it should create new base registers for.</p>


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee75d3e9f0900bee26680be79a90f9a3">canRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#ab064b648d7048dcfa869dc4021c54859">getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a38a536a09e7b29b14de24d3a0cb6f1b3">llvm::MachineFrameInfo::getLocalFrameMaxAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa306e1d00f65a9bb1030e66e9d195a69">llvm::MachineFrameInfo::getLocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="#a0f78fc5fd7a7ad8a92ce3a0ba77aecf4">isFrameOffsetLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a5638ad10fa6d78adda170a382dc7f75a">llvm::ARMFunctionInfo::isThumb1OnlyFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a6c02973966a15241aedb2a1016de4ff3">llvm::ARMFunctionInfo::isThumbFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### requiresFrameIndexScavenging() {#aff38ab5d18db335f91dd3fe93ff4014d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::requiresFrameIndexScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>

</div>
</div>

### requiresRegisterScavenging() {#ac25ab1983ee8331e6281acb26981712a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::requiresRegisterScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code Generation virtual methods...</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>

</div>
</div>

### requiresVirtualBaseRegisters() {#a4ab4194265d15e3af4f75a6630321156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::requiresVirtualBaseRegisters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>

</div>
</div>

### resolveFrameIndex() {#ac69f26dc070e18750b9974aaa24565ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseRegisterInfo::resolveFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BaseReg, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a5638ad10fa6d78adda170a382dc7f75a">llvm::ARMFunctionInfo::isThumb1OnlyFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a0ca923fe17988bbe7dc155452c4b8253">llvm::ARMFunctionInfo::isThumb2Function</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a6c02973966a15241aedb2a1016de4ff3">llvm::ARMFunctionInfo::isThumbFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#ab8e6b81acb0eec0b1d8ccda6db37697d">llvm::ThumbRegisterInfo::resolveFrameIndex</a>.</p>

</div>
</div>

### shouldCoalesce() {#a0dc0ac22a4727eaf94ec9a2fff5fa8b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::shouldCoalesce (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC, unsigned SubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC, unsigned DstSubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * NewRC, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SrcRC and DstRC will be morphed into NewRC if this returns true.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#ad3621e39db26f1bd8bc50d3d054a1a9c">llvm::ARMFunctionInfo::getCoalescedWeight</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### shouldRewriteCopySrc() {#a4360b9c445d8cc8fa2328c483241eff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseRegisterInfo::shouldRewriteCopySrc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DefRC, unsigned DefSubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC, unsigned SrcSubReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a5f57fdbb65e054ee2e03be0ffd3001b3">llvm::TargetRegisterInfo::shouldRewriteCopySrc</a>.</p>

</div>
</div>

### updateRegAllocHint() {#a2e4e7b801f3b166aebe037d065fa6923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseRegisterInfo::updateRegAllocHint (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armri/#a82ee67fc162fec9281be1b46631adcc2a2ae32bcb4cedddc631c44e40903546ec">llvm::ARMRI::RegPairEven</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armri/#a82ee67fc162fec9281be1b46631adcc2af83bd18d3419478667dd162f113dabb5">llvm::ARMRI::RegPairOdd</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BasePtr {#ad7d3d20d0e64bd376f5dd31b1ffc716f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMBaseRegisterInfo::BasePtr = ARM::R6</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BasePtr - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> physical register used as a base ptr in complex stack frames.</p>


<p>I.e., when we need a 3rd base, not just SP and FP, due to variable size stack objects.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aee75d3e9f0900bee26680be79a90f9a3">canRealignStack</a>, <a href="#afffd40779f75bf01f506173853995976">getBaseRegister</a>, <a href="#a185c9e3a52cfad64d466568e38c70308">getReservedRegs</a> and <a href="#adb3bbd8da3d2794c25c551a779fef663">isInlineAsmReadOnlyReg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp">ARMBaseRegisterInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
