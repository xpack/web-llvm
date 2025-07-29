---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LowOverheadLoop` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a> (MachineLoop &amp;ML, MachineLoopInfo &amp;MLI, ReachingDefAnalysis &amp;RDA, const TargetRegisterInfo &amp;TRI, const ARMBaseInstrInfo &amp;TII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb11d0b5d726b02916f412453587951">ValidateMVEInst</a> (MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8636a64eab683e602d55bd3cc23ebfb7">AnalyseMVEInst</a> (MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f229e9f5c9ffd689f6b437accb522d">AddVCTP</a> (MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8272d1e2af6d68d30fbd619283a68c5">ValidateLiveOuts</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a> (ARMBasicBlockUtils *BBUtils)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309a1516b668315256070f5de8849ab1">FoundAllComponents</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptblock">VPTBlock</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355bbdbb545ccbb9f73dd41ca2e7790f">getVPTBlocks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d9c8ad4596ae35c6c6977dcc607e83">getLoopStartOperand</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6321a492d8cc075688ffadb330e42983">getStartOpcode</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491c4143dd9465fdcf8ef53386dedb1b">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd558713e401ce2daba1f2d347b5437c">ML</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b963b648252e0156468f2ca0185fa20">Preheader</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f9916871729e47b10a24958f664da2">MLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e5a7bddfd1a0a0cc40ec84877f567d">RDA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b675d8b2b3a971bea89735dfdca5165">TRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd44549572b4e9a381dc42b0f33fa94a">TII</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79dab52cc941085b598caab4f76f1405">MF</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd8fba0b5b8837c16072bd5118559ab">StartInsertPt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8e628daf61d6b19d6def1069e09517">StartInsertBB</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad706c1540f91008bacbe2e3136d82f74">Start</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928857dd91e8bc294bd2f7fb33c16650">Dec</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad22c793ef35d04069cf71d88842b1d4c">End</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a96e9cd60259f4869384d63bf8e1a6">TPNumElements</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b77c5fddce880ca199e3eeb05665124">VCTPs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a7a92727f975e4b3a7d5e536017bb56">ToRemove</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4745ebe81421b834ad0bd35bd05f1b">BlockMasksToRecompute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f47e46f94aaf40795d0b598bc52d9ff">DoubleWidthResultInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab044db0c921289efae9050cbfc5895">VMOVCopies</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6663cf8ef1ff1c161b2766225b37ff1a">Revert</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ca5d5bc154204d88e79d37729be08">CannotTailPredicate</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate">VPTState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc8576b3b90df902b31125d77f5762e">VPTstate</a></td>
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


<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LowOverheadLoop() {#aff890ddd726ba815dfa456b4a5b6f432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::LowOverheadLoop (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; ML, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; MLI, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> &amp; RDA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> &amp; TII)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a79dab52cc941085b598caab4f76f1405">MF</a>, <a href="#abd558713e401ce2daba1f2d347b5437c">ML</a>, <a href="#ad5f9916871729e47b10a24958f664da2">MLI</a>, <a href="#a8b963b648252e0156468f2ca0185fa20">Preheader</a>, <a href="#a43e5a7bddfd1a0a0cc40ec84877f567d">RDA</a>, <a href="#acd44549572b4e9a381dc42b0f33fa94a">TII</a>, <a href="#aa8a96e9cd60259f4869384d63bf8e1a6">TPNumElements</a> and <a href="#a7b675d8b2b3a971bea89735dfdca5165">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddVCTP() {#a76f229e9f5c9ffd689f6b437accb522d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowOverheadLoop::AddVCTP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a43e5a7bddfd1a0a0cc40ec84877f567d">RDA</a> and <a href="#a7b77c5fddce880ca199e3eeb05665124">VCTPs</a>.</p>


<p>Referenced by <a href="#afdb11d0b5d726b02916f412453587951">ValidateMVEInst</a>.</p>

</div>
</div>

### AnalyseMVEInst() {#a8636a64eab683e602d55bd3cc23ebfb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::AnalyseMVEInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a153ca5d5bc154204d88e79d37729be08">CannotTailPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#afdb11d0b5d726b02916f412453587951">ValidateMVEInst</a>.</p>

</div>
</div>

### dump() {#a491c4143dd9465fdcf8ef53386dedb1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::dump ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a928857dd91e8bc294bd2f7fb33c16650">Dec</a>, <a href="#ad22c793ef35d04069cf71d88842b1d4c">End</a>, <a href="#a309a1516b668315256070f5de8849ab1">FoundAllComponents</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ad706c1540f91008bacbe2e3136d82f74">Start</a> and <a href="#a7b77c5fddce880ca199e3eeb05665124">VCTPs</a>.</p>

</div>
</div>

### FoundAllComponents() {#a309a1516b668315256070f5de8849ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::FoundAllComponents ()</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a928857dd91e8bc294bd2f7fb33c16650">Dec</a>, <a href="#ad22c793ef35d04069cf71d88842b1d4c">End</a> and <a href="#ad706c1540f91008bacbe2e3136d82f74">Start</a>.</p>


<p>Referenced by <a href="#a491c4143dd9465fdcf8ef53386dedb1b">dump</a> and <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a>.</p>

</div>
</div>

### getLoopStartOperand() {#a02d9c8ad4596ae35c6c6977dcc607e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::getLoopStartOperand ()</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a>, <a href="#ad706c1540f91008bacbe2e3136d82f74">Start</a> and <a href="#aa8a96e9cd60259f4869384d63bf8e1a6">TPNumElements</a>.</p>

</div>
</div>

### getStartOpcode() {#a6321a492d8cc075688ffadb330e42983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::getStartOpcode ()</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a022cded702d737077e735b1eb79f8a28">llvm::isDoLoopStart</a>, <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a>, <a href="#ad706c1540f91008bacbe2e3136d82f74">Start</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa66305962c0042c0ef4d8f881a282d72">llvm::VCTPOpcodeToLSTP</a> and <a href="#a7b77c5fddce880ca199e3eeb05665124">VCTPs</a>.</p>

</div>
</div>

### getVPTBlocks() {#a355bbdbb545ccbb9f73dd41ca2e7790f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; VPTBlock &gt; &amp; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::getVPTBlocks ()</td>
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



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Reference <a href="#aebc8576b3b90df902b31125d77f5762e">VPTstate</a>.</p>

</div>
</div>

### IsTailPredicationLegal() {#a193a7893570050077d12ca10a34c0082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::IsTailPredicationLegal ()</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a153ca5d5bc154204d88e79d37729be08">CannotTailPredicate</a>, <a href="#a309a1516b668315256070f5de8849ab1">FoundAllComponents</a>, <a href="#abd558713e401ce2daba1f2d347b5437c">ML</a>, <a href="#a6663cf8ef1ff1c161b2766225b37ff1a">Revert</a> and <a href="#a7b77c5fddce880ca199e3eeb05665124">VCTPs</a>.</p>


<p>Referenced by <a href="#a02d9c8ad4596ae35c6c6977dcc607e83">getLoopStartOperand</a>, <a href="#a6321a492d8cc075688ffadb330e42983">getStartOpcode</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### Validate() {#a5cca05384a54726657bc35a6cc1b7f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowOverheadLoop::Validate (<a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils">ARMBasicBlockUtils</a> * BBUtils)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a153ca5d5bc154204d88e79d37729be08">CannotTailPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad22c793ef35d04069cf71d88842b1d4c">End</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#ac892cf3d96fe5e728db657b6e02932f0">llvm::ARMBasicBlockUtils::getOffsetOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac0b14ffe3bb6e079f201c83a682b8943">llvm::getWhileLoopStartTargetBB</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a1744b6aaacbb052e862e88903ded5956">llvm::ARMBasicBlockUtils::isBBInRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace27fc73322204af1d8dbd05dea927bc">llvm::isWhileLoopStart</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#abd558713e401ce2daba1f2d347b5437c">ML</a>, <a href="#a6663cf8ef1ff1c161b2766225b37ff1a">Revert</a>, <a href="#ad706c1540f91008bacbe2e3136d82f74">Start</a>, <a href="#a8e8e628daf61d6b19d6def1069e09517">StartInsertBB</a>, <a href="#a7dd8fba0b5b8837c16072bd5118559ab">StartInsertPt</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### ValidateLiveOuts() {#ad8272d1e2af6d68d30fbd619283a68c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowOverheadLoop::ValidateLiveOuts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#afebe38e4f4ade382a8e857b27cd990a2">llvm::SetVector&lt; T, Vector, Set, N &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a33871fd2a06a8af436f0cb548798ec5d">isHorizontalReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a5898b6ed934ad744eefecc5d5297a3a8">isRegInClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aac4710f97e398ee1ab548fa48b5bb9">llvm::isVCTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a0eba246efd54ade21f193d2362acdead">isVectorPredicated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32fb714dc42507917fed431c24b79020">llvm::isVPTOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a364ed6e68f92f797c0cd9e53ce5ea2a5">llvm::MachineBasicBlock::liveins</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abd558713e401ce2daba1f2d347b5437c">ML</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4af3b3369c27dc1c8355bcccdf3b7d5578">llvm::Predicated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#ad6f25f6a5125ee4d8f6e01e85ebf836e">producesFalseLanesZero</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a43e5a7bddfd1a0a0cc40ec84877f567d">RDA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a8af4c9dee593e1e883a0d3509c25d1d0">retainsPreviousHalfElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a9df1ebcc0b9226f9cfda9d5f73a21526">shouldInspect</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a7b675d8b2b3a971bea89735dfdca5165">TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a> and <a href="#a9ab044db0c921289efae9050cbfc5895">VMOVCopies</a>.</p>


<p>Referenced by <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### ValidateMVEInst() {#afdb11d0b5d726b02916f412453587951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowOverheadLoop::ValidateMVEInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a76f229e9f5c9ffd689f6b437accb522d">AddVCTP</a>, <a href="#a153ca5d5bc154204d88e79d37729be08">CannotTailPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a2f47e46f94aaf40795d0b598bc52d9ff">DoubleWidthResultInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a00f72b50a86f27bb8b126906a164f8ba">isDomainMVE</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aac4710f97e398ee1ab548fa48b5bb9">llvm::isVCTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a8535dd8e5a6bb6d0f053ba22246a1593">isVectorPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a0eba246efd54ade21f193d2362acdead">isVectorPredicated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7a043e6726bd97f9874d70905025648b">llvm::ARM::isVpred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32fb714dc42507917fed431c24b79020">llvm::isVPTOpcode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abd558713e401ce2daba1f2d347b5437c">ML</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a46ef4c167cadd485c1e39881969bc2d5">producesDoubleWidthResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a9df1ebcc0b9226f9cfda9d5f73a21526">shouldInspect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a5d85b8fd4787153b0ade229c616b7562">ValidateMVEStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a6f4d311cce1cd30c215499f79215051c">llvm::ARMII::ValidForTailPredication</a> and <a href="#aebc8576b3b90df902b31125d77f5762e">VPTstate</a>.</p>


<p>Referenced by <a href="#a8636a64eab683e602d55bd3cc23ebfb7">AnalyseMVEInst</a>.</p>

</div>
</div>

### ValidateTailPredicate() {#a22414e0619deaa2a695fd6d31002bb9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowOverheadLoop::ValidateTailPredicate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/register/#a49effcc0d9e7a321043ade70145d11f6">llvm::Register::asMCReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#ab781884eec3c9f1366adf3bb5f4ece69">DisableTailPredication</a>, <a href="#a2f47e46f94aaf40795d0b598bc52d9ff">DoubleWidthResultInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1158b6031fe51c293913bcd9a3353e5">llvm::getAddSubImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a469e94cf2a0777a0bb92dfb2f6fa5b12">llvm::getTailPredVectorWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#ad84c5ccc73435217f046a6fe26d547f9">getVecSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51c2a3a98a4139250a74ecae0bec5c65">llvm::isMovRegOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5fc054f5fba4582092c2761201b57519">llvm::isSubImmOpcode</a>, <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abd558713e401ce2daba1f2d347b5437c">ML</a>, <a href="#a8b963b648252e0156468f2ca0185fa20">Preheader</a>, <a href="#a43e5a7bddfd1a0a0cc40ec84877f567d">RDA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a9df1ebcc0b9226f9cfda9d5f73a21526">shouldInspect</a>, <a href="#ad706c1540f91008bacbe2e3136d82f74">Start</a>, <a href="#a8e8e628daf61d6b19d6def1069e09517">StartInsertBB</a>, <a href="#a7dd8fba0b5b8837c16072bd5118559ab">StartInsertPt</a>, <a href="#a8a7a92727f975e4b3a7d5e536017bb56">ToRemove</a>, <a href="#aa8a96e9cd60259f4869384d63bf8e1a6">TPNumElements</a>, <a href="#ad8272d1e2af6d68d30fbd619283a68c5">ValidateLiveOuts</a>, <a href="#a7b77c5fddce880ca199e3eeb05665124">VCTPs</a> and <a href="#aebc8576b3b90df902b31125d77f5762e">VPTstate</a>.</p>


<p>Referenced by <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockMasksToRecompute {#a3e4745ebe81421b834ad0bd35bd05f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 4&gt; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::BlockMasksToRecompute</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>

</div>
</div>

### CannotTailPredicate {#a153ca5d5bc154204d88e79d37729be08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::CannotTailPredicate = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a8636a64eab683e602d55bd3cc23ebfb7">AnalyseMVEInst</a>, <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a>, <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a> and <a href="#afdb11d0b5d726b02916f412453587951">ValidateMVEInst</a>.</p>

</div>
</div>

### Dec {#a928857dd91e8bc294bd2f7fb33c16650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::Dec = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a491c4143dd9465fdcf8ef53386dedb1b">dump</a> and <a href="#a309a1516b668315256070f5de8849ab1">FoundAllComponents</a>.</p>

</div>
</div>

### DoubleWidthResultInstrs {#a2f47e46f94aaf40795d0b598bc52d9ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 4&gt; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::DoubleWidthResultInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#afdb11d0b5d726b02916f412453587951">ValidateMVEInst</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### End {#ad22c793ef35d04069cf71d88842b1d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::End = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a491c4143dd9465fdcf8ef53386dedb1b">dump</a>, <a href="#a309a1516b668315256070f5de8849ab1">FoundAllComponents</a> and <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a>.</p>

</div>
</div>

### MF {#a79dab52cc941085b598caab4f76f1405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a>.</p>

</div>
</div>

### ML {#abd558713e401ce2daba1f2d347b5437c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoop&amp; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ML</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a>, <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a>, <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a>, <a href="#ad8272d1e2af6d68d30fbd619283a68c5">ValidateLiveOuts</a>, <a href="#afdb11d0b5d726b02916f412453587951">ValidateMVEInst</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### MLI {#ad5f9916871729e47b10a24958f664da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo&amp; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::MLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a>.</p>

</div>
</div>

### Preheader {#a8b963b648252e0156468f2ca0185fa20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::Preheader = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### RDA {#a43e5a7bddfd1a0a0cc40ec84877f567d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachingDefAnalysis&amp; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::RDA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a76f229e9f5c9ffd689f6b437accb522d">AddVCTP</a>, <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a>, <a href="#ad8272d1e2af6d68d30fbd619283a68c5">ValidateLiveOuts</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### Revert {#a6663cf8ef1ff1c161b2766225b37ff1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::Revert = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a> and <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a>.</p>

</div>
</div>

### Start {#ad706c1540f91008bacbe2e3136d82f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::Start = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a491c4143dd9465fdcf8ef53386dedb1b">dump</a>, <a href="#a309a1516b668315256070f5de8849ab1">FoundAllComponents</a>, <a href="#a02d9c8ad4596ae35c6c6977dcc607e83">getLoopStartOperand</a>, <a href="#a6321a492d8cc075688ffadb330e42983">getStartOpcode</a>, <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### StartInsertBB {#a8e8e628daf61d6b19d6def1069e09517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::StartInsertBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### StartInsertPt {#a7dd8fba0b5b8837c16072bd5118559ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::StartInsertPt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a5cca05384a54726657bc35a6cc1b7f74">Validate</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### TII {#acd44549572b4e9a381dc42b0f33fa94a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMBaseInstrInfo&amp; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a>.</p>

</div>
</div>

### ToRemove {#a8a7a92727f975e4b3a7d5e536017bb56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 4&gt; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ToRemove</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### TPNumElements {#aa8a96e9cd60259f4869384d63bf8e1a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::TPNumElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a02d9c8ad4596ae35c6c6977dcc607e83">getLoopStartOperand</a>, <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### TRI {#a7b675d8b2b3a971bea89735dfdca5165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#aff890ddd726ba815dfa456b4a5b6f432">LowOverheadLoop</a> and <a href="#ad8272d1e2af6d68d30fbd619283a68c5">ValidateLiveOuts</a>.</p>

</div>
</div>

### VCTPs {#a7b77c5fddce880ca199e3eeb05665124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *, 4&gt; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::VCTPs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a76f229e9f5c9ffd689f6b437accb522d">AddVCTP</a>, <a href="#a491c4143dd9465fdcf8ef53386dedb1b">dump</a>, <a href="#a6321a492d8cc075688ffadb330e42983">getStartOpcode</a>, <a href="#a193a7893570050077d12ca10a34c0082">IsTailPredicationLegal</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

### VMOVCopies {#a9ab044db0c921289efae9050cbfc5895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 4&gt; anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::VMOVCopies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#ad8272d1e2af6d68d30fbd619283a68c5">ValidateLiveOuts</a>.</p>

</div>
</div>

### VPTstate {#aebc8576b3b90df902b31125d77f5762e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTState anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::VPTstate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#a355bbdbb545ccbb9f73dd41ca2e7790f">getVPTBlocks</a>, <a href="#afdb11d0b5d726b02916f412453587951">ValidateMVEInst</a> and <a href="#a22414e0619deaa2a695fd6d31002bb9d">ValidateTailPredicate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
