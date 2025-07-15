---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64InstructionSelector` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05eae0f7e71dedbf2aa224f4c38eaf5">AArch64InstructionSelector</a> (const AArch64TargetMachine &amp;TM, const AArch64Subtarget &amp;STI, const AArch64RegisterBankInfo &amp;RBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a register bank, and a type, return the smallest register class that can represent that combination. <a href="#af05eae0f7e71dedbf2aa224f4c38eaf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab262affd2dff9550b4c19d920d21136">selectCompareBranchFedByFCmp</a> (MachineInstr &amp;I, MachineInstr &amp;FCmp, MachineIRBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7835ac895d410e58d9e094ff9ea8d6a0">selectCompareBranchFedByICmp</a> (MachineInstr &amp;I, MachineInstr &amp;ICmp, MachineIRBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8b67464ec020f4a40a549b1653cee5">tryOptCompareBranchFedByICmp</a> (MachineInstr &amp;I, MachineInstr &amp;ICmp, MachineIRBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a837d6174175d2ad93a02815794af8c83">tryOptAndIntoCompareBranch</a> (MachineInstr &amp;AndInst, bool Invert, MachineBasicBlock *DstMBB, MachineIRBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf1575bd51e7b6b91a92904410f268aa">select</a> (MachineInstr &amp;I) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select the (possibly generic) instruction <span class="doxyComputerOutput">I</span> to only use target-specific opcodes. <a href="#acf1575bd51e7b6b91a92904410f268aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83151fce4b310c403a42a444660e030b">setupMF</a> (MachineFunction &amp;MF, GISelKnownBits *KB, CodeGenCoverage *CoverageInfo, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setup per-MF executor state. <a href="#a83151fce4b310c403a42a444660e030b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a351c916dc6beda1d43bd73526550747b">selectImpl</a> (MachineInstr &amp;I, CodeGenCoverage &amp;CoverageInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tblgen-erated 'select' implementation, used as the initial selector for the patterns that don't require complex C++. <a href="#a351c916dc6beda1d43bd73526550747b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad162c736325899752752db3704aa1595">preISelLower</a> (MachineInstr &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283fdd97f071b4a9948422026d590186">earlySelect</a> (MachineInstr &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f89e27e475d3cc59922f212ba2922b">selectAndRestoreState</a> (MachineInstr &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save state that is shared between select calls, call select on <span class="doxyComputerOutput">I</span> and then restore the saved state. <a href="#a25f89e27e475d3cc59922f212ba2922b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e55090db7909c26abd97d3b29abfa61">processPHIs</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf69661f1b6089a24141ba232e20dae">earlySelectSHL</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009e77efca5522b14dce1c1ae103b3f9">contractCrossBankCopyIntoStore</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate same-sized cross-bank copies into stores before selectImpl(). <a href="#a009e77efca5522b14dce1c1ae103b3f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf70776136caad338d1943e228a45702">convertPtrAddToAdd</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This lowering tries to look for G_PTR_ADD instructions and then converts them to a standard G_ADD with a COPY on the source. <a href="#adf70776136caad338d1943e228a45702">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6b29e14f00dda770a2fbfc63dc33485">selectVaStartAAPCS</a> (MachineInstr &amp;I, MachineFunction &amp;MF, MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac11466883ccafaf4fc0f39eced7fda79">selectVaStartDarwin</a> (MachineInstr &amp;I, MachineFunction &amp;MF, MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e3d92bad9bfc7aa46dd0fdedfd8543">selectCompareBranch</a> (MachineInstr &amp;I, MachineFunction &amp;MF, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9bda4e39cd62deaa118371b91831fe">selectVectorAshrLshr</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92133d53afe21485777eed333a14fa93">selectVectorSHL</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875a4ba35f2b56dd82d6c673ffb7fc96">emitScalarToVector</a> (unsigned EltSize, const TargetRegisterClass *DstRC, Register Scalar, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a69a004bf8c5d96a593dcb98735fc6">emitNarrowVector</a> (Register DstReg, Register SrcReg, MachineIRBuilder &amp;MIRBuilder, MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to narrow vector that was widened by emitScalarToVector. <a href="#a72a69a004bf8c5d96a593dcb98735fc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277649237a306d77c468a5bfc6b6b8f3">emitLaneInsert</a> (std::optional&lt; Register &gt; DstReg, Register SrcReg, Register EltReg, unsigned LaneIdx, const RegisterBank &amp;RB, MachineIRBuilder &amp;MIRBuilder) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a lane insert into <span class="doxyComputerOutput">DstReg</span>, or a new vector register if std::nullopt is provided. <a href="#a277649237a306d77c468a5bfc6b6b8f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae277c162686b7c68014bfc3cde865fe4">emitConstantVector</a> (Register Dst, Constant *CV, MachineIRBuilder &amp;MIRBuilder, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a sequence of instructions representing a constant <span class="doxyComputerOutput">CV</span> for a vector register <span class="doxyComputerOutput">Dst</span>. <a href="#ae277c162686b7c68014bfc3cde865fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4440a1b3592fcd2c5cb2491addff0ece">tryAdvSIMDModImm8</a> (Register Dst, unsigned DstSize, APInt Bits, MachineIRBuilder &amp;MIRBuilder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05cd8aa16b47b35a22dc52e0ffd51b8f">tryAdvSIMDModImm16</a> (Register Dst, unsigned DstSize, APInt Bits, MachineIRBuilder &amp;MIRBuilder, bool Inv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18128d2a02cd5be7601756814e88af3d">tryAdvSIMDModImm32</a> (Register Dst, unsigned DstSize, APInt Bits, MachineIRBuilder &amp;MIRBuilder, bool Inv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd988201d74aa61567734debc3c958a">tryAdvSIMDModImm64</a> (Register Dst, unsigned DstSize, APInt Bits, MachineIRBuilder &amp;MIRBuilder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920e87ea1cfaed92d1fac1f052c4d501">tryAdvSIMDModImm321s</a> (Register Dst, unsigned DstSize, APInt Bits, MachineIRBuilder &amp;MIRBuilder, bool Inv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d16518feeb58d169a0ec0e59fd63e6">tryAdvSIMDModImmFP</a> (Register Dst, unsigned DstSize, APInt Bits, MachineIRBuilder &amp;MIRBuilder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd77dbcba67e2237f2b70274dc3e3ff">tryOptConstantBuildVec</a> (MachineInstr &amp;MI, LLT DstTy, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e889089620e7e580b69c98fa625a6d">tryOptBuildVecToSubregToReg</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae40ae6e14203d8aa368fee62fa924c6">selectBuildVector</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42e07cd2c5f3813797e6a5cf42f25e31">selectMergeValues</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ce95dd7e4c83726a14ba39a524ff82">selectUnmergeValues</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae22d49e8cc2d210ffdb69fcd2fdc1b44">selectShuffleVector</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a3997aa971a05ed73ddc3f41dfe7be">selectExtractElt</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39baf8cd7d59984c76fa52ba758e692">selectConcatVectors</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d5f3b7006745545cd2126b063e7e68">selectSplitVectorUnmerge</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef2d14c189d3182a566f37298d21655">selectVectorLoadIntrinsic</a> (unsigned Opc, unsigned NumVecs, MachineInstr &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to select vector load intrinsics like @llvm.aarch64.neon.ld2. <a href="#a8ef2d14c189d3182a566f37298d21655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f80e3a03a676974b4b4344081ce5d9">selectVectorLoadLaneIntrinsic</a> (unsigned Opc, unsigned NumVecs, MachineInstr &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0bb67adce30bc7d13dfefe2e6646faa">selectVectorStoreIntrinsic</a> (MachineInstr &amp;I, unsigned NumVecs, unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c02c14ad0150c30c04a8adda3c6c515">selectVectorStoreLaneIntrinsic</a> (MachineInstr &amp;I, unsigned NumVecs, unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7416e4d6a818cf24cbaee6cbbe629d6">selectIntrinsicWithSideEffects</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f5297ca8bfca225319decf0e0ee86b">selectIntrinsic</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac850de532b5463d33c96e822b6a16cc5">selectJumpTable</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774783af482908c7c6c2627ad8bb87b6">selectBrJT</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3194cefb4ce8e00fac93b2efb4c79e83">selectTLSGlobalValue</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c359961a4e9534dc89f1a06aac27b85">selectPtrAuthGlobalValue</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608bb29ce6e36506183ed1a59e224b1d">selectReduction</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e939273d92d6e17ef0110fc372371a">selectMOPS</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e0e7af2b14165f3aaeac34514feef63">selectUSMovFromExtend</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab37d4eea40494013b28d7b6877cd1ccf">SelectTable</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, unsigned NumVecs, unsigned Opc1, unsigned Opc2, bool isExt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12092f21db7efc10c6ab26fe2380aac5">selectIndexedExtLoad</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe8753bbee1ecf306e16bbedd3243a8">selectIndexedLoad</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba06a67d6743c921f16ba1662694f34f">selectIndexedStore</a> (GIndexedStore &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0ed35445f07c2a273aa962e169865b">emitConstantPoolEntry</a> (const Constant *CPVal, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46eacb5cfed9ae1a84a59d29552e8b66">emitLoadFromConstantPool</a> (const Constant *CPVal, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dcc6b0186690348121e882a90ca0735">emitVectorConcat</a> (std::optional&lt; Register &gt; Dst, Register Op1, Register Op2, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5d74db0407e426f9f33f6349426431">emitIntegerCompare</a> (MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineOperand &amp;Predicate, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30cdbee925a8444eec0224015ee00145">emitFPCompare</a> (Register LHS, Register RHS, MachineIRBuilder &amp;MIRBuilder, std::optional&lt; CmpInst::Predicate &gt;=std::nullopt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a floating point comparison between <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span>. <a href="#a30cdbee925a8444eec0224015ee00145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af743dc3bac45dcf6481b44967c3cf90b">emitInstr</a> (unsigned Opcode, std::initializer_list&lt; llvm::DstOp &gt; DstOps, std::initializer_list&lt; llvm::SrcOp &gt; SrcOps, MachineIRBuilder &amp;MIRBuilder, const ComplexRendererFns &amp;RenderFns=std::nullopt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf0a681f8d375d2118b7820d0f8f975">emitAddSub</a> (const std::array&lt; std::array&lt; unsigned, 2 &gt;, 5 &gt; &amp;AddrModeAndSizeToOpcode, Register Dst, MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to emit an add or sub instruction. <a href="#a2bf0a681f8d375d2118b7820d0f8f975">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6e1fe9f846c7d6973a298195f824a3">emitADD</a> (Register DefReg, MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade28aff92559b730e51ec3ed1239df47">emitADDS</a> (Register Dst, MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60329d62347841a6a904397baa8b496">emitSUBS</a> (Register Dst, MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7291a485c57a707bd520fd1416428138">emitADCS</a> (Register Dst, MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628c0f0a35d5e4f23759e0d160b9ea23">emitSBCS</a> (Register Dst, MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cca95085bdacee1368dd864f4fe3f2a">emitCMN</a> (MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4831b858b6e465e0b98127bbbe8cee33">emitTST</a> (MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b4a76eb12e73735ee69e1687771629">emitSelect</a> (Register Dst, Register LHS, Register RHS, AArch64CC::CondCode CC, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bce1062abfd2979c750d84964490ae0">emitExtractVectorElt</a> (std::optional&lt; Register &gt; DstReg, const RegisterBank &amp;DstRB, LLT ScalarTy, Register VecReg, unsigned LaneIdx, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3891c4bd14f68e32ae663c2cc69a09">emitCSINC</a> (Register Dst, Register Src1, Register Src2, AArch64CC::CondCode Pred, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ddc54b45bf830cfd634504f06b5884a">emitCSetForFCmp</a> (Register Dst, CmpInst::Predicate Pred, MachineIRBuilder &amp;MIRBuilder) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a CSet for a FP compare. <a href="#a4ddc54b45bf830cfd634504f06b5884a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b68f1b2ad0beef2270c8f885c26edc">emitCarryIn</a> (MachineInstr &amp;I, Register CarryReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an instruction that sets NZCV to the carry-in expected by <span class="doxyComputerOutput">I</span>. <a href="#a14b68f1b2ad0beef2270c8f885c26edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b105eee32559a820078be26fb9c7aba">emitOverflowOp</a> (unsigned Opcode, Register Dst, MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineIRBuilder &amp;MIRBuilder) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the overflow op for <span class="doxyComputerOutput">Opcode</span>. <a href="#a0b105eee32559a820078be26fb9c7aba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35558fa9598640018812a4758a0f40e9">selectOverflowOp</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8327f0e50f527c3216c957c0dd1aed7">emitConjunction</a> (Register Val, AArch64CC::CondCode &amp;OutCC, MachineIRBuilder &amp;MIB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit expression as a conjunction (a series of CCMP/CFCMP ops). <a href="#ab8327f0e50f527c3216c957c0dd1aed7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54a6af8998978db7088625e0ae7e1f3">emitConditionalComparison</a> (Register LHS, Register RHS, CmpInst::Predicate CC, AArch64CC::CondCode Predicate, AArch64CC::CondCode OutCC, MachineIRBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2419c4178439add7064b801a2e2f828">emitConjunctionRec</a> (Register Val, AArch64CC::CondCode &amp;OutCC, bool Negate, Register CCOp, AArch64CC::CondCode Predicate, MachineIRBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda589f41725737ecbfe4bfeaa4ea951">emitTestBit</a> (Register TestReg, uint64_t Bit, bool IsNegative, MachineBasicBlock *DstMBB, MachineIRBuilder &amp;MIB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a TB(N)Z instruction which tests <span class="doxyComputerOutput">Bit</span> in <span class="doxyComputerOutput">TestReg</span>. <a href="#abda589f41725737ecbfe4bfeaa4ea951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf4f4048100bafb6176cc566e1b09698">emitCBZ</a> (Register CompareReg, bool IsNegative, MachineBasicBlock *DestMBB, MachineIRBuilder &amp;MIB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a CB(N)Z instruction which branches to <span class="doxyComputerOutput">DestMBB</span>. <a href="#acf4f4048100bafb6176cc566e1b09698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08dc3a152abeaf8931d6c885cce24b9b">selectShiftA_32</a> (const MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09b58717a6159600e362c6d3caf9ddf">selectShiftB_32</a> (const MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7ae46dba1ae2c64f3107dc6a43b89e">selectShiftA_64</a> (const MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1583b9431cba266b8c29ef892577160">selectShiftB_64</a> (const MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ef795760a6f3666ea2dd5c419c7c89">select12BitValueWithLeftShift</a> (uint64_t Immed) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to select an immediate value that can be represented as a 12-bit value shifted left by either 0 or 12. <a href="#a50ef795760a6f3666ea2dd5c419c7c89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa33ab02e192a578ee0ae3139dac8204c">selectArithImmed</a> (MachineOperand &amp;Root) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectArithImmed - Select an immediate value that can be represented as a 12-bit value shifted left by either 0 or 12. <a href="#aa33ab02e192a578ee0ae3139dac8204c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff7297b72c5d1ab57bff475b73b263f">selectNegArithImmed</a> (MachineOperand &amp;Root) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectNegArithImmed - As above, but negates the value before trying to select it. <a href="#a0ff7297b72c5d1ab57bff475b73b263f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f7acae51ba89c2b3c92f22cf53f569">selectAddrModeUnscaled</a> (MachineOperand &amp;Root, unsigned Size) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select a "register plus unscaled signed 9-bit immediate" address. <a href="#af4f7acae51ba89c2b3c92f22cf53f569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42ad92eb018806e69d8fdb219ae57ab">selectAddrModeUnscaled8</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a910cd225662f5dd44d55e5b1860b100c">selectAddrModeUnscaled16</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc575035e429b7e9397f58128bda6ce0">selectAddrModeUnscaled32</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0bb9ae60b36f8083ba17d02d404629">selectAddrModeUnscaled64</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1161c5e76c79f6ad82501de03520ba4c">selectAddrModeUnscaled128</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee824bf8367585b47a3aeebb68beaf3">tryFoldAddLowIntoImm</a> (MachineInstr &amp;RootDef, unsigned Size, MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to try to fold in a GISEL_ADD_LOW into an immediate, to be used from complex pattern matchers like selectAddrModeIndexed(). <a href="#a0ee824bf8367585b47a3aeebb68beaf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971a9d27067b67eb24debe53b6d3e8d4">selectAddrModeIndexed</a> (MachineOperand &amp;Root, unsigned Size) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select a "register plus scaled unsigned 12-bit immediate" address. <a href="#a971a9d27067b67eb24debe53b6d3e8d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a84999cfeb041d180b65c128d1278a665">selectAddrModeIndexed</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ea2c1b3c82940b66e0a1f92cd9e293">isWorthFoldingIntoAddrMode</a> (MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if we are sure that folding MI into load/store addressing mode is beneficial or not. <a href="#ae2ea2c1b3c82940b66e0a1f92cd9e293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af761fdf2f644e7b626aa7d42b24c3082">isWorthFoldingIntoExtendedReg</a> (MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, bool IsAddrOperand) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is worth folding MI into an extended register. <a href="#af761fdf2f644e7b626aa7d42b24c3082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6cbc7ca3e7109c94c1cb5f223629b9">selectAddrModeShiftedExtendXReg</a> (MachineOperand &amp;Root, unsigned SizeInBytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used for computing addresses like this: <a href="#aaf6cbc7ca3e7109c94c1cb5f223629b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e136748ec6b953fd4f4db87cf999c8">selectExtendedSHL</a> (MachineOperand &amp;Root, MachineOperand &amp;Base, MachineOperand &amp;Offset, unsigned SizeInBytes, bool WantsExt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></span> which contains a base, offset, and whether or not a shift + extend should be folded into an addressing mode. <a href="#aa2e136748ec6b953fd4f4db87cf999c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06ab88243a957a7c5b5e30b121ff1da">selectAddrModeRegisterOffset</a> (MachineOperand &amp;Root) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used for computing addresses like this: <a href="#ae06ab88243a957a7c5b5e30b121ff1da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2260c281108503134d45f4ae2a70a0">selectAddrModeXRO</a> (MachineOperand &amp;Root, unsigned SizeInBytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is intended to be equivalent to selectAddrModeXRO in AArch64ISelDAGtoDAG. <a href="#afa2260c281108503134d45f4ae2a70a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf396537c7ad3d3d668cb71183db6d37">selectAddrModeXRO</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05256685e561b6ebf67d6cfa057db31">selectAddrModeWRO</a> (MachineOperand &amp;Root, unsigned SizeInBytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used for computing addresses like this: <a href="#aa05256685e561b6ebf67d6cfa057db31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a460d782da320838c534a66a7d47aea63">selectAddrModeWRO</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53f6caa0424bc88f7704beae8823406">selectShiftedRegister</a> (MachineOperand &amp;Root, bool AllowROR=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select a "shifted register" operand. <a href="#ac53f6caa0424bc88f7704beae8823406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d1abba062d9d2ec0c7fc93f4b818adc">selectArithShiftedRegister</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8959074ca780f5b8dae1d468ee7270f">selectLogicalShiftedRegister</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cce7d7e6c8096abb8d45f96d37988a6">getExtendTypeForInst</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, bool IsLoadStore=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an extend instruction, determine the correct shift-extend type for that instruction. <a href="#a7cce7d7e6c8096abb8d45f96d37988a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab269ffb756db8a8e6c91a9cc62298d">moveScalarRegClass</a> (Register Reg, const TargetRegisterClass &amp;RC, MachineIRBuilder &amp;MIB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move <span class="doxyComputerOutput">Reg</span> to <span class="doxyComputerOutput">RC</span> if <span class="doxyComputerOutput">Reg</span> is not already on <span class="doxyComputerOutput">RC</span>. <a href="#a1ab269ffb756db8a8e6c91a9cc62298d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d88c97a72999f5d82617e63dba3fb0a">selectArithExtendedRegister</a> (MachineOperand &amp;Root) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select an "extended register" operand. <a href="#a4d88c97a72999f5d82617e63dba3fb0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90587a2df176ee775e2b701d1ac58942">selectExtractHigh</a> (MachineOperand &amp;Root) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70857bef2054bb5d25324647f20d2f35">renderTruncImm</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;MI, int OpIdx=-1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b27afc814f8a81794bd656fd784cdcd">renderLogicalImm32</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;I, int OpIdx=-1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ba7b34884abc123d4488ad3278a70e">renderLogicalImm64</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;I, int OpIdx=-1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5f553440b585dfa96041522e851563">renderUbsanTrap</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;MI, int OpIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b53cf04ff0e7a9a4130c759684fdb6">renderFPImm16</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;MI, int OpIdx=-1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c1c85e15f61e4d4a96e7e2da54deb1">renderFPImm32</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;MI, int OpIdx=-1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7d0276306ddc42ffabdee6ce8595e0">renderFPImm64</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;MI, int OpIdx=-1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef10c89e0593186de7e6288d26fb44b">renderFPImm32SIMDModImmType4</a> (MachineInstrBuilder &amp;MIB, const MachineInstr &amp;MI, int OpIdx=-1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f5208aa196c697ca152a45cf1f403b">materializeLargeCMVal</a> (MachineInstr &amp;I, const Value *V, unsigned OpFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2017a0d5297b89ee04d69dd2f1ff446b">tryOptSelect</a> (GSelect &amp;Sel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b1d0d5f28cce4f477e64ebffececb1">tryOptSelectConjunction</a> (GSelect &amp;Sel, MachineInstr &amp;CondMI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab5d083edbf744189ba625c61caeedc">tryFoldIntegerCompare</a> (MachineOperand &amp;LHS, MachineOperand &amp;RHS, MachineOperand &amp;Predicate, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ae1e98ec2e48dd5f6bda6a55cec123">isLoadStoreOfNumBytes</a> (const MachineInstr &amp;MI, unsigned NumBytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">MI</span> is a load or store of <span class="doxyComputerOutput">NumBytes</span> bytes. <a href="#ae6ae1e98ec2e48dd5f6bda6a55cec123">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad568c930d31d0d9b4a43ec05827685">isDef32</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">MI</span> is guaranteed to have the high-half of a 64-bit register zeroed out. <a href="#a1ad568c930d31d0d9b4a43ec05827685">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine">AArch64TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ecd1d9e0d57e5b89ad6ebdbe6b9d66">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae21fdecd11628c1d9cb0da1e9fe6840f">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo">AArch64InstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890b1e0bb5ec6da30048e40dc38f7427">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo">AArch64RegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345cc6e6dccf33bf37e5623966a220c3">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo">AArch64RegisterBankInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70bcf66f03eecfa6591c77e4c976524f">RBI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe4495aade98de335d1a4a45ad1465a">ProduceNonFlagSettingCondBr</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a1d5c3a1d1922e31058c7ab38b340f">MFReturnAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146ab4742ca86061b2e57d63d3d4e4f4">MIB</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd9e1db771e6baae1043da8baed60df">getName</a> ()</td>
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


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64InstructionSelector() {#af05eae0f7e71dedbf2aa224f4c38eaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64InstructionSelector::AArch64InstructionSelector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine">AArch64TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo">AArch64RegisterBankInfo</a> &amp; RBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a register bank, and a type, return the smallest register class that can represent that combination.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a1ab538c256c3204b950075744d5b2b16">GET_GLOBALISEL_PREDICATES_INIT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a1cd36a579f079f7f4506d9d097b2f0a8">GET_GLOBALISEL_TEMPORARIES_INIT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### selectCompareBranchFedByFCmp() {#aab262affd2dff9550b4c19d920d21136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectCompareBranchFedByFCmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; FCmp, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Helper functions for selectCompareBranch.</p>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectCompareBranchFedByICmp() {#a7835ac895d410e58d9e094ff9ea8d6a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectCompareBranchFedByICmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; ICmp, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryOptAndIntoCompareBranch() {#a837d6174175d2ad93a02815794af8c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::tryOptAndIntoCompareBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; AndInst, bool Invert, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryOptCompareBranchFedByICmp() {#a1c8b67464ec020f4a40a549b1653cee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::tryOptCompareBranchFedByICmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; ICmp, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### select() {#acf1575bd51e7b6b91a92904410f268aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::select (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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

<p>Select the (possibly generic) instruction <span class="doxyComputerOutput">I</span> to only use target-specific opcodes.</p>


<p>It is OK to insert multiple instructions, but they cannot be generic pre-isel instructions.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>whether selection succeeded.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>I.getParent() &amp;&amp; I.getParent()-&gt;<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p>if returns true: for I in all mutated/inserted instructions: !isPreISelGenericOpcode(I.getOpcode())</p></dd>
</dl>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6eb17a3fc032cb29dbc1908f1d4ba046">llvm::MachineInstrBuilder::addBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a79aef281242f8877523e32b6a669356e">changeICMPPredToAArch64CC</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#ae5900cfb710c3c8b5f5d2a5b0cadabf9">llvm::GIMatchTableExecutor::CoverageInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a832ad315a355f4ddcc32f189f34e28a9">llvm::AArch64_AM::encodeLogicalImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a9a76e0197f5c34a3e15ba92fbdc9c8b4">llvm::EVT::getFloatingPointVT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aee59c647052fc9557561e596681da3c0">llvm::MachineOperand::getFPImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56f5d55460d7e31fc6c3318882f36ac7">llvm::getIConstantVRegSExtVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3e9d2a9063bce7f5b3d7dd21fd05c79d">llvm::MachineMemOperand::getMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a515116c40bd191aee04f328b504d5692">llvm::GMemOperation::getMemSize</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#ac815a03646b3fcf26176feb2c669fb9e">llvm::GMemOperation::getMemSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a902b09cfe1ad72267169b4f08909f680">getSubRegForClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa45abfa63d76025a0e5b9a46e25dd8d">llvm::MachineMemOperand::getSuccessOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a4df127df519885541003937cde4f22d6">llvm::AArch64FunctionInfo::hasELFSignedGOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a239427c2c3a01e23bd15b29633696536">llvm::GlobalValue::isThreadLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a52fb4682a4be0321cf8eec99c1f76f93">llvm::GIMatchTableExecutor::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc">llvm::AArch64II::MO_NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a7f04634c15a04a59d5f234002e613b5b">llvm::AArch64II::MO_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a3a5053185998bdf24f3167c234915785">llvm::AArch64II::MO_PAGEOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">llvm::AArch64CC::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1cf224b3316c689f4735877ef0bbd893">llvm::MachineInstr::NoFPExcept</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a8e3929f9a80e9ff6d48e35bba3e2d600">selectBinaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#ab328c242b91fe2bc4d6d0797761fdea1">selectDebugInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a18c672925e05a23b72838be961003fc7">selectFPConvOpc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a61d01252826372b1ec3aefc12e0c23d1">selectLoadStoreUIOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a9554b6a1531cc435fc2508a89a9748e0">llvm::GIMatchTableExecutor::shouldOptForSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#ac3419b7821dce4fc2e3a6f4a96b7dbaa">unsupportedBinOp</a>.</p>

</div>
</div>

### setupMF() {#a83151fce4b310c403a42a444660e030b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> * kb, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage">CodeGenCoverage</a> * covinfo, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * psi, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * bfi)</td>
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

<p>Setup per-MF executor state.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a224495037f6eee0b6970aa0c30fffb74">llvm::GIMatchTableExecutor::BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#ae5900cfb710c3c8b5f5d2a5b0cadabf9">llvm::GIMatchTableExecutor::CoverageInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a42689945d570c32ab32defb5469ca47b">llvm::GIMatchTableExecutor::KB</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a52fb4682a4be0321cf8eec99c1f76f93">llvm::GIMatchTableExecutor::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#aa2ed5c2002db167510960436bf654fc2">llvm::GIMatchTableExecutor::PSI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#abc092c61ef888b461f955c86b994511c">llvm::GIMatchTableExecutor::setupMF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### contractCrossBankCopyIntoStore() {#a009e77efca5522b14dce1c1ae103b3f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::contractCrossBankCopyIntoStore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminate same-sized cross-bank copies into stores before selectImpl().</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### convertPtrAddToAdd() {#adf70776136caad338d1943e228a45702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::convertPtrAddToAdd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This lowering tries to look for G_PTR_ADD instructions and then converts them to a standard G_ADD with a COPY on the source.</p>


<p>The motivation behind this is to expose the add semantics to the imported tablegen patterns. We shouldn't need to check for uses being loads/stores, because the selector works bottom up, uses before defs. By the time we end up trying to select a G_PTR_ADD, we should have already attempted to fold this into addressing modes and were therefore unsuccessful.</p>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### earlySelect() {#a283fdd97f071b4a9948422026d590186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::earlySelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### earlySelectSHL() {#a1bf69661f1b6089a24141ba232e20dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::earlySelectSHL (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitADCS() {#a7291a485c57a707bd520fd1416428138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitADCS (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitADD() {#aaf6e1fe9f846c7d6973a298195f824a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitADD (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DefReg, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitADDS() {#ade28aff92559b730e51ec3ed1239df47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitADDS (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitAddSub() {#a2bf0a681f8d375d2118b7820d0f8f975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitAddSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::array&lt; std::array&lt; unsigned, 2 &gt;, 5 &gt; &amp; AddrModeAndSizeToOpcode, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to emit an add or sub instruction.</p>


<p><span class="doxyComputerOutput">AddrModeAndSizeToOpcode</span> must contain each of the opcode variants above in a specific order.</p>


<p>Below is an example of the expected input to <span class="doxyComputerOutput">AddrModeAndSizeToOpcode</span>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::array&lt;std::array&lt;unsigned, 2&gt;, 4&gt; Table {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> {{AArch64::ADDXri, AArch64::ADDWri},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  {AArch64::ADDXrs, AArch64::ADDWrs},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  {AArch64::ADDXrr, AArch64::ADDWrr},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  {AArch64::SUBXri, AArch64::SUBWri},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  {AArch64::ADDXrx, AArch64::ADDWrx}}};</span></span></div>

</div>


<p>Each row in the table corresponds to a different addressing mode. Each column corresponds to a different register size.</p>



:::danger
<p>Rows must be structured as follows:</p>


<ul class="doxyList ">
<li>Row 0: The ri opcode variants</li>
<li>Row 1: The rs opcode variants</li>
<li>Row 2: The rr opcode variants</li>
<li>Row 3: The ri opcode variants for negative immediates</li>
<li>Row 4: The rx opcode variants</li>
</ul>
:::



:::danger
<p>Columns must be structured as follows:</p>


<ul class="doxyList ">
<li>Column 0: The 64-bit opcode variants</li>
<li>Column 1: The 32-bit opcode variants</li>
</ul>
:::


<p><span class="doxyComputerOutput">Dst</span> is the destination register of the binop to emit. <span class="doxyComputerOutput">LHS</span> is the left-hand operand of the binop to emit. <span class="doxyComputerOutput">RHS</span> is the right-hand operand of the binop to emit.</p>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitCarryIn() {#a14b68f1b2ad0beef2270c8f885c26edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitCarryIn (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> CarryReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an instruction that sets NZCV to the carry-in expected by <span class="doxyComputerOutput">I</span>.</p>


<p>Might elide the instruction if the previous instruction already sets NZCV correctly.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitCBZ() {#acf4f4048100bafb6176cc566e1b09698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitCBZ (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> CompareReg, bool IsNegative, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DestMBB, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a CB(N)Z instruction which branches to <span class="doxyComputerOutput">DestMBB</span>.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitCMN() {#a6cca95085bdacee1368dd864f4fe3f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitCMN (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitConditionalComparison() {#af54a6af8998978db7088625e0ae7e1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitConditionalComparison (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> CC, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> OutCC, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitConjunction() {#ab8327f0e50f527c3216c957c0dd1aed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitConjunction (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> &amp; OutCC, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit expression as a conjunction (a series of CCMP/CFCMP ops).</p>


<p>In some cases this is even possible with OR operations in the expression.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitConjunctionRec() {#af2419c4178439add7064b801a2e2f828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitConjunctionRec (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> &amp; OutCC, bool Negate, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> CCOp, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> Predicate, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitConstantPoolEntry() {#a2d0ed35445f07c2a273aa962e169865b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64InstructionSelector::emitConstantPoolEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CPVal, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitConstantVector() {#ae277c162686b7c68014bfc3cde865fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitConstantVector (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CV, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a sequence of instructions representing a constant <span class="doxyComputerOutput">CV</span> for a vector register <span class="doxyComputerOutput">Dst</span>.</p>


<p>(E.g. a MOV, or a load from a constant pool.)</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the last instruction in the sequence on success, and nullptr otherwise.</p></dd>
</dl>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitCSetForFCmp() {#a4ddc54b45bf830cfd634504f06b5884a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitCSetForFCmp (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a CSet for a FP compare.</p>


<p><span class="doxyComputerOutput">Dst</span> is expected to be a 32-bit scalar register.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitCSINC() {#acf3891c4bd14f68e32ae663c2cc69a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitCSINC (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src1, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src2, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitExtractVectorElt() {#a0bce1062abfd2979c750d84964490ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitExtractVectorElt (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; DstReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; DstRB, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ScalarTy, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VecReg, unsigned LaneIdx, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitFPCompare() {#a30cdbee925a8444eec0224015ee00145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitFPCompare (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> &gt; Pred=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a floating point comparison between <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span>.</p>


<p><span class="doxyComputerOutput">Pred</span> if given is the intended predicate to use.</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitInstr() {#af743dc3bac45dcf6481b44967c3cf90b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitInstr (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">llvm::DstOp</a> &gt; DstOps, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">llvm::SrcOp</a> &gt; SrcOps, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a> &amp; RenderFns=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitIntegerCompare() {#acd5d74db0407e426f9f33f6349426431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitIntegerCompare (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Predicate, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitLaneInsert() {#a277649237a306d77c468a5bfc6b6b8f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitLaneInsert (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> EltReg, unsigned LaneIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; RB, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a lane insert into <span class="doxyComputerOutput">DstReg</span>, or a new vector register if std::nullopt is provided.</p>


<p>The lane inserted into is defined by <span class="doxyComputerOutput">LaneIdx</span>. The vector source register is given by <span class="doxyComputerOutput">SrcReg</span>. The register containing the element is given by <span class="doxyComputerOutput">EltReg</span>.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitLoadFromConstantPool() {#a46eacb5cfed9ae1a84a59d29552e8b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitLoadFromConstantPool (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CPVal, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitNarrowVector() {#a72a69a004bf8c5d96a593dcb98735fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitNarrowVector (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to narrow vector that was widened by emitScalarToVector.</p>


<p>Copy lowest part of 128-bit or 64-bit vector to 64-bit or 32-bit vector, correspondingly.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitOverflowOp() {#a0b105eee32559a820078be26fb9c7aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; MachineInstr *, AArch64CC::CondCode &gt; AArch64InstructionSelector::emitOverflowOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the overflow op for <span class="doxyComputerOutput">Opcode</span>.</p>


<p><span class="doxyComputerOutput">Opcode</span> is expected to be an overflow op's opcode, e.g. G_UADDO, G_USUBO, etc.</p>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitSBCS() {#a628c0f0a35d5e4f23759e0d160b9ea23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitSBCS (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitScalarToVector() {#a875a4ba35f2b56dd82d6c673ffb7fc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitScalarToVector (unsigned EltSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Scalar, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitSelect() {#a41b4a76eb12e73735ee69e1687771629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitSelect (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RHS, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> CC, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitSUBS() {#ab60329d62347841a6a904397baa8b496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitSUBS (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitTestBit() {#abda589f41725737ecbfe4bfeaa4ea951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitTestBit (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TestReg, uint64_t Bit, bool IsNegative, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DstMBB, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a TB(N)Z instruction which tests <span class="doxyComputerOutput">Bit</span> in <span class="doxyComputerOutput">TestReg</span>.</p>


<p><span class="doxyComputerOutput">IsNegative</span> is true if the test should be "not zero". This will also optimize the test bit instruction when possible.</p>


<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitTST() {#a4831b858b6e465e0b98127bbbe8cee33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitTST (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitVectorConcat() {#a7dcc6b0186690348121e882a90ca0735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::emitVectorConcat (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### getExtendTypeForInst() {#a7cce7d7e6c8096abb8d45f96d37988a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64_AM::ShiftExtendType AArch64InstructionSelector::getExtendTypeForInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, bool IsLoadStore=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an extend instruction, determine the correct shift-extend type for that instruction.</p>


<p>If the instruction is going to be used in a load or store, pass <span class="doxyComputerOutput">IsLoadStore</span> = true.</p>


<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### isDef32() {#a1ad568c930d31d0d9b4a43ec05827685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::isDef32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">MI</span> is guaranteed to have the high-half of a 64-bit register zeroed out.</p>


<p>In other words, the result of MI has been explicitly zero extended.</p>


<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### isLoadStoreOfNumBytes() {#ae6ae1e98ec2e48dd5f6bda6a55cec123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::isLoadStoreOfNumBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned NumBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">MI</span> is a load or store of <span class="doxyComputerOutput">NumBytes</span> bytes.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### isWorthFoldingIntoAddrMode() {#ae2ea2c1b3c82940b66e0a1f92cd9e293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; AArch64InstructionSelector::isWorthFoldingIntoAddrMode (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if we are sure that folding MI into load/store addressing mode is beneficial or not.</p>


<p>Returns:</p>


<ul class="doxyList ">
<li>true if folding MI would be beneficial.</li>
<li>false if folding MI would be bad.</li>
<li>std::nullopt if it is not sure whether folding MI is beneficial.</li>
</ul>

<p><span class="doxyComputerOutput">MI</span> can be the offset operand of G_PTR_ADD, e.g. G_SHL in the example:</p>


<p>%13:gpr(s64) = G_CONSTANT i64 1 %8:gpr(s64) = G_SHL %6, %13(s64) %9:gpr(p0) = G_PTR_ADD %0, %8(s64) %12:gpr(s32) = G_LOAD %9(p0) :: (load (s16))</p>


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### isWorthFoldingIntoExtendedReg() {#af761fdf2f644e7b626aa7d42b24c3082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::isWorthFoldingIntoExtendedReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, bool IsAddrOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is worth folding MI into an extended register.</p>


<p>That is, if it's safe to pull it into the addressing mode of a load or store as a shift. <span class="doxyComputerOutput">IsAddrOperand</span> whether the def of MI is used as an address operand (e.g. feeding into an LDR/STR).</p>


<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### materializeLargeCMVal() {#ac9f5208aa196c697ca152a45cf1f403b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::materializeLargeCMVal (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned OpFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### moveScalarRegClass() {#a1ab269ffb756db8a8e6c91a9cc62298d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AArch64InstructionSelector::moveScalarRegClass (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move <span class="doxyComputerOutput">Reg</span> to <span class="doxyComputerOutput">RC</span> if <span class="doxyComputerOutput">Reg</span> is not already on <span class="doxyComputerOutput">RC</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Either <span class="doxyComputerOutput">Reg</span> if no change was necessary, or the new register created by moving <span class="doxyComputerOutput">Reg</span>.</p></dd>
</dl>


<p>Note: This uses emitCopy right now.</p>


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### preISelLower() {#ad162c736325899752752db3704aa1595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::preISelLower (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### processPHIs() {#a7e55090db7909c26abd97d3b29abfa61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::processPHIs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderFPImm16() {#a55b53cf04ff0e7a9a4130c759684fdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderFPImm16 (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIdx=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderFPImm32() {#a36c1c85e15f61e4d4a96e7e2da54deb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderFPImm32 (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIdx=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderFPImm32SIMDModImmType4() {#a0ef10c89e0593186de7e6288d26fb44b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderFPImm32SIMDModImmType4 (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIdx=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderFPImm64() {#adb7d0276306ddc42ffabdee6ce8595e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderFPImm64 (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIdx=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderLogicalImm32() {#a2b27afc814f8a81794bd656fd784cdcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderLogicalImm32 (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, int OpIdx=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderLogicalImm64() {#a58ba7b34884abc123d4488ad3278a70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderLogicalImm64 (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, int OpIdx=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderTruncImm() {#a70857bef2054bb5d25324647f20d2f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderTruncImm (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIdx=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### renderUbsanTrap() {#a7f5f553440b585dfa96041522e851563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::renderUbsanTrap (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### select12BitValueWithLeftShift() {#a50ef795760a6f3666ea2dd5c419c7c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::select12BitValueWithLeftShift (uint64_t Immed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to select an immediate value that can be represented as a 12-bit value shifted left by either 0 or 12.</p>


<p>If it is possible to do so, return the immediate and shift value. If not, return std::nullopt.</p>


<p>Used by selectArithImmed and selectNegArithImmed.</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeIndexed() {#a971a9d27067b67eb24debe53b6d3e8d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectAddrModeIndexed (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select a "register plus scaled unsigned 12-bit immediate" address.</p>


<p>The "Size" argument is the size in bytes of the memory reference, which determines the scale.</p>


<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeIndexed() {#a84999cfeb041d180b65c128d1278a665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeIndexed (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeRegisterOffset() {#ae06ab88243a957a7c5b5e30b121ff1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectAddrModeRegisterOffset (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is used for computing addresses like this:</p>


<p>ldr x1, [x2, x3]</p>


<p>Where x2 is the base register, and x3 is an offset register.</p>


<p>When possible (or profitable) to fold a G_PTR_ADD into the address calculation, this will do so. Otherwise, it will return std::nullopt.</p>


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeShiftedExtendXReg() {#aaf6cbc7ca3e7109c94c1cb5f223629b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectAddrModeShiftedExtendXReg (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, unsigned SizeInBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is used for computing addresses like this:</p>


<p>ldr x1, [x2, x3, lsl #3]</p>


<p>Where x2 is the base register, and x3 is an offset register. The shift-left is a constant value specific to this load instruction. That is, we'll never see anything other than a 3 here (which corresponds to the size of the element being loaded.)</p>


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeUnscaled() {#af4f7acae51ba89c2b3c92f22cf53f569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectAddrModeUnscaled (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select a "register plus unscaled signed 9-bit immediate" address.</p>


<p>This should only match when there is an offset that is not valid for a scaled immediate addressing mode. The "Size" argument is the size in bytes of the memory reference, which is needed here to know what is valid for a scaled immediate.</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeUnscaled128() {#a1161c5e76c79f6ad82501de03520ba4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeUnscaled128 (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeUnscaled16() {#a910cd225662f5dd44d55e5b1860b100c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeUnscaled16 (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeUnscaled32() {#abc575035e429b7e9397f58128bda6ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeUnscaled32 (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeUnscaled64() {#a0f0bb9ae60b36f8083ba17d02d404629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeUnscaled64 (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeUnscaled8() {#aa42ad92eb018806e69d8fdb219ae57ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeUnscaled8 (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeWRO() {#aa05256685e561b6ebf67d6cfa057db31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectAddrModeWRO (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, unsigned SizeInBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is used for computing addresses like this:</p>


<p>ldr x0, [xBase, wOffset, sxtw #LegalShiftVal]</p>


<p>Where we have a 64-bit base register, a 32-bit offset register, and an extend (which may or may not be signed).</p>


<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeWRO() {#a460d782da320838c534a66a7d47aea63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeWRO (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeXRO() {#afa2260c281108503134d45f4ae2a70a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectAddrModeXRO (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, unsigned SizeInBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is intended to be equivalent to selectAddrModeXRO in AArch64ISelDAGtoDAG.</p>


<p>It's used for selecting X register offset loads.</p>


<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAddrModeXRO() {#adf396537c7ad3d3d668cb71183db6d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectAddrModeXRO (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAndRestoreState() {#a25f89e27e475d3cc59922f212ba2922b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectAndRestoreState (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Save state that is shared between select calls, call select on <span class="doxyComputerOutput">I</span> and then restore the saved state.</p>


<p>This can be used to recursively call select within a select call.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectArithExtendedRegister() {#a4d88c97a72999f5d82617e63dba3fb0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectArithExtendedRegister (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select an "extended register" operand.</p>


<p>This operand folds in an extend followed by an optional left shift.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectArithImmed() {#aa33ab02e192a578ee0ae3139dac8204c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectArithImmed (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectArithImmed - Select an immediate value that can be represented as a 12-bit value shifted left by either 0 or 12.</p>


<p>If so, return true with Val set to the 12-bit value and Shift set to the shifter operand.</p>


<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectArithShiftedRegister() {#a1d1abba062d9d2ec0c7fc93f4b818adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectArithShiftedRegister (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectBrJT() {#a774783af482908c7c6c2627ad8bb87b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectBrJT (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectBuildVector() {#aae40ae6e14203d8aa368fee62fa924c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectBuildVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectCompareBranch() {#a20e3d92bad9bfc7aa46dd0fdedfd8543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectCompareBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectConcatVectors() {#ac39baf8cd7d59984c76fa52ba758e692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectConcatVectors (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectExtendedSHL() {#aa2e136748ec6b953fd4f4db87cf999c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectExtendedSHL (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Offset, unsigned SizeInBytes, bool WantsExt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a></span> which contains a base, offset, and whether or not a shift + extend should be folded into an addressing mode.</p>


<p>Returns None when this is not profitable or possible.</p>


<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectExtractElt() {#ac6a3997aa971a05ed73ddc3f41dfe7be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectExtractElt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectExtractHigh() {#a90587a2df176ee775e2b701d1ac58942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectExtractHigh (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectImpl() {#a351c916dc6beda1d43bd73526550747b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectImpl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage">CodeGenCoverage</a> &amp; CoverageInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tblgen-erated 'select' implementation, used as the initial selector for the patterns that don't require complex C++.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectIndexedExtLoad() {#a12092f21db7efc10c6ab26fe2380aac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectIndexedExtLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectIndexedLoad() {#aafe8753bbee1ecf306e16bbedd3243a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectIndexedLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectIndexedStore() {#aba06a67d6743c921f16ba1662694f34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectIndexedStore (<a href="/web-llvm/docs/api/classes/llvm/gindexedstore">GIndexedStore</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectIntrinsic() {#a30f5297ca8bfca225319decf0e0ee86b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectIntrinsicWithSideEffects() {#ae7416e4d6a818cf24cbaee6cbbe629d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectIntrinsicWithSideEffects (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectJumpTable() {#ac850de532b5463d33c96e822b6a16cc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectJumpTable (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectLogicalShiftedRegister() {#ad8959074ca780f5b8dae1d468ee7270f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexRendererFns anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectLogicalShiftedRegister (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
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



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectMergeValues() {#a42e07cd2c5f3813797e6a5cf42f25e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectMergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectMOPS() {#a05e939273d92d6e17ef0110fc372371a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectMOPS (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectNegArithImmed() {#a0ff7297b72c5d1ab57bff475b73b263f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectNegArithImmed (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectNegArithImmed - As above, but negates the value before trying to select it.</p>

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectOverflowOp() {#a35558fa9598640018812a4758a0f40e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectOverflowOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectPtrAuthGlobalValue() {#a4c359961a4e9534dc89f1a06aac27b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectPtrAuthGlobalValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectReduction() {#a608bb29ce6e36506183ed1a59e224b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::selectReduction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectShiftA\_32() {#a08dc3a152abeaf8931d6c885cce24b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectShiftA_32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectShiftA\_64() {#aec7ae46dba1ae2c64f3107dc6a43b89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectShiftA_64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectShiftB\_32() {#af09b58717a6159600e362c6d3caf9ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectShiftB_32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectShiftB\_64() {#ac1583b9431cba266b8c29ef892577160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectShiftB_64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectShiftedRegister() {#ac53f6caa0424bc88f7704beae8823406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::selectShiftedRegister (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, bool AllowROR=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select a "shifted register" operand.</p>


<p>If the value is not shifted, set the shift operand to a default value of "lsl 0".</p>


<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectShuffleVector() {#ae22d49e8cc2d210ffdb69fcd2fdc1b44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectShuffleVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectSplitVectorUnmerge() {#ad0d5f3b7006745545cd2126b063e7e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectSplitVectorUnmerge (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### SelectTable() {#ab37d4eea40494013b28d7b6877cd1ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::SelectTable (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned NumVecs, unsigned Opc1, unsigned Opc2, bool isExt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectTLSGlobalValue() {#a3194cefb4ce8e00fac93b2efb4c79e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectTLSGlobalValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectUnmergeValues() {#ac2ce95dd7e4c83726a14ba39a524ff82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectUnmergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectUSMovFromExtend() {#a5e0e7af2b14165f3aaeac34514feef63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectUSMovFromExtend (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVaStartAAPCS() {#ac6b29e14f00dda770a2fbfc63dc33485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectVaStartAAPCS (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVaStartDarwin() {#ac11466883ccafaf4fc0f39eced7fda79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectVaStartDarwin (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVectorAshrLshr() {#adf9bda4e39cd62deaa118371b91831fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectVectorAshrLshr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVectorLoadIntrinsic() {#a8ef2d14c189d3182a566f37298d21655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectVectorLoadIntrinsic (unsigned Opc, unsigned NumVecs, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to select vector load intrinsics like @llvm.aarch64.neon.ld2.</p>


<p>*, @llvm.aarch64.neon.ld4.*, etc. <span class="doxyComputerOutput">Opc</span> is the opcode that the selected instruction should use. <span class="doxyComputerOutput">NumVecs</span> is the number of vector destinations for the instruction. <span class="doxyComputerOutput">I</span> is the original G_INTRINSIC_W_SIDE_EFFECTS instruction.</p>


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVectorLoadLaneIntrinsic() {#a30f80e3a03a676974b4b4344081ce5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectVectorLoadLaneIntrinsic (unsigned Opc, unsigned NumVecs, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVectorSHL() {#a92133d53afe21485777eed333a14fa93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectVectorSHL (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVectorStoreIntrinsic() {#ad0bb67adce30bc7d13dfefe2e6646faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64InstructionSelector::selectVectorStoreIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, unsigned NumVecs, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectVectorStoreLaneIntrinsic() {#a4c02c14ad0150c30c04a8adda3c6c515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::selectVectorStoreLaneIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, unsigned NumVecs, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryAdvSIMDModImm16() {#a05cd8aa16b47b35a22dc52e0ffd51b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::tryAdvSIMDModImm16 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, unsigned DstSize, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Bits, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, bool Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryAdvSIMDModImm32() {#a18128d2a02cd5be7601756814e88af3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::tryAdvSIMDModImm32 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, unsigned DstSize, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Bits, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, bool Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryAdvSIMDModImm321s() {#a920e87ea1cfaed92d1fac1f052c4d501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::tryAdvSIMDModImm321s (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, unsigned DstSize, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Bits, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, bool Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryAdvSIMDModImm64() {#a3cd988201d74aa61567734debc3c958a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::tryAdvSIMDModImm64 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, unsigned DstSize, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Bits, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryAdvSIMDModImm8() {#a4440a1b3592fcd2c5cb2491addff0ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::tryAdvSIMDModImm8 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, unsigned DstSize, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Bits, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryAdvSIMDModImmFP() {#a30d16518feeb58d169a0ec0e59fd63e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::tryAdvSIMDModImmFP (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, unsigned DstSize, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Bits, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryFoldAddLowIntoImm() {#a0ee824bf8367585b47a3aeebb68beaf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector::ComplexRendererFns AArch64InstructionSelector::tryFoldAddLowIntoImm (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; RootDef, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to try to fold in a GISEL_ADD_LOW into an immediate, to be used from complex pattern matchers like selectAddrModeIndexed().</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryFoldIntegerCompare() {#a6ab5d083edbf744189ba625c61caeedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64InstructionSelector::tryFoldIntegerCompare (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Predicate, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryOptBuildVecToSubregToReg() {#af4e889089620e7e580b69c98fa625a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::tryOptBuildVecToSubregToReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a G_BUILD_VECTOR instruction <span class="doxyComputerOutput">MI</span> can be selected as a SUBREG_TO_REG.</p></dd>
</dl>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryOptConstantBuildVec() {#a4bd77dbcba67e2237f2b70274dc3e3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::tryOptConstantBuildVec (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> DstTy, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryOptSelect() {#a2017a0d5297b89ee04d69dd2f1ff446b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::tryOptSelect (<a href="/web-llvm/docs/api/classes/llvm/gselect">GSelect</a> &amp; Sel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### tryOptSelectConjunction() {#a03b1d0d5f28cce4f477e64ebffececb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64InstructionSelector::tryOptSelectConjunction (<a href="/web-llvm/docs/api/classes/llvm/gselect">GSelect</a> &amp; Sel, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CondMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MFReturnAddr {#a04a1d5c3a1d1922e31058c7ab38b340f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::MFReturnAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### MIB {#a146ab4742ca86061b2e57d63d3d4e4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::MIB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### ProduceNonFlagSettingCondBr {#aabe4495aade98de335d1a4a45ad1465a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::ProduceNonFlagSettingCondBr = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### RBI {#a70bcf66f03eecfa6591c77e4c976524f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64RegisterBankInfo&amp; anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::RBI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### STI {#ae21fdecd11628c1d9cb0da1e9fe6840f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget&amp; anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### TII {#a890b1e0bb5ec6da30048e40dc38f7427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64InstrInfo&amp; anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### TM {#a61ecd1d9e0d57e5b89ad6ebdbe6b9d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64TargetMachine&amp; anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

### TRI {#a345cc6e6dccf33bf37e5623966a220c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64RegisterInfo&amp; anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getName() {#acfd9e1db771e6baae1043da8baed60df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::getName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp">AArch64InstructionSelector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
