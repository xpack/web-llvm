---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/systemzxplinkframelowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SystemZXPLINKFrameLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SystemZXPLINKFrameLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">Target/SystemZ/SystemZFrameLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/systemzframelowering">SystemZFrameLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcdc2077c9cfc6b08d447fc27020702">SystemZXPLINKFrameLowering</a> (unsigned PointerSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8195925dae80a73b2c6101290b5962b">assignCalleeSavedSpillSlots</a> (MachineFunction &amp;MF, const TargetRegisterInfo *TRI, std::vector&lt; CalleeSavedInfo &gt; &amp;CSI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2560d194f394dd45de1fa04505061ae">determineCalleeSaves</a> (MachineFunction &amp;MF, BitVector &amp;SavedRegs, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method determines which of the registers reported by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">TargetRegisterInfo::getCalleeSavedRegs()</a> should actually get saved. <a href="#ae2560d194f394dd45de1fa04505061ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db07f97c8d52e506e689b789b231f0c">spillCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, ArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spillCalleeSavedRegisters - Issues instruction(s) to spill all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of store instructions via storeRegToStackSlot(). <a href="#a9db07f97c8d52e506e689b789b231f0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d043cad28262fefa366ecc64c9591f1">restoreCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBII, MutableArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>restoreCalleeSavedRegisters - Issues instruction(s) to restore all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of load instructions via loadRegToStackSlot(). <a href="#a3d043cad28262fefa366ecc64c9591f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd38718f81e97d49ac056306d2efbab">emitEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cebd1e96489b04d18f2a7c39c250f8">emitPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitProlog/emitEpilog - These methods insert prolog and epilog code into the function. <a href="#a58cebd1e96489b04d18f2a7c39c250f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f79e8cb7551ca57450108d9816b2ba">inlineStackProbe</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;PrologMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a StackProbe stub (if any) with the actual probe code inline. <a href="#a35f79e8cb7551ca57450108d9816b2ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8f0ca7af8321ea32072c40fe93619e">processFunctionBeforeFrameFinalized</a> (MachineFunction &amp;MF, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processFunctionBeforeFrameFinalized - This method is called immediately before the specified function's frame layout (MF.getFrameInfo()) is finalized. <a href="#acd8f0ca7af8321ea32072c40fe93619e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6447282533aad4f054c9bfcf8df8028f">determineFrameLayout</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013e15990830b9ac4d1e6e1c7405a94c">getBackchainOffset</a> (MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8dbd1fe5c383d82e680f0d42db7f6ba">getReturnAddressOffset</a> (MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f850288e925f301a01218710e88254">getOrCreateFramePointerSaveIndex</a> (MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845c852c1b1e54f803079f5b52a5319c">hasFPImpl</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41a1f75dda8a0388533a02c31213131">RegSpillOffsets</a></td>
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


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZXPLINKFrameLowering() {#a7bcdc2077c9cfc6b08d447fc27020702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZXPLINKFrameLowering::SystemZXPLINKFrameLowering (unsigned PointerSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ad2976f679b52f9eb2463970555bd8853">llvm::SystemZFrameLowering::SystemZFrameLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignCalleeSavedSpillSlots() {#af8195925dae80a73b2c6101290b5962b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZXPLINKFrameLowering::assignCalleeSavedSpillSlots (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad2270087c6b8d7061c3a5e83fb61c0a6">llvm::MachineFrameInfo::CreateFixedSpillStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a30879ff6117981879b395426d14e4f1a">llvm::SystemZMachineFunctionInfo::getFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6df2e6b0780053d3aef7a82c6ac2198c">llvm::SystemZSubtarget::getSpecialRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab7e47514d5ce433432975dac4df8e7e7">isXPLeafCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a7d111d4b9003a9aab4efe813d03777b6">llvm::TargetStackID::NoAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a873676551ca13a3c6967138405521074">llvm::SystemZMachineFunctionInfo::setRestoreGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#ab5ed9336b0baada4e0af52364a3168ce">llvm::SystemZMachineFunctionInfo::setSpillGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a6ba514594eb802f087046edbe201f8f4">llvm::MachineFrameInfo::setStackID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### determineCalleeSaves() {#ae2560d194f394dd45de1fa04505061ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZXPLINKFrameLowering::determineCalleeSaves (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SavedRegs, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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

<p>This method determines which of the registers reported by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">TargetRegisterInfo::getCalleeSavedRegs()</a> should actually get saved.</p>


<p>The default implementation checks populates the <span class="doxyComputerOutput">SavedRegs</span> bitset with all registers which are modified in the function, targets may override this function to save additional registers. This method also sets up the register scavenger ensuring there is a free register or a frameindex available. This method should not be called by any passes outside of PEI, because it may change state passed in by <span class="doxyComputerOutput">MF</span> and <span class="doxyComputerOutput">RS</span>. The preferred interface outside PEI is getCalleeSaves.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6df2e6b0780053d3aef7a82c6ac2198c">llvm::SystemZSubtarget::getSpecialRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>.</p>

</div>
</div>

### determineFrameLayout() {#a6447282533aad4f054c9bfcf8df8028f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZXPLINKFrameLowering::determineFrameLayout (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae70474766f2a88bab5b2b77bcb22212b">llvm::MachineFrameInfo::getObjectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6df2e6b0780053d3aef7a82c6ac2198c">llvm::SystemZSubtarget::getSpecialRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a7d111d4b9003a9aab4efe813d03777b6">llvm::TargetStackID::NoAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3cd29e7edbcaceb5834eaa7d089a5bc4">llvm::MachineFrameInfo::setObjectOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae4d51e9e70d6a7fb366f2a09d10a0945">llvm::MachineFrameInfo::setStackSize</a>.</p>


<p>Referenced by <a href="#a58cebd1e96489b04d18f2a7c39c250f8">emitPrologue</a>.</p>

</div>
</div>

### emitEpilogue() {#a4bd38718f81e97d49ac056306d2efbab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZXPLINKFrameLowering::emitEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a14dcf0fbd3cd8fd45c8f5e915ddfaead">llvm::SystemZSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a42e9dc89bad4c86a456b5215547bca72">llvm::SystemZMachineFunctionInfo::getRestoreGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6df2e6b0780053d3aef7a82c6ac2198c">llvm::SystemZSubtarget::getSpecialRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a0f113efcd05970b283ecc2cd99a91379">llvm::SystemZ::GPRRegs::LowGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>.</p>

</div>
</div>

### emitPrologue() {#a58cebd1e96489b04d18f2a7c39c250f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZXPLINKFrameLowering::emitPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>emitProlog/emitEpilog - These methods insert prolog and epilog code into the function.</p>

<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="#a6447282533aad4f054c9bfcf8df8028f">determineFrameLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a14dcf0fbd3cd8fd45c8f5e915ddfaead">llvm::SystemZSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6521d4d5560c03b2e6490883558b882c">llvm::TargetFrameLowering::getOffsetOfLocalArea</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6df2e6b0780053d3aef7a82c6ac2198c">llvm::SystemZSubtarget::getSpecialRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#af7c04579e3a921c01f95cb27f2ab243e">llvm::SystemZ::XPLINK64ArgGPRs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a880191f32861e3017b27d79724a2f270">llvm::SystemZ::XPLINK64NumArgGPRs</a>.</p>

</div>
</div>

### getBackchainOffset() {#a013e15990830b9ac4d1e6e1c7405a94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZXPLINKFrameLowering::getBackchainOffset (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>

</div>
</div>

### getOrCreateFramePointerSaveIndex() {#a44f850288e925f301a01218710e88254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SystemZXPLINKFrameLowering::getOrCreateFramePointerSaveIndex (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a30879ff6117981879b395426d14e4f1a">llvm::SystemZMachineFunctionInfo::getFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a7d111d4b9003a9aab4efe813d03777b6">llvm::TargetStackID::NoAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a910a3701ca0348c12618adbf52d9d822">llvm::SystemZMachineFunctionInfo::setFramePointerSaveIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a6ba514594eb802f087046edbe201f8f4">llvm::MachineFrameInfo::setStackID</a>.</p>

</div>
</div>

### getReturnAddressOffset() {#aa8dbd1fe5c383d82e680f0d42db7f6ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SystemZXPLINKFrameLowering::getReturnAddressOffset (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a>.</p>

</div>
</div>

### inlineStackProbe() {#a35f79e8cb7551ca57450108d9816b2ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZXPLINKFrameLowering::inlineStackProbe (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PrologueMBB)</td>
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

<p>Replace a StackProbe stub (if any) with the actual probe code inline.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#ac16fd1071e402b10701ff234436a9054">llvm::SystemZ::CCMASK_CMP_LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a85e05170e3e584f721ea86c6b04edaba">llvm::SystemZ::CCMASK_ICMP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee5f6b149b3f5ee5ed6ad7db9b58b148">llvm::fullyRecomputeLiveIns</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af9745f59d6647bd43f9f7959ca1a9971">llvm::MachineBasicBlock::isLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a70b0525ecc6022336feb019ff63c934c">llvm::MachineFunction::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a175299250e6f7f5542fb5474ff0c9c6a">llvm::SystemZ::splitBlockBefore</a>.</p>

</div>
</div>

### processFunctionBeforeFrameFinalized() {#acd8f0ca7af8321ea32072c40fe93619e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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

<p>processFunctionBeforeFrameFinalized - This method is called immediately before the specified function's frame layout (MF.getFrameInfo()) is finalized.</p>


<p>Once the frame is finalized, MO_FrameIndex operands are replaced with direct constants. This method is optional.</p>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1455 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#aecaae26e25f7f952810d98e50264b5fb">llvm::RegScavenger::addScavengingFrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a61960903871aa95a7161074c6f1eec8f">llvm::MachineFrameInfo::CreateSpillStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a66046fdf8661d5276f951337b0cf892d">llvm::MachineFrameInfo::estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a4f335273c28b17552a7cfd802f42be2a">llvm::MachineFrameInfo::getMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae70474766f2a88bab5b2b77bcb22212b">llvm::MachineFrameInfo::getObjectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6df2e6b0780053d3aef7a82c6ac2198c">llvm::SystemZSubtarget::getSpecialRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a02a7503d1af1782b35b3683e173cb5f0">llvm::MachineFrameInfo::setMaxCallFrameSize</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af941923e75bebb485321894b2ddbeb0a">llvm::MachineFrameInfo::setOffsetAdjustment</a>.</p>

</div>
</div>

### restoreCalleeSavedRegisters() {#a3d043cad28262fefa366ecc64c9591f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>restoreCalleeSavedRegisters - Issues instruction(s) to restore all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of load instructions via loadRegToStackSlot().</p>


<p>If it returns true, and any of the registers in CSI is not restored, it sets the corresponding Restored flag in CSI to false. Returns false otherwise.</p>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a42e9dc89bad4c86a456b5215547bca72">llvm::SystemZMachineFunctionInfo::getRestoreGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a864aaacf976eb30999ce0d740e5657a5">llvm::SystemZ::GPRRegs::GPROffset</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a5e605731741359de2b6b05844f8e61db">llvm::SystemZ::GPRRegs::HighGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a0f113efcd05970b283ecc2cd99a91379">llvm::SystemZ::GPRRegs::LowGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### spillCalleeSavedRegisters() {#a9db07f97c8d52e506e689b789b231f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZXPLINKFrameLowering::spillCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>spillCalleeSavedRegisters - Issues instruction(s) to spill all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of store instructions via storeRegToStackSlot().</p>


<p>Returns false otherwise.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ad0da681a52b5ef146c8a106fe63ded93">addSavedGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#aa701312e2d05a863767f777851aebb0e">llvm::SystemZMachineFunctionInfo::getSpillGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### hasFPImpl() {#a845c852c1b1e54f803079f5b52a5319c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZXPLINKFrameLowering::hasFPImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 1451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RegSpillOffsets {#ab41a1f75dda8a0388533a02c31213131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;unsigned&gt; llvm::SystemZXPLINKFrameLowering::RegSpillOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
