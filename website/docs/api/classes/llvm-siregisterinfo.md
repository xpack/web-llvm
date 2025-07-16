---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/siregisterinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIRegisterInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SIRegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">Target/AMDGPU/SIRegisterInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/amdgpugenregisterinfo">AMDGPUGenRegisterInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4103353fd223c191f291d3ffaf5bfa4f">SIRegisterInfo</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed80e0d9bfe4e57de24283efa7572eb4">spillSGPRToVGPR</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe36d27e3fe50e1c4594b3438eeb8b8">getAlignedHighSGPRForRC</a> (const MachineFunction &amp;MF, const unsigned Align, const TargetRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the largest available SGPR aligned to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></span> for the register class <span class="doxyComputerOutput">RC</span>. <a href="#a6fe36d27e3fe50e1c4594b3438eeb8b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51db99e6baa393260b874d1d04e7ecdc">reservedPrivateSegmentBufferReg</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the end register initially reserved for the scratch buffer in case spilling is needed. <a href="#a51db99e6baa393260b874d1d04e7ecdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e00b2ca262e101590cc2335dded3d8">getMaxNumVectorRegs</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pair of maximum numbers of VGPRs and AGPRs that meet the number of waves per execution unit required for the function <span class="doxyComputerOutput">MF</span>. <a href="#a59e00b2ca262e101590cc2335dded3d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4a909a1725cc86437f4f350ab35cdb">isAsmClobberable</a> (const MachineFunction &amp;MF, MCRegister PhysReg) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44684a6923b734e7d14143bf086cbb87">getCalleeSavedRegs</a> (const MachineFunction *MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79100c984bb96e884a15246958f61c2d">getCalleeSavedRegsViaCopy</a> (const MachineFunction *MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231685f805cba88c2b061802b1b95052">getCallPreservedMask</a> (const MachineFunction &amp;MF, CallingConv::ID) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6927f52a74df8a472aae164cffd527b1">getNoPreservedMask</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6ed1642c7c6a0432f86928a5c102ba">getCSRFirstUseCost</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51be90716cd9b3020e0ca8a4bce547c0">getLargestLegalSuperClass</a> (const TargetRegisterClass *RC, const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317bd7480ba741300b70f6243d33ff1f">getFrameRegister</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449d102f1b4d3b881282d6609caf6023">hasBasePointer</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832c99f27458588b340a9c294f6fd200">getBaseRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa5409f4a9ae9129ad49bd05ba293f6">shouldRealignStack</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eafea62423808eaf1bec18900ec929e">requiresRegisterScavenging</a> (const MachineFunction &amp;Fn) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d3fc8e591bfc7b5854f86d00241221">requiresFrameIndexScavenging</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ab56a48816c54d3db51d4724304663">requiresFrameIndexReplacementScavenging</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ba4cd4553b5e0d7245b42c6d459418">requiresVirtualBaseRegisters</a> (const MachineFunction &amp;Fn) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a40d4d0736a73e47089ba3ef2e1566">getScratchInstrOffset</a> (const MachineInstr *MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc210f7d04be558143f8a891c892e550">getFrameIndexInstrOffset</a> (const MachineInstr *MI, int Idx) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae2e3ed0f579b512e6a38d0f116553ea">needsFrameBaseReg</a> (MachineInstr *MI, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c8d8abacb01c870f729e8d2027364f">materializeFrameBaseRegister</a> (MachineBasicBlock *MBB, int FrameIdx, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae803619fba0f2282f638ddd36ba004de">resolveFrameIndex</a> (MachineInstr &amp;MI, Register BaseReg, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0989f99e854e569e8096a89e73f2e046">isFrameOffsetLegal</a> (const MachineInstr *MI, Register BaseReg, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ec67a466802ee8e0c1f1b7aa7bbf39">getPointerRegClass</a> (const MachineFunction &amp;MF, unsigned Kind=0) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4861767cf942190a83cf6083003bba05">getCrossCopyRegClass</a> (const TargetRegisterClass *RC) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a legal register class to copy a register in the specified class to or from. <a href="#a4861767cf942190a83cf6083003bba05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee68072e1038a895a2998d78395db856">buildVGPRSpillLoadStore</a> (SGPRSpillBuilder &amp;SB, int Index, int Offset, bool IsLoad, bool IsKill=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad48896d5bbe85488559a5007c3a4b7df">spillSGPR</a> (MachineBasicBlock::iterator MI, int FI, RegScavenger *RS, SlotIndexes *Indexes=nullptr, LiveIntervals *LIS=nullptr, bool OnlyToVGPR=false, bool SpillToPhysVGPRLane=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">OnlyToVGPR</span> is true, this will only succeed if this manages to find a free VGPR lane to spill. <a href="#ad48896d5bbe85488559a5007c3a4b7df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab71844c6563b3998af3c09ff2e3368">restoreSGPR</a> (MachineBasicBlock::iterator MI, int FI, RegScavenger *RS, SlotIndexes *Indexes=nullptr, LiveIntervals *LIS=nullptr, bool OnlyToVGPR=false, bool SpillToPhysVGPRLane=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4103d19eae05425cf7aee3ad915250">spillEmergencySGPR</a> (MachineBasicBlock::iterator MI, MachineBasicBlock &amp;RestoreMBB, Register SGPR, RegScavenger *RS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a> (MachineBasicBlock::iterator MI, int SPAdj, unsigned FIOperandNum, RegScavenger *RS) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5236ffd9cb568bb917937e7273cc650a">eliminateSGPRToVGPRSpillFrameIndex</a> (MachineBasicBlock::iterator MI, int FI, RegScavenger *RS, SlotIndexes *Indexes=nullptr, LiveIntervals *LIS=nullptr, bool SpillToPhysVGPRLane=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of eliminateFrameIndex. <a href="#a5236ffd9cb568bb917937e7273cc650a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d23e7ce3b1f81486f99bad83a5d71a2">getRegAsmName</a> (MCRegister Reg) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954d76fe761bb4014b2da81cac2360cf">getHWRegIndex</a> (MCRegister Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a858849019ce7366904469c53972c54dc">getVGPRClassForBitWidth</a> (unsigned BitWidth) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c70283c6a0d2ce11aecfa43139e987e">getAGPRClassForBitWidth</a> (unsigned BitWidth) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a60ced6bc204b78bafcf33db515a087">getVectorSuperClassForBitWidth</a> (unsigned BitWidth) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab664dae585bc43224746468fa919da87">isSGPRClassID</a> (unsigned RCID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980c731f7723b02b66010f4fce010c0f">isSGPRReg</a> (const MachineRegisterInfo &amp;MRI, Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b864efe9f37aaee60c010d2e5e6eb0">isSGPRPhysReg</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add069634d629007ba8a03a426c6bfea7">isVectorSuperClass</a> (const TargetRegisterClass *RC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad38d8f2d6815113e60a7a04012e465a5">isVSSuperClass</a> (const TargetRegisterClass *RC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fcc4d3294381da29adb855c5f56c0d5">getEquivalentVGPRClass</a> (const TargetRegisterClass *SRC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c0bb4b4e2204e019541b6cd98bd9792">getEquivalentAGPRClass</a> (const TargetRegisterClass *SRC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981883145186bf6da58e5bd7f6476f30">getEquivalentSGPRClass</a> (const TargetRegisterClass *VRC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e83ecd12d46c80703ce5d3ef34ead33">getCompatibleSubRegClass</a> (const TargetRegisterClass *SuperRC, const TargetRegisterClass *SubRC, unsigned SubIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a register class which is compatible with <span class="doxyComputerOutput">SuperRC</span>, such that a subregister exists with class <span class="doxyComputerOutput">SubRC</span> with subregister index <span class="doxyComputerOutput">SubIdx</span>. <a href="#a0e83ecd12d46c80703ce5d3ef34ead33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891021470cc8979b7dfcc936fad1cd44">shouldRewriteCopySrc</a> (const TargetRegisterClass *DefRC, unsigned DefSubReg, const TargetRegisterClass *SrcRC, unsigned SrcSubReg) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83297079e933130ab3b78a428b7070e3">opCanUseLiteralConstant</a> (unsigned OpType) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f55007393b9c2edcdb84c55e5df5514">opCanUseInlineConstant</a> (unsigned OpType) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b7e735a8aa6ece99bb5e9ea399c7f4">findUnusedRegister</a> (const MachineRegisterInfo &amp;MRI, const TargetRegisterClass *RC, const MachineFunction &amp;MF, bool ReserveHighestVGPR=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a lowest register that is not used at any point in the function. <a href="#a18b7e735a8aa6ece99bb5e9ea399c7f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b95c7a5620b2e92ef8ca3aa8be15bd">getRegClassForReg</a> (const MachineRegisterInfo &amp;MRI, Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4eaf548fa62f15dc35f4018fef3707">getRegClassForOperandReg</a> (const MachineRegisterInfo &amp;MRI, const MachineOperand &amp;MO) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a549e07395027c7b32774e27e9f28bc91">isVGPR</a> (const MachineRegisterInfo &amp;MRI, Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc61376f4183268183912910024e1f2c">isAGPR</a> (const MachineRegisterInfo &amp;MRI, Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d63c5cc5bfab2094fae30cf9472d436">isVectorRegister</a> (const MachineRegisterInfo &amp;MRI, Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c2077ba7c905d8271fd4d7b9af0fe7">isDivergentRegClass</a> (const TargetRegisterClass *RC) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ec1a620b5a1409ba4bac8c1d6e4b5b">isUniformReg</a> (const MachineRegisterInfo &amp;MRI, const RegisterBankInfo &amp;RBI, Register Reg) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7ead7725a07da4240f0edea1e4a2d6">getRegSplitParts</a> (const TargetRegisterClass *RC, unsigned EltSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce857be755106a0d747fa67ac782857">shouldCoalesce</a> (MachineInstr *MI, const TargetRegisterClass *SrcRC, unsigned SubReg, const TargetRegisterClass *DstRC, unsigned DstSubReg, const TargetRegisterClass *NewRC, LiveIntervals &amp;LIS) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7dbd22ec4e0cc058f8290a8b98cacc6">getRegPressureLimit</a> (const TargetRegisterClass *RC, MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad176a9433aea8ba75bcf6413209240d">getRegPressureSetLimit</a> (const MachineFunction &amp;MF, unsigned Idx) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc03c7ece1270aa0066e484af24eb28f">getRegUnitPressureSets</a> (unsigned RegUnit) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42bd3548ca638f68b47f7996f163c2b7">getReturnAddressReg</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615681753cb320f792b5656571637921">getRegClassForSizeOnBank</a> (unsigned Size, const RegisterBank &amp;Bank) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809fe721e6e5d39e8029eac15928a983">getRegClassForTypeOnBank</a> (LLT Ty, const RegisterBank &amp;Bank) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a627e6584be398e0555f4b38d8f26f546">getConstrainedRegClassForOperand</a> (const MachineOperand &amp;MO, const MachineRegisterInfo &amp;MRI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3849d39b02d4071b4fca54e2c7f49c7">getBoolRC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13a2d4e77a20d7844faee6e8cbcec42">getWaveMaskRegClass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed9393956ff6935e29af9881de204f1f">getVGPR64Class</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbdf0119b398fd6464742936fe420056">getVCC</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9528c639f619ab6f7cee1a52e3a7472">getExec</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2008041a23dfc43ff1e90b014a2936">getRegClass</a> (unsigned RCID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96cdbab4e65a936880975a58e0dde922">findReachingDef</a> (Register Reg, unsigned SubReg, MachineInstr &amp;Use, MachineRegisterInfo &amp;MRI, LiveIntervals *LIS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423e24bdb9993c90a2c13e2c04ff257a">getAllVGPRRegMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2b27ba8592dbf1220ca840abdda38e">getAllAGPRRegMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a02e51c998cca0b6edec7728bde9479">getAllVectorRegMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d328ac32b1d8a39f355b3195db147ff">getAllAllocatableSRegMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7eff7d73e979a05739b21cc353f748c">getChannelFromSubReg</a> (unsigned SubReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1ce2155cda91c2070745f4aec2c66ac">getNumChannelsFromSubReg</a> (unsigned SubReg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2188a3779b5fa9631631a60b3512c81e">get32BitRegister</a> (MCPhysReg Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2adf69ba524926c5454f5d259c1c4dac">isProperlyAlignedRC</a> (const TargetRegisterClass &amp;RC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a24e95ba5416c84845c50bbf4c2ee4d">getProperlyAlignedRC</a> (const TargetRegisterClass *RC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8124351ef6dec4eeea242717aa9398c">getAllSGPR128</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all SGPR128 which satisfy the waves per execution unit requirement of the subtarget. <a href="#aa8124351ef6dec4eeea242717aa9398c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14decdeb6229c84439416eddcebafc29">getAllSGPR64</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all SGPR64 which satisfy the waves per execution unit requirement of the subtarget. <a href="#a14decdeb6229c84439416eddcebafc29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c8ff148cc4e90b6ae0362db6bb48bf1">getAllSGPR32</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all SGPR32 which satisfy the waves per execution unit requirement of the subtarget. <a href="#a4c8ff148cc4e90b6ae0362db6bb48bf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57982dfc711f20ecf31431bc37259cd7">buildSpillLoadStore</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, const DebugLoc &amp;DL, unsigned LoadStoreOp, int Index, Register ValueReg, bool ValueIsKill, MCRegister ScratchOffsetReg, int64_t InstrOffset, MachineMemOperand *MMO, RegScavenger *RS, LiveRegUnits *LiveUnits=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b7e264a1a447b652821dae53bb1993">getRegClassAlignmentNumBits</a> (const TargetRegisterClass *RC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade66e9017b034317e0a4ba23bfe66876">isRegClassAligned</a> (const TargetRegisterClass *RC, unsigned AlignNumBits) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae24a21441afe482d6119ffa30efc33c1">getSubRegAlignmentNumBits</a> (const TargetRegisterClass *RC, unsigned SubReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7435cc0e3ba036d3183793e46cdee546">getNumUsedPhysRegs</a> (const MachineRegisterInfo &amp;MRI, const TargetRegisterClass &amp;RC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0b6ddb4ec6dd34820e168d9c2a5224">getVRegFlagValue</a> (StringRef Name) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be1c0f1057f7c2a457719a6581ce49b">getVRegFlagsOfReg</a> (Register Reg, const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b20bef91a090d2b2fb43153c9d29bfd">reserveRegisterTuples</a> (BitVector &amp;, MCRegister Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871cbd1f1eb940f7783deb2dbc4fc5ec">ST</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1f1ebe12872b7a1cbccf98f75bfde5">SpillSGPRToVGPR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a7eea978dd4a31f4e33aedf028be3a1">isWave32</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93912d0b8967964dd59f2dbf25ceee55">RegPressureIgnoredUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1be43761db2568933db89648201ab15c">getSubRegFromChannel</a> (unsigned Channel, unsigned NumRegs=1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d029d76398d3153d0f6d8ab3be94c88">isChainScratchRegister</a> (Register VGPR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d8aef424553a9b93de21ced693f0b09">getSGPRClassForBitWidth</a> (unsigned BitWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a> (const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a> (const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a> (const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb8776ee5f539fe6391a6d521af25f1">hasVGPRs</a> (const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1364aa9eb8390d678c037be69450deb">hasAGPRs</a> (const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b17b04c6d4d3b578c7ba3497652df4">hasSGPRs</a> (const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4185689ad93fedfa57db7bfeb8ddd3">hasVectorRegisters</a> (const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd11f1c73a15ab0fc73bacd1cdb64a6">getNumCoveredRegs</a> (LaneBitmask LM)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::array&lt; std::vector&lt; int16_t &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1273be5e5df6942e8505bd30c59f3cb">RegSplitParts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sub reg indexes for getRegSplitParts. <a href="#ae1273be5e5df6942e8505bd30c59f3cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::array&lt; std::array&lt; uint16_t, 32 &gt;, 9 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e3de70db165e23a99e7661e0dd1d291">SubRegFromChannelTable</a></td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIRegisterInfo() {#a4103353fd223c191f291d3ffaf5bfa4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIRegisterInfo::SIRegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a97c95e670f51481c3335f17610341b38">EnableSpillSGPRToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a822cab8661beb03276b0566d33e41592">llvm::MCRegister::from</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a266833fddf153d13701fb723996d3155">llvm::AMDGPU::isHi16Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a28f217b28ea2d167112e0b86d1e4dd39">SubRegFromChannelTableWidthMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildSpillLoadStore() {#a57982dfc711f20ecf31431bc37259cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIRegisterInfo::buildSpillLoadStore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, unsigned LoadStoreOp, int Index, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValueReg, bool ValueIsKill, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> ScratchOffsetReg, int64_t InstrOffset, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS, <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> * LiveUnits=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a3996f7c3774880bfe32422602fe34f9c">llvm::LiveRegUnits::available</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5e4d7acf58e87826a15b94d37144f2b">llvm::getDefRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#ab991bb1444579648a165d1b134a0854d">llvm::MachineMemOperand::getFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a328299d8f8d9100f6eaadc2bbf13ba43">llvm::AMDGPU::getFlatScratchInstSTfromSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2c49a690cf18ca46eda313ffdfe93ac5">llvm::AMDGPU::getFlatScratchInstSVfromSS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a7dc3779dd98f912496a86e4bd7174576">getFlatScratchSpillOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#af684573fd6deeb84f46bd0fc7d11483d">getOffenMUBUFLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a0bce5d32f25712c3d538ba9892f7bab7">getOffenMUBUFStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#acc8a2c40a5d623bd8c7c28e93eda91d3">llvm::AMDGPU::getRegBitWidth</a>, <a href="#a77b95c7a5620b2e92ef8ca3aa8be15bd">getRegClassForReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a1be43761db2568933db89648201ab15c">getSubRegFromChannel</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a9459055a98e20980521289e8d20fcc7e">llvm::MachinePointerInfo::getWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a27037167fddcdde3b6207d025267bbfc">llvm::RegScavenger::isRegUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a53ca7cff9e929ba372da9780fdd44b02">llvm::MachineRegisterInfo::isReserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca52f68ce5f52560b3ddb63ce8b2bd75">llvm::MOLastUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0ac990e2b3f7973d16c33555e9adf9aeade2c15857e3d2b12a4459c3510421493">llvm::MachineInstr::ReloadReuse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a62d08c8303092539ecb1fde389108e7a">llvm::RegScavenger::scavengeRegisterBackwards</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a698b6937d98b7ee400dee8b7b3c8a4bd">llvm::MachineInstr::setAsmPrinterFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a34542ec002baa6b027a6d05644c6bb2e">llvm::RegScavenger::setRegUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#adfdb32bd422a7613ae83c10f2841abf7">spillVGPRtoAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a8154ff62ee9b4a9eaca3572120081634">llvm::AMDGPU::CPol::TH_LU</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#aee68072e1038a895a2998d78395db856">buildVGPRSpillLoadStore</a> and <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a>.</p>

