---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86framelowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86FrameLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::X86FrameLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">Target/X86/X86FrameLowering.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a> (const X86Subtarget &amp;STI, MaybeAlign StackAlignOverride)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6cb0d8b5d8e3b35dee29f5e752d31c">emitStackProbe</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, bool InProlog, std::optional&lt; MachineFunction::DebugInstrOperandPair &gt; InstrNum=std::nullopt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target stack probe code. <a href="#a6a6cb0d8b5d8e3b35dee29f5e752d31c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88384d07e66c382b05f793848660d90">stackProbeFunctionModifiesSP</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the stack probe function call return with a modified stack pointer? <a href="#ad88384d07e66c382b05f793848660d90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91705445bd9fc240a0092580cab1d092">inlineStackProbe</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;PrologMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a StackProbe inline-stub with the actual probe code inline. <a href="#a91705445bd9fc240a0092580cab1d092">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd4fee4d18fa2066d758dff7168ef36">emitCalleeSavedFrameMovesFullCFA</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits Dwarf Info specifying offsets of callee saved registers and frame pointer. <a href="#acbd4fee4d18fa2066d758dff7168ef36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, bool IsPrologue) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitProlog/emitEpilog - These methods insert prolog and epilog code into the function. <a href="#af2ab7cd691053c57c27e810c549a0300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8faf9a625064bfefafb7ace646815ff">adjustForSegmentedStacks</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;PrologueMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjust the prologue to have the function use segmented stacks. <a href="#ac8faf9a625064bfefafb7ace646815ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd992a2165073c9cea53128d5b6c4145">adjustForHiPEPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;PrologueMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erlang programs may need a special prologue to handle the stack size they might need at runtime. <a href="#afd992a2165073c9cea53128d5b6c4145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbb50454d9bb068f4ab6b2d08fb7abf">determineCalleeSaves</a> (MachineFunction &amp;MF, BitVector &amp;SavedRegs, RegScavenger *RS=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method determines which of the registers reported by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">TargetRegisterInfo::getCalleeSavedRegs()</a> should actually get saved. <a href="#a6cbb50454d9bb068f4ab6b2d08fb7abf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6fdca5f3b44d406ff07e43b2f140f6">assignCalleeSavedSpillSlots</a> (MachineFunction &amp;MF, const TargetRegisterInfo *TRI, std::vector&lt; CalleeSavedInfo &gt; &amp;CSI) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc942a637e5d48a94d4033498b7479dd">spillCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, ArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spillCalleeSavedRegisters - Issues instruction(s) to spill all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of store instructions via storeRegToStackSlot(). <a href="#afc942a637e5d48a94d4033498b7479dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ed22ca5dc3213bfb96e1ddbc41952e">restoreCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, MutableArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>restoreCalleeSavedRegisters - Issues instruction(s) to restore all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of load instructions via loadRegToStackSlot(). <a href="#a94ed22ca5dc3213bfb96e1ddbc41952e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068e9d1fd54621ae340f26c41d170a1a">spillFPBP</a> (MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a function uses base pointer and the base pointer is clobbered by inline asm, RA doesn't detect this case, and after the inline asm, the base pointer contains garbage value. <a href="#a068e9d1fd54621ae340f26c41d170a1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6696e7a9f36d7983d3593e5f4a17831f">hasReservedCallFrame</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasReservedCallFrame - Under normal circumstances, when a frame pointer is not required, we reserve argument space for call sites in the function immediately on entry to the current function. <a href="#a6696e7a9f36d7983d3593e5f4a17831f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c500b38e3912753a3b7354b88b10993">canSimplifyCallFramePseudos</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canSimplifyCallFramePseudos - If there is a reserved call frame, the call frame pseudos can be simplified. <a href="#a0c500b38e3912753a3b7354b88b10993">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d66887ade3ca46870e0921376f86fd1">needsFrameIndexResolution</a> (const MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84fbe17f451c957c67de546c98f2b79b">getFrameIndexReference</a> (const MachineFunction &amp;MF, int FI, Register &amp;FrameReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFrameIndexReference - This method should return the base register and offset used to reference a frame index location. <a href="#a84fbe17f451c957c67de546c98f2b79b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd3876e593314b23ed0679279ee31dfe">getWin64EHFrameIndexRef</a> (const MachineFunction &amp;MF, int FI, Register &amp;SPReg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ebbed1ceecae3f74214e33fc8c533f">getFrameIndexReferenceSP</a> (const MachineFunction &amp;MF, int FI, Register &amp;SPReg, int Adjustment) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb20caf4eb8695705452f25d78a18a06">getFrameIndexReferencePreferSP</a> (const MachineFunction &amp;MF, int FI, Register &amp;FrameReg, bool IgnoreSPUpdates) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as <span class="doxyComputerOutput">getFrameIndexReference</span>, except that the stack pointer (as opposed to the frame pointer) will be the preferred value for <span class="doxyComputerOutput">FrameReg</span>. <a href="#afb20caf4eb8695705452f25d78a18a06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f78769915f0742f77e73e45abab318">eliminateCallFramePseudoInstr</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called during prolog/epilog code insertion to eliminate call frame setup and destroy pseudo instructions (but only if the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> is using them). <a href="#aa5f78769915f0742f77e73e45abab318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b381a1c38101d4e17121c7b993e00c">getWinEHParentFrameOffset</a> (const MachineFunction &amp;MF) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8d1523f211998978b3fa0bfe8818a1">processFunctionBeforeFrameFinalized</a> (MachineFunction &amp;MF, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processFunctionBeforeFrameFinalized - This method is called immediately before the specified function's frame layout (MF.getFrameInfo()) is finalized. <a href="#a6a8d1523f211998978b3fa0bfe8818a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d9e67f21b6a4968a6074b082944dc6">processFunctionBeforeFrameIndicesReplaced</a> (MachineFunction &amp;MF, RegScavenger *RS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processFunctionBeforeFrameIndicesReplaced - This method is called immediately before MO_FrameIndex operands are eliminated, but after the frame is finalized. <a href="#af7d9e67f21b6a4968a6074b082944dc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d6349ca67f14c36e41916e41536da4">mergeSPUpdates</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;MBBI, bool doMergeWithPrevious) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the instruction before/after the passed instruction. <a href="#af1d6349ca67f14c36e41916e41536da4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;MBBI, const DebugLoc &amp;DL, int64_t NumBytes, bool InEpilogue) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a series of instructions to increment / decrement the stack pointer by a constant value. <a href="#aa8a605a58ebdee20705834400bdbb922">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e593e787ba6a94dbd287c32abe4006">canUseLEAForSPInEpilogue</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that LEA can be used on SP in an epilogue sequence for <span class="doxyComputerOutput">MF</span>. <a href="#ad7e593e787ba6a94dbd287c32abe4006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652c5c131aaf585181fb0ff722781118">canUseAsPrologue</a> (const MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not the given <span class="doxyComputerOutput">MBB</span> can be used as a prologue for the target. <a href="#a652c5c131aaf585181fb0ff722781118">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae24f16623a7d1df7b850c55694e9d27">canUseAsEpilogue</a> (const MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not the given <span class="doxyComputerOutput">MBB</span> can be used as a epilogue for the target. <a href="#aae24f16623a7d1df7b850c55694e9d27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e24606b8fe6124decedb17e5ffa405e">enableShrinkWrapping</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target will correctly handle shrink wrapping. <a href="#a7e24606b8fe6124decedb17e5ffa405e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee8390bf727c3086a7b864de6c6913e">orderFrameObjects</a> (const MachineFunction &amp;MF, SmallVectorImpl&lt; int &gt; &amp;ObjectsToAllocate) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Order the symbols in the local stack. <a href="#adee8390bf727c3086a7b864de6c6913e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0079a40a972f2942156b2d73bbf190">BuildCFI</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, const MCCFIInstruction &amp;CFIInst, MachineInstr::MIFlag Flag=MachineInstr::NoFlags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wraps up getting a CFI index and building a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> for it. <a href="#aef0079a40a972f2942156b2d73bbf190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, bool RestoreSP=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets up EBP and optionally ESI based on the incoming EBP value. <a href="#a535388ac574e0f8d844662d315997b3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0900cd962cd955b2b6de25731710f5">restoreWinEHStackPointersInParent</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f9f26d96deb10d0d3b394fe12e2b0f5">getInitialCFAOffset</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return initial CFA offset value i.e. <a href="#a5f9f26d96deb10d0d3b394fe12e2b0f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac406e51bd21d4da6eb9762f2f36df6">getInitialCFARegister</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return initial CFA register value i.e. <a href="#abac406e51bd21d4da6eb9762f2f36df6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase">DwarfFrameBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca49f4bdff5eb8f32e4b650f33d6f98e">getDwarfFrameBase</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the frame base information to be encoded in the DWARF subprogram debug info. <a href="#aca49f4bdff5eb8f32e4b650f33d6f98e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009e40a8d70eae94c4dc32285c717732">has128ByteRedZone</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function has a redzone (accessible bytes past the frame of the top of stack function) as part of it's ABI. <a href="#a009e40a8d70eae94c4dc32285c717732">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493d9a8215b5ec117b32762217d66f80">hasFPImpl</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasFPImpl - Return true if the specified function should have a dedicated frame pointer register. <a href="#a493d9a8215b5ec117b32762217d66f80">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af638105f984cedc23b3245bc9229e236">isWin64Prologue</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we need to use the restricted Windows x64 prologue and epilogue code patterns that can be described with WinCFI (.seh_* directives). <a href="#af638105f984cedc23b3245bc9229e236">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c6fc5253875c943f364255766f388f">needsDwarfCFI</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1feb8d8cc6107264ab7c1394b01d5b">calculateMaxStackAlign</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4ecee50166bf8fcaeb2c8f03304581">emitStackProbeCall</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, bool InProlog, std::optional&lt; MachineFunction::DebugInstrOperandPair &gt; InstrNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target stack probe as a call to a helper function. <a href="#a1e4ecee50166bf8fcaeb2c8f03304581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada3420cb1df4417aa90fe0698f6cc3b1">emitStackProbeInline</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, bool InProlog) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target stack probe as an inline sequence. <a href="#ada3420cb1df4417aa90fe0698f6cc3b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43619cbca9b358a92076bd02945a88bf">emitStackProbeInlineWindowsCoreCLR64</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, bool InProlog) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82bede7e1fb4696cb037cc72065c88a0">emitStackProbeInlineGeneric</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, bool InProlog) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645e4e238e6594dd9816b24dc62a4f86">emitStackProbeInlineGenericBlock</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, uint64_t Offset, uint64_t Align) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aac1740e736ea330beb84b387a9818b">emitStackProbeInlineGenericLoop</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, uint64_t Offset, uint64_t Align) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba9b90da06993d722a55cf56d9f6c7b1">emitZeroCallUsedRegs</a> (BitVector RegsToZero, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target zero call-used regs. <a href="#aba9b90da06993d722a55cf56d9f6c7b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ebeb032a4a9c27af284212d5051f2ce">adjustFrameForMsvcCxxEh</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b16c050e22b49ccaed8174396c64aea">BuildStackAlignAND</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, unsigned Reg, uint64_t MaxAlign) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Aligns the stack pointer by ANDing it with -MaxAlign. <a href="#a2b16c050e22b49ccaed8174396c64aea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2c36b5d0d1f8f63e3e5280f2dff710">adjustStackWithPops</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, int Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make small positive stack adjustments using POPs. <a href="#a3a2c36b5d0d1f8f63e3e5280f2dff710">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f118647874ff018b75856624c38dd08">BuildStackAdjustment</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const DebugLoc &amp;DL, int64_t Offset, bool InEpilogue) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjusts the stack pointer using LEA, SUB, or ADD. <a href="#a7f118647874ff018b75856624c38dd08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1648550ec282b6dcf1b5fa8dbc4ca3">getPSPSlotOffsetFromSP</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae51a715a851d665a5f98e0125bdb4f73">getWinEHFuncletFrameSize</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cc324c3010ff1c9ea386c02e165ab1">emitCatchRetReturnValue</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, MachineInstr *CatchRet) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize the catchret target MBB in RAX. <a href="#aa5cc324c3010ff1c9ea386c02e165ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5015b24b5088c73f49a18ff556ec4af4">spillFPBPUsingSP</a> (MachineFunction &amp;MF, const MachineBasicBlock::iterator BeforeMI, Register FP, Register BP, int SPAdjust) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Issue instructions to allocate stack space and spill frame pointer and/or base pointer to stack using stack pointer register. <a href="#a5015b24b5088c73f49a18ff556ec4af4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355e7b8668257cd522c34492f06e880d">restoreFPBPUsingSP</a> (MachineFunction &amp;MF, const MachineBasicBlock::iterator AfterMI, Register FP, Register BP, int SPAdjust) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Issue instructions to restore frame pointer and/or base pointer from stack using stack pointer register, and free stack space. <a href="#a355e7b8668257cd522c34492f06e880d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71fcd1fe99e4f0c613775f548f1c3adb">saveAndRestoreFPBPUsingSP</a> (MachineFunction &amp;MF, MachineBasicBlock::iterator BeforeMI, MachineBasicBlock::iterator AfterMI, bool SpillFP, bool SpillBP) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec08de73f8475855b8eb6720fcc7f263">checkInterferedAccess</a> (MachineFunction &amp;MF, MachineBasicBlock::reverse_iterator DefMI, MachineBasicBlock::reverse_iterator KillMI, bool SpillFP, bool SpillBP) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the live range of FP or BP (DefMI, KillMI), check if there is any interfered stack access in the range, usually generated by register spill. <a href="#aec08de73f8475855b8eb6720fcc7f263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119ea4a6b09a7301ccedb02f4addc79a">skipSpillFPBP</a> (MachineFunction &amp;MF, MachineBasicBlock::reverse_iterator &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeee4b43efe13447f760c28d545fe653">STI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo">X86InstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo">X86RegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is64Bit implies that x86_64 instructions are available. <a href="#ab69c52bac76806c714de3de7674d8f31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7761d9f26e6c0722ee9c9d8c5e052c1c">IsLP64</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb804392ca8368795013f2e5dc001ee2">Uses64BitFramePtr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the 64-bit frame or stack pointer should be used. <a href="#abb804392ca8368795013f2e5dc001ee2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7147559f9c35cbab44e96ecc2408c90">StackPtr</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86FrameLowering() {#a116242916a44a6d4f5301270c6c4f05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86FrameLowering::X86FrameLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; STI, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> StackAlignOverride)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="#a7761d9f26e6c0722ee9c9d8c5e052c1c">IsLP64</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a>, <a href="#ab7147559f9c35cbab44e96ecc2408c90">StackPtr</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6a6d31b2f1e5754f5824c5dec555eeac">llvm::TargetFrameLowering::TargetFrameLowering</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a>, <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a> and <a href="#abb804392ca8368795013f2e5dc001ee2">Uses64BitFramePtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustForHiPEPrologue() {#afd992a2165073c9cea53128d5b6c4145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::adjustForHiPEPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PrologueMBB)</td>
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

