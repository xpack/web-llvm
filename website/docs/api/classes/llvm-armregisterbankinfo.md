---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armregisterbankinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMRegisterBankInfo` Class

<p>This class provides the information for the target register banks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARMRegisterBankInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-h">Target/ARM/ARMRegisterBankInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armgenregisterbankinfo">ARMGenRegisterBankInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bbc28e24343e76c9a993bed3190ba2">ARMRegisterBankInfo</a> (const TargetRegisterInfo &amp;TRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59ec25334715d44d5eecd8568b29e36">getInstrMapping</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the mapping of the different operands of <span class="doxyComputerOutput">MI</span> on the register bank. <a href="#af59ec25334715d44d5eecd8568b29e36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class provides the information for the target register banks.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-h">ARMRegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMRegisterBankInfo() {#aa2bbc28e24343e76c9a993bed3190ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMRegisterBankInfo::ARMRegisterBankInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-h">ARMRegisterBankInfo.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-cpp">ARMRegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a5f52adc63779186445abc2276acf8d92">llvm::ARM::checkPartialMappings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa2cd6a82625e3df20e052349b0a35fbd">llvm::ARM::checkValueMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#aa0393eeb48bb9235b4fc40b19ebb52f1">llvm::RegisterBank::covers</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a86c7cb8b065aaa7ceace9c9218ace573">llvm::RegisterBankInfo::getMaximumSize</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInstrMapping() {#af59ec25334715d44d5eecd8568b29e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; ARMRegisterBankInfo::getInstrMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-h">ARMRegisterBankInfo.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-cpp">ARMRegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#abe7d332de484fcc6cdc4c2a5e7bdd31b">llvm::RegisterBankInfo::DefaultMappingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a6143fb16c52690926880e9335db7d85aaee127c687344d51cc6f022a7f1e943c5">llvm::ARM::DPR3OpsIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a640c554d91abd68270b79cdef71b99a2">llvm::RegisterBankInfo::getInvalidInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a6143fb16c52690926880e9335db7d85aaac00f8778fd59039ff8ae5bbf5caf2bc">llvm::ARM::GPR3OpsIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a6a8b4e2c26c2c0aad751c5bf296858c6">llvm::ARMSubtarget::hasVFP2Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cdb63ce3baf9ea9a1f86aed27f40fe8">llvm::isPreISelGenericOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#af484a43d5e4fa2ff1f1790d06f2ca94d">llvm::RegisterBankInfo::InstructionMapping::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a6143fb16c52690926880e9335db7d85aa1727dbe93008565d0ebf771196b6172e">llvm::ARM::SPR3OpsIdx</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ab182e7140b8a5a70ce004af063708bff">llvm::ARM::ValueMappings</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-cpp">ARMRegisterBankInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-h">ARMRegisterBankInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