</div>
</div>

### buildVGPRSpillLoadStore() {#aee68072e1038a895a2998d78395db856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIRegisterInfo::buildVGPRSpillLoadStore (<a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder">SGPRSpillBuilder</a> &amp; SB, int Index, int Offset, bool IsLoad, bool IsKill=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 1921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aa750847e3dbb44a3dbf3c143151b895e">llvm::SIMachineFunctionInfo::addToSpilledVGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a57982dfc711f20ecf31431bc37259cd7">buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a6bcb85b82e6330375b977191fef41e2b">llvm::SGPRSpillBuilder::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#aff46ff3cb1f469b01f6171c8134934ca">llvm::SGPRSpillBuilder::EltSize</a>, <a href="#a832c99f27458588b340a9c294f6fd200">getBaseRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#a317bd7480ba741300b70f6243d33ff1f">getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="#a449d102f1b4d3b881282d6609caf6023">hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ad83a7a6b291c68ccc27722290777f333">llvm::SGPRSpillBuilder::MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ad37a50e8e31fa920654f835564ec022a">llvm::SGPRSpillBuilder::MF</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a1aec2625932d694fc229189a21239233">llvm::SGPRSpillBuilder::MFI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#aa29651d0ae788b6421aaf620050ee9fc">llvm::SGPRSpillBuilder::MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a56a1d04bcd3219469b87445ae2df358d">llvm::SGPRSpillBuilder::RS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a29a8016e50342e4598b3cb8a6601694f">llvm::TargetStackID::SGPRSpill</a> and <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a25f41f0ca74f2026ead9ed683f10e6b3">llvm::SGPRSpillBuilder::TmpVGPR</a>.</p>

