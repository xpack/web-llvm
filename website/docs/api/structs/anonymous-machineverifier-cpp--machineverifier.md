---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-machineverifier-cpp-/machineverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MachineVerifier` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{MachineVerifier.cpp}::MachineVerifier { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb0af3f20c655a05b85bf8bd0d17290">RegVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 16 &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7515f74c09d87830e827e246e3370aa">RegMaskVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *, 4 &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817eebb0935f04aae42afad79e30a3d6">RegSet</a> = <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8b816afd805c78ea6ce805e294c5c2">RegMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7a6b12b82a177fe2fadb0c3aa51097">BlockSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 8 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19171d1cdf2a6314188f142bbf9b99e9">MachineVerifier</a> (MachineFunctionAnalysisManager &amp;MFAM, const char *b, raw_ostream *OS, bool AbortOnError=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425a5bc2fd119f68ba7d600520241926">MachineVerifier</a> (Pass *pass, const char *b, raw_ostream *OS, bool AbortOnError=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a> (const char *b, LiveVariables *LiveVars, LiveIntervals *LiveInts, LiveStacks *LiveStks, SlotIndexes *Indexes, raw_ostream *OS, bool AbortOnError=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584173fafbf5c085fa334e4a236febed">verify</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587ee120f5b142b50860160b9e698d2c">addRegWithSubRegs</a> (RegVector &amp;RV, Register Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ecab0dcc8cd296f6c8bb0988dcd25d4">isReserved</a> (Register Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83e2e7a6e2935a30ec4bd45be04ea33">isAllocatable</a> (Register Reg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> (const MachineBasicBlock *MBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e25e754febed9d86fa367556dde1cc5">visitMachineBundleBefore</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea75ebde801fdd2dac4b3a279de9eeb">verifyAllRegOpsScalar</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that all of <span class="doxyComputerOutput">MI's</span> virtual register operands are scalars. <a href="#a8ea75ebde801fdd2dac4b3a279de9eeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d2e4271c38bdc43a3b072a050a1a0f">verifyVectorElementMatch</a> (LLT Ty0, LLT Ty1, const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check that types are consistent when two operands need to have the same number of vector elements. <a href="#a46d2e4271c38bdc43a3b072a050a1a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65af2646bf1b0db3340b48e472c7194c">verifyGIntrinsicSideEffects</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba6472d6c916233f98bf13155d959bf">verifyGIntrinsicConvergence</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a> (const MachineOperand *MO, unsigned MONum)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a> (const MachineBasicBlock *MBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> (const char *msg, const MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac7e17898dfcf67d9b745d74926f1c8">report</a> (const char *msg, const MachineBasicBlock *MBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4330df68342a7c3972e7e6e6852c40b8">report</a> (const char *msg, const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd58763bac8cd7e011630ae06d14656">report</a> (const char *msg, const MachineOperand *MO, unsigned MONum, LLT MOVRegType=LLT{})</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9af968db2378a07e8ccc04d6e100b5">report</a> (const Twine &amp;Msg, const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a> (const LiveInterval &amp;LI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a714204eaae44d1230babc303f282e1ef">report_context</a> (const LiveRange &amp;LR, VirtRegOrUnit VRegOrUnit, LaneBitmask LaneMask) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174d49c5fb27ac4cfb907989cf31ba96">report_context</a> (const LiveRange::Segment &amp;S) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02cdb6766947f5b6254789d07cfb88e">report_context</a> (const VNInfo &amp;VNI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb656c419a8873b3108189dda9eba4ca">report_context</a> (SlotIndex Pos) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> (MCPhysReg PhysReg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb948937bd8d69deb8fa5a8ffa491d0">report_context_liverange</a> (const LiveRange &amp;LR) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07287e0c57a0d4d5238eebb0cca0fcc">report_context_lanemask</a> (LaneBitmask LaneMask) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae38908b27849a89a7e45d4d235212be9">report_context_vreg</a> (Register VReg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a> (VirtRegOrUnit VRegOrUnit) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c94504ca3d3dcb826cd34ec463f98e">verifyInlineAsm</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a> (const MachineOperand *MO, unsigned MONum)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a> (const MachineOperand *MO, unsigned MONum, SlotIndex UseIdx, const LiveRange &amp;LR, VirtRegOrUnit VRegOrUnit, LaneBitmask LaneMask=LaneBitmask::getNone())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a> (const MachineOperand *MO, unsigned MONum, SlotIndex DefIdx, const LiveRange &amp;LR, VirtRegOrUnit VRegOrUnit, bool SubRangeCheck=false, LaneBitmask LaneMask=LaneBitmask::getNone())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34a220d0655748b7ad5a1b5d2994dec">markReachable</a> (const MachineBasicBlock *MBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990694380bae24a3a5b09b9a12f2e333">calcRegsPassed</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5250336b7b5e6c5f3c8e88fb9a9041">checkPHIOps</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97f881f7a367863cbd154c3adb1477f2">calcRegsRequired</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a> (const LiveInterval &amp;)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a> (const LiveRange &amp;, const VNInfo *, VirtRegOrUnit, LaneBitmask)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a> (const LiveRange &amp;, const LiveRange::const_iterator I, VirtRegOrUnit, LaneBitmask)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8281afcc693674f4ff5c0d2198c770">verifyLiveRange</a> (const LiveRange &amp;, VirtRegOrUnit, LaneBitmask LaneMask=LaneBitmask::getNone())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure on every path through the CFG, a FrameSetup &lt;n&gt; is always followed by a FrameDestroy &lt;n&gt;, stack adjustments are identical on all CFG edges to a merge point, and frame is destroyed at end of a return block. <a href="#a63ebe76813ff76375cf5705af12bdcd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026d7ee38d907cccbeb812b0747f957c">verifyStackProtector</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check that the stack protector is the top-most object in the stack. <a href="#a026d7ee38d907cccbeb812b0747f957c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca3d76a730626f0c9a0b4c85080e857">verifySlotIndexes</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0b543b45553dd02d7c1801ea59a31f">verifyProperties</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce0d09b265d455289b94043ffb4dff7">MFAM</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef38834758876f9b5ddb6cb0a4ba5e2a">PASS</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851c87f496a7efe488499e0799b79a03">Banner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9599bcccbe0a4a711aaa63ce373ae210">TM</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad137877cd7afd839b779d787a94d9a">RBI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf4d1e7c8ef538cff52d1e67d21d597f">isFunctionRegBankSelected</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ebf4892cb9961d63fe6691ae9296dd0">isFunctionSelected</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6daa5950d65d33692a36f3638417d741">isFunctionTracksDebugUserValues</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9b7298af9712b0dbe14fad12e44793">FirstNonPHI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5206b5d1e2b30c3fa57ccc093f70b518">FirstTerminator</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9a7a6b12b82a177fe2fadb0c3aa51097">BlockSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4237d028145173f9212a57223b91def">FunctionBlocks</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13765a244d6e934af46ec0a627b59925">regsReserved</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a817eebb0935f04aae42afad79e30a3d6">RegSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b5a4081ce723184fea1277ebea4c5ac">regsLive</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aefb0af3f20c655a05b85bf8bd0d17290">RegVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c60a652432f5bb026313d7f70006a6">regsDefined</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aefb0af3f20c655a05b85bf8bd0d17290">RegVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac413e02c0425e60d0674041f9d641f4f">regsDead</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aefb0af3f20c655a05b85bf8bd0d17290">RegVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bce6a8ada69da1302518e0c38a91a5">regsKilled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab7515f74c09d87830e827e246e3370aa">RegMaskVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8154011099ded2eb5f1375a7564e96f9">regMasks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d616b586fe73a891822b60cf2812dd">lastIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo">BBInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livevariables">LiveVariables</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be61c1a407ed680072a5bb87da9f0d3">LiveVars</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livestacks">LiveStacks</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3e2a496d3614dd93f99d43c2c5921f">LiveStks</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machineverifier-cpp-/machineverifier/reportederrors">ReportedErrors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c3b861c16bd22644b51e096b42155f">ReportedErrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5056903a77a7aa46d4d1529db53f7fe">DT</a></td>
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


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockSet {#a9a7a6b12b82a177fe2fadb0c3aa51097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineVerifier.cpp}::MachineVerifier::BlockSet =  SmallPtrSet&lt;const MachineBasicBlock *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

### RegMap {#a0e8b816afd805c78ea6ce805e294c5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineVerifier.cpp}::MachineVerifier::RegMap =  DenseMap&lt;Register, const MachineInstr *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

### RegMaskVector {#ab7515f74c09d87830e827e246e3370aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineVerifier.cpp}::MachineVerifier::RegMaskVector =  SmallVector&lt;const uint32_t *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

### RegSet {#a817eebb0935f04aae42afad79e30a3d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineVerifier.cpp}::MachineVerifier::RegSet =  DenseSet&lt;Register&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

### RegVector {#aefb0af3f20c655a05b85bf8bd0d17290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineVerifier.cpp}::MachineVerifier::RegVector =  SmallVector&lt;Register, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineVerifier() {#a19171d1cdf2a6314188f142bbf9b99e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineVerifier.cpp}::MachineVerifier::MachineVerifier (<a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp; MFAM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * b, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * OS, bool AbortOnError=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a851c87f496a7efe488499e0799b79a03">Banner</a>, <a href="#a7ce0d09b265d455289b94043ffb4dff7">MFAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ad4ae565ad87db4c534952e2c88f310">llvm::nulls</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a> and <a href="#a21c3b861c16bd22644b51e096b42155f">ReportedErrs</a>.</p>

</div>
</div>

### MachineVerifier() {#a425a5bc2fd119f68ba7d600520241926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineVerifier.cpp}::MachineVerifier::MachineVerifier (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * pass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * b, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * OS, bool AbortOnError=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a851c87f496a7efe488499e0799b79a03">Banner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ad4ae565ad87db4c534952e2c88f310">llvm::nulls</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="#aef38834758876f9b5ddb6cb0a4ba5e2a">PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab1172d7b7736569e908ce727bfb3e358">pass</a> and <a href="#a21c3b861c16bd22644b51e096b42155f">ReportedErrs</a>.</p>

</div>
</div>

### MachineVerifier() {#a30d2959fa9a01f37d8d76f3bcc08df4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineVerifier.cpp}::MachineVerifier::MachineVerifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * b, <a href="/web-llvm/docs/api/classes/llvm/livevariables">LiveVariables</a> * LiveVars, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LiveInts, <a href="/web-llvm/docs/api/classes/llvm/livestacks">LiveStacks</a> * LiveStks, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * OS, bool AbortOnError=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a851c87f496a7efe488499e0799b79a03">Banner</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#a1b3e2a496d3614dd93f99d43c2c5921f">LiveStks</a>, <a href="#a5be61c1a407ed680072a5bb87da9f0d3">LiveVars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ad4ae565ad87db4c534952e2c88f310">llvm::nulls</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a> and <a href="#a21c3b861c16bd22644b51e096b42155f">ReportedErrs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRegWithSubRegs() {#a587ee120f5b142b50860160b9e698d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineVerifier.cpp}::MachineVerifier::addRegWithSubRegs (<a href="#aefb0af3f20c655a05b85bf8bd0d17290">RegVector</a> &amp; RV, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>.</p>

</div>
</div>

### calcRegsPassed() {#a990694380bae24a3a5b09b9a12f2e333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::calcRegsPassed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-machineverifier-cpp-/filteringvregset/#ab6fe7bf6104a726f38b2e4e8ddd56f94">anonymous{MachineVerifier.cpp}::FilteringVRegSet::add</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineverifier-cpp-/filteringvregset/#a16c3feb6db6da66b21ef930c5c0b8be8">anonymous{MachineVerifier.cpp}::FilteringVRegSet::addToFilter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineverifier-cpp-/filteringvregset/#a4d09760d8a3d3fddeb70626ecf13981a">anonymous{MachineVerifier.cpp}::FilteringVRegSet::begin</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineverifier-cpp-/filteringvregset/#a677ad556efd74ab5cf5fbc31561db63b">anonymous{MachineVerifier.cpp}::FilteringVRegSet::end</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a558fbc6485736983a15c6b578a17451a">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::reachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a3edb7457d24a8d9c58df780276bea365">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::regsLiveOut</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineverifier-cpp-/filteringvregset/#a73059040c7a782968f6211ce82bbc778">anonymous{MachineVerifier.cpp}::FilteringVRegSet::size</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#afee0a2825321483d53174c8e8e84036d">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsPassed</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### calcRegsRequired() {#a97f881f7a367863cbd154c3adb1477f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::calcRegsRequired ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ae1eedfc9b0913658a7d008d918ffebcb">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a9a6c466b192e4e6ce4ac0f88a1ff408c">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsLiveIn</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ae78d3d82256fc3b1b7bcd4812c65c8f7">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsRequired</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### checkLiveness() {#aa2b8ab3df737c2492c7967447e7abac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::checkLiveness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, unsigned MONum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a587ee120f5b142b50860160b9e698d2c">addRegWithSubRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a>, <a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#abd6aa9da048ef7a4faeaac6484d5c9a6">llvm::MachineOperand::isEarlyClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="#a9ecab0dcc8cd296f6c8bb0988dcd25d4">isReserved</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#a5be61c1a407ed680072a5bb87da9f0d3">LiveVars</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25e1f327ac41c8df2bcf4215b100f516">llvm::none</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3be9857a09c82046b77a71918b5e214f">llvm::MachineOperand::readsReg</a>, <a href="#ac413e02c0425e60d0674041f9d641f4f">regsDead</a>, <a href="#af8c60a652432f5bb026313d7f70006a6">regsDefined</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ae244f4ada08e286ad4219e5c1059c4ed">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::regsKilled</a>, <a href="#ad7bce6a8ada69da1302518e0c38a91a5">regsKilled</a>, <a href="#a2b5a4081ce723184fea1277ebea4c5ac">regsLive</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a8c9627b7e8bbfa4fbd02f6644907147f">llvm::LiveQueryResult::valueOut</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a9a6c466b192e4e6ce4ac0f88a1ff408c">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsLiveIn</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### checkLivenessAtDef() {#a4d40a357c884c36942205713e7bf3244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::checkLivenessAtDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, unsigned MONum, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, bool SubRangeCheck=false, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=LaneBitmask::getNone())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a149e4cda329019551bbb27fe3159eca6">llvm::LiveQueryResult::isDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a5e861d6342e1d7e2bc9d2002d70a4567">llvm::SlotIndex::isRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0b73244049319d841fd11a238f35b5d1">llvm::SlotIndex::isSameInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a18e324aefc6383c44d175158f5954246">llvm::VirtRegOrUnit::isVirtualReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a>, <a href="#ab07287e0c57a0d4d5238eebb0cca0fcc">report_context_lanemask</a>, <a href="#a0cb948937bd8d69deb8fa5a8ffa491d0">report_context_liverange</a>, <a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a84d7fba74d57269f494283490fd93439">llvm::LiveRange::verify</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a> and <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>.</p>

</div>
</div>

### checkLivenessAtUse() {#a185de6f70a894f044801931c4956150d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::checkLivenessAtUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, unsigned MONum, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> UseIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=LaneBitmask::getNone())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e64ef30db46c5331dc31759ebd8b9d">llvm::HasValue</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#af155aeaffc7607f4f27ab4cfcbb39a64">llvm::LiveQueryResult::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a>, <a href="#ab07287e0c57a0d4d5238eebb0cca0fcc">report_context_lanemask</a>, <a href="#a0cb948937bd8d69deb8fa5a8ffa491d0">report_context_liverange</a>, <a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a8c9627b7e8bbfa4fbd02f6644907147f">llvm::LiveQueryResult::valueOut</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a84d7fba74d57269f494283490fd93439">llvm::LiveRange::verify</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a> and <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>.</p>

</div>
</div>

### checkPHIOps() {#a1d5250336b7b5e6c5f3c8e88fb9a9041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::checkPHIOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">llvm::MachineOperand::isDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#abd6aa9da048ef7a4faeaac6484d5c9a6">llvm::MachineOperand::isEarlyClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad3008c73231cdb4922d197fe56525364">llvm::MachineOperand::isInternalRead</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ad7d3f4b6e00638ec19ba44c6efcfa6dd">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::isLiveOut</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afe1784e242ce66da6029b3a681896bd2">llvm::MachineOperand::isMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a558fbc6485736983a15c6b578a17451a">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::reachable</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### isAllocatable() {#ab83e2e7a6e2935a30ec4bd45be04ea33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::isAllocatable (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a13765a244d6e934af46ec0a627b59925">regsReserved</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>


<p>Referenced by <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### isReserved() {#a9ecab0dcc8cd296f6c8bb0988dcd25d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::isReserved (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Reference <a href="#a13765a244d6e934af46ec0a627b59925">regsReserved</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### markReachable() {#ac34a220d0655748b7ad5a1b5d2994dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::markReachable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#ac34a220d0655748b7ad5a1b5d2994dec">markReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a558fbc6485736983a15c6b578a17451a">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::reachable</a>.</p>


<p>Referenced by <a href="#ac34a220d0655748b7ad5a1b5d2994dec">markReachable</a>, <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>.</p>

</div>
</div>

### report() {#abbf23e33875e57bec10c9b670fc6338c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a851c87f496a7efe488499e0799b79a03">Banner</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a> and <a href="#a21c3b861c16bd22644b51e096b42155f">ReportedErrs</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a>, <a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a>, <a href="#a1d5250336b7b5e6c5f3c8e88fb9a9041">checkPHIOps</a>, <a href="#a6ac7e17898dfcf67d9b745d74926f1c8">report</a>, <a href="#a4330df68342a7c3972e7e6e6852c40b8">report</a>, <a href="#a2fd58763bac8cd7e011630ae06d14656">report</a>, <a href="#a8e9af968db2378a07e8ccc04d6e100b5">report</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a8ea75ebde801fdd2dac4b3a279de9eeb">verifyAllRegOpsScalar</a>, <a href="#a2ba6472d6c916233f98bf13155d959bf">verifyGIntrinsicConvergence</a>, <a href="#a65af2646bf1b0db3340b48e472c7194c">verifyGIntrinsicSideEffects</a>, <a href="#a97c94504ca3d3dcb826cd34ec463f98e">verifyInlineAsm</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a>, <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>, <a href="#a2a0b543b45553dd02d7c1801ea59a31f">verifyProperties</a>, <a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a>, <a href="#a026d7ee38d907cccbeb812b0747f957c">verifyStackProtector</a>, <a href="#a46d2e4271c38bdc43a3b072a050a1a0f">verifyVectorElementMatch</a>, <a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#a5e25e754febed9d86fa367556dde1cc5">visitMachineBundleBefore</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>, <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### report() {#a6ac7e17898dfcf67d9b745d74926f1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>

</div>
</div>

### report() {#a4330df68342a7c3972e7e6e6852c40b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>

</div>
</div>

### report() {#a2fd58763bac8cd7e011630ae06d14656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, unsigned MONum, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MOVRegType=<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>{})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aedeaf186a99c875b4196318a4083ff77">llvm::MachineOperand::print</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>

</div>
</div>

### report() {#a8e9af968db2378a07e8ccc04d6e100b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>

</div>
</div>

### report\_context() {#a163a05eda2dac62644268d58ced77f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Reference <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a>, <a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a> and <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>.</p>

</div>
</div>

### report\_context() {#a714204eaae44d1230babc303f282e1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="#ab07287e0c57a0d4d5238eebb0cca0fcc">report_context_lanemask</a>, <a href="#a0cb948937bd8d69deb8fa5a8ffa491d0">report_context_liverange</a> and <a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a>.</p>

</div>
</div>

### report\_context() {#a174d49c5fb27ac4cfb907989cf31ba96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LiveRange::Segment &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Reference <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>.</p>

</div>
</div>

### report\_context() {#ad02cdb6766947f5b6254789d07cfb88e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> &amp; VNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a> and <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>.</p>

</div>
</div>

### report\_context() {#aeb656c419a8873b3108189dda9eba4ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Reference <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>.</p>

</div>
</div>

### report\_context() {#a74c373ff308d311f21cd1f873d75fdbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineVerifier.cpp}::MachineVerifier::report_context (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a990694380bae24a3a5b09b9a12f2e333">calcRegsPassed</a>, <a href="#a97f881f7a367863cbd154c3adb1477f2">calcRegsRequired</a>, <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a>, <a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a>, <a href="#a1d5250336b7b5e6c5f3c8e88fb9a9041">checkPHIOps</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac34a220d0655748b7ad5a1b5d2994dec">markReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ab07287e0c57a0d4d5238eebb0cca0fcc">report_context_lanemask</a>, <a href="#a0cb948937bd8d69deb8fa5a8ffa491d0">report_context_liverange</a>, <a href="#ae38908b27849a89a7e45d4d235212be9">report_context_vreg</a>, <a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a>, <a href="#a97c94504ca3d3dcb826cd34ec463f98e">verifyInlineAsm</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#a0c8281afcc693674f4ff5c0d2198c770">verifyLiveRange</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a>, <a href="#a2a0b543b45553dd02d7c1801ea59a31f">verifyProperties</a>, <a href="#aaca3d76a730626f0c9a0b4c85080e857">verifySlotIndexes</a>, <a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a> and <a href="#a026d7ee38d907cccbeb812b0747f957c">verifyStackProtector</a>.</p>

</div>
</div>

### report\_context\_lanemask() {#ab07287e0c57a0d4d5238eebb0cca0fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context_lanemask (<a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a>.</p>


<p>Referenced by <a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a>, <a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a>, <a href="#a714204eaae44d1230babc303f282e1ef">report_context</a> and <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>.</p>

</div>
</div>

### report\_context\_liverange() {#a0cb948937bd8d69deb8fa5a8ffa491d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context_liverange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Reference <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>.</p>


<p>Referenced by <a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a>, <a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a>, <a href="#a714204eaae44d1230babc303f282e1ef">report_context</a> and <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>.</p>

</div>
</div>

### report\_context\_vreg() {#ae38908b27849a89a7e45d4d235212be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context_vreg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>, <a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### report\_context\_vreg\_regunit() {#ae36ab79a9b6cf7db6749f67cb0c2db04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::report_context_vreg_regunit (<a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a8c3eafc3717d96b9269e1de018e0f1fd">llvm::VirtRegOrUnit::asMCRegUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a9a3a1e74e92fbb2346d4cd0b396d85b9">llvm::VirtRegOrUnit::asVirtualReg</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a18e324aefc6383c44d175158f5954246">llvm::VirtRegOrUnit::isVirtualReg</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34302b557354b8a09796c30b9f7408ab">llvm::printRegUnit</a>, <a href="#ae38908b27849a89a7e45d4d235212be9">report_context_vreg</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>


<p>Referenced by <a href="#a4d40a357c884c36942205713e7bf3244">checkLivenessAtDef</a>, <a href="#a185de6f70a894f044801931c4956150d">checkLivenessAtUse</a>, <a href="#a714204eaae44d1230babc303f282e1ef">report_context</a> and <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>.</p>

</div>
</div>

### verify() {#a584173fafbf5c085fa334e4a236febed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineVerifier::verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if no problems were found.</p></dd>
</dl>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a8014afd87e04236365d1796e38bc15f5">llvm::MachineFunctionProperties::FailedISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="#acf4d1e7c8ef538cff52d1e67d21d597f">isFunctionRegBankSelected</a>, <a href="#a1ebf4892cb9961d63fe6691ae9296dd0">isFunctionSelected</a>, <a href="#a6daa5950d65d33692a36f3638417d741">isFunctionTracksDebugUserValues</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#a1b3e2a496d3614dd93f99d43c2c5921f">LiveStks</a>, <a href="#a5be61c1a407ed680072a5bb87da9f0d3">LiveVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#a7ce0d09b265d455289b94043ffb4dff7">MFAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="#aef38834758876f9b5ddb6cb0a4ba5e2a">PASS</a>, <a href="#abad137877cd7afd839b779d787a94d9a">RBI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a062927be2f9d18d9995e64b0779c3dcf">llvm::MachineFunctionProperties::RegBankSelected</a>, <a href="#a8154011099ded2eb5f1375a7564e96f9">regMasks</a>, <a href="#ac413e02c0425e60d0674041f9d641f4f">regsDead</a>, <a href="#af8c60a652432f5bb026313d7f70006a6">regsDefined</a>, <a href="#ad7bce6a8ada69da1302518e0c38a91a5">regsKilled</a>, <a href="#a2b5a4081ce723184fea1277ebea4c5ac">regsLive</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a21c3b861c16bd22644b51e096b42155f">ReportedErrs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a91b442d385b54e1418d81adc34871053">llvm::MachineFunctionProperties::Selected</a>, <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a>, <a href="#a9599bcccbe0a4a711aaa63ce373ae210">TM</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76b22d924565975a49b2283fa838e5f2">llvm::MachineFunctionProperties::TracksDebugUserValues</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>, <a href="#a2a0b543b45553dd02d7c1801ea59a31f">verifyProperties</a>, <a href="#aaca3d76a730626f0c9a0b4c85080e857">verifySlotIndexes</a>, <a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a>, <a href="#a5e25e754febed9d86fa367556dde1cc5">visitMachineBundleBefore</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>, <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifierlegacypass/#a11b302b39fa3845b19fad010fae1e7ea">anonymous{MachineVerifier.cpp}::MachineVerifierLegacyPass::runOnMachineFunction</a>.</p>

</div>
</div>

### verifyAllRegOpsScalar() {#a8ea75ebde801fdd2dac4b3a279de9eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineVerifier::verifyAllRegOpsScalar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that all of <span class="doxyComputerOutput">MI's</span> virtual register operands are scalars.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if all virtual register operands are scalar. False otherwise.</p></dd>
</dl>


<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>


<p>Referenced by <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### verifyGIntrinsicConvergence() {#a2ba6472d6c916233f98bf13155d959bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineVerifier::verifyGIntrinsicConvergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a89cda2218259523c41863fc1175d6907">llvm::Intrinsic::getAttributes</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> and <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a>.</p>


<p>Referenced by <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### verifyGIntrinsicSideEffects() {#a65af2646bf1b0db3340b48e472c7194c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineVerifier::verifyGIntrinsicSideEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a89cda2218259523c41863fc1175d6907">llvm::Intrinsic::getAttributes</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> and <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a>.</p>


<p>Referenced by <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### verifyInlineAsm() {#a97c94504ca3d3dcb826cd34ec463f98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyInlineAsm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afe1784e242ce66da6029b3a681896bd2">llvm::MachineOperand::isMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aaa71c733e5aa6113e60a3a806e01bb10">llvm::MachineBasicBlock::isPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ad8e4e0d44daebe8c07cf5d6d60a4fc30">llvm::InlineAsm::MIOp_FirstOperand</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a>.</p>

</div>
</div>

### verifyLiveInterval() {#a787f3f4287374d61c5f0657dd83acbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyLiveInterval (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a5c2526062a291ca7d78fe98bbf66edb7">llvm::LiveRange::covers</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ae72973e4a97d936d5d4805a89a3cc2ec">llvm::ConnectedVNInfoEqClasses::getEqClass</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9eb4aa155c41e60dff42f4e741a0dcf0">llvm::LiveRange::valnos</a> and <a href="#a0c8281afcc693674f4ff5c0d2198c770">verifyLiveRange</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>.</p>

</div>
</div>

### verifyLiveIntervals() {#a42f45acfa351a67ac2975773261005d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyLiveIntervals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a> and <a href="#a0c8281afcc693674f4ff5c0d2198c770">verifyLiveRange</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### verifyLiveRange() {#a0c8281afcc693674f4ff5c0d2198c770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyLiveRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=LaneBitmask::getNone())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9a5e7c523f12f9f164b786769de1ca47">llvm::LiveRange::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9eb4aa155c41e60dff42f4e741a0dcf0">llvm::LiveRange::valnos</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a> and <a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a> and <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>.</p>

</div>
</div>

### verifyLiveRangeSegment() {#abc440c9fad640641c26ddae8c08dce82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyLiveRangeSegment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LiveRange::const_iterator I, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a9a3a1e74e92fbb2346d4cd0b396d85b9">llvm::VirtRegOrUnit::asVirtualReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af4a07ae5c460ac08439a1a71d15e0166">llvm::LiveInterval::computeSubRangeUndefs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a11bad3e34d11ffb7b0412de6bbd294b3">llvm::SlotIndex::getDeadSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a93450063916ca1ab1f11bf3304a6ad03">llvm::LiveRange::getNumValNums</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac832da130f4d71a4533a69d98315fb19">llvm::SlotIndex::getPrevSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a060100d6b75129bdef5516fac8f89a55">llvm::LiveRange::getValNumInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a7e1ec6260b229b2f5913405b758bc146">llvm::LiveRange::getVNInfoBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0c74422518b3479395817926489e9eec">llvm::SlotIndex::isBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#af7b521cd03cfcb1115186e877d0e820d">llvm::SlotIndex::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a305ac7d0553ef0ce21d461f5eabfe71c">llvm::SlotIndex::isEarlyClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a13c4005ea769c09d88be76fa40744e7e">llvm::LiveRangeCalc::isJointlyDominated</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0b73244049319d841fd11a238f35b5d1">llvm::SlotIndex::isSameInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/mibundleoperanditeratorbase/#a74c921d2258b6ce681a00ff5603ea43b">llvm::MIBundleOperandIteratorBase&lt; ValueT &gt;::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a18e324aefc6383c44d175158f5954246">llvm::VirtRegOrUnit::isVirtualReg</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#addd80df79ba902914c7d8a52e3896b79">llvm::MachineBasicBlock::predecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a2e0aa187d296e1330d12a948094f601b">llvm::MachineFunctionProperties::TiedOpsRewritten</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a0c8281afcc693674f4ff5c0d2198c770">verifyLiveRange</a>.</p>

</div>
</div>

### verifyLiveRangeValue() {#a38cfbca05868eacdc315641e8ed182d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyLiveRangeValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit">VirtRegOrUnit</a> VRegOrUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a8c3eafc3717d96b9269e1de018e0f1fd">llvm::VirtRegOrUnit::asMCRegUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a9a3a1e74e92fbb2346d4cd0b396d85b9">llvm::VirtRegOrUnit::asVirtualReg</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a305ac7d0553ef0ce21d461f5eabfe71c">llvm::SlotIndex::isEarlyClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a5e861d6342e1d7e2bc9d2002d70a4567">llvm::SlotIndex::isRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/mibundleoperanditeratorbase/#a74c921d2258b6ce681a00ff5603ea43b">llvm::MIBundleOperandIteratorBase&lt; ValueT &gt;::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a18e324aefc6383c44d175158f5954246">llvm::VirtRegOrUnit::isVirtualReg</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a0c8281afcc693674f4ff5c0d2198c770">verifyLiveRange</a>.</p>

</div>
</div>

### verifyLiveVariables() {#a3f673ecaaa953b4589aa7d0f5f2320bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyLiveVariables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="#a5be61c1a407ed680072a5bb87da9f0d3">LiveVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ae78d3d82256fc3b1b7bcd4812c65c8f7">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsRequired</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### verifyPreISelGenericInstruction() {#abdca91902881772e4b8e135a14ff1223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyPreISelGenericInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">llvm::fcAllFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ac33fa4c8cfeb9287f51f95404a459de8">llvm::LLT::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ab240d0d30dfa9b392ef9d813f3f9e4be">llvm::ConstantInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a90b790ccb1af4ea5ccd69db4b8cd2d81">llvm::IntegerType::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a4f9d007abe180fd0a5d2ed7cbec50e58">llvm::ConstantInt::getIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a5ea985de61dfccc6e599ccf7a460c3a3">llvm::MachineMemOperand::getRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#ad5f891a5d9822c7aab1b8bb0190a522f">llvm::DstOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a622dee2e5d865699df4407bd0bdbf903">llvm::MachineOperand::getShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensaasmbackend-cpp/#a13a0babfc55adc9b798c39e65ec9e8a3">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a3536ced38fb9e6404151cfa03b4531dc">llvm::APFloatBase::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abcceb535a4bb1e23c320e7628476bd5d">llvm::MachineMemOperand::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa45abfa63d76025a0e5b9a46e25dd8d">llvm::MachineMemOperand::getSuccessOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a1ebf4892cb9961d63fe6691ae9296dd0">isFunctionSelected</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a44f92ba840149cc7f75e38279341257a">llvm::MachineOperand::isIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGE</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd23ed05c97e269d0d268636c7d6a6b7">llvm::LLT::isPointerOrPointerVector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a55ca901a46a6561125ef38f6c33c2700">llvm::LLT::isPointerVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a8028200b9efbd55fe7db4c69199893d2">llvm::LLT::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3016e0f01ad96a198f81f74397b1c0e6">llvm::LLT::isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a81521682ef12b5e4f681502f9346a4ad">llvm::MachineOperand::isShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#aab5329eaa9a958adfa2c8de4d24e16cc">isStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="#abad137877cd7afd839b779d787a94d9a">RBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea0cbc6611f5540bd0809a388dc95a615b">llvm::Test</a>, <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>, <a href="#a8ea75ebde801fdd2dac4b3a279de9eeb">verifyAllRegOpsScalar</a>, <a href="#a2ba6472d6c916233f98bf13155d959bf">verifyGIntrinsicConvergence</a>, <a href="#a65af2646bf1b0db3340b48e472c7194c">verifyGIntrinsicSideEffects</a> and <a href="#a46d2e4271c38bdc43a3b072a050a1a0f">verifyVectorElementMatch</a>.</p>


<p>Referenced by <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a>.</p>

</div>
</div>

### verifyProperties() {#a2a0b543b45553dd02d7c1801ea59a31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyProperties (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### verifySlotIndexes() {#aaca3d76a730626f0c9a0b4c85080e857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifySlotIndexes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### verifyStackFrame() {#a63ebe76813ff76375cf5705af12bdcd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyStackFrame ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make sure on every path through the CFG, a FrameSetup &lt;n&gt; is always followed by a FrameDestroy &lt;n&gt;, stack adjustments are identical on all CFG edges to a merge point, and frame is destroyed at end of a return block.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ca9174266d6241bed1ff75961249393">llvm::df_ext_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12f5ac004bb20214c37ec85406cea83">llvm::df_ext_end</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/stackstateofbb/#a115542f71b91cdb9b117448f68b0823f">anonymous{MachineVerifier.cpp}::StackStateOfBB::EntryIsSetup</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/stackstateofbb/#a3a7052efc37205ac23b46f86eb6fd564">anonymous{MachineVerifier.cpp}::StackStateOfBB::EntryValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/stackstateofbb/#a350fc0290a2b88053dad27de365e138f">anonymous{MachineVerifier.cpp}::StackStateOfBB::ExitIsSetup</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/stackstateofbb/#adf615e1d10345c0e4a6d692ed4406f00">anonymous{MachineVerifier.cpp}::StackStateOfBB::ExitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>.</p>

</div>
</div>

### verifyStackProtector() {#a026d7ee38d907cccbeb812b0747f957c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::verifyStackProtector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check that the stack protector is the top-most object in the stack.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac51e2d34abb79b72afef355fac525c76">llvm::MachineFrameInfo::getObjectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#aa76eab97e3072a1ebd4bf1ff00d19423">llvm::TargetFrameLowering::getStackGrowthDirection</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5ee88eb786413b2cf541122aa749392c">llvm::MachineFrameInfo::getStackProtectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac7c993678733273ea9d16db7ff87b2c6">llvm::MachineFrameInfo::hasStackProtectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af5302d38d9a16eee93f13a1579c8773d">llvm::MachineFrameInfo::isDeadObjectIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a91b0115deec3489d7e082a4a13f022ff">llvm::MachineFrameInfo::isSpillSlotObjectIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab86af583f3ac779bb3f74071d36b5923">llvm::MachineFrameInfo::isVariableSizedObjectIndex</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a>.</p>


<p>Referenced by <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a> and <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>.</p>

</div>
</div>

### verifyVectorElementMatch() {#a46d2e4271c38bdc43a3b072a050a1a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineVerifier::verifyVectorElementMatch (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty0, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check that types are consistent when two operands need to have the same number of vector elements.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the types are valid.</p></dd>
</dl>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>


<p>Referenced by <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### visitMachineBasicBlockAfter() {#a36ffe3ff182fd7ba55acab429ea1cf7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineBasicBlockAfter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="#ab1d616b586fe73a891822b60cf2812dd">lastIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="#a2b5a4081ce723184fea1277ebea4c5ac">regsLive</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### visitMachineBasicBlockBefore() {#afa06aa56938cd078f6e40733f5406dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineBasicBlockBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ade9b7298af9712b0dbe14fad12e44793">FirstNonPHI</a>, <a href="#a5206b5d1e2b30c3fa57ccc093f70b518">FirstTerminator</a>, <a href="#af4237d028145173f9212a57223b91def">FunctionBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af2741cb32381997a1e0f074f63d977ae">llvm::MCAsmInfo::getExceptionHandlingType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa42c3828ac3f788f2ef3ff6fa46e4926">llvm::MachineFrameInfo::getPristineRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ab83e2e7a6e2935a30ec4bd45be04ea33">isAllocatable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5309dbf19ec5ccffe3072c6087e106d3">llvm::isScopedEHPersonality</a>, <a href="#ab1d616b586fe73a891822b60cf2812dd">lastIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c">llvm::MachineFunctionProperties::NoPHIs</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#af8c60a652432f5bb026313d7f70006a6">regsDefined</a>, <a href="#ad7bce6a8ada69da1302518e0c38a91a5">regsKilled</a>, <a href="#a2b5a4081ce723184fea1277ebea4c5ac">regsLive</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa56c07cdb4f03ddef7dfdf460811d36e">llvm::BitVector::set_bits</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a0f60fd9b862dff366e18e32c6d98d96b">llvm::SjLj</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>, <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a>, <a href="#a9599bcccbe0a4a711aaa63ce373ae210">TM</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### visitMachineBundleAfter() {#a91a98a9dff1a64d1c6ba9a9dc801cf72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineBundleAfter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8154011099ded2eb5f1375a7564e96f9">regMasks</a>, <a href="#ac413e02c0425e60d0674041f9d641f4f">regsDead</a>, <a href="#af8c60a652432f5bb026313d7f70006a6">regsDefined</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ae244f4ada08e286ad4219e5c1059c4ed">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::regsKilled</a>, <a href="#ad7bce6a8ada69da1302518e0c38a91a5">regsKilled</a>, <a href="#a2b5a4081ce723184fea1277ebea4c5ac">regsLive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e1137200d6e86367be1d605fdc14e6c">llvm::set_subtract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8b4f88b1fadc8f51a643e5faaa13afa6">llvm::set_union</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### visitMachineBundleBefore() {#a5e25e754febed9d86fa367556dde1cc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineBundleBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a5206b5d1e2b30c3fa57ccc093f70b518">FirstTerminator</a>, <a href="#a327c370e45b2c31ea1c3ecf3a40d2eac">Indexes</a>, <a href="#ab1d616b586fe73a891822b60cf2812dd">lastIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### visitMachineFunctionAfter() {#ad19536429e02ee5405f51a51bbb256cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineFunctionAfter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a990694380bae24a3a5b09b9a12f2e333">calcRegsPassed</a>, <a href="#a97f881f7a367863cbd154c3adb1477f2">calcRegsRequired</a>, <a href="#a1d5250336b7b5e6c5f3c8e88fb9a9041">checkPHIOps</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="#ae5056903a77a7aa46d4d1529db53f7fe">DT</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#ab83e2e7a6e2935a30ec4bd45be04ea33">isAllocatable</a>, <a href="#a9ecab0dcc8cd296f6c8bb0988dcd25d4">isReserved</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#a5be61c1a407ed680072a5bb87da9f0d3">LiveVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ae244f4ada08e286ad4219e5c1059c4ed">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::regsKilled</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a3edb7457d24a8d9c58df780276bea365">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::regsLiveOut</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#ae38908b27849a89a7e45d4d235212be9">report_context_vreg</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp/#a13500e0b51ad6dd146c75e65f00d7f4b">verifyConvergenceControl</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#ae78d3d82256fc3b1b7bcd4812c65c8f7">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsRequired</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### visitMachineFunctionBefore() {#a3cc52e45540d8251a2f942f68ea47fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineFunctionBefore ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#af4237d028145173f9212a57223b91def">FunctionBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#ab1d616b586fe73a891822b60cf2812dd">lastIndex</a>, <a href="#ac34a220d0655748b7ad5a1b5d2994dec">markReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aaade7258f8691e12938b62f86ed739cf">MBBInfoMap</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#aaa438e2355f9535e204713d84fa40c25">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::Preds</a>, <a href="#a13765a244d6e934af46ec0a627b59925">regsReserved</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo/#a355df476c99ea83d0b29880448ba7aff">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::Succs</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>, <a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a> and <a href="#a026d7ee38d907cccbeb812b0747f957c">verifyStackProtector</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### visitMachineInstrBefore() {#a9434209a25739262432f55e8fe33ccc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineInstrBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="#ade9b7298af9712b0dbe14fad12e44793">FirstNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a561d1afc8f2935939a4a113510bd7c96">llvm::StatepointOpers::getCCIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a85ea607a43ea9b3eb84ed72058693d4a">llvm::StatepointOpers::getFirstGCPtrIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#ae7d95624b4914f95a0a9c37c3c51007d">llvm::StatepointOpers::getFlagsIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a289e1a5ef6161b0fadbbf111e2202b63">llvm::StatepointOpers::getIDPos</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#abd9e6bbd445b4fa79a9cc1495c522a51">llvm::StatepointOpers::getNBytesPos</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a6eac7e12c3d75912cbabca5d885486d5">llvm::StatepointOpers::getNCallArgsPos</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a72f688fbc467b422cbaa2863879853b0">llvm::StatepointOpers::getNumAllocaIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a9ccc324192981f7ce3091453bb0b68a5">llvm::StatepointOpers::getNumDeoptArgsIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a74489068197c4dc2f59abb1ee9da80e2">llvm::StatepointOpers::getNumGcMapEntriesIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#afec1cbe3c73e6d6b86e5d6b00815dc2e">llvm::StatepointOpers::getNumGCPtrIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#ad5f891a5d9822c7aab1b8bb0190a522f">llvm::DstOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a5cafb166cf7c4937f5647a084c4eaee2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isNonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cdb63ce3baf9ea9a1f86aed27f40fe8">llvm::isPreISelGenericOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51226361b4778741a8b60487c293d43a">llvm::isPreISelGenericOptimizationHint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a09808ae32b91764194984d6892e40a2e">llvm::MachineInstr::NoConvergent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c">llvm::MachineFunctionProperties::NoPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a>, <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>, <a href="#a97c94504ca3d3dcb826cd34ec463f98e">verifyInlineAsm</a> and <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### visitMachineOperand() {#a16957e467c8bf1aa4c3c8614d7315709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineVerifier::visitMachineOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, unsigned MONum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a88c30c92aa9995b0cc70bfe60294ff65">llvm::MachineOperand::getCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#aaff74ccaefe7ac1cf0c4c7eb88c85d28">llvm::RegisterBank::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae6876d59aeec5bc210b359fbdcf6c1ad">llvm::MachineOperand::getRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#abee1c3236731101b249f6eeffd8cd7ba">llvm::TargetRegisterClass::hasSuperClassEq</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">llvm::MachineOperand::isDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="#acf4d1e7c8ef538cff52d1e67d21d597f">isFunctionRegBankSelected</a>, <a href="#a1ebf4892cb9961d63fe6691ae9296dd0">isFunctionSelected</a>, <a href="#a6daa5950d65d33692a36f3638417d741">isFunctionTracksDebugUserValues</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cdb63ce3baf9ea9a1f86aed27f40fe8">llvm::isPreISelGenericOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8be49bc86b5d01b52b90baf1b4477667">llvm::MachineOperand::isRenamable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a79d3c4a8df3c60d4d97cc39c300d69c0">llvm::MachineOperand::isValidExcessOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a400c0b88110521ad1de258a7885d9038">llvm::LiveRange::liveAt</a>, <a href="#a7ee3ec9796622852744a9c48a7e62c6f">LiveInts</a>, <a href="#a1b3e2a496d3614dd93f99d43c2c5921f">LiveStks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a5414f76815c8f01cd360c99ff6fb27a7">loads</a>, <a href="#afeb2e7a3544799ca8e0711ec641a1411">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0270d8f468e7b92dafb486293ecf137d">llvm::MachineOperand::MO_CFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">llvm::MachineOperand::MO_FrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">llvm::MachineOperand::MO_RegisterMask</a>, <a href="#ae77bbaad58d319a46439d74e7d973261">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da767514e15ea244ad3e683ae79b583534">llvm::MCOI::OPERAND_IMMEDIATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da4ab8ff4de9da34b9b60f04a21860aec1">llvm::MCOI::OPERAND_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da62a6ddcdddcce55f836b1720d29f90dc">llvm::MCOI::OPERAND_REGISTER</a>, <a href="#a0bd1931caadb4b988521640e0d8d42f0">OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="#abad137877cd7afd839b779d787a94d9a">RBI</a>, <a href="#a8154011099ded2eb5f1375a7564e96f9">regMasks</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a7d2c711a42f51c1f7b3ce3f8f560fa74">stores</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a2e0aa187d296e1330d12a948094f601b">llvm::MachineFunctionProperties::TiedOpsRewritten</a>, <a href="#a9825e35170da96bcf974d23aeaaf5055">TII</a> and <a href="#a7b6ca8744d6019dd22ad353712c33523">TRI</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Banner {#a851c87f496a7efe488499e0799b79a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* anonymous{MachineVerifier.cpp}::MachineVerifier::Banner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a>, <a href="#a19171d1cdf2a6314188f142bbf9b99e9">MachineVerifier</a>, <a href="#a425a5bc2fd119f68ba7d600520241926">MachineVerifier</a> and <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>.</p>

</div>
</div>

### DT {#ae5056903a77a7aa46d4d1529db53f7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree anonymous{MachineVerifier.cpp}::MachineVerifier::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### FirstNonPHI {#ade9b7298af9712b0dbe14fad12e44793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* anonymous{MachineVerifier.cpp}::MachineVerifier::FirstNonPHI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a>.</p>

</div>
</div>

### FirstTerminator {#a5206b5d1e2b30c3fa57ccc093f70b518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* anonymous{MachineVerifier.cpp}::MachineVerifier::FirstTerminator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#a5e25e754febed9d86fa367556dde1cc5">visitMachineBundleBefore</a>.</p>

</div>
</div>

### FunctionBlocks {#af4237d028145173f9212a57223b91def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockSet anonymous{MachineVerifier.cpp}::MachineVerifier::FunctionBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>.</p>

</div>
</div>

### Indexes {#a327c370e45b2c31ea1c3ecf3a40d2eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* anonymous{MachineVerifier.cpp}::MachineVerifier::Indexes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a>, <a href="#a6ac7e17898dfcf67d9b745d74926f1c8">report</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a4330df68342a7c3972e7e6e6852c40b8">report</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#aaca3d76a730626f0c9a0b4c85080e857">verifySlotIndexes</a>, <a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#a5e25e754febed9d86fa367556dde1cc5">visitMachineBundleBefore</a>.</p>

</div>
</div>

### isFunctionRegBankSelected {#acf4d1e7c8ef538cff52d1e67d21d597f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::isFunctionRegBankSelected = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### isFunctionSelected {#a1ebf4892cb9961d63fe6691ae9296dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::isFunctionSelected = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### isFunctionTracksDebugUserValues {#a6daa5950d65d33692a36f3638417d741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::isFunctionTracksDebugUserValues = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### lastIndex {#ab1d616b586fe73a891822b60cf2812dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex anonymous{MachineVerifier.cpp}::MachineVerifier::lastIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#a5e25e754febed9d86fa367556dde1cc5">visitMachineBundleBefore</a> and <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>.</p>

</div>
</div>

### LiveInts {#a7ee3ec9796622852744a9c48a7e62c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* anonymous{MachineVerifier.cpp}::MachineVerifier::LiveInts = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### LiveStks {#a1b3e2a496d3614dd93f99d43c2c5921f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveStacks* anonymous{MachineVerifier.cpp}::MachineVerifier::LiveStks = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### LiveVars {#a5be61c1a407ed680072a5bb87da9f0d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveVariables* anonymous{MachineVerifier.cpp}::MachineVerifier::LiveVars = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a> and <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>.</p>

</div>
</div>

### MBBInfoMap {#aaade7258f8691e12938b62f86ed739cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, BBInfo&gt; anonymous{MachineVerifier.cpp}::MachineVerifier::MBBInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a990694380bae24a3a5b09b9a12f2e333">calcRegsPassed</a>, <a href="#a97f881f7a367863cbd154c3adb1477f2">calcRegsRequired</a>, <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a1d5250336b7b5e6c5f3c8e88fb9a9041">checkPHIOps</a>, <a href="#ac34a220d0655748b7ad5a1b5d2994dec">markReachable</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a>, <a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a> and <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>.</p>

</div>
</div>

### MF {#afeb2e7a3544799ca8e0711ec641a1411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction* anonymous{MachineVerifier.cpp}::MachineVerifier::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a990694380bae24a3a5b09b9a12f2e333">calcRegsPassed</a>, <a href="#a97f881f7a367863cbd154c3adb1477f2">calcRegsRequired</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a74c373ff308d311f21cd1f873d75fdbe">report_context</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a2ba6472d6c916233f98bf13155d959bf">verifyGIntrinsicConvergence</a>, <a href="#a65af2646bf1b0db3340b48e472c7194c">verifyGIntrinsicSideEffects</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a>, <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>, <a href="#a2a0b543b45553dd02d7c1801ea59a31f">verifyProperties</a>, <a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a>, <a href="#a026d7ee38d907cccbeb812b0747f957c">verifyStackProtector</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>, <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### MFAM {#a7ce0d09b265d455289b94043ffb4dff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionAnalysisManager* anonymous{MachineVerifier.cpp}::MachineVerifier::MFAM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a19171d1cdf2a6314188f142bbf9b99e9">MachineVerifier</a> and <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### MRI {#ae77bbaad58d319a46439d74e7d973261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* anonymous{MachineVerifier.cpp}::MachineVerifier::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a8ea75ebde801fdd2dac4b3a279de9eeb">verifyAllRegOpsScalar</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a>, <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>, <a href="#a2a0b543b45553dd02d7c1801ea59a31f">verifyProperties</a>, <a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>, <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### OS {#a0bd1931caadb4b988521640e0d8d42f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; anonymous{MachineVerifier.cpp}::MachineVerifier::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a1d5250336b7b5e6c5f3c8e88fb9a9041">checkPHIOps</a>, <a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a>, <a href="#a19171d1cdf2a6314188f142bbf9b99e9">MachineVerifier</a>, <a href="#a425a5bc2fd119f68ba7d600520241926">MachineVerifier</a>, <a href="#a6ac7e17898dfcf67d9b745d74926f1c8">report</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a>, <a href="#a4330df68342a7c3972e7e6e6852c40b8">report</a>, <a href="#a2fd58763bac8cd7e011630ae06d14656">report</a>, <a href="#a163a05eda2dac62644268d58ced77f2b">report_context</a>, <a href="#a174d49c5fb27ac4cfb907989cf31ba96">report_context</a>, <a href="#ad02cdb6766947f5b6254789d07cfb88e">report_context</a>, <a href="#aeb656c419a8873b3108189dda9eba4ca">report_context</a>, <a href="#ab07287e0c57a0d4d5238eebb0cca0fcc">report_context_lanemask</a>, <a href="#a0cb948937bd8d69deb8fa5a8ffa491d0">report_context_liverange</a>, <a href="#ae38908b27849a89a7e45d4d235212be9">report_context_vreg</a>, <a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a787f3f4287374d61c5f0657dd83acbb4">verifyLiveInterval</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a3f673ecaaa953b4589aa7d0f5f2320bb">verifyLiveVariables</a>, <a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a>, <a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#a5e25e754febed9d86fa367556dde1cc5">visitMachineBundleBefore</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### PASS {#aef38834758876f9b5ddb6cb0a4ba5e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass* const anonymous{MachineVerifier.cpp}::MachineVerifier::PASS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a425a5bc2fd119f68ba7d600520241926">MachineVerifier</a> and <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### RBI {#abad137877cd7afd839b779d787a94d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo* anonymous{MachineVerifier.cpp}::MachineVerifier::RBI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### regMasks {#a8154011099ded2eb5f1375a7564e96f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegMaskVector anonymous{MachineVerifier.cpp}::MachineVerifier::regMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### regsDead {#ac413e02c0425e60d0674041f9d641f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegVector anonymous{MachineVerifier.cpp}::MachineVerifier::regsDead</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a> and <a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a>.</p>

</div>
</div>

### regsDefined {#af8c60a652432f5bb026313d7f70006a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegVector anonymous{MachineVerifier.cpp}::MachineVerifier::regsDefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a>.</p>

</div>
</div>

### regsKilled {#ad7bce6a8ada69da1302518e0c38a91a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegVector anonymous{MachineVerifier.cpp}::MachineVerifier::regsKilled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a>.</p>

</div>
</div>

### regsLive {#a2b5a4081ce723184fea1277ebea4c5ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegSet anonymous{MachineVerifier.cpp}::MachineVerifier::regsLive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a36ffe3ff182fd7ba55acab429ea1cf7b">visitMachineBasicBlockAfter</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a> and <a href="#a91a98a9dff1a64d1c6ba9a9dc801cf72">visitMachineBundleAfter</a>.</p>

</div>
</div>

### regsReserved {#a13765a244d6e934af46ec0a627b59925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{MachineVerifier.cpp}::MachineVerifier::regsReserved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#ab83e2e7a6e2935a30ec4bd45be04ea33">isAllocatable</a>, <a href="#a9ecab0dcc8cd296f6c8bb0988dcd25d4">isReserved</a> and <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>.</p>

</div>
</div>

### ReportedErrs {#a21c3b861c16bd22644b51e096b42155f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReportedErrors anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a30d2959fa9a01f37d8d76f3bcc08df4a">MachineVerifier</a>, <a href="#a19171d1cdf2a6314188f142bbf9b99e9">MachineVerifier</a>, <a href="#a425a5bc2fd119f68ba7d600520241926">MachineVerifier</a>, <a href="#abbf23e33875e57bec10c9b670fc6338c">report</a> and <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>.</p>

</div>
</div>

### TII {#a9825e35170da96bcf974d23aeaaf5055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{MachineVerifier.cpp}::MachineVerifier::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a2ba6472d6c916233f98bf13155d959bf">verifyGIntrinsicConvergence</a>, <a href="#a65af2646bf1b0db3340b48e472c7194c">verifyGIntrinsicSideEffects</a>, <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>, <a href="#a63ebe76813ff76375cf5705af12bdcd6">verifyStackFrame</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

### TM {#a9599bcccbe0a4a711aaa63ce373ae210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* anonymous{MachineVerifier.cpp}::MachineVerifier::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a584173fafbf5c085fa334e4a236febed">verify</a> and <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>.</p>

</div>
</div>

### TRI {#a7b6ca8744d6019dd22ad353712c33523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{MachineVerifier.cpp}::MachineVerifier::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a587ee120f5b142b50860160b9e698d2c">addRegWithSubRegs</a>, <a href="#aa2b8ab3df737c2492c7967447e7abac9">checkLiveness</a>, <a href="#ab83e2e7a6e2935a30ec4bd45be04ea33">isAllocatable</a>, <a href="#a2fd58763bac8cd7e011630ae06d14656">report</a>, <a href="#ae38908b27849a89a7e45d4d235212be9">report_context_vreg</a>, <a href="#ae36ab79a9b6cf7db6749f67cb0c2db04">report_context_vreg_regunit</a>, <a href="#a584173fafbf5c085fa334e4a236febed">verify</a>, <a href="#a42f45acfa351a67ac2975773261005d7">verifyLiveIntervals</a>, <a href="#abc440c9fad640641c26ddae8c08dce82">verifyLiveRangeSegment</a>, <a href="#a38cfbca05868eacdc315641e8ed182d4">verifyLiveRangeValue</a>, <a href="#abdca91902881772e4b8e135a14ff1223">verifyPreISelGenericInstruction</a>, <a href="#afa06aa56938cd078f6e40733f5406dab">visitMachineBasicBlockBefore</a>, <a href="#ad19536429e02ee5405f51a51bbb256cd">visitMachineFunctionAfter</a>, <a href="#a3cc52e45540d8251a2f942f68ea47fa3">visitMachineFunctionBefore</a>, <a href="#a9434209a25739262432f55e8fe33ccc7">visitMachineInstrBefore</a> and <a href="#a16957e467c8bf1aa4c3c8614d7315709">visitMachineOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
