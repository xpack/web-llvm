---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/siinstrinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIInstrInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SIInstrInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">Target/AMDGPU/SIInstrInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/amdgpugeninstrinfo">AMDGPUGenInstrInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72325fbaa02efc224ea2e26d09ad1279">SetVectorType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 32 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BranchPredicate { <a href="#a883d9ad2075425d80f316f9a4f52dc21">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetOperandFlags { <a href="#ade90146180a53b9d9edc077b933e70bb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe40d3ac1550829e52891bb120130ef5">SIInstrInfo</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a671b685940387f88a924858a371d4">buildExtractSubReg</a> (MachineBasicBlock::iterator MI, MachineRegisterInfo &amp;MRI, const MachineOperand &amp;SuperReg, const TargetRegisterClass *SuperRC, unsigned SubIdx, const TargetRegisterClass *SubRC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2e17618e19433e64677bce53b46370">buildExtractSubRegOrImm</a> (MachineBasicBlock::iterator MI, MachineRegisterInfo &amp;MRI, const MachineOperand &amp;SuperReg, const TargetRegisterClass *SuperRC, unsigned SubIdx, const TargetRegisterClass *SubRC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd7333a1ddd4f2210a9870f8e2b20b0">getRegisterInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e46b1324c854b961e52b00f4d16573c">getSubtarget</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e3c3928f613445e6a6c1f3b1073744">isReallyTriviallyReMaterializable</a> (const MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857ec99c61bfc201bb60525234551102">isIgnorableUse</a> (const MachineOperand &amp;MO) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeddbadaf9b53e5eee3dade2e9cd3512d">isSafeToSink</a> (MachineInstr &amp;MI, MachineBasicBlock *SuccToSinkTo, MachineCycleInfo *CI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ed4b8df3900d37518583f29bbb0144">areLoadsFromSameBasePtr</a> (SDNode *Load0, SDNode *Load1, int64_t &amp;Offset0, int64_t &amp;Offset1) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b8aa29292db7fc2337041ca50f795ed">isGlobalMemoryObject</a> (const MachineInstr *MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a> (const MachineInstr &amp;LdSt, SmallVectorImpl&lt; const MachineOperand * &gt; &amp;BaseOps, int64_t &amp;Offset, bool &amp;OffsetIsScalable, LocationSize &amp;Width, const TargetRegisterInfo *TRI) const final</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48560701bbaa0465f8ef8d92874caaf0">shouldClusterMemOps</a> (ArrayRef&lt; const MachineOperand * &gt; BaseOps1, int64_t Offset1, bool OffsetIsScalable1, ArrayRef&lt; const MachineOperand * &gt; BaseOps2, int64_t Offset2, bool OffsetIsScalable2, unsigned ClusterSize, unsigned NumBytes) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185895a367f8cba1b465d6fd2a660fe7">shouldScheduleLoadsNear</a> (SDNode *Load0, SDNode *Load1, int64_t Offset0, int64_t Offset1, unsigned NumLoads) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519410003771768aef013bd57efa6cf4">copyPhysReg</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, const DebugLoc &amp;DL, MCRegister DestReg, MCRegister SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fac55ed154a25a20608a5f71dc833c0">materializeImmediate</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, const DebugLoc &amp;DL, Register DestReg, int64_t Value) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6409b94615d6f974f7cea22ee2814862">getPreferredSelectRegClass</a> (unsigned Size) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae141c2c150567424d8cc080976608e">insertNE</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register SrcReg, int Value) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad94f2f559486e50040a794798454f67f">insertEQ</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register SrcReg, int Value) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec207a1c12adfc61c6566436e5a2cd7">storeRegToStackSlot</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register SrcReg, bool isKill, int FrameIndex, const TargetRegisterClass *RC, const TargetRegisterInfo *TRI, Register VReg, MachineInstr::MIFlag Flags=MachineInstr::NoFlags) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4a49e8ceb6213fe44eb0ebc9869eb1">loadRegFromStackSlot</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register DestReg, int FrameIndex, const TargetRegisterClass *RC, const TargetRegisterInfo *TRI, Register VReg, MachineInstr::MIFlag Flags=MachineInstr::NoFlags) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a864a107b54979b53706e9d88f51c07e3">expandPostRAPseudo</a> (MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765f84a0c5289fe4fc72c224abc2e4ac">reMaterialize</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register DestReg, unsigned SubIdx, const MachineInstr &amp;Orig, const TargetRegisterInfo &amp;TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e9b54f022eddc33ee49305e85d6b7f">expandMovDPP64</a> (MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ab509751b75f67128683efcbef3e71">getMovOpcode</a> (const TargetRegisterClass *DstRC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d33066a44cffac139a9ab987c34c6d">getIndirectRegWriteMovRelPseudo</a> (unsigned VecSize, unsigned EltSize, bool IsSGPR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c6c099091f6e286415971cc7979316a">getIndirectGPRIDXPseudo</a> (unsigned VecSize, bool IsIndirectSrc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee81828a7ba7ae3e86ed968067d671b4">commuteOpcode</a> (unsigned Opc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa6d240b967c15d0c6d925b87499b05">commuteOpcode</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d85a4b5e2ddc4731835d9e0c55d4ae8">findCommutedOpIndices</a> (const MachineInstr &amp;MI, unsigned &amp;SrcOpIdx0, unsigned &amp;SrcOpIdx1) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfadbbb64a5f40343313285156b65dc2">findCommutedOpIndices</a> (const MCInstrDesc &amp;Desc, unsigned &amp;SrcOpIdx0, unsigned &amp;SrcOpIdx1) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c11ec8de146c5e79bfd5dea3cfab01">isBranchOffsetInRange</a> (unsigned BranchOpc, int64_t BrOffset) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4b6b90314d09d2b71e77d7127607c9">getBranchDestBlock</a> (const MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ef91f370e4eb770203cf33a176616a">hasDivergentBranch</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the block terminate with divergent branch. <a href="#ac5ef91f370e4eb770203cf33a176616a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3eb40a3be5c2fb6f804f1e5649fd57">insertIndirectBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock &amp;NewDestBB, MachineBasicBlock &amp;RestoreBB, const DebugLoc &amp;DL, int64_t BrOffset, RegScavenger *RS) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96da06741a80bacedc0da0469394eff3">analyzeBranchImpl</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, MachineBasicBlock *&amp;TBB, MachineBasicBlock *&amp;FBB, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, bool AllowModify) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324a232b4fdfd0993af2c0de8ab5a374">analyzeBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *&amp;TBB, MachineBasicBlock *&amp;FBB, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, bool AllowModify=false) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a93ad1fcae43e09eb8a6d4c55d79ca">removeBranch</a> (MachineBasicBlock &amp;MBB, int *BytesRemoved=nullptr) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73e9b3e610bd8cac60e740a61fcf5bf">insertBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *TBB, MachineBasicBlock *FBB, ArrayRef&lt; MachineOperand &gt; Cond, const DebugLoc &amp;DL, int *BytesAdded=nullptr) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8d351faef4293dcc8a164ce2f87d5c">reverseBranchCondition</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5805a583f1403b04347f8c0f5df005">canInsertSelect</a> (const MachineBasicBlock &amp;MBB, ArrayRef&lt; MachineOperand &gt; Cond, Register DstReg, Register TrueReg, Register FalseReg, int &amp;CondCycles, int &amp;TrueCycles, int &amp;FalseCycles) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953f3ddec823a0c7db75e73dbf550632">insertSelect</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register DstReg, ArrayRef&lt; MachineOperand &gt; Cond, Register TrueReg, Register FalseReg) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88bfb92ca2f7d419adc7e6645406a7c">insertVectorSelect</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register DstReg, ArrayRef&lt; MachineOperand &gt; Cond, Register TrueReg, Register FalseReg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c872d6942793868e63eea201d0d8af">analyzeCompare</a> (const MachineInstr &amp;MI, Register &amp;SrcReg, Register &amp;SrcReg2, int64_t &amp;CmpMask, int64_t &amp;CmpValue) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241b0b6bb1961190125114fb88db4a27">optimizeCompareInstr</a> (MachineInstr &amp;CmpInstr, Register SrcReg, Register SrcReg2, int64_t CmpMask, int64_t CmpValue, const MachineRegisterInfo *MRI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a> (const MachineInstr &amp;MIa, const MachineInstr &amp;MIb) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe4716676c6cd66f5db59639fc63bc8">removeModOperands</a> (MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a> (MachineInstr &amp;UseMI, MachineInstr &amp;DefMI, Register Reg, MachineRegisterInfo *MRI) const final</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a671450d13848a2a6b079f214174efee0">getMachineCSELookAheadLimit</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4445a2ce5876c120e2a6e6796edaf5c">convertToThreeAddress</a> (MachineInstr &amp;MI, LiveVariables *LV, LiveIntervals *LIS) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3f4df7c81b52adcd9a67f4c0937634">isSchedulingBoundary</a> (const MachineInstr &amp;MI, const MachineBasicBlock *MBB, const MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87226bc5abee70cba380c80a150917e1">isSALU</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2cd816c352a41376b0e659e485e9ab0">isVALU</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a442e49a14785b3d4d178bd56cd65d20c">isImage</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5b6e8b61c6dea0c9a2b710bc387464">isVMEM</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ebd70b2428374bec760033a071ed77">isSOP1</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1fc08ee7f9afef760e977c0d05ec1ad">isSOP2</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da5f49658f691382c762e246c183d09">isSOPC</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942451ddbfccce7cef5bd4ad5789f564">isSOPK</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b4c62a3fb13c8ee7c8fd227b004aa4">isSOPP</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b5d90dd54abf16e6fc7dd6d229a89a2">isPacked</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2d1485717248598c2a6ae6ca262e94e">isVOP1</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88be1c1d521b53193aeb82aac36b2342">isVOP2</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47bb27735aca2ff82019bf9ed21632c9">isVOP3</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91182af2c28f7c3e0654a2c7d33150f4">isSDWA</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60186bc8b94ad7c8cd4eb4d253ca906f">isVOPC</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73d2c1e9830ef93cfc4355a334a3f49">isMUBUF</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4099cb524aff500420cd554be72e16d">isMTBUF</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c774e0a392ba6bd21225cb9439d15eb">isSMRD</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6831e85182fd706818bd9196f8604a">isBufferSMRD</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e53bd5414e49ae1835daca35246337e">isDS</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fdde0eeb809933430f14eed5d1bb368">isLDSDMA</a> (uint16_t Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e83f800c08c44c81dbcf2b44d340f4">isGWS</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b208f7f6a759e6572b26d8b9ebb435">isAlwaysGDS</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae972e1a9bfca78b705492eca0fa93c21">isMIMG</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a301b1984223b30ed846ed33ea67b9fef">isVIMAGE</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29068808a3ef3c47175d5b83292b27c3">isVSAMPLE</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5224ad33a1e97bad70c72d6fd61728a9">isGather4</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248ac957da40daa5249681573066b693">isSegmentSpecificFLAT</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0213035c0c8aafb9c83ccab262d2e84f">isFLATGlobal</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a106115f2e43839ccbb8304f38cc33ef6">isFLATScratch</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585c7de40f618667f419b94928255632">isFLAT</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca118bcab72fa2bdc9d3f21c5f0892ba">isEXP</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a57155f2a7f277616abc8e72a26d4e">isAtomicNoRet</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398ffd28d7b40e800b2b394a332e8f1b">isAtomicRet</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3240800d3a7421ad0a66117d1427e5">isAtomic</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac480fbed83b389892dac3700ebc2a228">isWQM</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50cfc49b7fd5dcd5797fd5c2e528092">isDisableWQM</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e525d2b10c6f432c4ee58dcba3a95c5">isVGPRSpill</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ee73177af6a48c7ce8c098c6a9cb19">isSGPRSpill</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54dd07afbc21c48f8a0563bf246e466a">isSpill</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b97d5468dc585811f9ee483258e74b">isDPP</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e42e66a4042bf3ca2b5feccc17a9f0f">isTRANS</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a4ed2583bd6448a049175c27b0f6c4">isVOP3P</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb482928f89d29ad3f81f61cc6631e6">isVINTRP</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657f9370200aef683a600a5050624e6b">isMAI</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4066528dcb90837f8f1c5c69ce14a6f">isWMMA</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e150c88299d77a023abc7edfc3c49c">isSWMMAC</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af1ed9673e6fd142b364ce35a925e03">isDOT</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102a3360ca127a95fa27ce5bd43b2089">isLDSDIR</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ff9e192390622fadf2d0a9e5ef0326">isVINTERP</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3c9e158c4e62a5330d07d74b49570d">isScalarStore</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4415862e701263a670bb75582cd42764">isFixedSize</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b02e48dc93169ab00bccabbc6b4b72">hasFPClamp</a> (uint16_t Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12dd3d67cb6eaad5443d1d2bf367e8f0">getClampMask</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2f43a12c41999677d0c4091c34d317">usesFPDPRounding</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7146fde75e8d02adcab5d5dc553ee954">isFPAtomic</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af892ee82a59cd4966b937e3a42f3fad9">isBarrierStart</a> (unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf12e6eac61dc3de048b1937aecfa964">isBarrier</a> (unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ea5d87214dc42f15929ac6d1283d8c">doesNotReadTiedSource</a> (uint16_t Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1339a29754829b3bc7fb3fb212d5e17d">isIGLP</a> (unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9938a8f55c69eb97ade8a23db210860a">isIGLP</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7db8082f8579f37580a95bb96bb2ad2">isWaitcnt</a> (unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf7fd6ca838658494b35472858597c9">isVGPRCopy</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12bfd4ca919a2fdb6f1c03d5c2859e54">hasVGPRUses</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd85372be31eb6cd26e75c961e2ca5fa">hasUnwantedEffectsWhenEXECEmpty</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used to determine if an instruction can be safely executed under EXEC = 0 without hardware error, indeterminate results, and/or visible effects on future vector execution or outside the shader. <a href="#acd85372be31eb6cd26e75c961e2ca5fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4705aea7dab2a011b09f6036a49087c">mayReadEXEC</a> (const MachineRegisterInfo &amp;MRI, const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction could potentially depend on the value of exec. <a href="#ad4705aea7dab2a011b09f6036a49087c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a> (const APInt &amp;Imm) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9e39c1fc1cf514ffd33b75339b815e">isInlineConstant</a> (const APFloat &amp;Imm) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10caa873ff6bab070fa0217d5402267b">isInlineConstant</a> (const MachineOperand &amp;MO, uint8_t OperandType) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937968cca64524eb49e6b3ae31398da7">isInlineConstant</a> (const MachineOperand &amp;MO, const MCOperandInfo &amp;OpInfo) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601c42a582df16aaa8a045ec741ebe4a">isInlineConstant</a> (const MachineInstr &amp;MI, const MachineOperand &amp;UseMO, const MachineOperand &amp;DefMO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">returns</span> true if <span class="doxyComputerOutput">UseMO</span> is substituted with <span class="doxyComputerOutput">DefMO</span> in <span class="doxyComputerOutput">MI</span> it would be an inline immediate. <a href="#a601c42a582df16aaa8a045ec741ebe4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8199afaa2a1a1d226a09ad721ed956c1">isInlineConstant</a> (const MachineInstr &amp;MI, unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">returns</span> true if the operand <span class="doxyComputerOutput">OpIdx</span> in <span class="doxyComputerOutput">MI</span> is a valid inline immediate. <a href="#a8199afaa2a1a1d226a09ad721ed956c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e476239af2c0fd428aa3daec3b3672">isInlineConstant</a> (const MachineInstr &amp;MI, unsigned OpIdx, const MachineOperand &amp;MO) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47667f6ac9bbf55b4aa5442354af468d">isInlineConstant</a> (const MachineOperand &amp;MO) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835ce544e7ae111f1889501136ea6b3d">isImmOperandLegal</a> (const MachineInstr &amp;MI, unsigned OpNo, const MachineOperand &amp;MO) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b55958d73cd9fa8c5a32f5a6ac5a4c">hasVALU32BitEncoding</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this 64-bit VALU instruction has a 32-bit encoding. <a href="#a71b55958d73cd9fa8c5a32f5a6ac5a4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6067626e3318b8569835d83acbd92e">usesConstantBus</a> (const MachineRegisterInfo &amp;MRI, const MachineOperand &amp;MO, const MCOperandInfo &amp;OpInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this operand uses the constant bus. <a href="#a1f6067626e3318b8569835d83acbd92e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2655c5c71aa8f4688c6bfb02bc2589f9">usesConstantBus</a> (const MachineRegisterInfo &amp;MRI, const MachineInstr &amp;MI, int OpIdx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479dd1c44dc19d46f04837f4da7ce325">hasModifiers</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has any modifiers. <a href="#a479dd1c44dc19d46f04837f4da7ce325">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea349efd44508e36429de592f1437b14">hasModifiersSet</a> (const MachineInstr &amp;MI, unsigned OpName) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff49d92e227fa12fc068d203a22bd15">hasAnyModifiersSet</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae844768b9501609ab55c31b3c4f6ea5">canShrink</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31aa4c781d7a65b275b3de1882180675">buildShrunkInst</a> (MachineInstr &amp;MI, unsigned NewOpcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a> (const MachineInstr &amp;MI, StringRef &amp;ErrInfo) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac498c193dd1d1e364aa8e9b640f72826">getVALUOp</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef020b54917711fa4fbe9b8ad48258b">insertScratchExecCopy</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, Register Reg, bool IsSCCLive, SlotIndexes *Indexes=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3fa2ce8f194193f39ed6428a86c05f">restoreExec</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, Register Reg, SlotIndexes *Indexes=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d38ae4f1dfa5ec71b0f78fab996425b">getOpRegClass</a> (const MachineInstr &amp;MI, unsigned OpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the correct register class for <span class="doxyComputerOutput">OpNo</span>. <a href="#a7d38ae4f1dfa5ec71b0f78fab996425b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df02605d5e00cad00c3b7f4aef3aa14">getOpSize</a> (uint16_t Opcode, unsigned OpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size in bytes of the operand OpNo on the given. <a href="#a0df02605d5e00cad00c3b7f4aef3aa14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9190a9fa370b0c81005613f21afed7d7">getOpSize</a> (const MachineInstr &amp;MI, unsigned OpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This form should usually be preferred since it handles operands with unknown register classes. <a href="#a9190a9fa370b0c81005613f21afed7d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb529d6108d5dfdf8479ac3b03c9812">legalizeOpWithMove</a> (MachineInstr &amp;MI, unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize the <span class="doxyComputerOutput">OpIndex</span> operand of this instruction by inserting a MOV. <a href="#a4cb529d6108d5dfdf8479ac3b03c9812">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a> (const MachineInstr &amp;MI, unsigned OpIdx, const MachineOperand *MO=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">MO</span> is a legal operand if it was the <span class="doxyComputerOutput">OpIdx</span> Operand for <span class="doxyComputerOutput">MI</span>. <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9b286b0c8c32ae52faedcc2a6130a7">isLegalVSrcOperand</a> (const MachineRegisterInfo &amp;MRI, const MCOperandInfo &amp;OpInfo, const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">MO</span> would be a valid operand for the given operand definition <span class="doxyComputerOutput">OpInfo</span>. <a href="#a3d9b286b0c8c32ae52faedcc2a6130a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abecccbf97c3a9d0be384e6c639fcf2dc">isLegalRegOperand</a> (const MachineRegisterInfo &amp;MRI, const MCOperandInfo &amp;OpInfo, const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">MO</span> (a register operand) is a legal register for the given operand description or operand index. <a href="#abecccbf97c3a9d0be384e6c639fcf2dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65e8335ea0b5232a7f07f8fd5ec3566">isLegalRegOperand</a> (const MachineInstr &amp;MI, unsigned OpIdx, const MachineOperand &amp;MO) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f877e67f5943b857f8976d4a289848">legalizeOperandsVOP2</a> (MachineRegisterInfo &amp;MRI, MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize operands in <span class="doxyComputerOutput">MI</span> by either commuting it or inserting a copy of src1. <a href="#a76f877e67f5943b857f8976d4a289848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0673c8aeb9b580e1be469133adba37e5">legalizeOperandsVOP3</a> (MachineRegisterInfo &amp;MRI, MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix operands in <span class="doxyComputerOutput">MI</span> to satisfy constant bus requirements. <a href="#a0673c8aeb9b580e1be469133adba37e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b6ac3924041b35531d4e9bf66c3df4">readlaneVGPRToSGPR</a> (Register SrcReg, MachineInstr &amp;UseMI, MachineRegisterInfo &amp;MRI, const TargetRegisterClass *DstRC=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a value from a VGPR (<span class="doxyComputerOutput">SrcReg</span>) to SGPR. <a href="#ac5b6ac3924041b35531d4e9bf66c3df4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c2911f44ee301ccf57ae61b7915b5a">legalizeOperandsSMRD</a> (MachineRegisterInfo &amp;MRI, MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23855b574f5790880e0cdfc2b6b39aad">legalizeOperandsFLAT</a> (MachineRegisterInfo &amp;MRI, MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31612a0bf935add36f82065133267d4a">legalizeGenericOperand</a> (MachineBasicBlock &amp;InsertMBB, MachineBasicBlock::iterator I, const TargetRegisterClass *DstRC, MachineOperand &amp;Op, MachineRegisterInfo &amp;MRI, const DebugLoc &amp;DL) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> (MachineInstr &amp;MI, MachineDominatorTree *MDT=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize all operands in this instruction. <a href="#a09787033a63326e79a0d1445d3e0de13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac786791624fc85886f2db5c5e0601f1b">moveFlatAddrToVGPR</a> (MachineInstr &amp;Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change SADDR form of a FLAT <span class="doxyComputerOutput">Inst</span> to its VADDR form if saddr operand was moved to VGPR. <a href="#ac786791624fc85886f2db5c5e0601f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1be82aaa744c6cf1f72570ea7d421cc3">moveToVALU</a> (SIInstrWorklist &amp;Worklist, MachineDominatorTree *MDT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the instructions opcode with the equivalent VALU opcode. <a href="#a1be82aaa744c6cf1f72570ea7d421cc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3719bc967fb84bbbd69ac597866ea1">moveToVALUImpl</a> (SIInstrWorklist &amp;Worklist, MachineDominatorTree *MDT, MachineInstr &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e550107fa28c8e3869a5b28dad59b9">insertNoop</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a34ad93d12d742710032a33f3ecb57">insertNoops</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, unsigned Quantity) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d04c20f5631c0950af280cb294db89d">insertReturn</a> (MachineBasicBlock &amp;MBB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dbf2885fa89980322c2f4b58f85ff18">insertSimulatedTrap</a> (MachineRegisterInfo &amp;MRI, MachineBasicBlock &amp;MBB, MachineInstr &amp;MI, const DebugLoc &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build instructions that simulate the behavior of a <span class="doxyComputerOutput">s_trap 2</span> instructions for hardware (namely, gfx11) that runs in PRIV=1 mode. <a href="#a7dbf2885fa89980322c2f4b58f85ff18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a> (MachineInstr &amp;MI, unsigned OperandName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the operand named <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a61297a04e9cd91c9658b9affecdd9797">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91c24c1bac9593b16c365d98f980099">getNamedOperand</a> (const MachineInstr &amp;MI, unsigned OpName) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2594ff53aaaa639014fafa681a4046ba">getNamedImmOperand</a> (const MachineInstr &amp;MI, unsigned OpName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get required immediate operand. <a href="#a2594ff53aaaa639014fafa681a4046ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a8333f33c54fcb73d4f41ee264ce8e">getDefaultRsrcDataFormat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c31a9fd43cc1a320582913a2f27ece">getScratchRsrcWords23</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975ccb82baef08d83e403c8818c52db8">isLowLatencyInstruction</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2569a20f3cd4919625f6409b53d657">isHighLatencyDef</a> (int Opc) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a62886ad892b99c103c15122b7eaa9">getMCOpcodeFromPseudo</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the descriptor of the target-specific machine instruction that corresponds to the specified pseudo or native opcode. <a href="#ae3a62886ad892b99c103c15122b7eaa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5a8099c7351303ef337ec57d5e8e24">isStackAccess</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d714113557721ffd5bd3d06dc79642">isSGPRStackAccess</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9bf357fe1b75c63b4b789a93b0a7a7">isLoadFromStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207df7ea2d140c874d9b1d93d60774c7">isStoreToStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d7b26c45988dda37e32395313029eb">getInstBundleSize</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a> (const MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c0128051315d3d5cc1f32047c7449c">mayAccessFlatAddressSpace</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af346776aba97ebc30be21629ac0eadb9">decomposeMachineOperandsTargetFlags</a> (unsigned TF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; int, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7d43f6cef90b6a7954a38c64fd31d6">getSerializableTargetIndices</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb14a9b3b3a3886cead6fd320980b3a">getSerializableDirectMachineOperandTargetFlags</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a37b361832888b7decb77cfdf3d465">getSerializableMachineMemOperandTargetFlags</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56dfc46c9da130d7a7e06d7d6588164">CreateTargetPostRAHazardRecognizer</a> (const InstrItineraryData *II, const ScheduleDAG *DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used by the post-RA scheduler (SchedulePostRAList.cpp). <a href="#ab56dfc46c9da130d7a7e06d7d6588164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec04a6eb6586a960ecd2e9210cac2952">CreateTargetPostRAHazardRecognizer</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the hazard recognizer used at -O0 by the PostRAHazardRecognizer pass. <a href="#aec04a6eb6586a960ecd2e9210cac2952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab6232188433548694ea1a9a98d542f">CreateTargetMIHazardRecognizer</a> (const InstrItineraryData *II, const ScheduleDAGMI *DAG) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c35b9011bab80878520faf9afcd601a">getLiveRangeSplitOpcode</a> (Register Reg, const MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff5f8777cbfcc5921552cf2f4a93a36">isBasicBlockPrologue</a> (const MachineInstr &amp;MI, Register Reg=Register()) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3489e1fa192776df90b3f6b8e66511">createPHIDestinationCopy</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsPt, const DebugLoc &amp;DL, Register Src, Register Dst) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454f04c1cce23ff2b87305df8909ab33">createPHISourceCopy</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsPt, const DebugLoc &amp;DL, Register Src, unsigned SrcSubReg, Register Dst) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7d2799877b8bf1ebd139ef268ee7d6">isWave32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15fe0ce54453ae7355ee50ef1beb52a0">getAddNoCarry</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register DestReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a partially built integer add instruction without carry. <a href="#a15fe0ce54453ae7355ee50ef1beb52a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed0535a6ce0e4e5969a60a1635d0b18a">getAddNoCarry</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register DestReg, RegScavenger &amp;RS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339cb5c023edce57dbe8c60c466b0f68">getKillTerminatorFromPseudo</a> (unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018ed0bfa6715cb59a09af809ceb586e">isLegalMUBUFImmOffset</a> (unsigned Imm) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1952f8650a3b903ff78f5d5eb09c29a4">splitMUBUFOffset</a> (uint32_t Imm, uint32_t &amp;SOffset, uint32_t &amp;ImmOffset, Align Alignment=Align(4)) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97de5c81e48922426466768a69b38bf">isLegalFLATOffset</a> (int64_t Offset, unsigned AddrSpace, uint64_t FlatVariant) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if <span class="doxyComputerOutput">Offset</span> is legal for the subtarget as the offset to a FLAT encoded instruction. <a href="#ab97de5c81e48922426466768a69b38bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; int64_t, int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b89f22fd1adb2250ed1a38ed01ff5a">splitFlatOffset</a> (int64_t COffsetVal, unsigned AddrSpace, uint64_t FlatVariant) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split <span class="doxyComputerOutput">COffsetVal</span> into {immediate offset field, remainder offset} values. <a href="#a51b89f22fd1adb2250ed1a38ed01ff5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1cb325e16f2016182edac3352ea467">allowNegativeFlatOffset</a> (uint64_t FlatVariant) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if negative offsets are allowed for the given <span class="doxyComputerOutput">FlatVariant</span>. <a href="#abf1cb325e16f2016182edac3352ea467">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a> (int Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target-specific opcode if Opcode is a pseudo instruction. <a href="#ae25e963e7382528026a78b5c2e31c435">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02ccaad1b78c3ebc1d06867f9c3e3b6">isAsmOnlyOpcode</a> (int MCOp) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this instruction should only be used by assembler. <a href="#ab02ccaad1b78c3ebc1d06867f9c3e3b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18c5827c119a73ea6f07b4ef4649654">getRegClass</a> (const MCInstrDesc &amp;TID, unsigned OpNum, const TargetRegisterInfo *TRI, const MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76905a82cf568afc14dd95691c867f0">fixImplicitOperands</a> (MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba962e46a3ab42206182058420cb876f">foldMemoryOperandImpl</a> (MachineFunction &amp;MF, MachineInstr &amp;MI, ArrayRef&lt; unsigned &gt; Ops, MachineBasicBlock::iterator InsertPt, int FrameIndex, LiveIntervals *LIS=nullptr, VirtRegMap *VRM=nullptr) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c89059d817934a6c4432b698ba8171">getInstrLatency</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;MI, unsigned *PredCost=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25f">InstructionUniformity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8f884db0a3faadefc981023902a1ec">getInstructionUniformity</a> (const MachineInstr &amp;MI) const override final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25f">InstructionUniformity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125b690ac5caa9383822f14c597e792b">getGenericInstructionUniformity</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mirformatter">MIRFormatter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6165ccb8a99f947530a124903920c602">getMIRFormatter</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f84f62ec436fae299a1b7951bf940e5">getSchedModel</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0196eca3002f5fd8c339ea859ddd12f">enforceOperandRCAlignment</a> (MachineInstr &amp;MI, unsigned OpName) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02d3a96bd6edd57c5ad1ac0997c3689">isCopyInstrImpl</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specific machine instruction is a instruction that moves/copies value from one register to another register return destination and source registers as machine operands. <a href="#aa02d3a96bd6edd57c5ad1ac0997c3689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f165f45ca62b4d27bde48f484897da">swapSourceModifiers</a> (MachineInstr &amp;MI, MachineOperand &amp;Src0, unsigned Src0OpName, MachineOperand &amp;Src1, unsigned Src1OpName) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbc2f6b22e0c1dfd00546ef61cc0ac3">isLegalToSwap</a> (const MachineInstr &amp;MI, unsigned fromIdx, const MachineOperand *fromMO, unsigned toIdx, const MachineOperand *toMO) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5d3b4379e4e570f14f6700d6e87467">commuteInstructionImpl</a> (MachineInstr &amp;MI, bool NewMI, unsigned OpIdx0, unsigned OpIdx1) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430d1aef5d72ff9fc6cd5878ac4df6db">swapOperands</a> (MachineInstr &amp;Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77bb8c11f1e95e89d8d98429ce1eeccb">moveScalarAddSub</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, MachineDominatorTree *MDT=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2014eed012ceadf10d88ec92c2f8607">lowerSelect</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, MachineDominatorTree *MDT=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310387a9e4da8f1b6601510dbc6f3bbd">lowerScalarAbs</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0219467e82cf77b377ae06d2d0ba6c">lowerScalarXnor</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd4a9a3988c99dc52823db254da66a3">splitScalarNotBinop</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cfe91dfa2c3929f31cfb708fb1beb93">splitScalarBinOpN2</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8db97737df973c3d0e5a118199676b41">splitScalar64BitUnaryOp</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, unsigned Opcode, bool Swap=false) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaaf2b0fbbed0a3986acec5544f1fb7e">splitScalar64BitBinaryOp</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, unsigned Opcode, MachineDominatorTree *MDT=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df4da022ec1274c7018c352937aa252">splitScalarSMulU64</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, MachineDominatorTree *MDT) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e945caa27deeb315dbd75f60cef403">splitScalarSMulPseudo</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, MachineDominatorTree *MDT) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68070868c56f9e66716c171b173afc2">splitScalar64BitXnor</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, MachineDominatorTree *MDT=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb56aa00cc198632f8cce0ed435b7a1">splitScalar64BitBCNT</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95d7166bb858a197e65c3e87deeda719">splitScalar64BitBFE</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12719632d2b956fa5f3728d302f180f0">splitScalar64BitCountOp</a> (SIInstrWorklist &amp;Worklist, MachineInstr &amp;Inst, unsigned Opcode, MachineDominatorTree *MDT=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd5087b7659c43c871bb297f626841d">movePackToVALU</a> (SIInstrWorklist &amp;Worklist, MachineRegisterInfo &amp;MRI, MachineInstr &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540d9f98316c586ac678a4f41cdcc540">addUsersToMoveToVALUWorklist</a> (Register Reg, MachineRegisterInfo &amp;MRI, SIInstrWorklist &amp;Worklist) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420c8abb8318650cbed42957c262a72d">addSCCDefUsersToVALUWorklist</a> (MachineOperand &amp;Op, MachineInstr &amp;SCCDefInst, SIInstrWorklist &amp;Worklist, Register NewCond=Register()) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ac34e4b52acd5a19de9075edfb6570">addSCCDefsToVALUWorklist</a> (MachineInstr *SCCUseInst, SIInstrWorklist &amp;Worklist) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8d217323ca49497ee5b9da76e67d25">getDestEquivalentVGPRClass</a> (const MachineInstr &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886ffd2612b0cdc9069185ba4c1b0639">checkInstOffsetsDoNotOverlap</a> (const MachineInstr &amp;MIa, const MachineInstr &amp;MIb) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3063538e9f379aefb19ec206c80ae5">findUsedSGPR</a> (const MachineInstr &amp;MI, int OpIndices[3]) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07cf58235a87446cd8fab901e082728">verifyCopy</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, StringRef &amp;ErrInfo) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d9a298eefc229476399189a99a6199">RI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab639456d26be9a017e2bf1411cbef255">ST</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10cc4d3cb843e5c3ec533d0d5425513">SchedModel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/amdgpumirformatter">AMDGPUMIRFormatter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00bd3fe47c6faeabb0e003c2aa98948b">Formatter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826c5f2bb260d27a430d48225e03383e">isFoldableCopy</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d7ac7b1dd9a9e4ae81fb54010f324f9">isSALU</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b830059090a1bb27b14e1e524fdb46">isVMEM</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adacd3cb5a6ca5003891b6d0032b9ade5">isSOP1</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4551760d712abe6c1234a4997e22de">isSOP2</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbbf88b03dcc6927f63b144f40bbc54c">isSOPC</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d0fced78b683ae1e38051a1313615d2">isSOPK</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1152df63da5e2f53576d9922fa408625">isSOPP</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4c830b57693cee2adf434f4b9c394f">isPacked</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1b887d2fad2d25f93580c261fea3a9">isVOP1</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323a96a23d09892cc1b252bf1cba2732">isVOP2</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aab14aaa9761a9af59b094090851ca3">isVOP3</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3295a9f4a742f69dfa4d7bb91cced3a9">isSDWA</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8b8e35244538ba4a04d756420454ba">isVOPC</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b60e6be6801b1f90d723990ef68009">isDS</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0e7b29c4c834f0985caab8aea638f9">isLDSDMA</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2be32319a4c9ca5a0a37d0e2a3a68b">isGWS</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa81dfde6b9b4ae42959839cd84cd63">isVIMAGE</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bda023e350bc4b64cf3eaf60ad17a93">isVSAMPLE</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d7080130a2d44447525617ead75825">isGather4</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed947ddafde5421d3f771f43f9c04d1">isSegmentSpecificFLAT</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65dcf8264f3f411eed5734a4b1ad7efa">isFLATGlobal</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13fdc38a01504ed9a44abd1c9018737d">isFLATScratch</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d40ab246e329190bbf36cd93fd88e83">isEXP</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7c4c826cd2ba559b369d732208fc07">isDualSourceBlendEXP</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb07a5c117ab74c3cd893b82560bb82">isAtomicNoRet</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4c2a9d09070e2709f9725a915575e4">isAtomicRet</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf2a604407f622a88ca631dfa50dd3b0">isAtomic</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35927952ceaf2f903e7d3aa920588daf">mayWriteLDSThroughDMA</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d133265b86c18fe71284768fa495726">isWQM</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72af200d9640277de56f3c208181a9fb">isDisableWQM</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54d6d16078e78dfe594321574f39223">isVGPRSpill</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f10f87fb228c645dab08a31a02d0a6">isSGPRSpill</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e38d2ff0c0ba3927e062447f0ea649">isSpill</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9abb6b24aca583f0b52e19267d750f3">isWWMRegSpillOpcode</a> (uint16_t Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959cf6b60787d90b8753099bcaa53f8a">isChainCallOpcode</a> (uint64_t Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960996ed89167b7ad321c647644d8dfb">isDPP</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c01b647a2569809ece29a7ce35e5102">isTRANS</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b8098108d7629973d94015838b8904">isVOP3P</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367f8f335f81011958967cd6fb98e9db">isVINTRP</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0605f773275c0461756eae0fb2321fa0">isMAI</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ebcd476b7e0bf9c549c423546b18dc">isMFMA</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3def5eabd8d8f1c67948c9626bf2be74">isDOT</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad20315758fcf345ce175df966fae0c82">isWMMA</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8354f891fe3cb5f3df8d1d867b6780">isMFMAorWMMA</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0e3ab6c51718d8e2181821b6147022">isSWMMAC</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2aaf80981b29494436f2b18a604e1c">isLDSDIR</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e762ca75d1db9247a7d659fbf77d2a">isVINTERP</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57ec0924f807505d7b9a64e30b1dc49">isScalarUnit</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea20d1c20096fa82081f0b56e083dd32">usesVM_CNT</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabb9a8e62924675b70fc1f53021735f4">usesLGKM_CNT</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1abe1ce598551b2ff787ff98d987373">sopkIsZext</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8fba38c0c431dd917ceff91ccdbd73">isScalarStore</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedb55bd2a3f524ae536b9c0ef17e41c0">isFixedSize</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cd70c26e65e8c622336b8d1b5ecc1e">hasFPClamp</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae181c0f85f73d387339267a62642b7ab">hasIntClamp</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4216fe6040d5c549d7ea1f997f3fb53b">usesFPDPRounding</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa31803a8b78287f011850b909536ae">isFPAtomic</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8a3508b676977a0396a0bb055c0a03">isNeverUniform</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945c33dc75a8491a32c7bd3e3d5ae944">isF16PseudoScalarTrans</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d948b7e2917067bdbab9e5ca0fff861">doesNotReadTiedSource</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81793225c0abc2a358b3710ed81189ec">getNonSoftWaitcntOpcode</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49e04076b2aaf96a7497774136482f3">modifiesModeRegister</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction modifies the mode register.q. <a href="#ac49e04076b2aaf96a7497774136482f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1656e5749e564620d30b6c2bd704f11">getNumWaitStates</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of wait states that result from executing this instruction. <a href="#ac1656e5749e564620d30b6c2bd704f11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca25d96b652c00368600bd3845f5591">isKillTerminator</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa48fff435124100b9bc18b162bcfd3">getMaxMUBUFImmOffset</a> (const GCNSubtarget &amp;ST)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8221c74806acd5e0e133095c1bd6a3ce">getDSShaderTypeValue</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9423207b1e848080ff3094e5a093d1fe">getBranchOpcode</a> (BranchPredicate Cond)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static BranchPredicate</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d8a3cec14381fa584c86f5dd3dbeb97">getBranchPredicate</a> (unsigned Opcode)</td>
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


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### SetVectorType {#a72325fbaa02efc224ea2e26d09ad1279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SIInstrInfo::SetVectorType =  SmallSetVector&lt;MachineInstr *, 32&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### BranchPredicate {#a883d9ad2075425d80f316f9a4f52dc21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SIInstrInfo::BranchPredicate </td>
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
<td class="doxyEnumItemName">INVALID_BR<a id="a883d9ad2075425d80f316f9a4f52dc21a09f9e94ba3450337acc691c9c2d03cf2"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCC_TRUE<a id="a883d9ad2075425d80f316f9a4f52dc21ac38fc465f58f07e889c73410035d84a4"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCC_FALSE<a id="a883d9ad2075425d80f316f9a4f52dc21a4926cd631582aad4b572e1471f10e0fc"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCCNZ<a id="a883d9ad2075425d80f316f9a4f52dc21a47274df4cd00525371cdf4901c3ee670"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCCZ<a id="a883d9ad2075425d80f316f9a4f52dc21acf9a8925ece568a47e35a2de24a15269"></a></td>
<td class="doxyEnumItemDescription"> (= -2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXECNZ<a id="a883d9ad2075425d80f316f9a4f52dc21a8e326a45571ea2dff56459f287724eb4"></a></td>
<td class="doxyEnumItemDescription"> (= -3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXECZ<a id="a883d9ad2075425d80f316f9a4f52dc21a90706b80a7962869fcc20a59ed5f2ae2"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### TargetOperandFlags {#ade90146180a53b9d9edc077b933e70bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SIInstrInfo::TargetOperandFlags </td>
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
<td class="doxyEnumItemName">MO_MASK<a id="ade90146180a53b9d9edc077b933e70bba31e6af0765d85a29b3539b4b14a42998"></a></td>
<td class="doxyEnumItemDescription"> (= 0xf)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NONE<a id="ade90146180a53b9d9edc077b933e70bbab9b475527cd46e49f6208722a1034e92"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTPCREL<a id="ade90146180a53b9d9edc077b933e70bbae1cf0b40cb6ab32eca2bb094dbf01c87"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTPCREL32<a id="ade90146180a53b9d9edc077b933e70bbaf8bf104f053c930813dce1aa8b9f9f7c"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTPCREL32_LO<a id="ade90146180a53b9d9edc077b933e70bba2a19cea491a8770e242de4561299ee96"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTPCREL32_HI<a id="ade90146180a53b9d9edc077b933e70bbad2a7a2d26258b290db9b195d021623a2"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_REL32<a id="ade90146180a53b9d9edc077b933e70bba563c4436cfc2d24b41acd1cfd4357977"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_REL32_LO<a id="ade90146180a53b9d9edc077b933e70bba878d31fbae9344bcf4e0b9a8928f4107"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_REL32_HI<a id="ade90146180a53b9d9edc077b933e70bba5330b2c3f2242c9c700f91ae1372500e"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_FAR_BRANCH_OFFSET<a id="ade90146180a53b9d9edc077b933e70bba4d206cbdcdd039cb05719c60fc873c89"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ABS32_LO<a id="ade90146180a53b9d9edc077b933e70bbafe82a0bc03151bffd10d66929b1ed545"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ABS32_HI<a id="ade90146180a53b9d9edc077b933e70bba3e9ced1912f545db50d64c7932e9ae72"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SIInstrInfo() {#afe40d3ac1550829e52891bb120130ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIInstrInfo::SIInstrInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a6ef020b54917711fa4fbe9b8ad48258b">insertScratchExecCopy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowNegativeFlatOffset() {#abf1cb325e16f2016182edac3352ea467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::allowNegativeFlatOffset (uint64_t FlatVariant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if negative offsets are allowed for the given <span class="doxyComputerOutput">FlatVariant</span>.</p>

<p>Declaration at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574">llvm::SIInstrFlags::FLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a318d59d6a50364a460b64bb7ad1f17d0">llvm::AMDGPU::isGFX12Plus</a>.</p>


<p>Referenced by <a href="#ab97de5c81e48922426466768a69b38bf">isLegalFLATOffset</a> and <a href="#a51b89f22fd1adb2250ed1a38ed01ff5a">splitFlatOffset</a>.</p>

</div>
</div>

### analyzeBranch() {#a324a232b4fdfd0993af2c0de8ab5a374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::analyzeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; FBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, bool AllowModify=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a96da06741a80bacedc0da0469394eff3">analyzeBranchImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### analyzeBranchImpl() {#a96da06741a80bacedc0da0469394eff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::analyzeBranchImpl (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; FBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, bool AllowModify)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>


<p>Referenced by <a href="#a324a232b4fdfd0993af2c0de8ab5a374">analyzeBranch</a>.</p>

</div>
</div>

### analyzeCompare() {#a86c872d6942793868e63eea201d0d8af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::analyzeCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg2, int64_t &amp; CmpMask, int64_t &amp; CmpValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### areLoadsFromSameBasePtr() {#a09ed4b8df3900d37518583f29bbb0144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::areLoadsFromSameBasePtr (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load0, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load1, int64_t &amp; Offset0, int64_t &amp; Offset1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a90cd0589eba5e5112a68717f122f1fbe">llvm::SDNode::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f96a3399d86d6f136aaa121de4217a3">llvm::SDNode::getMachineOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ae6e6e83717666f42581170b4599cd238">getNumOperandsNoGlue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a08b60e6be6801b1f90d723990ef68009">isDS</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1223d6e9a7dfb6e51299b894beccc679">llvm::SDNode::isMachineOpcode</a>, <a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a>, <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>, <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a99ae43a8879de19170e80277b5c54b88">nodesHaveSameOperandValue</a>.</p>

</div>
</div>

### areMemAccessesTriviallyDisjoint() {#af724c54b41bc0a366bf3197f2855ce83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::areMemAccessesTriviallyDisjoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MIa, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MIb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aabc3917d917c6247778c88107945d13b">llvm::MachineInstr::hasOrderedMemoryRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8c161f5f015730ac6853c802c3693a41">llvm::MachineInstr::hasUnmodeledSideEffects</a>, <a href="#a08b60e6be6801b1f90d723990ef68009">isDS</a>, <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="#a65dcf8264f3f411eed5734a4b1ad7efa">isFLATGlobal</a>, <a href="#a13fdc38a01504ed9a44abd1c9018737d">isFLATScratch</a>, <a href="#afb0e7b29c4c834f0985caab8aea638f9">isLDSDMA</a>, <a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a>, <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>, <a href="#a8ed947ddafde5421d3f771f43f9c04d1">isSegmentSpecificFLAT</a>, <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a17f5d15a7320dec2cfefb6617f711ab7">llvm::MachineInstr::mayLoadOrStore</a>.</p>

</div>
</div>

### buildExtractSubReg() {#a76a671b685940387f88a924858a371d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::buildExtractSubReg (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; SuperReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SuperRC, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SubRC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="#abe2e17618e19433e64677bce53b46370">buildExtractSubRegOrImm</a>.</p>

</div>
</div>

### buildExtractSubRegOrImm() {#abe2e17618e19433e64677bce53b46370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand SIInstrInfo::buildExtractSubRegOrImm (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; SuperReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SuperRC, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SubRC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a76a671b685940387f88a924858a371d4">buildExtractSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### buildShrunkInst() {#a31aa4c781d7a65b275b3de1882180675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIInstrInfo::buildShrunkInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned NewOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a3e1a0dd2de88c2c34c60cc5d4e127d94">copyFlagsToImplicitVCC</a>, <a href="#ac76905a82cf568afc14dd95691c867f0">fixImplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a3496944fcc473dfe584e6615503a7a76">llvm::MCInstrDesc::getNumDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da767514e15ea244ad3e683ae79b583534">llvm::MCOI::OPERAND_IMMEDIATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ab0f83d3ae48a019dc05e1bc02e765c8d">llvm::AMDGPU::OPERAND_INPUT_MODS</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>.</p>

</div>
</div>

### canInsertSelect() {#acf5805a583f1403b04347f8c0f5df005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::canInsertSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TrueReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FalseReg, int &amp; CondCycles, int &amp; TrueCycles, int &amp; FalseCycles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#acc8a2c40a5d623bd8c7c28e93eda91d3">llvm::AMDGPU::getRegBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### canShrink() {#aae844768b9501609ab55c31b3c4f6ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::canShrink (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#aea349efd44508e36429de592f1437b14">hasModifiersSet</a>, <a href="#a71b55958d73cd9fa8c5a32f5a6ac5a4c">hasVALU32BitEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### commuteOpcode() {#aee81828a7ba7ae3e86ed968067d671b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SIInstrInfo::commuteOpcode (unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac4c95246ad0278e01cc6e03560005f0b">llvm::AMDGPU::getCommuteOrig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a96286d8f7d90ece30046d826bbb71422">llvm::AMDGPU::getCommuteRev</a> and <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>.</p>


<p>Referenced by <a href="#adf5d3b4379e4e570f14f6700d6e87467">commuteInstructionImpl</a>, <a href="#abfa6d240b967c15d0c6d925b87499b05">commuteOpcode</a> and <a href="#a76f877e67f5943b857f8976d4a289848">legalizeOperandsVOP2</a>.</p>

</div>
</div>

### commuteOpcode() {#abfa6d240b967c15d0c6d925b87499b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READONLY int llvm::SIInstrInfo::commuteOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#aee81828a7ba7ae3e86ed968067d671b4">commuteOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### convertToThreeAddress() {#ad4445a2ce5876c120e2a6e6796edaf5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIInstrInfo::convertToThreeAddress (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/livevariables">LiveVariables</a> * LV, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3896 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a76321b20db4feab750d85c2329cfcbc6">llvm::LiveVariables::VarInfo::AliveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#a4f223ae1e481ce22245c3c7c7736dbe9">llvm::SparseBitVector&lt; ElementSize &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7326d1a0ae53d6dece409404840c5e6f">getFoldableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6f3043b29023d270fc4bc5062dff7cee">llvm::LiveIntervals::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5ff7467be99b93194854ce84b534f711">llvm::AMDGPU::getMFMAEarlyClobberOp</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a12372c0d57f71b8f15bf80dc32f1c9ea">getNewFMAInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#af73ca972d296b25a689a90fb5a0713f3">llvm::LiveVariables::getVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a11cd70de340f310acc70781d57a00136">llvm::LiveIntervals::hasInterval</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#ad20315758fcf345ce175df966fae0c82">isWMMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2006d74041f6c3411ccd43a4ce7e610b">llvm::AMDGPU::mapWMMA2AddrTo3AddrOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#afbdfb2cc5decd8f22ea3ccc1ecea4028">llvm::LiveIntervals::ReplaceMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a8edb2219f51b89b23621bd1da1dfd6f8">updateLiveVariables</a>.</p>

</div>
</div>

### copyPhysReg() {#a519410003771768aef013bd57efa6cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::copyPhysReg (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> DestReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a519410003771768aef013bd57efa6cf4">copyPhysReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0659d4ea243fea474f4fa0a359197710">Fix16BitCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a266833fddf153d13701fb723996d3155">llvm::AMDGPU::isHi16Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a3b095994a942145ccaaed4f175c7172a">llvm::SISrcMods::OP_SEL_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af0e8126187c47c5b74a1bdc635158144">llvm::SISrcMods::OP_SEL_1</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab567bf4900296a78df5fbc74ef1aedce">reportIllegalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">llvm::MachineInstr::tieOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6a58f19664e2b69107495d2085514f7874">llvm::AMDGPU::SDWA::UNUSED_PRESERVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaf4e7a9b6898b774104bfcd24a211d7e3">llvm::AMDGPU::SDWA::WORD_0</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aa3bd07eb171e650bc021c8e2517e175d0">llvm::AMDGPU::SDWA::WORD_1</a>.</p>


<p>Referenced by <a href="#a519410003771768aef013bd57efa6cf4">copyPhysReg</a>.</p>

</div>
</div>

### createPHIDestinationCopy() {#aea3489e1fa192776df90b3f6b8e66511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIInstrInfo::createPHIDestinationCopy (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a804530332064e8450f5c01c1291e3ec8">llvm::TargetInstrInfo::createPHIDestinationCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### createPHISourceCopy() {#a454f04c1cce23ff2b87305df8909ab33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIInstrInfo::createPHISourceCopy (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, unsigned SrcSubReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aaf9cd5e2258e984d377933b695ccf39b">llvm::TargetInstrInfo::createPHISourceCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### CreateTargetMIHazardRecognizer() {#a4ab6232188433548694ea1a9a98d542f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * SIInstrInfo::CreateTargetMIHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9028 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5da941cb7cfe3ae9b3dae1f5caac8b78">llvm::TargetInstrInfo::CreateTargetMIHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78c0f3feb8a81ca338f843494cff564e">llvm::ScheduleDAGMI::hasVRegLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>.</p>

</div>
</div>

### CreateTargetPostRAHazardRecognizer() {#ab56dfc46c9da130d7a7e06d7d6588164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * SIInstrInfo::CreateTargetPostRAHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is used by the post-RA scheduler (SchedulePostRAList.cpp).</p>


<p>The post-RA version of misched uses CreateTargetMIHazardRecognizer.</p>


<p>Declaration at line 1349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9013 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>.</p>

</div>
</div>

### CreateTargetPostRAHazardRecognizer() {#aec04a6eb6586a960ecd2e9210cac2952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * SIInstrInfo::CreateTargetPostRAHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the hazard recognizer used at -O0 by the PostRAHazardRecognizer pass.</p>

<p>Declaration at line 1353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### decomposeMachineOperandsTargetFlags() {#af346776aba97ebc30be21629ac0eadb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; SIInstrInfo::decomposeMachineOperandsTargetFlags (unsigned TF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9040 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="#ade90146180a53b9d9edc077b933e70bba31e6af0765d85a29b3539b4b14a42998">MO_MASK</a>.</p>

</div>
</div>

### doesNotReadTiedSource() {#ad6ea5d87214dc42f15929ac6d1283d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::doesNotReadTiedSource (uint16_t Opcode)</td>
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



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4777a05ca68d18f5d938d481ea0127c3">llvm::SIInstrFlags::TiedSourceNotRead</a>.</p>

</div>
</div>

### enforceOperandRCAlignment() {#ae0196eca3002f5fd8c339ea859ddd12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::enforceOperandRCAlignment (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 10111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="#a0df02605d5e00cad00c3b7f4aef3aa14">getOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### expandMovDPP64() {#ad8e9b54f022eddc33ee49305e85d6b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; MachineInstr *, MachineInstr * &gt; SIInstrInfo::expandMovDPP64 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a9370c0de85c12bd0062063b7fcbc64ed">llvm::SrcOp::getImm</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a18d2b72326bbdea2a9c1653b090f00ff">llvm::AMDGPU::isLegalDPALU_DPPControl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>


<p>Referenced by <a href="#a864a107b54979b53706e9d88f51c07e3">expandPostRAPseudo</a>.</p>

</div>
</div>

### expandPostRAPseudo() {#a864a107b54979b53706e9d88f51c07e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::expandPostRAPseudo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder/#a6c15d55cada45b3ba4ec4ba5560c39c4">llvm::MIBundleBuilder::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder/#a43e65fa50b984d52c85101caf001e543">llvm::MIBundleBuilder::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae4cfeb86ad3780d71eb022485e91d211">llvm::MachineInstrBuilder::copyImplicitOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vgprindexmode/#af5252ebf458b72b49d66ec97f51841e3adf241b71cde6b36cee10241a2e89fda3">llvm::AMDGPU::VGPRIndexMode::DST_ENABLE</a>, <a href="#ad8e9b54f022eddc33ee49305e85d6b7f">expandMovDPP64</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aeeb52dce7ed6b6e3abc562031782d77d">llvm::TargetInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a9370c0de85c12bd0062063b7fcbc64ed">llvm::SrcOp::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a7d38ae4f1dfa5ec71b0f78fab996425b">getOpRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#aeae23d6b812a5aaa9734ebcdeb4f2d26">llvm::MCInstrDesc::implicit_uses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a3b095994a942145ccaaed4f175c7172a">llvm::SISrcMods::OP_SEL_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af0e8126187c47c5b74a1bdc635158144">llvm::SISrcMods::OP_SEL_1</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab979122f21b7fa46d3d2d9b21983068b">llvm::MachineOperand::setIsUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aa233a8fe996a2045f5b02f5161e145c2">llvm::MachineOperand::setOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vgprindexmode/#af5252ebf458b72b49d66ec97f51841e3a064e9e9900217c959cd4bec112627012">llvm::AMDGPU::VGPRIndexMode::SRC0_ENABLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">llvm::MachineInstr::tieOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>

</div>
</div>

### findCommutedOpIndices() {#a6d85a4b5e2ddc4731835d9e0c55d4ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::findCommutedOpIndices (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; SrcOpIdx0, unsigned &amp; SrcOpIdx1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2867 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a6d85a4b5e2ddc4731835d9e0c55d4ae8">findCommutedOpIndices</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a6d85a4b5e2ddc4731835d9e0c55d4ae8">findCommutedOpIndices</a>.</p>

</div>
</div>

### findCommutedOpIndices() {#acfadbbb64a5f40343313285156b65dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::findCommutedOpIndices (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; Desc, unsigned &amp; SrcOpIdx0, unsigned &amp; SrcOpIdx1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>.</p>

</div>
</div>

### fixImplicitOperands() {#ac76905a82cf568afc14dd95691c867f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::fixImplicitOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a31aa4c781d7a65b275b3de1882180675">buildShrunkInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcncreatevopd-cpp-/gcncreatevopd/#afc677780cbd237adfee6dd02bf20541f">anonymous{GCNCreateVOPD.cpp}::GCNCreateVOPD::doReplace</a>, <a href="#ad73e9b3e610bd8cac60e740a61fcf5bf">insertBranch</a>, <a href="#a953f3ddec823a0c7db75e73dbf550632">insertSelect</a>, <a href="#a76f877e67f5943b857f8976d4a289848">legalizeOperandsVOP2</a> and <a href="#aae3719bc967fb84bbbd69ac597866ea1">moveToVALUImpl</a>.</p>

</div>
</div>

### foldImmediate() {#a7a3901a88827b844402f5a9e484945a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::foldImmediate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="#a0df02605d5e00cad00c3b7f4aef3aa14">getOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="#afff49d92e227fa12fc068d203a22bd15">hasAnyModifiersSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b622c469acc130c9a500b85b1473ef3">llvm::Hi_32</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#abbf7fd6ca838658494b35472858597c9">isVGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a901112c493d3827cda924430a6fbc9f4">llvm::Lo_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>, <a href="#a4fe4716676c6cd66f5db59639fc63bc8">removeModOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a001d31fcea92be51d2999826b806606f">llvm::MachineOperand::setSubReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#a31612a0bf935add36f82065133267d4a">legalizeGenericOperand</a>.</p>

</div>
</div>

### foldMemoryOperandImpl() {#aba962e46a3ab42206182058420cb876f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIInstrInfo::foldMemoryOperandImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, int FrameIndex, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#abee1c3236731101b249f6eeffd8cd7ba">llvm::TargetRegisterClass::hasSuperClassEq</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### getAddNoCarry() {#a15fe0ce54453ae7355ee50ef1beb52a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder SIInstrInfo::getAddNoCarry (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a partially built integer add instruction without carry.</p>


<p>Caller must add source operands. For pre-GFX9 it will generate unused carry destination operand. TODO: After GFX9 it should return a no-carry operation.</p>


<p>Declaration at line 1382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### getAddNoCarry() {#aed0535a6ce0e4e5969a60a1635d0b18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder SIInstrInfo::getAddNoCarry (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> &amp; RS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a27037167fddcdde3b6207d025267bbfc">llvm::RegScavenger::isRegUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a62d08c8303092539ecb1fde389108e7a">llvm::RegScavenger::scavengeRegisterBackwards</a>.</p>

</div>
</div>

### getBranchDestBlock() {#acb4b6b90314d09d2b71e77d7127607c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SIInstrInfo::getBranchDestBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2908 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getClampMask() {#a12dd3d67cb6eaad5443d1d2bf367e8f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SIInstrInfo::getClampMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca52880c64f523a9a892d8e4d33c3375dd">llvm::SIInstrFlags::ClampHi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca1f248cc663b917010c5d5ea2cff9445f">llvm::SIInstrFlags::ClampLo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4c00f2292227a96409b86e250bac9b87">llvm::SIInstrFlags::FPClamp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaeac247ab12a49434e1142ece1a35379b">llvm::SIInstrFlags::IntClamp</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getDefaultRsrcDataFormat() {#a10a8333f33c54fcb73d4f41ee264ce8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SIInstrInfo::getDefaultRsrcDataFormat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a062b134de5c9143eab05c83faab131e9">llvm::AMDGPU::RSRC_DATA_FORMAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx10/#a9f4b9c2257280532185aa363f023fbf5a5c6b3dafe669e154050061d41549394e">llvm::AMDGPU::UfmtGFX10::UFMT_32_FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx11/#a5cb0b88974a1601339c538367073d209ad2933e2b4eeecbfbd0bbb780922604d8">llvm::AMDGPU::UfmtGFX11::UFMT_32_FLOAT</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>


<p>Referenced by <a href="#af0c31a9fd43cc1a320582913a2f27ece">getScratchRsrcWords23</a>.</p>

</div>
</div>

### getGenericInstructionUniformity() {#a125b690ac5caa9383822f14c597e792b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionUniformity SIInstrInfo::getGenericInstructionUniformity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9746 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa32c426b55435c648a805b1103c96dcdf">llvm::AlwaysUniform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8d745b7be75e1d4d4139b093d7d6eb8f">llvm::AMDGPU::isGenericAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5ee59b5ad9e64f6b900b6cdd5567b15b">llvm::AMDGPU::isIntrinsicAlwaysUniform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8ab2011ec30da8a5edbd54bf0e498363">llvm::AMDGPU::isIntrinsicSourceOfDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa45ca4337861caa0e5a6723c79b31e191">llvm::NeverUniform</a>.</p>


<p>Referenced by <a href="#a8e8f884db0a3faadefc981023902a1ec">getInstructionUniformity</a>.</p>

</div>
</div>

### getIndirectGPRIDXPseudo() {#a2c6c099091f6e286415971cc7979316a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc &amp; SIInstrInfo::getIndirectGPRIDXPseudo (unsigned VecSize, bool IsIndirectSrc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getIndirectRegWriteMovRelPseudo() {#a14d33066a44cffac139a9ab987c34c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc &amp; SIInstrInfo::getIndirectRegWriteMovRelPseudo (unsigned VecSize, unsigned EltSize, bool IsSGPR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a18409f473f705c06f6eba730ece4e63e">getIndirectSGPRWriteMovRelPseudo32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2f03a1ac84f3a1c4e5612c9293ea6244">getIndirectSGPRWriteMovRelPseudo64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a750144640bbe8f2024eaf9296b3181dd">getIndirectVGPRWriteMovRelPseudoOpc</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getInstBundleSize() {#a31d7b26c45988dda37e32395313029eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getInstBundleSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>.</p>

</div>
</div>

### getInstrLatency() {#ab9c89059d817934a6c4432b698ba8171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned * PredCost=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getInstructionUniformity() {#a8e8f884db0a3faadefc981023902a1ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionUniformity SIInstrInfo::getInstructionUniformity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9795 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa32c426b55435c648a805b1103c96dcdf">llvm::AlwaysUniform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="#a125b690ac5caa9383822f14c597e792b">getGenericInstructionUniformity</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#acf2a604407f622a88ca631dfa50dd3b0">isAtomic</a>, <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="#a0d8a3508b676977a0396a0bb055c0a03">isNeverUniform</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa45ca4337861caa0e5a6723c79b31e191">llvm::NeverUniform</a>.</p>

</div>
</div>

### getInstSizeInBytes() {#a0ced2d6b15f87f297ec231c753e624e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getInstSizeInBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a31d7b26c45988dda37e32395313029eb">getInstBundleSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="#ae3a62886ad892b99c103c15122b7eaa9">getMCOpcodeFromPseudo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a960996ed89167b7ad321c647644d8dfb">isDPP</a>, <a href="#aedb55bd2a3f524ae536b9c0ef17e41c0">isFixedSize</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="#a2d7ac7b1dd9a9e4ae81fb54010f324f9">isSALU</a>, <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#af49d69e68344d6292702edca157e7eed">llvm::AMDGPUAsmPrinter::emitInstruction</a>, <a href="#a31d7b26c45988dda37e32395313029eb">getInstBundleSize</a> and <a href="#ac6a93ad1fcae43e09eb8a6d4c55d79ca">removeBranch</a>.</p>

</div>
</div>

### getKillTerminatorFromPseudo() {#a339cb5c023edce57dbe8c60c466b0f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc &amp; SIInstrInfo::getKillTerminatorFromPseudo (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getLiveRangeSplitOpcode() {#a0c35b9011bab80878520faf9afcd601a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getLiveRangeSplitOpcode (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aa49d47a31cd6d7ac85e7aaa3753ccc48">llvm::SIMachineFunctionInfo::checkFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/virtregflag/#ae40fa7ccf9ef4e1fa2db150e4b74f7a9a31784c8e60845a8b46a9de185dec5645">llvm::AMDGPU::VirtRegFlag::WWM_REG</a>.</p>

</div>
</div>

### getMachineCSELookAheadLimit() {#a671450d13848a2a6b079f214174efee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIInstrInfo::getMachineCSELookAheadLimit ()</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### getMCOpcodeFromPseudo() {#ae3a62886ad892b99c103c15122b7eaa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc &amp; llvm::SIInstrInfo::getMCOpcodeFromPseudo (unsigned Opcode)</td>
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

<p>Return the descriptor of the target-specific machine instruction that corresponds to the specified pseudo or native opcode.</p>

<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>.</p>


<p>Referenced by <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>.</p>

</div>
</div>

### getMemOperandsWithOffsetWidth() {#a0c826f5192676a1dfa8468a38b9ce1c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::getMemOperandsWithOffsetWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; LdSt, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; &amp; BaseOps, int64_t &amp; Offset, bool &amp; OffsetIsScalable, <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &amp; Width, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a7d38ae4f1dfa5ec71b0f78fab996425b">getOpRegClass</a>, <a href="#a0df02605d5e00cad00c3b7f4aef3aa14">getOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a08b60e6be6801b1f90d723990ef68009">isDS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a>, <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a1b20766e517418d6dbe92cd0d6aa42ae">isStride64</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a17f5d15a7320dec2cfefb6617f711ab7">llvm::MachineInstr::mayLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### getMIRFormatter() {#a6165ccb8a99f947530a124903920c602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MIRFormatter * llvm::SIInstrInfo::getMIRFormatter ()</td>
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



<p>Definition at line 1451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### getMovOpcode() {#a75ab509751b75f67128683efcbef3e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getMovOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### getNamedImmOperand() {#a2594ff53aaaa639014fafa681a4046ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::SIInstrInfo::getNamedImmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpName)</td>
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

<p>Get required immediate operand.</p>

<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### getNamedOperand() {#a61297a04e9cd91c9658b9affecdd9797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * SIInstrInfo::getNamedOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OperandName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the operand named <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>If <span class="doxyComputerOutput">MI</span> does not have an operand named <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, this function returns nullptr.</p>


<p>Declaration at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8794 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a31aa4c781d7a65b275b3de1882180675">buildShrunkInst</a>, <a href="#aae844768b9501609ab55c31b3c4f6ea5">canShrink</a>, <a href="#ad4445a2ce5876c120e2a6e6796edaf5c">convertToThreeAddress</a>, <a href="#ad8e9b54f022eddc33ee49305e85d6b7f">expandMovDPP64</a>, <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="#ac91c24c1bac9593b16c365d98f980099">getNamedOperand</a>, <a href="#aea349efd44508e36429de592f1437b14">hasModifiersSet</a>, <a href="#a75d714113557721ffd5bd3d06dc79642">isSGPRStackAccess</a>, <a href="#afb5a8099c7351303ef337ec57d5e8e24">isStackAccess</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>, <a href="#a23855b574f5790880e0cdfc2b6b39aad">legalizeOperandsFLAT</a>, <a href="#ad5c2911f44ee301ccf57ae61b7915b5a">legalizeOperandsSMRD</a>, <a href="#a765f84a0c5289fe4fc72c224abc2e4ac">reMaterialize</a>, <a href="#a64f165f45ca62b4d27bde48f484897da">swapSourceModifiers</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### getNamedOperand() {#ac91c24c1bac9593b16c365d98f980099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READONLY const MachineOperand * llvm::SIInstrInfo::getNamedOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpName)</td>
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



<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getOpRegClass() {#a7d38ae4f1dfa5ec71b0f78fab996425b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIInstrInfo::getOpRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the correct register class for <span class="doxyComputerOutput">OpNo</span>.</p>


<p>For target-specific instructions, this will return the register class that has been defined in tablegen. For generic instructions, like REG_SEQUENCE it will return the register class of its machine operand. to infer the correct register class base on the other operands.</p>


<p>Declaration at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5772 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a60ab44d62adfcff55385762363e231cf">adjustAllocatableRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a864a107b54979b53706e9d88f51c07e3">expandPostRAPseudo</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="#a9190a9fa370b0c81005613f21afed7d7">getOpSize</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### getOpSize() {#a0df02605d5e00cad00c3b7f4aef3aa14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIInstrInfo::getOpSize (uint16_t Opcode, unsigned OpNo)</td>
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

<p>Return the size in bytes of the operand OpNo on the given.</p>

<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da767514e15ea244ad3e683ae79b583534">llvm::MCOI::OPERAND_IMMEDIATE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#a9173ff0e651bbc7ce633a7c4b83d9586">llvm::MCOperandInfo::OperandType</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#ad3abf78805559fecd7642d0c57032c56">llvm::MCOperandInfo::RegClass</a>.</p>


<p>Referenced by <a href="#ae0196eca3002f5fd8c339ea859ddd12f">enforceOperandRCAlignment</a>, <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="#ae4e476239af2c0fd428aa3daec3b3672">isInlineConstant</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### getOpSize() {#a9190a9fa370b0c81005613f21afed7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIInstrInfo::getOpSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNo)</td>
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

<p>This form should usually be preferred since it handles operands with unknown register classes.</p>

<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a7d38ae4f1dfa5ec71b0f78fab996425b">getOpRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### getPreferredSelectRegClass() {#a6409b94615d6f974f7cea22ee2814862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIInstrInfo::getPreferredSelectRegClass (unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getRegClass() {#ac18c5827c119a73ea6f07b4ef4649654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIInstrInfo::getRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; TID, unsigned OpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a60ab44d62adfcff55385762363e231cf">adjustAllocatableRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca953a5ba3766c4aea8d9b8eeeba722679">llvm::SIInstrFlags::DS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574">llvm::SIInstrFlags::FLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#adcb5f001406dc2b45024dd582c444e6d">llvm::MCInstrDesc::Opcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="#a23855b574f5790880e0cdfc2b6b39aad">legalizeOperandsFLAT</a> and <a href="#a765f84a0c5289fe4fc72c224abc2e4ac">reMaterialize</a>.</p>

</div>
</div>

### getRegisterInfo() {#addd7333a1ddd4f2210a9870f8e2b20b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo &amp; llvm::SIInstrInfo::getRegisterInfo ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizer/#ab79827646b209ce331fda1c168b262e4">anonymous{SILoadStoreOptimizer.cpp}::SILoadStoreOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#ae53d8e40bdcb428165b0243af4be1dcc">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::runOnMachineFunction</a>.</p>

</div>
</div>

### getSchedModel() {#a5f84f62ec436fae299a1b7951bf940e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel &amp; llvm::SIInstrInfo::getSchedModel ()</td>
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



<p>Definition at line 1459 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### getScratchRsrcWords23() {#af0c31a9fd43cc1a320582913a2f27ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SIInstrInfo::getScratchRsrcWords23 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a10a8333f33c54fcb73d4f41ee264ce8e">getDefaultRsrcDataFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5a55a26fbacd40b385e54565fdebc4dd">llvm::AMDGPU::RSRC_ELEMENT_SIZE_SHIFT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae0376d4668bb0a8b7d4afa76f6ce3fee">llvm::AMDGPU::RSRC_INDEX_STRIDE_SHIFT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a823f64d5695b8da6f9b418bd4dc55176">llvm::AMDGPU::RSRC_TID_ENABLE</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### getSerializableDirectMachineOperandTargetFlags() {#a1bb14a9b3b3a3886cead6fd320980b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; unsigned, const char * &gt; &gt; SIInstrInfo::getSerializableDirectMachineOperandTargetFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9045 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ade90146180a53b9d9edc077b933e70bba3e9ced1912f545db50d64c7932e9ae72">MO_ABS32_HI</a>, <a href="#ade90146180a53b9d9edc077b933e70bbafe82a0bc03151bffd10d66929b1ed545">MO_ABS32_LO</a>, <a href="#ade90146180a53b9d9edc077b933e70bbae1cf0b40cb6ab32eca2bb094dbf01c87">MO_GOTPCREL</a>, <a href="#ade90146180a53b9d9edc077b933e70bbad2a7a2d26258b290db9b195d021623a2">MO_GOTPCREL32_HI</a>, <a href="#ade90146180a53b9d9edc077b933e70bba2a19cea491a8770e242de4561299ee96">MO_GOTPCREL32_LO</a>, <a href="#ade90146180a53b9d9edc077b933e70bba5330b2c3f2242c9c700f91ae1372500e">MO_REL32_HI</a> and <a href="#ade90146180a53b9d9edc077b933e70bba878d31fbae9344bcf4e0b9a8928f4107">MO_REL32_LO</a>.</p>

</div>
</div>

### getSerializableMachineMemOperandTargetFlags() {#ad2a37b361832888b7decb77cfdf3d465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; MachineMemOperand::Flags, const char * &gt; &gt; SIInstrInfo::getSerializableMachineMemOperandTargetFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9060 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca52f68ce5f52560b3ddb63ce8b2bd75">llvm::MOLastUse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a615f4542f26ca7383f06e780996f8ef3">llvm::MONoClobber</a>.</p>

</div>
</div>

### getSerializableTargetIndices() {#abb7d43f6cef90b6a7954a38c64fd31d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; int, const char * &gt; &gt; SIInstrInfo::getSerializableTargetIndices ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abe1ffb7444626273ec47b5526acfdeecaf272dd7e3cb82c0cfe63d334df30b2bd">llvm::AMDGPU::TI_CONSTDATA_START</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abe1ffb7444626273ec47b5526acfdeecac29025755991987ce428f17a06249777">llvm::AMDGPU::TI_SCRATCH_RSRC_DWORD0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abe1ffb7444626273ec47b5526acfdeeca82f70483c4222cdb713853c39905d3ed">llvm::AMDGPU::TI_SCRATCH_RSRC_DWORD1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abe1ffb7444626273ec47b5526acfdeecae8cfedcf88479cd7484e7342f2f2cc72">llvm::AMDGPU::TI_SCRATCH_RSRC_DWORD2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abe1ffb7444626273ec47b5526acfdeeca89d5abd5e008a11096b19f24eb566914">llvm::AMDGPU::TI_SCRATCH_RSRC_DWORD3</a>.</p>

</div>
</div>

### getSubtarget() {#a6e46b1324c854b961e52b00f4d16573c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget &amp; llvm::SIInstrInfo::getSubtarget ()</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gcncreatevopd-cpp-/gcncreatevopd/#afc677780cbd237adfee6dd02bf20541f">anonymous{GCNCreateVOPD.cpp}::GCNCreateVOPD::doReplace</a>.</p>

</div>
</div>

### getVALUOp() {#ac498c193dd1d1e364aa8e9b640f72826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getVALUOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#aae3719bc967fb84bbbd69ac597866ea1">moveToVALUImpl</a>.</p>

</div>
</div>

### hasAnyModifiersSet() {#afff49d92e227fa12fc068d203a22bd15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::hasAnyModifiersSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#aea349efd44508e36429de592f1437b14">hasModifiersSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ad606e03c366b7e91da3b735a7126fe5a">ModifierOpNames</a>.</p>


<p>Referenced by <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>.</p>

</div>
</div>

### hasDivergentBranch() {#ac5ef91f370e4eb770203cf33a176616a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::hasDivergentBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the block terminate with divergent branch.</p>


<p>Note this only work before lowering the pseudo control flow instructions.</p>


<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aeddbadaf9b53e5eee3dade2e9cd3512d">isSafeToSink</a>.</p>

</div>
</div>

### hasFPClamp() {#ae9b02e48dc93169ab00bccabbc6b4b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::hasFPClamp (uint16_t Opcode)</td>
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



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4c00f2292227a96409b86e250bac9b87">llvm::SIInstrFlags::FPClamp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### hasModifiers() {#a479dd1c44dc19d46f04837f4da7ce325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::hasModifiers (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction has any modifiers.</p>


<p>e.g. src[012]_mod, omod, clamp.</p>


<p>Declaration at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>.</p>

</div>
</div>

### hasModifiersSet() {#aea349efd44508e36429de592f1437b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::hasModifiersSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aae844768b9501609ab55c31b3c4f6ea5">canShrink</a> and <a href="#afff49d92e227fa12fc068d203a22bd15">hasAnyModifiersSet</a>.</p>

</div>
</div>

### hasUnwantedEffectsWhenEXECEmpty() {#acd85372be31eb6cd26e75c961e2ca5fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::hasUnwantedEffectsWhenEXECEmpty (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function is used to determine if an instruction can be safely executed under EXEC = 0 without hardware error, indeterminate results, and/or visible effects on future vector execution or outside the shader.</p>


<p>Note: as of 2024 the only use of this is SIPreEmitPeephole where it is used in removing branches over short EXEC = 0 sequences. As such it embeds certain assumptions which may not apply to every case of EXEC = 0 execution.</p>


<p>Declaration at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#adf12e6eac61dc3de048b1937aecfa964">isBarrier</a>, <a href="#a2d40ab246e329190bbf36cd93fd88e83">isEXP</a>, <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ac49e04076b2aaf96a7497774136482f3">modifiesModeRegister</a>.</p>

</div>
</div>

### hasVALU32BitEncoding() {#a71b55958d73cd9fa8c5a32f5a6ac5a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::hasVALU32BitEncoding (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this 64-bit VALU instruction has a 32-bit encoding.</p>


<p>This function will return false if you pass it a 32-bit instruction.</p>


<p>Declaration at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a17fda9e2f2cb60c24bfdec02d7793b86">llvm::AMDGPU::getVOPe32</a> and <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>.</p>


<p>Referenced by <a href="#aae844768b9501609ab55c31b3c4f6ea5">canShrink</a>.</p>

</div>
</div>

### hasVGPRUses() {#a12bfd4ca919a2fdb6f1c03d5c2859e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::hasVGPRUses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### insertBranch() {#ad73e9b3e610bd8cac60e740a61fcf5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::insertBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int * BytesAdded=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#ac76905a82cf568afc14dd95691c867f0">fixImplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessacontext-cpp/#a31d3975d3ebe3475aef26122625d5b59">isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7fc0854a9d3fced0dedf2c7f61fe7a72">preserveCondRegFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab979122f21b7fa46d3d2d9b21983068b">llvm::MachineOperand::setIsUndef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### insertEQ() {#ad94f2f559486e50040a794798454f67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIInstrInfo::insertEQ (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, int Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### insertIndirectBranch() {#aff3eb40a3be5c2fb6f804f1e5649fd57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::insertIndirectBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; NewDestBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; RestoreBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int64_t BrOffset, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7ffeb5b3940506a54e69e72e26e2a6cd">llvm::MachineInstrBuilder::addSym</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a37d8557c5bc9e9a92ce9b663e21f5e47">llvm::MCBinaryExpr::createAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#aaf1cb4447353da4a08ae3b5d55ca3eda">llvm::MCBinaryExpr::createAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/depctr/#aa9b70486e0433ce7ad354709d973c40e">llvm::AMDGPU::DepCtr::encodeFieldSaSdst</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a4f1af6e587ae8846628561570b54e2ee">llvm::RegScavenger::enterBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a14812153b6cf8c1cb26c3de8b96ba91c">llvm::RegScavenger::enterBasicBlockEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a21318dc0d2ad096d488aa3bfe4248c68">llvm::SIMachineFunctionInfo::getLongBranchReservedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1cc134bd22a318835dc929323da70ea4">llvm::MachineBasicBlock::getSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#ade90146180a53b9d9edc077b933e70bba4d206cbdcdd039cb05719c60fc873c89">MO_FAR_BRANCH_OFFSET</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a62d08c8303092539ecb1fde389108e7a">llvm::RegScavenger::scavengeRegisterBackwards</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac8ce95857a66b3706a84d1fd5072f0dd">llvm::MachineInstr::setPostInstrSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a34542ec002baa6b027a6d05644c6bb2e">llvm::RegScavenger::setRegUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a7f1486460b5e2da7f4527bbb2da54eff">llvm::MCSymbol::setVariableValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### insertNE() {#acae141c2c150567424d8cc080976608e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIInstrInfo::insertNE (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, int Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### insertNoop() {#ad8e550107fa28c8e3869a5b28dad59b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::insertNoop (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a35a34ad93d12d742710032a33f3ecb57">insertNoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### insertNoops() {#a35a34ad93d12d742710032a33f3ecb57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::insertNoops (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, unsigned Quantity)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2008 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad8e550107fa28c8e3869a5b28dad59b9">insertNoop</a>.</p>

</div>
</div>

### insertReturn() {#a2d04c20f5631c0950af280cb294db89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::insertReturn (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2019 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### insertScratchExecCopy() {#a6ef020b54917711fa4fbe9b8ad48258b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::insertScratchExecCopy (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool IsSCCLive, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a10aea73adf903930a8ce4c133dfa5a1e">llvm::SlotIndexes::insertMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>, <a href="#afe40d3ac1550829e52891bb120130ef5">SIInstrInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### insertSelect() {#a953f3ddec823a0c7db75e73dbf550632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::insertSelect (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TrueReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FalseReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#ac76905a82cf568afc14dd95691c867f0">fixImplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7fc0854a9d3fced0dedf2c7f61fe7a72">preserveCondRegFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### insertSimulatedTrap() {#a7dbf2885fa89980322c2f4b58f85ff18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SIInstrInfo::insertSimulatedTrap (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build instructions that simulate the behavior of a <span class="doxyComputerOutput">s_trap 2</span> instructions for hardware (namely, gfx11) that runs in PRIV=1 mode.</p>


<p>There, s_trap is interpreted as a nop.</p>


<p>Declaration at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2037 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a3a326b706ed4c9caaca05063b47c98dba255aa2c1bc0f43a997d8bb4c70c69b60">llvm::AMDGPU::SendMsg::ID_INTERRUPT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a3a326b706ed4c9caaca05063b47c98dbade3e6b1afcdf7295a4e9f63595868aa9">llvm::AMDGPU::SendMsg::ID_RTN_GET_DOORBELL</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a80e7aa469ce27c761eef3c645e55ed88a47de73eb7c73a07ac2cfc17fc3533f33">llvm::GCNSubtarget::LLVMAMDHSATrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a70b0525ecc6022336feb019ff63c934c">llvm::MachineFunction::push_back</a>.</p>

</div>
</div>

### insertVectorSelect() {#ad88bfb92ca2f7d419adc7e6645406a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::insertVectorSelect (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TrueReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FalseReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a10e708480cdc97c951368e06c13eac92">llvm::MachineOperand::setImplicit</a>.</p>

</div>
</div>

### isAlwaysGDS() {#aa4b208f7f6a759e6572b26d8b9ebb435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isAlwaysGDS (uint16_t Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="#a5d2be32319a4c9ca5a0a37d0e2a3a68b">isGWS</a>.</p>

</div>
</div>

### isAsmOnlyOpcode() {#ab02ccaad1b78c3ebc1d06867f9c3e3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isAsmOnlyOpcode (int MCOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this instruction should only be used by assembler.</p>


<p>Return true if this opcode should not be used by codegen.</p>


<p>Declaration at line 1425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>.</p>

</div>
</div>

### isAtomic() {#a0e3240800d3a7421ad0a66117d1427e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isAtomic (uint16_t Opcode)</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9dbc1631e11296bf1f8e95a2111a1bb9">llvm::SIInstrFlags::IsAtomicNoRet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca046343a654627954ce26d0e7531e12f7">llvm::SIInstrFlags::IsAtomicRet</a>.</p>

</div>
</div>

### isAtomicNoRet() {#a74a57155f2a7f277616abc8e72a26d4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isAtomicNoRet (uint16_t Opcode)</td>
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



<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9dbc1631e11296bf1f8e95a2111a1bb9">llvm::SIInstrFlags::IsAtomicNoRet</a>.</p>

</div>
</div>

### isAtomicRet() {#a398ffd28d7b40e800b2b394a332e8f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isAtomicRet (uint16_t Opcode)</td>
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



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca046343a654627954ce26d0e7531e12f7">llvm::SIInstrFlags::IsAtomicRet</a>.</p>

</div>
</div>

### isBarrier() {#adf12e6eac61dc3de048b1937aecfa964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isBarrier (unsigned Opcode)</td>
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



<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Reference <a href="#af892ee82a59cd4966b937e3a42f3fad9">isBarrierStart</a>.</p>


<p>Referenced by <a href="#acd85372be31eb6cd26e75c961e2ca5fa">hasUnwantedEffectsWhenEXECEmpty</a>.</p>

</div>
</div>

### isBarrierStart() {#af892ee82a59cd4966b937e3a42f3fad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isBarrierStart (unsigned Opcode)</td>
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



<p>Definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="#adf12e6eac61dc3de048b1937aecfa964">isBarrier</a>.</p>

</div>
</div>

### isBasicBlockPrologue() {#a0ff5f8777cbfcc5921552cf2f4a93a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isBasicBlockPrologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9080 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#ad1f10f87fb228c645dab08a31a02d0a6">isSGPRSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aa2a1ec6e61c80b53b1c166df59f9048c">llvm::SIMachineFunctionInfo::isWWMReg</a>, <a href="#ab9abb6b24aca583f0b52e19267d750f3">isWWMRegSpillOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isBranchOffsetInRange() {#ad6c11ec8de146c5e79bfd5dea3cfab01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isBranchOffsetInRange (unsigned BranchOpc, int64_t BrOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2891 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a8a8d5237b21cadc5584ca3d8a2c07966">BranchOffsetBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a>.</p>

</div>
</div>

### isBufferSMRD() {#a6c6831e85182fd706818bd9196f8604a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isBufferSMRD (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isDisableWQM() {#ab50cfc49b7fd5dcd5797fd5c2e528092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDisableWQM (uint16_t Opcode)</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecae0063a0501793fcbc332d543bd1541bc">llvm::SIInstrFlags::DisableWQM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isDOT() {#a4af1ed9673e6fd142b364ce35a925e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDOT (uint16_t Opcode)</td>
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



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecabd8ac36f299f3add1ff63d49475d51a5">llvm::SIInstrFlags::IsDOT</a>.</p>

</div>
</div>

### isDPP() {#ad7b97d5468dc585811f9ee483258e74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDPP (uint16_t Opcode)</td>
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



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca06434d3505958806f243119630f8c976">llvm::SIInstrFlags::DPP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isDS() {#a6e53bd5414e49ae1835daca35246337e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDS (uint16_t Opcode)</td>
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



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca953a5ba3766c4aea8d9b8eeeba722679">llvm::SIInstrFlags::DS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isEXP() {#aca118bcab72fa2bdc9d3f21c5f0892ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isEXP (uint16_t Opcode)</td>
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



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3f6b33151573e94a6ef7f14b809dbe70">llvm::SIInstrFlags::EXP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isFixedSize() {#a4415862e701263a670bb75582cd42764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFixedSize (uint16_t Opcode)</td>
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



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3f90dc3ee0272479ff77f144e37b8abc">llvm::SIInstrFlags::FIXED_SIZE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isFLAT() {#a585c7de40f618667f419b94928255632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFLAT (uint16_t Opcode)</td>
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



<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574">llvm::SIInstrFlags::FLAT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isFLATGlobal() {#a0213035c0c8aafb9c83ccab262d2e84f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFLATGlobal (uint16_t Opcode)</td>
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



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca125415c6b554fcb76cedd65841141a92">llvm::SIInstrFlags::FlatGlobal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isFLATScratch() {#a106115f2e43839ccbb8304f38cc33ef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFLATScratch (uint16_t Opcode)</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isFPAtomic() {#a7146fde75e8d02adcab5d5dc553ee954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFPAtomic (uint16_t Opcode)</td>
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



<p>Definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaccce8eb3ea48e8b0d5f5b7e9e011cc19">llvm::SIInstrFlags::FPAtomic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isGather4() {#a5224ad33a1e97bad70c72d6fd61728a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isGather4 (uint16_t Opcode)</td>
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



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca1fb3a3c9d73c11f77861315b283e3fde">llvm::SIInstrFlags::Gather4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isGlobalMemoryObject() {#a6b8aa29292db7fc2337041ca50f795ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isGlobalMemoryObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 10145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae46a80302699b257d06337de4b804a17">llvm::TargetInstrInfo::isGlobalMemoryObject</a>, <a href="#a1339a29754829b3bc7fb3fb212d5e17d">isIGLP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isGWS() {#a46e83f800c08c44c81dbcf2b44d340f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isGWS (uint16_t Opcode)</td>
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



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0f98bad3dd2f0146ac2135da67847c9d">llvm::SIInstrFlags::GWS</a>.</p>

</div>
</div>

### isHighLatencyDef() {#a4c2569a20f3cd4919625f6409b53d657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isHighLatencyDef (int Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a> and <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>.</p>

</div>
</div>

### isIGLP() {#a1339a29754829b3bc7fb3fb212d5e17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isIGLP (unsigned Opcode)</td>
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



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a6b8aa29292db7fc2337041ca50f795ed">isGlobalMemoryObject</a>.</p>

</div>
</div>

### isIGLP() {#a9938a8f55c69eb97ade8a23db210860a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isIGLP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a9938a8f55c69eb97ade8a23db210860a">isIGLP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9938a8f55c69eb97ade8a23db210860a">isIGLP</a>.</p>

</div>
</div>

### isIgnorableUse() {#a857ec99c61bfc201bb60525234551102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isIgnorableUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a70e16ebf8bd9b6d4b89331190206e635">resultDependsOnExec</a>.</p>

</div>
</div>

### isImage() {#a442e49a14785b3d4d178bd56cd65d20c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isImage (uint16_t Opcode)</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="#a5aa81dfde6b9b4ae42959839cd84cd63">isVIMAGE</a> and <a href="#a6bda023e350bc4b64cf3eaf60ad17a93">isVSAMPLE</a>.</p>

</div>
</div>

### isImmOperandLegal() {#a835ce544e7ae111f1889501136ea6b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isImmOperandLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="#a0605f773275c0461756eae0fb2321fa0">isMAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7fba5af4359eeeef753f1c286ea8d0d7">llvm::AMDGPU::isSISrcOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0890848fb02b90b1f7956063bc61cb3">llvm::MachineOperand::isTargetIndex</a>, <a href="#a0aab14aaa9761a9af59b094090851ca3">isVOP3</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da767514e15ea244ad3e683ae79b583534">llvm::MCOI::OPERAND_IMMEDIATE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#a9173ff0e651bbc7ce633a7c4b83d9586">llvm::MCOperandInfo::OperandType</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#ad3abf78805559fecd7642d0c57032c56">llvm::MCOperandInfo::RegClass</a>.</p>


<p>Referenced by <a href="#acbbc2f6b22e0c1dfd00546ef61cc0ac3">isLegalToSwap</a> and <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>.</p>

</div>
</div>

### isInlineConstant() {#a0480d6290cd95e40641f2af7a18fb764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a79ce723bbdcb8a66b32fec6499ecd9f9">llvm::AMDGPU::isInlinableLiteral32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af4cb2c8159c390d78b6a547ac87179ae">llvm::AMDGPU::isInlinableLiteral64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af0fd9bf68eb8edb07ba320437ba49d4b">llvm::AMDGPU::isInlinableLiteralI16</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ad4445a2ce5876c120e2a6e6796edaf5c">convertToThreeAddress</a>, <a href="#a864a107b54979b53706e9d88f51c07e3">expandPostRAPseudo</a>, <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>, <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>, <a href="#a835ce544e7ae111f1889501136ea6b3d">isImmOperandLegal</a>, <a href="#a6c9e39c1fc1cf514ffd33b75339b815e">isInlineConstant</a>, <a href="#a601c42a582df16aaa8a045ec741ebe4a">isInlineConstant</a>, <a href="#a8199afaa2a1a1d226a09ad721ed956c1">isInlineConstant</a>, <a href="#ae4e476239af2c0fd428aa3daec3b3672">isInlineConstant</a>, <a href="#a47667f6ac9bbf55b4aa5442354af468d">isInlineConstant</a>, <a href="#a937968cca64524eb49e6b3ae31398da7">isInlineConstant</a>, <a href="#acbbc2f6b22e0c1dfd00546ef61cc0ac3">isLegalToSwap</a>, <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>, <a href="#a0673c8aeb9b580e1be469133adba37e5">legalizeOperandsVOP3</a>, <a href="#a1f6067626e3318b8569835d83acbd92e">usesConstantBus</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isInlineConstant() {#a6c9e39c1fc1cf514ffd33b75339b815e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0243bafd9ec35896d5329c743ec1b545">llvm::AMDGPU::isInlinableLiteralBF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0d8a9668df772986cb7ab4cd7092b58e">llvm::AMDGPU::isInlinableLiteralFP16</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ae28d826c1042631ac188d8295949ff52a4ac2c7646ad25f6198c3cbbc627c5b54">llvm::APFloatBase::S_BFloat</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ae28d826c1042631ac188d8295949ff52addf4aea26776fa9ef6fbecdd9d4bd42f">llvm::APFloatBase::S_IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ae28d826c1042631ac188d8295949ff52a34e6dc98e540680ba8a019c81ea26459">llvm::APFloatBase::S_IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ae28d826c1042631ac188d8295949ff52a256aae058a9193e7a33e5c1e74487863">llvm::APFloatBase::S_IEEEsingle</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a78aae6e86ca05443b019735012c7d73a">llvm::APFloatBase::SemanticsToEnum</a>.</p>

</div>
</div>

### isInlineConstant() {#a10caa873ff6bab070fa0217d5402267b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, uint8_t OperandType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a901ba4ff66898215882da41143ddf69a">llvm::AMDGPU::isInlinableIntLiteral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a79ce723bbdcb8a66b32fec6499ecd9f9">llvm::AMDGPU::isInlinableLiteral32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af4cb2c8159c390d78b6a547ac87179ae">llvm::AMDGPU::isInlinableLiteral64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0243bafd9ec35896d5329c743ec1b545">llvm::AMDGPU::isInlinableLiteralBF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0d8a9668df772986cb7ab4cd7092b58e">llvm::AMDGPU::isInlinableLiteralFP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2afaf4ec0cb75eeba46faa203868cb15">llvm::AMDGPU::isInlinableLiteralV2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3cf384b520551827b3b9e6fb0355d052">llvm::AMDGPU::isInlinableLiteralV2F16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a23487558448d80c567c442aeacebe56a">llvm::AMDGPU::isInlinableLiteralV2I16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da9d91ca77438f331351ff52a89bf14c88">llvm::MCOI::OPERAND_GENERIC_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da58357ec2eafafe432f311d2e6d81077b">llvm::MCOI::OPERAND_GENERIC_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da4c331d30c2ed39ba95bef6d7276021e6">llvm::MCOI::OPERAND_GENERIC_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da75a285ee8fad18f515d9dde7868cfb53">llvm::MCOI::OPERAND_GENERIC_3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da12ba721e6374735955b7fd1b89146dce">llvm::MCOI::OPERAND_GENERIC_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96daa7f9e35ab0a7d9b58d114769a5944f6f">llvm::MCOI::OPERAND_GENERIC_5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da767514e15ea244ad3e683ae79b583534">llvm::MCOI::OPERAND_IMMEDIATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af4b9cc7ae4320e5423baac7b35410470">llvm::AMDGPU::OPERAND_INLINE_SPLIT_BARRIER_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ab0f83d3ae48a019dc05e1bc02e765c8d">llvm::AMDGPU::OPERAND_INPUT_MODS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a887993ba93e1d73774d547bbe51e0317">llvm::AMDGPU::OPERAND_KIMM16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a09dd1263fb2164c20f99f89f69e01a6e">llvm::AMDGPU::OPERAND_KIMM32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da4ab8ff4de9da34b9b60f04a21860aec1">llvm::MCOI::OPERAND_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a4a3081e798f991d04637c07ba0edf448">llvm::AMDGPU::OPERAND_REG_IMM_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a78981b9ce721164ac724d51f2c4f0a32">llvm::AMDGPU::OPERAND_REG_IMM_BF16_DEFERRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a7bcafeceef57e87bc524d5cc035837d5">llvm::AMDGPU::OPERAND_REG_IMM_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aff389f984e981455b4107b4708a77e5b">llvm::AMDGPU::OPERAND_REG_IMM_FP16_DEFERRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa7f8a98ec46b1d30189640d9ff59bc1e">llvm::AMDGPU::OPERAND_REG_IMM_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af8ac73c62f6f1da6175d32824633a064">llvm::AMDGPU::OPERAND_REG_IMM_FP32_DEFERRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a96e7ee25f7665368353ac98b104770a1">llvm::AMDGPU::OPERAND_REG_IMM_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aea3ce103b7ba06ee5ca50925e7064101">llvm::AMDGPU::OPERAND_REG_IMM_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a5df5b6b6089b9237400d2c422db445d8">llvm::AMDGPU::OPERAND_REG_IMM_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a206ff13aa7a98aac961a631569867e3d">llvm::AMDGPU::OPERAND_REG_IMM_INT64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a69bbd47f175c95849d7a6086a6550a66">llvm::AMDGPU::OPERAND_REG_IMM_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a20958300f68759315cb6cb2491d42cec">llvm::AMDGPU::OPERAND_REG_IMM_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae0f1ac0de50b2280311f02d7e1f5b25e">llvm::AMDGPU::OPERAND_REG_IMM_V2FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a455e964e5660b09e16a498dd96cf0bd6">llvm::AMDGPU::OPERAND_REG_IMM_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa3d68df7f69a18a66156e5e08c2c7504">llvm::AMDGPU::OPERAND_REG_IMM_V2INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a8c06c3c283a06956e261937775ff3838">llvm::AMDGPU::OPERAND_REG_INLINE_AC_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9eb871898b75ab91e808faf50f5f41a5">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa10ec5681f77906549e7a745593139a9">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae51ff25f16b928b2b8712a613e4fd3db">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9242629e3f7e6539015220a3d77d7dc7">llvm::AMDGPU::OPERAND_REG_INLINE_AC_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9f903a56d49f51a4697c5198aaea3459">llvm::AMDGPU::OPERAND_REG_INLINE_AC_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa122eae99199c0ac86716819fde2efc9">llvm::AMDGPU::OPERAND_REG_INLINE_AC_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a52eeb3170ac03d3af5c8ea11b06ea93c">llvm::AMDGPU::OPERAND_REG_INLINE_AC_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9dfb8a7518a9154161c7a05b644e6e47">llvm::AMDGPU::OPERAND_REG_INLINE_AC_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a3d11c500720aebcbecc6b2b1291b468f">llvm::AMDGPU::OPERAND_REG_INLINE_C_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae6c8f9b5c5805da722239e1e5d8cda5d">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ac073c33efc03a1882ee8155b8d68a794">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a2f2cb7a6e0c1e04d17d4a2d79dfc85ca">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a8d695369aef7c9f7e0589f5b4673ea46">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ad670957823c39ba1006b962d2023a19a">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a86ef6f68b415f39fcd28ae0dd431297c">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a431ef474cd3520ce1676091d1297cbac">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9babf1fd52dcf14ed0effdd6fe207007">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af49dc86d5a2c2386386ce4c0023cfd0f">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ad6dad922f054838a22df6973a79987be">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a240a6f2882eded67e4b70c6bb2f18411">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da62a6ddcdddcce55f836b1720d29f90dc">llvm::MCOI::OPERAND_REGISTER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da83076f86f6450732bc883b8723492eb2">llvm::MCOI::OPERAND_UNKNOWN</a>.</p>

</div>
</div>

### isInlineConstant() {#a937968cca64524eb49e6b3ae31398da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> &amp; OpInfo)</td>
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



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#a9173ff0e651bbc7ce633a7c4b83d9586">llvm::MCOperandInfo::OperandType</a>.</p>

</div>
</div>

### isInlineConstant() {#a601c42a582df16aaa8a045ec741ebe4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; UseMO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; DefMO)</td>
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

<p><span class="doxyComputerOutput">returns</span> true if <span class="doxyComputerOutput">UseMO</span> is substituted with <span class="doxyComputerOutput">DefMO</span> in <span class="doxyComputerOutput">MI</span> it would be an inline immediate.</p>

<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0c893675dfd5d1b1e4aea1e8211217c7">llvm::MachineOperand::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isInlineConstant() {#a8199afaa2a1a1d226a09ad721ed956c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx)</td>
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

<p><span class="doxyComputerOutput">returns</span> true if the operand <span class="doxyComputerOutput">OpIdx</span> in <span class="doxyComputerOutput">MI</span> is a valid inline immediate.</p>

<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isInlineConstant() {#ae4e476239af2c0fd428aa3daec3b3672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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



<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0df02605d5e00cad00c3b7f4aef3aa14">getOpSize</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a5df5b6b6089b9237400d2c422db445d8">llvm::AMDGPU::OPERAND_REG_IMM_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a206ff13aa7a98aac961a631569867e3d">llvm::AMDGPU::OPERAND_REG_IMM_INT64</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### isInlineConstant() {#a47667f6ac9bbf55b4aa5442354af468d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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



<p>Definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0c893675dfd5d1b1e4aea1e8211217c7">llvm::MachineOperand::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a> and <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>.</p>

</div>
</div>

### isLDSDIR() {#a102a3360ca127a95fa27ce5bd43b2089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isLDSDIR (uint16_t Opcode)</td>
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



<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecafe9bf84e87ab9f272db7a7145eb59758">llvm::SIInstrFlags::LDSDIR</a>.</p>

</div>
</div>

### isLDSDMA() {#a9fdde0eeb809933430f14eed5d1bb368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isLDSDMA (uint16_t Opcode)</td>
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



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a> and <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a>.</p>

</div>
</div>

### isLegalFLATOffset() {#ab97de5c81e48922426466768a69b38bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isLegalFLATOffset (int64_t Offset, unsigned AddrSpace, uint64_t FlatVariant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns if <span class="doxyComputerOutput">Offset</span> is legal for the subtarget as the offset to a FLAT encoded instruction.</p>


<p>If <span class="doxyComputerOutput">Signed</span>, this is for an instruction that interprets the offset as signed.</p>


<p>Declaration at line 1406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#abf1cb325e16f2016182edac3352ea467">allowNegativeFlatOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574">llvm::SIInstrFlags::FLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2e4f719c21c52424a5a4e87c0d77c9d8">llvm::AMDGPU::getNumFlatOffsetBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a51b89f22fd1adb2250ed1a38ed01ff5a">splitFlatOffset</a>.</p>

</div>
</div>

### isLegalMUBUFImmOffset() {#a018ed0bfa6715cb59a09af809ceb586e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isLegalMUBUFImmOffset (unsigned Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="#a1fa48fff435124100b9bc18b162bcfd3">getMaxMUBUFImmOffset</a>.</p>

</div>
</div>

### isLegalRegOperand() {#abecccbf97c3a9d0be384e6c639fcf2dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isLegalRegOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> &amp; OpInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">MO</span> (a register operand) is a legal register for the given operand description or operand index.</p>


<p>The operand index version provide more legality checks</p>


<p>Declaration at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#abee1c3236731101b249f6eeffd8cd7ba">llvm::TargetRegisterClass::hasSuperClassEq</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#ad3abf78805559fecd7642d0c57032c56">llvm::MCOperandInfo::RegClass</a>.</p>


<p>Referenced by <a href="#ab65e8335ea0b5232a7f07f8fd5ec3566">isLegalRegOperand</a>, <a href="#acbbc2f6b22e0c1dfd00546ef61cc0ac3">isLegalToSwap</a>, <a href="#a3d9b286b0c8c32ae52faedcc2a6130a7">isLegalVSrcOperand</a>, <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a> and <a href="#a76f877e67f5943b857f8976d4a289848">legalizeOperandsVOP2</a>.</p>

</div>
</div>

### isLegalRegOperand() {#ab65e8335ea0b5232a7f07f8fd5ec3566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isLegalRegOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a08b60e6be6801b1f90d723990ef68009">isDS</a>, <a href="#abecccbf97c3a9d0be384e6c639fcf2dc">isLegalRegOperand</a>, <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isLegalVSrcOperand() {#a3d9b286b0c8c32ae52faedcc2a6130a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isLegalVSrcOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> &amp; OpInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">MO</span> would be a valid operand for the given operand definition <span class="doxyComputerOutput">OpInfo</span>.</p>


<p>Note this does not attempt to validate constant bus restrictions (e.g. literal constant usage).</p>


<p>Declaration at line 1217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5925 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#abecccbf97c3a9d0be384e6c639fcf2dc">isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0890848fb02b90b1f7956063bc61cb3">llvm::MachineOperand::isTargetIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isLoadFromStackSlot() {#aac9bf357fe1b75c63b4b789a93b0a7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIInstrInfo::isLoadFromStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8884 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>, <a href="#ad1f10f87fb228c645dab08a31a02d0a6">isSGPRSpill</a>, <a href="#a75d714113557721ffd5bd3d06dc79642">isSGPRStackAccess</a>, <a href="#afb5a8099c7351303ef337ec57d5e8e24">isStackAccess</a>, <a href="#ab54d6d16078e78dfe594321574f39223">isVGPRSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### isLowLatencyInstruction() {#a975ccb82baef08d83e403c8818c52db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isLowLatencyInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isMAI() {#a657f9370200aef683a600a5050624e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMAI (uint16_t Opcode)</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa0bc33f3818c02a577a8b209d98766cb">llvm::SIInstrFlags::IsMAI</a>.</p>

</div>
</div>

### isMIMG() {#ae972e1a9bfca78b705492eca0fa93c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMIMG (uint16_t Opcode)</td>
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



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0666b703f5fe8ee884171492fb6a685a">llvm::SIInstrFlags::MIMG</a>.</p>

</div>
</div>

### isMTBUF() {#ab4099cb524aff500420cd554be72e16d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMTBUF (uint16_t Opcode)</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4863f895381859543f89e4423126a73f">llvm::SIInstrFlags::MTBUF</a>.</p>

</div>
</div>

### isMUBUF() {#aa73d2c1e9830ef93cfc4355a334a3f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMUBUF (uint16_t Opcode)</td>
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



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2fca87a5855f045ac7f07d8c2814e81f">llvm::SIInstrFlags::MUBUF</a>.</p>

</div>
</div>

### isOperandLegal() {#af7ee4c22ed353efa8afd9ea35e4af06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isOperandLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">MO</span> is a legal operand if it was the <span class="doxyComputerOutput">OpIdx</span> Operand for <span class="doxyComputerOutput">MI</span>.</p>

<p>Declaration at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5936 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#a945c33dc75a8491a32c7bd3e3d5ae944">isF16PseudoScalarTrans</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a835ce544e7ae111f1889501136ea6b3d">isImmOperandLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af4cb2c8159c390d78b6a547ac87179ae">llvm::AMDGPU::isInlinableLiteral64</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="#abecccbf97c3a9d0be384e6c639fcf2dc">isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7fba5af4359eeeef753f1c286ea8d0d7">llvm::AMDGPU::isSISrcOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0890848fb02b90b1f7956063bc61cb3">llvm::MachineOperand::isTargetIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4dbb64e9d316b0b56b74d3364cb601da">llvm::AMDGPU::isValid32BitLiteral</a>, <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a>, <a href="#a0aab14aaa9761a9af59b094090851ca3">isVOP3</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a96e7ee25f7665368353ac98b104770a1">llvm::AMDGPU::OPERAND_REG_IMM_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a206ff13aa7a98aac961a631569867e3d">llvm::AMDGPU::OPERAND_REG_IMM_INT64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae0f1ac0de50b2280311f02d7e1f5b25e">llvm::AMDGPU::OPERAND_REG_IMM_V2FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa3d68df7f69a18a66156e5e08c2c7504">llvm::AMDGPU::OPERAND_REG_IMM_V2INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da83076f86f6450732bc883b8723492eb2">llvm::MCOI::OPERAND_UNKNOWN</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#a9173ff0e651bbc7ce633a7c4b83d9586">llvm::MCOperandInfo::OperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#ad3abf78805559fecd7642d0c57032c56">llvm::MCOperandInfo::RegClass</a> and <a href="#a1f6067626e3318b8569835d83acbd92e">usesConstantBus</a>.</p>


<p>Referenced by <a href="#ad4445a2ce5876c120e2a6e6796edaf5c">convertToThreeAddress</a> and <a href="#a0673c8aeb9b580e1be469133adba37e5">legalizeOperandsVOP3</a>.</p>

</div>
</div>

### isPacked() {#a2b5d90dd54abf16e6fc7dd6d229a89a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isPacked (uint16_t Opcode)</td>
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



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaacf639f4528a313767923c5575e1828e">llvm::SIInstrFlags::IsPacked</a>.</p>

</div>
</div>

### isReallyTriviallyReMaterializable() {#a64e3c3928f613445e6a6c1f3b1073744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isReallyTriviallyReMaterializable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aee8dc206a90191cd9b5a7ad2fbbead3d">canRemat</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ab671544f7af287b25a5e612f6e919975">llvm::TargetInstrInfo::isReallyTriviallyReMaterializable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isSafeToSink() {#aeddbadaf9b53e5eee3dade2e9cd3512d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isSafeToSink (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccToSinkTo, <a href="/web-llvm/docs/api/namespaces/llvm/#aee433bfa58b17266f2cff728e02fba26">MachineCycleInfo</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#aaacae7a4847ee9e5021fdbcdddd8bffb">llvm::GenericCycle&lt; ContextT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo/#affe3d364d20f96ecf084548127e37ab8">llvm::GenericCycleInfo&lt; ContextT &gt;::getCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a408a62c86ed1c263bb09c6d2b7ec09d2">llvm::GenericCycle&lt; ContextT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#ad77d36615fa8aaf293c745a472af6e50">llvm::GenericCycle&lt; ContextT &gt;::getParentCycle</a>, <a href="#ac5ef91f370e4eb770203cf33a176616a">hasDivergentBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isSALU() {#a87226bc5abee70cba380c80a150917e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSALU (uint16_t Opcode)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab20a2dd15666d86af4e1fdeb88b1be7c">llvm::SIInstrFlags::SALU</a>.</p>

</div>
</div>

### isScalarStore() {#abc3c9e158c4e62a5330d07d74b49570d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isScalarStore (uint16_t Opcode)</td>
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



<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadaafc9c279a6480f1729929b26a4ad05">llvm::SIInstrFlags::SCALAR_STORE</a>.</p>

</div>
</div>

### isSchedulingBoundary() {#abe3f4df7c81b52adcd9a67f4c0937634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isSchedulingBoundary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ad6eb45e94bf447aa904024868317f94e">changesVGPRIndexingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isSDWA() {#a91182af2c28f7c3e0654a2c7d33150f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSDWA (uint16_t Opcode)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3cb08b10c27a453c57a2708e83859b47">llvm::SIInstrFlags::SDWA</a>.</p>

</div>
</div>

### isSegmentSpecificFLAT() {#a248ac957da40daa5249681573066b693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSegmentSpecificFLAT (uint16_t Opcode)</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca125415c6b554fcb76cedd65841141a92">llvm::SIInstrFlags::FlatGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### isSGPRSpill() {#a96ee73177af6a48c7ce8c098c6a9cb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSGPRSpill (uint16_t Opcode)</td>
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



<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a2d7ac7b1dd9a9e4ae81fb54010f324f9">isSALU</a> and <a href="#a54dd07afbc21c48f8a0563bf246e466a">isSpill</a>.</p>

</div>
</div>

### isSGPRStackAccess() {#a75d714113557721ffd5bd3d06dc79642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::isSGPRStackAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8876 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aac9bf357fe1b75c63b4b789a93b0a7a7">isLoadFromStackSlot</a> and <a href="#a207df7ea2d140c874d9b1d93d60774c7">isStoreToStackSlot</a>.</p>

</div>
</div>

### isSMRD() {#a0c774e0a392ba6bd21225cb9439d15eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSMRD (uint16_t Opcode)</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca30118e93ea743944a8fa1d846dcbaf37">llvm::SIInstrFlags::SMRD</a>.</p>

</div>
</div>

### isSOP1() {#a32ebd70b2428374bec760033a071ed77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOP1 (uint16_t Opcode)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa1db6db58e0bae030fb7277723deb3a9">llvm::SIInstrFlags::SOP1</a>.</p>

</div>
</div>

### isSOP2() {#aa1fc08ee7f9afef760e977c0d05ec1ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOP2 (uint16_t Opcode)</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2f0e3ce334e6b7fa59a2822e2770ab1d">llvm::SIInstrFlags::SOP2</a>.</p>

</div>
</div>

### isSOPC() {#a3da5f49658f691382c762e246c183d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOPC (uint16_t Opcode)</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadad0f2be60062a72d37634705e8aed51">llvm::SIInstrFlags::SOPC</a>.</p>

</div>
</div>

### isSOPK() {#a942451ddbfccce7cef5bd4ad5789f564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOPK (uint16_t Opcode)</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca95d3d9b72a40bcb9f88738fd86094a62">llvm::SIInstrFlags::SOPK</a>.</p>

</div>
</div>

### isSOPP() {#ae6b4c62a3fb13c8ee7c8fd227b004aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOPP (uint16_t Opcode)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3240de017ea18f8b8daf38bc4d927294">llvm::SIInstrFlags::SOPP</a>.</p>

</div>
</div>

### isSpill() {#a54dd07afbc21c48f8a0563bf246e466a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSpill (uint16_t Opcode)</td>
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



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa444d6850530e37d8af98558ce5b25f5">llvm::SIInstrFlags::Spill</a>.</p>


<p>Referenced by <a href="#ad1f10f87fb228c645dab08a31a02d0a6">isSGPRSpill</a>, <a href="#a96ee73177af6a48c7ce8c098c6a9cb19">isSGPRSpill</a>, <a href="#ab54d6d16078e78dfe594321574f39223">isVGPRSpill</a> and <a href="#a1e525d2b10c6f432c4ee58dcba3a95c5">isVGPRSpill</a>.</p>

</div>
</div>

### isStackAccess() {#afb5a8099c7351303ef337ec57d5e8e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::isStackAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="#aac9bf357fe1b75c63b4b789a93b0a7a7">isLoadFromStackSlot</a> and <a href="#a207df7ea2d140c874d9b1d93d60774c7">isStoreToStackSlot</a>.</p>

</div>
</div>

### isStoreToStackSlot() {#a207df7ea2d140c874d9b1d93d60774c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIInstrInfo::isStoreToStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>, <a href="#ad1f10f87fb228c645dab08a31a02d0a6">isSGPRSpill</a>, <a href="#a75d714113557721ffd5bd3d06dc79642">isSGPRStackAccess</a>, <a href="#afb5a8099c7351303ef337ec57d5e8e24">isStackAccess</a>, <a href="#ab54d6d16078e78dfe594321574f39223">isVGPRSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### isSWMMAC() {#a38e150c88299d77a023abc7edfc3c49c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSWMMAC (uint16_t Opcode)</td>
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



<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2b696c2aeb385ace4a1088a1169606a4">llvm::SIInstrFlags::IsSWMMAC</a>.</p>

</div>
</div>

### isTRANS() {#a9e42e66a4042bf3ca2b5feccc17a9f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isTRANS (uint16_t Opcode)</td>
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



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca6edf620aaa09a9f39b50177b8fa809d4">llvm::SIInstrFlags::TRANS</a>.</p>

</div>
</div>

### isVALU() {#aa2cd816c352a41376b0e659e485e9ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVALU (uint16_t Opcode)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca25bdad6e13bc9ed9f9ce690ae614db1c">llvm::SIInstrFlags::VALU</a>.</p>

</div>
</div>

### isVGPRCopy() {#abbf7fd6ca838658494b35472858597c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVGPRCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>.</p>

</div>
</div>

### isVGPRSpill() {#a1e525d2b10c6f432c4ee58dcba3a95c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVGPRSpill (uint16_t Opcode)</td>
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



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a54dd07afbc21c48f8a0563bf246e466a">isSpill</a> and <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a>.</p>

</div>
</div>

### isVIMAGE() {#a301b1984223b30ed846ed33ea67b9fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVIMAGE (uint16_t Opcode)</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaffe2f0079ddf5f206b323cdecec1e655">llvm::SIInstrFlags::VIMAGE</a>.</p>

</div>
</div>

### isVINTERP() {#ad2ff9e192390622fadf2d0a9e5ef0326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVINTERP (uint16_t Opcode)</td>
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



<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca1440c15f5bea6a1ebb07324b7be433c3">llvm::SIInstrFlags::VINTERP</a>.</p>

</div>
</div>

### isVINTRP() {#abbb482928f89d29ad3f81f61cc6631e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVINTRP (uint16_t Opcode)</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0bd36c4d359999d7043f5fdf440b0c7c">llvm::SIInstrFlags::VINTRP</a>.</p>

</div>
</div>

### isVMEM() {#aba5b6e8b61c6dea0c9a2b710bc387464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVMEM (uint16_t Opcode)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a> and <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>.</p>

</div>
</div>

### isVOP1() {#aa2d1485717248598c2a6ae6ca262e94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP1 (uint16_t Opcode)</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0dd2852ae8f20b7261f6d01eb354f1ff">llvm::SIInstrFlags::VOP1</a>.</p>

</div>
</div>

### isVOP2() {#a88be1c1d521b53193aeb82aac36b2342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP2 (uint16_t Opcode)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca600d26b3fa43f262c5ca2270667c0be2">llvm::SIInstrFlags::VOP2</a>.</p>

</div>
</div>

### isVOP3() {#a47bb27735aca2ff82019bf9ed21632c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP3 (uint16_t Opcode)</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca78562688e8d67f7ffa892e4b92311a98">llvm::SIInstrFlags::VOP3</a>.</p>

</div>
</div>

### isVOP3P() {#ac8a4ed2583bd6448a049175c27b0f6c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP3P (uint16_t Opcode)</td>
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



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4b3bb80273571c42a8b35d5e952034c9">llvm::SIInstrFlags::VOP3P</a>.</p>

</div>
</div>

### isVOPC() {#a60186bc8b94ad7c8cd4eb4d253ca906f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOPC (uint16_t Opcode)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca40767b966aa194931bb6ce67e3649de7">llvm::SIInstrFlags::VOPC</a>.</p>

</div>
</div>

### isVSAMPLE() {#a29068808a3ef3c47175d5b83292b27c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVSAMPLE (uint16_t Opcode)</td>
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



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca68afea1b16331758f09fc0d8c229b86f">llvm::SIInstrFlags::VSAMPLE</a>.</p>

</div>
</div>

### isWaitcnt() {#ab7db8082f8579f37580a95bb96bb2ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isWaitcnt (unsigned Opcode)</td>
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



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Reference <a href="#a81793225c0abc2a358b3710ed81189ec">getNonSoftWaitcntOpcode</a>.</p>

</div>
</div>

### isWave32() {#a4b7d2799877b8bf1ebd139ef268ee7d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isWave32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9688 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a1e3fa2ce8f194193f39ed6428a86c05f">restoreExec</a>.</p>

</div>
</div>

### isWMMA() {#ab4066528dcb90837f8f1c5c69ce14a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isWMMA (uint16_t Opcode)</td>
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



<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadb719433b001db91973f66b4bc3b6dc8">llvm::SIInstrFlags::IsWMMA</a>.</p>

</div>
</div>

### isWQM() {#ac480fbed83b389892dac3700ebc2a228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isWQM (uint16_t Opcode)</td>
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



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecae51b91ec89e9fd6502c3339d1360c147">llvm::SIInstrFlags::WQM</a>.</p>

</div>
</div>

### legalizeGenericOperand() {#a31612a0bf935add36f82065133267d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::legalizeGenericOperand (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; InsertMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### legalizeOperands() {#a09787033a63326e79a0d1445d3e0de13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SIInstrInfo::legalizeOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize all operands in this instruction.</p>


<p>This function may create new instructions and control-flow around <span class="doxyComputerOutput">MI</span>. If present, <span class="doxyComputerOutput">MDT</span> is updated.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A new basic block that contains <span class="doxyComputerOutput">MI</span> if new blocks were created.</p></dd>
</dl>


<p>Declaration at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad84ebe08bb098cd283e922fd186f77e9">llvm::MachineInstrBuilder::cloneMemRefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2586ad27c00166b367fe4d171be2bfaf">extractRsrcPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5eb95c1fe12d25bcfe6d3b63f6148605">llvm::AMDGPU::getAddr64Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7f0521fa2de44271fd4b909ea7351ef3">llvm::MachineBasicBlock::getFirstTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af7672ecd68ad0182beb360a4453b51ba">llvm::AMDGPU::getIfAddr64Inst</a>, <a href="#a2594ff53aaaa639014fafa681a4046ba">getNamedImmOperand</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="#a7d38ae4f1dfa5ec71b0f78fab996425b">getOpRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af9f05d3701d61f10054f263eec92da45">llvm::AMDGPU::isGraphics</a>, <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a>, <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a>, <a href="#a5aa81dfde6b9b4ae42959839cd84cd63">isVIMAGE</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a323a96a23d09892cc1b252bf1cba2732">isVOP2</a>, <a href="#a0aab14aaa9761a9af59b094090851ca3">isVOP3</a>, <a href="#a4e8b8e35244538ba4a04d756420454ba">isVOPC</a>, <a href="#a6bda023e350bc4b64cf3eaf60ad17a93">isVSAMPLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="#a31612a0bf935add36f82065133267d4a">legalizeGenericOperand</a>, <a href="#a23855b574f5790880e0cdfc2b6b39aad">legalizeOperandsFLAT</a>, <a href="#ad5c2911f44ee301ccf57ae61b7915b5a">legalizeOperandsSMRD</a>, <a href="#a76f877e67f5943b857f8976d4a289848">legalizeOperandsVOP2</a>, <a href="#a0673c8aeb9b580e1be469133adba37e5">legalizeOperandsVOP3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#ac5b6ac3924041b35531d4e9bf66c3df4">readlaneVGPRToSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>


<p>Referenced by <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a> and <a href="#aae3719bc967fb84bbbd69ac597866ea1">moveToVALUImpl</a>.</p>

</div>
</div>

### legalizeOperandsFLAT() {#a23855b574f5790880e0cdfc2b6b39aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::legalizeOperandsFLAT (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0c893675dfd5d1b1e4aea1e8211217c7">llvm::MachineOperand::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ac18c5827c119a73ea6f07b4ef4649654">getRegClass</a>, <a href="#a8ed947ddafde5421d3f771f43f9c04d1">isSegmentSpecificFLAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac786791624fc85886f2db5c5e0601f1b">moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#ac5b6ac3924041b35531d4e9bf66c3df4">readlaneVGPRToSGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### legalizeOperandsSMRD() {#ad5c2911f44ee301ccf57ae61b7915b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::legalizeOperandsSMRD (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#ac5b6ac3924041b35531d4e9bf66c3df4">readlaneVGPRToSGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### legalizeOperandsVOP2() {#a76f877e67f5943b857f8976d4a289848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::legalizeOperandsVOP2 (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize operands in <span class="doxyComputerOutput">MI</span> by either commuting it or inserting a copy of src1.</p>

<p>Declaration at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="#aee81828a7ba7ae3e86ed968067d671b4">commuteOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a81a328aa5781f7c744daa43c44df83c6">findImplicitSGPRRead</a>, <a href="#ac76905a82cf568afc14dd95691c867f0">fixImplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="#abecccbf97c3a9d0be384e6c639fcf2dc">isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a4cb529d6108d5dfdf8479ac3b03c9812">legalizeOpWithMove</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a001d31fcea92be51d2999826b806606f">llvm::MachineOperand::setSubReg</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### legalizeOperandsVOP3() {#a0673c8aeb9b580e1be469133adba37e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::legalizeOperandsVOP3 (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fix operands in <span class="doxyComputerOutput">MI</span> to satisfy constant bus requirements.</p>

<p>Declaration at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a4cb529d6108d5dfdf8479ac3b03c9812">legalizeOpWithMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### legalizeOpWithMove() {#a4cb529d6108d5dfdf8479ac3b03c9812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::legalizeOpWithMove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize the <span class="doxyComputerOutput">OpIndex</span> operand of this instruction by inserting a MOV.</p>


<p>For example: ADD_I32_e32 VGPR0, 15 to MOV VGPR1, 15 ADD_I32_e32 VGPR0, VGPR1</p>


<p>If the operand being legalized is a register, then a COPY will be used instead of MOV.</p>


<p>Declaration at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a76f877e67f5943b857f8976d4a289848">legalizeOperandsVOP2</a> and <a href="#a0673c8aeb9b580e1be469133adba37e5">legalizeOperandsVOP3</a>.</p>

</div>
</div>

### loadRegFromStackSlot() {#abe4a49e8ceb6213fe44eb0ebc9869eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::loadRegFromStackSlot (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, int FrameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a99bfc979f4349f70e0dd24ea53445ff0">getSGPRSpillRestoreOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2afcc4a332bb78d31847fd4a394a5aeb">llvm::SIMachineFunctionInfo::getStackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a38ebe847e991176c228c75849c200990">getVectorRegSpillRestoreOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ab5b19e21fc6b0765d7d551d2f07ae0f7">llvm::SIMachineFunctionInfo::setHasSpilledSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a29a8016e50342e4598b3cb8a6601694f">llvm::TargetStackID::SGPRSpill</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### materializeImmediate() {#a9fac55ed154a25a20608a5f71dc833c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::materializeImmediate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#abee1c3236731101b249f6eeffd8cd7ba">llvm::TargetRegisterClass::hasSuperClassEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### mayAccessFlatAddressSpace() {#a16c0128051315d3d5cc1f32047c7449c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::mayAccessFlatAddressSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### mayReadEXEC() {#ad4705aea7dab2a011b09f6036a49087c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::mayReadEXEC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the instruction could potentially depend on the value of exec.</p>


<p>If false, exec dependencies may safely be ignored.</p>


<p>Declaration at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#a2d7ac7b1dd9a9e4ae81fb54010f324f9">isSALU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3aae92be65f5f16f806ad48d474027e">llvm::isTargetSpecificOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### moveFlatAddrToVGPR() {#ac786791624fc85886f2db5c5e0601f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::moveFlatAddrToVGPR (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change SADDR form of a FLAT <span class="doxyComputerOutput">Inst</span> to its VADDR form if saddr operand was moved to VGPR.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if succeeded.</p></dd>
</dl>


<p>Declaration at line 1263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2c49a690cf18ca46eda313ffdfe93ac5">llvm::AMDGPU::getFlatScratchInstSVfromSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a42e6f807e1852ff50f30ed48bce3abea">llvm::AMDGPU::getGlobalVaddrOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a8ed947ddafde5421d3f771f43f9c04d1">isSegmentSpecificFLAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac3b161ec90385105cb46a08b52139e60">llvm::MachineInstr::removeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">llvm::MachineInstr::tieOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8e66e9ca7739874b25b9337940c26a0a">llvm::MachineInstr::untieRegOperand</a>.</p>


<p>Referenced by <a href="#a23855b574f5790880e0cdfc2b6b39aad">legalizeOperandsFLAT</a>.</p>

</div>
</div>

### moveToVALU() {#a1be82aaa744c6cf1f72570ea7d421cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::moveToVALU (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the instructions opcode with the equivalent VALU opcode.</p>


<p>This function will also move the users of MachineInstruntions in the <span class="doxyComputerOutput">WorkList</span> to the VALU if necessary. If present, <span class="doxyComputerOutput">MDT</span> is updated.</p>


<p>Declaration at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist/#a0d90003509aad438a4fac7978bb3b306">llvm::SIInstrWorklist::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist/#a67e2aba6990c1e340e7f789ea6688654">llvm::SIInstrWorklist::erase_top</a>, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist/#a88a473b1453e1bbe1c0dcdab2a55f0eb">llvm::SIInstrWorklist::getDeferredList</a>, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist/#a6b8ec06b7f4c404f9c7629468073ef61">llvm::SIInstrWorklist::isDeferred</a>, <a href="#aae3719bc967fb84bbbd69ac597866ea1">moveToVALUImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist/#a0449f0738b3cb21f6e3d445f37543c38">llvm::SIInstrWorklist::top</a>.</p>

</div>
</div>

### moveToVALUImpl() {#aae3719bc967fb84bbbd69ac597866ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::moveToVALUImpl (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a51f1fa9d5384d3b9c157a8216fef671d">llvm::MachineInstr::explicit_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="#ac76905a82cf568afc14dd95691c867f0">fixImplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad73e18478cd951f76d35a88c4d43ef5a">llvm::MachineInstr::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ac498c193dd1d1e364aa8e9b640f72826">getVALUOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad0666b4ee4d5d2ade97f5f1e63865bab">llvm::MachineInstr::implicit_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1912d4fbc40c61a12b1f770ad54dfd74">llvm::MachineInstr::isCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a75b79141e48ddded5600396eeb38eb1c">llvm::AMDGPU::isTrue16Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a0aab14aaa9761a9af59b094090851ca3">isVOP3</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac3b161ec90385105cb46a08b52139e60">llvm::MachineInstr::removeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a1be82aaa744c6cf1f72570ea7d421cc3">moveToVALU</a>.</p>

</div>
</div>

### optimizeCompareInstr() {#a241b0b6bb1961190125114fb88db4a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::optimizeCompareInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CmpInstr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg2, int64_t CmpMask, int64_t CmpValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9960 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7326d1a0ae53d6dece409404840c5e6f">getFoldableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80bd4ec8a9b2f8e7d9d75ab708a55c2">llvm::maxUIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>.</p>

</div>
</div>

### pseudoToMCOpcode() {#ae25e963e7382528026a78b5c2e31c435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SIInstrInfo::pseudoToMCOpcode (int Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a target-specific opcode if Opcode is a pseudo instruction.</p>


<p>Return -1 if the target-specific opcode for the pseudo instruction does not exist. If Opcode is not a pseudo instruction, this is identity.</p>


<p>Declaration at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadf3e0b276b086c14975adb3e2f00aa2c">llvm::SIInstrFlags::D16Buf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad079e8a6a0505ccce0ad2463d95aff73">llvm::AMDGPU::getMCOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5ff7467be99b93194854ce84b534f711">llvm::AMDGPU::getMFMAEarlyClobberOp</a>, <a href="#a81793225c0abc2a358b3710ed81189ec">getNonSoftWaitcntOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siencodingfamily/#ac0e8470f1a7e777b89ff85c06a5d46e0a7955d7c744435b171f0765c8e71d9f01">llvm::SIEncodingFamily::GFX80</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siencodingfamily/#ac0e8470f1a7e777b89ff85c06a5d46e0a5abe17ac8902bedceac72d80a3847e84">llvm::SIEncodingFamily::GFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siencodingfamily/#ac0e8470f1a7e777b89ff85c06a5d46e0a592bfac8aebf96c76ac5a1c7d1b50ea5">llvm::SIEncodingFamily::GFX90A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siencodingfamily/#ac0e8470f1a7e777b89ff85c06a5d46e0aa9c81f5c373123ac7eca13034907e288">llvm::SIEncodingFamily::GFX940</a>, <a href="#ab02ccaad1b78c3ebc1d06867f9c3e3b6">isAsmOnlyOpcode</a>, <a href="#a0605f773275c0461756eae0fb2321fa0">isMAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ac62bf222d2be994c709cc3abd57561a2">isRenamedInGFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siencodingfamily/#ac0e8470f1a7e777b89ff85c06a5d46e0a00d4ca5b02be436eeaf3d76e421fb1d3">llvm::SIEncodingFamily::SDWA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3cb08b10c27a453c57a2708e83859b47">llvm::SIInstrFlags::SDWA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siencodingfamily/#ac0e8470f1a7e777b89ff85c06a5d46e0ae10bfa40a3e82d9dcac79bf5ee11963c">llvm::SIEncodingFamily::SDWA10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siencodingfamily/#ac0e8470f1a7e777b89ff85c06a5d46e0a6fecfb3d512c10bb6bcb5fd41acf9346">llvm::SIEncodingFamily::SDWA9</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7e6b8f037057140c61a8d8fa6899eb76">subtargetEncodingFamily</a>.</p>


<p>Referenced by <a href="#aee81828a7ba7ae3e86ed968067d671b4">commuteOpcode</a>, <a href="#ad4445a2ce5876c120e2a6e6796edaf5c">convertToThreeAddress</a>, <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>, <a href="#ae3a62886ad892b99c103c15122b7eaa9">getMCOpcodeFromPseudo</a> and <a href="#a71b55958d73cd9fa8c5a32f5a6ac5a4c">hasVALU32BitEncoding</a>.</p>

</div>
</div>

### readlaneVGPRToSGPR() {#ac5b6ac3924041b35531d4e9bf66c3df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIInstrInfo::readlaneVGPRToSGPR (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy a value from a VGPR (<span class="doxyComputerOutput">SrcReg</span>) to SGPR.</p>


<p>The desired register class for the dst register (<span class="doxyComputerOutput">DstRC</span>) can be optionally supplied. This function can only be used when it is know that the value in SrcReg is same across all threads in the wave.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The SGPR register that <span class="doxyComputerOutput">SrcReg</span> was copied to.</p></dd>
</dl>


<p>Declaration at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 6231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>, <a href="#a23855b574f5790880e0cdfc2b6b39aad">legalizeOperandsFLAT</a> and <a href="#ad5c2911f44ee301ccf57ae61b7915b5a">legalizeOperandsSMRD</a>.</p>

</div>
</div>

### reMaterialize() {#a765f84a0c5289fe4fc72c224abc2e4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::reMaterialize (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Orig, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac485421b5fcb9454ea64e74f6396a810">llvm::MachineFunction::CloneMachineInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ac18c5827c119a73ea6f07b4ef4649654">getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab37075d621acbbfc96ef2662f2e29883">llvm::MachineInstr::memoperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aadcfe8906a95ad57f3f7a7d433f47204">llvm::TargetInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a001d31fcea92be51d2999826b806606f">llvm::MachineOperand::setSubReg</a>.</p>

</div>
</div>

### removeBranch() {#ac6a93ad1fcae43e09eb8a6d4c55d79ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::removeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, int * BytesRemoved=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### removeModOperands() {#a4fe4716676c6cd66f5db59639fc63bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::removeModOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ad606e03c366b7e91da3b735a7126fe5a">ModifierOpNames</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#a7a3901a88827b844402f5a9e484945a6">foldImmediate</a>.</p>

</div>
</div>

### restoreExec() {#a1e3fa2ce8f194193f39ed6428a86c05f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::restoreExec (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a10aea73adf903930a8ce4c133dfa5a1e">llvm::SlotIndexes::insertMachineInstrInMaps</a>, <a href="#a4b7d2799877b8bf1ebd139ef268ee7d6">isWave32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>.</p>

</div>
</div>

### reverseBranchCondition() {#a4d8d351faef4293dcc8a164ce2f87d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::reverseBranchCondition (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### shouldClusterMemOps() {#a48560701bbaa0465f8ef8d92874caaf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::shouldClusterMemOps (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; BaseOps1, int64_t Offset1, bool OffsetIsScalable1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; BaseOps2, int64_t Offset2, bool OffsetIsScalable2, unsigned ClusterSize, unsigned NumBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abe41cc313a9e7bcb8b71d428f64fb3a8">llvm::DefaultMemoryClusterDWordsLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a4e5d2df17988a87d9d72b6075ec1e5bf">llvm::SIMachineFunctionInfo::getMaxMemoryClusterDWords</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### shouldScheduleLoadsNear() {#a185895a367f8cba1b465d6fd2a660fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::shouldScheduleLoadsNear (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load0, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load1, int64_t Offset0, int64_t Offset1, unsigned NumLoads)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### splitFlatOffset() {#a51b89f22fd1adb2250ed1a38ed01ff5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int64_t, int64_t &gt; SIInstrInfo::splitFlatOffset (int64_t COffsetVal, unsigned AddrSpace, uint64_t FlatVariant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split <span class="doxyComputerOutput">COffsetVal</span> into {immediate offset field, remainder offset} values.</p>

<p>Declaration at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="#abf1cb325e16f2016182edac3352ea467">allowNegativeFlatOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2e4f719c21c52424a5a4e87c0d77c9d8">llvm::AMDGPU::getNumFlatOffsetBits</a>, <a href="#ab97de5c81e48922426466768a69b38bf">isLegalFLATOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>.</p>

</div>
</div>

### splitMUBUFOffset() {#a1952f8650a3b903ff78f5d5eb09c29a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::splitMUBUFOffset (uint32_t Imm, uint32_t &amp; SOffset, uint32_t &amp; ImmOffset, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(4))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="#a1fa48fff435124100b9bc18b162bcfd3">getMaxMUBUFImmOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05609d049bfe3c5c2f64711566131a86a28d0edd045e05cf5af64e35ae0c4c6ef">llvm::Low</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### storeRegToStackSlot() {#a6ec207a1c12adfc61c6566436e5a2cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::storeRegToStackSlot (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, bool isKill, int FrameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 1724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aa92f8b057e8d007d8e3c03828035b1d1">getSGPRSpillSaveOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2afcc4a332bb78d31847fd4a394a5aeb">llvm::SIMachineFunctionInfo::getStackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a651d110c1dac1aa8d4ba6cf535bfa6a0">getVectorRegSpillSaveOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ab5b19e21fc6b0765d7d551d2f07ae0f7">llvm::SIMachineFunctionInfo::setHasSpilledSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8fe30fcccc3364b6ff5ee7ba28aed8f8">llvm::SIMachineFunctionInfo::setHasSpilledVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a29a8016e50342e4598b3cb8a6601694f">llvm::TargetStackID::SGPRSpill</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### usesConstantBus() {#a1f6067626e3318b8569835d83acbd92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::usesConstantBus (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> &amp; OpInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this operand uses the constant bus.</p>

<p>Declaration at line 1126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>, <a href="#a2655c5c71aa8f4688c6bfb02bc2589f9">usesConstantBus</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### usesConstantBus() {#a2655c5c71aa8f4688c6bfb02bc2589f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::usesConstantBus (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIdx)</td>
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



<p>Definition at line 1130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#a1f6067626e3318b8569835d83acbd92e">usesConstantBus</a>.</p>

</div>
</div>

### usesFPDPRounding() {#aea2f43a12c41999677d0c4091c34d317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::usesFPDPRounding (uint16_t Opcode)</td>
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



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecade5bdaea3c9b894b4d8d07410372c7f1">llvm::SIInstrFlags::FPDPRounding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### verifyInstruction() {#ab92b353cd5e64914fd35af38bb31e61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::verifyInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ErrInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a1be8a1ab79f4d1830526cc8d48960168">llvm::SISrcMods::ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a19e16a0f3c37ba1524eb85c891bfa760">compareMachineOp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a81a328aa5781f7c744daa43c44df83c6">findImplicitSGPRRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9af58a5d20f2215a00b675f34db92771">llvm::AMDGPU::getAddrSizeMIMGOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a08b135e0f9484354a83410d97d698b22">llvm::AMDGPU::getBasicFromSDWAOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae1884e3318cb1f8a4465b1b4bd4d9827">llvm::AMDGPU::getMIMGBaseOpcodeInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7967181b077a4a08f5baf9950e30660d">llvm::AMDGPU::getMIMGDimInfoByEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0b5b29d1275f84b9e530fd2419cc03ac">llvm::AMDGPU::getMIMGInfo</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="#a7d38ae4f1dfa5ec71b0f78fab996425b">getOpRegClass</a>, <a href="#a0df02605d5e00cad00c3b7f4aef3aa14">getOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a51a3fe5250a82abf0ecbe57b156d1fd0">llvm::AMDGPU::isDPALU_DPP</a>, <a href="#a08b60e6be6801b1f90d723990ef68009">isDS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afcb818bd3e34498f8f72ca555a36d5eb">llvm::MachineOperand::isFPImm</a>, <a href="#a39d7080130a2d44447525617ead75825">isGather4</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a18d2b72326bbdea2a9c1653b090f00ff">llvm::AMDGPU::isLegalDPALU_DPPControl</a>, <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aa196e9f76f5a5bdc8a8aca82f95cd2b3">isRegOrFI</a>, <a href="#a3295a9f4a742f69dfa4d7bb91cced3a9">isSDWA</a>, <a href="#a1c990a34866f377751f50f112cef61bc">isSMRD</a>, <a href="#a5c4551760d712abe6c1234a4997e22de">isSOP2</a>, <a href="#adbbf88b03dcc6927f63b144f40bbc54c">isSOPC</a>, <a href="#a7d0fced78b683ae1e38051a1313615d2">isSOPK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#adbb4dcc227f28ef32563170ce820d498">isSubRegOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a>, <a href="#ab54d6d16078e78dfe594321574f39223">isVGPRSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a323a96a23d09892cc1b252bf1cba2732">isVOP2</a>, <a href="#a0aab14aaa9761a9af59b094090851ca3">isVOP3</a>, <a href="#a4e8b8e35244538ba4a04d756420454ba">isVOPC</a>, <a href="#a6bda023e350bc4b64cf3eaf60ad17a93">isVSAMPLE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ad8e4e0d44daebe8c07cf5d6d60a4fc30">llvm::InlineAsm::MIOp_FirstOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af1ceb53a1b47dab205dc19070b47a1a6">llvm::SISrcMods::NEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da767514e15ea244ad3e683ae79b583534">llvm::MCOI::OPERAND_IMMEDIATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af4b9cc7ae4320e5423baac7b35410470">llvm::AMDGPU::OPERAND_INLINE_SPLIT_BARRIER_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a09dd1263fb2164c20f99f89f69e01a6e">llvm::AMDGPU::OPERAND_KIMM32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa7f8a98ec46b1d30189640d9ff59bc1e">llvm::AMDGPU::OPERAND_REG_IMM_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af8ac73c62f6f1da6175d32824633a064">llvm::AMDGPU::OPERAND_REG_IMM_FP32_DEFERRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a5df5b6b6089b9237400d2c422db445d8">llvm::AMDGPU::OPERAND_REG_IMM_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae0f1ac0de50b2280311f02d7e1f5b25e">llvm::AMDGPU::OPERAND_REG_IMM_V2FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9eb871898b75ab91e808faf50f5f41a5">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa10ec5681f77906549e7a745593139a9">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae51ff25f16b928b2b8712a613e4fd3db">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9242629e3f7e6539015220a3d77d7dc7">llvm::AMDGPU::OPERAND_REG_INLINE_AC_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9f903a56d49f51a4697c5198aaea3459">llvm::AMDGPU::OPERAND_REG_INLINE_AC_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae6c8f9b5c5805da722239e1e5d8cda5d">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ac073c33efc03a1882ee8155b8d68a794">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a2f2cb7a6e0c1e04d17d4a2d79dfc85ca">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a8d695369aef7c9f7e0589f5b4673ea46">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ad670957823c39ba1006b962d2023a19a">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a86ef6f68b415f39fcd28ae0dd431297c">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da62a6ddcdddcce55f836b1720d29f90dc">llvm::MCOI::OPERAND_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a0842f25a9552eadbca3c10f9af0a36fe">llvm::SISrcMods::SEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#abcb710fb84bc86d961b6afbaa4f65d25">shouldReadExec</a>, <a href="#ad1abe1ce598551b2ff787ff98d987373">sopkIsZext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6a58f19664e2b69107495d2085514f7874">llvm::AMDGPU::SDWA::UNUSED_PRESERVE</a>, <a href="#a1f6067626e3318b8569835d83acbd92e">usesConstantBus</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#af49d69e68344d6292702edca157e7eed">llvm::AMDGPUAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### commuteInstructionImpl() {#adf5d3b4379e4e570f14f6700d6e87467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIInstrInfo::commuteInstructionImpl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool NewMI, unsigned OpIdx0, unsigned OpIdx1)</td>
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



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2811 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="#aee81828a7ba7ae3e86ed968067d671b4">commuteOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#acbbc2f6b22e0c1dfd00546ef61cc0ac3">isLegalToSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2f4e57397c15057e80f3edaeca9377f4">swapImmOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="#a64f165f45ca62b4d27bde48f484897da">swapSourceModifiers</a>.</p>

</div>
</div>

### isCopyInstrImpl() {#aa02d3a96bd6edd57c5ad1ac0997c3689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DestSourcePair &gt; SIInstrInfo::isCopyInstrImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>If the specific machine instruction is a instruction that moves/copies value from one register to another register return destination and source registers as machine operands.</p>

<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2697 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isLegalToSwap() {#acbbc2f6b22e0c1dfd00546ef61cc0ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isLegalToSwap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned fromIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * fromMO, unsigned toIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * toMO)</td>
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



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="#a835ce544e7ae111f1889501136ea6b3d">isImmOperandLegal</a>, <a href="#a0480d6290cd95e40641f2af7a18fb764">isInlineConstant</a>, <a href="#abecccbf97c3a9d0be384e6c639fcf2dc">isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da83076f86f6450732bc883b8723492eb2">llvm::MCOI::OPERAND_UNKNOWN</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#a9173ff0e651bbc7ce633a7c4b83d9586">llvm::MCOperandInfo::OperandType</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo/#ad3abf78805559fecd7642d0c57032c56">llvm::MCOperandInfo::RegClass</a>.</p>


<p>Referenced by <a href="#adf5d3b4379e4e570f14f6700d6e87467">commuteInstructionImpl</a>.</p>

</div>
</div>

### swapSourceModifiers() {#a64f165f45ca62b4d27bde48f484897da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::swapSourceModifiers (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Src0, unsigned Src0OpName, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Src1, unsigned Src1OpName)</td>
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



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a61297a04e9cd91c9658b9affecdd9797">getNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>.</p>


<p>Referenced by <a href="#adf5d3b4379e4e570f14f6700d6e87467">commuteInstructionImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addSCCDefsToVALUWorklist() {#a27ac34e4b52acd5a19de9075edfb6570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::addSCCDefsToVALUWorklist (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * SCCUseInst, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### addSCCDefUsersToVALUWorklist() {#a420c8abb8318650cbed42957c262a72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::addSCCDefUsersToVALUWorklist (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; SCCDefInst, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewCond=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### addUsersToMoveToVALUWorklist() {#a540d9f98316c586ac678a4f41cdcc540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::addUsersToMoveToVALUWorklist (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### checkInstOffsetsDoNotOverlap() {#a886ffd2612b0cdc9069185ba4c1b0639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::checkInstOffsetsDoNotOverlap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MIa, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MIb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### findUsedSGPR() {#afa3063538e9f379aefb19ec206c80ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SIInstrInfo::findUsedSGPR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIndices=[3])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### getDestEquivalentVGPRClass() {#adb8d217323ca49497ee5b9da76e67d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SIInstrInfo::getDestEquivalentVGPRClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### lowerScalarAbs() {#a310387a9e4da8f1b6601510dbc6f3bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::lowerScalarAbs (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7857 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### lowerScalarXnor() {#afd0219467e82cf77b377ae06d2d0ba6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::lowerScalarXnor (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7884 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### lowerSelect() {#ac2014eed012ceadf10d88ec92c2f8607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::lowerSelect (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### movePackToVALU() {#a0cd5087b7659c43c871bb297f626841d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::movePackToVALU (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### moveScalarAddSub() {#a77bb8c11f1e95e89d8d98429ce1eeccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, MachineBasicBlock * &gt; SIInstrInfo::moveScalarAddSub (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalar64BitBCNT() {#a5eb56aa00cc198632f8cce0ed435b7a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalar64BitBCNT (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalar64BitBFE() {#a95d7166bb858a197e65c3e87deeda719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalar64BitBFE (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalar64BitBinaryOp() {#afaaf2b0fbbed0a3986acec5544f1fb7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalar64BitBinaryOp (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalar64BitCountOp() {#a12719632d2b956fa5f3728d302f180f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalar64BitCountOp (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8448 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalar64BitUnaryOp() {#a8db97737df973c3d0e5a118199676b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalar64BitUnaryOp (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, unsigned Opcode, bool Swap=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8007 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalar64BitXnor() {#aa68070868c56f9e66716c171b173afc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalar64BitXnor (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalarBinOpN2() {#a8cfe91dfa2c3929f31cfb708fb1beb93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalarBinOpN2 (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7978 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalarNotBinop() {#afcd4a9a3988c99dc52823db254da66a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalarNotBinop (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 7949 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalarSMulPseudo() {#a36e945caa27deeb315dbd75f60cef403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalarSMulPseudo (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### splitScalarSMulU64() {#a9df4da022ec1274c7018c352937aa252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::splitScalarSMulU64 (<a href="/web-llvm/docs/api/structs/llvm/siinstrworklist">SIInstrWorklist</a> &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 8068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### swapOperands() {#a430d1aef5d72ff9fc6cd5878ac4df6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInstrInfo::swapOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 5848 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### verifyCopy() {#af07cf58235a87446cd8fab901e082728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::verifyCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ErrInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Formatter {#a00bd3fe47c6faeabb0e003c2aa98948b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AMDGPUMIRFormatter&gt; llvm::SIInstrInfo::Formatter</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### RI {#a55d9a298eefc229476399189a99a6199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo llvm::SIInstrInfo::RI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### SchedModel {#ad10cc4d3cb843e5c3ec533d0d5425513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSchedModel llvm::SIInstrInfo::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### ST {#ab639456d26be9a017e2bf1411cbef255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; llvm::SIInstrInfo::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### doesNotReadTiedSource() {#a3d948b7e2917067bdbab9e5ca0fff861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::doesNotReadTiedSource (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4777a05ca68d18f5d938d481ea0127c3">llvm::SIInstrFlags::TiedSourceNotRead</a>.</p>

</div>
</div>

### getDSShaderTypeValue() {#a8221c74806acd5e0e133095c1bd6a3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getDSShaderTypeValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 1457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca16c3e679fa61136bfeb3c5c9b7542d9f">llvm::CallingConv::AMDGPU_CS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad61318e853e529ac703f52a853efa1d1">llvm::CallingConv::AMDGPU_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539">llvm::CallingConv::AMDGPU_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606">llvm::CallingConv::AMDGPU_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca27a385675142c462571165c839e41aa0">llvm::CallingConv::AMDGPU_KERNEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf2c5be679d7769a9f3e5e308f73a9ff8">llvm::CallingConv::AMDGPU_LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8">llvm::CallingConv::AMDGPU_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getMaxMUBUFImmOffset() {#a1fa48fff435124100b9bc18b162bcfd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getMaxMUBUFImmOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Declaration at line 1398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>


<p>Referenced by <a href="#a018ed0bfa6715cb59a09af809ceb586e">isLegalMUBUFImmOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a14daf64c8f1ebcbe259a41854f49ad12">llvm::AMDGPULegalizerInfo::splitBufferOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a0924254734e306adcc8cdcd0e2a3544c">llvm::AMDGPURegisterBankInfo::splitBufferOffsets</a> and <a href="#a1952f8650a3b903ff78f5d5eb09c29a4">splitMUBUFOffset</a>.</p>

</div>
</div>

### getNonSoftWaitcntOpcode() {#a81793225c0abc2a358b3710ed81189ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIInstrInfo::getNonSoftWaitcntOpcode (unsigned Opcode)</td>
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



<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="#ab7db8082f8579f37580a95bb96bb2ad2">isWaitcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a80ca145710cb63f6d1484dacf37a8620">isWaitInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a8ca037899f2fcee956e635f6f5c0cb2c">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::promoteSoftWaitCnt</a> and <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>.</p>

</div>
</div>

### getNumWaitStates() {#ac1656e5749e564620d30b6c2bd704f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getNumWaitStates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return the number of wait states that result from executing this instruction.</p>

<p>Declaration at line 1292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 2095 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#ac513504a5496ffefed38d73cde2a351c">getWaitStatesSince</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a4e91d805ee46e758435fafffa3126255">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::runOnMachineBasicBlock</a>.</p>

</div>
</div>

### hasFPClamp() {#a88cd70c26e65e8c622336b8d1b5ecc1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::hasFPClamp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4c00f2292227a96409b86e250bac9b87">llvm::SIInstrFlags::FPClamp</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### hasIntClamp() {#ae181c0f85f73d387339267a62642b7ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::hasIntClamp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaeac247ab12a49434e1142ece1a35379b">llvm::SIInstrFlags::IntClamp</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isAtomic() {#acf2a604407f622a88ca631dfa50dd3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9dbc1631e11296bf1f8e95a2111a1bb9">llvm::SIInstrFlags::IsAtomicNoRet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca046343a654627954ce26d0e7531e12f7">llvm::SIInstrFlags::IsAtomicRet</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8e8f884db0a3faadefc981023902a1ec">getInstructionUniformity</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#a8107942d0fa6a3f4caa48f073e3ca1c4">isValidClauseInst</a>.</p>

</div>
</div>

### isAtomicNoRet() {#afbb07a5c117ab74c3cd893b82560bb82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isAtomicNoRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9dbc1631e11296bf1f8e95a2111a1bb9">llvm::SIInstrFlags::IsAtomicNoRet</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a4d5807670c4c32383f66d0e1df8936e0">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getVmemWaitEventType</a>.</p>

</div>
</div>

### isAtomicRet() {#a6c4c2a9d09070e2709f9725a915575e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isAtomicRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca046343a654627954ce26d0e7531e12f7">llvm::SIInstrFlags::IsAtomicRet</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### isChainCallOpcode() {#a959cf6b60787d90b8753099bcaa53f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isChainCallOpcode (uint64_t Opcode)</td>
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



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>

</div>
</div>

### isDisableWQM() {#a72af200d9640277de56f3c208181a9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDisableWQM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecae0063a0501793fcbc332d543bd1541bc">llvm::SIInstrFlags::DisableWQM</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isDOT() {#a3def5eabd8d8f1c67948c9626bf2be74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDOT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecabd8ac36f299f3add1ff63d49475d51a5">llvm::SIInstrFlags::IsDOT</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isDPP() {#a960996ed89167b7ad321c647644d8dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDPP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca06434d3505958806f243119630f8c976">llvm::SIInstrFlags::DPP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a>.</p>

</div>
</div>

### isDS() {#a08b60e6be6801b1f90d723990ef68009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca953a5ba3766c4aea8d9b8eeeba722679">llvm::SIInstrFlags::DS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a09ed4b8df3900d37518583f29bbb0144">areLoadsFromSameBasePtr</a>, <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="#ab65e8335ea0b5232a7f07f8fd5ec3566">isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpusetwavepriority-cpp-/amdgpusetwavepriority/#abca075108e917d65c698fd137d0afdd9">anonymous{AMDGPUSetWavePriority.cpp}::AMDGPUSetWavePriority::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a0673f88d21e33d7a42a66e19328fab3b">shouldRunLdsBranchVmemWARHazardFixup</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isDualSourceBlendEXP() {#acb7c4c826cd2ba559b369d732208fc07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isDualSourceBlendEXP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#af7592dc94276d1958420bcfb414b6998a8c000dbdd84cae416e103d023ca4f3bc">llvm::AMDGPU::Exp::ET_DUAL_SRC_BLEND0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#af7592dc94276d1958420bcfb414b6998a46aec9d69fc2301884b99597f4090df5">llvm::AMDGPU::Exp::ET_DUAL_SRC_BLEND1</a>, <a href="#a2d40ab246e329190bbf36cd93fd88e83">isEXP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isEXP() {#a2d40ab246e329190bbf36cd93fd88e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isEXP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3f6b33151573e94a6ef7f14b809dbe70">llvm::SIInstrFlags::EXP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="#acd85372be31eb6cd26e75c961e2ca5fa">hasUnwantedEffectsWhenEXECEmpty</a>, <a href="#acb7c4c826cd2ba559b369d732208fc07">isDualSourceBlendEXP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#a0a4dd89f625a6f7a354c0a5994114d1a">anonymous{AMDGPUExportClustering.cpp}::isExport</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### isF16PseudoScalarTrans() {#a945c33dc75a8491a32c7bd3e3d5ae944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isF16PseudoScalarTrans (unsigned Opcode)</td>
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



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>.</p>

</div>
</div>

### isFixedSize() {#aedb55bd2a3f524ae536b9c0ef17e41c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFixedSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3f90dc3ee0272479ff77f144e37b8abc">llvm::SIInstrFlags::FIXED_SIZE</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>.</p>

</div>
</div>

### isFLAT() {#adc3333d2d5974f4068df84f8706fc7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFLAT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574">llvm::SIInstrFlags::FLAT</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a43bab10420c4f91cf1dbbfbc34660926">breaksVMEMSoftClause</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a10d3dc29c5b795204cec9fe33433f1cc">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getHardClauseType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="#a8e8f884db0a3faadefc981023902a1ec">getInstructionUniformity</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a4d5807670c4c32383f66d0e1df8936e0">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getVmemWaitEventType</a>, <a href="#a4c2569a20f3cd4919625f6409b53d657">isHighLatencyDef</a>, <a href="#afb0e7b29c4c834f0985caab8aea638f9">isLDSDMA</a>, <a href="#a9fdde0eeb809933430f14eed5d1bb368">isLDSDMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a1f84fc794016facc8c5127ef79b740f2">isLdsDma</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#a3cb10174de0992496c363dd170177079">isVMEMClauseInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3b41f307768619a97e70860c9ff562cd">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::isVMEMOrFlatVMEM</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>, <a href="#a16c0128051315d3d5cc1f32047c7449c">mayAccessFlatAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isFLATGlobal() {#a65dcf8264f3f411eed5734a4b1ad7efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFLATGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca125415c6b554fcb76cedd65841141a92">llvm::SIInstrFlags::FlatGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac39e1c7fea00a5f2395927d0891edfce">anonymous{SIInsertWaitcnts.cpp}::updateVMCntOnly</a>.</p>

</div>
</div>

### isFLATScratch() {#a13fdc38a01504ed9a44abd1c9018737d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFLATScratch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#adc210f7d04be558143f8a891c892e550">llvm::SIRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a08a40d4d0736a73e47089ba3ef2e1566">llvm::SIRegisterInfo::getScratchInstrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a0989f99e854e569e8096a89e73f2e046">llvm::SIRegisterInfo::isFrameOffsetLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aae2e3ed0f579b512e6a38d0f116553ea">llvm::SIRegisterInfo::needsFrameBaseReg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac39e1c7fea00a5f2395927d0891edfce">anonymous{SIInsertWaitcnts.cpp}::updateVMCntOnly</a>.</p>

</div>
</div>

### isFoldableCopy() {#a826c5f2bb260d27a430d48225e03383e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isFoldableCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7326d1a0ae53d6dece409404840c5e6f">getFoldableImm</a>.</p>

</div>
</div>

### isFPAtomic() {#aaaa31803a8b78287f011850b909536ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isFPAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaccce8eb3ea48e8b0d5f5b7e9e011cc19">llvm::SIInstrFlags::FPAtomic</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isGather4() {#a39d7080130a2d44447525617ead75825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isGather4 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca1fb3a3c9d73c11f77861315b283e3fde">llvm::SIInstrFlags::Gather4</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isGWS() {#a5d2be32319a4c9ca5a0a37d0e2a3a68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isGWS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0f98bad3dd2f0146ac2135da67847c9d">llvm::SIInstrFlags::GWS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa4b208f7f6a759e6572b26d8b9ebb435">isAlwaysGDS</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>.</p>

</div>
</div>

### isImage() {#a7cffecf3a0aef3f0140d36560a2959d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isImage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#abdcf600002fd489c76924f2ec4f4fc0f">isMIMG</a>, <a href="#a5aa81dfde6b9b4ae42959839cd84cd63">isVIMAGE</a>, <a href="#a6bda023e350bc4b64cf3eaf60ad17a93">isVSAMPLE</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="#a08b830059090a1bb27b14e1e524fdb46">isVMEM</a>, <a href="#aba5b6e8b61c6dea0c9a2b710bc387464">isVMEM</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isKillTerminator() {#a6ca25d96b652c00368600bd3845f5591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::isKillTerminator (unsigned Opcode)</td>
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



<p>Declaration at line 1393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 9144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### isLDSDIR() {#a5b2aaf80981b29494436f2b18a604e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isLDSDIR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecafe9bf84e87ab9f272db7a7145eb59758">llvm::SIInstrFlags::LDSDIR</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### isLDSDMA() {#afb0e7b29c4c834f0985caab8aea638f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isLDSDMA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#adc3333d2d5974f4068df84f8706fc7d2">isFLAT</a>, <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a>, <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a> and <a href="#a35927952ceaf2f903e7d3aa920588daf">mayWriteLDSThroughDMA</a>.</p>

</div>
</div>

### isMAI() {#a0605f773275c0461756eae0fb2321fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMAI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa0bc33f3818c02a577a8b209d98766cb">llvm::SIInstrFlags::IsMAI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="#a835ce544e7ae111f1889501136ea6b3d">isImmOperandLegal</a>, <a href="#a96ebcd476b7e0bf9c549c423546b18dc">isMFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a1ae686346eda7767d0bff99d452e0b9f">isXDL</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a> and <a href="#ae25e963e7382528026a78b5c2e31c435">pseudoToMCOpcode</a>.</p>

</div>
</div>

### isMFMA() {#a96ebcd476b7e0bf9c549c423546b18dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMFMA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a0605f773275c0461756eae0fb2321fa0">isMAI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a3c8354f891fe3cb5f3df8d1d867b6780">isMFMAorWMMA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#accfcd00e03bf4fddc4d3b32657c3e291">llvm::GCNHazardRecognizer::ShouldPreferAnother</a>.</p>

</div>
</div>

### isMFMAorWMMA() {#a3c8354f891fe3cb5f3df8d1d867b6780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMFMAorWMMA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a96ebcd476b7e0bf9c549c423546b18dc">isMFMA</a>, <a href="#a4a0e3ab6c51718d8e2181821b6147022">isSWMMAC</a>, <a href="#ad20315758fcf345ce175df966fae0c82">isWMMA</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isMIMG() {#abdcf600002fd489c76924f2ec4f4fc0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMIMG (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0666b703f5fe8ee884171492fb6a685a">llvm::SIInstrFlags::MIMG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a10d3dc29c5b795204cec9fe33433f1cc">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getHardClauseType</a>, <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ae89cf351b4c02b5f35b361ad6ca79d14">anonymous{SIInsertWaitcnts.cpp}::getVmemType</a>, <a href="#a4c2569a20f3cd4919625f6409b53d657">isHighLatencyDef</a>, <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="#a442e49a14785b3d4d178bd56cd65d20c">isImage</a>, <a href="#ab65e8335ea0b5232a7f07f8fd5ec3566">isLegalRegOperand</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isMTBUF() {#a2c6289dfab83449b3f69792b35277cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMTBUF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4863f895381859543f89e4423126a73f">llvm::SIInstrFlags::MTBUF</a>.</p>


<p>Referenced by <a href="#a09ed4b8df3900d37518583f29bbb0144">areLoadsFromSameBasePtr</a>, <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="#a4c2569a20f3cd4919625f6409b53d657">isHighLatencyDef</a>, <a href="#a08b830059090a1bb27b14e1e524fdb46">isVMEM</a>, <a href="#aba5b6e8b61c6dea0c9a2b710bc387464">isVMEM</a> and <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### isMUBUF() {#a8616d2d8f4c04005569e89bcfe67e421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isMUBUF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2fca87a5855f045ac7f07d8c2814e81f">llvm::SIInstrFlags::MUBUF</a>.</p>


<p>Referenced by <a href="#a09ed4b8df3900d37518583f29bbb0144">areLoadsFromSameBasePtr</a>, <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#adc210f7d04be558143f8a891c892e550">llvm::SIRegisterInfo::getFrameIndexInstrOffset</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a08a40d4d0736a73e47089ba3ef2e1566">llvm::SIRegisterInfo::getScratchInstrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a0989f99e854e569e8096a89e73f2e046">llvm::SIRegisterInfo::isFrameOffsetLegal</a>, <a href="#a4c2569a20f3cd4919625f6409b53d657">isHighLatencyDef</a>, <a href="#afb0e7b29c4c834f0985caab8aea638f9">isLDSDMA</a>, <a href="#a9fdde0eeb809933430f14eed5d1bb368">isLDSDMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a1f84fc794016facc8c5127ef79b740f2">isLdsDma</a>, <a href="#aac9bf357fe1b75c63b4b789a93b0a7a7">isLoadFromStackSlot</a>, <a href="#a207df7ea2d140c874d9b1d93d60774c7">isStoreToStackSlot</a>, <a href="#a08b830059090a1bb27b14e1e524fdb46">isVMEM</a>, <a href="#aba5b6e8b61c6dea0c9a2b710bc387464">isVMEM</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aae2e3ed0f579b512e6a38d0f116553ea">llvm::SIRegisterInfo::needsFrameBaseReg</a>.</p>

</div>
</div>

### isNeverUniform() {#a0d8a3508b676977a0396a0bb055c0a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isNeverUniform (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca31a282e99b9ec37019e46aa2481190e9">llvm::SIInstrFlags::IsNeverUniform</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8e8f884db0a3faadefc981023902a1ec">getInstructionUniformity</a>.</p>

</div>
</div>

### isPacked() {#aae4c830b57693cee2adf434f4b9c394f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isPacked (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaacf639f4528a313767923c5575e1828e">llvm::SIInstrFlags::IsPacked</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isSALU() {#a2d7ac7b1dd9a9e4ae81fb54010f324f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSALU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab20a2dd15666d86af4e1fdeb88b1be7c">llvm::SIInstrFlags::SALU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aee8dc206a90191cd9b5a7ad2fbbead3d">canRemat</a>, <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>, <a href="#ad1f10f87fb228c645dab08a31a02d0a6">isSGPRSpill</a>, <a href="#a96ee73177af6a48c7ce8c098c6a9cb19">isSGPRSpill</a>, <a href="#ad4705aea7dab2a011b09f6036a49087c">mayReadEXEC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#abcb710fb84bc86d961b6afbaa4f65d25">shouldReadExec</a>.</p>

</div>
</div>

### isScalarStore() {#a9a8fba38c0c431dd917ceff91ccdbd73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isScalarStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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
<dd><p>true if this is an s_store_dword* instruction. This is more specific than isSMEM &amp;&amp; mayStore.</p></dd>
</dl>


<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadaafc9c279a6480f1729929b26a4ad05">llvm::SIInstrFlags::SCALAR_STORE</a>.</p>

</div>
</div>

### isScalarUnit() {#ae57ec0924f807505d7b9a64e30b1dc49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isScalarUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab20a2dd15666d86af4e1fdeb88b1be7c">llvm::SIInstrFlags::SALU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca30118e93ea743944a8fa1d846dcbaf37">llvm::SIInstrFlags::SMRD</a>.</p>

</div>
</div>

### isSDWA() {#a3295a9f4a742f69dfa4d7bb91cced3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSDWA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3cb08b10c27a453c57a2708e83859b47">llvm::SIInstrFlags::SDWA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aee8dc206a90191cd9b5a7ad2fbbead3d">canRemat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a3a1aa0c4abee6f79580733a3c6e9077f">getDstSelForwardingOperand</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isSegmentSpecificFLAT() {#a8ed947ddafde5421d3f771f43f9c04d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSegmentSpecificFLAT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca125415c6b554fcb76cedd65841141a92">llvm::SIInstrFlags::FlatGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da">llvm::SIInstrFlags::FlatScratch</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a10d3dc29c5b795204cec9fe33433f1cc">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getHardClauseType</a>, <a href="#a23855b574f5790880e0cdfc2b6b39aad">legalizeOperandsFLAT</a>, <a href="#ac786791624fc85886f2db5c5e0601f1b">moveFlatAddrToVGPR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a0673f88d21e33d7a42a66e19328fab3b">shouldRunLdsBranchVmemWARHazardFixup</a>.</p>

</div>
</div>

### isSGPRSpill() {#ad1f10f87fb228c645dab08a31a02d0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSGPRSpill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a2d7ac7b1dd9a9e4ae81fb54010f324f9">isSALU</a>, <a href="#a54dd07afbc21c48f8a0563bf246e466a">isSpill</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a0ff5f8777cbfcc5921552cf2f4a93a36">isBasicBlockPrologue</a>, <a href="#aac9bf357fe1b75c63b4b789a93b0a7a7">isLoadFromStackSlot</a> and <a href="#a207df7ea2d140c874d9b1d93d60774c7">isStoreToStackSlot</a>.</p>

</div>
</div>

### isSMRD() {#a1c990a34866f377751f50f112cef61bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSMRD (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca30118e93ea743944a8fa1d846dcbaf37">llvm::SIInstrFlags::SMRD</a>.</p>


<p>Referenced by <a href="#a09ed4b8df3900d37518583f29bbb0144">areLoadsFromSameBasePtr</a>, <a href="#af724c54b41bc0a366bf3197f2855ce83">areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a18506bf00376c57b5c843b5253e9712e">breaksSMEMSoftClause</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aee8dc206a90191cd9b5a7ad2fbbead3d">canRemat</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a10d3dc29c5b795204cec9fe33433f1cc">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getHardClauseType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="#a0c826f5192676a1dfa8468a38b9ce1c3">getMemOperandsWithOffsetWidth</a>, <a href="#acd85372be31eb6cd26e75c961e2ca5fa">hasUnwantedEffectsWhenEXECEmpty</a>, <a href="#a6c6831e85182fd706818bd9196f8604a">isBufferSMRD</a>, <a href="#a975ccb82baef08d83e403c8818c52db8">isLowLatencyInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#af3367b6df459bfb820f419891f9ae8d3">isSMEMClauseInst</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#abcb710fb84bc86d961b6afbaa4f65d25">shouldReadExec</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isSOP1() {#adacd3cb5a6ca5003891b6d0032b9ade5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOP1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa1db6db58e0bae030fb7277723deb3a9">llvm::SIInstrFlags::SOP1</a>.</p>

</div>
</div>

### isSOP2() {#a5c4551760d712abe6c1234a4997e22de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOP2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2f0e3ce334e6b7fa59a2822e2770ab1d">llvm::SIInstrFlags::SOP2</a>.</p>


<p>Referenced by <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isSOPC() {#adbbf88b03dcc6927f63b144f40bbc54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOPC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadad0f2be60062a72d37634705e8aed51">llvm::SIInstrFlags::SOPC</a>.</p>


<p>Referenced by <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isSOPK() {#a7d0fced78b683ae1e38051a1313615d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOPK (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca95d3d9b72a40bcb9f88738fd86094a62">llvm::SIInstrFlags::SOPK</a>.</p>


<p>Referenced by <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isSOPP() {#a1152df63da5e2f53576d9922fa408625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSOPP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3240de017ea18f8b8daf38bc4d927294">llvm::SIInstrFlags::SOPP</a>.</p>

</div>
</div>

### isSpill() {#a15e38d2ff0c0ba3927e062447f0ea649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSpill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa444d6850530e37d8af98558ce5b25f5">llvm::SIInstrFlags::Spill</a>.</p>

</div>
</div>

### isSWMMAC() {#a4a0e3ab6c51718d8e2181821b6147022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isSWMMAC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2b696c2aeb385ace4a1088a1169606a4">llvm::SIInstrFlags::IsSWMMAC</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a3c8354f891fe3cb5f3df8d1d867b6780">isMFMAorWMMA</a>.</p>

</div>
</div>

### isTRANS() {#a7c01b647a2569809ece29a7ce35e5102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isTRANS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca6edf620aaa09a9f39b50177b8fa809d4">llvm::SIInstrFlags::TRANS</a>.</p>

</div>
</div>

### isVALU() {#ade8d533000b775c514d9ac189b66c3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVALU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca25bdad6e13bc9ed9f9ce690ae614db1c">llvm::SIInstrFlags::VALU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a3a1aa0c4abee6f79580733a3c6e9077f">getDstSelForwardingOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="#a0ced2d6b15f87f297ec231c753e624e6">getInstSizeInBytes</a>, <a href="#a857ec99c61bfc201bb60525234551102">isIgnorableUse</a>, <a href="#afb0e7b29c4c834f0985caab8aea638f9">isLDSDMA</a>, <a href="#a9fdde0eeb809933430f14eed5d1bb368">isLDSDMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a1f84fc794016facc8c5127ef79b740f2">isLdsDma</a>, <a href="#acbbc2f6b22e0c1dfd00546ef61cc0ac3">isLegalToSwap</a>, <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>, <a href="#ab54d6d16078e78dfe594321574f39223">isVGPRSpill</a>, <a href="#a1e525d2b10c6f432c4ee58dcba3a95c5">isVGPRSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpusetwavepriority-cpp-/amdgpusetwavepriority/#abca075108e917d65c698fd137d0afdd9">anonymous{AMDGPUSetWavePriority.cpp}::AMDGPUSetWavePriority::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#abcb710fb84bc86d961b6afbaa4f65d25">shouldReadExec</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isVGPRSpill() {#ab54d6d16078e78dfe594321574f39223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVGPRSpill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a54dd07afbc21c48f8a0563bf246e466a">isSpill</a>, <a href="#ade8d533000b775c514d9ac189b66c3a5">isVALU</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aac9bf357fe1b75c63b4b789a93b0a7a7">isLoadFromStackSlot</a>, <a href="#a207df7ea2d140c874d9b1d93d60774c7">isStoreToStackSlot</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isVIMAGE() {#a5aa81dfde6b9b4ae42959839cd84cd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVIMAGE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaffe2f0079ddf5f206b323cdecec1e655">llvm::SIInstrFlags::VIMAGE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ae89cf351b4c02b5f35b361ad6ca79d14">anonymous{SIInsertWaitcnts.cpp}::getVmemType</a>, <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="#a442e49a14785b3d4d178bd56cd65d20c">isImage</a> and <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>.</p>

</div>
</div>

### isVINTERP() {#a85e762ca75d1db9247a7d659fbf77d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVINTERP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca1440c15f5bea6a1ebb07324b7be433c3">llvm::SIInstrFlags::VINTERP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aba82e76518953661f6dcb009c73e1a1f">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcnt</a>.</p>

</div>
</div>

### isVINTRP() {#a367f8f335f81011958967cd6fb98e9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVINTRP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0bd36c4d359999d7043f5fdf440b0c7c">llvm::SIInstrFlags::VINTRP</a>.</p>

</div>
</div>

### isVMEM() {#a08b830059090a1bb27b14e1e524fdb46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVMEM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="#a2c6289dfab83449b3f69792b35277cac">isMTBUF</a>, <a href="#a8616d2d8f4c04005569e89bcfe67e421">isMUBUF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a43bab10420c4f91cf1dbbfbc34660926">breaksVMEMSoftClause</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a10d3dc29c5b795204cec9fe33433f1cc">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getHardClauseType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a4d5807670c4c32383f66d0e1df8936e0">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getVmemWaitEventType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#a3cb10174de0992496c363dd170177079">isVMEMClauseInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusetwavepriority-cpp/#a7b7e23f3b3b1766a6de33e770a0394e4">isVMEMLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3b41f307768619a97e70860c9ff562cd">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::isVMEMOrFlatVMEM</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a8b16457758ae332c79a7f276f68d2c17">llvm::GCNHazardRecognizer::PreEmitNoopsCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a0673f88d21e33d7a42a66e19328fab3b">shouldRunLdsBranchVmemWARHazardFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac39e1c7fea00a5f2395927d0891edfce">anonymous{SIInsertWaitcnts.cpp}::updateVMCntOnly</a>.</p>

</div>
</div>

### isVOP1() {#afe1b887d2fad2d25f93580c261fea3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0dd2852ae8f20b7261f6d01eb354f1ff">llvm::SIInstrFlags::VOP1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aee8dc206a90191cd9b5a7ad2fbbead3d">canRemat</a>.</p>

</div>
</div>

### isVOP2() {#a323a96a23d09892cc1b252bf1cba2732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca600d26b3fa43f262c5ca2270667c0be2">llvm::SIInstrFlags::VOP2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aee8dc206a90191cd9b5a7ad2fbbead3d">canRemat</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isVOP3() {#a0aab14aaa9761a9af59b094090851ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP3 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca78562688e8d67f7ffa892e4b92311a98">llvm::SIInstrFlags::VOP3</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aee8dc206a90191cd9b5a7ad2fbbead3d">canRemat</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="#a835ce544e7ae111f1889501136ea6b3d">isImmOperandLegal</a>, <a href="#af7ee4c22ed353efa8afd9ea35e4af06f">isOperandLegal</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a>, <a href="#aae3719bc967fb84bbbd69ac597866ea1">moveToVALUImpl</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isVOP3P() {#ac1b8098108d7629973d94015838b8904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOP3P (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4b3bb80273571c42a8b35d5e952034c9">llvm::SIInstrFlags::VOP3P</a>.</p>

</div>
</div>

### isVOPC() {#a4e8b8e35244538ba4a04d756420454ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVOPC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca40767b966aa194931bb6ce67e3649de7">llvm::SIInstrFlags::VOPC</a>.</p>


<p>Referenced by <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isVSAMPLE() {#a6bda023e350bc4b64cf3eaf60ad17a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isVSAMPLE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca68afea1b16331758f09fc0d8c229b86f">llvm::SIInstrFlags::VSAMPLE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ae89cf351b4c02b5f35b361ad6ca79d14">anonymous{SIInsertWaitcnts.cpp}::getVmemType</a>, <a href="#a7cffecf3a0aef3f0140d36560a2959d9">isImage</a>, <a href="#a442e49a14785b3d4d178bd56cd65d20c">isImage</a>, <a href="#a09787033a63326e79a0d1445d3e0de13">legalizeOperands</a> and <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### isWMMA() {#ad20315758fcf345ce175df966fae0c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isWMMA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadb719433b001db91973f66b4bc3b6dc8">llvm::SIInstrFlags::IsWMMA</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad4445a2ce5876c120e2a6e6796edaf5c">convertToThreeAddress</a> and <a href="#a3c8354f891fe3cb5f3df8d1d867b6780">isMFMAorWMMA</a>.</p>

</div>
</div>

### isWQM() {#a3d133265b86c18fe71284768fa495726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isWQM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecae51b91ec89e9fd6502c3339d1360c147">llvm::SIInstrFlags::WQM</a>.</p>

</div>
</div>

### isWWMRegSpillOpcode() {#ab9abb6b24aca583f0b52e19267d750f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::isWWMRegSpillOpcode (uint16_t Opcode)</td>
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



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a0ff5f8777cbfcc5921552cf2f4a93a36">isBasicBlockPrologue</a>.</p>

</div>
</div>

### mayWriteLDSThroughDMA() {#a35927952ceaf2f903e7d3aa920588daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::mayWriteLDSThroughDMA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="#afb0e7b29c4c834f0985caab8aea638f9">isLDSDMA</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a4d5807670c4c32383f66d0e1df8936e0">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getVmemWaitEventType</a>.</p>

</div>
</div>

### modifiesModeRegister() {#ac49e04076b2aaf96a7497774136482f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInstrInfo::modifiesModeRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true if the instruction modifies the mode register.q.</p>

<p>Declaration at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 4204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#acd85372be31eb6cd26e75c961e2ca5fa">hasUnwantedEffectsWhenEXECEmpty</a>.</p>

</div>
</div>

### sopkIsZext() {#ad1abe1ce598551b2ff787ff98d987373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::sopkIsZext (unsigned Opcode)</td>
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



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>Referenced by <a href="#ab92b353cd5e64914fd35af38bb31e61b">verifyInstruction</a>.</p>

</div>
</div>

### usesFPDPRounding() {#a4216fe6040d5c549d7ea1f997f3fb53b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::usesFPDPRounding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecade5bdaea3c9b894b4d8d07410372c7f1">llvm::SIInstrFlags::FPDPRounding</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### usesLGKM\_CNT() {#aabb9a8e62924675b70fc1f53021735f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::usesLGKM_CNT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaee110070224119e12075fafd4909dc9c">llvm::SIInstrFlags::LGKM_CNT</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### usesVM\_CNT() {#aea20d1c20096fa82081f0b56e083dd32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIInstrInfo::usesVM_CNT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaf5dfd8c9db8b07c80292e662aa96c6a7">llvm::SIInstrFlags::VM_CNT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getBranchOpcode() {#a9423207b1e848080ff3094e5a093d1fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SIInstrInfo::getBranchOpcode (BranchPredicate Cond)</td>
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



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3051 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

### getBranchPredicate() {#a1d8a3cec14381fa584c86f5dd3dbeb97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIInstrInfo::BranchPredicate SIInstrInfo::getBranchPredicate (unsigned Opcode)</td>
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



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>, definition at line 3070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp">SIInstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
