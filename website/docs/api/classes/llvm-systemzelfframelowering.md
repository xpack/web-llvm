---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/systemzelfframelowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SystemZELFFrameLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SystemZELFFrameLowering { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58316b44b04618482649ecd2e7974e0">SystemZELFFrameLowering</a> (unsigned PointerSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4554341b316dd0b06a915ec883f4f74a">assignCalleeSavedSpillSlots</a> (MachineFunction &amp;MF, const TargetRegisterInfo *TRI, std::vector&lt; CalleeSavedInfo &gt; &amp;CSI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb6f3247260b906218068229b8d5b67">determineCalleeSaves</a> (MachineFunction &amp;MF, BitVector &amp;SavedRegs, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method determines which of the registers reported by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">TargetRegisterInfo::getCalleeSavedRegs()</a> should actually get saved. <a href="#a9eb6f3247260b906218068229b8d5b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e549bf3d7f691714f73696c1df480c">spillCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, ArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spillCalleeSavedRegisters - Issues instruction(s) to spill all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of store instructions via storeRegToStackSlot(). <a href="#ac0e549bf3d7f691714f73696c1df480c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d74c0d6159ac707f99c91219d0c6a5">restoreCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBII, MutableArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>restoreCalleeSavedRegisters - Issues instruction(s) to restore all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of load instructions via loadRegToStackSlot(). <a href="#a15d74c0d6159ac707f99c91219d0c6a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae45b5d3065cf62a7eac0053f27cb8103">processFunctionBeforeFrameFinalized</a> (MachineFunction &amp;MF, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processFunctionBeforeFrameFinalized - This method is called immediately before the specified function's frame layout (MF.getFrameInfo()) is finalized. <a href="#ae45b5d3065cf62a7eac0053f27cb8103">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a734b1c5c857eaef57158e8ceefb5b5ce">emitPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitProlog/emitEpilog - These methods insert prolog and epilog code into the function. <a href="#a734b1c5c857eaef57158e8ceefb5b5ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa8ef70d3b7b3f9c421b488302f563a">emitEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e80a52ee9eaf5dce1b7a90d1901d0e">inlineStackProbe</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;PrologMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a StackProbe stub (if any) with the actual probe code inline. <a href="#a61e80a52ee9eaf5dce1b7a90d1901d0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95fac1598df11a84e80e2da098dbe4b3">getFrameIndexReference</a> (const MachineFunction &amp;MF, int FI, Register &amp;FrameReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFrameIndexReference - This method should return the base register and offset used to reference a frame index location. <a href="#a95fac1598df11a84e80e2da098dbe4b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420e13f932ebcdd50a90e807d5e5674f">orderFrameObjects</a> (const MachineFunction &amp;MF, SmallVectorImpl&lt; int &gt; &amp;ObjectsToAllocate) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Order the symbols in the local stack frame. <a href="#a420e13f932ebcdd50a90e807d5e5674f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d8710804e26a041e428fb0bae67559">getRegSpillOffset</a> (MachineFunction &amp;MF, Register Reg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e53ebf2b443013c10d250085799adfc">usePackedStack</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5069e361bd482dbe05fb7373b84568a1">getBackchainOffset</a> (MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e085dd575c71a2e4deedbe9bb8e4153">getReturnAddressOffset</a> (MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23acc2efffdbd8d4592f6c70004b958a">getOrCreateFramePointerSaveIndex</a> (MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639478d440d115bb94fd83bf9054da98">hasFPImpl</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eda57e81e0d9eff1dac4b2f91a5b347">RegSpillOffsets</a></td>
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


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZELFFrameLowering() {#ad58316b44b04618482649ecd2e7974e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZELFFrameLowering::SystemZELFFrameLowering (unsigned PointerSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ad2976f679b52f9eb2463970555bd8853">llvm::SystemZFrameLowering::SystemZFrameLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignCalleeSavedSpillSlots() {#a4554341b316dd0b06a915ec883f4f74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZELFFrameLowering::assignCalleeSavedSpillSlots (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#ab58bf05e46b0dbaad61b7a7e66a73758">llvm::SystemZ::ELFArgGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a6b61566754b11f0948d412edeebd7237">llvm::SystemZMC::ELFCallFrameSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#adbb3aafa6e9294472bd94ff65ccfa355">llvm::SystemZ::ELFNumArgGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a>, <a href="#ad7d8710804e26a041e428fb0bae67559">getRegSpillOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a2a086e3b69a693c18fb475e2bbdaed02">llvm::SystemZMachineFunctionInfo::getVarArgsFirstGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a873676551ca13a3c6967138405521074">llvm::SystemZMachineFunctionInfo::setRestoreGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#ab5ed9336b0baada4e0af52364a3168ce">llvm::SystemZMachineFunctionInfo::setSpillGPRRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="#a9e53ebf2b443013c10d250085799adfc">usePackedStack</a>.</p>

</div>
</div>

### determineCalleeSaves() {#a9eb6f3247260b906218068229b8d5b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZELFFrameLowering::determineCalleeSaves (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SavedRegs, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#ab58bf05e46b0dbaad61b7a7e66a73758">llvm::SystemZ::ELFArgGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#adbb3aafa6e9294472bd94ff65ccfa355">llvm::SystemZ::ELFNumArgGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a2a086e3b69a693c18fb475e2bbdaed02">llvm::SystemZMachineFunctionInfo::getVarArgsFirstGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### emitEpilogue() {#a8aa8ef70d3b7b3f9c421b488302f563a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZELFFrameLowering::emitEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a42e9dc89bad4c86a456b5215547bca72">llvm::SystemZMachineFunctionInfo::getRestoreGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a0f113efcd05970b283ecc2cd99a91379">llvm::SystemZ::GPRRegs::LowGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitPrologue() {#a734b1c5c857eaef57158e8ceefb5b5ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZELFFrameLowering::emitPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab08619b14fe0d6edc17b186c5a452e9e">buildCFAOffs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a28391c59e5f478e4513f021226549734">buildDefCFAReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a6a60a82f8cb445e9e7029e38733b2d30">llvm::MCCFIInstruction::createOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a6b61566754b11f0948d412edeebd7237">llvm::SystemZMC::ELFCallFrameSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a83f02207faff8f50e2fec3a8b2c7e383">llvm::SystemZMC::ELFCFAOffsetFromInitialSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="#a5069e361bd482dbe05fb7373b84568a1">getBackchainOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="#a95fac1598df11a84e80e2da098dbe4b3">getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a14dcf0fbd3cd8fd45c8f5e915ddfaead">llvm::SystemZSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac51e2d34abb79b72afef355fac525c76">llvm::MachineFrameInfo::getObjectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#aa701312e2d05a863767f777851aebb0e">llvm::SystemZMachineFunctionInfo::getSpillGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6196c0b2b70e295635d88295247ad98c">llvm::SystemZSubtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a864aaacf976eb30999ce0d740e5657a5">llvm::SystemZ::GPRRegs::GPROffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab9d041119cb005797a695c6ba89a7657">llvm::TargetLoweringBase::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af5302d38d9a16eee93f13a1579c8773d">llvm::MachineFrameInfo::isDeadObjectIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a0f113efcd05970b283ecc2cd99a91379">llvm::SystemZ::GPRRegs::LowGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae4d51e9e70d6a7fb366f2a09d10a0945">llvm::MachineFrameInfo::setStackSize</a>.</p>

</div>
</div>

### getBackchainOffset() {#a5069e361bd482dbe05fb7373b84568a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZELFFrameLowering::getBackchainOffset (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a6b61566754b11f0948d412edeebd7237">llvm::SystemZMC::ELFCallFrameSize</a> and <a href="#a9e53ebf2b443013c10d250085799adfc">usePackedStack</a>.</p>


<p>Referenced by <a href="#a734b1c5c857eaef57158e8ceefb5b5ce">emitPrologue</a>, <a href="#a23acc2efffdbd8d4592f6c70004b958a">getOrCreateFramePointerSaveIndex</a> and <a href="#a61e80a52ee9eaf5dce1b7a90d1901d0e">inlineStackProbe</a>.</p>

</div>
</div>

### getFrameIndexReference() {#a95fac1598df11a84e80e2da098dbe4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset SystemZELFFrameLowering::getFrameIndexReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; FrameReg)</td>
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

<p>getFrameIndexReference - This method should return the base register and offset used to reference a frame index location.</p>


<p>Returns the displacement from the frame register to the stack frame of the specified index, along with the frame register used (in output arg FrameReg).</p>


<p>The offset is returned directly, and the base register is returned via FrameReg.</p>


<p>This is the default implementation which is overridden for some targets.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a6b61566754b11f0948d412edeebd7237">llvm::SystemZMC::ELFCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#af88a8f2328543f94aea3ba85d954fafa">llvm::TargetFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a734b1c5c857eaef57158e8ceefb5b5ce">emitPrologue</a>.</p>

</div>
</div>

### getOrCreateFramePointerSaveIndex() {#a23acc2efffdbd8d4592f6c70004b958a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SystemZELFFrameLowering::getOrCreateFramePointerSaveIndex (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a6b61566754b11f0948d412edeebd7237">llvm::SystemZMC::ELFCallFrameSize</a>, <a href="#a5069e361bd482dbe05fb7373b84568a1">getBackchainOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a30879ff6117981879b395426d14e4f1a">llvm::SystemZMachineFunctionInfo::getFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a910a3701ca0348c12618adbf52d9d822">llvm::SystemZMachineFunctionInfo::setFramePointerSaveIndex</a>.</p>


<p>Referenced by <a href="#ae45b5d3065cf62a7eac0053f27cb8103">processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### getRegSpillOffset() {#ad7d8710804e26a041e428fb0bae67559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SystemZELFFrameLowering::getRegSpillOffset (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a9e53ebf2b443013c10d250085799adfc">usePackedStack</a>.</p>


<p>Referenced by <a href="#a4554341b316dd0b06a915ec883f4f74a">assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### getReturnAddressOffset() {#a8e085dd575c71a2e4deedbe9bb8e4153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SystemZELFFrameLowering::getReturnAddressOffset (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a> and <a href="#a9e53ebf2b443013c10d250085799adfc">usePackedStack</a>.</p>

</div>
</div>

### inlineStackProbe() {#a61e80a52ee9eaf5dce1b7a90d1901d0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZELFFrameLowering::inlineStackProbe (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PrologueMBB)</td>
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

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab08619b14fe0d6edc17b186c5a452e9e">buildCFAOffs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a28391c59e5f478e4513f021226549734">buildDefCFAReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a47bab903d4239eca9c0ad8b19126a3d8">llvm::SystemZ::CCMASK_CMP_GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a85e05170e3e584f721ea86c6b04edaba">llvm::SystemZ::CCMASK_ICMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a6b61566754b11f0948d412edeebd7237">llvm::SystemZMC::ELFCallFrameSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a83f02207faff8f50e2fec3a8b2c7e383">llvm::SystemZMC::ELFCFAOffsetFromInitialSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a643c44e66aa189f635b59361c6e80179">llvm::SystemZ::emitBlockAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee5f6b149b3f5ee5ed6ad7db9b58b148">llvm::fullyRecomputeLiveIns</a>, <a href="#a5069e361bd482dbe05fb7373b84568a1">getBackchainOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a6196c0b2b70e295635d88295247ad98c">llvm::SystemZSubtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a175299250e6f7f5542fb5474ff0c9c6a">llvm::SystemZ::splitBlockBefore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>

</div>
</div>

### orderFrameObjects() {#a420e13f932ebcdd50a90e807d5e5674f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZELFFrameLowering::orderFrameObjects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; objectsToAllocate)</td>
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

<p>Order the symbols in the local stack frame.</p>


<p>The list of objects that we want to order is in <span class="doxyComputerOutput">objectsToAllocate</span> as indices into the <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a>. The array can be reordered in any way upon return. The contents of the array, however, may not be modified (i.e. only their order may be changed). By default, just maintain the original order.</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac51e2d34abb79b72afef355fac525c76">llvm::MachineFrameInfo::getObjectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzii/#af95a60521e541cc7a0f27971c1e83a3aa17cc0ecc83840b2e4f8c76252da98a58">llvm::SystemZII::Has20BitOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### processFunctionBeforeFrameFinalized() {#ae45b5d3065cf62a7eac0053f27cb8103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZELFFrameLowering::processFunctionBeforeFrameFinalized (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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


<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#aecaae26e25f7f952810d98e50264b5fb">llvm::RegScavenger::addScavengingFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a61960903871aa95a7161074c6f1eec8f">llvm::MachineFrameInfo::CreateSpillStackObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a6b61566754b11f0948d412edeebd7237">llvm::SystemZMC::ELFCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a66046fdf8661d5276f951337b0cf892d">llvm::MachineFrameInfo::estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae70474766f2a88bab5b2b77bcb22212b">llvm::MachineFrameInfo::getObjectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="#a23acc2efffdbd8d4592f6c70004b958a">getOrCreateFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#ab9bcc44f982f5988daba81dc6368c184">llvm::SystemZFrameLowering::getPointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a42e9dc89bad4c86a456b5215547bca72">llvm::SystemZMachineFunctionInfo::getRestoreGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af9745f59d6647bd43f9f7959ca1a9971">llvm::MachineBasicBlock::isLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a0f113efcd05970b283ecc2cd99a91379">llvm::SystemZ::GPRRegs::LowGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#a9e53ebf2b443013c10d250085799adfc">usePackedStack</a>.</p>

</div>
</div>

### restoreCalleeSavedRegisters() {#a15d74c0d6159ac707f99c91219d0c6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZELFFrameLowering::restoreCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a42e9dc89bad4c86a456b5215547bca72">llvm::SystemZMachineFunctionInfo::getRestoreGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a864aaacf976eb30999ce0d740e5657a5">llvm::SystemZ::GPRRegs::GPROffset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a5e605731741359de2b6b05844f8e61db">llvm::SystemZ::GPRRegs::HighGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a0f113efcd05970b283ecc2cd99a91379">llvm::SystemZ::GPRRegs::LowGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### spillCalleeSavedRegisters() {#ac0e549bf3d7f691714f73696c1df480c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZELFFrameLowering::spillCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ad0da681a52b5ef146c8a106fe63ded93">addSavedGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#ab58bf05e46b0dbaad61b7a7e66a73758">llvm::SystemZ::ELFArgGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#adbb3aafa6e9294472bd94ff65ccfa355">llvm::SystemZ::ELFNumArgGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#aa701312e2d05a863767f777851aebb0e">llvm::SystemZMachineFunctionInfo::getSpillGPRRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a2a086e3b69a693c18fb475e2bbdaed02">llvm::SystemZMachineFunctionInfo::getVarArgsFirstGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a864aaacf976eb30999ce0d740e5657a5">llvm::SystemZ::GPRRegs::GPROffset</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a5e605731741359de2b6b05844f8e61db">llvm::SystemZ::GPRRegs::HighGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>, <a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs/#a0f113efcd05970b283ecc2cd99a91379">llvm::SystemZ::GPRRegs::LowGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### usePackedStack() {#a9e53ebf2b443013c10d250085799adfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZELFFrameLowering::usePackedStack (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a4554341b316dd0b06a915ec883f4f74a">assignCalleeSavedSpillSlots</a>, <a href="#a5069e361bd482dbe05fb7373b84568a1">getBackchainOffset</a>, <a href="#ad7d8710804e26a041e428fb0bae67559">getRegSpillOffset</a>, <a href="#a8e085dd575c71a2e4deedbe9bb8e4153">getReturnAddressOffset</a> and <a href="#ae45b5d3065cf62a7eac0053f27cb8103">processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### hasFPImpl() {#a639478d440d115bb94fd83bf9054da98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZELFFrameLowering::hasFPImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>, definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RegSpillOffsets {#a8eda57e81e0d9eff1dac4b2f91a5b347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;unsigned&gt; llvm::SystemZELFFrameLowering::RegSpillOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-h">SystemZFrameLowering.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