</div>
</div>

### eliminateFrameIndex() {#acd7a7dc7a2d3ba79fe5ee12378638317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::eliminateFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, int SPAdj, unsigned FIOperandNum, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 2276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aa750847e3dbb44a3dbf3c143151b895e">llvm::SIMachineFunctionInfo::addToSpilledVGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a66ba876f71016493af6fd1dc6980d912">buildMUBUFOffsetLoadStore</a>, <a href="#a57982dfc711f20ecf31431bc37259cd7">buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a>, <a href="#a832c99f27458588b340a9c294f6fd200">getBaseRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a328299d8f8d9100f6eaadc2bbf13ba43">llvm::AMDGPU::getFlatScratchInstSTfromSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5c4e292db193538fa8ef82438d1ca2e2">llvm::AMDGPU::getFlatScratchInstSVfromSVS</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#a317bd7480ba741300b70f6243d33ff1f">getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a999c78fd2b7e94a4831025beed90e47d">getNumSubRegsForSpillOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#ad5f891a5d9822c7aab1b8bb0190a522f">llvm::DstOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2f10d8d12924c5866f49408dad1b8f1f">llvm::SIMachineFunctionInfo::getScratchRSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a62da22e6fbef4231a8fb45ae9aaf147c">llvm::SIMachineFunctionInfo::getSGPRForEXECCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2afcc4a332bb78d31847fd4a394a5aeb">llvm::SIMachineFunctionInfo::getStackPtrOffsetReg</a>, <a href="#a449d102f1b4d3b881282d6609caf6023">hasBasePointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a4a54a8e4e1d0b402f3cfd22a32bb3452">llvm::AMDGPUMachineFunction::isBottomOfStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a901ba4ff66898215882da41143ddf69a">llvm::AMDGPU::isInlinableIntLiteral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a79ce723bbdcb8a66b32fec6499ecd9f9">llvm::AMDGPU::isInlinableLiteral32</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a27037167fddcdde3b6207d025267bbfc">llvm::RegScavenger::isRegUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a53ca7cff9e929ba372da9780fdd44b02">llvm::MachineRegisterInfo::isReserved</a>, <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0aab14aaa9761a9af59b094090851ca3">llvm::SIInstrInfo::isVOP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a4c5b26e761294db59c1ad1cc6fc1d0ba">llvm::RegState::Renamable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#a2ab71844c6563b3998af3c09ff2e3368">restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a62d08c8303092539ecb1fde389108e7a">llvm::RegScavenger::scavengeRegisterBackwards</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a48bcf9eb66f880de8e7f4d0fcc8af320">llvm::MachineOperand::setIsRenamable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a45ffb8b95e5b75eeb68be7d300eb9618">llvm::MachineInstrBuilder::setOperandDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="#ad48896d5bbe85488559a5007c3a4b7df">spillSGPR</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### eliminateSGPRToVGPRSpillFrameIndex() {#a5236ffd9cb568bb917937e7273cc650a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::eliminateSGPRToVGPRSpillFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, int FI, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes=nullptr, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr, bool SpillToPhysVGPRLane=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special case of eliminateFrameIndex.</p>


<p>Returns true if the SGPR was spilled to a VGPR and the stack slot can be safely eliminated when all other users are handled.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 2237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a2ab71844c6563b3998af3c09ff2e3368">restoreSGPR</a> and <a href="#ad48896d5bbe85488559a5007c3a4b7df">spillSGPR</a>.</p>

</div>
</div>

### findReachingDef() {#a96cdbab4e65a936880975a58e0dde922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIRegisterInfo::findReachingDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned SubReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Use, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6dca6a95f0921bc90d88adfddd44e304">llvm::LiveIntervals::getDomTree</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1882fe2a570964e4c6abb0eac322beab">llvm::LiveIntervals::getInstructionFromIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6f3043b29023d270fc4bc5062dff7cee">llvm::LiveIntervals::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a7b2ec2588cc48710e468563a0e71d24a">llvm::LiveIntervals::getRegUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a11cd70de340f310acc70781d57a00136">llvm::LiveIntervals::hasInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a5bcdd85778add4287db384472cde8acd">llvm::SlotIndex::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### findUnusedRegister() {#a18b7e735a8aa6ece99bb5e9ea399c7f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister SIRegisterInfo::findUnusedRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool ReserveHighestRegister=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a lowest register that is not used at any point in the function.</p>


<p>If all registers are used, then this function will return AMDGPU::NoRegister. If <span class="doxyComputerOutput">ReserveHighestRegister</span> = true, then return highest unused register.</p>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

### get32BitRegister() {#a2188a3779b5fa9631631a60b3512c81e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPhysReg SIRegisterInfo::get32BitRegister (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getAGPRClassForBitWidth() {#a5c70283c6a0d2ce11aecfa43139e987e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getAGPRClassForBitWidth (unsigned BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a579681b680a30ed1485e42c4b0b608ca">getAlignedAGPRClassForBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a18480f5029e47987aa4272813c9f1851">getAnyAGPRClassForBitWidth</a>.</p>


<p>Referenced by <a href="#a7c0bb4b4e2204e019541b6cd98bd9792">getEquivalentAGPRClass</a>, <a href="#a615681753cb320f792b5656571637921">getRegClassForSizeOnBank</a> and <a href="#a2adf69ba524926c5454f5d259c1c4dac">isProperlyAlignedRC</a>.</p>

</div>
</div>

### getAlignedHighSGPRForRC() {#a6fe36d27e3fe50e1c4594b3438eeb8b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister SIRegisterInfo::getAlignedHighSGPRForRC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Align, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the largest available SGPR aligned to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></span> for the register class <span class="doxyComputerOutput">RC</span>.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>.</p>


<p>Referenced by <a href="#a51db99e6baa393260b874d1d04e7ecdc">reservedPrivateSegmentBufferReg</a>.</p>

</div>
</div>

### getAllAGPRRegMask() {#abb2b27ba8592dbf1220ca840abdda38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * SIRegisterInfo::getAllAGPRRegMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getAllAllocatableSRegMask() {#a6d328ac32b1d8a39f355b3195db147ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * SIRegisterInfo::getAllAllocatableSRegMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getAllSGPR128() {#aa8124351ef6dec4eeea242717aa9398c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; SIRegisterInfo::getAllSGPR128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all SGPR128 which satisfy the waves per execution unit requirement of the subtarget.</p>

