---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/philoweringhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PhiLoweringHelper` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PhiLoweringHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">Target/AMDGPU/SILowerI1Copies.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper">DivergenceLoweringHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper">Vreg1LoweringHelper</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a> (MachineFunction *MF, MachineDominatorTree *DT, MachinePostDominatorTree *PDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e0144122edbca94d040f2885be68eb1">~PhiLoweringHelper</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b1d4a4b487362c26550bdbab4ea36a">isConstantLaneMask</a> (Register Reg, bool &amp;Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72bd12fda2631c827d985132e090883">getSaluInsertionAtEnd</a> (MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a point at the end of the given <span class="doxyComputerOutput">MBB</span> to insert SALU instructions for lane mask calculation. <a href="#ad72bd12fda2631c827d985132e090883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0c3d95c2434973b3b5795aecadf243">initializeLaneMaskRegisterAttributes</a> (Register LaneMask)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9e1c74c0536fbade814091fd3c8ee3">isLaneMaskReg</a> (Register Reg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08cf4a0f128ee9edaa571de8aeff7f5">markAsLaneMask</a> (Register DstReg) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e33d733fd295b7e8f40320cd8a9bbe2">getCandidatesForLowering</a> (SmallVectorImpl&lt; MachineInstr * &gt; &amp;Vreg1Phis) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977e7d4ce353a9c3e9284feef1598824">collectIncomingValuesFromPhi</a> (const MachineInstr *MI, SmallVectorImpl&lt; Incoming &gt; &amp;Incomings) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af052e96e38471b6180b7f53c045ab933">replaceDstReg</a> (Register NewReg, Register OldReg, MachineBasicBlock *MBB)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec4519e75acc0a0ec9b9e6d014e77be">buildMergeLaneMasks</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register DstReg, Register PrevReg, Register CurReg)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a824eba86a6110e7b7d0ba389356aed9b">constrainAsLaneMask</a> (Incoming &amp;In)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec177d403afa0864501ca04f08ec425">IsWave32</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b1d6c9ae89f83c6918aaee904070c3">MF</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c654bc63075ea6446978668af9b23c7">DT</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60a09fb7712789a3e5e58806b4aa10d">PDT</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587ec89e73d2290668b58a5e7f771f35">MRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaada4db8807fee28bb4785a3ab1f9df1">ST</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab37b9650dd3ff2294ac2556672c52eb3">TII</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">MachineRegisterInfo::VRegAttrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acefa582f93360081f06fe71aef54da34">LaneMaskRegAttrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb5b9ea9fecf728e509eb1d1c749e36">PhiRegisters</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28c61f3424d42ec86dca0bce1b10266">ExecReg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1c001f50d207502739b89a74ee5747">MovOp</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f5a15970e967ccbd3fe821e6d843fdb">AndOp</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579b1d38ea323d182d66c8db95263877">OrOp</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d640108a701d456f16d8b3ea85a7aa1">XorOp</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af740485c69305e62a9c4f68369437174">AndN2Op</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e02e6fd3b0984f62948db4061d4ca44">OrN2Op</a></td>
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


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PhiLoweringHelper() {#a2a55e57cd0a8346f83e5e2ebe32beb65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PhiLoweringHelper::PhiLoweringHelper (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> * PDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="#af740485c69305e62a9c4f68369437174">AndN2Op</a>, <a href="#a4f5a15970e967ccbd3fe821e6d843fdb">AndOp</a>, <a href="#a5c654bc63075ea6446978668af9b23c7">DT</a>, <a href="#ab28c61f3424d42ec86dca0bce1b10266">ExecReg</a>, <a href="#a9ec177d403afa0864501ca04f08ec425">IsWave32</a>, <a href="#a80b1d6c9ae89f83c6918aaee904070c3">MF</a>, <a href="#a2e1c001f50d207502739b89a74ee5747">MovOp</a>, <a href="#a587ec89e73d2290668b58a5e7f771f35">MRI</a>, <a href="#a1e02e6fd3b0984f62948db4061d4ca44">OrN2Op</a>, <a href="#a579b1d38ea323d182d66c8db95263877">OrOp</a>, <a href="#aa60a09fb7712789a3e5e58806b4aa10d">PDT</a>, <a href="#aaada4db8807fee28bb4785a3ab1f9df1">ST</a>, <a href="#ab37b9650dd3ff2294ac2556672c52eb3">TII</a> and <a href="#a4d640108a701d456f16d8b3ea85a7aa1">XorOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a2423554b7e9d6146ea4a617838f10505">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::DivergenceLoweringHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a22a13176b4055ad945163e17b880be43">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::Vreg1LoweringHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PhiLoweringHelper() {#a4e0144122edbca94d040f2885be68eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::PhiLoweringHelper::~PhiLoweringHelper ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildMergeLaneMasks() {#aeec4519e75acc0a0ec9b9e6d014e77be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PhiLoweringHelper::buildMergeLaneMasks (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PrevReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> CurReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### collectIncomingValuesFromPhi() {#a977e7d4ce353a9c3e9284feef1598824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PhiLoweringHelper::collectIncomingValuesFromPhi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> &gt; &amp; Incomings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### constrainAsLaneMask() {#a824eba86a6110e7b7d0ba389356aed9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PhiLoweringHelper::constrainAsLaneMask (<a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> &amp; In)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### getCandidatesForLowering() {#a5e33d733fd295b7e8f40320cd8a9bbe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PhiLoweringHelper::getCandidatesForLowering (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; Vreg1Phis)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### getSaluInsertionAtEnd() {#ad72bd12fda2631c827d985132e090883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator PhiLoweringHelper::getSaluInsertionAtEnd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a point at the end of the given <span class="doxyComputerOutput">MBB</span> to insert SALU instructions for lane mask calculation.</p>


<p>Take terminators and SCC into account.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>, definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a097c72f44ae13674fb0e7f71c997c7b5">instrDefsUsesSCC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### initializeLaneMaskRegisterAttributes() {#add0c3d95c2434973b3b5795aecadf243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PhiLoweringHelper::initializeLaneMaskRegisterAttributes (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> LaneMask)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>References <a href="#acefa582f93360081f06fe71aef54da34">LaneMaskRegAttrs</a> and <a href="#a587ec89e73d2290668b58a5e7f771f35">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a> and <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### isConstantLaneMask() {#ae3b1d4a4b487362c26550bdbab4ea36a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PhiLoweringHelper::isConstantLaneMask (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>, definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="#a4b9e1c74c0536fbade814091fd3c8ee3">isLaneMaskReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a2e1c001f50d207502739b89a74ee5747">MovOp</a> and <a href="#a587ec89e73d2290668b58a5e7f771f35">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a>.</p>

</div>
</div>

### isLaneMaskReg() {#a4b9e1c74c0536fbade814091fd3c8ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PhiLoweringHelper::isLaneMaskReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>References <a href="#a587ec89e73d2290668b58a5e7f771f35">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#aaada4db8807fee28bb4785a3ab1f9df1">ST</a> and <a href="#ab37b9650dd3ff2294ac2556672c52eb3">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="#ae3b1d4a4b487362c26550bdbab4ea36a">isConstantLaneMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a6cf0eec5c3acd7ff97e6e5dec15a97d6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesFromI1</a> and <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>.</p>

</div>
</div>

### lowerPhis() {#a0321e28cc3da73c666a6f5e58a541de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PhiLoweringHelper::lowerPhis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>, definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#af0d1a82b4e629e834c2ed53e5cbe22ef">llvm::SSAUpdater::AddAvailableValue</a>, <a href="/web-llvm/docs/api/structs/llvm/incoming/#abff0731632db5e52bc5ea3fdba5dbd8d">llvm::Incoming::Block</a>, <a href="#aeec4519e75acc0a0ec9b9e6d014e77be">buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a977e7d4ce353a9c3e9284feef1598824">collectIncomingValuesFromPhi</a>, <a href="#a824eba86a6110e7b7d0ba389356aed9b">constrainAsLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b43ba7ddb7fcd4dab5bf28c829a423">llvm::createLaneMaskReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5c654bc63075ea6446978668af9b23c7">DT</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a5e33d733fd295b7e8f40320cd8a9bbe2">getCandidatesForLowering</a>, <a href="#ad72bd12fda2631c827d985132e090883">getSaluInsertionAtEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a4fe3279aae4f726813a672d4a9b26cb1">llvm::SSAUpdater::Initialize</a>, <a href="#add0c3d95c2434973b3b5795aecadf243">initializeLaneMaskRegisterAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a1a1f1395998a21569f5baea74c7018b0">insertUndefLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="#acefa582f93360081f06fe71aef54da34">LaneMaskRegAttrs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa08cf4a0f128ee9edaa571de8aeff7f5">markAsLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a80b1d6c9ae89f83c6918aaee904070c3">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a587ec89e73d2290668b58a5e7f771f35">MRI</a>, <a href="#aa60a09fb7712789a3e5e58806b4aa10d">PDT</a>, <a href="#a5cb5b9ea9fecf728e509eb1d1c749e36">PhiRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/incoming/#add0311bdcdd42cf92009abbc6c209df6">llvm::Incoming::Reg</a>, <a href="#af052e96e38471b6180b7f53c045ab933">replaceDstReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="#ab37b9650dd3ff2294ac2556672c52eb3">TII</a> and <a href="/web-llvm/docs/api/structs/llvm/incoming/#adf98eddaedb122096fd002bc09fc9b76">llvm::Incoming::UpdatedReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/amdgpuglobaliseldivergencelowering/#a13bb7baebeca659ef9eacc195d86c082">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::AMDGPUGlobalISelDivergenceLowering::runOnMachineFunction</a>.</p>

</div>
</div>

### markAsLaneMask() {#aa08cf4a0f128ee9edaa571de8aeff7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PhiLoweringHelper::markAsLaneMask (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### replaceDstReg() {#af052e96e38471b6180b7f53c045ab933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PhiLoweringHelper::replaceDstReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AndN2Op {#af740485c69305e62a9c4f68369437174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PhiLoweringHelper::AndN2Op</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ab9a1b7f5aa7e5ea5d39a1003616bf24d">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### AndOp {#a4f5a15970e967ccbd3fe821e6d843fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PhiLoweringHelper::AndOp</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ab9a1b7f5aa7e5ea5d39a1003616bf24d">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### DT {#a5c654bc63075ea6446978668af9b23c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* llvm::PhiLoweringHelper::DT = nullptr</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a2423554b7e9d6146ea4a617838f10505">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::DivergenceLoweringHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>, <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a22a13176b4055ad945163e17b880be43">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::Vreg1LoweringHelper</a>.</p>

</div>
</div>

### ExecReg {#ab28c61f3424d42ec86dca0bce1b10266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::PhiLoweringHelper::ExecReg</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ab9a1b7f5aa7e5ea5d39a1003616bf24d">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### IsWave32 {#a9ec177d403afa0864501ca04f08ec425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PhiLoweringHelper::IsWave32 = false</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### LaneMaskRegAttrs {#acefa582f93360081f06fe71aef54da34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo::VRegAttrs llvm::PhiLoweringHelper::LaneMaskRegAttrs</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ab9a1b7f5aa7e5ea5d39a1003616bf24d">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a>, <a href="#add0c3d95c2434973b3b5795aecadf243">initializeLaneMaskRegisterAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a> and <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### MF {#a80b1d6c9ae89f83c6918aaee904070c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::PhiLoweringHelper::MF = nullptr</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a2423554b7e9d6146ea4a617838f10505">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::DivergenceLoweringHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ae8882b2a7fc8ce50e0ae8a34ffd802c1">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::getCandidatesForLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ae033ec699e4956dff9206a339674990f">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::getCandidatesForLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a6cf0eec5c3acd7ff97e6e5dec15a97d6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesFromI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>, <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a22a13176b4055ad945163e17b880be43">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::Vreg1LoweringHelper</a>.</p>

</div>
</div>

### MovOp {#a2e1c001f50d207502739b89a74ee5747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PhiLoweringHelper::MovOp</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="#ae3b1d4a4b487362c26550bdbab4ea36a">isConstantLaneMask</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### MRI {#a587ec89e73d2290668b58a5e7f771f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::PhiLoweringHelper::MRI = nullptr</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ab9a1b7f5aa7e5ea5d39a1003616bf24d">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ab0d21052f1c1a7b915dfa38ab641db71">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::cleanConstrainRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a03ce5016666b0f1d6de775b6fec814c4">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::constrainAsLaneMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ae8882b2a7fc8ce50e0ae8a34ffd802c1">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::getCandidatesForLowering</a>, <a href="#add0c3d95c2434973b3b5795aecadf243">initializeLaneMaskRegisterAttributes</a>, <a href="#ae3b1d4a4b487362c26550bdbab4ea36a">isConstantLaneMask</a>, <a href="#a4b9e1c74c0536fbade814091fd3c8ee3">isLaneMaskReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a7705c8d988a3ccfc9c35783759cd7334">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::isVreg1</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a6cf0eec5c3acd7ff97e6e5dec15a97d6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesFromI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#abc221f9ddb2aa39e4a840a7c55a3d1c5">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::markAsLaneMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a2961ec025986c8fb2c4e9981302383a6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::markAsLaneMask</a>, <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a2034914dc6524f4ca5b13bbd22635446">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::replaceDstReg</a>.</p>

</div>
</div>

### OrN2Op {#a1e02e6fd3b0984f62948db4061d4ca44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PhiLoweringHelper::OrN2Op</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### OrOp {#a579b1d38ea323d182d66c8db95263877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PhiLoweringHelper::OrOp</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ab9a1b7f5aa7e5ea5d39a1003616bf24d">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### PDT {#aa60a09fb7712789a3e5e58806b4aa10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePostDominatorTree* llvm::PhiLoweringHelper::PDT = nullptr</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a2423554b7e9d6146ea4a617838f10505">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::DivergenceLoweringHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>, <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a22a13176b4055ad945163e17b880be43">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::Vreg1LoweringHelper</a>.</p>

</div>
</div>

### PhiRegisters {#a5cb5b9ea9fecf728e509eb1d1c749e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Register&gt; llvm::PhiLoweringHelper::PhiRegisters</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a> and <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>.</p>

</div>
</div>

### ST {#aaada4db8807fee28bb4785a3ab1f9df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* llvm::PhiLoweringHelper::ST = nullptr</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a03ce5016666b0f1d6de775b6fec814c4">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::constrainAsLaneMask</a>, <a href="#a4b9e1c74c0536fbade814091fd3c8ee3">isLaneMaskReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#abc221f9ddb2aa39e4a840a7c55a3d1c5">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::markAsLaneMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a2961ec025986c8fb2c4e9981302383a6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::markAsLaneMask</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

### TII {#ab37b9650dd3ff2294ac2556672c52eb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* llvm::PhiLoweringHelper::TII = nullptr</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a>, <a href="#a4b9e1c74c0536fbade814091fd3c8ee3">isLaneMaskReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a6cf0eec5c3acd7ff97e6e5dec15a97d6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesFromI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="#a0321e28cc3da73c666a6f5e58a541de8">lowerPhis</a>, <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a34f531a3e81c860e3a04f902568f63c7">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::replaceDstReg</a>.</p>

</div>
</div>

### XorOp {#a4d640108a701d456f16d8b3ea85a7aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PhiLoweringHelper::XorOp</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a> and <a href="#a2a55e57cd0a8346f83e5e2ebe32beb65">PhiLoweringHelper</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