<p>Erlang programs may need a special prologue to handle the stack size they might need at runtime.</p>


<p>That is because Erlang/OTP does not implement a C stack but uses a custom implementation of hybrid stack/heap architecture. (for more information see Eric Stenman's Ph.D. thesis: <a href="http://publications.uu.se/uu/fulltext/nbn_se_uu_diva-2688.pdf">http://publications.uu.se/uu/fulltext/nbn_se_uu_diva-2688.pdf</a>)</p>


<p>CheckStack: temp0 = sp - MaxStack if( temp0 &lt; SP_LIMIT(P) ) goto IncStack else goto OldStart OldStart: ... IncStack: call inc_stack # doubles the stack space temp0 = sp - MaxStack if( temp0 &lt; SP_LIMIT(P) ) goto IncStack else goto OldStart</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acce9c12cc977a88dc7bc51493ce7681c">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eafeeb44274a14a14010dc990daecb39a0">llvm::X86::COND_AE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eae364c60967a7bc453d49caffc07d7bef">llvm::X86::COND_LE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ae2c3c56fbe514f4a3ee837a4af0499a8">getHiPELiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a06bb57eb1830a137e7b8f8b25908ed24">llvm::Module::getNamedMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a1021e45de682ea397f9aa6c529ac80be">GetScratchRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a640f34062e7189756ce67e60d5dfd629">llvm::MachineRegisterInfo::isLiveIn</a>, <a href="#a7761d9f26e6c0722ee9c9d8c5e052c1c">IsLP64</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a364ed6e68f92f797c0cd9e53ce5ea2a5">llvm::MachineBasicBlock::liveins</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6a437bb3c4a44ac328344e5f361c7816">llvm::MachineFunction::push_front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a8efc9cbc802adc2bb2673b4ba6308869">llvm::MachineFunction::verify</a>.</p>

</div>
</div>

### adjustForSegmentedStacks() {#ac8faf9a625064bfefafb7ace646815ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::adjustForSegmentedStacks (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PrologueMBB)</td>
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

<p>Adjust the prologue to have the function use segmented stacks.</p>


<p>This works by adding a check even before the "normal" function prologue.</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acce9c12cc977a88dc7bc51493ce7681c">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eade92e2f17ca0acdd1ffa23d01df381df">llvm::X86::COND_A</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a2e51353f9cba613d53a5c85b94f224b1">llvm::X86MachineFunctionInfo::getArgumentStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ae106f6c6362377b3016f0d174227e193">llvm::TargetMachine::getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a39d0dcc2605f63349a774a79927b2209">getMOVriOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a56e1b2d1999aadf4c513caee1ce5275b">llvm::BranchProbability::getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a1021e45de682ea397f9aa6c529ac80be">GetScratchRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afd00958cba7080048a84cccfcef55d71">llvm::BranchProbability::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ab29c5668ec7d2b12468b97aa33e5f87b">HasNestArgument</a>, <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a640f34062e7189756ce67e60d5dfd629">llvm::MachineRegisterInfo::isLiveIn</a>, <a href="#a7761d9f26e6c0722ee9c9d8c5e052c1c">IsLP64</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#ad6f5455eb7ba6ed74cab551099d0a952">kSplitStackAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a364ed6e68f92f797c0cd9e53ce5ea2a5">llvm::MachineBasicBlock::liveins</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a00d2c6aab11836fcd2116ef07924253e">llvm::MachineFrameInfo::needsSplitStackProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6a437bb3c4a44ac328344e5f361c7816">llvm::MachineFunction::push_front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a8efc9cbc802adc2bb2673b4ba6308869">llvm::MachineFunction::verify</a>.</p>

</div>
</div>

### assignCalleeSavedSpillSlots() {#a7c6fdca5f3b44d406ff07e43b2f140f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::assignCalleeSavedSpillSlots (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ad0cd3133a28b196d900d4a2fb49f19e2">llvm::X86MachineFunctionInfo::addCandidateForPush2Pop2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad2270087c6b8d7061c3a5e83fb61c0a6">llvm::MachineFrameInfo::CreateFixedSpillStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a61960903871aa95a7161074c6f1eec8f">llvm::MachineFrameInfo::CreateSpillStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1f09e99062be1101e3a2cf3ff88878f7">llvm::MachineFrameInfo::ensureMaxAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ab47b5e1f45cd8a0fbdd840547e6517af">llvm::X86MachineFunctionInfo::getNumCandidatesForPush2Pop2</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6521d4d5560c03b2e6490883558b882c">llvm::TargetFrameLowering::getOffsetOfLocalArea</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aad8e7e85710893cb7fa03109a108a070">llvm::X86MachineFunctionInfo::getRestoreBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a7c7a3251bd6c1b0b89e5712c89aaa305">llvm::X86MachineFunctionInfo::getTCReturnAddrDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a9bbe23d1b534d969ab8244ae95a15bf7">llvm::X86MachineFunctionInfo::getWinEHXMMSlotInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aa92686e5bcf4b22006a54652f92254df">llvm::X86MachineFunctionInfo::hasSwiftAsyncContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ae61044e0566a5eefd1fd0d2f1fd16805">llvm::X86MachineFunctionInfo::padForPush2Pop2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#af3682a96148f7c1e534dfa7c2726ccec">llvm::X86MachineFunctionInfo::setCalleeSavedFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5ed62fb6fd245cb4efd8ea1bb4d56856">llvm::MachineFrameInfo::setCVBytesOfCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aaa40c0068f7a88682bc61cd9c56fede4">llvm::X86MachineFunctionInfo::setHasSEHFramePtrSave</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a0920abec0037c0cd3eb296f505ffc187">llvm::X86MachineFunctionInfo::setPadForPush2Pop2</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a8109e774fb19e0ec57444aa577358ef4">llvm::X86MachineFunctionInfo::setRestoreBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#af98de3669b3b297736be7a9a77b5caf1">llvm::X86MachineFunctionInfo::setSEHFramePtrSaveIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### BuildCFI() {#aef0079a40a972f2942156b2d73bbf190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::BuildCFI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a> &amp; CFIInst, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flag=<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">MachineInstr::NoFlags</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wraps up getting a CFI index and building a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> for it.</p>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a9d7ee9c6eaabde95dd9695326a77f253">llvm::MCCFIInstruction::getOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaea7047186e58e6304947fbe2b12963ca">llvm::MCCFIInstruction::OpAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a> and <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a>.</p>


<p>Referenced by <a href="#aa5f78769915f0742f77e73e45abab318">eliminateCallFramePseudoInstr</a>, <a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a>, <a href="#acbd4fee4d18fa2066d758dff7168ef36">emitCalleeSavedFrameMovesFullCFA</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>.</p>

</div>
</div>

### canSimplifyCallFramePseudos() {#a0c500b38e3912753a3b7354b88b10993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::canSimplifyCallFramePseudos (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>canSimplifyCallFramePseudos - If there is a reserved call frame, the call frame pseudos can be simplified.</p>


<p>Having a FP, as in the default implementation, is not sufficient here since we can't always use it. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a more nuanced condition.</p>


<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="#a6696e7a9f36d7983d3593e5f4a17831f">hasReservedCallFrame</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### canUseAsEpilogue() {#aae24f16623a7d1df7b850c55694e9d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::canUseAsEpilogue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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


<p>The epilogue will be inserted before the first terminator of that block. This method is used by the shrink-wrapping pass to decide if <span class="doxyComputerOutput">MBB</span> will be correctly handled by the target.</p>


<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad7e593e787ba6a94dbd287c32abe4006">canUseLEAForSPInEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a63bd353ca84282a830d803a6bf9e4c5e">flagsNeedToBePreservedBeforeTheTerminators</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aa92686e5bcf4b22006a54652f92254df">llvm::X86MachineFunctionInfo::hasSwiftAsyncContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>.</p>

</div>
</div>

### canUseAsPrologue() {#a652c5c131aaf585181fb0ff722781118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::canUseAsPrologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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


<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aa92686e5bcf4b22006a54652f92254df">llvm::X86MachineFunctionInfo::hasSwiftAsyncContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### canUseLEAForSPInEpilogue() {#ad7e593e787ba6a94dbd287c32abe4006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::canUseLEAForSPInEpilogue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that LEA can be used on SP in an epilogue sequence for <span class="doxyComputerOutput">MF</span>.</p>

<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>


<p>Referenced by <a href="#aae24f16623a7d1df7b850c55694e9d27">canUseAsEpilogue</a>.</p>

</div>
</div>

### determineCalleeSaves() {#a6cbb50454d9bb068f4ab6b2d08fb7abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::determineCalleeSaves (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SavedRegs, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
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


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### eliminateCallFramePseudoInstr() {#aa5f78769915f0742f77e73e45abab318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator X86FrameLowering::eliminateCallFramePseudoInstr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
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


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3761 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ae31fe0327c2bb8a7d5cfbc532825e5a3">blockEndIsUnreachable</a>, <a href="#aef0079a40a972f2942156b2d73bbf190">BuildCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ad6a85756410e7929f561fc1454069563">llvm::MCCFIInstruction::createAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a2097ca045c7251b81f97c5fc3efdcfc8">llvm::MCCFIInstruction::createGnuArgsSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84ab4fe87e4046ecd1f9f3d96bbf63822b3">llvm::DwarfCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ae14195edab055f9809a0349de0be5cce">llvm::X86MachineFunctionInfo::getHasPushSequences</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="#a6696e7a9f36d7983d3593e5f4a17831f">hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#af1d6349ca67f14c36e41916e41536da4">mergeSPUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>

</div>
</div>

### emitCalleeSavedFrameMoves() {#a6c1f3151b66ea2dfd6a8b9cef815d51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitCalleeSavedFrameMoves (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool IsPrologue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="#aef0079a40a972f2942156b2d73bbf190">BuildCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ac6eb36207cf2c7ebbd9a67e63dcc5568">llvm::MCCFIInstruction::createEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a6a60a82f8cb445e9e7029e38733b2d30">llvm::MCCFIInstruction::createOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a43cce47857fdb1dfec97aeba83ab82a3">llvm::MCCFIInstruction::createRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a64f8c7400de58c117c5af250f000675f">FramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ab35a2bbb33b7a14cf05c24b429e2f593">llvm::X86MachineFunctionInfo::getStackPtrSaveMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>


<p>Referenced by <a href="#acbd4fee4d18fa2066d758dff7168ef36">emitCalleeSavedFrameMovesFullCFA</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a> and <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>.</p>

</div>
</div>

### emitCalleeSavedFrameMovesFullCFA() {#acbd4fee4d18fa2066d758dff7168ef36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitCalleeSavedFrameMovesFullCFA (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI)</td>
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

<p>Emits Dwarf Info specifying offsets of callee saved registers and frame pointer.</p>


<p>This is called only when basic block sections are enabled.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="#aef0079a40a972f2942156b2d73bbf190">BuildCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a6a60a82f8cb445e9e7029e38733b2d30">llvm::MCCFIInstruction::createOffset</a>, <a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a64f8c7400de58c117c5af250f000675f">FramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a> and <a href="#abb804392ca8368795013f2e5dc001ee2">Uses64BitFramePtr</a>.</p>

</div>
</div>

### emitEpilogue() {#a353d6967ff6cb7d22110de97773d65d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aef0079a40a972f2942156b2d73bbf190">BuildCFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a045c9bd8c547ec3f14eba7aedf55a044">calculateSetFPREG</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a43cce47857fdb1dfec97aeba83ab82a3">llvm::MCCFIInstruction::createRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a64f8c7400de58c117c5af250f000675f">FramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ac794820144c3b6fd6caaa134ea23675e">llvm::X86MachineFunctionInfo::getAMXProgModel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ad6e59a435273270b3ef84dc8a841c122">llvm::X86MachineFunctionInfo::getCalleeSavedFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a48597b35dc2ab842232cc2a5c6047401">getLEArOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#abe688d8814460e4a62c6e50b82d1be9a">getPOPOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ab35a2bbb33b7a14cf05c24b429e2f593">llvm::X86MachineFunctionInfo::getStackPtrSaveMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a7c7a3251bd6c1b0b89e5712c89aaa305">llvm::X86MachineFunctionInfo::getTCReturnAddrDelta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aa92686e5bcf4b22006a54652f92254df">llvm::X86MachineFunctionInfo::hasSwiftAsyncContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4a8d56726b9e91d336422a546d126a0f">llvm::MachineFunction::hasWinCFI</a>, <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#adee4182085538431c4a8cb7ffec54783">isFuncletReturnInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7736bfc4c1afef875ecf02f2a7701fe3">llvm::Triple::isOSWindows</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#a8485a5e7c82a6e2b65a859701c4a6cb8">isTailCallOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7aa92628f81845096d30f91faafc41c043">llvm::ManagedRA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#af1d6349ca67f14c36e41916e41536da4">mergeSPUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ad7332117b148c3f93c1d7e58306ee748">llvm::Function::needsUnwindTableEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#ab7147559f9c35cbab44e96ecc2408c90">StackPtr</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a>, <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>, <a href="#abb804392ca8368795013f2e5dc001ee2">Uses64BitFramePtr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>

</div>
</div>

### emitPrologue() {#af2ab7cd691053c57c27e810c549a0300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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


<p>emitPrologue - Push callee-saved registers onto the stack, which automatically adjust the stack pointer.</p>


<p>Adjust the stack pointer to allocate space for local variables. Also emit labels used by the exception handler to generate the exception handling frames.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 1562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a19e260b3bbf8fad8480d151e11919836">llvm::MachineFrameInfo::adjustsStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78637df2e0b9a5e2109af945b0baaf34a68eec46437c384d8dad18d5464ebc35c">llvm::Always</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aef0079a40a972f2942156b2d73bbf190">BuildCFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a045c9bd8c547ec3f14eba7aedf55a044">calculateSetFPREG</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa05b0e25c98ba4300ca28989a35dab72a">llvm::CoreCLR</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a03445be1c81520587d5bb31b353f5558">llvm::MCCFIInstruction::createDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ac6eb36207cf2c7ebbd9a67e63dcc5568">llvm::MCCFIInstruction::createEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a6a60a82f8cb445e9e7029e38733b2d30">llvm::MCCFIInstruction::createOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78637df2e0b9a5e2109af945b0baaf34ad21e9e46158e1ff1c0b2553c4d17cd1b">llvm::DeploymentBased</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo/#a1685e8ca2cc67569dbfdd32ad11cbe70">llvm::WinEHFuncInfo::EHRegNodeFrameIndex</a>, <a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="#a6a6cb0d8b5d8e3b35dee29f5e752d31c">emitStackProbe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a64f8c7400de58c117c5af250f000675f">FramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ad6e59a435273270b3ef84dc8a841c122">llvm::X86MachineFunctionInfo::getCalleeSavedFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a7133d921c103967178f1388c8f273da3">llvm::Module::getCodeViewFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="#a84fbe17f451c957c67de546c98f2b79b">getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a8ed3059d287792eb8e73780ac551e918">llvm::X86MachineFunctionInfo::getHasSEHFramePtrSave</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a39d0dcc2605f63349a774a79927b2209">getMOVriOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6f77e4e800ba4dffd63e8ddb330062aa">llvm::Function::getPersonalityFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#aef1cc59e277ff82741aa24e3e170ee04">getPUSHOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aad8e7e85710893cb7fa03109a108a070">llvm::X86MachineFunctionInfo::getRestoreBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a5e8edced8a4733e0f6d5d1f9a31f16a4">llvm::X86MachineFunctionInfo::getRestoreBasePointerOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a75b0fbc272791b1c8f9acaa3564abddb">llvm::X86MachineFunctionInfo::getSEHFramePtrSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ab35a2bbb33b7a14cf05c24b429e2f593">llvm::X86MachineFunctionInfo::getStackPtrSaveMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a7c7a3251bd6c1b0b89e5712c89aaa305">llvm::X86MachineFunctionInfo::getTCReturnAddrDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#af2f0359e40743109c0db7eeebf23c2e9">llvm::X86MachineFunctionInfo::getUsesRedZone</a>, <a href="#acd3876e593314b23ed0679279ee31dfe">getWin64EHFrameIndexRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a11cf771f7f11ea4fdacdbd5420371172">llvm::MachineFunction::getWinEHFuncInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="#a009e40a8d70eae94c4dc32285c717732">has128ByteRedZone</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac901643b9a98a52b1c323b79f28b8dcc">llvm::MachineFrameInfo::hasCopyImplyingStackAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6a0f6312963ee6fb0969243607174949">llvm::Function::hasPersonalityFn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aa92686e5bcf4b22006a54652f92254df">llvm::X86MachineFunctionInfo::hasSwiftAsyncContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c9fb92464f96c0e0f326d624e82eab">llvm::isAsynchronousEHPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a833aa9ac03a9d223ea251585baaa5642">isEAXLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a74d57d95c26d07b86a63a501e1052739">isOpcodeRep</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a53ca7cff9e929ba372da9780fdd44b02">llvm::MachineRegisterInfo::isReserved</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#af1d6349ca67f14c36e41916e41536da4">mergeSPUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ae39565b585476b7142228e439e80372e">llvm::X86II::MO_GOTPCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aab34bedfd8d86f0adbefe4ae0e708f428">llvm::MSVC_CXX</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ad7332117b148c3f93c1d7e58306ee748">llvm::Function::needsUnwindTableEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78637df2e0b9a5e2109af945b0baaf34a6e7b34fa59e1bd229b207892956dc41c">llvm::Never</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo/#a14648296e0e889504d49ee3aa956663c">llvm::WinEHFuncInfo::PSPSymFrameIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a>, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo/#a38a08c28728c84e59ce6c4ef79bdabcc">llvm::WinEHFuncInfo::SEHSetFrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a330afa0baf556056f9c032480dd57347">llvm::MachineFunction::setHasWinCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af941923e75bebb485321894b2ddbeb0a">llvm::MachineFrameInfo::setOffsetAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae4d51e9e70d6a7fb366f2a09d10a0945">llvm::MachineFrameInfo::setStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aa0d5df8154c4118afbefc1b9e8c6ad02">llvm::X86MachineFunctionInfo::setUsesRedZone</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab499fb31e894a900402d0871eee39b75">llvm::MachineFunction::shouldSplitStack</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#ab7147559f9c35cbab44e96ecc2408c90">StackPtr</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#a66a62a15c006f8bc55698e0bea465699">llvm::TargetOptions::SwiftAsyncFramePointer</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a>, <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>, <a href="#abb804392ca8368795013f2e5dc001ee2">Uses64BitFramePtr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca765508a953368531a7d69d1279e6cfb1">llvm::CallingConv::X86_INTR</a>.</p>

</div>
</div>

### emitSPUpdate() {#aa8a605a58ebdee20705834400bdbb922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitSPUpdate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int64_t NumBytes, bool InEpilogue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a series of instructions to increment / decrement the stack pointer by a constant value.</p>


<p>emitSPUpdate - Emit a series of instructions to increment / decrement the stack pointer by a constant value.</p>


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a9eeab7cb8d11a73a02d732d54f891239">getADDrrOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5e4d7acf58e87826a15b94d37144f2b">llvm::getDefRegState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a39d0dcc2605f63349a774a79927b2209">getMOVriOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ae47fe718044419c88efa13772780b920">getSUBrrOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3a1f79eb5e89f41ad5a3d8e9b2a367a">llvm::getUndefRegState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a833aa9ac03a9d223ea251585baaa5642">isEAXLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#ab7147559f9c35cbab44e96ecc2408c90">StackPtr</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a>, <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a> and <a href="#abb804392ca8368795013f2e5dc001ee2">Uses64BitFramePtr</a>.</p>


<p>Referenced by <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#a94ed22ca5dc3213bfb96e1ddbc41952e">restoreCalleeSavedRegisters</a> and <a href="#afc942a637e5d48a94d4033498b7479dd">spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### emitStackProbe() {#a6a6cb0d8b5d8e3b35dee29f5e752d31c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitStackProbe (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool InProlog, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2097b2a990ffa425c1885d12a5e33ef8">MachineFunction::DebugInstrOperandPair</a> &gt; InstrNum=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target stack probe code.</p>


<p>This is required for all large stack allocations on Windows. The caller is required to materialize the number of bytes to probe in RAX/EAX. <span class="doxyComputerOutput">InstrNum</span> optionally contains a debug-info instruction number for the new stack pointer.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a> and <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a>.</p>


<p>Referenced by <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>.</p>

</div>
</div>

### enableShrinkWrapping() {#a7e24606b8fe6124decedb17e5ffa405e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::enableShrinkWrapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3914 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#aff8632a15d42e54c1367a81afc1b6602">llvm::MCObjectFileInfo::getCompactUnwindSection</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca20ddc463f96d806f369d56205ea205f5">llvm::CallingConv::HiPE</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab499fb31e894a900402d0871eee39b75">llvm::MachineFunction::shouldSplitStack</a>.</p>

</div>
</div>

### getDwarfFrameBase() {#aca49f4bdff5eb8f32e4b650f33d6f98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetFrameLowering::DwarfFrameBase X86FrameLowering::getDwarfFrameBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return the frame base information to be encoded in the DWARF subprogram debug info.</p>

<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aefb3b77455d0e0f2e1e8b56604c63c0c">llvm::TargetRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a5f9f26d96deb10d0d3b394fe12e2b0f5">getInitialCFAOffset</a>, <a href="#abac406e51bd21d4da6eb9762f2f36df6">getInitialCFARegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a7aec3b56c5a4ee2489363834a3b6ca99">llvm::X86MachineFunctionInfo::hasCFIAdjustCfa</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#ab9d82d53acc347a5ab75ea59da93c298">llvm::TargetFrameLowering::DwarfFrameBase::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#a82acb7f3bcf1d1f621a2afbcc936e85b">llvm::TargetFrameLowering::DwarfFrameBase::Location</a> and <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#a0f3e9e851be1c3d4d7276752c0c2d330">llvm::TargetFrameLowering::DwarfFrameBase::Offset</a>.</p>

</div>
</div>

### getFrameIndexReference() {#a84fbe17f451c957c67de546c98f2b79b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset X86FrameLowering::getFrameIndexReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; FrameReg)</td>
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


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a045c9bd8c547ec3f14eba7aedf55a044">calculateSetFPREG</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ad6e59a435273270b3ef84dc8a841c122">llvm::X86MachineFunctionInfo::getCalleeSavedFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a7024c419adc3f16454faa53af71fb515">llvm::X86MachineFunctionInfo::getFAIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6521d4d5560c03b2e6490883558b882c">llvm::TargetFrameLowering::getOffsetOfLocalArea</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aad8e7e85710893cb7fa03109a108a070">llvm::X86MachineFunctionInfo::getRestoreBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a7c7a3251bd6c1b0b89e5712c89aaa305">llvm::X86MachineFunctionInfo::getTCReturnAddrDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca765508a953368531a7d69d1279e6cfb1">llvm::CallingConv::X86_INTR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#afb20caf4eb8695705452f25d78a18a06">getFrameIndexReferencePreferSP</a>, <a href="#acd3876e593314b23ed0679279ee31dfe">getWin64EHFrameIndexRef</a> and <a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a>.</p>

</div>
</div>

### getFrameIndexReferencePreferSP() {#afb20caf4eb8695705452f25d78a18a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset X86FrameLowering::getFrameIndexReferencePreferSP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; FrameReg, bool IgnoreSPUpdates)</td>
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

<p>Same as <span class="doxyComputerOutput">getFrameIndexReference</span>, except that the stack pointer (as opposed to the frame pointer) will be the preferred value for <span class="doxyComputerOutput">FrameReg</span>.</p>


<p>This is generally used for emitting statepoint or EH tables that use offsets from RSP. If <span class="doxyComputerOutput">IgnoreSPUpdates</span> is true, the returned offset is only guaranteed to be valid with respect to the value of SP at the end of the prologue.</p>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a84fbe17f451c957c67de546c98f2b79b">getFrameIndexReference</a>, <a href="#a79ebbed1ceecae3f74214e33fc8c533f">getFrameIndexReferenceSP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a7c7a3251bd6c1b0b89e5712c89aaa305">llvm::X86MachineFunctionInfo::getTCReturnAddrDelta</a>, <a href="#a6696e7a9f36d7983d3593e5f4a17831f">hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### getFrameIndexReferenceSP() {#a79ebbed1ceecae3f74214e33fc8c533f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset X86FrameLowering::getFrameIndexReferenceSP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SPReg, int Adjustment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2734 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6521d4d5560c03b2e6490883558b882c">llvm::TargetFrameLowering::getOffsetOfLocalArea</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a> and <a href="#afb20caf4eb8695705452f25d78a18a06">getFrameIndexReferencePreferSP</a>.</p>

</div>
</div>

### getInitialCFAOffset() {#a5f9f26d96deb10d0d3b394fe12e2b0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int X86FrameLowering::getInitialCFAOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return initial CFA offset value i.e.</p>


<p>the one valid at the beginning of the function (before any stack operations).</p>


<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>Reference <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>


<p>Referenced by <a href="#aca49f4bdff5eb8f32e4b650f33d6f98e">getDwarfFrameBase</a>.</p>

</div>
</div>

### getInitialCFARegister() {#abac406e51bd21d4da6eb9762f2f36df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register X86FrameLowering::getInitialCFARegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return initial CFA register value i.e.</p>


<p>the one valid at the beginning of the function (before any stack operations).</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>Reference <a href="#ab7147559f9c35cbab44e96ecc2408c90">StackPtr</a>.</p>


<p>Referenced by <a href="#aca49f4bdff5eb8f32e4b650f33d6f98e">getDwarfFrameBase</a>.</p>

</div>
</div>

### getWin64EHFrameIndexRef() {#acd3876e593314b23ed0679279ee31dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int X86FrameLowering::getWin64EHFrameIndexRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SPReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="#a84fbe17f451c957c67de546c98f2b79b">getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a4f335273c28b17552a7cfd802f42be2a">llvm::MachineFrameInfo::getMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a9bbe23d1b534d969ab8244ae95a15bf7">llvm::X86MachineFunctionInfo::getWinEHXMMSlotInfo</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a> and <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>.</p>

</div>
</div>

### getWinEHParentFrameOffset() {#ac7b381a1c38101d4e17121c7b993e00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FrameLowering::getWinEHParentFrameOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>.</p>

</div>
</div>

### has128ByteRedZone() {#a009e40a8d70eae94c4dc32285c717732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::has128ByteRedZone (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the function has a redzone (accessible bytes past the frame of the top of stack function) as part of it's ABI.</p>

<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="#ab69c52bac76806c714de3de7674d8f31">Is64Bit</a> and <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a50dbd5a76550f7eac8bc29cb7811b2d5">emitLockedStackOp</a> and <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>.</p>

</div>
</div>

### hasReservedCallFrame() {#a6696e7a9f36d7983d3593e5f4a17831f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::hasReservedCallFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>.</p>


<p>Referenced by <a href="#a0c500b38e3912753a3b7354b88b10993">canSimplifyCallFramePseudos</a>, <a href="#aa5f78769915f0742f77e73e45abab318">eliminateCallFramePseudoInstr</a> and <a href="#afb20caf4eb8695705452f25d78a18a06">getFrameIndexReferencePreferSP</a>.</p>

</div>
</div>

### inlineStackProbe() {#a91705445bd9fc240a0092580cab1d092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::inlineStackProbe (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PrologMBB)</td>
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

<p>Replace a StackProbe inline-stub with the actual probe code inline.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab622d694b5fcb0edb99159f1ebdcdb6b">llvm::MachineBasicBlock::findDebugLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### mergeSPUpdates() {#af1d6349ca67f14c36e41916e41536da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int X86FrameLowering::mergeSPUpdates (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MBBI, bool doMergeWithPrevious)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the instruction before/after the passed instruction.</p>


<p>If it is an ADD/SUB/LEA instruction it is deleted argument and the stack adjustment is returned as a positive value for ADD/LEA and a negative for SUB.</p>


<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a9d7ee9c6eaabde95dd9695326a77f253">llvm::MCCFIInstruction::getOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaea7047186e58e6304947fbe2b12963ca">llvm::MCCFIInstruction::OpAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca5822faf65b27795cd48bd44712d48927">llvm::MCCFIInstruction::OpDefCfaOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9256279285c60fce1b2eb1b928599461">llvm::skipDebugInstructionsBackward</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a> and <a href="#ab7147559f9c35cbab44e96ecc2408c90">StackPtr</a>.</p>


<p>Referenced by <a href="#aa5f78769915f0742f77e73e45abab318">eliminateCallFramePseudoInstr</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a> and <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>.</p>

</div>
</div>

### needsFrameIndexResolution() {#a0d66887ade3ca46870e0921376f86fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::needsFrameIndexResolution (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#acb35f7f6a131a64e636d936246ebd37f">llvm::MachineFrameInfo::hasStackObjects</a>.</p>

</div>
</div>

### orderFrameObjects() {#adee8390bf727c3086a7b864de6c6913e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::orderFrameObjects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; ObjectsToAllocate)</td>
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

<p>Order the symbols in the local stack.</p>


<p>We want to place the local stack objects in some sort of sensible order. The heuristic we use is to try and pack them according to static number of uses and size in order to minimize code size.</p>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac51e2d34abb79b72afef355fac525c76">llvm::MachineFrameInfo::getObjectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### processFunctionBeforeFrameFinalized() {#a6a8d1523f211998978b3fa0bfe8818a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::processFunctionBeforeFrameFinalized (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1f09e99062be1101e3a2cf3ff88878f7">llvm::MachineFrameInfo::ensureMaxAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6f77e4e800ba4dffd63e8ddb330062aa">llvm::Function::getPersonalityFn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aab34bedfd8d86f0adbefe4ae0e708f428">llvm::MSVC_CXX</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a330afa0baf556056f9c032480dd57347">llvm::MachineFunction::setHasWinCFI</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>

</div>
</div>

### processFunctionBeforeFrameIndicesReplaced() {#af7d9e67f21b6a4968a6074b082944dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::processFunctionBeforeFrameIndicesReplaced (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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

<p>processFunctionBeforeFrameIndicesReplaced - This method is called immediately before MO_FrameIndex operands are eliminated, but after the frame is finalized.</p>


<p>This method is optional.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ab35a2bbb33b7a14cf05c24b429e2f593">llvm::X86MachineFunctionInfo::getStackPtrSaveMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#afc0900cd962cd955b2b6de25731710f5">restoreWinEHStackPointersInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aefa6fd7c14db84eada72c79be21b2ad5">llvm::X86MachineFunctionInfo::setStackPtrSaveMI</a> and <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>.</p>

</div>
</div>

### restoreCalleeSavedRegisters() {#a94ed22ca5dc3213bfb96e1ddbc41952e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::restoreCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aae2bf8b46988a2fc0589e95903930c19">llvm::MutableArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a9d959094f4544749c129c46034cbed67">llvm::MutableArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ae299adbcf2ff9ecc484dc4b73d262eaa">getPOP2Opcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#abe688d8814460e4a62c6e50b82d1be9a">getPOPOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aad8e7e85710893cb7fa03109a108a070">llvm::X86MachineFunctionInfo::getRestoreBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c9fb92464f96c0e0f326d624e82eab">llvm::isAsynchronousEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a2bfcb8851d30d4d3ac6b27a82e7f85f7">llvm::X86MachineFunctionInfo::isCandidateForPush2Pop2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#adee4182085538431c4a8cb7ffec54783">isFuncletReturnInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ae61044e0566a5eefd1fd0d2f1fd16805">llvm::X86MachineFunctionInfo::padForPush2Pop2</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### restoreWin32EHStackPointers() {#a535388ac574e0f8d844662d315997b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator X86FrameLowering::restoreWin32EHStackPointers (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool RestoreSP=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets up EBP and optionally ESI based on the incoming EBP value.</p>


<p>Only needed for 32-bit. Used in funclet prologues and at catchret destinations.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a64f8c7400de58c117c5af250f000675f">FramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a1ecf75331d34e66af2a1ecb91a339090">getADDriOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#aeb11e994c5580c80bbb0951eb05f9c80">llvm::StackOffset::getFixed</a>, <a href="#a84fbe17f451c957c67de546c98f2b79b">getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a8ed3059d287792eb8e73780ac551e918">llvm::X86MachineFunctionInfo::getHasSEHFramePtrSave</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a75b0fbc272791b1c8f9acaa3564abddb">llvm::X86MachineFunctionInfo::getSEHFramePtrSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a11cf771f7f11ea4fdacdbd5420371172">llvm::MachineFunction::getWinEHFuncInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a>, <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a> and <a href="#abb804392ca8368795013f2e5dc001ee2">Uses64BitFramePtr</a>.</p>


<p>Referenced by <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a> and <a href="#afc0900cd962cd955b2b6de25731710f5">restoreWinEHStackPointersInParent</a>.</p>

</div>
</div>

### restoreWinEHStackPointersInParent() {#afc0900cd962cd955b2b6de25731710f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::restoreWinEHStackPointersInParent (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6f77e4e800ba4dffd63e8ddb330062aa">llvm::Function::getPersonalityFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c9fb92464f96c0e0f326d624e82eab">llvm::isAsynchronousEHPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a>.</p>


<p>Referenced by <a href="#af7d9e67f21b6a4968a6074b082944dc6">processFunctionBeforeFrameIndicesReplaced</a>.</p>

</div>
</div>

### spillCalleeSavedRegisters() {#afc942a637e5d48a94d4033498b7479dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::spillCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2984 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a2621d6b164bd8fb5ef4356154ea9b399">getPUSH2Opcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#aef1cc59e277ff82741aa24e3e170ee04">getPUSHOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aad8e7e85710893cb7fa03109a108a070">llvm::X86MachineFunctionInfo::getRestoreBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a2bfcb8851d30d4d3ac6b27a82e7f85f7">llvm::X86MachineFunctionInfo::isCandidateForPush2Pop2</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ae61044e0566a5eefd1fd0d2f1fd16805">llvm::X86MachineFunctionInfo::padForPush2Pop2</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebe6da1ab4a07020669f3d6148c0b559">llvm::ArrayRef&lt; T &gt;::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a709f5d7f042648ec20197939d9a6805f">llvm::ArrayRef&lt; T &gt;::rend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="#a926474da108c2083d64a3a03742677ae">SlotSize</a>, <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### spillFPBP() {#a068e9d1fd54621ae340f26c41d170a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::spillFPBP (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>If a function uses base pointer and the base pointer is clobbered by inline asm, RA doesn't detect this case, and after the inline asm, the base pointer contains garbage value.</p>


<p>For example if a 32b x86 function uses base pointer esi, and esi is clobbered by following inline asm asm("rep movsb" : "+D"(ptr), "+S"(x), "+c"(c)::"memory"); We need to save esi before the asm and restore it after the asm.</p>


<p>The problem can also occur to frame pointer if there is a function call, and the callee uses a different calling convention and clobbers the fp.</p>


<p>Because normal frame objects (spill slots) are accessed through fp/bp register, so we can't spill fp/bp to normal spill slots.</p>


<p>FIXME: There are 2 possible enhancements:</p>


<ol class="doxyList" type="1">
<li>In many cases there are different physical registers not clobbered by inline asm, we can use one of them as base pointer. Or use a virtual register as base pointer and let RA allocate a physical register to it.</li>
<li>If there is no other instructions access stack with fp/bp from the inline asm to the epilog, and no cfi requirement for a correct fp, we can skip the save and restore operations.</li>
</ol>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a9f3bec55d4dcb107b606a8ff918f7567">llvm::X86MachineFunctionInfo::getBPClobberedByCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a43bece9f74d59569cf44bfa0cd162496">llvm::X86MachineFunctionInfo::getFPClobberedByCall</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ac83b44e69c9f9f4f9d60be2d72f4a5df">llvm::TargetSubtargetInfo::getFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4070e578614e01d4c3f4aae3df10304c">llvm::MachineFunction::hasInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a63e534b2d2892aadaa791d48b0397c74">isFPBPAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#acc62a034274e2d51b819c39b96de48dd">isInvoke</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6a6d31b2f1e5754f5824c5dec555eeac">llvm::TargetFrameLowering::TargetFrameLowering</a>, <a href="#a9eb08d8f7165ce65d875c2329952262b">TII</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

### stackProbeFunctionModifiesSP() {#ad88384d07e66c382b05f793848660d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::stackProbeFunctionModifiesSP ()</td>
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

<p>Does the stack probe function call return with a modified stack pointer?</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>Reference <a href="#afeee4b43efe13447f760c28d545fe653">STI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### hasFPImpl() {#a493d9a8215b5ec117b32762217d66f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::hasFPImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>hasFPImpl - Return true if the specified function should have a dedicated frame pointer register.</p>


<p>This is true if the function has variable sized allocas or if frame pointer elimination is disabled.</p>


<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a768ff6dfb15d23afedd7f07501afee9e">llvm::MachineFunction::callsEHReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6799fb8536b173a2078ef97e1f0d16ec">llvm::MachineFunction::callsUnwindInit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a046dd28b46bd584d050eca36d081c372">llvm::X86MachineFunctionInfo::getForceFramePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac901643b9a98a52b1c323b79f28b8dcc">llvm::MachineFrameInfo::hasCopyImplyingStackAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a51773b6c05f392988bf6395ccd1788ce">llvm::MachineFrameInfo::hasOpaqueSPAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a503a8cb169aa29ac907c218692087db3">llvm::MachineFrameInfo::hasPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#aa136a47fd323997cfe9d1ac8419ede8f">llvm::X86MachineFunctionInfo::hasPreallocatedCall</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa7d9e2f26e4c8b32f51c455b220ce13c">llvm::MachineFrameInfo::hasStackMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="#a1b652b91e12384b9f49bb38521b78ffe">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### adjustFrameForMsvcCxxEh() {#a9ebeb032a4a9c27af284212d5051f2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::adjustFrameForMsvcCxxEh (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### adjustStackWithPops() {#a3a2c36b5d0d1f8f63e3e5280f2dff710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::adjustStackWithPops (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make small positive stack adjustments using POPs.</p>

<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3687 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### BuildStackAdjustment() {#a7f118647874ff018b75856624c38dd08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder X86FrameLowering::BuildStackAdjustment (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int64_t Offset, bool InEpilogue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adjusts the stack pointer using LEA, SUB, or ADD.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### BuildStackAlignAND() {#a2b16c050e22b49ccaed8174396c64aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::BuildStackAlignAND (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, unsigned Reg, uint64_t MaxAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Aligns the stack pointer by ANDing it with -MaxAlign.</p>

<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### calculateMaxStackAlign() {#afa1feb8d8cc6107264ab7c1394b01d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t X86FrameLowering::calculateMaxStackAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### checkInterferedAccess() {#aec08de73f8475855b8eb6720fcc7f263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::checkInterferedAccess (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#abada92f8cd2854d2b747f14c4a7be0ed">MachineBasicBlock::reverse_iterator</a> DefMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#abada92f8cd2854d2b747f14c4a7be0ed">MachineBasicBlock::reverse_iterator</a> KillMI, bool SpillFP, bool SpillBP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given the live range of FP or BP (DefMI, KillMI), check if there is any interfered stack access in the range, usually generated by register spill.</p>

<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitCatchRetReturnValue() {#aa5cc324c3010ff1c9ea386c02e165ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitCatchRetReturnValue (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CatchRet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Materialize the catchret target MBB in RAX.</p>

<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 3074 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitStackProbeCall() {#a1e4ecee50166bf8fcaeb2c8f03304581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitStackProbeCall (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool InProlog, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2097b2a990ffa425c1885d12a5e33ef8">MachineFunction::DebugInstrOperandPair</a> &gt; InstrNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target stack probe as a call to a helper function.</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitStackProbeInline() {#ada3420cb1df4417aa90fe0698f6cc3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitStackProbeInline (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool InProlog)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target stack probe as an inline sequence.</p>

<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitStackProbeInlineGeneric() {#a82bede7e1fb4696cb037cc72065c88a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitStackProbeInlineGeneric (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool InProlog)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitStackProbeInlineGenericBlock() {#a645e4e238e6594dd9816b24dc62a4f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitStackProbeInlineGenericBlock (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, uint64_t Offset, uint64_t Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitStackProbeInlineGenericLoop() {#a9aac1740e736ea330beb84b387a9818b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitStackProbeInlineGenericLoop (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, uint64_t Offset, uint64_t Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitStackProbeInlineWindowsCoreCLR64() {#a43619cbca9b358a92076bd02945a88bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitStackProbeInlineWindowsCoreCLR64 (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, bool InProlog)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### emitZeroCallUsedRegs() {#aba9b90da06993d722a55cf56d9f6c7b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::emitZeroCallUsedRegs (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> RegsToZero, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Emit target zero call-used regs.</p>

<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### getPSPSlotOffsetFromSP() {#abb1648550ec282b6dcf1b5fa8dbc4ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FrameLowering::getPSPSlotOffsetFromSP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### getWinEHFuncletFrameSize() {#ae51a715a851d665a5f98e0125bdb4f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FrameLowering::getWinEHFuncletFrameSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 2342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### isWin64Prologue() {#af638105f984cedc23b3245bc9229e236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::isWin64Prologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we need to use the restricted Windows x64 prologue and epilogue code patterns that can be described with WinCFI (.seh_* directives).</p>

<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 1441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### needsDwarfCFI() {#af0c6fc5253875c943f364255766f388f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::needsDwarfCFI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 1445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### restoreFPBPUsingSP() {#a355e7b8668257cd522c34492f06e880d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::restoreFPBPUsingSP (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> AfterMI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FP, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BP, int SPAdjust)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Issue instructions to restore frame pointer and/or base pointer from stack using stack pointer register, and free stack space.</p>

<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### saveAndRestoreFPBPUsingSP() {#a71fcd1fe99e4f0c613775f548f1c3adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::saveAndRestoreFPBPUsingSP (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> BeforeMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> AfterMI, bool SpillFP, bool SpillBP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### skipSpillFPBP() {#a119ea4a6b09a7301ccedb02f4addc79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FrameLowering::skipSpillFPBP (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#abada92f8cd2854d2b747f14c4a7be0ed">MachineBasicBlock::reverse_iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

### spillFPBPUsingSP() {#a5015b24b5088c73f49a18ff556ec4af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86FrameLowering::spillFPBPUsingSP (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> BeforeMI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FP, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BP, int SPAdjust)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Issue instructions to allocate stack space and spill frame pointer and/or base pointer to stack using stack pointer register.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>, definition at line 4279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Is64Bit {#ab69c52bac76806c714de3de7674d8f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86FrameLowering::Is64Bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is64Bit implies that x86_64 instructions are available.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#afd992a2165073c9cea53128d5b6c4145">adjustForHiPEPrologue</a>, <a href="#ac8faf9a625064bfefafb7ace646815ff">adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a>, <a href="#acbd4fee4d18fa2066d758dff7168ef36">emitCalleeSavedFrameMovesFullCFA</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="#a009e40a8d70eae94c4dc32285c717732">has128ByteRedZone</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

### IsLP64 {#a7761d9f26e6c0722ee9c9d8c5e052c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86FrameLowering::IsLP64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#afd992a2165073c9cea53128d5b6c4145">adjustForHiPEPrologue</a>, <a href="#ac8faf9a625064bfefafb7ace646815ff">adjustForSegmentedStacks</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

### SlotSize {#a926474da108c2083d64a3a03742677ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86FrameLowering::SlotSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#afd992a2165073c9cea53128d5b6c4145">adjustForHiPEPrologue</a>, <a href="#a7c6fdca5f3b44d406ff07e43b2f140f6">assignCalleeSavedSpillSlots</a>, <a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="#a84fbe17f451c957c67de546c98f2b79b">getFrameIndexReference</a>, <a href="#ac7b381a1c38101d4e17121c7b993e00c">getWinEHParentFrameOffset</a>, <a href="#a6a8d1523f211998978b3fa0bfe8818a1">processFunctionBeforeFrameFinalized</a>, <a href="#a94ed22ca5dc3213bfb96e1ddbc41952e">restoreCalleeSavedRegisters</a>, <a href="#afc942a637e5d48a94d4033498b7479dd">spillCalleeSavedRegisters</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

### StackPtr {#ab7147559f9c35cbab44e96ecc2408c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86FrameLowering::StackPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="#abac406e51bd21d4da6eb9762f2f36df6">getInitialCFARegister</a>, <a href="#af1d6349ca67f14c36e41916e41536da4">mergeSPUpdates</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

### STI {#afeee4b43efe13447f760c28d545fe653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget&amp; llvm::X86FrameLowering::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#afd992a2165073c9cea53128d5b6c4145">adjustForHiPEPrologue</a>, <a href="#ac8faf9a625064bfefafb7ace646815ff">adjustForSegmentedStacks</a>, <a href="#a7c6fdca5f3b44d406ff07e43b2f140f6">assignCalleeSavedSpillSlots</a>, <a href="#aae24f16623a7d1df7b850c55694e9d27">canUseAsEpilogue</a>, <a href="#a652c5c131aaf585181fb0ff722781118">canUseAsPrologue</a>, <a href="#a6cbb50454d9bb068f4ab6b2d08fb7abf">determineCalleeSaves</a>, <a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a>, <a href="#acbd4fee4d18fa2066d758dff7168ef36">emitCalleeSavedFrameMovesFullCFA</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="#a6a6cb0d8b5d8e3b35dee29f5e752d31c">emitStackProbe</a>, <a href="#afb20caf4eb8695705452f25d78a18a06">getFrameIndexReferencePreferSP</a>, <a href="#a009e40a8d70eae94c4dc32285c717732">has128ByteRedZone</a>, <a href="#a6a8d1523f211998978b3fa0bfe8818a1">processFunctionBeforeFrameFinalized</a>, <a href="#af7d9e67f21b6a4968a6074b082944dc6">processFunctionBeforeFrameIndicesReplaced</a>, <a href="#a94ed22ca5dc3213bfb96e1ddbc41952e">restoreCalleeSavedRegisters</a>, <a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a>, <a href="#afc942a637e5d48a94d4033498b7479dd">spillCalleeSavedRegisters</a>, <a href="#ad88384d07e66c382b05f793848660d90">stackProbeFunctionModifiesSP</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

### TII {#a9eb08d8f7165ce65d875c2329952262b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrInfo&amp; llvm::X86FrameLowering::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#afd992a2165073c9cea53128d5b6c4145">adjustForHiPEPrologue</a>, <a href="#ac8faf9a625064bfefafb7ace646815ff">adjustForSegmentedStacks</a>, <a href="#aef0079a40a972f2942156b2d73bbf190">BuildCFI</a>, <a href="#aa5f78769915f0742f77e73e45abab318">eliminateCallFramePseudoInstr</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="#a6a6cb0d8b5d8e3b35dee29f5e752d31c">emitStackProbe</a>, <a href="#a94ed22ca5dc3213bfb96e1ddbc41952e">restoreCalleeSavedRegisters</a>, <a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a>, <a href="#afc942a637e5d48a94d4033498b7479dd">spillCalleeSavedRegisters</a>, <a href="#a068e9d1fd54621ae340f26c41d170a1a">spillFPBP</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

### TRI {#a1b652b91e12384b9f49bb38521b78ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86RegisterInfo* llvm::X86FrameLowering::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#a7c6fdca5f3b44d406ff07e43b2f140f6">assignCalleeSavedSpillSlots</a>, <a href="#a0c500b38e3912753a3b7354b88b10993">canSimplifyCallFramePseudos</a>, <a href="#a652c5c131aaf585181fb0ff722781118">canUseAsPrologue</a>, <a href="#a6cbb50454d9bb068f4ab6b2d08fb7abf">determineCalleeSaves</a>, <a href="#a6c1f3151b66ea2dfd6a8b9cef815d51c">emitCalleeSavedFrameMoves</a>, <a href="#acbd4fee4d18fa2066d758dff7168ef36">emitCalleeSavedFrameMovesFullCFA</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="#a84fbe17f451c957c67de546c98f2b79b">getFrameIndexReference</a>, <a href="#afb20caf4eb8695705452f25d78a18a06">getFrameIndexReferencePreferSP</a>, <a href="#a79ebbed1ceecae3f74214e33fc8c533f">getFrameIndexReferenceSP</a>, <a href="#a5f9f26d96deb10d0d3b394fe12e2b0f5">getInitialCFAOffset</a>, <a href="#acd3876e593314b23ed0679279ee31dfe">getWin64EHFrameIndexRef</a>, <a href="#a493d9a8215b5ec117b32762217d66f80">hasFPImpl</a>, <a href="#adee8390bf727c3086a7b864de6c6913e">orderFrameObjects</a>, <a href="#a94ed22ca5dc3213bfb96e1ddbc41952e">restoreCalleeSavedRegisters</a>, <a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a>, <a href="#afc942a637e5d48a94d4033498b7479dd">spillCalleeSavedRegisters</a>, <a href="#a068e9d1fd54621ae340f26c41d170a1a">spillFPBP</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

### Uses64BitFramePtr {#abb804392ca8368795013f2e5dc001ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86FrameLowering::Uses64BitFramePtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the 64-bit frame or stack pointer should be used.</p>


<p>True for most 64-bit targets with the exception of x32. If this is false, 32-bit instruction operands should be used to manipulate StackPtr and FramePtr.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a>.</p>


<p>Referenced by <a href="#acbd4fee4d18fa2066d758dff7168ef36">emitCalleeSavedFrameMovesFullCFA</a>, <a href="#a353d6967ff6cb7d22110de97773d65d8">emitEpilogue</a>, <a href="#af2ab7cd691053c57c27e810c549a0300">emitPrologue</a>, <a href="#aa8a605a58ebdee20705834400bdbb922">emitSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a080a45c15fffba2e3b64ca45ff9fe069">llvm::X86RegisterInfo::getPointerRegClass</a>, <a href="#a535388ac574e0f8d844662d315997b3d">restoreWin32EHStackPointers</a> and <a href="#a116242916a44a6d4f5301270c6c4f05e">X86FrameLowering</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp">X86FrameLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-h">X86FrameLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
