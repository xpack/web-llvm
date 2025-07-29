---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvframelowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RISCVFrameLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVFrameLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">Target/RISCV/RISCVFrameLowering.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af893429fa90ab18cd29ed194fd04fdf6">RISCVFrameLowering</a> (const RISCVSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131316d63f21b59d27d82ae95b91bfc7">emitPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitProlog/emitEpilog - These methods insert prolog and epilog code into the function. <a href="#a131316d63f21b59d27d82ae95b91bfc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa587d71d9d14ad035e31b99fc0c90802">emitEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc745007e032dc7daac0eb03fbd9f0f1">getStackSizeWithRVVPadding</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9258a9f50df17d6b3c064af9bf06c2bf">getFrameIndexReference</a> (const MachineFunction &amp;MF, int FI, Register &amp;FrameReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFrameIndexReference - This method should return the base register and offset used to reference a frame index location. <a href="#a9258a9f50df17d6b3c064af9bf06c2bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e3cf793a3ed0af11da73a0bfbb5ad1">determineCalleeSaves</a> (MachineFunction &amp;MF, BitVector &amp;SavedRegs, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method determines which of the registers reported by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">TargetRegisterInfo::getCalleeSavedRegs()</a> should actually get saved. <a href="#aa2e3cf793a3ed0af11da73a0bfbb5ad1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae380dabb206877f151fa2c3c39f9585a">processFunctionBeforeFrameFinalized</a> (MachineFunction &amp;MF, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processFunctionBeforeFrameFinalized - This method is called immediately before the specified function's frame layout (MF.getFrameInfo()) is finalized. <a href="#ae380dabb206877f151fa2c3c39f9585a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38fe3f67034841400e749f75768348a2">hasBP</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682ca2f9a07f1d42cf4b7aa0e62fc569">hasReservedCallFrame</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasReservedCallFrame - Under normal circumstances, when a frame pointer is not required, we reserve argument space for call sites in the function immediately on entry to the current function. <a href="#a682ca2f9a07f1d42cf4b7aa0e62fc569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac33945153d277b7244196a35084006">eliminateCallFramePseudoInstr</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called during prolog/epilog code insertion to eliminate call frame setup and destroy pseudo instructions (but only if the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> is using them). <a href="#aeac33945153d277b7244196a35084006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0c9359d4e969f68a7c7643fc3fcb5c">assignCalleeSavedSpillSlots</a> (MachineFunction &amp;MF, const TargetRegisterInfo *TRI, std::vector&lt; CalleeSavedInfo &gt; &amp;CSI, unsigned &amp;MinCSFrameIndex, unsigned &amp;MaxCSFrameIndex) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>assignCalleeSavedSpillSlots - Allows target to override spill slot assignment logic. <a href="#a5a0c9359d4e969f68a7c7643fc3fcb5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d66c6615f09ca15ca384387a5d0eb3e">spillCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, ArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spillCalleeSavedRegisters - Issues instruction(s) to spill all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of store instructions via storeRegToStackSlot(). <a href="#a2d66c6615f09ca15ca384387a5d0eb3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6658cff9efc100c5b2751bed442d5a9b">restoreCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, MutableArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>restoreCalleeSavedRegisters - Issues instruction(s) to restore all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of load instructions via loadRegToStackSlot(). <a href="#a6658cff9efc100c5b2751bed442d5a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16cde5f8fc9f15e96e996e063f1dcb9c">getFirstSPAdjustAmount</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c7d3374923da4e91bd8cdfd0d7f599">canUseAsPrologue</a> (const MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not the given <span class="doxyComputerOutput">MBB</span> can be used as a prologue for the target. <a href="#af6c7d3374923da4e91bd8cdfd0d7f599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c55a328d2daf9b5e2f457c8880e21c4">canUseAsEpilogue</a> (const MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not the given <span class="doxyComputerOutput">MBB</span> can be used as a epilogue for the target. <a href="#a4c55a328d2daf9b5e2f457c8880e21c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fdd175ee23fc8aaf606ccbb71ce040c">enableShrinkWrapping</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target will correctly handle shrink wrapping. <a href="#a1fdd175ee23fc8aaf606ccbb71ce040c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9391651a0d38be1661b6fcadc024a22e">isSupportedStackID</a> (TargetStackID::Value ID) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">TargetStackID::Value</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d4b4d6b1afea141d3e29b028e4f2e8">getStackIDForScalableVectors</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the StackID that scalable vectors should be associated with. <a href="#ac0d4b4d6b1afea141d3e29b028e4f2e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee88007dc4d49f7684f94536cb6312bf">isStackIdSafeForLocalArea</a> (unsigned StackId) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns whether or not it is safe for an object with the given stack id to be bundled into the local area. <a href="#aee88007dc4d49f7684f94536cb6312bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d69df780f835d45386962290fc32210">allocateStack</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, MachineFunction &amp;MF, uint64_t Offset, uint64_t RealStackSize, bool EmitCFI, bool NeedProbe, uint64_t ProbeSize, bool DynAllocation) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a6257e7a03156ea3018b555f0aff4b2">hasFPImpl</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdc7d01ca3f45ceeee7437f60a22c72">determineFrameLayout</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae568d715a0ec209238f80c2959a45a5e">emitCalleeSavedRVVPrologCFI</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, bool HasFP) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a268fd6889287258dd204f087d8947">emitCalleeSavedRVVEpilogCFI</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Emitter&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87851d3edbb52240f67f83bdae619c38">emitCFIForCSI</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const SmallVector&lt; CalleeSavedInfo, 8 &gt; &amp;CSI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e6d9f7ed922763315f0d2223e0d8aa2">deallocateStack</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, uint64_t &amp;StackSize, int64_t CFAOffset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; int64_t, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5767fdcc35fa6bea07aaeca4903a191">assignRVVStackObjectOffsets</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80d5470620b06f18bcd89944fa2d615f">inlineStackProbe</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;PrologueMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a StackProbe stub (if any) with the actual probe code inline. <a href="#a80d5470620b06f18bcd89944fa2d615f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d92644dab86d6aac408d33486b95e4">allocateAndProbeStackForRVV</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, int64_t Amount, MachineInstr::MIFlag Flag, bool EmitCFI, bool DynAllocation) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a></td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVFrameLowering() {#af893429fa90ab18cd29ed194fd04fdf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVFrameLowering::RISCVFrameLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ab51d8ccc37acb885f5b25675d4b06582">getABIStackAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a>, <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6a6d31b2f1e5754f5824c5dec555eeac">llvm::TargetFrameLowering::TargetFrameLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocateStack() {#a5d69df780f835d45386962290fc32210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::allocateStack (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, uint64_t Offset, uint64_t RealStackSize, bool EmitCFI, bool NeedProbe, uint64_t ProbeSize, bool DynAllocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a03445be1c81520587d5bb31b353f5558">llvm::MCCFIInstruction::createDefCfaRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a131316d63f21b59d27d82ae95b91bfc7">emitPrologue</a>.</p>

</div>
</div>

### assignCalleeSavedSpillSlots() {#a5a0c9359d4e969f68a7c7643fc3fcb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::assignCalleeSavedSpillSlots (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI, unsigned &amp; MinCSFrameIndex, unsigned &amp; MaxCSFrameIndex)</td>
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

<p>assignCalleeSavedSpillSlots - Allows target to override spill slot assignment logic.</p>


<p>If implemented, <a href="#a5a0c9359d4e969f68a7c7643fc3fcb5c">assignCalleeSavedSpillSlots()</a> should assign frame slots to all CSI entries and return true. If this method returns false, spill slots will be assigned using generic implementation. <a href="#a5a0c9359d4e969f68a7c7643fc3fcb5c">assignCalleeSavedSpillSlots()</a> may add, delete or rearrange elements of CSI.</p>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad2270087c6b8d7061c3a5e83fb61c0a6">llvm::MachineFrameInfo::CreateFixedSpillStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a810744cdd1df25a6c262b32a99b29917">FixedCSRFIMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae4ad01c7c2990a944ca190cd409a60d5">getMaxPushPopReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a7bcee7be41e609e2b3e3239648007832">getPushPopEncodingAndNum</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a6b0e6be6a451881260fcd7f29b7fb4fc">llvm::RISCVRegisterInfo::isRVVRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a6ba514594eb802f087046edbe201f8f4">llvm::MachineFrameInfo::setStackID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### canUseAsEpilogue() {#a4c55a328d2daf9b5e2f457c8880e21c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::canUseAsEpilogue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not the given <span class="doxyComputerOutput">MBB</span> can be used as a epilogue for the target.</p>


<p>The epilogue will be inserted before the first terminator of that block. This method is used by the shrink-wrapping pass to decide if <span class="doxyComputerOutput">MBB</span> will be correctly handled by the target. As soon as the target enable shrink-wrapping without overriding this method, we assume that each basic block is a valid epilogue.</p>


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 2091 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a31aa2680ec79198a4c94f35b3a1ad97e">llvm::MachineBasicBlock::getFallThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a82f5d244972c88ff03ee56d6c090ac70">llvm::MachineBasicBlock::isReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adbff55f335d303816547f35eb6edb948">llvm::MachineBasicBlock::size</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a96dd72f1aba111c3927d4c600a643618">llvm::RISCVMachineFunctionInfo::useSaveRestoreLibCalls</a>.</p>

</div>
</div>

### canUseAsPrologue() {#af6c7d3374923da4e91bd8cdfd0d7f599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::canUseAsPrologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not the given <span class="doxyComputerOutput">MBB</span> can be used as a prologue for the target.</p>


<p>The prologue will be inserted first in this basic block. This method is used by the shrink-wrapping pass to decide if <span class="doxyComputerOutput">MBB</span> will be correctly handled by the target. As soon as the target enable shrink-wrapping without overriding this method, we assume that each basic block is a valid prologue.</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 2074 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a4f1af6e587ae8846628561570b54e2ee">llvm::RegScavenger::enterBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a27037167fddcdde3b6207d025267bbfc">llvm::RegScavenger::isRegUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a96dd72f1aba111c3927d4c600a643618">llvm::RISCVMachineFunctionInfo::useSaveRestoreLibCalls</a>.</p>

</div>
</div>

### determineCalleeSaves() {#aa2e3cf793a3ed0af11da73a0bfbb5ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::determineCalleeSaves (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SavedRegs, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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


<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a3c75dbf1bd34c20b6265e6af91a32a06">llvm::RISCVABI::getBPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a38fe3f67034841400e749f75768348a2">hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>

</div>
</div>

### eliminateCallFramePseudoInstr() {#aeac33945153d277b7244196a35084006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator RISCVFrameLowering::eliminateCallFramePseudoInstr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
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


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#ac54cd9ae6b849b3a2fd1fe982f9d09e2">llvm::TargetFrameLowering::alignSPAdjust</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="#a682ca2f9a07f1d42cf4b7aa0e62fc569">hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">llvm::MachineInstr::NoFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a> and <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a>.</p>

</div>
</div>

### emitEpilogue() {#aa587d71d9d14ad035e31b99fc0c90802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::emitEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="#a16cde5f8fc9f15e96e996e063f1dcb9c">getFirstSPAdjustAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ab858e12b9896856aca708f103f94e8b7">getPushOrLibCallsSavedInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a857ca8ebd4e64059aa8774f14445e414">getRVVCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#ac92bd14c26009fdfdc00576604da950f">llvm::StackOffset::getScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="#afc745007e032dc7daac0eb03fbd9f0f1">getStackSizeWithRVVPadding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="#a682ca2f9a07f1d42cf4b7aa0e62fc569">hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0270bdca4aeb43f39bf91c900a398057">llvm::next_nodbg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### emitPrologue() {#a131316d63f21b59d27d82ae95b91bfc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::emitPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a19e260b3bbf8fad8480d151e11919836">llvm::MachineFrameInfo::adjustsStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#a5d69df780f835d45386962290fc32210">allocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aad03ef5cfbe6e7cad076d9e45ba06592">llvm::LLVMContext::diagnose</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a3c75dbf1bd34c20b6265e6af91a32a06">llvm::RISCVABI::getBPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="#a16cde5f8fc9f15e96e996e063f1dcb9c">getFirstSPAdjustAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3836203fac855ac3c5718b701bd13ffd">llvm::MachineFrameInfo::getMaxAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ab858e12b9896856aca708f103f94e8b7">getPushOrLibCallsSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a857ca8ebd4e64059aa8774f14445e414">getRVVCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#ac92bd14c26009fdfdc00576604da950f">llvm::StackOffset::getScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="#afc745007e032dc7daac0eb03fbd9f0f1">getStackSizeWithRVVPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="#a38fe3f67034841400e749f75768348a2">hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a889bd3ec782a056c71f40ea116bad9b8">llvm::RISCVTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a53ca7cff9e929ba372da9780fdd44b02">llvm::MachineRegisterInfo::isReserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### enableShrinkWrapping() {#a1fdd175ee23fc8aaf606ccbb71ce040c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::enableShrinkWrapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Returns true if the target will correctly handle shrink wrapping.</p>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 2066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a9c38a8cc0a38636c95bd2826de9d72d4">llvm::Function::hasOptNone</a>.</p>

</div>
</div>

### getFirstSPAdjustAmount() {#a16cde5f8fc9f15e96e996e063f1dcb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t RISCVFrameLowering::getFirstSPAdjustAmount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="#afc745007e032dc7daac0eb03fbd9f0f1">getStackSizeWithRVVPadding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#aa587d71d9d14ad035e31b99fc0c90802">emitEpilogue</a>, <a href="#a131316d63f21b59d27d82ae95b91bfc7">emitPrologue</a> and <a href="#a9258a9f50df17d6b3c064af9bf06c2bf">getFrameIndexReference</a>.</p>

</div>
</div>

### getFrameIndexReference() {#a9258a9f50df17d6b3c064af9bf06c2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset RISCVFrameLowering::getFrameIndexReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; FrameReg)</td>
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


<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aab735eb6b844f1b683d12013a083b4e2">llvm::StackOffset::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a3c75dbf1bd34c20b6265e6af91a32a06">llvm::RISCVABI::getBPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="#a16cde5f8fc9f15e96e996e063f1dcb9c">getFirstSPAdjustAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aefb3b77455d0e0f2e1e8b56604c63c0c">llvm::TargetRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a60679e554cbf7092c8a0ae6c5db2661a">llvm::MachineFrameInfo::getOffsetAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6521d4d5560c03b2e6490883558b882c">llvm::TargetFrameLowering::getOffsetOfLocalArea</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a3bb61639d8566c8d12f66c562d948bef">llvm::StackOffset::getScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="#afc745007e032dc7daac0eb03fbd9f0f1">getStackSizeWithRVVPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a>, <a href="#a38fe3f67034841400e749f75768348a2">hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a96e76d4f9381108bffdc265b4d666b16">llvm::TargetRegisterInfo::hasStackRealignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>.</p>

</div>
</div>

### getStackIDForScalableVectors() {#ac0d4b4d6b1afea141d3e29b028e4f2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetStackID::Value RISCVFrameLowering::getStackIDForScalableVectors ()</td>
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

<p>Returns the StackID that scalable vectors should be associated with.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 2133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a>.</p>

</div>
</div>

### getStackSizeWithRVVPadding() {#afc745007e032dc7daac0eb03fbd9f0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t RISCVFrameLowering::getStackSizeWithRVVPadding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>.</p>


<p>Referenced by <a href="#aa587d71d9d14ad035e31b99fc0c90802">emitEpilogue</a>, <a href="#a131316d63f21b59d27d82ae95b91bfc7">emitPrologue</a>, <a href="#a16cde5f8fc9f15e96e996e063f1dcb9c">getFirstSPAdjustAmount</a> and <a href="#a9258a9f50df17d6b3c064af9bf06c2bf">getFrameIndexReference</a>.</p>

</div>
</div>

### hasBP() {#a38fe3f67034841400e749f75768348a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::hasBP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a4f335273c28b17552a7cfd802f42be2a">llvm::MachineFrameInfo::getMaxCallFrameSize</a>, <a href="#a682ca2f9a07f1d42cf4b7aa0e62fc569">hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a99cdf1b99c0f1b7e1bf2111aa7d2eaa3">llvm::MachineFrameInfo::isMaxCallFrameSizeComputed</a>, <a href="#a8682aca3721b6e3f6152ad82b053e209">STI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#aa2e3cf793a3ed0af11da73a0bfbb5ad1">determineCalleeSaves</a>, <a href="#a131316d63f21b59d27d82ae95b91bfc7">emitPrologue</a>, <a href="#a9258a9f50df17d6b3c064af9bf06c2bf">getFrameIndexReference</a> and <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a277355964aa533df56cf3e0de6701b3d">llvm::RISCVRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### hasReservedCallFrame() {#a682ca2f9a07f1d42cf4b7aa0e62fc569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::hasReservedCallFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>hasReservedCallFrame - Under normal circumstances, when a frame pointer is not required, we reserve argument space for call sites in the function immediately on entry to the current function.</p>


<p>This eliminates the need for add/sub sp brackets around call sites. Returns true if the call frame is included as part of the stack frame.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a56e2c07f0563d2e32c68a2fd08d716b0">hasRVVFrameObject</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>.</p>


<p>Referenced by <a href="#aeac33945153d277b7244196a35084006">eliminateCallFramePseudoInstr</a>, <a href="#aa587d71d9d14ad035e31b99fc0c90802">emitEpilogue</a> and <a href="#a38fe3f67034841400e749f75768348a2">hasBP</a>.</p>

</div>
</div>

### isStackIdSafeForLocalArea() {#aee88007dc4d49f7684f94536cb6312bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVFrameLowering::isStackIdSafeForLocalArea (unsigned StackId)</td>
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

<p>This method returns whether or not it is safe for an object with the given stack id to be bundled into the local area.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a>.</p>

</div>
</div>

### isSupportedStackID() {#a9391651a0d38be1661b6fcadc024a22e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::isSupportedStackID (<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">TargetStackID::Value</a> ID)</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 2120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a7d111d4b9003a9aab4efe813d03777b6">llvm::TargetStackID::NoAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a29a8016e50342e4598b3cb8a6601694f">llvm::TargetStackID::SGPRSpill</a> and <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5ab9b4a66e5478772af595c40fbce45c03">llvm::TargetStackID::WasmLocal</a>.</p>

</div>
</div>

### processFunctionBeforeFrameFinalized() {#ae380dabb206877f151fa2c3c39f9585a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::processFunctionBeforeFrameFinalized (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#aecaae26e25f7f952810d98e50264b5fb">llvm::RegScavenger::addScavengingFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a61960903871aa95a7161074c6f1eec8f">llvm::MachineFrameInfo::CreateSpillStackObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1f09e99062be1101e3a2cf3ff88878f7">llvm::MachineFrameInfo::ensureMaxAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchframelowering-cpp/#a02d23368b0ce7bd846cc8270dd411aa9">estimateFunctionSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a66046fdf8661d5276f951337b0cf892d">llvm::MachineFrameInfo::estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af59f353dd1adb78d8e0187803c5edb83">getScavSlotsNumForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a56e2c07f0563d2e32c68a2fd08d716b0">hasRVVFrameObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### restoreCalleeSavedRegisters() {#a6658cff9efc100c5b2751bed442d5a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::restoreCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a810744cdd1df25a6c262b32a99b29917">FixedCSRFIMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a392d167565f63198879bcfedd3ac419d">getRestoreLibCallName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a86dbb25971eae90ef852db776e870895">llvm::RISCVMachineFunctionInfo::getRVPushRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a491b8849e11a13d0111b3124977727ed">llvm::RISCVMachineFunctionInfo::getRVPushRlist</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a857ca8ebd4e64059aa8774f14445e414">getRVVCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a88c54d5a1b8d0b2add526cf7424fc165">llvm::RISCVZC::INVALID_RLIST</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a1aabb0d5da92e7ec4f977806b0f8d0ca">llvm::RISCVMachineFunctionInfo::isPushable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a5c3971e24b86ff0172b94caf1cdae609">llvm::RISCVII::MO_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### spillCalleeSavedRegisters() {#a2d66c6615f09ca15ca384387a5d0eb3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::spillCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a810744cdd1df25a6c262b32a99b29917">FixedCSRFIMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a86dbb25971eae90ef852db776e870895">llvm::RISCVMachineFunctionInfo::getRVPushRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a491b8849e11a13d0111b3124977727ed">llvm::RISCVMachineFunctionInfo::getRVPushRlist</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a857ca8ebd4e64059aa8774f14445e414">getRVVCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a4bf4f9d1247175b3a6e0def631bda61b">getSpillLibCallName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a1aabb0d5da92e7ec4f977806b0f8d0ca">llvm::RISCVMachineFunctionInfo::isPushable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a5c3971e24b86ff0172b94caf1cdae609">llvm::RISCVII::MO_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### hasFPImpl() {#a5a6257e7a03156ea3018b555f0aff4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVFrameLowering::hasFPImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocateAndProbeStackForRVV() {#a31d92644dab86d6aac408d33486b95e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::allocateAndProbeStackForRVV (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int64_t Amount, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flag, bool EmitCFI, bool DynAllocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### assignRVVStackObjectOffsets() {#ad5767fdcc35fa6bea07aaeca4903a191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int64_t, Align &gt; RISCVFrameLowering::assignRVVStackObjectOffsets (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### deallocateStack() {#a3e6d9f7ed922763315f0d2223e0d8aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::deallocateStack (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, uint64_t &amp; StackSize, int64_t CFAOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### determineFrameLayout() {#adcdc7d01ca3f45ceeee7437f60a22c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::determineFrameLayout (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### emitCalleeSavedRVVEpilogCFI() {#a95a268fd6889287258dd204f087d8947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::emitCalleeSavedRVVEpilogCFI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1975 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### emitCalleeSavedRVVPrologCFI() {#ae568d715a0ec209238f80c2959a45a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::emitCalleeSavedRVVPrologCFI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, bool HasFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 1939 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### emitCFIForCSI() {#a87851d3edbb52240f67f83bdae619c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Emitter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::emitCFIForCSI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a>, 8 &gt; &amp; CSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### inlineStackProbe() {#a80d5470620b06f18bcd89944fa2d615f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVFrameLowering::inlineStackProbe (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PrologueMBB)</td>
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

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>, definition at line 2211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### STI {#a8682aca3721b6e3f6152ad82b053e209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVSubtarget&amp; llvm::RISCVFrameLowering::STI</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>.</p>


<p>Referenced by <a href="#a5d69df780f835d45386962290fc32210">allocateStack</a>, <a href="#a5a0c9359d4e969f68a7c7643fc3fcb5c">assignCalleeSavedSpillSlots</a>, <a href="#aeac33945153d277b7244196a35084006">eliminateCallFramePseudoInstr</a>, <a href="#aa587d71d9d14ad035e31b99fc0c90802">emitEpilogue</a>, <a href="#a131316d63f21b59d27d82ae95b91bfc7">emitPrologue</a>, <a href="#a16cde5f8fc9f15e96e996e063f1dcb9c">getFirstSPAdjustAmount</a>, <a href="#a38fe3f67034841400e749f75768348a2">hasBP</a> and <a href="#af893429fa90ab18cd29ed194fd04fdf6">RISCVFrameLowering</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
