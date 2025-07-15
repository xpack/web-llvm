---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TwoAddressInstructionImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89f1cec083455bb48b4ddfe09d226a1">TiedPairList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, unsigned &gt;, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b40fbd709da998548503953c2dbcbc4">TiedOperandMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/smallvector">TiedPairList</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d739177a188e603bd2fe32cc78fefe">TwoAddressInstructionImpl</a> (MachineFunction &amp;MF, MachineFunctionPass *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1d87a226756bff697fc8d06828d5d5">TwoAddressInstructionImpl</a> (MachineFunction &amp;MF, MachineFunctionAnalysisManager &amp;MFAM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2024641defd8a390ad9061673ea1b645">setOptLevel</a> (CodeGenOptLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc0a5064c340800de9ce752c881316d">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduce two-address instructions to two operands. <a href="#a7bc0a5064c340800de9ce752c881316d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53698a99c2c1cee5710e55606be40717">getSingleDef</a> (Register Reg, MachineBasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the MachineInstr* if it is the single def of the Reg in current BB. <a href="#a53698a99c2c1cee5710e55606be40717">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c59e44bda76b45559237db0361b3c55">isRevCopyChain</a> (Register FromReg, Register ToReg, int Maxlen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if there is a reversed copy chain from FromReg to ToReg: Tmp1 = copy Tmp2; FromReg = copy Tmp1; ToReg = add FromReg ... Tmp2 = copy ToReg; MaxLen specifies the maximum length of the copy chain the func can walk through. <a href="#a1c59e44bda76b45559237db0361b3c55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e62fc4d65cf68a72c9faa88e8e1422">noUseAfterLastDef</a> (Register Reg, unsigned Dist, unsigned &amp;LastDef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are no intervening uses between the last instruction in the MBB that defines the specified register and the two-address instruction which is being processed. <a href="#a65e62fc4d65cf68a72c9faa88e8e1422">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d40499a0b5c071f0d5bf9431f05aa9">isCopyToReg</a> (MachineInstr &amp;MI, Register &amp;SrcReg, Register &amp;DstReg, bool &amp;IsSrcPhys, bool &amp;IsDstPhys) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified MI is a copy instruction or an extract_subreg instruction. <a href="#ac4d40499a0b5c071f0d5bf9431f05aa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27026067b73b9a61dcb8b2cc6149ef14">isPlainlyKilled</a> (const MachineInstr *MI, LiveRange &amp;LR) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc8783e7d5e5886a14bbb47a48757bb">isPlainlyKilled</a> (const MachineInstr *MI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given register value, which is used by the given instruction, is killed by the given instruction. <a href="#a7fc8783e7d5e5886a14bbb47a48757bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75520b3e1bade547d21f755992dcfb19">isPlainlyKilled</a> (const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the register used by the given operand is killed by the operand's instruction. <a href="#a75520b3e1bade547d21f755992dcfb19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183968c822123bdb01f883e468733245">isKilled</a> (MachineInstr &amp;MI, Register Reg, bool allowFalsePositives) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given register value, which is used by the given instruction, is killed by the given instruction. <a href="#a183968c822123bdb01f883e468733245">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31c911923fbd203eb8a154555fd791f">findOnlyInterestingUse</a> (Register Reg, MachineBasicBlock *MBB, bool &amp;IsCopy, Register &amp;DstReg, bool &amp;IsDstPhys) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a register, if all its uses are in the same basic block, return the last use instruction if it's a copy or a two-address use. <a href="#ac31c911923fbd203eb8a154555fd791f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6091c3b0b5a8227b7e03b2feccbdabde">regsAreCompatible</a> (Register RegA, Register RegB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the two registers are equal or aliased. <a href="#a6091c3b0b5a8227b7e03b2feccbdabde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a116703915f99fa8129627bba5544edae">removeMapRegEntry</a> (const MachineOperand &amp;MO, DenseMap&lt; Register, Register &gt; &amp;RegMap) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>From RegMap remove entries mapped to a physical register which overlaps MO. <a href="#a116703915f99fa8129627bba5544edae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f852d1a82b5ee14f9a0d7b5149d7d60">removeClobberedSrcRegMap</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register is clobbered, old entries mapped to it should be deleted. <a href="#a5f852d1a82b5ee14f9a0d7b5149d7d60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48595faa201b4d3623fede572031b04c">regOverlapsSet</a> (const SmallVectorImpl&lt; Register &gt; &amp;Set, Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c96e7cb13d87ff8d960aa332e3dd23">isProfitableToCommute</a> (Register RegA, Register RegB, Register RegC, MachineInstr *MI, unsigned Dist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's potentially profitable to commute the two-address instruction that's being processed. <a href="#a57c96e7cb13d87ff8d960aa332e3dd23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab091ded925bddb8f476e04d5a7f47ff4">commuteInstruction</a> (MachineInstr *MI, unsigned DstIdx, unsigned RegBIdx, unsigned RegCIdx, unsigned Dist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Commute a two-address instruction and update the basic block, distance map, and live variables if needed. <a href="#ab091ded925bddb8f476e04d5a7f47ff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b12a7dec6b59c0b40770e52e622ba7f">isProfitableToConv3Addr</a> (Register RegA, Register RegB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to convert the given 2-address instruction to a 3-address one. <a href="#a7b12a7dec6b59c0b40770e52e622ba7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89646c0256bd544e3deeec6b8b887fb7">convertInstTo3Addr</a> (MachineBasicBlock::iterator &amp;mi, MachineBasicBlock::iterator &amp;nmi, Register RegA, Register RegB, unsigned &amp;Dist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the specified two-address instruction into a three address one. <a href="#a89646c0256bd544e3deeec6b8b887fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5159e63b36bd7dfcf6b8e27ee8d141df">isDefTooClose</a> (Register Reg, unsigned Dist, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the re-scheduling will put the given instruction too close to the defs of its register dependencies. <a href="#a5159e63b36bd7dfcf6b8e27ee8d141df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d0b5a9a71597081eda066ea6958e37a">rescheduleMIBelowKill</a> (MachineBasicBlock::iterator &amp;mi, MachineBasicBlock::iterator &amp;nmi, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there is one more local instruction that reads 'Reg' and it kills 'Reg, consider moving the instruction below the kill instruction in order to eliminate the need for the copy. <a href="#a7d0b5a9a71597081eda066ea6958e37a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d82d5d5c44dbd96e483476e98e486d">rescheduleKillAboveMI</a> (MachineBasicBlock::iterator &amp;mi, MachineBasicBlock::iterator &amp;nmi, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there is one more local instruction that reads 'Reg' and it kills 'Reg, consider moving the kill instruction above the current two-address instruction in order to eliminate the need for the copy. <a href="#a39d82d5d5c44dbd96e483476e98e486d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f726f51550bfdcf9d7fce169ad9a2ba">tryInstructionTransform</a> (MachineBasicBlock::iterator &amp;mi, MachineBasicBlock::iterator &amp;nmi, unsigned SrcIdx, unsigned DstIdx, unsigned &amp;Dist, bool shouldOnlyCommute)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the case where an instruction has a single pair of tied register operands, attempt some transformations that may either eliminate the tied operands or improve the opportunities for coalescing away the register copy. <a href="#a3f726f51550bfdcf9d7fce169ad9a2ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e4e13d9e6eba7efe01e17d8533a020">tryInstructionCommute</a> (MachineInstr *MI, unsigned DstOpIdx, unsigned BaseOpIdx, bool BaseOpKilled, unsigned Dist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to commute the operand 'BaseOpIdx' and some other operand in the given machine instruction to improve opportunities for coalescing and elimination of a register to register copy. <a href="#a99e4e13d9e6eba7efe01e17d8533a020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0167fa7009f2302141393704e964e11e">scanUses</a> (Register DstReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan forward recursively for only uses, update maps if the use is a copy or a two-address instruction. <a href="#a0167fa7009f2302141393704e964e11e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dda4fa7cc111567721fdb7663a3c909">processCopy</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified instruction is not yet processed, process it if it's a copy. <a href="#a3dda4fa7cc111567721fdb7663a3c909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0ffb4951dfef93d8628a96eb132f45">collectTiedOperands</a> (MachineInstr *MI, TiedOperandMap &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeef1cc462e7c7fb1336d20a3c5d72f3">processTiedPairs</a> (MachineInstr *MI, TiedPairList &amp;, unsigned &amp;Dist)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e94784aa1ca8e149a3eda36c62b5acd">eliminateRegSequence</a> (MachineBasicBlock::iterator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate a REG_SEQUENCE instruction as part of the de-ssa process. <a href="#a5e94784aa1ca8e149a3eda36c62b5acd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5342f57eb77a5781a3ce0e3f9648d8b9">processStatepoint</a> (MachineInstr *MI, TiedOperandMap &amp;TiedOperands)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f23f1d499979a9c1ef91ccf46e33875">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318363e3d546df707dd328692914badb">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace54fe653c3cf60539c0a61e1de7a6e0">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bf741ff64ac3bdc15ee17b62c1ff5e">InstrItins</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b9c8a264682e3369abc6ad8fa45152">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livevariables">LiveVariables</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aea4f14b4d8ee712fe5bf3de92db692">LV</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2baae2405e4da49e140a5d5a4206a18">LIS</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4972f83b62bf8630d0cc4611a9030f9c">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a35c6a468da21dd2a63f4d80a59a550">OptLevel</a> = CodeGenOptLevel::None</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae324a1295416ce755e061351bea53576">MBB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac216784580af51472e182d22a0e7b62b">DistanceMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169c5a151f24045d7df8822d150a5be7">Processed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87c03b13032cedbb86dbe1dc49c014b">SrcRegMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b02790c6e2bcac779241a70d0d9f13">DstRegMap</a></td>
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


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### TiedOperandMap {#a3b40fbd709da998548503953c2dbcbc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::TiedOperandMap =  SmallDenseMap&lt;unsigned, TiedPairList&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### TiedPairList {#ad89f1cec083455bb48b4ddfe09d226a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::TiedPairList =  SmallVector&lt;std::pair&lt;unsigned, unsigned&gt;, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TwoAddressInstructionImpl() {#a37d739177a188e603bd2fe32cc78fefe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::TwoAddressInstructionImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### TwoAddressInstructionImpl() {#a4b1d87a226756bff697fc8d06828d5d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::TwoAddressInstructionImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp; MFAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a7bc0a5064c340800de9ce752c881316d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reduce two-address instructions to two operands.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a50d461a887e200e704e5157d3b21514d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a2e0aa187d296e1330d12a948094f601b">llvm::MachineFunctionProperties::TiedOpsRewritten</a>.</p>

</div>
</div>

### setOptLevel() {#a2024641defd8a390ad9061673ea1b645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::setOptLevel (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> Level)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectTiedOperands() {#a8c0ffb4951dfef93d8628a96eb132f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::collectTiedOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">TiedOperandMap</a> &amp; TiedOperands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### commuteInstruction() {#ab091ded925bddb8f476e04d5a7f47ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::commuteInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned DstIdx, unsigned RegBIdx, unsigned RegCIdx, unsigned Dist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Commute a two-address instruction and update the basic block, distance map, and live variables if needed.</p>


<p>Return true if it is successful.</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### convertInstTo3Addr() {#a89646c0256bd544e3deeec6b8b887fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::convertInstTo3Addr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; mi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; nmi, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegB, unsigned &amp; Dist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the specified two-address instruction into a three address one.</p>


<p>Return true if this transformation was successful.</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### eliminateRegSequence() {#a5e94784aa1ca8e149a3eda36c62b5acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TwoAddressInstructionImpl::eliminateRegSequence (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminate a REG_SEQUENCE instruction as part of the de-ssa process.</p>


<p>The instruction is turned into a sequence of sub-register copies:</p>


<p>dst = REG_SEQUENCE v1, ssub0, v2, ssub1</p>


<p>Becomes:</p>


<p>undef dst:ssub0 = COPY v1 dst:ssub1 = COPY v2</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### findOnlyInterestingUse() {#ac31c911923fbd203eb8a154555fd791f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * TwoAddressInstructionImpl::findOnlyInterestingUse (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, bool &amp; IsCopy, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; DstReg, bool &amp; IsDstPhys)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a register, if all its uses are in the same basic block, return the last use instruction if it's a copy or a two-address use.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### getSingleDef() {#a53698a99c2c1cee5710e55606be40717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * TwoAddressInstructionImpl::getSingleDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the MachineInstr* if it is the single def of the Reg in current BB.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isCopyToReg() {#ac4d40499a0b5c071f0d5bf9431f05aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isCopyToReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; DstReg, bool &amp; IsSrcPhys, bool &amp; IsDstPhys)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified MI is a copy instruction or an extract_subreg instruction.</p>


<p>It also returns the source and destination registers and whether they are physical registers by reference.</p>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isDefTooClose() {#a5159e63b36bd7dfcf6b8e27ee8d141df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isDefTooClose (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned Dist, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the re-scheduling will put the given instruction too close to the defs of its register dependencies.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isKilled() {#a183968c822123bdb01f883e468733245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isKilled (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool allowFalsePositives)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given register value, which is used by the given instruction, is killed by the given instruction.</p>


<p>This looks through coalescable copies to see if the original value is potentially not killed.</p>


<p>For example, in this code:</p>


<p>reg1034 = copy reg1024 reg1035 = copy killed reg1025 reg1036 = add killed reg1034, killed reg1035</p>


<p>reg1034 is not considered to be killed, since it is copied from a register which is not killed. Treating it as not killed lets the normal heuristics commute the (two-address) add, which lets coalescing eliminate the extra copy.</p>


<p>If allowFalsePositives is true then likely kills are treated as kills even if it can't be proven that they are kills.</p>


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isPlainlyKilled() {#a27026067b73b9a61dcb8b2cc6149ef14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isPlainlyKilled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isPlainlyKilled() {#a7fc8783e7d5e5886a14bbb47a48757bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isPlainlyKilled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given register value, which is used by the given instruction, is killed by the given instruction.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isPlainlyKilled() {#a75520b3e1bade547d21f755992dcfb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isPlainlyKilled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the register used by the given operand is killed by the operand's instruction.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isProfitableToCommute() {#a57c96e7cb13d87ff8d960aa332e3dd23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isProfitableToCommute (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegC, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Dist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's potentially profitable to commute the two-address instruction that's being processed.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isProfitableToConv3Addr() {#a7b12a7dec6b59c0b40770e52e622ba7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isProfitableToConv3Addr (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is profitable to convert the given 2-address instruction to a 3-address one.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### isRevCopyChain() {#a1c59e44bda76b45559237db0361b3c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::isRevCopyChain (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FromReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg, int Maxlen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if there is a reversed copy chain from FromReg to ToReg: Tmp1 = copy Tmp2; FromReg = copy Tmp1; ToReg = add FromReg ... Tmp2 = copy ToReg; MaxLen specifies the maximum length of the copy chain the func can walk through.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### noUseAfterLastDef() {#a65e62fc4d65cf68a72c9faa88e8e1422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::noUseAfterLastDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned Dist, unsigned &amp; LastDef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there are no intervening uses between the last instruction in the MBB that defines the specified register and the two-address instruction which is being processed.</p>


<p>It also returns the last def location by reference.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### processCopy() {#a3dda4fa7cc111567721fdb7663a3c909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TwoAddressInstructionImpl::processCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the specified instruction is not yet processed, process it if it's a copy.</p>


<p>For a copy instruction, we find the physical registers the source and destination registers might be mapped to. These are kept in point-to maps used to determine future optimizations. e.g. v1024 = mov r0 v1025 = mov r1 v1026 = add v1024, v1025 r1 = mov r1026 If 'add' is a two-address instruction, v1024, v1026 are both potentially coalesced to r0 (from the input side). v1025 is mapped to r1. v1026 is potentially joined with r1 on the output side. It's worthwhile to commute 'add' to eliminate a copy.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### processStatepoint() {#a5342f57eb77a5781a3ce0e3f9648d8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::processStatepoint (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">TiedOperandMap</a> &amp; TiedOperands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### processTiedPairs() {#adeef1cc462e7c7fb1336d20a3c5d72f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TwoAddressInstructionImpl::processTiedPairs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallvector">TiedPairList</a> &amp; TiedPairs, unsigned &amp; Dist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### regOverlapsSet() {#a48595faa201b4d3623fede572031b04c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::regOverlapsSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Set, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### regsAreCompatible() {#a6091c3b0b5a8227b7e03b2feccbdabde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::regsAreCompatible (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the two registers are equal or aliased.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### removeClobberedSrcRegMap() {#a5f852d1a82b5ee14f9a0d7b5149d7d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TwoAddressInstructionImpl::removeClobberedSrcRegMap (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a physical register is clobbered, old entries mapped to it should be deleted.</p>


<p>For example</p>



<pre><code>%2:gr64 = COPY killed $rdx
MUL64r %3:gr64, implicit-def $rax, implicit-def $rdx
</code></pre>


<p>After the MUL instruction, $rdx contains different value than in the COPY instruction. So %2 should not map to $rdx after MUL.</p>


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### removeMapRegEntry() {#a116703915f99fa8129627bba5544edae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TwoAddressInstructionImpl::removeMapRegEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; RegMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>From RegMap remove entries mapped to a physical register which overlaps MO.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### rescheduleKillAboveMI() {#a39d82d5d5c44dbd96e483476e98e486d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::rescheduleKillAboveMI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; mi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; nmi, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there is one more local instruction that reads 'Reg' and it kills 'Reg, consider moving the kill instruction above the current two-address instruction in order to eliminate the need for the copy.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### rescheduleMIBelowKill() {#a7d0b5a9a71597081eda066ea6958e37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::rescheduleMIBelowKill (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; mi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; nmi, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there is one more local instruction that reads 'Reg' and it kills 'Reg, consider moving the instruction below the kill instruction in order to eliminate the need for the copy.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### scanUses() {#a0167fa7009f2302141393704e964e11e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TwoAddressInstructionImpl::scanUses (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan forward recursively for only uses, update maps if the use is a copy or a two-address instruction.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### tryInstructionCommute() {#a99e4e13d9e6eba7efe01e17d8533a020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::tryInstructionCommute (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned DstOpIdx, unsigned BaseOpIdx, bool BaseOpKilled, unsigned Dist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to commute the operand 'BaseOpIdx' and some other operand in the given machine instruction to improve opportunities for coalescing and elimination of a register to register copy.</p>


<p>'DstOpIdx' specifies the index of MI def operand. 'BaseOpKilled' specifies if the register associated with 'BaseOpIdx' operand is killed by the given instruction. The 'Dist' arguments provides the distance of MI from the start of the current basic block and it is used to determine if it is profitable to commute operands in the instruction.</p>


<p>Returns true if the transformation happened. Otherwise, returns false.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### tryInstructionTransform() {#a3f726f51550bfdcf9d7fce169ad9a2ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TwoAddressInstructionImpl::tryInstructionTransform (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; mi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; nmi, unsigned SrcIdx, unsigned DstIdx, unsigned &amp; Dist, bool shouldOnlyCommute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the case where an instruction has a single pair of tied register operands, attempt some transformations that may either eliminate the tied operands or improve the opportunities for coalescing away the register copy.</p>


<p>Returns true if no copy needs to be inserted to untie mi's operands (either because they were untied, or because mi was rescheduled, and will be visited again later). If the shouldOnlyCommute flag is true, only instruction commutation is attempted.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a4972f83b62bf8630d0cc4611a9030f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### DistanceMap {#ac216784580af51472e182d22a0e7b62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr*, unsigned&gt; anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::DistanceMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### DstRegMap {#a08b02790c6e2bcac779241a70d0d9f13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, Register&gt; anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::DstRegMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### InstrItins {#a49bf741ff64ac3bdc15ee17b62c1ff5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::InstrItins = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### LIS {#af2baae2405e4da49e140a5d5a4206a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::LIS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### LV {#a5aea4f14b4d8ee712fe5bf3de92db692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveVariables* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::LV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### MBB {#ae324a1295416ce755e061351bea53576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::MBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### MF {#a8f23f1d499979a9c1ef91ccf46e33875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### MRI {#ac1b9c8a264682e3369abc6ad8fa45152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### OptLevel {#a5a35c6a468da21dd2a63f4d80a59a550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::OptLevel = CodeGenOptLevel::None</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### Processed {#a169c5a151f24045d7df8822d150a5be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr*, 8&gt; anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::Processed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### SrcRegMap {#ad87c03b13032cedbb86dbe1dc49c014b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, Register&gt; anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::SrcRegMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### TII {#a318363e3d546df707dd328692914badb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

### TRI {#ace54fe653c3cf60539c0a61e1de7a6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp">TwoAddressInstructionPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
