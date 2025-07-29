---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regscavenger
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegScavenger` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RegScavenger { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">llvm/CodeGen/RegisterScavenging.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9793ceec475b244641f3ed7294d3d0">RegScavenger</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349def858d7ff22474b3f9013486807f">assignRegToScavengingIndex</a> (int FI, Register Reg, MachineInstr *Restore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> that <span class="doxyComputerOutput">Reg</span> is in use at scavenging index <span class="doxyComputerOutput">FI</span>. <a href="#a349def858d7ff22474b3f9013486807f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f1af6e587ae8846628561570b54e2ee">enterBasicBlock</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start tracking liveness from the begin of basic block <span class="doxyComputerOutput">MBB</span>. <a href="#a4f1af6e587ae8846628561570b54e2ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14812153b6cf8c1cb26c3de8b96ba91c">enterBasicBlockEnd</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start tracking liveness from the end of basic block <span class="doxyComputerOutput">MBB</span>. <a href="#a14812153b6cf8c1cb26c3de8b96ba91c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a44764b1c5681c8fb057f13b3f30047">backward</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update internal register state and move MBB iterator backwards. <a href="#a4a44764b1c5681c8fb057f13b3f30047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141a7cc4eaf09030c0f17b68f7445ffc">backward</a> (MachineBasicBlock::iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call <a href="#a4a44764b1c5681c8fb057f13b3f30047">backward()</a> to update internal register state to just before <span class="doxyComputerOutput">*I</span>. <a href="#a141a7cc4eaf09030c0f17b68f7445ffc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27037167fddcdde3b6207d025267bbfc">isRegUsed</a> (Register Reg, bool includeReserved=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if a specific register is currently used. <a href="#a27037167fddcdde3b6207d025267bbfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf92711851d9d2abd2ef7f6c1b68bf8">getRegsAvailable</a> (const TargetRegisterClass *RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all available registers in the register class in Mask. <a href="#afaf92711851d9d2abd2ef7f6c1b68bf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28849ec4920f5ee3f97d344633e695f4">FindUnusedReg</a> (const TargetRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find an unused register of the specified register class. <a href="#a28849ec4920f5ee3f97d344633e695f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecaae26e25f7f952810d98e50264b5fb">addScavengingFrameIndex</a> (int FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a scavenging frame index. <a href="#aecaae26e25f7f952810d98e50264b5fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a0ed0e83e8058a1594c9bb6e9678cc">isScavengingFrameIndex</a> (int FI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query whether a frame index is a scavenging frame index. <a href="#a82a0ed0e83e8058a1594c9bb6e9678cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826f99fb1aca624d8a7d61d511c3960b">getScavengingFrameIndices</a> (SmallVectorImpl&lt; int &gt; &amp;A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an array of scavenging frame indices. <a href="#a826f99fb1aca624d8a7d61d511c3960b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d08c8303092539ecb1fde389108e7a">scavengeRegisterBackwards</a> (const TargetRegisterClass &amp;RC, MachineBasicBlock::iterator To, bool RestoreAfter, int SPAdj, bool AllowSpill=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make a register of the specific register class available from the current position backwards to the place before <span class="doxyComputerOutput">To</span>. <a href="#a62d08c8303092539ecb1fde389108e7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34542ec002baa6b027a6d05644c6bb2e">setRegUsed</a> (Register Reg, LaneBitmask LaneMask=LaneBitmask::getAll())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tell the scavenger a register is used. <a href="#a34542ec002baa6b027a6d05644c6bb2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fd6bedfd5f59208b06d0c1de8f0539">isReserved</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a register is reserved. It is never "unused". <a href="#a97fd6bedfd5f59208b06d0c1de8f0539">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ed991248853d083b7ccbe6e26ec021">init</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize RegisterScavenger. <a href="#a54ed991248853d083b7ccbe6e26ec021">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ScavengedInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321eac3fed6b98ad50c1695ad13cd51f">spill</a> (Register Reg, const TargetRegisterClass &amp;RC, int SPAdj, MachineBasicBlock::iterator Before, MachineBasicBlock::iterator &amp;UseMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Spill a register after position <span class="doxyComputerOutput">After</span> and reload it before position <span class="doxyComputerOutput">UseMI</span>. <a href="#a321eac3fed6b98ad50c1695ad13cd51f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94fb19af4f2d733c6c0478a164eb23bd">TRI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ec6a230015884ad6f8f466546fd23a">TII</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab8eef969e9bfe54c36310fc773774f">MRI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd21a7041e94c6a6d4b512e59bb423a3">MBB</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4727723e389fc2d7c57a641f58c5935e">MBBI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; ScavengedInfo, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70399f48c5869c0f05e350a6255dff5">Scavenged</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A vector of information on scavenged registers. <a href="#ae70399f48c5869c0f05e350a6255dff5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9485c904255ac13374fce12b26dccec9">LiveUnits</a></td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegScavenger() {#acd9793ceec475b244641f3ed7294d3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegScavenger::RegScavenger ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addScavengingFrameIndex() {#aecaae26e25f7f952810d98e50264b5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegScavenger::addScavengingFrameIndex (int FI)</td>
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

<p>Add a scavenging frame index.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a878a2b864e18e3d074d75b426ea7912d">llvm::HexagonFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a27b8c40891bfea8db2ad3b9fa25cba0f">llvm::MipsSEFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a230b654eb7319d9e7a6d9d62afa2d5f8">llvm::ARCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a822d4e9a00115ac2bc39355157e84ead">llvm::LoongArchFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#ad1c7f63bd41f376ebc594e3f8440d1ad">llvm::XCoreFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a0c261e12c68fb10f3ab5532c07ad30c9">llvm::XtensaFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### assignRegToScavengingIndex() {#a349def858d7ff22474b3f9013486807f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegScavenger::assignRegToScavengingIndex (int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Restore=nullptr)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> that <span class="doxyComputerOutput">Reg</span> is in use at scavenging index <span class="doxyComputerOutput">FI</span>.</p>


<p>This is for targets which need to directly manage the spilling process, and need to update the scavenger's internal state. It's expected this be called a second time with <span class="doxyComputerOutput">Restore</span> set to a non-null value, so that the externally inserted restore instruction resets the scavenged slot liveness when encountered.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### backward() {#a4a44764b1c5681c8fb057f13b3f30047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegScavenger::backward ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update internal register state and move MBB iterator backwards.</p>


<p>This method gives precise results even in the absence of kill flags.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="#a141a7cc4eaf09030c0f17b68f7445ffc">backward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#acd22577c1abdac8d676fc8dc30e7c223">llvm::Mips16InstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>.</p>

</div>
</div>

### backward() {#a141a7cc4eaf09030c0f17b68f7445ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegScavenger::backward (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I)</td>
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

<p>Call <a href="#a4a44764b1c5681c8fb057f13b3f30047">backward()</a> to update internal register state to just before <span class="doxyComputerOutput">*I</span>.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>


<p>References <a href="#a4a44764b1c5681c8fb057f13b3f30047">backward</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### enterBasicBlock() {#a4f1af6e587ae8846628561570b54e2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegScavenger::enterBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start tracking liveness from the begin of basic block <span class="doxyComputerOutput">MBB</span>.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#af6c7d3374923da4e91bd8cdfd0d7f599">llvm::RISCVFrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>.</p>

</div>
</div>

### enterBasicBlockEnd() {#a14812153b6cf8c1cb26c3de8b96ba91c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegScavenger::enterBasicBlockEnd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start tracking liveness from the end of basic block <span class="doxyComputerOutput">MBB</span>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="#a4a44764b1c5681c8fb057f13b3f30047">backward()</a> to move towards the beginning of the block.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#acd22577c1abdac8d676fc8dc30e7c223">llvm::Mips16InstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>.</p>

</div>
</div>

### FindUnusedReg() {#a28849ec4920f5ee3f97d344633e695f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register RegScavenger::FindUnusedReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find an unused register of the specified register class.</p>


<p>Return 0 if none is found.</p>


<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a27037167fddcdde3b6207d025267bbfc">isRegUsed</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>.</p>

</div>
</div>

### getRegsAvailable() {#afaf92711851d9d2abd2ef7f6c1b68bf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector RegScavenger::getRegsAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all available registers in the register class in Mask.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>Reference <a href="#a27037167fddcdde3b6207d025267bbfc">isRegUsed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#acd22577c1abdac8d676fc8dc30e7c223">llvm::Mips16InstrInfo::loadImmediate</a>.</p>

</div>
</div>

### getScavengingFrameIndices() {#a826f99fb1aca624d8a7d61d511c3960b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegScavenger::getScavengingFrameIndices (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; A)</td>
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

<p>Get an array of scavenging frame indices.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isRegUsed() {#a27037167fddcdde3b6207d025267bbfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegScavenger::isRegUsed (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool includeReserved=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return if a specific register is currently used.</p>

<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#af6c7d3374923da4e91bd8cdfd0d7f599">llvm::RISCVFrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="#a28849ec4920f5ee3f97d344633e695f4">FindUnusedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aed0535a6ce0e4e5969a60a1635d0b18a">llvm::SIInstrInfo::getAddNoCarry</a>, <a href="#afaf92711851d9d2abd2ef7f6c1b68bf8">getRegsAvailable</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>.</p>

</div>
</div>

### isScavengingFrameIndex() {#a82a0ed0e83e8058a1594c9bb6e9678cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegScavenger::isScavengingFrameIndex (int FI)</td>
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

<p>Query whether a frame index is a scavenging frame index.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a6f318a4b1d38e66b324c0748304e60de">llvm::ARMBaseRegisterInfo::eliminateFrameIndex</a> and <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

### scavengeRegisterBackwards() {#a62d08c8303092539ecb1fde389108e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register RegScavenger::scavengeRegisterBackwards (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> To, bool RestoreAfter, int SPAdj, bool AllowSpill=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make a register of the specific register class available from the current position backwards to the place before <span class="doxyComputerOutput">To</span>.</p>


<p>If <span class="doxyComputerOutput">RestoreAfter</span> is true this includes the instruction following the current position. SPAdj is the stack adjustment due to call frame, it's passed along to eliminateFrameIndex(). Returns the scavenged register.</p>


<p>If <span class="doxyComputerOutput">AllowSpill</span> is false, fail if a spill is required to make the register available, and return NoRegister.</p>


<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a989e26280ba069ba20dd83144c3bd31a">findSurvivorBackwards</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#afbf6359290d600a6fbc13f6370dc45ba">llvm::TargetRegisterClass::getRawAllocationOrder</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aed0535a6ce0e4e5969a60a1635d0b18a">llvm::SIInstrInfo::getAddNoCarry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a1b25635def2844fb5e6c8a79f3af0a6c">InsertFPConstInst</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#ae88297df93601a3a0929300e6a6b58d7">InsertSPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a176bfede6f24b05b428c0f42f9d95390">scavengeVReg</a>.</p>

</div>
</div>

### setRegUsed() {#a34542ec002baa6b027a6d05644c6bb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegScavenger::setRegUsed (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=<a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">LaneBitmask::getAll</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tell the scavenger a register is used.</p>

<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a1b25635def2844fb5e6c8a79f3af0a6c">InsertFPConstInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#ae88297df93601a3a0929300e6a6b58d7">InsertSPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### init() {#a54ed991248853d083b7ccbe6e26ec021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegScavenger::init (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize RegisterScavenger.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>

</div>
</div>

### isReserved() {#a97fd6bedfd5f59208b06d0c1de8f0539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegScavenger::isReserved (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Returns true if a register is reserved. It is never "unused".</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

### spill() {#a321eac3fed6b98ad50c1695ad13cd51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegScavenger::ScavengedInfo &amp; RegScavenger::spill (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, int SPAdj, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Before, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; UseMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Spill a register after position <span class="doxyComputerOutput">After</span> and reload it before position <span class="doxyComputerOutput">UseMI</span>.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LiveUnits {#a9485c904255ac13374fce12b26dccec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegUnits llvm::RegScavenger::LiveUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

### MBB {#acd21a7041e94c6a6d4b512e59bb423a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::RegScavenger::MBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

### MBBI {#a4727723e389fc2d7c57a641f58c5935e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::RegScavenger::MBBI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

### MRI {#acab8eef969e9bfe54c36310fc773774f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::RegScavenger::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

### Scavenged {#ae70399f48c5869c0f05e350a6255dff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ScavengedInfo, 2&gt; llvm::RegScavenger::Scavenged</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A vector of information on scavenged registers.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

### TII {#a41ec6a230015884ad6f8f466546fd23a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::RegScavenger::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

### TRI {#a94fb19af4f2d733c6c0478a164eb23bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::RegScavenger::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">RegisterScavenging.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp">RegisterScavenging.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
