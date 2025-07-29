---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/veframelowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VEFrameLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::VEFrameLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">Target/VE/VEFrameLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about stack frame layout on the target. <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e190960cb43aef63bcf599ce16a073">VEFrameLowering</a> (const VESubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c8272ea0652d9ab75b889488f2717f">emitPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitProlog/emitEpilog - These methods insert prolog and epilog code into the function. <a href="#ab3c8272ea0652d9ab75b889488f2717f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1be113dfec8a96458235eea8ac0797f">emitEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e84300cf3bfbf40a89fdeaf965097f">emitPrologueInsns</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, uint64_t NumBytes, bool RequireFPUpdate) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae07475a5705c0ed37023fc64008c7b">emitEpilogueInsns</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, uint64_t NumBytes, bool RequireFPUpdate) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc7fee319b167f2cf6a30ac6b11dda1">eliminateCallFramePseudoInstr</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called during prolog/epilog code insertion to eliminate call frame setup and destroy pseudo instructions (but only if the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> is using them). <a href="#a5dc7fee319b167f2cf6a30ac6b11dda1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4762e4f2c447b020abc88c3bd501c407">hasBP</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8584a08557bd83d31c1c5d0a43d51f">hasGOT</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee55b75c9eb981974c109867e79c9d7f">hasReservedCallFrame</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasReservedCallFrame - Under normal circumstances, when a frame pointer is not required, we reserve argument space for call sites in the function immediately on entry to the current function. <a href="#aee55b75c9eb981974c109867e79c9d7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48cf712ec4f56aeb10dc17a7270ea33">determineCalleeSaves</a> (MachineFunction &amp;MF, BitVector &amp;SavedRegs, RegScavenger *RS=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method determines which of the registers reported by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">TargetRegisterInfo::getCalleeSavedRegs()</a> should actually get saved. <a href="#aa48cf712ec4f56aeb10dc17a7270ea33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77083d402f6deba15f8ccf39ffff370e">getFrameIndexReference</a> (const MachineFunction &amp;MF, int FI, Register &amp;FrameReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFrameIndexReference - This method should return the base register and offset used to reference a frame index location. <a href="#a77083d402f6deba15f8ccf39ffff370e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/spillslot">SpillSlot</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5439234a4280b3ec90a41a9700c5a7b4">getCalleeSavedSpillSlots</a> (unsigned &amp;NumEntries) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCalleeSavedSpillSlots - This method returns a pointer to an array of pairs, that contains an entry for each callee saved register that must be spilled to a particular stack location if it is spilled. <a href="#a5439234a4280b3ec90a41a9700c5a7b4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d1f569ffb5db8f2cbb0bc8fdf7515c">hasFPImpl</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de9124b1845b01e6911fbde53bc76f7">isLeafProc</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa119c12b7e830745658f3b6e6c3cc7e7">emitSPAdjustment</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, int64_t NumBytes, MaybeAlign MayAlign=MaybeAlign()) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a600cd89222c03117298b80e1c8c8eca9">emitSPExtend</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vesubtarget">VESubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a></td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VEFrameLowering() {#ad5e190960cb43aef63bcf599ce16a073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VEFrameLowering::VEFrameLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vesubtarget">VESubtarget</a> &amp; ST)</td>
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



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a>, <a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6a6d31b2f1e5754f5824c5dec555eeac">llvm::TargetFrameLowering::TargetFrameLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### determineCalleeSaves() {#aa48cf712ec4f56aeb10dc17a7270ea33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEFrameLowering::determineCalleeSaves (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SavedRegs, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
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


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="#a4762e4f2c447b020abc88c3bd501c407">hasBP</a>.</p>

</div>
</div>

### eliminateCallFramePseudoInstr() {#a5dc7fee319b167f2cf6a30ac6b11dda1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator VEFrameLowering::eliminateCallFramePseudoInstr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
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

<p>This method is called during prolog/epilog code insertion to eliminate call frame setup and destroy pseudo instructions (but only if the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> is using them).</p>


<p>It is responsible for eliminating these instructions, replacing them with concrete instructions. This method need only be implemented if using call frame setup/destroy pseudo instructions. Returns an iterator pointing to the instruction after the replaced one.</p>


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="#aee55b75c9eb981974c109867e79c9d7f">hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitEpilogue() {#ab1be113dfec8a96458235eea8ac0797f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEFrameLowering::emitEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a0ae07475a5705c0ed37023fc64008c7b">emitEpilogueInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### emitEpilogueInsns() {#a0ae07475a5705c0ed37023fc64008c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEFrameLowering::emitEpilogueInsns (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, uint64_t NumBytes, bool RequireFPUpdate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a4762e4f2c447b020abc88c3bd501c407">hasBP</a>, <a href="#adc8584a08557bd83d31c1c5d0a43d51f">hasGOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#ab1be113dfec8a96458235eea8ac0797f">emitEpilogue</a>.</p>

</div>
</div>

### emitPrologue() {#ab3c8272ea0652d9ab75b889488f2717f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEFrameLowering::emitPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a59e84300cf3bfbf40a89fdeaf965097f">emitPrologueInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3836203fac855ac3c5718b701bd13ffd">llvm::MachineFrameInfo::getMaxAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="#a4762e4f2c447b020abc88c3bd501c407">hasBP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae4d51e9e70d6a7fb366f2a09d10a0945">llvm::MachineFrameInfo::setStackSize</a>, <a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### emitPrologueInsns() {#a59e84300cf3bfbf40a89fdeaf965097f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEFrameLowering::emitPrologueInsns (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, uint64_t NumBytes, bool RequireFPUpdate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a4762e4f2c447b020abc88c3bd501c407">hasBP</a>, <a href="#adc8584a08557bd83d31c1c5d0a43d51f">hasGOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#ab3c8272ea0652d9ab75b889488f2717f">emitPrologue</a>.</p>

</div>
</div>

### getCalleeSavedSpillSlots() {#a5439234a4280b3ec90a41a9700c5a7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SpillSlot * llvm::VEFrameLowering::getCalleeSavedSpillSlots (unsigned &amp; NumEntries)</td>
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

<p>getCalleeSavedSpillSlots - This method returns a pointer to an array of pairs, that contains an entry for each callee saved register that must be spilled to a particular stack location if it is spilled.</p>


<p>Each entry in this array contains a &lt;register,offset&gt; pair, indicating the fixed offset from the incoming stack pointer that each register should be spilled at. If a register is not listed here, the code generator is allowed to spill it anywhere it chooses.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>.</p>

</div>
</div>

### getFrameIndexReference() {#a77083d402f6deba15f8ccf39ffff370e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset VEFrameLowering::getFrameIndexReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; FrameReg)</td>
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


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="#a4762e4f2c447b020abc88c3bd501c407">hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a> and <a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a>.</p>

</div>
</div>

### hasBP() {#a4762e4f2c447b020abc88c3bd501c407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VEFrameLowering::hasBP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="#a4abac9df111b1134c14d8cd2bd9cfece">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#aa48cf712ec4f56aeb10dc17a7270ea33">determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="#a0ae07475a5705c0ed37023fc64008c7b">emitEpilogueInsns</a>, <a href="#ab3c8272ea0652d9ab75b889488f2717f">emitPrologue</a>, <a href="#a59e84300cf3bfbf40a89fdeaf965097f">emitPrologueInsns</a> and <a href="#a77083d402f6deba15f8ccf39ffff370e">getFrameIndexReference</a>.</p>

</div>
</div>

### hasGOT() {#adc8584a08557bd83d31c1c5d0a43d51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VEFrameLowering::hasGOT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>


<p>Referenced by <a href="#a0ae07475a5705c0ed37023fc64008c7b">emitEpilogueInsns</a> and <a href="#a59e84300cf3bfbf40a89fdeaf965097f">emitPrologueInsns</a>.</p>

</div>
</div>

### hasReservedCallFrame() {#aee55b75c9eb981974c109867e79c9d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VEFrameLowering::hasReservedCallFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>hasReservedCallFrame - Under normal circumstances, when a frame pointer is not required, we reserve argument space for call sites in the function immediately on entry to the current function.</p>


<p>This eliminates the need for add/sub sp brackets around call sites. Returns true if the call frame is included as part of the stack frame.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>.</p>


<p>Referenced by <a href="#a5dc7fee319b167f2cf6a30ac6b11dda1">eliminateCallFramePseudoInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### hasFPImpl() {#aa1d1f569ffb5db8f2cbb0bc8fdf7515c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VEFrameLowering::hasFPImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitSPAdjustment() {#aa119c12b7e830745658f3b6e6c3cc7e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEFrameLowering::emitSPAdjustment (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, int64_t NumBytes, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> MayAlign=<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>

</div>
</div>

### emitSPExtend() {#a600cd89222c03117298b80e1c8c8eca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEFrameLowering::emitSPExtend (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>

</div>
</div>

### isLeafProc() {#a8de9124b1845b01e6911fbde53bc76f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VEFrameLowering::isLeafProc (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>, definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### STI {#a4abac9df111b1134c14d8cd2bd9cfece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VESubtarget&amp; llvm::VEFrameLowering::STI</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a>.</p>


<p>Referenced by <a href="#ab1be113dfec8a96458235eea8ac0797f">emitEpilogue</a>, <a href="#a0ae07475a5705c0ed37023fc64008c7b">emitEpilogueInsns</a>, <a href="#ab3c8272ea0652d9ab75b889488f2717f">emitPrologue</a>, <a href="#a59e84300cf3bfbf40a89fdeaf965097f">emitPrologueInsns</a>, <a href="#a77083d402f6deba15f8ccf39ffff370e">getFrameIndexReference</a>, <a href="#a4762e4f2c447b020abc88c3bd501c407">hasBP</a> and <a href="#ad5e190960cb43aef63bcf599ce16a073">VEFrameLowering</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-h">VEFrameLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
