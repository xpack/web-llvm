---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86instructionselector-cpp-/x86instructionselector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86InstructionSelector` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{X86InstructionSelector.cpp}::X86InstructionSelector { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf881f6a3d3ccbdf8f8069e7824fff9">X86InstructionSelector</a> (const X86TargetMachine &amp;TM, const X86Subtarget &amp;STI, const X86RegisterBankInfo &amp;RBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9fb38133cb5844e49ed1ad78588b2a">select</a> (MachineInstr &amp;I) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select the (possibly generic) instruction <span class="doxyComputerOutput">I</span> to only use target-specific opcodes. <a href="#a2f9fb38133cb5844e49ed1ad78588b2a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33312ecf73d0897b490b2c91b07e30b">selectImpl</a> (MachineInstr &amp;I, CodeGenCoverage &amp;CoverageInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tblgen-erated 'select' implementation, used as the initial selector for the patterns that don't require complex C++. <a href="#ae33312ecf73d0897b490b2c91b07e30b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc030da4503ea63a5e3e0979210b865">getLoadStoreOp</a> (const LLT &amp;Ty, const RegisterBank &amp;RB, unsigned Opc, Align Alignment) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9c37d9173b0ed72e786bcb6afd1731">selectLoadStoreOp</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a29559aae1140a939d7f31ec28925f1">selectFrameIndexOrGep</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340c12c5230b275559c08d559acf04a3">selectGlobalValue</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15dd6749040fff23c574982d4e22ba77">selectConstant</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50dd5151c221fe3f0d3b54ec4ae1d5c7">selectTruncOrPtrToInt</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad15d9317aa19d5d1591f6dc64d4c1c6">selectZext</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b2dcfff8a80aea0fa7aa5c9b3a375e">selectAnyext</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac637d41acea24497e8d6fdee5dc8a393">selectCmp</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8d5907c5df698350e48808a9885b59">selectFCmp</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e028cef308cc37f35da60534f78ccd">selectUAddSub</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3db160179b19bbdf2f219de726ddd3f">selectDebugInstr</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9ab1c98c8b2159669b2e232fef486f">selectCopy</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3564a584347e09529e9c25cf4fd16a40">selectUnmergeValues</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0858d99f5dc0b8cb926ade96de8ecc6d">selectMergeValues</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc187eefaeeb39a12bd5c0f175efa6ca">selectInsert</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ee6ddf47783ce92cee1fbd28d78930">selectExtract</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c4b6d326aad556f746c5bc3ab77f60">selectCondBranch</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3196a361821d43a1329096cae9986e6a">selectTurnIntoCOPY</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, const unsigned DstReg, const TargetRegisterClass *DstRC, const unsigned SrcReg, const TargetRegisterClass *SrcRC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030e1a998e03293e6059b3e45035a3f0">materializeFP</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fd097e65c1167fd5f8e60f1edd8abc4">selectImplicitDefOrPHI</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada1426ddb30eeabba1d71361ca45b6c">selectMulDivRem</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac89f9c17484cb5ddc1e54b88b3b9984d">selectSelect</a> (MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a917d947451d60458c8e83b49e43651">emitInsertSubreg</a> (unsigned DstReg, unsigned SrcReg, MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe76699b9f58f677bdd33370b56d46e">emitExtractSubreg</a> (unsigned DstReg, unsigned SrcReg, MachineInstr &amp;I, MachineRegisterInfo &amp;MRI, MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7260ab369f5d264a275f84d32f131fc8">getRegClass</a> (LLT Ty, const RegisterBank &amp;RB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822883b327968cc6139af929e6649dc0">getRegClass</a> (LLT Ty, unsigned Reg, MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5ec89ac0063fac12af044e237d1012">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a8c00cc4885a497b81b45596fc15c1">STI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab486ee47937a7e429bc07369896899f0">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo">X86RegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4fbf609582909b92d19afed5026b828">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo">X86RegisterBankInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c7c3cca08ea9a613cb6b45aa792dd9">RBI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf9518c36be4d0001fbf3dca6cb4e90">getName</a> ()</td>
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


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86InstructionSelector() {#a1bf881f6a3d3ccbdf8f8069e7824fff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86InstructionSelector::X86InstructionSelector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo">X86RegisterBankInfo</a> &amp; RBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a1ab538c256c3204b950075744d5b2b16">GET_GLOBALISEL_PREDICATES_INIT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a1cd36a579f079f7f4506d9d097b2f0a8">GET_GLOBALISEL_TEMPORARIES_INIT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### select() {#a2f9fb38133cb5844e49ed1ad78588b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::select (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#ae5900cfb710c3c8b5f5d2a5b0cadabf9">llvm::GIMatchTableExecutor::CoverageInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cdb63ce3baf9ea9a1f86aed27f40fe8">llvm::isPreISelGenericOpcode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a52fb4682a4be0321cf8eec99c1f76f93">llvm::GIMatchTableExecutor::MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitExtractSubreg() {#a6fe76699b9f58f677bdd33370b56d46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::emitExtractSubreg (unsigned DstReg, unsigned SrcReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### emitInsertSubreg() {#a5a917d947451d60458c8e83b49e43651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::emitInsertSubreg (unsigned DstReg, unsigned SrcReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### getLoadStoreOp() {#a6bc030da4503ea63a5e3e0979210b865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86InstructionSelector::getLoadStoreOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &amp; Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; RB, unsigned Opc, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### getRegClass() {#a7260ab369f5d264a275f84d32f131fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::getRegClass (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; RB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### getRegClass() {#a822883b327968cc6139af929e6649dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::getRegClass (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, unsigned Reg, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### materializeFP() {#a030e1a998e03293e6059b3e45035a3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::materializeFP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectAnyext() {#a22b2dcfff8a80aea0fa7aa5c9b3a375e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectAnyext (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectCmp() {#ac637d41acea24497e8d6fdee5dc8a393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectCmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectCondBranch() {#a99c4b6d326aad556f746c5bc3ab77f60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectCondBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectConstant() {#a15dd6749040fff23c574982d4e22ba77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectCopy() {#aaa9ab1c98c8b2159669b2e232fef486f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectDebugInstr() {#ac3db160179b19bbdf2f219de726ddd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectDebugInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectExtract() {#af9ee6ddf47783ce92cee1fbd28d78930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectFCmp() {#abb8d5907c5df698350e48808a9885b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectFCmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectFrameIndexOrGep() {#a2a29559aae1140a939d7f31ec28925f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectFrameIndexOrGep (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectGlobalValue() {#a340c12c5230b275559c08d559acf04a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectGlobalValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectImpl() {#ae33312ecf73d0897b490b2c91b07e30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::selectImpl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage">CodeGenCoverage</a> &amp; CoverageInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tblgen-erated 'select' implementation, used as the initial selector for the patterns that don't require complex C++.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectImplicitDefOrPHI() {#a8fd097e65c1167fd5f8e60f1edd8abc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectImplicitDefOrPHI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectInsert() {#acc187eefaeeb39a12bd5c0f175efa6ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectInsert (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectLoadStoreOp() {#a9c9c37d9173b0ed72e786bcb6afd1731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectLoadStoreOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectMergeValues() {#a0858d99f5dc0b8cb926ade96de8ecc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectMergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectMulDivRem() {#aada1426ddb30eeabba1d71361ca45b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectMulDivRem (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectSelect() {#ac89f9c17484cb5ddc1e54b88b3b9984d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectTruncOrPtrToInt() {#a50dd5151c221fe3f0d3b54ec4ae1d5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectTruncOrPtrToInt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectTurnIntoCOPY() {#a3196a361821d43a1329096cae9986e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectTurnIntoCOPY (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned DstReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned SrcReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectUAddSub() {#a68e028cef308cc37f35da60534f78ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectUAddSub (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectUnmergeValues() {#a3564a584347e09529e9c25cf4fd16a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectUnmergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### selectZext() {#aad15d9317aa19d5d1591f6dc64d4c1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InstructionSelector::selectZext (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RBI {#ae0c7c3cca08ea9a613cb6b45aa792dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86RegisterBankInfo&amp; anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::RBI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### STI {#a78a8c00cc4885a497b81b45596fc15c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget&amp; anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### TII {#ab486ee47937a7e429bc07369896899f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrInfo&amp; anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### TM {#a5f5ec89ac0063fac12af044e237d1012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86TargetMachine&amp; anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

### TRI {#af4fbf609582909b92d19afed5026b828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86RegisterInfo&amp; anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getName() {#acaf9518c36be4d0001fbf3dca6cb4e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::getName ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp">X86InstructionSelector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
