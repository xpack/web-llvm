---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcframelowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCFrameLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PPCFrameLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">Target/PowerPC/PPCFrameLowering.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc927cacd0c354e0916debf44258dd5e">PPCFrameLowering</a> (const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bca3a5e9c1e69593d1f15b4cb1c44c">determineFrameLayoutAndUpdate</a> (MachineFunction &amp;MF, bool UseEstimate=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the frame layout and update the machine function. <a href="#ad5bca3a5e9c1e69593d1f15b4cb1c44c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2efa5f4dacdde70f912da43c1f8ffcf">determineFrameLayout</a> (const MachineFunction &amp;MF, bool UseEstimate=false, unsigned *NewMaxCallFrameSize=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the frame layout but do not update the machine function. <a href="#ac2efa5f4dacdde70f912da43c1f8ffcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa670bf850cd6767f78408604873036f7">emitPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitProlog/emitEpilog - These methods insert prolog and epilog code into the function. <a href="#aa670bf850cd6767f78408604873036f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e6ca2286bfbfa6952e74370a9c563b">emitEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a5a3bd252aaac7b161ad8c01cf0951">inlineStackProbe</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;PrologMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a StackProbe stub (if any) with the actual probe code inline. <a href="#af0a5a3bd252aaac7b161ad8c01cf0951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b74a0fb5ceb4340d1d7a6f809e0a28">needsFP</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb33f3f153c050bf1a63bcd8223e836">replaceFPWithRealFP</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88484d585ecc86920ebee6396946eae2">determineCalleeSaves</a> (MachineFunction &amp;MF, BitVector &amp;SavedRegs, RegScavenger *RS=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method determines which of the registers reported by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">TargetRegisterInfo::getCalleeSavedRegs()</a> should actually get saved. <a href="#a88484d585ecc86920ebee6396946eae2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f176ff8abd35fbe2f043c22d088302e">processFunctionBeforeFrameFinalized</a> (MachineFunction &amp;MF, RegScavenger *RS=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processFunctionBeforeFrameFinalized - This method is called immediately before the specified function's frame layout (MF.getFrameInfo()) is finalized. <a href="#a3f176ff8abd35fbe2f043c22d088302e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65455efc149d81b4d1418acae7596b3">addScavengingSpillSlot</a> (MachineFunction &amp;MF, RegScavenger *RS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ba26b731da85ec85d9f4ebb7d27e02">spillCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, ArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spillCalleeSavedRegisters - Issues instruction(s) to spill all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of store instructions via storeRegToStackSlot(). <a href="#a42ba26b731da85ec85d9f4ebb7d27e02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace3b0eb52be3988997a7f6e4a5b59aab">assignCalleeSavedSpillSlots</a> (MachineFunction &amp;MF, const TargetRegisterInfo *TRI, std::vector&lt; CalleeSavedInfo &gt; &amp;CSI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will assign callee saved gprs to volatile vector registers for prologue spills when applicable. <a href="#ace3b0eb52be3988997a7f6e4a5b59aab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c498f1fcb62301a44ad58e2dc8e7fc">eliminateCallFramePseudoInstr</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called during prolog/epilog code insertion to eliminate call frame setup and destroy pseudo instructions (but only if the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> is using them). <a href="#a63c498f1fcb62301a44ad58e2dc8e7fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae5bad356a0c0583ebad92fbe899230c">restoreCalleeSavedRegisters</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, MutableArrayRef&lt; CalleeSavedInfo &gt; CSI, const TargetRegisterInfo *TRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>restoreCalleeSavedRegisters - Issues instruction(s) to restore all callee saved registers and returns true if it isn't possible / profitable to do so by issuing a series of load instructions via loadRegToStackSlot(). <a href="#aae5bad356a0c0583ebad92fbe899230c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2094cef29f00243385de148a1900e599">targetHandlesStackFrameRounding</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>targetHandlesStackFrameRounding - Returns true if the target is responsible for rounding up the stack frame (probably at emitPrologue time). <a href="#a2094cef29f00243385de148a1900e599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebd660e4b649282aa3b4ea870909ef1">getReturnSaveOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getReturnSaveOffset - Return the previous frame offset to save the return address. <a href="#a0ebd660e4b649282aa3b4ea870909ef1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c21693e6284bea34b3ebbece45efdd">getTOCSaveOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTOCSaveOffset - Return the previous frame offset to save the TOC register – 64-bit SVR4 ABI only. <a href="#af2c21693e6284bea34b3ebbece45efdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4140e94a76010e9dc920504d1acbb5d9">getFramePointerSaveOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFramePointerSaveOffset - Return the previous frame offset to save the frame pointer. <a href="#a4140e94a76010e9dc920504d1acbb5d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea9064376aa194c66fa3770d5904bf2">getBasePointerSaveOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getBasePointerSaveOffset - Return the previous frame offset to save the base pointer. <a href="#afea9064376aa194c66fa3770d5904bf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ec4d7eb2c3cc1d2d6cac266d4ea3eb">getLinkageSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLinkageSize - Return the size of the PowerPC ABI linkage area. <a href="#a50ec4d7eb2c3cc1d2d6cac266d4ea3eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/spillslot">SpillSlot</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a821743cb2c878d23ca01bb9b6c0ba">getCalleeSavedSpillSlots</a> (unsigned &amp;NumEntries) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCalleeSavedSpillSlots - This method returns a pointer to an array of pairs, that contains an entry for each callee saved register that must be spilled to a particular stack location if it is spilled. <a href="#a83a821743cb2c878d23ca01bb9b6c0ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e10b8a8fa4bda2b86f716b82032b1e">enableShrinkWrapping</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target will correctly handle shrink wrapping. <a href="#ac0e10b8a8fa4bda2b86f716b82032b1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a7a25670315a8393e0bc768526559c">canUseAsPrologue</a> (const MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods used by shrink wrapping to determine if MBB can be used for the function prologue/epilogue. <a href="#a99a7a25670315a8393e0bc768526559c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9566508140cc03db82c98053ef74be">canUseAsEpilogue</a> (const MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not the given <span class="doxyComputerOutput">MBB</span> can be used as a epilogue for the target. <a href="#a2c9566508140cc03db82c98053ef74be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add05bb6a2fc43dfa726b8a1a02d1b4c0">updateCalleeSaves</a> (const MachineFunction &amp;MF, BitVector &amp;SavedRegs) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd3c8e286f88d8f80913526cf5105e6">getStackThreshold</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStackThreshold - Return the maximum stack size <a href="#a2cd3c8e286f88d8f80913526cf5105e6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fdbbb3f732425b06a8a7526b1e49e7a">hasFPImpl</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047d552c2558a05e834ccd1bd0750b69">findScratchRegister</a> (MachineBasicBlock *MBB, bool UseAtEnd, bool TwoUniqueRegsRequired=false, Register *SR1=nullptr, Register *SR2=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find register[s] that can be used in function prologue and epilogue. <a href="#a047d552c2558a05e834ccd1bd0750b69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6b45d13414d0b730efff3d8cae83b4">twoUniqueScratchRegsRequired</a> (MachineBasicBlock *MBB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d19fc3f98636936e5c13e7d9988a34">createTailCallBranchInstr</a> (MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create branch instruction for PPC::TCRETURN* (tail call return) <a href="#a45d19fc3f98636936e5c13e7d9988a34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9f51db328b07b1943516a7c93913ea">stackUpdateCanBeMoved</a> (MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the conditions are correct to allow for the stack update to be moved past the CSR save/restore code. <a href="#adc9f51db328b07b1943516a7c93913ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaea8d2188fadc14aae892f001f13a10">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ecced2df1a2f272a1f99a58335ec836">ReturnSaveOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e667bae35cc365cf58de0c0ccda4a0">TOCSaveOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac9489be3b58e9ea891e7db43f7aad2">FramePointerSaveOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de157138bdd764492cf3ae4202533ca">LinkageSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69339ef165c863f260c40ab6f5501677">BasePointerSaveOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4a0e66478389671e5f8b98182e0a17">CRSaveOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c35747d71fb16dfb3407d99a10bb23">VSRContainingGPRs</a></td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCFrameLowering() {#acc927cacd0c354e0916debf44258dd5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCFrameLowering::PPCFrameLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#afcf9c9efe452f11d4713cc9657c1c4cd">computeBasePointerSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a2860a7b9656bf72a5002647efbb7a1f7">computeCRSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#ab24a042363e1e4863d84c337bd79cefd">computeFramePointerSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aad761a684381fe97901b2ca83b112b9b">computeLinkageSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a5fa3d40d2c434f1e70a98776e4922870">computeReturnSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aedfad9d0242953049a125df37ac8daa3">computeTOCSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6a6d31b2f1e5754f5824c5dec555eeac">llvm::TargetFrameLowering::TargetFrameLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addScavengingSpillSlot() {#ac65455efc149d81b4d1418acae7596b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::addScavengingSpillSlot (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#aecaae26e25f7f952810d98e50264b5fb">llvm::RegScavenger::addScavengingFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a61960903871aa95a7161074c6f1eec8f">llvm::MachineFrameInfo::CreateSpillStackObject</a>, <a href="#ac2efa5f4dacdde70f912da43c1f8ffcf">determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3836203fac855ac3c5718b701bd13ffd">llvm::MachineFrameInfo::getMaxAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aef2a1ee596539c697230ac5122d6584c">hasNonRISpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a1daf48d0b1ef864308803fcaa8e4ad83">hasSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#af515521ec01610e36ad4b3c5ece866f2">spillsCR</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a3f176ff8abd35fbe2f043c22d088302e">processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### assignCalleeSavedSpillSlots() {#ace3b0eb52be3988997a7f6e4a5b59aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::assignCalleeSavedSpillSlots (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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

<p>This function will assign callee saved gprs to volatile vector registers for prologue spills when applicable.</p>


<p>It returns false if there are any registers which were not spilled to volatile vector registers.</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a857e86404872fc7de94000c1d10e5afb">EnablePEVectorSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a2da3bac3ad70ccb97150626385ebd6a7">llvm::BitVector::find_first</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa19094c99ca405ec1efe38da727d27de">llvm::BitVector::none</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a168122d6ac4ed2a8b722e01b592ad289">llvm::BitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa56c07cdb4f03ddef7dfdf460811d36e">llvm::BitVector::set_bits</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#abf86e1383aec181a5a2d9967eb8070fd">llvm::BitVector::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### canUseAsEpilogue() {#a2c9566508140cc03db82c98053ef74be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::canUseAsEpilogue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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


<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### canUseAsPrologue() {#a99a7a25670315a8393e0bc768526559c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::canUseAsPrologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Methods used by shrink wrapping to determine if MBB can be used for the function prologue/epilogue.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### determineCalleeSaves() {#a88484d585ecc86920ebee6396946eae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::determineCalleeSaves (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SavedRegs, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
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


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 1970 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#adba30c3fa864715e30671ffc0b46a088">llvm::PPCFunctionInfo::getBasePointerSaveIndex</a>, <a href="#afea9064376aa194c66fa3770d5904bf2">getBasePointerSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a384c43d1e80952121cb39a1736bb9b8e">llvm::PPCFunctionInfo::getFramePointerSaveIndex</a>, <a href="#a4140e94a76010e9dc920504d1acbb5d9">getFramePointerSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a08f2debfe0bdcad74420a98b94d9e73b">llvm::PPCFunctionInfo::getTailCallSPDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad54fc81a4ef7ab96137a9b6e78fdf838">llvm::TargetOptions::GuaranteedTailCallOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a69189b7d95c4b78145d9dc25a3de148b">MustSaveLR</a>, <a href="#a11b74a0fb5ceb4340d1d7a6f809e0a28">needsFP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a168122d6ac4ed2a8b722e01b592ad289">llvm::BitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a61f31dae9fefe06f4271963a430228b2">llvm::PPCFunctionInfo::setBasePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#ad045aaa62d63f6767b7bb1290a768d81">llvm::PPCFunctionInfo::setCRSpillFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#afd615e1f3b75dc847e26ce6bd4932a56">llvm::PPCFunctionInfo::setFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#ab2f210dad848bd0d8a47921d46c78ea8">llvm::PPCFunctionInfo::setMustSaveLR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a9440f7f307efcb40ddecd6f056818ab3">llvm::PPCFunctionInfo::setPICBasePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>, <a href="#add05bb6a2fc43dfa726b8a1a02d1b4c0">updateCalleeSaves</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a488e8422444868d47101cb1b7c3fd51d">llvm::PPCFunctionInfo::usesPICBase</a>.</p>

</div>
</div>

### determineFrameLayout() {#ac2efa5f4dacdde70f912da43c1f8ffcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PPCFrameLowering::determineFrameLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool UseEstimate=false, unsigned * NewMaxCallFrameSize=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the frame layout but do not update the machine function.</p>


<p>determineFrameLayout - Determine the size of the frame and maximum call frame size.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> object can be const in this case as it is not modified.</p>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a19e260b3bbf8fad8480d151e11919836">llvm::MachineFrameInfo::adjustsStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a66046fdf8661d5276f951337b0cf892d">llvm::MachineFrameInfo::estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a50ec4d7eb2c3cc1d2d6cac266d4ea3eb">getLinkageSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3836203fac855ac3c5718b701bd13ffd">llvm::MachineFrameInfo::getMaxAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a4f335273c28b17552a7cfd802f42be2a">llvm::MachineFrameInfo::getMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a69189b7d95c4b78145d9dc25a3de148b">MustSaveLR</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a58259420ed94baab8d78d6d49f909b5f">llvm::PPCFunctionInfo::mustSaveTOC</a>.</p>


<p>Referenced by <a href="#ac65455efc149d81b4d1418acae7596b3">addScavengingSpillSlot</a>, <a href="#ad5bca3a5e9c1e69593d1f15b4cb1c44c">determineFrameLayoutAndUpdate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a719f4d1ca702ed3f9db724471eb2206d">llvm::PPCRegisterInfo::needsFrameBaseReg</a>.</p>

</div>
</div>

### determineFrameLayoutAndUpdate() {#ad5bca3a5e9c1e69593d1f15b4cb1c44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PPCFrameLowering::determineFrameLayoutAndUpdate (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool UseEstimate=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the frame layout and update the machine function.</p>


<p>determineFrameLayoutAndUpdate - Determine the size of the frame and maximum call frame size.</p>


<p>Update the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> object with the stack size.</p>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="#ac2efa5f4dacdde70f912da43c1f8ffcf">determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a02a7503d1af1782b35b3683e173cb5f0">llvm::MachineFrameInfo::setMaxCallFrameSize</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae4d51e9e70d6a7fb366f2a09d10a0945">llvm::MachineFrameInfo::setStackSize</a>.</p>


<p>Referenced by <a href="#aa670bf850cd6767f78408604873036f7">emitPrologue</a>.</p>

</div>
</div>

### eliminateCallFramePseudoInstr() {#a63c498f1fcb62301a44ad58e2dc8e7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator PPCFrameLowering::eliminateCallFramePseudoInstr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
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


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad54fc81a4ef7ab96137a9b6e78fdf838">llvm::TargetOptions::GuaranteedTailCallOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### emitEpilogue() {#a14e6ca2286bfbfa6952e74370a9c563b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::emitEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 1542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4b94e0ca517e149914aa0c34ee06c9fa">llvm::MachineFunction::exposesReturnsTwice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#adba30c3fa864715e30671ffc0b46a088">llvm::PPCFunctionInfo::getBasePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a384c43d1e80952121cb39a1736bb9b8e">llvm::PPCFunctionInfo::getFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#aacbb35468239038634c099ca495dcaab">llvm::PPCFunctionInfo::getMinReservedArea</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a172ea2e4053ed66cf2ae890669d24cd3">llvm::PPCFunctionInfo::getMustSaveCRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a24d7e69b87d99564e2c02b6e9d6ac353">llvm::PPCFunctionInfo::getPICBasePointerSaveIndex</a>, <a href="#a0ebd660e4b649282aa3b4ea870909ef1">getReturnSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a9785445e300aec53bac5d47777ad28ea">llvm::PPCFunctionInfo::getROPProtectionHashSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a08f2debfe0bdcad74420a98b94d9e73b">llvm::PPCFunctionInfo::getTailCallSPDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad54fc81a4ef7ab96137a9b6e78fdf838">llvm::TargetOptions::GuaranteedTailCallOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a6207e730a0051bddd35b25e05407681a">llvm::PPCFunctionInfo::hasFastCall</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a69189b7d95c4b78145d9dc25a3de148b">MustSaveLR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#ad9a64ea0a856eaeb01d6ba4e430ae60e">llvm::PPCFunctionInfo::mustSaveLR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a488e8422444868d47101cb1b7c3fd51d">llvm::PPCFunctionInfo::usesPICBase</a>.</p>

</div>
</div>

### emitPrologue() {#aa670bf850cd6767f78408604873036f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::emitPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a03445be1c81520587d5bb31b353f5558">llvm::MCCFIInstruction::createDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a6a60a82f8cb445e9e7029e38733b2d30">llvm::MCCFIInstruction::createOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a5efbfe5cee3e83355dec981c2d43611f">llvm::MCCFIInstruction::createRegister</a>, <a href="#ad5bca3a5e9c1e69593d1f15b4cb1c44c">determineFrameLayoutAndUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#adba30c3fa864715e30671ffc0b46a088">llvm::PPCFunctionInfo::getBasePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a384c43d1e80952121cb39a1736bb9b8e">llvm::PPCFunctionInfo::getFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3836203fac855ac3c5718b701bd13ffd">llvm::MachineFrameInfo::getMaxAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a172ea2e4053ed66cf2ae890669d24cd3">llvm::PPCFunctionInfo::getMustSaveCRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a24d7e69b87d99564e2c02b6e9d6ac353">llvm::PPCFunctionInfo::getPICBasePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>, <a href="#a0ebd660e4b649282aa3b4ea870909ef1">getReturnSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a9785445e300aec53bac5d47777ad28ea">llvm::PPCFunctionInfo::getROPProtectionHashSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac4e23bdb97cbb1eebd9ddd6606a1006f">llvm::PPCTargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a20e0ba2c46bef474e31cf8c2f9322db0">llvm::PPCTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acff74dc04327bef6824ecb2e3648d0f0">llvm::RegState::ImplicitKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a69189b7d95c4b78145d9dc25a3de148b">MustSaveLR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#ad9a64ea0a856eaeb01d6ba4e430ae60e">llvm::PPCFunctionInfo::mustSaveLR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a58259420ed94baab8d78d6d49f909b5f">llvm::PPCFunctionInfo::mustSaveTOC</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#abcb33f3f153c050bf1a63bcd8223e836">replaceFPWithRealFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3cd29e7edbcaceb5834eaa7d089a5bc4">llvm::MachineFrameInfo::setObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a488e8422444868d47101cb1b7c3fd51d">llvm::PPCFunctionInfo::usesPICBase</a>.</p>

</div>
</div>

### enableShrinkWrapping() {#ac0e10b8a8fa4bda2b86f716b82032b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::enableShrinkWrapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a2df082f8ff947495e48aaf8f83520ddd">llvm::PPCFunctionInfo::shrinkWrapDisabled</a>.</p>

</div>
</div>

### getBasePointerSaveOffset() {#afea9064376aa194c66fa3770d5904bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PPCFrameLowering::getBasePointerSaveOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getBasePointerSaveOffset - Return the previous frame offset to save the base pointer.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2733 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="#a88484d585ecc86920ebee6396946eae2">determineCalleeSaves</a>.</p>

</div>
</div>

### getCalleeSavedSpillSlots() {#a83a821743cb2c878d23ca01bb9b6c0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCFrameLowering::SpillSlot * PPCFrameLowering::getCalleeSavedSpillSlots (unsigned &amp; NumEntries)</td>
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

<p>getCalleeSavedSpillSlots - This method returns a pointer to an array of pairs, that contains an entry for each callee saved register that must be spilled to a particular stack location if it is spilled.</p>


<p>Each entry in this array contains a &lt;register,offset&gt; pair, indicating the fixed offset from the incoming stack pointer that each register should be spilled at. If a register is not listed here, the code generator is allowed to spill it anywhere it chooses.</p>


<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a6a32ebac50dfb7de135fedcd704fabe4">CALLEE_SAVED_FPRS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a932dd3cdcf409995885720b9a5864951">CALLEE_SAVED_GPRS32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a96d284acf9986fe6911aca50dd5000e1">CALLEE_SAVED_GPRS64</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a14b420b0bf00ca64a056b46fcc59090b">CALLEE_SAVED_VRS</a>.</p>

</div>
</div>

### getFramePointerSaveOffset() {#a4140e94a76010e9dc920504d1acbb5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PPCFrameLowering::getFramePointerSaveOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFramePointerSaveOffset - Return the previous frame offset to save the frame pointer.</p>

<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="#a88484d585ecc86920ebee6396946eae2">determineCalleeSaves</a>.</p>

</div>
</div>

### getLinkageSize() {#a50ec4d7eb2c3cc1d2d6cac266d4ea3eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCFrameLowering::getLinkageSize ()</td>
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

<p>getLinkageSize - Return the size of the PowerPC ABI linkage area.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>


<p>Referenced by <a href="#ac2efa5f4dacdde70f912da43c1f8ffcf">determineFrameLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a239d964ac9520cb492a050586bab9d35">mapArgRegToOffsetAIX</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a0ccb1948e466b25257ec5f95a2b8e11e">needStackSlotPassParameters</a>.</p>

</div>
</div>

### getReturnSaveOffset() {#a0ebd660e4b649282aa3b4ea870909ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::PPCFrameLowering::getReturnSaveOffset ()</td>
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

<p>getReturnSaveOffset - Return the previous frame offset to save the return address.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>


<p>Referenced by <a href="#a14e6ca2286bfbfa6952e74370a9c563b">emitEpilogue</a> and <a href="#aa670bf850cd6767f78408604873036f7">emitPrologue</a>.</p>

</div>
</div>

### getStackThreshold() {#a2cd3c8e286f88d8f80913526cf5105e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PPCFrameLowering::getStackThreshold ()</td>
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

<p>getStackThreshold - Return the maximum stack size</p>

<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2808 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a309fabb5424f0b563465484f21775555">llvm::TargetFrameLowering::getStackThreshold</a>.</p>

</div>
</div>

### getTOCSaveOffset() {#af2c21693e6284bea34b3ebbece45efdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PPCFrameLowering::getTOCSaveOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getTOCSaveOffset - Return the previous frame offset to save the TOC register – 64-bit SVR4 ABI only.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>.</p>

</div>
</div>

### inlineStackProbe() {#af0a5a3bd252aaac7b161ad8c01cf0951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::inlineStackProbe (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PrologueMBB)</td>
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

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a28391c59e5f478e4513f021226549734">buildDefCFAReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a03445be1c81520587d5bb31b353f5558">llvm::MCCFIInstruction::createDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab622d694b5fcb0edb99159f1ebdcdb6b">llvm::MachineBasicBlock::findDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee5f6b149b3f5ee5ed6ad7db9b58b148">llvm::fullyRecomputeLiveIns</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3836203fac855ac3c5718b701bd13ffd">llvm::MachineFrameInfo::getMaxAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac4e23bdb97cbb1eebd9ddd6606a1006f">llvm::PPCTargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a44abec85091b571da2189ac4bd139095">llvm::PPC::PRED_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a46cd6e935d7b9cc679d9cb0cf025ae91">llvm::PPC::PRED_LT</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### needsFP() {#a11b74a0fb5ceb4340d1d7a6f809e0a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::needsFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4b94e0ca517e149914aa0c34ee06c9fa">llvm::MachineFunction::exposesReturnsTwice</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a6207e730a0051bddd35b25e05407681a">llvm::PPCFunctionInfo::hasFastCall</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a503a8cb169aa29ac907c218692087db3">llvm::MachineFrameInfo::hasPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa7d9e2f26e4c8b32f51c455b220ce13c">llvm::MachineFrameInfo::hasStackMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#a88484d585ecc86920ebee6396946eae2">determineCalleeSaves</a>, <a href="#a3fdbbb3f732425b06a8a7526b1e49e7a">hasFPImpl</a>, <a href="#a3f176ff8abd35fbe2f043c22d088302e">processFunctionBeforeFrameFinalized</a>, <a href="#abcb33f3f153c050bf1a63bcd8223e836">replaceFPWithRealFP</a> and <a href="#aae5bad356a0c0583ebad92fbe899230c">restoreCalleeSavedRegisters</a>.</p>

</div>
</div>

### processFunctionBeforeFrameFinalized() {#a3f176ff8abd35fbe2f043c22d088302e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::processFunctionBeforeFrameFinalized (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
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


<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2071 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="#ac65455efc149d81b4d1418acae7596b3">addScavengingSpillSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#adba30c3fa864715e30671ffc0b46a088">llvm::PPCFunctionInfo::getBasePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a384c43d1e80952121cb39a1736bb9b8e">llvm::PPCFunctionInfo::getFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a24d7e69b87d99564e2c02b6e9d6ac353">llvm::PPCFunctionInfo::getPICBasePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5b92dc4f379813174c0942c8d1d8e241">llvm::MachineFrameInfo::getRestorePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af5ba92668c96fb23e8d5fa9add3daab6">llvm::MachineFrameInfo::getSavePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a08f2debfe0bdcad74420a98b94d9e73b">llvm::PPCFunctionInfo::getTailCallSPDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad54fc81a4ef7ab96137a9b6e78fdf838">llvm::TargetOptions::GuaranteedTailCallOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a763b7a1e7127b495f396b30f0d9c95f1">llvm::MachineFrameInfo::hasTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a58259420ed94baab8d78d6d49f909b5f">llvm::PPCFunctionInfo::mustSaveTOC</a>, <a href="#a11b74a0fb5ceb4340d1d7a6f809e0a28">needsFP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3cd29e7edbcaceb5834eaa7d089a5bc4">llvm::MachineFrameInfo::setObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#af515521ec01610e36ad4b3c5ece866f2">spillsCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a488e8422444868d47101cb1b7c3fd51d">llvm::PPCFunctionInfo::usesPICBase</a>.</p>

</div>
</div>

### replaceFPWithRealFP() {#abcb33f3f153c050bf1a63bcd8223e836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::replaceFPWithRealFP (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="#a11b74a0fb5ceb4340d1d7a6f809e0a28">needsFP</a>.</p>


<p>Referenced by <a href="#aa670bf850cd6767f78408604873036f7">emitPrologue</a>.</p>

</div>
</div>

### restoreCalleeSavedRegisters() {#aae5bad356a0c0583ebad92fbe899230c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::restoreCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#ad7ac9a830d8314a42e5b9d6d87168249">isCalleeSavedCR</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a58259420ed94baab8d78d6d49f909b5f">llvm::PPCFunctionInfo::mustSaveTOC</a>, <a href="#a11b74a0fb5ceb4340d1d7a6f809e0a28">needsFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a4f0f388c4bafdb925e326b829c3f92bd">restoreCRs</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### spillCalleeSavedRegisters() {#a42ba26b731da85ec85d9f4ebb7d27e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::spillCalleeSavedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acff74dc04327bef6824ecb2e3648d0f0">llvm::RegState::ImplicitKill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a58259420ed94baab8d78d6d49f909b5f">llvm::PPCFunctionInfo::mustSaveTOC</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### targetHandlesStackFrameRounding() {#a2094cef29f00243385de148a1900e599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCFrameLowering::targetHandlesStackFrameRounding ()</td>
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

<p>targetHandlesStackFrameRounding - Returns true if the target is responsible for rounding up the stack frame (probably at emitPrologue time).</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### updateCalleeSaves() {#add05bb6a2fc43dfa726b8a1a02d1b4c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::updateCalleeSaves (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SavedRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 2743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa19094c99ca405ec1efe38da727d27de">llvm::BitVector::none</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>


<p>Referenced by <a href="#a88484d585ecc86920ebee6396946eae2">determineCalleeSaves</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### hasFPImpl() {#a3fdbbb3f732425b06a8a7526b1e49e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::hasFPImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a> and <a href="#a11b74a0fb5ceb4340d1d7a6f809e0a28">needsFP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createTailCallBranchInstr() {#a45d19fc3f98636936e5c13e7d9988a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCFrameLowering::createTailCallBranchInstr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create branch instruction for PPC::TCRETURN* (tail call return)</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MBB</td>
<td class="doxyParamItemDescription"><p>that is terminated by PPC::TCRETURN*</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

### findScratchRegister() {#a047d552c2558a05e834ccd1bd0750b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::findScratchRegister (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, bool UseAtEnd, bool TwoUniqueRegsRequired=false, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> * SR1=nullptr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> * SR2=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find register[s] that can be used in function prologue and epilogue.</p>


<p>Find register[s] that can be use as scratch register[s] in function prologue and epilogue to save various registers (Link <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, Base Pointer, etc.). Prefer R0/R12, if available. Otherwise choose whatever register[s] are available.</p>


<p>This method will return true if it is able to find enough unique scratch registers (1 or 2 depending on the requirement). If it is unable to find enough available registers in the block, it will return false and set any passed output parameter that corresponds to a required unique register to PPC::NoRegister.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MBB</td>
<td class="doxyParamItemDescription"><p>The machine basic block to find an available register for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] UseAtEnd</td>
<td class="doxyParamItemDescription"><p>Specify whether the scratch register will be used at the end of the basic block (i.e., will the scratch register kill a register defined in the basic block)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TwoUniqueRegsRequired</td>
<td class="doxyParamItemDescription"><p>Specify whether this basic block will require two unique scratch registers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] SR1</td>
<td class="doxyParamItemDescription"><p>The scratch register to use</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] SR2</td>
<td class="doxyParamItemDescription"><p>The second scratch register. If this pointer is not null the function will attempt to set it to an available register regardless of whether there is a hard requirement for two unique scratch registers.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the required number of registers was found. false if the required number of scratch register weren't available. If either output parameter refers to a required scratch register that isn't available, it will be set to an invalid value.</p></dd>
</dl>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