<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getAllSGPR32() {#a4c8ff148cc4e90b6ae0362db6bb48bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; SIRegisterInfo::getAllSGPR32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all SGPR32 which satisfy the waves per execution unit requirement of the subtarget.</p>

<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getAllSGPR64() {#a14decdeb6229c84439416eddcebafc29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; SIRegisterInfo::getAllSGPR64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all SGPR64 which satisfy the waves per execution unit requirement of the subtarget.</p>

<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getAllVectorRegMask() {#a7a02e51c998cca0b6edec7728bde9479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * SIRegisterInfo::getAllVectorRegMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getAllVGPRRegMask() {#a423e24bdb9993c90a2c13e2c04ff257a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * SIRegisterInfo::getAllVGPRRegMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getBaseRegister() {#a832c99f27458588b340a9c294f6fd200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIRegisterInfo::getBaseRegister ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#aee68072e1038a895a2998d78395db856">buildVGPRSpillLoadStore</a>, <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a> and <a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a>.</p>

</div>
</div>

### getBoolRC() {#ac3849d39b02d4071b4fca54e2c7f49c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::SIRegisterInfo::getBoolRC ()</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a531864eddd4fb4fb020cf583a10507c1">llvm::GCNSubtarget::getBoolRC</a> and <a href="#a0e2008041a23dfc43ff1e90b014a2936">getRegClass</a>.</p>

</div>
</div>

### getCalleeSavedRegs() {#a44684a6923b734e7d14143bf086cbb87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * SIRegisterInfo::getCalleeSavedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca521c5b7a44a8222c814379b57481aec9">llvm::CallingConv::AMDGPU_CS_ChainPreserve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f9824c54cfd32b3e38c01d5331f318b">llvm::CallingConv::AMDGPU_Gfx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca94ec9273479164e4aec1d5d91b71dc85">llvm::CallingConv::Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>.</p>

</div>
</div>

### getCalleeSavedRegsViaCopy() {#a79100c984bb96e884a15246958f61c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * SIRegisterInfo::getCalleeSavedRegsViaCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getCallPreservedMask() {#a231685f805cba88c2b061802b1b95052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * SIRegisterInfo::getCallPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8d298f27ddf40e08cd5aacea9837784f">llvm::CallingConv::AMDGPU_CS_Chain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca521c5b7a44a8222c814379b57481aec9">llvm::CallingConv::AMDGPU_CS_ChainPreserve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f9824c54cfd32b3e38c01d5331f318b">llvm::CallingConv::AMDGPU_Gfx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca94ec9273479164e4aec1d5d91b71dc85">llvm::CallingConv::Cold</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>.</p>

</div>
</div>

### getChannelFromSubReg() {#ad7eff7d73e979a05739b21cc353f748c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIRegisterInfo::getChannelFromSubReg (unsigned SubReg)</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a>.</p>

</div>
</div>

### getCompatibleSubRegClass() {#a0e83ecd12d46c80703ce5d3ef34ead33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getCompatibleSubRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SuperRC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SubRC, unsigned SubIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a register class which is compatible with <span class="doxyComputerOutput">SuperRC</span>, such that a subregister exists with class <span class="doxyComputerOutput">SubRC</span> with subregister index <span class="doxyComputerOutput">SubIdx</span>.</p>


<p>If this is impossible (e.g., an unaligned subregister index within a register tuple), return null.</p>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a8ea8ce186fc4a70ad542e74d015d84ed">llvm::TargetRegisterClass::hasSubClassEq</a>.</p>

</div>
</div>

### getConstrainedRegClassForOperand() {#a627e6584be398e0555f4b38d8f26f546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getConstrainedRegClassForOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a809fe721e6e5d39e8029eac15928a983">getRegClassForTypeOnBank</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### getCrossCopyRegClass() {#a4861767cf942190a83cf6083003bba05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getCrossCopyRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a legal register class to copy a register in the specified class to or from.</p>


<p>If it is possible to copy the register directly without using a cross register class copy, return the specified RC. Returns NULL if it is not possible to copy between two registers of the specified class.</p>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#a2fcc4d3294381da29adb855c5f56c0d5">getEquivalentVGPRClass</a>, <a href="#ae13a2d4e77a20d7844faee6e8cbcec42">getWaveMaskRegClass</a> and <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>.</p>

</div>
</div>

### getCSRFirstUseCost() {#aad6ed1642c7c6a0432f86928a5c102ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIRegisterInfo::getCSRFirstUseCost ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

### getEquivalentAGPRClass() {#a7c0bb4b4e2204e019541b6cd98bd9792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getEquivalentAGPRClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SRC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An AGPR reg class with the same width as <span class="doxyComputerOutput">SRC</span></p></dd>
</dl>


<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5c70283c6a0d2ce11aecfa43139e987e">getAGPRClassForBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getEquivalentSGPRClass() {#a981883145186bf6da58e5bd7f6476f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getEquivalentSGPRClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * VRC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A SGPR reg class with the same width as <span class="doxyComputerOutput">SRC</span></p></dd>
</dl>


<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7d8aef424553a9b93de21ced693f0b09">getSGPRClassForBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getEquivalentVGPRClass() {#a2fcc4d3294381da29adb855c5f56c0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getEquivalentVGPRClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SRC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A VGPR reg class with the same width as <span class="doxyComputerOutput">SRC</span></p></dd>
</dl>


<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a858849019ce7366904469c53972c54dc">getVGPRClassForBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a4861767cf942190a83cf6083003bba05">getCrossCopyRegClass</a>.</p>

</div>
</div>

### getExec() {#ad9528c639f619ab6f7cee1a52e3a7472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister SIRegisterInfo::getExec ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmasking-cpp-/sioptimizeexecmasking/#a3f94a6aec90b35cbf3ae3345cba041de">anonymous{SIOptimizeExecMasking.cpp}::SIOptimizeExecMasking::run</a>.</p>

</div>
</div>

### getFrameIndexInstrOffset() {#adc210f7d04be558143f8a891c892e550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t SIRegisterInfo::getFrameIndexInstrOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="#a08a40d4d0736a73e47089ba3ef2e1566">getScratchInstrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a13fdc38a01504ed9a44abd1c9018737d">llvm::SIInstrInfo::isFLATScratch</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8616d2d8f4c04005569e89bcfe67e421">llvm::SIInstrInfo::isMUBUF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getFrameRegister() {#a317bd7480ba741300b70f6243d33ff1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIRegisterInfo::getFrameRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="#aee68072e1038a895a2998d78395db856">buildVGPRSpillLoadStore</a>, <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a1d2fa221d761f2dbaeb65823e305b8d7">llvm::SIFrameLowering::getFrameIndexReference</a>.</p>

</div>
</div>

### getHWRegIndex() {#a954d76fe761bb4014b2da81cac2360cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIRegisterInfo::getHWRegIndex (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a7435cc0e3ba036d3183793e46cdee546">getNumUsedPhysRegs</a>, <a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>.</p>

</div>
</div>

### getLargestLegalSuperClass() {#a51be90716cd9b3020e0ca8a4bce547c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getLargestLegalSuperClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a7bfa77f06f5334b1488db754fd694959">llvm::TargetRegisterInfo::getLargestLegalSuperClass</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a> and <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a>.</p>

</div>
</div>

### getMaxNumVectorRegs() {#a59e00b2ca262e101590cc2335dded3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; SIRegisterInfo::getMaxNumVectorRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pair of maximum numbers of VGPRs and AGPRs that meet the number of waves per execution unit required for the function <span class="doxyComputerOutput">MF</span>.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a024479869943dfba001bb5701d62a243">llvm::SIMachineFunctionInfo::usesAGPRs</a>.</p>


<p>Referenced by <a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a>.</p>

</div>
</div>

### getNoPreservedMask() {#a6927f52a74df8a472aae164cffd527b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * SIRegisterInfo::getNoPreservedMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getNumChannelsFromSubReg() {#aa1ce2155cda91c2070745f4aec2c66ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIRegisterInfo::getNumChannelsFromSubReg (unsigned SubReg)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#a1dd11f1c73a15ab0fc73bacd1cdb64a6">getNumCoveredRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### getNumUsedPhysRegs() {#a7435cc0e3ba036d3183793e46cdee546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIRegisterInfo::getNumUsedPhysRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#a954d76fe761bb4014b2da81cac2360cf">getHWRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a208148ec39e21c8c4591ad914e318dc9">llvm::TargetRegisterClass::getRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

### getPointerRegClass() {#ac9ec67a466802ee8e0c1f1b7aa7bbf39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getPointerRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Kind=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getProperlyAlignedRC() {#a2a24e95ba5416c84845c50bbf4c2ee4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getProperlyAlignedRC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a579681b680a30ed1485e42c4b0b608ca">getAlignedAGPRClassForBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#ab0c04890a9c392cb7719d1609f47a8ab">getAlignedVectorSuperClassForBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a87ad104ee3bd1baee94c325741fbad84">getAlignedVGPRClassForBitWidth</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>, <a href="#add069634d629007ba8a03a426c6bfea7">isVectorSuperClass</a>, <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a60ab44d62adfcff55385762363e231cf">adjustAllocatableRegClass</a>.</p>

</div>
</div>

### getRegAsmName() {#a6d23e7ce3b1f81486f99bad83a5d71a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef SIRegisterInfo::getRegAsmName (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a2d1579b3e66d752d5d8ecae54574c9c8">llvm::AMDGPUInstPrinter::getRegisterName</a>.</p>

</div>
</div>

### getRegClass() {#a0e2008041a23dfc43ff1e90b014a2936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getRegClass (unsigned RCID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#ac3849d39b02d4071b4fca54e2c7f49c7">getBoolRC</a> and <a href="#ae13a2d4e77a20d7844faee6e8cbcec42">getWaveMaskRegClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a60ab44d62adfcff55385762363e231cf">adjustAllocatableRegClass</a> and <a href="#ab664dae585bc43224746468fa919da87">isSGPRClassID</a>.</p>

</div>
</div>

### getRegClassAlignmentNumBits() {#af3b7e264a1a447b652821dae53bb1993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIRegisterInfo::getRegClassAlignmentNumBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aa31daf7b6aafc48bf39ca586d5f89c07f">llvm::RegTupleAlignUnitsMask</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a1cc1ce48e42ab86c1419314bef07f00b">llvm::TargetRegisterClass::TSFlags</a>.</p>


<p>Referenced by <a href="#ade66e9017b034317e0a4ba23bfe66876">isRegClassAligned</a>.</p>

</div>
</div>

### getRegClassForOperandReg() {#aae4eaf548fa62f15dc35f4018fef3707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getRegClassForOperandReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a77b95c7a5620b2e92ef8ca3aa8be15bd">getRegClassForReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### getRegClassForReg() {#a77b95c7a5620b2e92ef8ca3aa8be15bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getRegClassForReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a57982dfc711f20ecf31431bc37259cd7">buildSpillLoadStore</a>, <a href="#aae4eaf548fa62f15dc35f4018fef3707">getRegClassForOperandReg</a>, <a href="#acc61376f4183268183912910024e1f2c">isAGPR</a> and <a href="#a549e07395027c7b32774e27e9f28bc91">isVGPR</a>.</p>

</div>
</div>

### getRegClassForSizeOnBank() {#a615681753cb320f792b5656571637921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getRegClassForSizeOnBank (unsigned Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; Bank)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5c70283c6a0d2ce11aecfa43139e987e">getAGPRClassForBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="#a7d8aef424553a9b93de21ced693f0b09">getSGPRClassForBitWidth</a>, <a href="#a858849019ce7366904469c53972c54dc">getVGPRClassForBitWidth</a>, <a href="#ae13a2d4e77a20d7844faee6e8cbcec42">getWaveMaskRegClass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a809fe721e6e5d39e8029eac15928a983">getRegClassForTypeOnBank</a>.</p>

</div>
</div>

### getRegClassForTypeOnBank() {#a809fe721e6e5d39e8029eac15928a983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::SIRegisterInfo::getRegClassForTypeOnBank (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; Bank)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>Reference <a href="#a615681753cb320f792b5656571637921">getRegClassForSizeOnBank</a>.</p>


<p>Referenced by <a href="#a627e6584be398e0555f4b38d8f26f546">getConstrainedRegClassForOperand</a>.</p>

</div>
</div>

### getRegPressureLimit() {#aa7dbd22ec4e0cc058f8290a8b98cacc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIRegisterInfo::getRegPressureLimit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3642 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>.</p>


<p>Referenced by <a href="#aad176a9433aea8ba75bcf6413209240d">getRegPressureSetLimit</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>.</p>

</div>
</div>

### getRegPressureSetLimit() {#aad176a9433aea8ba75bcf6413209240d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIRegisterInfo::getRegPressureSetLimit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#aa7dbd22ec4e0cc058f8290a8b98cacc6">getRegPressureLimit</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getRegSplitParts() {#a4b7ead7725a07da4240f0edea1e4a2d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; int16_t &gt; SIRegisterInfo::getRegSplitParts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned EltSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#acc8a2c40a5d623bd8c7c28e93eda91d3">llvm::AMDGPU::getRegBitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a>.</p>

</div>
</div>

### getRegUnitPressureSets() {#afc03c7ece1270aa0066e484af24eb28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int * SIRegisterInfo::getRegUnitPressureSets (unsigned RegUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a>.</p>

</div>
</div>

### getReservedRegs() {#aae11cbd7196aeff4a4b2a12be9835f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector SIRegisterInfo::getReservedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#ae308e6ee93ceb33e921d72d659230669">llvm::BitVector::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a03cd6f65abab2f2a3a529436312672ae">llvm::SIMachineFunctionInfo::getAGPRSpillVGPRs</a>, <a href="#a832c99f27458588b340a9c294f6fd200">getBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8b9fc912e50d4b2f7e3173b59e33ed76">llvm::SIMachineFunctionInfo::getFrameOffsetReg</a>, <a href="#a954d76fe761bb4014b2da81cac2360cf">getHWRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a21318dc0d2ad096d488aa3bfe4248c68">llvm::SIMachineFunctionInfo::getLongBranchReservedReg</a>, <a href="#a59e00b2ca262e101590cc2335dded3d8">getMaxNumVectorRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a98bf94f5163bc94294a5ad5ab7b2935c">llvm::SIMachineFunctionInfo::getNonWWMRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2f10d8d12924c5866f49408dad1b8f1f">llvm::SIMachineFunctionInfo::getScratchRSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a62da22e6fbef4231a8fb45ae9aaf147c">llvm::SIMachineFunctionInfo::getSGPRForEXECCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2afcc4a332bb78d31847fd4a394a5aeb">llvm::SIMachineFunctionInfo::getStackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a7f30f9a28894281de1c9f3d039eaa75f">llvm::SIMachineFunctionInfo::getVGPRForAGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a3ad38929c0ec14005197226cd279d7c6">llvm::SIMachineFunctionInfo::getVGPRSpillAGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ac90363de2bb9275d5c5939845d1cd5f6">llvm::SIMachineFunctionInfo::getWWMReservedRegs</a>, <a href="#a449d102f1b4d3b881282d6609caf6023">hasBasePointer</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>, <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a>, <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>

</div>
</div>

### getReturnAddressReg() {#a42bd3548ca638f68b47f7996f163c2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister SIRegisterInfo::getReturnAddressReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getScratchInstrOffset() {#a08a40d4d0736a73e47089ba3ef2e1566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t SIRegisterInfo::getScratchInstrOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a13fdc38a01504ed9a44abd1c9018737d">llvm::SIInstrInfo::isFLATScratch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8616d2d8f4c04005569e89bcfe67e421">llvm::SIInstrInfo::isMUBUF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#adc210f7d04be558143f8a891c892e550">getFrameIndexInstrOffset</a>, <a href="#a0989f99e854e569e8096a89e73f2e046">isFrameOffsetLegal</a> and <a href="#aae2e3ed0f579b512e6a38d0f116553ea">needsFrameBaseReg</a>.</p>

</div>
</div>

### getSubRegAlignmentNumBits() {#ae24a21441afe482d6119ffa30efc33c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIRegisterInfo::getSubRegAlignmentNumBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned SubReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aab50fe4810eed28d1cabb48bd46f77f77">llvm::HasAGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aa04f97be66117d82353b26db62b1edb9f">llvm::HasSGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aa7cc027812f1a15199cc2980ee11fcb64">llvm::HasVGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aa921d7055b6159c0f2fb71e306d752ed7">llvm::RegKindMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a1cc1ce48e42ab86c1419314bef07f00b">llvm::TargetRegisterClass::TSFlags</a>.</p>

</div>
</div>

### getVCC() {#adbdf0119b398fd6464742936fe420056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister SIRegisterInfo::getVCC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getVectorSuperClassForBitWidth() {#a3a60ced6bc204b78bafcf33db515a087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getVectorSuperClassForBitWidth (unsigned BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#ab0c04890a9c392cb7719d1609f47a8ab">getAlignedVectorSuperClassForBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#abdad2be7dc25d794785c9e91b5ac2e65">getAnyVectorSuperClassForBitWidth</a>.</p>


<p>Referenced by <a href="#a2adf69ba524926c5454f5d259c1c4dac">isProperlyAlignedRC</a>.</p>

</div>
</div>

### getVGPR64Class() {#aed9393956ff6935e29af9881de204f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getVGPR64Class ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### getVGPRClassForBitWidth() {#a858849019ce7366904469c53972c54dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getVGPRClassForBitWidth (unsigned BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a87ad104ee3bd1baee94c325741fbad84">getAlignedVGPRClassForBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a92ee7062b6ed2a9e052ae150659363aa">getAnyVGPRClassForBitWidth</a>.</p>


<p>Referenced by <a href="#a2fcc4d3294381da29adb855c5f56c0d5">getEquivalentVGPRClass</a>, <a href="#a615681753cb320f792b5656571637921">getRegClassForSizeOnBank</a> and <a href="#a2adf69ba524926c5454f5d259c1c4dac">isProperlyAlignedRC</a>.</p>

</div>
</div>

### getVRegFlagsOfReg() {#a9be1c0f1057f7c2a457719a6581ce49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; StringLiteral &gt; SIRegisterInfo::getVRegFlagsOfReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/virtregflag/#ae40fa7ccf9ef4e1fa2db150e4b74f7a9a31784c8e60845a8b46a9de185dec5645">llvm::AMDGPU::VirtRegFlag::WWM_REG</a>.</p>

</div>
</div>

### getVRegFlagValue() {#ada0b6ddb4ec6dd34820e168d9c2a5224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint8_t &gt; llvm::SIRegisterInfo::getVRegFlagValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/virtregflag/#ae40fa7ccf9ef4e1fa2db150e4b74f7a9a31784c8e60845a8b46a9de185dec5645">llvm::AMDGPU::VirtRegFlag::WWM_REG</a>.</p>

</div>
</div>

### getWaveMaskRegClass() {#ae13a2d4e77a20d7844faee6e8cbcec42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::SIRegisterInfo::getWaveMaskRegClass ()</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a4861767cf942190a83cf6083003bba05">getCrossCopyRegClass</a>, <a href="#a0e2008041a23dfc43ff1e90b014a2936">getRegClass</a> and <a href="#a615681753cb320f792b5656571637921">getRegClassForSizeOnBank</a>.</p>

</div>
</div>

### hasBasePointer() {#a449d102f1b4d3b881282d6609caf6023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::hasBasePointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="#a2aa5409f4a9ae9129ad49bd05ba293f6">shouldRealignStack</a>.</p>


<p>Referenced by <a href="#aee68072e1038a895a2998d78395db856">buildVGPRSpillLoadStore</a>, <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a> and <a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a>.</p>

</div>
</div>

### isAGPR() {#acc61376f4183268183912910024e1f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isAGPR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#a77b95c7a5620b2e92ef8ca3aa8be15bd">getRegClassForReg</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a6d63c5cc5bfab2094fae30cf9472d436">isVectorRegister</a>.</p>

</div>
</div>

### isAsmClobberable() {#a5c4a909a1725cc86437f4f350ab35cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isAsmClobberable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a53ca7cff9e929ba372da9780fdd44b02">llvm::MachineRegisterInfo::isReserved</a>.</p>

</div>
</div>

### isDivergentRegClass() {#ac1c2077ba7c905d8271fd4d7b9af0fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isDivergentRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>Reference <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a>.</p>

</div>
</div>

### isFrameOffsetLegal() {#a0989f99e854e569e8096a89e73f2e046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isFrameOffsetLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BaseReg, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a>, <a href="#a08a40d4d0736a73e47089ba3ef2e1566">getScratchInstrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a13fdc38a01504ed9a44abd1c9018737d">llvm::SIInstrInfo::isFLATScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a901ba4ff66898215882da41143ddf69a">llvm::AMDGPU::isInlinableIntLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8616d2d8f4c04005569e89bcfe67e421">llvm::SIInstrInfo::isMUBUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### isProperlyAlignedRC() {#a2adf69ba524926c5454f5d259c1c4dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isProperlyAlignedRC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#a5c70283c6a0d2ce11aecfa43139e987e">getAGPRClassForBitWidth</a>, <a href="#a3a60ced6bc204b78bafcf33db515a087">getVectorSuperClassForBitWidth</a>, <a href="#a858849019ce7366904469c53972c54dc">getVGPRClassForBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#abee1c3236731101b249f6eeffd8cd7ba">llvm::TargetRegisterClass::hasSuperClassEq</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>, <a href="#add069634d629007ba8a03a426c6bfea7">isVectorSuperClass</a> and <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a>.</p>

</div>
</div>

### isRegClassAligned() {#ade66e9017b034317e0a4ba23bfe66876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isRegClassAligned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned AlignNumBits)</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af3b7e264a1a447b652821dae53bb1993">getRegClassAlignmentNumBits</a>.</p>

</div>
</div>

### isSGPRClassID() {#ab664dae585bc43224746468fa919da87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isSGPRClassID (unsigned RCID)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> contains only SGPR registers</p></dd>
</dl>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#a0e2008041a23dfc43ff1e90b014a2936">getRegClass</a> and <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a>.</p>

</div>
</div>

### isSGPRPhysReg() {#ad9b864efe9f37aaee60c010d2e5e6eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isSGPRPhysReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### isSGPRReg() {#a980c731f7723b02b66010f4fce010c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isSGPRReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#ae803619fba0f2282f638ddd36ba004de">resolveFrameIndex</a>.</p>

</div>
</div>

### isUniformReg() {#a66ec1a620b5a1409ba4bac8c1d6e4b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isUniformReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &amp; RBI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a02005f6abd229d62b4b708665c9473d5">llvm::RegisterBankInfo::isDivergentRegBank</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isVectorRegister() {#a6d63c5cc5bfab2094fae30cf9472d436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isVectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#acc61376f4183268183912910024e1f2c">isAGPR</a>, <a href="#a549e07395027c7b32774e27e9f28bc91">isVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### isVectorSuperClass() {#add069634d629007ba8a03a426c6bfea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isVectorSuperClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true only if this class contains both VGPR and AGPR registers</p></dd>
</dl>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#ae1364aa9eb8390d678c037be69450deb">hasAGPRs</a>, <a href="#ae2b17b04c6d4d3b578c7ba3497652df4">hasSGPRs</a> and <a href="#a8cb8776ee5f539fe6391a6d521af25f1">hasVGPRs</a>.</p>


<p>Referenced by <a href="#a2a24e95ba5416c84845c50bbf4c2ee4d">getProperlyAlignedRC</a> and <a href="#a2adf69ba524926c5454f5d259c1c4dac">isProperlyAlignedRC</a>.</p>

</div>
</div>

### isVGPR() {#a549e07395027c7b32774e27e9f28bc91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isVGPR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="#a77b95c7a5620b2e92ef8ca3aa8be15bd">getRegClassForReg</a>, <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a6d63c5cc5bfab2094fae30cf9472d436">isVectorRegister</a>.</p>

</div>
</div>

### isVSSuperClass() {#ad38d8f2d6815113e60a7a04012e465a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isVSSuperClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true only if this class contains both VGPR and SGPR registers</p></dd>
</dl>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#ae1364aa9eb8390d678c037be69450deb">hasAGPRs</a>, <a href="#ae2b17b04c6d4d3b578c7ba3497652df4">hasSGPRs</a> and <a href="#a8cb8776ee5f539fe6391a6d521af25f1">hasVGPRs</a>.</p>

</div>
</div>

### materializeFrameBaseRegister() {#a06c8d8abacb01c870f729e8d2027364f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIRegisterInfo::materializeFrameBaseRegister (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, int FrameIdx, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a45ffb8b95e5b75eeb68be7d300eb9618">llvm::MachineInstrBuilder::setOperandDead</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### needsFrameBaseReg() {#aae2e3ed0f579b512e6a38d0f116553ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::needsFrameBaseReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a>, <a href="#a08a40d4d0736a73e47089ba3ef2e1566">getScratchInstrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#aef241765e05d84992ebe4133862b899d">isFIPlusImmOrVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a13fdc38a01504ed9a44abd1c9018737d">llvm::SIInstrInfo::isFLATScratch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8616d2d8f4c04005569e89bcfe67e421">llvm::SIInstrInfo::isMUBUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### opCanUseInlineConstant() {#a5f55007393b9c2edcdb84c55e5df5514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::opCanUseInlineConstant (unsigned OpType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if operands defined with this operand type can accept an inline constant. i.e. An integer value in the range (-16, 64) or -4.0f, -2.0f, -1.0f, -0.5f, 0.0f, 0.5f, 1.0f, 2.0f, 4.0f.</p></dd>
</dl>


<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a6a94af9168cb0dc562da82cc18c0432b">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FIRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ac26a044324fb469414a0a9e8b139dcb7">llvm::AMDGPU::OPERAND_REG_INLINE_AC_LAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a5f53e66ffdcd70ad55a4bf78e485f76a">llvm::AMDGPU::OPERAND_SRC_FIRST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5afbe953ff149274f4e4fdcb9495f0ee78">llvm::AMDGPU::OPERAND_SRC_LAST</a>.</p>

</div>
</div>

### opCanUseLiteralConstant() {#a83297079e933130ab3b78a428b7070e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::opCanUseLiteralConstant (unsigned OpType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if operands defined with this operand type can accept a literal constant (i.e. any 32-bit immediate).</p></dd>
</dl>


<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a3fd1d76bc769c21d286735fc7f05ecb9">llvm::AMDGPU::OPERAND_REG_IMM_FIRST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5acb42f4972af1b5b77b3802c10a125640">llvm::AMDGPU::OPERAND_REG_IMM_LAST</a>.</p>

</div>
</div>

### requiresFrameIndexReplacementScavenging() {#a29ab56a48816c54d3db51d4724304663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::requiresFrameIndexReplacementScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#acb35f7f6a131a64e636d936246ebd37f">llvm::MachineFrameInfo::hasStackObjects</a>.</p>

</div>
</div>

### requiresFrameIndexScavenging() {#a86d3fc8e591bfc7b5854f86d00241221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::requiresFrameIndexScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### requiresRegisterScavenging() {#a5eafea62423808eaf1bec18900ec929e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::requiresRegisterScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#acb35f7f6a131a64e636d936246ebd37f">llvm::MachineFrameInfo::hasStackObjects</a>.</p>

</div>
</div>

### requiresVirtualBaseRegisters() {#ae8ba4cd4553b5e0d7245b42c6d459418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::requiresVirtualBaseRegisters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### reservedPrivateSegmentBufferReg() {#a51db99e6baa393260b874d1d04e7ecdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister SIRegisterInfo::reservedPrivateSegmentBufferReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the end register initially reserved for the scratch buffer in case spilling is needed.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="#a6fe36d27e3fe50e1c4594b3438eeb8b8">getAlignedHighSGPRForRC</a>.</p>

</div>
</div>

### resolveFrameIndex() {#ae803619fba0f2282f638ddd36ba004de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIRegisterInfo::resolveFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BaseReg, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a980c731f7723b02b66010f4fce010c0f">isSGPRReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### restoreSGPR() {#a2ab71844c6563b3998af3c09ff2e3368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::restoreSGPR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, int FI, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes=nullptr, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr, bool OnlyToVGPR=false, bool SpillToPhysVGPRLane=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 2085 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a6bcb85b82e6330375b977191fef41e2b">llvm::SGPRSpillBuilder::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a954666a1d726bbc08a503d36255d694a">llvm::SGPRSpillBuilder::getPerVGPRData</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a6de0a7cfa1ac234ffcf0d1f889989a36">llvm::SIMachineFunctionInfo::getSGPRSpillToPhysicalVGPRLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a45f899ac3822c8f8c6a9f59b3b4206cb">llvm::SIMachineFunctionInfo::getSGPRSpillToVirtualVGPRLanes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a10aea73adf903930a8ce4c133dfa5a1e">llvm::SlotIndexes::insertMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ad83a7a6b291c68ccc27722290777f333">llvm::SGPRSpillBuilder::MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a1aec2625932d694fc229189a21239233">llvm::SGPRSpillBuilder::MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7a43f1a8fe6945949f7ebaeec8bf9a7">llvm::SGPRSpillBuilder::NumSubRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7c906625fab2baf872e16248962b859">llvm::SGPRSpillBuilder::prepare</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#aa86a4d647e79dbdeb3d2d43ec301abcd">llvm::SGPRSpillBuilder::readWriteTmpVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0dbecb97d916d10bb623cf46c199e0ae">llvm::LiveIntervals::removeAllRegUnitsForPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#ae59d457759eabf9feb31656d3a8bb8b0">llvm::SlotIndexes::replaceMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a941b8646dc54e403a97acfb1ee56d774">llvm::SGPRSpillBuilder::restore</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a13301cdc7cdfed3dd8f993e0f1b9d359">llvm::SGPRSpillBuilder::SplitParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#addf4f1853b616359f0800e0792b75e40">llvm::SGPRSpillBuilder::SuperReg</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ae46fbdc9694bcc2a7e842fbebea72d74">llvm::SGPRSpillBuilder::TII</a> and <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a25f41f0ca74f2026ead9ed683f10e6b3">llvm::SGPRSpillBuilder::TmpVGPR</a>.</p>


<p>Referenced by <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a> and <a href="#a5236ffd9cb568bb917937e7273cc650a">eliminateSGPRToVGPRSpillFrameIndex</a>.</p>

</div>
</div>

### shouldCoalesce() {#abce857be755106a0d747fa67ac782857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::shouldCoalesce (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC, unsigned SubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC, unsigned DstSubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * NewRC, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### shouldRealignStack() {#a2aa5409f4a9ae9129ad49bd05ba293f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::shouldRealignStack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ab5e5e73c5c13ca2211e1d365363e4170">llvm::TargetRegisterInfo::shouldRealignStack</a>.</p>


<p>Referenced by <a href="#a449d102f1b4d3b881282d6609caf6023">hasBasePointer</a>.</p>

</div>
</div>

### shouldRewriteCopySrc() {#a891021470cc8979b7dfcc936fad1cd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::shouldRewriteCopySrc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DefRC, unsigned DefSubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC, unsigned SrcSubReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

### spillEmergencySGPR() {#a3d4103d19eae05425cf7aee3ad915250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::spillEmergencySGPR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; RestoreMBB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SGPR, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 2165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af7541e1fd9a4513270d9abfd49aed959">llvm::SIMachineFunctionInfo::addToSpilledSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a6bcb85b82e6330375b977191fef41e2b">llvm::SGPRSpillBuilder::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a954666a1d726bbc08a503d36255d694a">llvm::SGPRSpillBuilder::getPerVGPRData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a4f912e4c6f99e1bf50c66ee8fb26ed2a">llvm::SGPRSpillBuilder::IsKill</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ad83a7a6b291c68ccc27722290777f333">llvm::SGPRSpillBuilder::MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a1aec2625932d694fc229189a21239233">llvm::SGPRSpillBuilder::MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7a43f1a8fe6945949f7ebaeec8bf9a7">llvm::SGPRSpillBuilder::NumSubRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7c906625fab2baf872e16248962b859">llvm::SGPRSpillBuilder::prepare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a941b8646dc54e403a97acfb1ee56d774">llvm::SGPRSpillBuilder::restore</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a1181ec84c08b8b5aa563db567163a48a">llvm::SGPRSpillBuilder::setMI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a13301cdc7cdfed3dd8f993e0f1b9d359">llvm::SGPRSpillBuilder::SplitParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#addf4f1853b616359f0800e0792b75e40">llvm::SGPRSpillBuilder::SuperReg</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ae46fbdc9694bcc2a7e842fbebea72d74">llvm::SGPRSpillBuilder::TII</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a25f41f0ca74f2026ead9ed683f10e6b3">llvm::SGPRSpillBuilder::TmpVGPR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>

</div>
</div>

### spillSGPR() {#ad48896d5bbe85488559a5007c3a4b7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::spillSGPR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, int FI, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes=nullptr, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr, bool OnlyToVGPR=false, bool SpillToPhysVGPRLane=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">OnlyToVGPR</span> is true, this will only succeed if this manages to find a free VGPR lane to spill.</p>

<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 1954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af7541e1fd9a4513270d9abfd49aed959">llvm::SIMachineFunctionInfo::addToSpilledSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a6bcb85b82e6330375b977191fef41e2b">llvm::SGPRSpillBuilder::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8b9fc912e50d4b2f7e3173b59e33ed76">llvm::SIMachineFunctionInfo::getFrameOffsetReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a954666a1d726bbc08a503d36255d694a">llvm::SGPRSpillBuilder::getPerVGPRData</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a6de0a7cfa1ac234ffcf0d1f889989a36">llvm::SIMachineFunctionInfo::getSGPRSpillToPhysicalVGPRLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a45f899ac3822c8f8c6a9f59b3b4206cb">llvm::SIMachineFunctionInfo::getSGPRSpillToVirtualVGPRLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2afcc4a332bb78d31847fd4a394a5aeb">llvm::SIMachineFunctionInfo::getStackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a10aea73adf903930a8ce4c133dfa5a1e">llvm::SlotIndexes::insertMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a4f912e4c6f99e1bf50c66ee8fb26ed2a">llvm::SGPRSpillBuilder::IsKill</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ad83a7a6b291c68ccc27722290777f333">llvm::SGPRSpillBuilder::MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a1aec2625932d694fc229189a21239233">llvm::SGPRSpillBuilder::MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7a43f1a8fe6945949f7ebaeec8bf9a7">llvm::SGPRSpillBuilder::NumSubRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7c906625fab2baf872e16248962b859">llvm::SGPRSpillBuilder::prepare</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#aa86a4d647e79dbdeb3d2d43ec301abcd">llvm::SGPRSpillBuilder::readWriteTmpVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0dbecb97d916d10bb623cf46c199e0ae">llvm::LiveIntervals::removeAllRegUnitsForPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#ae59d457759eabf9feb31656d3a8bb8b0">llvm::SlotIndexes::replaceMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a941b8646dc54e403a97acfb1ee56d774">llvm::SGPRSpillBuilder::restore</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a13301cdc7cdfed3dd8f993e0f1b9d359">llvm::SGPRSpillBuilder::SplitParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#addf4f1853b616359f0800e0792b75e40">llvm::SGPRSpillBuilder::SuperReg</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ae46fbdc9694bcc2a7e842fbebea72d74">llvm::SGPRSpillBuilder::TII</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a25f41f0ca74f2026ead9ed683f10e6b3">llvm::SGPRSpillBuilder::TmpVGPR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>


<p>Referenced by <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a> and <a href="#a5236ffd9cb568bb917937e7273cc650a">eliminateSGPRToVGPRSpillFrameIndex</a>.</p>

</div>
</div>

### spillSGPRToVGPR() {#aed80e0d9bfe4e57de24283efa7572eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::spillSGPRToVGPR ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### reserveRegisterTuples() {#a6b20bef91a090d2b2fb43153c9d29bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIRegisterInfo::reserveRegisterTuples (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; Reserved, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### isWave32 {#a4a7eea978dd4a31f4e33aedf028be3a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isWave32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

### RegPressureIgnoredUnits {#a93912d0b8967964dd59f2dbf25ceee55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::SIRegisterInfo::RegPressureIgnoredUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

### SpillSGPRToVGPR {#a3d1f1ebe12872b7a1cbccf98f75bfde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::SpillSGPRToVGPR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

### ST {#a871cbd1f1eb940f7783deb2dbc4fc5ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; llvm::SIRegisterInfo::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getNumCoveredRegs() {#a1dd11f1c73a15ab0fc73bacd1cdb64a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIRegisterInfo::getNumCoveredRegs (<a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LM)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#ad5db2a0ee1a5c07c0638e80c63ab56e0">llvm::LaneBitmask::getAsInteger</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="#aa1ce2155cda91c2070745f4aec2c66ac">getNumChannelsFromSubReg</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#a8a4c16c737c90f7de638e1ee724d4785">llvm::GCNRegPressure::inc</a>.</p>

</div>
</div>

### getSGPRClassForBitWidth() {#a7d8aef424553a9b93de21ced693f0b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIRegisterInfo::getSGPRClassForBitWidth (unsigned BitWidth)</td>
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



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 3429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#a981883145186bf6da58e5bd7f6476f30">getEquivalentSGPRClass</a>, <a href="#a615681753cb320f792b5656571637921">getRegClassForSizeOnBank</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#aa5fe965eac66ae9ebc69835fe44c679d">isIllegalRegisterType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a4b2db808be70ea68e0f121c1942982a9">moreElementsToNextExistingRegClass</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a4e1374fde17218f949e94ee57e18dc2c">llvm::AMDGPUDAGToDAGISel::Select</a>.</p>

</div>
</div>

### getSubRegFromChannel() {#a1be43761db2568933db89648201ab15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIRegisterInfo::getSubRegFromChannel (unsigned Channel, unsigned NumRegs=1)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the sub reg enum value for the given <span class="doxyComputerOutput">Channel</span> (e.g. getSubRegFromChannel(0) -&gt; AMDGPU::sub0)</p></dd>
</dl>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a28f217b28ea2d167112e0b86d1e4dd39">SubRegFromChannelTableWidthMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a52716532c3562bbe9c3fc343761c3c8a">llvm::SITargetLowering::AddMemOpInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a7bc05bcba45ed1e4e903c1c952d09178">buildRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a2eb27f39675fc1e8bd17f11e78e855d0">buildRegSequence32</a>, <a href="#a57982dfc711f20ecf31431bc37259cd7">buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a14e3343381ea7e432b532ffdc24df933">computeIndirectRegAndOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a278bc9f5720547f5e171d0a62290d69f">llvm::AMDGPUDAGToDAGISel::SelectBuildVector</a>.</p>

</div>
</div>

### hasAGPRs() {#ae1364aa9eb8390d678c037be69450deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::hasAGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class contains AGPR registers.</p></dd>
</dl>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aab50fe4810eed28d1cabb48bd46f77f77">llvm::HasAGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a1cc1ce48e42ab86c1419314bef07f00b">llvm::TargetRegisterClass::TSFlags</a>.</p>


<p>Referenced by <a href="#a2c4185689ad93fedfa57db7bfeb8ddd3">hasVectorRegisters</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>, <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a>, <a href="#add069634d629007ba8a03a426c6bfea7">isVectorSuperClass</a>, <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a> and <a href="#ad38d8f2d6815113e60a7a04012e465a5">isVSSuperClass</a>.</p>

</div>
</div>

### hasSGPRs() {#ae2b17b04c6d4d3b578c7ba3497652df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::hasSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class contains SGPR registers.</p></dd>
</dl>


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aa04f97be66117d82353b26db62b1edb9f">llvm::HasSGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a1cc1ce48e42ab86c1419314bef07f00b">llvm::TargetRegisterClass::TSFlags</a>.</p>


<p>Referenced by <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>, <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a>, <a href="#add069634d629007ba8a03a426c6bfea7">isVectorSuperClass</a>, <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a> and <a href="#ad38d8f2d6815113e60a7a04012e465a5">isVSSuperClass</a>.</p>

</div>
</div>

### hasVectorRegisters() {#a2c4185689ad93fedfa57db7bfeb8ddd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::hasVectorRegisters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class contains any vector registers.</p></dd>
</dl>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#ae1364aa9eb8390d678c037be69450deb">hasAGPRs</a> and <a href="#a8cb8776ee5f539fe6391a6d521af25f1">hasVGPRs</a>.</p>

</div>
</div>

### hasVGPRs() {#a8cb8776ee5f539fe6391a6d521af25f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::hasVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class contains VGPR registers.</p></dd>
</dl>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a80a02dd25ab114aa8eef8cf954b22c4aa7cc027812f1a15199cc2980ee11fcb64">llvm::HasVGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a1cc1ce48e42ab86c1419314bef07f00b">llvm::TargetRegisterClass::TSFlags</a>.</p>


<p>Referenced by <a href="#a2c4185689ad93fedfa57db7bfeb8ddd3">hasVectorRegisters</a>, <a href="#afb15c9a705b04d0a7709e0c0f8af33fa">isAGPRClass</a>, <a href="#af58d646af8dd60e4e514303dfa81de9c">isSGPRClass</a>, <a href="#add069634d629007ba8a03a426c6bfea7">isVectorSuperClass</a>, <a href="#a929252209ec1fab87cd43439ed3365c7">isVGPRClass</a> and <a href="#ad38d8f2d6815113e60a7a04012e465a5">isVSSuperClass</a>.</p>

</div>
</div>

### isAGPRClass() {#afb15c9a705b04d0a7709e0c0f8af33fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isAGPRClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class contains only AGPR registers</p></dd>
</dl>


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#ae1364aa9eb8390d678c037be69450deb">hasAGPRs</a>, <a href="#ae2b17b04c6d4d3b578c7ba3497652df4">hasSGPRs</a> and <a href="#a8cb8776ee5f539fe6391a6d521af25f1">hasVGPRs</a>.</p>


<p>Referenced by <a href="#a57982dfc711f20ecf31431bc37259cd7">buildSpillLoadStore</a>, <a href="#a4861767cf942190a83cf6083003bba05">getCrossCopyRegClass</a>, <a href="#a51be90716cd9b3020e0ca8a4bce547c0">getLargestLegalSuperClass</a>, <a href="#a2a24e95ba5416c84845c50bbf4c2ee4d">getProperlyAlignedRC</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a>, <a href="#acc61376f4183268183912910024e1f2c">isAGPR</a>, <a href="#a2adf69ba524926c5454f5d259c1c4dac">isProperlyAlignedRC</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a024479869943dfba001bb5701d62a243">llvm::SIMachineFunctionInfo::usesAGPRs</a>.</p>

</div>
</div>

### isChainScratchRegister() {#a5d029d76398d3153d0f6d8ab3be94c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIRegisterInfo::isChainScratchRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VGPR)</td>
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



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1e0aa89e6577318443a666796f159a30">llvm::SIMachineFunctionInfo::allocateWWMSpill</a>.</p>

</div>
</div>

### isSGPRClass() {#af58d646af8dd60e4e514303dfa81de9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isSGPRClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class contains only SGPR registers</p></dd>
</dl>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#ae1364aa9eb8390d678c037be69450deb">hasAGPRs</a>, <a href="#ae2b17b04c6d4d3b578c7ba3497652df4">hasSGPRs</a> and <a href="#a8cb8776ee5f539fe6391a6d521af25f1">hasVGPRs</a>.</p>


<p>Referenced by <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a>, <a href="#ac1c2077ba7c905d8271fd4d7b9af0fe7">isDivergentRegClass</a>, <a href="#ab664dae585bc43224746468fa919da87">isSGPRClassID</a>, <a href="#ad9b864efe9f37aaee60c010d2e5e6eb0">isSGPRPhysReg</a>, <a href="#a980c731f7723b02b66010f4fce010c0f">isSGPRReg</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a10799c8833054017c6ab052c8b9c1aa2">llvm::SITargetLowering::requiresUniformRegister</a>.</p>

</div>
</div>

### isVGPRClass() {#a929252209ec1fab87cd43439ed3365c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIRegisterInfo::isVGPRClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this class contains only VGPR registers</p></dd>
</dl>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>


<p>References <a href="#ae1364aa9eb8390d678c037be69450deb">hasAGPRs</a>, <a href="#ae2b17b04c6d4d3b578c7ba3497652df4">hasSGPRs</a> and <a href="#a8cb8776ee5f539fe6391a6d521af25f1">hasVGPRs</a>.</p>


<p>Referenced by <a href="#acd7a7dc7a2d3ba79fe5ee12378638317">eliminateFrameIndex</a>, <a href="#a51be90716cd9b3020e0ca8a4bce547c0">getLargestLegalSuperClass</a>, <a href="#a2a24e95ba5416c84845c50bbf4c2ee4d">getProperlyAlignedRC</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="#aae11cbd7196aeff4a4b2a12be9835f28">getReservedRegs</a>, <a href="#a2adf69ba524926c5454f5d259c1c4dac">isProperlyAlignedRC</a> and <a href="#a549e07395027c7b32774e27e9f28bc91">isVGPR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### RegSplitParts {#ae1273be5e5df6942e8505bd30c59f3cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt; std::vector&lt; int16_t &gt;, 16 &gt; SIRegisterInfo::RegSplitParts</td>
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

<p>Sub reg indexes for getRegSplitParts.</p>


<p>First index represents subreg size from 1 to 16 DWORDs. The inner vector is sorted by bit offset. Provided a register can be fully split with given subregs, all elements of the inner vector combined give a full lane mask.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

### SubRegFromChannelTable {#a5e3de70db165e23a99e7661e0dd1d291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt; std::array&lt; uint16_t, 32 &gt;, 9 &gt; SIRegisterInfo::SubRegFromChannelTable</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
