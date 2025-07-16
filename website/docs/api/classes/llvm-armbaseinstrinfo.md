---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armbaseinstrinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMBaseInstrInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMBaseInstrInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">Target/ARM/ARMBaseInstrInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/armgeninstrinfo">ARMGenInstrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arminstrinfo">ARMInstrInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo">Thumb1InstrInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo">Thumb2InstrInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e82ffc3423eb67eef1e1a43f0b75ce7">ARMBaseInstrInfo</a> (const ARMSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324c804be47df2ecc6a140dc77f886bf">hasNOP</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4600f410854a2540949d8bfb93c9c348">getUnindexedOpcode</a> (unsigned Opc) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa264594513bbe667a36f2a0609fd0b3f">convertToThreeAddress</a> (MachineInstr &amp;MI, LiveVariables *LV, LiveIntervals *LIS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo">ARMBaseRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af60b6e85233b66dc672a98e641a408a9">getSubtarget</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4105078d9414276e67bb58a5f27306">CreateTargetHazardRecognizer</a> (const TargetSubtargetInfo *STI, const ScheduleDAG *DAG) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e340b4e4b4412f6808ff4270bfa6999">CreateTargetMIHazardRecognizer</a> (const InstrItineraryData *II, const ScheduleDAGMI *DAG) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a624af1a09f6ec191f88dfd2b26c3e54a">CreateTargetPostRAHazardRecognizer</a> (const InstrItineraryData *II, const ScheduleDAG *DAG) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c27deca75181d5b0986eb74bc38a1b1">analyzeBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *&amp;TBB, MachineBasicBlock *&amp;FBB, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, bool AllowModify=false) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6769b286c60f2ddb73d5c01ab2951f9f">removeBranch</a> (MachineBasicBlock &amp;MBB, int *BytesRemoved=nullptr) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2351273089a9b61efc8258cc7778093">insertBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *TBB, MachineBasicBlock *FBB, ArrayRef&lt; MachineOperand &gt; Cond, const DebugLoc &amp;DL, int *BytesAdded=nullptr) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b0989b431ac4ebde3936d535004cb88">reverseBranchCondition</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82cd49093b0102e0d11c6a3e60731ea5">isPredicated</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81895310467818e56fd11bbcbb64ee59">createMIROperandComment</a> (const MachineInstr &amp;MI, const MachineOperand &amp;Op, unsigned OpIdx, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6">ARMCC::CondCodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704420ac69ea3ab0e4dbb6f0769ee29a">getPredicate</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6d61a8fec7e62b7b19947fe5820860d">PredicateInstruction</a> (MachineInstr &amp;MI, ArrayRef&lt; MachineOperand &gt; Pred) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0158188ba4a3924c0284491250b3474">SubsumesPredicate</a> (ArrayRef&lt; MachineOperand &gt; Pred1, ArrayRef&lt; MachineOperand &gt; Pred2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386315dfb757d24c2540155dcf9819ab">ClobbersPredicate</a> (MachineInstr &amp;MI, std::vector&lt; MachineOperand &gt; &amp;Pred, bool SkipDead) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8845a1756d587750a29c60cb382aa4e4">isPredicable</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPredicable - Return true if the specified instruction can be predicated. <a href="#a8845a1756d587750a29c60cb382aa4e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6395fc391c48db81db6a83fef912ac07">getInstSizeInBytes</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetInstSize - Returns the size of the specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#a6395fc391c48db81db6a83fef912ac07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af369e7c79dce338c58ce4ff14aed4ebb">isLoadFromStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcd5b0dab19d779b41fa0c97aa9378c">isStoreToStackSlot</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f9cb330567d54bc528af741e5394f5">isLoadFromStackSlotPostFE</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86f72dfcfa311751247ac3a6de57621">isStoreToStackSlotPostFE</a> (const MachineInstr &amp;MI, int &amp;FrameIndex) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654fa7da7f95a667f9663b3d6a130293">copyToCPSR</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, MCRegister SrcReg, bool KillSrc, const ARMSubtarget &amp;Subtarget) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6290d83ecf58d4693ea6442be7b23e">copyFromCPSR</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, MCRegister DestReg, bool KillSrc, const ARMSubtarget &amp;Subtarget) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abef9f720617461778f1a2e49d17ea159">copyPhysReg</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, MCRegister DestReg, MCRegister SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a7868df2562a3b48d08d24c9db87b98">storeRegToStackSlot</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, Register SrcReg, bool isKill, int FrameIndex, const TargetRegisterClass *RC, const TargetRegisterInfo *TRI, Register VReg, MachineInstr::MIFlag Flags=MachineInstr::NoFlags) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81fe15801547c074b2c33034c00df067">loadRegFromStackSlot</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, Register DestReg, int FrameIndex, const TargetRegisterClass *RC, const TargetRegisterInfo *TRI, Register VReg, MachineInstr::MIFlag Flags=MachineInstr::NoFlags) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2c3303ec55393902e579d316051289">expandPostRAPseudo</a> (MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe08501833a78c86e99338e6fef0137c">shouldSink</a> (const MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a744bd116065744fe9e1f41d4d63f87c0">reMaterialize</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register DestReg, unsigned SubIdx, const MachineInstr &amp;Orig, const TargetRegisterInfo &amp;TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4e4e4a8fa157eb9945d44717359bb1">duplicate</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertBefore, const MachineInstr &amp;Orig) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396ce0a5b70320d155c9959a080d543f">AddDReg</a> (MachineInstrBuilder &amp;MIB, unsigned Reg, unsigned SubIdx, unsigned State, const TargetRegisterInfo *TRI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a480d1fb65446ff93ffc9f140e213ab">produceSameValue</a> (const MachineInstr &amp;MI0, const MachineInstr &amp;MI1, const MachineRegisterInfo *MRI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ec5f3b915078525275298dc021f58c">areLoadsFromSameBasePtr</a> (SDNode *Load1, SDNode *Load2, int64_t &amp;Offset1, int64_t &amp;Offset2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>areLoadsFromSameBasePtr - This is used by the pre-regalloc scheduler to determine if two loads are loading from the same base address. <a href="#ab1ec5f3b915078525275298dc021f58c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac624f59926b6618a1da5645cae8bc2c5">shouldScheduleLoadsNear</a> (SDNode *Load1, SDNode *Load2, int64_t Offset1, int64_t Offset2, unsigned NumLoads) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>shouldScheduleLoadsNear - This is a used by the pre-regalloc scheduler to determine (in conjunction with areLoadsFromSameBasePtr) if two loads should be scheduled togther. <a href="#ac624f59926b6618a1da5645cae8bc2c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8309c88679a02fd91da5aa351a737e8d">isSchedulingBoundary</a> (const MachineInstr &amp;MI, const MachineBasicBlock *MBB, const MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3790c110e8f9d3ffde8dfde05bd53edb">isProfitableToIfCvt</a> (MachineBasicBlock &amp;MBB, unsigned NumCycles, unsigned ExtraPredCycles, BranchProbability Probability) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b272a39b33a4e8ab2ac4acb2e64d583">isProfitableToIfCvt</a> (MachineBasicBlock &amp;TMBB, unsigned NumT, unsigned ExtraT, MachineBasicBlock &amp;FMBB, unsigned NumF, unsigned ExtraF, BranchProbability Probability) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e712ae067b39367dd8df27c7fa5b39">isProfitableToDupForIfCvt</a> (MachineBasicBlock &amp;MBB, unsigned NumCycles, BranchProbability Probability) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e67eded3410916d5eb1b9710d9edb50">extraSizeToPredicateInstructions</a> (const MachineFunction &amp;MF, unsigned NumInsts) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc518a7d70c64758e7102bd60baab4bd">predictBranchSizeForIfCvt</a> (MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad537aedc883659240d215cd8613f7f9e">isProfitableToUnpredicate</a> (MachineBasicBlock &amp;TMBB, MachineBasicBlock &amp;FMBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2eee14e3c370b6df7f6db3960826a1">analyzeCompare</a> (const MachineInstr &amp;MI, Register &amp;SrcReg, Register &amp;SrcReg2, int64_t &amp;CmpMask, int64_t &amp;CmpValue) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>analyzeCompare - For a comparison instruction, return the source registers in SrcReg and SrcReg2 if having two register operands, and the value it compares against in CmpValue. <a href="#aea2eee14e3c370b6df7f6db3960826a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cb817575a9c4141e5a1268e6821503">optimizeCompareInstr</a> (MachineInstr &amp;CmpInstr, Register SrcReg, Register SrcReg2, int64_t CmpMask, int64_t CmpValue, const MachineRegisterInfo *MRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>optimizeCompareInstr - Convert the instruction to set the zero flag so that we can remove a "comparison with zero"; Remove a redundant CMP instruction if the flags can be updated in the same way by an earlier instruction such as SUB. <a href="#a12cb817575a9c4141e5a1268e6821503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af882e4e0e248f1f833eb8f4e00b06c62">analyzeSelect</a> (const MachineInstr &amp;MI, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, unsigned &amp;TrueOp, unsigned &amp;FalseOp, bool &amp;Optimizable) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567798554f5c662fc4a85150a9058b69">optimizeSelect</a> (MachineInstr &amp;MI, SmallPtrSetImpl&lt; MachineInstr * &gt; &amp;SeenMIs, bool) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309b19640cc1989cb6c46600e274cf45">foldImmediate</a> (MachineInstr &amp;UseMI, MachineInstr &amp;DefMI, Register Reg, MachineRegisterInfo *MRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>foldImmediate - 'Reg' is known to be defined by a move immediate instruction, try to fold the immediate into the use instruction. <a href="#a309b19640cc1989cb6c46600e274cf45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41289ca8ad61ff8ab86bc82a0afd8e1c">getNumMicroOps</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5db29ece2631cd6c9f36b99fe92feab">getOperandLatency</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;DefMI, unsigned DefIdx, const MachineInstr &amp;UseMI, unsigned UseIdx) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21153a0c2c9279d36a253cfb602bef43">getOperandLatency</a> (const InstrItineraryData *ItinData, SDNode *DefNode, unsigned DefIdx, SDNode *UseNode, unsigned UseIdx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint16_t, uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d0b95162803bce3077da0508daa9a7">getExecutionDomain</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VFP/NEON execution domains. <a href="#ad0d0b95162803bce3077da0508daa9a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b3180edf81915b106633986034d7a01">setExecutionDomain</a> (MachineInstr &amp;MI, unsigned Domain) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51539193cc8ad7ae2884993bbb57ddea">getPartialRegUpdateClearance</a> (const MachineInstr &amp;, unsigned, const TargetRegisterInfo *) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0904aef5bec338f4fea047c49455aa">breakPartialRegDependency</a> (MachineInstr &amp;, unsigned, const TargetRegisterInfo *TRI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d24a65d052560ecdc9cbd2194a5730">getNumLDMAddresses</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of addresses by LDM or VLDM or zero for unknown. <a href="#a54d24a65d052560ecdc9cbd2194a5730">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31eba269056d6cd7830101118d1d9547">decomposeMachineOperandsTargetFlags</a> (unsigned TF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b8142ae1da479687097277072cf97d">getSerializableDirectMachineOperandTargetFlags</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd1f16c5f15b23dfbd3f66027fc4dc1">getSerializableBitmaskMachineOperandTargetFlags</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7135ce67312a13f34932d42937861857">isFunctionSafeToOutlineFrom</a> (MachineFunction &amp;MF, bool OutlineFromLinkOnceODRs) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> supports the MachineOutliner. <a href="#a7135ce67312a13f34932d42937861857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">outliner::OutlinedFunction</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99791c9647b053fc872d35a3f0faafd7">getOutliningCandidateInfo</a> (const MachineModuleInfo &amp;MMI, std::vector&lt; outliner::Candidate &gt; &amp;RepeatedSequenceLocs, unsigned MinRepeats) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ff609e7f9151e0c2c6a6b1445c9134">mergeOutliningCandidateAttributes</a> (Function &amp;F, std::vector&lt; outliner::Candidate &gt; &amp;Candidates) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52">outliner::InstrType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abffddc65a79eca0830b7dd232ff74dc5">getOutliningTypeImpl</a> (const MachineModuleInfo &amp;MMI, MachineBasicBlock::iterator &amp;MIT, unsigned Flags) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedba2e5f9aa7cb803611f295ad04b865">isMBBSafeToOutlineFrom</a> (MachineBasicBlock &amp;MBB, unsigned &amp;Flags) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee485429210d9273f05a2ffc2d1f38d6">buildOutlinedFrame</a> (MachineBasicBlock &amp;MBB, MachineFunction &amp;MF, const outliner::OutlinedFunction &amp;OF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e56a357662b8329b718e0d8ae12983b">insertOutlinedCall</a> (Module &amp;M, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;It, MachineFunction &amp;MF, outliner::Candidate &amp;C) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773d4ec5eecb09f98e46019e6bf0194e">shouldOutlineFromFunctionByDefault</a> (MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable outlining by default at -Oz. <a href="#a773d4ec5eecb09f98e46019e6bf0194e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00d7b7c8844bba6d2b39f95b8172975f">isUnspillableTerminatorImpl</a> (const MachineInstr *MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo">TargetInstrInfo::PipelinerLoopInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637fe9208c860066ecf02233cd258f9b">analyzeLoopForPipelining</a> (MachineBasicBlock *LoopBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze loop L, which must be a single-basic-block loop, and if the conditions can be understood enough produce a PipelinerLoopInfo object. <a href="#a637fe9208c860066ecf02233cd258f9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea3c2409dae7b27a172ba7a8b6d17b5">isFpMLxInstruction</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFpMLxInstruction - Return true if the specified opcode is a fp MLA / MLS instruction. <a href="#adea3c2409dae7b27a172ba7a8b6d17b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168380fa7a6b64cf46cdb6a249137966">isFpMLxInstruction</a> (unsigned Opcode, unsigned &amp;MulOpc, unsigned &amp;AddSubOpc, bool &amp;NegAcc, bool &amp;HasLane) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFpMLxInstruction - This version also returns the multiply opcode and the addition / subtraction opcode to expand to. <a href="#a168380fa7a6b64cf46cdb6a249137966">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3191456b85282bb1bb504bcc48856d1f">canCauseFpMLxStall</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canCauseFpMLxStall - Return true if an instruction of the specified opcode will cause stalls when scheduled after (within 4-cycle window) a fp MLA / MLS instruction. <a href="#a3191456b85282bb1bb504bcc48856d1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf279a75270e2561fb5ce6d4128ad4f4">isSwiftFastImmShift</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction has a shift by immediate that can be executed in one cycle less. <a href="#adf279a75270e2561fb5ce6d4128ad4f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3ea3c557d071ba55dbd5fbd1fcc8be">getFramePred</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns predicate register associated with the given frame instruction. <a href="#a8a3ea3c557d071ba55dbd5fbd1fcc8be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/regimmpair">RegImmPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5fcf3c38734c224904ec0203c965b1">isAddImmediate</a> (const MachineInstr &amp;MI, Register Reg) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83de3f9ab24662688a50952de742a4dd">expandLoadStackGuardBase</a> (MachineBasicBlock::iterator MI, unsigned LoadImmOpc, unsigned LoadOpc) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7f60edec8e7b982c598aa278f9420c">getRegSequenceLikeInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, SmallVectorImpl&lt; RegSubRegPairAndIdx &gt; &amp;InputRegs) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the equivalent inputs of a REG_SEQUENCE for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>. <a href="#aba7f60edec8e7b982c598aa278f9420c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc76a889f289a0e841775d80aa0338ba">getExtractSubregLikeInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, RegSubRegPairAndIdx &amp;InputReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the equivalent inputs of a EXTRACT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>. <a href="#afc76a889f289a0e841775d80aa0338ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8556ad731efc2f7a407169624d812e">getInsertSubregLikeInputs</a> (const MachineInstr &amp;MI, unsigned DefIdx, RegSubRegPair &amp;BaseReg, RegSubRegPairAndIdx &amp;InsertedReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the equivalent inputs of a INSERT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>. <a href="#abc8556ad731efc2f7a407169624d812e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76e71e7ea189719baa6f8819724fac5">commuteInstructionImpl</a> (MachineInstr &amp;MI, bool NewMI, unsigned OpIdx1, unsigned OpIdx2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Commutes the operands in the given instruction. <a href="#af76e71e7ea189719baa6f8819724fac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79908cd03f29fd868447149400d19ffe">isCopyInstrImpl</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specific machine instruction is an instruction that moves/copies value from one register to another register return destination and source registers as machine operands. <a href="#a79908cd03f29fd868447149400d19ffe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ad81cebfbef0742380b0227ae7000e0a3">ParamLoadedValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9623871230b3a4317f06f55c576c404e">describeLoadedValue</a> (const MachineInstr &amp;MI, Register Reg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">TargetInstrInfo::describeLoadedValue</a>, used to enhance debug entry value descriptions for <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> targets. <a href="#a9623871230b3a4317f06f55c576c404e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27efc39ad941520c462ecff6325cc46">findRegisterToSaveLRTo</a> (outliner::Candidate &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an unused general-purpose register which can be used for constructing an outlined call if one exists. <a href="#ac27efc39ad941520c462ecff6325cc46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7613d24eec629046e10810112eac259">saveLROnStack</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator It, bool CFI, bool Auth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an instruction which saves the link register on top of the stack into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>. <a href="#af7613d24eec629046e10810112eac259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1f8d1a8c93d2ba1ebff3d5a1770c8e7">restoreLRFromStack</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator It, bool CFI, bool Auth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an instruction which restores the link register from the top the stack into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>. <a href="#af1f8d1a8c93d2ba1ebff3d5a1770c8e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d84a314dbc616feb32bba66d52af62">emitCFIForLRSaveToReg</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator It, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit CFI instructions into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>, for the case when the LR is saved in the register <span class="doxyComputerOutput">Reg</span>. <a href="#a97d84a314dbc616feb32bba66d52af62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9f02f867811525a0bf699e960fc8eb">emitCFIForLRRestoreFromReg</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator It) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit CFI instructions into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>, after the LR is was restored from a register. <a href="#aec9f02f867811525a0bf699e960fc8eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa5fe343b14edd27403ecf692b020aa">fixupPostOutline</a> (MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the offsets on outlined instructions in <span class="doxyComputerOutput">MBB</span> which use SP so that they will be valid post-outlining. <a href="#a3aa5fe343b14edd27403ecf692b020aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a28bf2970c6fb5bd9c5f072b460a1b0">checkAndUpdateStackOffset</a> (MachineInstr *MI, int64_t Fixup, bool Updt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the machine instruction offset can handle the stack fixup and updates it if requested. <a href="#a8a28bf2970c6fb5bd9c5f072b460a1b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf38989e9e617875124d7f669f8fe707">getInstBundleLength</a> (const MachineInstr &amp;MI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1347557d9fc31b56fb03b4d7652a0be1">getVLDMDefCycle</a> (const InstrItineraryData *ItinData, const MCInstrDesc &amp;DefMCID, unsigned DefClass, unsigned DefIdx, unsigned DefAlign) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec4b8a55e28d109346feb20ad225690">getLDMDefCycle</a> (const InstrItineraryData *ItinData, const MCInstrDesc &amp;DefMCID, unsigned DefClass, unsigned DefIdx, unsigned DefAlign) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d30fce9be8adebe1efba204f8d6593">getVSTMUseCycle</a> (const InstrItineraryData *ItinData, const MCInstrDesc &amp;UseMCID, unsigned UseClass, unsigned UseIdx, unsigned UseAlign) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80d5c5c2765f766b9cfea901b792436b">getSTMUseCycle</a> (const InstrItineraryData *ItinData, const MCInstrDesc &amp;UseMCID, unsigned UseClass, unsigned UseIdx, unsigned UseAlign) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d687910812181880b2e8b20ac06293">getOperandLatency</a> (const InstrItineraryData *ItinData, const MCInstrDesc &amp;DefMCID, unsigned DefIdx, unsigned DefAlign, const MCInstrDesc &amp;UseMCID, unsigned UseIdx, unsigned UseAlign) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239062d55e8ce0bde4cab5b8e660b37d">getOperandLatencyImpl</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;DefMI, unsigned DefIdx, const MCInstrDesc &amp;DefMCID, unsigned DefAdj, const MachineOperand &amp;DefMO, unsigned Reg, const MachineInstr &amp;UseMI, unsigned UseIdx, const MCInstrDesc &amp;UseMCID, unsigned UseAdj) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25446e8d0093dd28a9026ad51cba5fb2">getPredicationCost</a> (const MachineInstr &amp;MI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78557766396e15defb7ef991b400d1d9">getInstrLatency</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;MI, unsigned *PredCost=nullptr) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e85964e374f187b4a567b26b0557fde">getInstrLatency</a> (const InstrItineraryData *ItinData, SDNode *Node) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06703e4fdb23669e0e0b9848f7857b22">hasHighOperandLatency</a> (const TargetSchedModel &amp;SchedModel, const MachineRegisterInfo *MRI, const MachineInstr &amp;DefMI, unsigned DefIdx, const MachineInstr &amp;UseMI, unsigned UseIdx) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5df3464e5f85a4e554f9e157f61f8a">hasLowDefLatency</a> (const TargetSchedModel &amp;SchedModel, const MachineInstr &amp;DefMI, unsigned DefIdx) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e4a8d6b67f41804069d11ec9446bc0">verifyInstruction</a> (const MachineInstr &amp;MI, StringRef &amp;ErrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>verifyInstruction - Perform target specific instruction verification. <a href="#a63e4a8d6b67f41804069d11ec9446bc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284f8e759a99d87b543429943d540f55">expandLoadStackGuard</a> (MachineBasicBlock::iterator MI) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0e34f85670b3dce11a5b76e9dccc4ad">expandMEMCPY</a> (MachineBasicBlock::iterator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands MEMCPY to either LDMIA/STMIA or LDMIA_UPD/STMID_UPD depending on whether the result is used. <a href="#af0e34f85670b3dce11a5b76e9dccc4ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8818b3305fddbe923b53a26ace81b2">canFoldIntoMOVCC</a> (Register Reg, const MachineRegisterInfo &amp;MRI, const TargetInstrInfo *TII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify instructions that can be folded into a MOVCC instruction, and return the defining instruction. <a href="#aec8818b3305fddbe923b53a26ace81b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f75ef552d59a2525e44d38e2963116">isReallyTriviallyReMaterializable</a> (const MachineInstr &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ba93a7c22c00ea0a10475e2c48fe56">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9fe765ec7bd9b6298c2fcba38b3056">MLxEntryMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modeling special VFP / NEON fp MLA / MLS hazards. <a href="#add9fe765ec7bd9b6298c2fcba38b3056">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; unsigned, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac7fb18bac387946e6bb4d743ceea2f">MLxHazardOpcodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MLxHazardOpcodes - Set of add / sub and multiply opcodes that would cause stalls when scheduled together with fp MLA / MLS opcodes. <a href="#a5ac7fb18bac387946e6bb4d743ceea2f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e40e0592f6a3d97d6a86534e42f955">isCPSRDefined</a> (const MachineInstr &amp;MI)</td>
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


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ARMBaseInstrInfo() {#a7e82ffc3423eb67eef1e1a43f0b75ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMBaseInstrInfo::ARMBaseInstrInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a97de685f215df81fe66267171364ab6b">ARM_MLxTable</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstrinfo/#acfc55e82500841507fb5138c7295004e">llvm::ARMInstrInfo::ARMInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a0b2db65bc0fdda9727974edf6a99b0ec">llvm::Thumb1InstrInfo::Thumb1InstrInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#aa1902d86650dda33d140efdab7e03188">llvm::Thumb2InstrInfo::Thumb2InstrInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddDReg() {#a396ce0a5b70320d155c9959a080d543f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; ARMBaseInstrInfo::AddDReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, unsigned Reg, unsigned SubIdx, unsigned State, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afacc26f29d80e10be4785a96ed6444dc">llvm::Register::isPhysicalRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a81fe15801547c074b2c33034c00df067">loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="#a8a7868df2562a3b48d08d24c9db87b98">storeRegToStackSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### analyzeBranch() {#a9c27deca75181d5b0986eb74bc38a1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::analyzeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; FBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, bool AllowModify=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a7c115385fe95b53102bbfceb5d70e3a3">llvm::ARMSubtarget::enableMachinePipeliner</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e6336a1dd23986cd15023ea0aae5269">llvm::isCondBranchOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ebb5d5fa4431b1a1835d0a5f4e2796">llvm::isIndirectBranchOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b37f55b5ab197bb725692f21204c9bc">llvm::isJumpTableBranchOpcode</a>, <a href="#a82cd49093b0102e0d11c6a3e60731ea5">isPredicated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6b9dfcdbf3d90bda7eaa08f199297fc">llvm::isSpeculationBarrierEndBBOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abbf5784629864b659e702b4861bc3b1e">llvm::isUncondBranchOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a6769b286c60f2ddb73d5c01ab2951f9f">removeBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### analyzeCompare() {#aea2eee14e3c370b6df7f6db3960826a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::analyzeCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg2, int64_t &amp; CmpMask, int64_t &amp; CmpValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>analyzeCompare - For a comparison instruction, return the source registers in SrcReg and SrcReg2 if having two register operands, and the value it compares against in CmpValue.</p>


<p>Return true if the comparison instruction can be analyzed.</p>


<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#afe08501833a78c86e99338e6fef0137c">shouldSink</a>.</p>

</div>
</div>

### analyzeLoopForPipelining() {#a637fe9208c860066ecf02233cd258f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; TargetInstrInfo::PipelinerLoopInfo &gt; ARMBaseInstrInfo::analyzeLoopForPipelining (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LoopBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze loop L, which must be a single-basic-block loop, and if the conditions can be understood enough produce a PipelinerLoopInfo object.</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6999 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7f0521fa2de44271fd4b909ea7351ef3">llvm::MachineBasicBlock::getFirstTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a40bf8f9579717d3f9be7640f1c6d678b">llvm::MachineBasicBlock::instrs</a>, <a href="#a05e40e0592f6a3d97d6a86534e42f955">isCPSRDefined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aac4710f97e398ee1ab548fa48b5bb9">llvm::isVCTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab644fcf07a4c2708333cf66276282357">llvm::MachineBasicBlock::pred_begin</a>.</p>

</div>
</div>

### analyzeSelect() {#af882e4e0e248f1f833eb8f4e00b06c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::analyzeSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, unsigned &amp; TrueOp, unsigned &amp; FalseOp, bool &amp; Optimizable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### areLoadsFromSameBasePtr() {#ab1ec5f3b915078525275298dc021f58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::areLoadsFromSameBasePtr (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load1, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load2, int64_t &amp; Offset1, int64_t &amp; Offset2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>areLoadsFromSameBasePtr - This is used by the pre-regalloc scheduler to determine if two loads are loading from the same base address.</p>


<p>It should only return true if the base pointers are the same and the only differences between the two addresses is the offset. It also returns the offsets by reference.</p>


<p>It should only return true if the base pointers are the same and the only differences between the two addresses is the offset. It also returns the offsets by reference.</p>


<p>FIXME: remove this in favor of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> interface once pre-RA-sched is permanently disabled.</p>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1964 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f96a3399d86d6f136aaa121de4217a3">llvm::SDNode::getMachineOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1223d6e9a7dfb6e51299b894beccc679">llvm::SDNode::isMachineOpcode</a>.</p>

</div>
</div>

### breakPartialRegDependency() {#aec0904aef5bec338f4fea047c49455aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::breakPartialRegDependency (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### buildOutlinedFrame() {#aee485429210d9273f05a2ffc2d1f38d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::buildOutlinedFrame (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">outliner::OutlinedFunction</a> &amp; OF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#afaa7ed984d2671729752893984eb85a3">llvm::outliner::OutlinedFunction::Candidates</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#a83ee605247fd32b2a6981444fd996825">llvm::outliner::OutlinedFunction::FrameConstructionID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4ae6d079724e013e1fd057cf6fcb57675a">MachineOutlinerDefault</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4a0f5f89e2a0973bd42b48aa3ab23bc4a7">MachineOutlinerTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4ae4ec11c9120413385aef372aaa2a390c">MachineOutlinerThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>.</p>

</div>
</div>

### canCauseFpMLxStall() {#a3191456b85282bb1bb504bcc48856d1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseInstrInfo::canCauseFpMLxStall (unsigned Opcode)</td>
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

<p>canCauseFpMLxStall - Return true if an instruction of the specified opcode will cause stalls when scheduled after (within 4-cycle window) a fp MLA / MLS instruction.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>

</div>
</div>

### ClobbersPredicate() {#a386315dfb757d24c2540155dcf9819ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::ClobbersPredicate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Pred, bool SkipDead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a357fee59a6e283ccb47175016e6f9af1">llvm::ARMII::ThumbArithFlagSetting</a>.</p>

</div>
</div>

### convertToThreeAddress() {#aa264594513bbe667a36f2a0609fd0b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ARMBaseInstrInfo::convertToThreeAddress (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/livevariables">LiveVariables</a> * LV, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a7d9742a01ea175053d76a714474d88a6">llvm::ARMII::AddrMode2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a3e943d975799a4c55333c54eac1a7991">llvm::ARMII::AddrMode3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4aeda154c828d692cd52ca6cce8765f9ae">llvm::ARMII::AddrModeMask</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a722a7eaa41e03a18392be831f831627d">llvm::LiveVariables::addVirtualRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#ae58f90c0c07a77319dd769a8588a0fa7">llvm::LiveVariables::addVirtualRegisterKilled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2c3e98260a6eb6daa3ba1da72a45e05">llvm::condCodeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a34ded33b22d7f9418072a169b593ec4d">EnableARM3Addr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a29a2545f60f5e7f7cffd5e66b0d4cf87">llvm::ARM_AM::getAM2Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acda0e957b0c23c9beaa0d98238e140f3">llvm::ARM_AM::getAM2Op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f978e0398d511ac5d13a41269b2f5fe">llvm::ARM_AM::getAM2ShiftOpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a05a5f8eaf559ab55d1c8f7f9a7826a87">llvm::ARM_AM::getAM3Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acf54dffc0ef46cbffcaace8bcf2a3758">llvm::ARM_AM::getAM3Op</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f3447f06da0010c13eeb865004f71ca">llvm::ARM_AM::getSOImmVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a6f904876469fc050db9a5723a79d1200">llvm::ARM_AM::getSORegOpc</a>, <a href="#a4600f410854a2540949d8bfb93c9c348">getUnindexedOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#af73ca972d296b25a689a90fb5a0713f3">llvm::LiveVariables::getVarInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a090893e44b7d8da1ed8e65cc6b586ae8">llvm::ARMII::IndexModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac3c83a9ce4f6ef1a90d63ebe5722b2b9ab9fd312a3c788e0bd21fc94e46cf5ab2">llvm::ARMII::IndexModePost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac3c83a9ce4f6ef1a90d63ebe5722b2b9abf29846376f4da85457ab5fbc9dfcc70">llvm::ARMII::IndexModePre</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4ac928721626de611c1e5c7acfd4e05f79">llvm::ARMII::IndexModeShift</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2380c209ae5339835b5e6ea6d5c197ad">llvm::MachineInstr::readsRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">llvm::ARM_AM::sub</a>.</p>

</div>
</div>

### copyFromCPSR() {#a3b6290d83ecf58d4693ea6442be7b23e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::copyFromCPSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> DestReg, bool KillSrc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp; Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>.</p>


<p>Referenced by <a href="#abef9f720617461778f1a2e49d17ea159">copyPhysReg</a>.</p>

</div>
</div>

### copyPhysReg() {#abef9f720617461778f1a2e49d17ea159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::copyPhysReg (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> DestReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad0a79b68db2b8f84f92b1ee24352b3ce">llvm::MachineInstr::addRegisterDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa19514ee903587d4cfaee302cf7ce4d">llvm::addUnpredicatedMveVpredROp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2c3e98260a6eb6daa3ba1da72a45e05">llvm::condCodeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a3b6290d83ecf58d4693ea6442be7b23e">copyFromCPSR</a>, <a href="#a654fa7da7f95a667f9663b3d6a130293">copyToCPSR</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a4d30d32e32d7be938a8b0a0f4dd21418">llvm::Thumb2InstrInfo::copyPhysReg</a> and <a href="#a7e56a357662b8329b718e0d8ae12983b">insertOutlinedCall</a>.</p>

</div>
</div>

### copyToCPSR() {#a654fa7da7f95a667f9663b3d6a130293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::copyToCPSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SrcReg, bool KillSrc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp; Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>.</p>


<p>Referenced by <a href="#abef9f720617461778f1a2e49d17ea159">copyPhysReg</a>.</p>

</div>
</div>

### createMIROperandComment() {#a81895310467818e56fd11bbcbb64ee59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ARMBaseInstrInfo::createMIROperandComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op, unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad226a03c557dc47fb105410a216661b1">llvm::ARMCondCodeToString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea7fb8b18a37883f51af73238e47dea4">llvm::TargetInstrInfo::createMIROperandComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### CreateTargetHazardRecognizer() {#a1b4105078d9414276e67bb58a5f27306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * ARMBaseInstrInfo::CreateTargetHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a7242b69b2f705111801d717e2ea243b5">llvm::TargetInstrInfo::CreateTargetHazardRecognizer</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### CreateTargetMIHazardRecognizer() {#a7e340b4e4b4412f6808ff4270bfa6999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * ARMBaseInstrInfo::CreateTargetMIHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/multihazardrecognizer/#a618db508276a64a8834e47955553caed">llvm::MultiHazardRecognizer::AddHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5da941cb7cfe3ae9b3dae1f5caac8b78">llvm::TargetInstrInfo::CreateTargetMIHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78c0f3feb8a81ca338f843494cff564e">llvm::ScheduleDAGMI::hasVRegLiveness</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### CreateTargetPostRAHazardRecognizer() {#a624af1a09f6ec191f88dfd2b26c3e54a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * ARMBaseInstrInfo::CreateTargetPostRAHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/multihazardrecognizer/#a618db508276a64a8834e47955553caed">llvm::MultiHazardRecognizer::AddHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a000bd55721d30de4fee9eb3d812714ea">llvm::TargetInstrInfo::CreateTargetPostRAHazardRecognizer</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### decomposeMachineOperandsTargetFlags() {#a31eba269056d6cd7830101118d1d9547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; ARMBaseInstrInfo::decomposeMachineOperandsTargetFlags (unsigned TF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac33037e230d127af6de7945ce02e7e5aa0e45cd4ab4a729746f756f8d92e231b4">llvm::ARMII::MO_OPTION_MASK</a>.</p>

</div>
</div>

### duplicate() {#a7a4e4e4a8fa157eb9945d44717359bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; ARMBaseInstrInfo::duplicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertBefore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Orig)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a8d5210bd68a86582390a6fbf1f57e319">llvm::TargetInstrInfo::duplicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### expandPostRAPseudo() {#abe2c3303ec55393902e579d316051289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::expandPostRAPseudo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### extraSizeToPredicateInstructions() {#a9e67eded3410916d5eb1b9710d9edb50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::extraSizeToPredicateInstructions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned NumInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>.</p>

</div>
</div>

### foldImmediate() {#a309b19640cc1989cb6c46600e274cf45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::foldImmediate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>foldImmediate - 'Reg' is known to be defined by a move immediate instruction, try to fold the immediate into the use instruction.</p>

<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2c3e98260a6eb6daa3ba1da72a45e05">llvm::condCodeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#abbbd359eefeb5aed59eecadddd4bf756">llvm::ARM_AM::getSOImmTwoPartFirst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a605dd3e1bea15f2c42b7efa063273e1f">llvm::ARM_AM::getSOImmTwoPartSecond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#aa9be15b1cfdccd1e45bcbec61d2f111a">llvm::ARM_AM::getT2SOImmTwoPartFirst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a785452529e8d32f5611eea90afe4256a">llvm::ARM_AM::getT2SOImmTwoPartSecond</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a32e10f6539cad5809d0d09d3a8d41b62">llvm::MCInstrDesc::hasOptionalDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a6581a1f491b4f01c6b93d63ea095f5b6">llvm::ARM_AM::isSOImmTwoPartVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#aace5db47fb82e762bb6ac3aef10716cb">llvm::ARM_AM::isT2SOImmTwoPartVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### getExecutionDomain() {#ad0d0b95162803bce3077da0508daa9a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint16_t, uint16_t &gt; ARMBaseInstrInfo::getExecutionDomain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VFP/NEON execution domains.</p>

<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5058 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a96db53f04326f6421725b16e4ee7a596">llvm::ARMII::DomainMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a0f4e17fd43419980264bba50ce572d60">llvm::ARMII::DomainNEON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a23ab698d5fa355a202fb1f18b173f811">llvm::ARMII::DomainNEONA8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a0fecec4134a451feb93566a8a0a75ae1">llvm::ARMII::DomainVFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a9716711ecfa12e9b08bf9bca20b52429afbe482a8b25c7219e7cf97a031e42eb0">ExeGeneric</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a9716711ecfa12e9b08bf9bca20b52429a38642eed189597cd4b0c90fe46f2bcd2">ExeNEON</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a9716711ecfa12e9b08bf9bca20b52429a15d6a46113ff3279d6a41d41c6f57e01">ExeVFP</a>, <a href="#a82cd49093b0102e0d11c6a3e60731ea5">isPredicated</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getFramePred() {#a8a3ea3c557d071ba55dbd5fbd1fcc8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMBaseInstrInfo::getFramePred (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Returns predicate register associated with the given frame instruction.</p>

<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getInstSizeInBytes() {#a6395fc391c48db81db6a83fef912ac07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getInstSizeInBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetInstSize - Returns the size of the specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>GetInstSize - Return the size of the specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a6c02973966a15241aedb2a1016de4ff3">llvm::ARMFunctionInfo::isThumbFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a99791c9647b053fc872d35a3f0faafd7">getOutliningCandidateInfo</a> and <a href="#abc518a7d70c64758e7102bd60baab4bd">predictBranchSizeForIfCvt</a>.</p>

</div>
</div>

### getNumLDMAddresses() {#a54d24a65d052560ecdc9cbd2194a5730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getNumLDMAddresses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of addresses by LDM or VLDM or zero for unknown.</p>

<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getNumMicroOps() {#a41289ca8ad61ff8ab86bc82a0afd8e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getNumMicroOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ac7324b67d7e3be270177e6590f0bb1e5a97d6452d484864e16c59e4c1032af8dc">llvm::ARMSubtarget::DoubleIssue</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ac7324b67d7e3be270177e6590f0bb1e5a15d56a42a3f8569bb24a0cdc215d9729">llvm::ARMSubtarget::DoubleIssueCheckUnalignedAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a035351039a05ded742d1958d3d63d92b">llvm::InstrItineraryData::getNumMicroOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#af4b5497264eedd6889f04a4253ca2587">getNumMicroOpsSingleIssuePlusExtras</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a546b8cefb687c85f2a1383240bb5f4da">getNumMicroOpsSwiftLdSt</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#affe6bc9136f849e9b46fbccf620b3409">llvm::InstrItineraryData::isEmpty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ac7324b67d7e3be270177e6590f0bb1e5a4036c7f30f9ea851473b06416cbbc160">llvm::ARMSubtarget::SingleIssue</a> and <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ac7324b67d7e3be270177e6590f0bb1e5aeeb858b21b645dd260c1c4b16ccb5e23">llvm::ARMSubtarget::SingleIssuePlusExtras</a>.</p>

</div>
</div>

### getOperandLatency() {#ab5db29ece2631cd6c9f36b99fe92feab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, unsigned DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, unsigned UseIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#af6bfa18127f16dd84301143202b34ee1">getBundledDefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2a0d637eafda3140c5ba8f8c17ba25d9">getBundledUseMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1f3c8255141a4f5b7ed15fcf60118eb1">llvm::MachineInstr::isCopyLike</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#affe6bc9136f849e9b46fbccf620b3409">llvm::InstrItineraryData::isEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a120ccebe70e1b0ddf72fc776229d0025">llvm::MachineInstr::isImplicitDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9de0e8de0615ba9a3e4fa551e25ddcee">llvm::MachineInstr::isInsertSubreg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8d97d09150ddcbcf5039f938111358ee">llvm::MachineInstr::isRegSequence</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#a21153a0c2c9279d36a253cfb602bef43">getOperandLatency</a>.</p>

</div>
</div>

### getOperandLatency() {#a21153a0c2c9279d36a253cfb602bef43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * DefNode, unsigned DefIdx, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * UseNode, unsigned UseIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a29a2545f60f5e7f7cffd5e66b0d4cf87">llvm::ARM_AM::getAM2Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f978e0398d511ac5d13a41269b2f5fe">llvm::ARM_AM::getAM2ShiftOpc</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a90cd0589eba5e5112a68717f122f1fbe">llvm::SDNode::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f96a3399d86d6f136aaa121de4217a3">llvm::SDNode::getMachineOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#aee50fcacb786c1fc56168a0c55a4e934">llvm::MCInstrDesc::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a0fb39c8a77b3091e6a569fe24055e06f">llvm::InstrItineraryData::getOperandCycle</a>, <a href="#ab5db29ece2631cd6c9f36b99fe92feab">getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#affe6bc9136f849e9b46fbccf620b3409">llvm::InstrItineraryData::isEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1223d6e9a7dfb6e51299b894beccc679">llvm::SDNode::isMachineOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84">llvm::ARM_AM::lsl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a76f5f9f36bbd9f03c844c5b565f239efa25f26a9f4d00c9ac425953111519c041">llvm::ARM_AM::lsr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a2eae6ddcf171bdfe8cde452311ff4160">llvm::MCInstrDesc::mayLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#adcb5f001406dc2b45024dd582c444e6d">llvm::MCInstrDesc::Opcode</a>.</p>

</div>
</div>

### getOutliningCandidateInfo() {#a99791c9647b053fc872d35a3f0faafd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::unique_ptr&lt; outliner::OutlinedFunction &gt; &gt; ARMBaseInstrInfo::getOutliningCandidateInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &gt; &amp; RepeatedSequenceLocs, unsigned MinRepeats)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5895 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#a95d91bc5f619fedd6590f8513084924f">llvm::outliner::Candidate::back</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a34e9c849d91b1176c667422c85b9860f">llvm::ARMFunctionInfo::branchTargetEnforcement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a4dbb131b15a36f6d3944f6c3935c46f4">OutlinerCosts::CallDefault</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a9942cbb25bd866997456e6fa256c6dd9">OutlinerCosts::CallNoLRSave</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a830486cef2268f0966da3a014dd4be6c">OutlinerCosts::CallRegSave</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a57b44b33893ea182be7a83cec67d4a34">OutlinerCosts::CallTailCall</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#ac97b586fdf0154422f415aef0100be4c">OutlinerCosts::CallThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b64313b5c1907066b7bab1c60a2ea08">llvm::drop_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a89b2f5154ac1a331a2219bab83aa52b3">OutlinerCosts::FrameDefault</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a9a1f7ca7179cef30ecd94d1acb457ad0">OutlinerCosts::FrameNoLRSave</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#adc9642e59079db699cb247c8a2b4278f">OutlinerCosts::FrameRegSave</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a5c6c1645e386a210fd83bb8b9bb0ccd1">OutlinerCosts::FrameTailCall</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a65c1338480213bca90760854440bf135">OutlinerCosts::FrameThunk</a>, <a href="#a6395fc391c48db81db6a83fef912ac07">getInstSizeInBytes</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129a4f2a846b62b36aa105ec3ddfd151a482">HasCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a8edbf608fa301aa44ce994dd5ea0a874">isLRAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4ae6d079724e013e1fd057cf6fcb57675a">MachineOutlinerDefault</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4a91f63a4449fb0a4504497465cc2f4c9a">MachineOutlinerNoLRSave</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4a428eb3c2a256781b5e0589b47427e585">MachineOutlinerRegSave</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4a0f5f89e2a0973bd42b48aa3ab23bc4a7">MachineOutlinerTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4ae4ec11c9120413385aef372aaa2a390c">MachineOutlinerThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc14fa925bdbae07ef7bbd16ca82ce3d">llvm::partition</a>, <a href="/web-llvm/docs/api/structs/outlinercosts/#a9b0a792754b5e1083184eb3cb807f184">OutlinerCosts::SaveRestoreLROnStack</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a7f7b602a20180dd5d46065c354ae9902">llvm::ARMFunctionInfo::shouldSignReturnAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129ac7d6a08b9442af3460a55305a35fd823">UnsafeRegsDead</a>.</p>

</div>
</div>

### getOutliningTypeImpl() {#abffddc65a79eca0830b7dd232ff74dc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">outliner::InstrType ARMBaseInstrInfo::getOutliningTypeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MIT, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a96db53f04326f6421725b16e4ee7a596">llvm::ARMII::DomainMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4ab5112bfba90c616984021580dd1131b8">llvm::ARMII::DomainMVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#ac1a4ac2dc30f53dff05d2c7b2d8ebaef">llvm::MachineModuleInfo::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab4b44bc5aa744df4f8b70f971e8dcbf1">llvm::MachineFrameInfo::getNumObjects</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129a4f2a846b62b36aa105ec3ddfd151a482">HasCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52a795f5ad85ed392b65a70b46dacaeef34">llvm::outliner::Illegal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a81504f733d0491a446a16ef1ba0a5c2a">llvm::MachineFrameInfo::isCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52a5b2760b5bb9cc62190d2ddfe563776b9">llvm::outliner::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52a6adc06fdab039cdbfaaeda00060c5e63">llvm::outliner::LegalTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129a4833a7f75545b7500185a9ececd92b08">LRUnavailableSomewhere</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getPartialRegUpdateClearance() {#a51539193cc8ad7ae2884993bbb57ddea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getPartialRegUpdateClearance (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3be9857a09c82046b77a71918b5e214f">llvm::MachineOperand::readsReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getPredicate() {#a704420ac69ea3ab0e4dbb6f0769ee29a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMCC::CondCodes llvm::ARMBaseInstrInfo::getPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getRegisterInfo() {#a5df2d68f5108124f51112e732d713517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ARMBaseRegisterInfo &amp; llvm::ARMBaseInstrInfo::getRegisterInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<p>Referenced by <a href="#abef9f720617461778f1a2e49d17ea159">copyPhysReg</a>, <a href="#abe2c3303ec55393902e579d316051289">expandPostRAPseudo</a>, <a href="#ab5db29ece2631cd6c9f36b99fe92feab">getOperandLatency</a>, <a href="#a99791c9647b053fc872d35a3f0faafd7">getOutliningCandidateInfo</a>, <a href="#abffddc65a79eca0830b7dd232ff74dc5">getOutliningTypeImpl</a>, <a href="#aedba2e5f9aa7cb803611f295ad04b865">isMBBSafeToOutlineFrom</a>, <a href="#a3790c110e8f9d3ffde8dfde05bd53edb">isProfitableToIfCvt</a>, <a href="#a81fe15801547c074b2c33034c00df067">loadRegFromStackSlot</a>, <a href="#a12cb817575a9c4141e5a1268e6821503">optimizeCompareInstr</a>, <a href="#abc518a7d70c64758e7102bd60baab4bd">predictBranchSizeForIfCvt</a>, <a href="#a5b3180edf81915b106633986034d7a01">setExecutionDomain</a> and <a href="#a8a7868df2562a3b48d08d24c9db87b98">storeRegToStackSlot</a>.</p>

</div>
</div>

### getSerializableBitmaskMachineOperandTargetFlags() {#a5cd1f16c5f15b23dfbd3f66027fc4dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; unsigned, const char * &gt; &gt; ARMBaseInstrInfo::getSerializableBitmaskMachineOperandTargetFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getSerializableDirectMachineOperandTargetFlags() {#ae3b8142ae1da479687097277072cf97d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; unsigned, const char * &gt; &gt; ARMBaseInstrInfo::getSerializableDirectMachineOperandTargetFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getSubtarget() {#af60b6e85233b66dc672a98e641a408a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget &amp; llvm::ARMBaseInstrInfo::getSubtarget ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a8845a1756d587750a29c60cb382aa4e4">isPredicable</a> and <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a680a4b1885f1217b238bbada1e936512">llvm::Thumb2InstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### getUnindexedOpcode() {#a4600f410854a2540949d8bfb93c9c348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::ARMBaseInstrInfo::getUnindexedOpcode (unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa264594513bbe667a36f2a0609fd0b3f">convertToThreeAddress</a>.</p>

</div>
</div>

### hasNOP() {#a324c804be47df2ecc6a140dc77f886bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::hasNOP ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstrinfo/#ad900da7454c78d54e25c6fb062c851e5">llvm::ARMInstrInfo::getNop</a>.</p>

</div>
</div>

### insertBranch() {#aa2351273089a9b61efc8258cc7778093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::insertBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int * BytesAdded=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a0ca923fe17988bbe7dc155452c4b8253">llvm::ARMFunctionInfo::isThumb2Function</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a6c02973966a15241aedb2a1016de4ff3">llvm::ARMFunctionInfo::isThumbFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### insertOutlinedCall() {#a7e56a357662b8329b718e0d8ae12983b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator ARMBaseInstrInfo::insertOutlinedCall (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; It, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9117be19af857a7bdcee7bdf0279024c">llvm::MachineInstrBuilder::addGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#abef9f720617461778f1a2e49d17ea159">copyPhysReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#aa05c7b19e3485c51344a6101b1d153a9">llvm::ARMFunctionInfo::isLRSpilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4a91f63a4449fb0a4504497465cc2f4c9a">MachineOutlinerNoLRSave</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4a428eb3c2a256781b5e0589b47427e585">MachineOutlinerRegSave</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4a0f5f89e2a0973bd42b48aa3ab23bc4a7">MachineOutlinerTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ae25253bd68535ed8bdcb98a751098fe4ae4ec11c9120413385aef372aaa2a390c">MachineOutlinerThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a7f7b602a20180dd5d46065c354ae9902">llvm::ARMFunctionInfo::shouldSignReturnAddress</a>.</p>

</div>
</div>

### isAddImmediate() {#a4b5fcf3c38734c224904ec0203c965b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; RegImmPair &gt; ARMBaseInstrInfo::isAddImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### isFpMLxInstruction() {#adea3c2409dae7b27a172ba7a8b6d17b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseInstrInfo::isFpMLxInstruction (unsigned Opcode)</td>
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

<p>isFpMLxInstruction - Return true if the specified opcode is a fp MLA / MLS instruction.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>

</div>
</div>

### isFpMLxInstruction() {#a168380fa7a6b64cf46cdb6a249137966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isFpMLxInstruction (unsigned Opcode, unsigned &amp; MulOpc, unsigned &amp; AddSubOpc, bool &amp; NegAcc, bool &amp; HasLane)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isFpMLxInstruction - This version also returns the multiply opcode and the addition / subtraction opcode to expand to.</p>


<p>Return true for 'HasLane' for the MLX instructions with an extra lane operand.</p>


<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a97de685f215df81fe66267171364ab6b">ARM_MLxTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isFunctionSafeToOutlineFrom() {#a7135ce67312a13f34932d42937861857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isFunctionSafeToOutlineFrom (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool OutlineFromLinkOnceODRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> supports the MachineOutliner.</p>

<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a5638ad10fa6d78adda170a382dc7f75a">llvm::ARMFunctionInfo::isThumb1OnlyFunction</a>.</p>

</div>
</div>

### isLoadFromStackSlot() {#af369e7c79dce338c58ce4ff14aed4ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMBaseInstrInfo::isLoadFromStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isLoadFromStackSlotPostFE() {#a94f9cb330567d54bc528af741e5394f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMBaseInstrInfo::isLoadFromStackSlotPostFE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### isMBBSafeToOutlineFrom() {#aedba2e5f9aa7cb803611f295ad04b865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isMBBSafeToOutlineFrom (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned &amp; Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#af7ea64c95b144306f76693d958be9741">llvm::LiveRegUnits::accumulate</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#ab4fff7ad3de452b1b1d20de5afd986a3">llvm::LiveRegUnits::addLiveOuts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a3996f7c3774880bfe32422602fe34f9c">llvm::LiveRegUnits::available</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129a4f2a846b62b36aa105ec3ddfd151a482">HasCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a8edbf608fa301aa44ce994dd5ea0a874">isLRAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129a4833a7f75545b7500185a9ececd92b08">LRUnavailableSomewhere</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129ac7d6a08b9442af3460a55305a35fd823">UnsafeRegsDead</a>.</p>

</div>
</div>

### isPredicable() {#a8845a1756d587750a29c60cb382aa4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isPredicable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isPredicable - Return true if the specified instruction can be predicated.</p>


<p>By default, this returns true for every instruction with a PredicateOperand.</p>


<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a96db53f04326f6421725b16e4ee7a596">llvm::ARMII::DomainMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a0f4e17fd43419980264bba50ce572d60">llvm::ARMII::DomainNEON</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#af60b6e85233b66dc672a98e641a408a9">getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a70f4425ddecde73ce7618b5513220ba4">isEligibleForITBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a070cea0b95536a427b3ebbcedba2a630">llvm::isIndirectCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadefafc2b139179cb3a80c7bd52767eb">llvm::isIndirectControlFlowNotComingBack</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a0ca923fe17988bbe7dc155452c4b8253">llvm::ARMFunctionInfo::isThumb2Function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7e56496a8029847f46fea4d40383bd1">llvm::isV8EligibleForIT</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isPredicated() {#a82cd49093b0102e0d11c6a3e60731ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isPredicated (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9c27deca75181d5b0986eb74bc38a1b1">analyzeBranch</a>, <a href="#ad0d0b95162803bce3077da0508daa9a7">getExecutionDomain</a>, <a href="#a12cb817575a9c4141e5a1268e6821503">optimizeCompareInstr</a>, <a href="#a5b3180edf81915b106633986034d7a01">setExecutionDomain</a> and <a href="#afe08501833a78c86e99338e6fef0137c">shouldSink</a>.</p>

</div>
</div>

### isProfitableToDupForIfCvt() {#a55e712ae067b39367dd8df27c7fa5b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseInstrInfo::isProfitableToDupForIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned NumCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### isProfitableToIfCvt() {#a3790c110e8f9d3ffde8dfde05bd53edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isProfitableToIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned NumCycles, unsigned ExtraPredCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a079add9cf3b7069c79b91a3d8c7c28a3">llvm::findCMPToFoldIntoCBZ</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="#a3790c110e8f9d3ffde8dfde05bd53edb">isProfitableToIfCvt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a3790c110e8f9d3ffde8dfde05bd53edb">isProfitableToIfCvt</a>.</p>

</div>
</div>

### isProfitableToIfCvt() {#a5b272a39b33a4e8ab2ac4acb2e64d583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isProfitableToIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TMBB, unsigned NumT, unsigned ExtraT, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; FMBB, unsigned NumF, unsigned ExtraF, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#aaee6034264d5d0782e5d1489360730d9">llvm::BranchProbability::getCompl</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a9ccfc22b308af94572ad6843ecc21055">llvm::BranchProbability::scale</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### isProfitableToUnpredicate() {#ad537aedc883659240d215cd8613f7f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isProfitableToUnpredicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; FMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### isSchedulingBoundary() {#a8309c88679a02fd91da5aa351a737e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isSchedulingBoundary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dc83e9c9fd235321d84666f4e9b6990">llvm::isSEHInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a1fc0ffb0ef88e1f44113207a3afa4ded">llvm::Thumb2InstrInfo::isSchedulingBoundary</a>.</p>

</div>
</div>

### isStoreToStackSlot() {#aebcd5b0dab19d779b41fa0c97aa9378c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMBaseInstrInfo::isStoreToStackSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isStoreToStackSlotPostFE() {#ae86f72dfcfa311751247ac3a6de57621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMBaseInstrInfo::isStoreToStackSlotPostFE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int &amp; FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### isSwiftFastImmShift() {#adf279a75270e2561fb5ce6d4128ad4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isSwiftFastImmShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the instruction has a shift by immediate that can be executed in one cycle less.</p>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0d941a5b2ae5980beb76d03048a24eb3">llvm::ARM_AM::getSORegOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a552f0f6a6cad1279707100bfe7fc3e97">llvm::ARM_AM::getSORegShOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84">llvm::ARM_AM::lsl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a76f5f9f36bbd9f03c844c5b565f239efa25f26a9f4d00c9ac425953111519c041">llvm::ARM_AM::lsr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isUnspillableTerminatorImpl() {#a00d7b7c8844bba6d2b39f95b8172975f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseInstrInfo::isUnspillableTerminatorImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### loadRegFromStackSlot() {#a81fe15801547c074b2c33034c00df067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::loadRegFromStackSlot (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, int FrameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="#a396ce0a5b70320d155c9959a080d543f">AddDReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7bc392573220746bf1ef1f95fa98b46">llvm::addUnpredicatedMveVpredNOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5adb3c6bd94c0588ae581c154972651bfd">llvm::RegState::DefineNoRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>.</p>

</div>
</div>

### mergeOutliningCandidateAttributes() {#a68ff609e7f9151e0c2c6a6b1445c9134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::mergeOutliningCandidateAttributes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &gt; &amp; Candidates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>

</div>
</div>

### optimizeCompareInstr() {#a12cb817575a9c4141e5a1268e6821503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::optimizeCompareInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CmpInstr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg2, int64_t CmpMask, int64_t CmpValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>optimizeCompareInstr - Convert the instruction to set the zero flag so that we can remove a "comparison with zero"; Remove a redundant CMP instruction if the flags can be updated in the same way by an earlier instruction such as SUB.</p>


<p>optimizeCompareInstr - Convert the instruction supplying the argument to the comparison into one that sets the zero bit in the flags register; Remove a redundant Compare instruction if an earlier instruction can set the flags in the same way as Compare.</p>


<p>E.g. SUBrr(r1,r2) and CMPrr(r1,r2). We also handle the case where two operands are swapped: SUBrr(r1,r2) and CMPrr(r2,r1), by updating the condition code of instructions which use the flags.</p>


<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3030 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402">llvm::ARMCC::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a802d63db44042a459a19b9f89b5b470c">llvm::ARMCC::GE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a7b4dd2f8fa26445ea60946df0e7a87f7">getCmpToAddCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#aaa1eed53016f5d7e12499da95c6bb8de">getSwappedCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ace020af050937ea3b758ed0f2c07af50">llvm::ARMCC::GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a7ed629585c923f434528020bd892bb97">llvm::ARMCC::HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a038249ad0a9ef6d79cc3506c96dd3c1f">llvm::ARMCC::HS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a873fc496ea9eab446c2aea3723936a8a">isOptimizeCompareCandidate</a>, <a href="#a82cd49093b0102e0d11c6a3e60731ea5">isPredicated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a55fdcb2a9df9a69067eed1bc17a0b927">llvm::MachineOperand::isRegMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c645e5ca492fdaeaf12f389528f48fb">isSuitableForMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a59df2d2242b1477e41d1d160980ed371">llvm::ARMCC::LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a85a7716b3a259c91702bce293fb923df">llvm::ARMCC::LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a5b518bf08cf352b115648f7719a7f610">llvm::ARMCC::LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a5f1f4297ecf2dafb48ff1cb0597faea8">llvm::ARMCC::LT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46">llvm::ARMCC::MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c">llvm::ARMCC::NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8a1e111b6a355c527c0e325a6492c1fe">llvm::ARMCC::PL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ad2c4e3875c38c36df4848049d50cc28d">llvm::ARMCC::VC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6abe109952a13e776b7b978e02e4f33427">llvm::ARMCC::VS</a>.</p>

</div>
</div>

### optimizeSelect() {#a567798554f5c662fc4a85150a9058b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ARMBaseInstrInfo::optimizeSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; SeenMIs, bool PreferFalse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae26854c9925fc93880d644c0dcac8ba7">llvm::MachineInstr::clearKillInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2c3e98260a6eb6daa3ba1da72a45e05">llvm::condCodeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#a4bd63de978510703f28cd98ea7c0ffa5">llvm::ARMCC::getOppositeCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aca12cb3163511b8cfa235a411d789d46">llvm::MachineInstr::hasOptionalDef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a10e708480cdc97c951368e06c13eac92">llvm::MachineOperand::setImplicit</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">llvm::MachineInstr::tieOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a680a4b1885f1217b238bbada1e936512">llvm::Thumb2InstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### PredicateInstruction() {#ac6d61a8fec7e62b7b19947fe5820860d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::PredicateInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3f9bea613d044657b6538b7c8105bb1">llvm::getMatchingCondBranchOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abbf5784629864b659e702b4861bc3b1e">llvm::isUncondBranchOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a357fee59a6e283ccb47175016e6f9af1">llvm::ARMII::ThumbArithFlagSetting</a>.</p>

</div>
</div>

### predictBranchSizeForIfCvt() {#abc518a7d70c64758e7102bd60baab4bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::predictBranchSizeForIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a079add9cf3b7069c79b91a3d8c7c28a3">llvm::findCMPToFoldIntoCBZ</a>, <a href="#a6395fc391c48db81db6a83fef912ac07">getInstSizeInBytes</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### produceSameValue() {#a5a480d1fb65446ff93ffc9f140e213ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::produceSameValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#acaa82b4be1aefa234c71323630c2e63f">llvm::MachineConstantPoolEntry::ConstVal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool/#a906c142ea808e1bf1a66f59c4fb51048">llvm::MachineConstantPool::getConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ae204089fb50ef2edd07a7d18c5c4b79f">llvm::ARMConstantPoolValue::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab7650f958c093f7c5faf8c69dbc8c462a5f3288f908142ddad3dd5d8a95cfa364">llvm::MachineInstr::IgnoreVRegDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#a1c9559c3abf75a6df6bd2abe7131f277">llvm::MachineConstantPoolEntry::isMachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#a5c4adcee15baa3809b6c4393307b10d7">llvm::MachineConstantPoolEntry::MachineCPVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a5a480d1fb65446ff93ffc9f140e213ab">produceSameValue</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#a020d97c78e923fb96910f087012f9be5">llvm::MachineConstantPoolEntry::Val</a>.</p>


<p>Referenced by <a href="#a5a480d1fb65446ff93ffc9f140e213ab">produceSameValue</a>.</p>

</div>
</div>

### reMaterialize() {#a744bd116065744fe9e1f41d4d63f87c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::reMaterialize (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Orig, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad84ebe08bb098cd283e922fd186f77e9">llvm::MachineInstrBuilder::cloneMemRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### removeBranch() {#a6769b286c60f2ddb73d5c01ab2951f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::removeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, int * BytesRemoved=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e6336a1dd23986cd15023ea0aae5269">llvm::isCondBranchOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abbf5784629864b659e702b4861bc3b1e">llvm::isUncondBranchOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a9c27deca75181d5b0986eb74bc38a1b1">analyzeBranch</a>.</p>

</div>
</div>

### reverseBranchCondition() {#a1b0989b431ac4ebde3936d535004cb88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::reverseBranchCondition (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#a4bd63de978510703f28cd98ea7c0ffa5">llvm::ARMCC::getOppositeCondition</a>.</p>

</div>
</div>

### setExecutionDomain() {#a5b3180edf81915b106633986034d7a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::setExecutionDomain (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a9716711ecfa12e9b08bf9bca20b52429a38642eed189597cd4b0c90fe46f2bcd2">ExeNEON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a596b52704a2d5f9e2dfff04400eef99f">getCorrespondingDRegAndLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a019faf4f933d37d46d1fb3e7a37dccd5">getImplicitSPRUseForDPRUse</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3a1f79eb5e89f41ad5a3d8e9b2a367a">llvm::getUndefRegState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="#a82cd49093b0102e0d11c6a3e60731ea5">isPredicated</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>

</div>
</div>

### shouldOutlineFromFunctionByDefault() {#a773d4ec5eecb09f98e46019e6bf0194e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::shouldOutlineFromFunctionByDefault (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable outlining by default at -Oz.</p>

<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>.</p>

</div>
</div>

### shouldScheduleLoadsNear() {#ac624f59926b6618a1da5645cae8bc2c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::shouldScheduleLoadsNear (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load1, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load2, int64_t Offset1, int64_t Offset2, unsigned NumLoads)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>shouldScheduleLoadsNear - This is a used by the pre-regalloc scheduler to determine (in conjunction with areLoadsFromSameBasePtr) if two loads should be scheduled togther.</p>


<p>On some targets if two loads are loading from addresses in the same cache line, it's better if they are scheduled together. This function takes two integers that represent the load offsets from the common base address. It returns true if it decides it's desirable to schedule the two loads together. "NumLoads" is the number of loads that have already been scheduled after Load1.</p>


<p>On some targets if two loads are loading from addresses in the same cache line, it's better if they are scheduled together. This function takes two integers that represent the load offsets from the common base address. It returns true if it decides it's desirable to schedule the two loads together. "NumLoads" is the number of loads that have already been scheduled after Load1.</p>


<p>FIXME: remove this in favor of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> interface once pre-RA-sched is permanently disabled.</p>


<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2031 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f96a3399d86d6f136aaa121de4217a3">llvm::SDNode::getMachineOpcode</a>.</p>

</div>
</div>

### shouldSink() {#afe08501833a78c86e99338e6fef0137c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::shouldSink (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="#aea2eee14e3c370b6df7f6db3960826a1">analyzeCompare</a>, <a href="#a82cd49093b0102e0d11c6a3e60731ea5">isPredicated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>

</div>
</div>

### storeRegToStackSlot() {#a8a7868df2562a3b48d08d24c9db87b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::storeRegToStackSlot (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, bool isKill, int FrameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="#a396ce0a5b70320d155c9959a080d543f">AddDReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7bc392573220746bf1ef1f95fa98b46">llvm::addUnpredicatedMveVpredNOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="#a5df2d68f5108124f51112e732d713517">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### SubsumesPredicate() {#ac0158188ba4a3924c0284491250b3474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::SubsumesPredicate (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Pred1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Pred2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402">llvm::ARMCC::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a802d63db44042a459a19b9f89b5b470c">llvm::ARMCC::GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ace020af050937ea3b758ed0f2c07af50">llvm::ARMCC::GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a7ed629585c923f434528020bd892bb97">llvm::ARMCC::HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a038249ad0a9ef6d79cc3506c96dd3c1f">llvm::ARMCC::HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a59df2d2242b1477e41d1d160980ed371">llvm::ARMCC::LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a85a7716b3a259c91702bce293fb923df">llvm::ARMCC::LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a5b518bf08cf352b115648f7719a7f610">llvm::ARMCC::LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a5f1f4297ecf2dafb48ff1cb0597faea8">llvm::ARMCC::LT</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### commuteInstructionImpl() {#af76e71e7ea189719baa6f8819724fac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ARMBaseInstrInfo::commuteInstructionImpl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool NewMI, unsigned OpIdx1, unsigned OpIdx2)</td>
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

<p>Commutes the operands in the given instruction.</p>


<p>The commutable operands are specified by their indices OpIdx1 and OpIdx2.</p>


<p>Do not call this method for a non-commutable instruction or for non-commutable pair of operand indices OpIdx1 and OpIdx2. Even though the instruction is commutable, the method may still fail to commute the operands, null pointer is returned in such cases.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75925d9ebd5a8017581c9d07316be793">llvm::MachineInstr::findFirstPredOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab164a8257f8fe4e41fbb5381b9a24515">llvm::getInstrPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#a4bd63de978510703f28cd98ea7c0ffa5">llvm::ARMCC::getOppositeCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a4bf3235cec048cef2325e76190ac53b6">llvm::Thumb2InstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### describeLoadedValue() {#a9623871230b3a4317f06f55c576c404e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ParamLoadedValue &gt; ARMBaseInstrInfo::describeLoadedValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">TargetInstrInfo::describeLoadedValue</a>, used to enhance debug entry value descriptions for <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> targets.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="#a79908cd03f29fd868447149400d19ffe">isCopyInstrImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### expandLoadStackGuardBase() {#a83de3f9ab24662688a50952de742a4dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::expandLoadStackGuardBase (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, unsigned LoadImmOpc, unsigned LoadOpc)</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9117be19af857a7bdcee7bdf0279024c">llvm::MachineInstrBuilder::addGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad84ebe08bb098cd283e922fd186f77e9">llvm::MachineInstrBuilder::cloneMemRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#aa70144cee705b3f0db7f53ff3bf004e9">llvm::MachinePointerInfo::getGOT</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a66501d6d43642a526ab769458d700aa4">llvm::GlobalValue::hasDLLImportStorageClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac33037e230d127af6de7945ce02e7e5aafbf06a19f49d98cf37ed7aed51b56f02">llvm::ARMII::MO_COFFSTUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac33037e230d127af6de7945ce02e7e5aaa0968323e2f2cf5c8fdb022281f1342f">llvm::ARMII::MO_DLLIMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac33037e230d127af6de7945ce02e7e5aaeea291fff7f2b259205744614e6662e4">llvm::ARMII::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac33037e230d127af6de7945ce02e7e5aac8d5b41e417b81d1460929338ac1466e">llvm::ARMII::MO_NO_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac33037e230d127af6de7945ce02e7e5aa423a53db845fec016f1d73e6d066481f">llvm::ARMII::MO_NONLAZY</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f">llvm::MachineMemOperand::MODereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6">llvm::MachineMemOperand::MOInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>.</p>

</div>
</div>

### getExtractSubregLikeInputs() {#afc76a889f289a0e841775d80aa0338ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::getExtractSubregLikeInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#ad153312ce0e21a9c411b560bd535b1b7">RegSubRegPairAndIdx</a> &amp; InputReg)</td>
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

<p>Build the equivalent inputs of a EXTRACT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>.</p>


<p><span class="doxyComputerOutput"></span>[out] InputReg of the equivalent EXTRACT_SUBREG. E.g., EXTRACT_SUBREG %1:sub1, sub0, sub1 would produce:</p>


<ul class="doxyList ">
<li>%1:sub1, sub0</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build such an input sequence with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span>. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isExtractSubregLike().</p></dd>
</dl>


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#aad7e848e562b1368d6ee4794d84957c6">llvm::TargetInstrInfo::RegSubRegPair::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#a7f62bad8eb5dce2e4a7d7518fc5c21ac">llvm::TargetInstrInfo::RegSubRegPairAndIdx::SubIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#a66f92cf2247d7b3c3a351ff48dd42d7d">llvm::TargetInstrInfo::RegSubRegPair::SubReg</a>.</p>

</div>
</div>

### getInsertSubregLikeInputs() {#abc8556ad731efc2f7a407169624d812e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::getInsertSubregLikeInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> &amp; BaseReg, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#ad153312ce0e21a9c411b560bd535b1b7">RegSubRegPairAndIdx</a> &amp; InsertedReg)</td>
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

<p>Build the equivalent inputs of a INSERT_SUBREG for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>.</p>


<p><span class="doxyComputerOutput"></span>[out] BaseReg and <span class="doxyComputerOutput"></span>[out] InsertedReg contain the equivalent inputs of INSERT_SUBREG. E.g., INSERT_SUBREG %0:sub0, %1:sub1, sub3 would produce:</p>


<ul class="doxyList ">
<li>BaseReg: %0:sub0</li>
<li>InsertedReg: %1:sub1, sub3</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to build such an input sequence with the pair <span class="doxyComputerOutput">MI</span>, <span class="doxyComputerOutput">DefIdx</span>. False otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.isInsertSubregLike().</p></dd>
</dl>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#aad7e848e562b1368d6ee4794d84957c6">llvm::TargetInstrInfo::RegSubRegPair::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#a7f62bad8eb5dce2e4a7d7518fc5c21ac">llvm::TargetInstrInfo::RegSubRegPairAndIdx::SubIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#a66f92cf2247d7b3c3a351ff48dd42d7d">llvm::TargetInstrInfo::RegSubRegPair::SubReg</a>.</p>

</div>
</div>

### getRegSequenceLikeInputs() {#aba7f60edec8e7b982c598aa278f9420c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::getRegSequenceLikeInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DefIdx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#ad153312ce0e21a9c411b560bd535b1b7">RegSubRegPairAndIdx</a> &gt; &amp; InputRegs)</td>
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

<p>Build the equivalent inputs of a REG_SEQUENCE for the given <span class="doxyComputerOutput">MI</span> and <span class="doxyComputerOutput">DefIdx</span>.</p>


<p><span class="doxyComputerOutput"></span>[out] InputRegs of the equivalent REG_SEQUENCE. Each element of the list is modeled as &lt;Reg:SubReg, SubIdx&gt;. E.g., REG_SEQUENCE %1:sub1, sub0, %2, sub1 would produce two elements:</p>


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
<dd><p>MI.isRegSequenceLike().</p></dd>
</dl>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### isCopyInstrImpl() {#a79908cd03f29fd868447149400d19ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DestSourcePair &gt; ARMBaseInstrInfo::isCopyInstrImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>If the specific machine instruction is an instruction that moves/copies value from one register to another register return destination and source registers as machine operands.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9623871230b3a4317f06f55c576c404e">describeLoadedValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canFoldIntoMOVCC() {#aec8818b3305fddbe923b53a26ace81b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ARMBaseInstrInfo::canFoldIntoMOVCC (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify instructions that can be folded into a MOVCC instruction, and return the defining instruction.</p>

<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 2301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### checkAndUpdateStackOffset() {#a8a28bf2970c6fb5bd9c5f072b460a1b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::checkAndUpdateStackOffset (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int64_t Fixup, bool Updt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the machine instruction offset can handle the stack fixup and updates it if requested.</p>

<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### emitCFIForLRRestoreFromReg() {#aec9f02f867811525a0bf699e960fc8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::emitCFIForLRRestoreFromReg (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> It)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit CFI instructions into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>, after the LR is was restored from a register.</p>

<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### emitCFIForLRSaveToReg() {#a97d84a314dbc616feb32bba66d52af62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::emitCFIForLRSaveToReg (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> It, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit CFI instructions into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>, for the case when the LR is saved in the register <span class="doxyComputerOutput">Reg</span>.</p>

<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### expandLoadStackGuard() {#a284f8e759a99d87b543429943d540f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ARMBaseInstrInfo::expandLoadStackGuard (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>

</div>
</div>

### expandMEMCPY() {#af0e34f85670b3dce11a5b76e9dccc4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::expandMEMCPY (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands MEMCPY to either LDMIA/STMIA or LDMIA_UPD/STMID_UPD depending on whether the result is used.</p>

<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 1648 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### findRegisterToSaveLRTo() {#ac27efc39ad941520c462ecff6325cc46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMBaseInstrInfo::findRegisterToSaveLRTo (<a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an unused general-purpose register which can be used for constructing an outlined call if one exists.</p>


<p>Returns 0 otherwise.</p>


<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 5843 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### fixupPostOutline() {#a3aa5fe343b14edd27403ecf692b020aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::fixupPostOutline (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the offsets on outlined instructions in <span class="doxyComputerOutput">MBB</span> which use SP so that they will be valid post-outlining.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBB</td>
<td class="doxyParamItemDescription"><p>A <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a></span> in an outlined function.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getInstBundleLength() {#adf38989e9e617875124d7f669f8fe707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getInstBundleLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getInstrLatency() {#a78557766396e15defb7ef991b400d1d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned * PredCost=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4751 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getInstrLatency() {#a2e85964e374f187b4a567b26b0557fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4802 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getLDMDefCycle() {#adec4b8a55e28d109346feb20ad225690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getLDMDefCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; DefMCID, unsigned DefClass, unsigned DefIdx, unsigned DefAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3933 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getOperandLatency() {#a01d687910812181880b2e8b20ac06293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; DefMCID, unsigned DefIdx, unsigned DefAlign, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; UseMCID, unsigned UseIdx, unsigned UseAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4033 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getOperandLatencyImpl() {#a239062d55e8ce0bde4cab5b8e660b37d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getOperandLatencyImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, unsigned DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; DefMCID, unsigned DefAdj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; DefMO, unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, unsigned UseIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; UseMCID, unsigned UseAdj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getPredicationCost() {#a25446e8d0093dd28a9026ad51cba5fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMBaseInstrInfo::getPredicationCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4732 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getSTMUseCycle() {#a80d5c5c2765f766b9cfea901b792436b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getSTMUseCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; UseMCID, unsigned UseClass, unsigned UseIdx, unsigned UseAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4006 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getVLDMDefCycle() {#a1347557d9fc31b56fb03b4d7652a0be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getVLDMDefCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; DefMCID, unsigned DefClass, unsigned DefIdx, unsigned DefAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### getVSTMUseCycle() {#ae4d30fce9be8adebe1efba204f8d6593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; ARMBaseInstrInfo::getVSTMUseCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; UseMCID, unsigned UseClass, unsigned UseIdx, unsigned UseAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 3967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### hasHighOperandLatency() {#a06703e4fdb23669e0e0b9848f7857b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::hasHighOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> &amp; SchedModel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, unsigned DefIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, unsigned UseIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4820 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### hasLowDefLatency() {#a8e5df3464e5f85a4e554f9e157f61f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::hasLowDefLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> &amp; SchedModel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, unsigned DefIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### isReallyTriviallyReMaterializable() {#a35f75ef552d59a2525e44d38e2963116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isReallyTriviallyReMaterializable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### restoreLRFromStack() {#af1f8d1a8c93d2ba1ebff3d5a1770c8e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::restoreLRFromStack (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> It, bool CFI, bool Auth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an instruction which restores the link register from the top the stack into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>.</p>


<p>If <span class="doxyComputerOutput">Auth</span> is true, restore an authentication code and authenticate LR. If <span class="doxyComputerOutput">CFI</span> is true, emit CFI instructions.</p>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### saveLROnStack() {#af7613d24eec629046e10810112eac259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseInstrInfo::saveLROnStack (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> It, bool CFI, bool Auth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an instruction which saves the link register on top of the stack into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <span class="doxyComputerOutput">MBB</span> at position <span class="doxyComputerOutput">It</span>.</p>


<p>If <span class="doxyComputerOutput">Auth</span> is true, compute and store an authentication code alongiside the link register. If <span class="doxyComputerOutput">CFI</span> is true, emit CFI instructions.</p>


<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 6457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### verifyInstruction() {#a63e4a8d6b67f41804069d11ec9446bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::verifyInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ErrInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>verifyInstruction - Perform target specific instruction verification.</p>

<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 4858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MLxEntryMap {#add9fe765ec7bd9b6298c2fcba38b3056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::ARMBaseInstrInfo::MLxEntryMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modeling special VFP / NEON fp MLA / MLS hazards.</p>


<p>MLxEntryMap - Map fp MLA / MLS to the corresponding entry in the internal MLx table.</p>


<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>

</div>
</div>

### MLxHazardOpcodes {#a5ac7fb18bac387946e6bb4d743ceea2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;unsigned, 16&gt; llvm::ARMBaseInstrInfo::MLxHazardOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MLxHazardOpcodes - Set of add / sub and multiply opcodes that would cause stalls when scheduled together with fp MLA / MLS opcodes.</p>

<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>

</div>
</div>

### Subtarget {#a96ba93a7c22c00ea0a10475e2c48fe56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget&amp; llvm::ARMBaseInstrInfo::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isCPSRDefined() {#a05e40e0592f6a3d97d6a86534e42f955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseInstrInfo::isCPSRDefined (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a637fe9208c860066ecf02233cd258f9b">analyzeLoopForPipelining</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a70f4425ddecde73ce7618b5513220ba4">isEligibleForITBlock</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