### stackUpdateCanBeMoved() {#adc9f51db328b07b1943516a7c93913ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::stackUpdateCanBeMoved (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the conditions are correct to allow for the stack update to be moved past the CSR save/restore code.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

### twoUniqueScratchRegsRequired() {#ada6b45d13414d0b730efff3d8cae83b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCFrameLowering::twoUniqueScratchRegsRequired (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BasePointerSaveOffset {#a69339ef165c863f260c40ab6f5501677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::PPCFrameLowering::BasePointerSaveOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### CRSaveOffset {#a3e4a0e66478389671e5f8b98182e0a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::PPCFrameLowering::CRSaveOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### FramePointerSaveOffset {#a8ac9489be3b58e9ea891e7db43f7aad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::PPCFrameLowering::FramePointerSaveOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### LinkageSize {#a6de157138bdd764492cf3ae4202533ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::PPCFrameLowering::LinkageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### ReturnSaveOffset {#a7ecced2df1a2f272a1f99a58335ec836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::PPCFrameLowering::ReturnSaveOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### Subtarget {#abaea8d2188fadc14aae892f001f13a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCSubtarget&amp; llvm::PPCFrameLowering::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### TOCSaveOffset {#a59e667bae35cc365cf58de0c0ccda4a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::PPCFrameLowering::TOCSaveOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

### VSRContainingGPRs {#a76c35747d71fb16dfb3407d99a10bb23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, std::pair&lt;Register, Register&gt; &gt; llvm::PPCFrameLowering::VSRContainingGPRs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
