---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvregisterbankinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RISCVRegisterBankInfo` Class

<p>This class provides the information for the target register banks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RISCVRegisterBankInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">Target/RISCV/GISel/RISCVRegisterBankInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvgenregisterbankinfo">RISCVGenRegisterBankInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119aef9cb05281332fc7aa41ac3c4912">RISCVRegisterBankInfo</a> (unsigned HwMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a34245bb11e89a64a45063a8fc9e201">getInstrMapping</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the mapping of the different operands of <span class="doxyComputerOutput">MI</span> on the register bank. <a href="#a9a34245bb11e89a64a45063a8fc9e201">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc103c1694a8d8755660b056deeaaf28">hasFPConstraints</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447327ec6547bc9656f3174f5dbd8f68">onlyUsesFP</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0363556a519147bae9b987fb05a00928">anyUseOnlyUseFP</a> (Register Def, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae22d8fb04fe77397b8dff7cb2dfa3d2b">onlyDefinesFP</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI) const</td>
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

## Description {#details}

<p>This class provides the information for the target register banks.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVRegisterBankInfo() {#a119aef9cb05281332fc7aa41ac3c4912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVRegisterBankInfo::RISCVRegisterBankInfo (unsigned HwMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp">RISCVRegisterBankInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac0ce287dd4d4cd434f52b7c6f0bc4c5d">llvm::RegisterBankInfo::HwMode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInstrMapping() {#a9a34245bb11e89a64a45063a8fc9e201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; RISCVRegisterBankInfo::getInstrMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Get the mapping of the different operands of <span class="doxyComputerOutput">MI</span> on the register bank.</p>


<p>This mapping should be the direct translation of <span class="doxyComputerOutput">MI</span>. In other words, when <span class="doxyComputerOutput">MI</span> is mapped with the returned mapping, only the register banks of the operands of <span class="doxyComputerOutput">MI</span> need to be updated. In particular, neither the opcode nor the type of <span class="doxyComputerOutput">MI</span> needs to be updated for this direct mapping.</p>


<p>The target independent implementation gives a mapping based on the register classes for the target specific opcode. It uses the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#abe7d332de484fcc6cdc4c2a5e7bdd31b">RegisterBankInfo::DefaultMappingID</a> for that mapping. Make sure you do not use that <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the alternative mapping for MI. See getInstrAlternativeMappings for the alternative mappings.</p>


<p>For instance, if <span class="doxyComputerOutput">MI</span> is a vector add, the mapping should not be a scalarization of the add.</p>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p>returnedVal.verify(MI).</p></dd>
</dl>



:::info
<p>If returnedVal does not verify MI, this would probably mean that the target does not support that instruction.</p>
:::


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp">RISCVRegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#abe7d332de484fcc6cdc4c2a5e7bdd31b">llvm::RegisterBankInfo::DefaultMappingID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp/#a0616c08fb0bc4d99ac81773126e6e0b2">getFPValueMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a86c7cb8b065aaa7ceace9c9218ace573">llvm::RegisterBankInfo::getMaximumSize</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp/#a1f4b1a45ebbdb4ff925bbd023144ed88">getVRBValueMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#aa1445af56e4c6733b147e7be06176b84a5fa979feb41c7c349a347fec8355dcdc">llvm::RISCV::GPRB32Idx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#aa1445af56e4c6733b147e7be06176b84a3d6aa96b2bed6a8597bb4a847bef17d2">llvm::RISCV::GPRB64Idx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac96e94b58836a8c283b78c423b96f5bc">llvm::isPreISelGenericFloatingPointOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cdb63ce3baf9ea9a1f86aed27f40fe8">llvm::isPreISelGenericOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#af484a43d5e4fa2ff1f1790d06f2ca94d">llvm::RegisterBankInfo::InstructionMapping::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#aa8481c83f9995072aabb550d6120dbf9">llvm::RISCV::ValueMappings</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anyUseOnlyUseFP() {#a0363556a519147bae9b987fb05a00928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVRegisterBankInfo::anyUseOnlyUseFP (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any use of <span class="doxyComputerOutput">Def</span> only user FPRs.</p></dd>
</dl>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp">RISCVRegisterBankInfo.cpp</a>.</p>

</div>
</div>

### hasFPConstraints() {#adc103c1694a8d8755660b056deeaaf28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVRegisterBankInfo::hasFPConstraints (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> only uses and defines FPRs.</p></dd>
</dl>


<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp">RISCVRegisterBankInfo.cpp</a>.</p>

</div>
</div>

### onlyDefinesFP() {#ae22d8fb04fe77397b8dff7cb2dfa3d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVRegisterBankInfo::onlyDefinesFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> only defines FPRs.</p></dd>
</dl>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp">RISCVRegisterBankInfo.cpp</a>.</p>

</div>
</div>

### onlyUsesFP() {#a447327ec6547bc9656f3174f5dbd8f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVRegisterBankInfo::onlyUsesFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> only uses FPRs.</p></dd>
</dl>


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp">RISCVRegisterBankInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-cpp">RISCVRegisterBankInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvregisterbankinfo-h">RISCVRegisterBankInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
