---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsregisterbankinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsRegisterBankInfo` Class

<p>This class provides the information for the target register banks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MipsRegisterBankInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">Target/Mips/MipsRegisterBankInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipsgenregisterbankinfo">MipsGenRegisterBankInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstType { <a href="#afe4c259d338c3ce26c594fcb59f892d1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some instructions are used with both floating point and integer operands. <a href="#afe4c259d338c3ce26c594fcb59f892d1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a273294b63d70a86b69742c1f4256e098">MipsRegisterBankInfo</a> (const TargetRegisterInfo &amp;TRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7394a9cae0a48251b9ccaca67393ef89">getInstrMapping</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the mapping of the different operands of <span class="doxyComputerOutput">MI</span> on the register bank. <a href="#a7394a9cae0a48251b9ccaca67393ef89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e12ed6a5b2d3f3dd790e2c48f7d7906">applyMappingImpl</a> (MachineIRBuilder &amp;Builder, const OperandsMapper &amp;OpdMapper) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Here we have to narrowScalar s64 operands to s32, combine away G_MERGE or G_UNMERGE and erase instructions that became dead in the process. <a href="#a1e12ed6a5b2d3f3dd790e2c48f7d7906">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a381f41669927321758998407f3fe0994">setRegBank</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> determined that s64 operand is better to be split into two s32 operands in gprb. <a href="#a381f41669927321758998407f3fe0994">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ce6ee62ad3bdea7d11090ed44b152e">isAmbiguous_64</a> (InstType InstTy, unsigned OpSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb330d086a22cc09631175e4bc1bc40a">isAmbiguous_32</a> (InstType InstTy, unsigned OpSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c112e015c83ddbdc6701f4a838d65f">isAmbiguous_32or64</a> (InstType InstTy, unsigned OpSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df0ad61e78d4a844eefb19ec26ef791">isAmbiguousWithMergeOrUnmerge_64</a> (InstType InstTy, unsigned OpSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae95be4c38f3628d7f7b9272cb00b4448">isFloatingPoint_32or64</a> (InstType InstTy, unsigned OpSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc8ba74e796b08ddd1f7f32c6814a7b">isFloatingPoint_64</a> (InstType InstTy, unsigned OpSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4016fc717db22e999b0654bd9b16b1a">isInteger_32</a> (InstType InstTy, unsigned OpSize) const</td>
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

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### InstType {#afe4c259d338c3ce26c594fcb59f892d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsRegisterBankInfo::InstType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some instructions are used with both floating point and integer operands.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotDetermined<a id="afe4c259d338c3ce26c594fcb59f892d1a6ce942399586e7b8353c3342314af4c3"></a></td>
<td class="doxyEnumItemDescription">Temporary type, when visit(..., nullptr) finishes will convert to one of the remaining types: Integer, FloatingPoint or Ambiguous</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Integer<a id="afe4c259d338c3ce26c594fcb59f892d1a88150d4064e8e9d47b031614ca660814"></a></td>
<td class="doxyEnumItemDescription">Connected with instruction that interprets 'bags of bits' as integers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FloatingPoint<a id="afe4c259d338c3ce26c594fcb59f892d1a35ff84adff2c7040ca1745867857f1b2"></a></td>
<td class="doxyEnumItemDescription">Connected with instruction that interprets 'bags of bits' as floating point numbers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ambiguous<a id="afe4c259d338c3ce26c594fcb59f892d1abef962e7691caa991a0c5c542da4b1d5"></a></td>
<td class="doxyEnumItemDescription">Represents moving 'bags of bits' around</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AmbiguousWithMergeOrUnmerge<a id="afe4c259d338c3ce26c594fcb59f892d1a4fcc26d63de1b849edb496d4e5f4ef33"></a></td>
<td class="doxyEnumItemDescription">Only used for s64</td>
</tr>

</table>
</dd>
</dl>


<p>We assign InstType to such instructions as it helps us to avoid cross bank copies. InstType deppends on context.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MipsRegisterBankInfo() {#a273294b63d70a86b69742c1f4256e098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsRegisterBankInfo::MipsRegisterBankInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp">MipsRegisterBankInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyMappingImpl() {#a1e12ed6a5b2d3f3dd790e2c48f7d7906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsRegisterBankInfo::applyMappingImpl (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
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

<p>Here we have to narrowScalar s64 operands to s32, combine away G_MERGE or G_UNMERGE and erase instructions that became dead in the process.</p>


<p>We manually assign bank to def operand of all new instructions that were created in the process since they will not end up in <a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> loop.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp">MipsRegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp/#aa3f4b8913b938fe26940a3ee727e4244">combineAwayG_UNMERGE_VALUES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/giselworklist/#aac654c5789d6fda12f159e82f65abc26">llvm::GISelWorkList&lt; N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#abc4d15552b6f7e8b121a84146a69aa59">llvm::TargetSubtargetInfo::getLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a397c999d8b2ead3f13eba866dfc3295e">llvm::RegisterBankInfo::OperandsMapper::getMI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a841196bdb378891dcedb1c23a02a30d2">llvm::RegisterBankInfo::OperandsMapper::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/giselworklist/#a34c480754e4a8cbc2469974e79a08924">llvm::GISelWorkList&lt; N &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab24db762f0912a99f1e4d9e44eaeaa44">llvm::MachineIRBuilder::setInstrAndDebugLoc</a> and <a href="#a381f41669927321758998407f3fe0994">setRegBank</a>.</p>

</div>
</div>

### getInstrMapping() {#a7394a9cae0a48251b9ccaca67393ef89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; MipsRegisterBankInfo::getInstrMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp">MipsRegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp/#a76bb7e313bac1bca54c0442c2a9391ab">CustomMappingID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#abe7d332de484fcc6cdc4c2a5e7bdd31b">llvm::RegisterBankInfo::DefaultMappingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a79d5a347aa1209fc7bcbd315581c161ea865025afb891a0646cfdf8b492f11598">llvm::Mips::DPRIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp/#a8729cb6dd5338d9cfcdd47408bd3a0e8">getFprbMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp/#a0c212c19b61016faa646a4977ae19570">getGprbOrCustomMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a640c554d91abd68270b79cdef71b99a2">llvm::RegisterBankInfo::getInvalidInstructionMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp/#a266eeca30be14882336c5b3df06bd770">getMSAMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a79d5a347aa1209fc7bcbd315581c161ea679ade74210cf2d0e800c7d583d34d06">llvm::Mips::GPRIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#af484a43d5e4fa2ff1f1790d06f2ca94d">llvm::RegisterBankInfo::InstructionMapping::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a79d5a347aa1209fc7bcbd315581c161ead2950878794c8a53663dd44476e82623">llvm::Mips::SPRIdx</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a5d31dff27d1530d68a4e0c934a199614">llvm::Mips::ValueMappings</a>.</p>

</div>
</div>

### setRegBank() {#a381f41669927321758998407f3fe0994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsRegisterBankInfo::setRegBank (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> determined that s64 operand is better to be split into two s32 operands in gprb.</p>


<p>Here we manually set register banks of def operands of newly created instructions since they will not get regbankselected.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp">MipsRegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#a1e12ed6a5b2d3f3dd790e2c48f7d7906">applyMappingImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isAmbiguous\_32() {#aeb330d086a22cc09631175e4bc1bc40a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsRegisterBankInfo::isAmbiguous_32 (InstType InstTy, unsigned OpSize)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

### isAmbiguous\_32or64() {#a77c112e015c83ddbdc6701f4a838d65f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsRegisterBankInfo::isAmbiguous_32or64 (InstType InstTy, unsigned OpSize)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

### isAmbiguous\_64() {#a48ce6ee62ad3bdea7d11090ed44b152e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsRegisterBankInfo::isAmbiguous_64 (InstType InstTy, unsigned OpSize)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

### isAmbiguousWithMergeOrUnmerge\_64() {#a1df0ad61e78d4a844eefb19ec26ef791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsRegisterBankInfo::isAmbiguousWithMergeOrUnmerge_64 (InstType InstTy, unsigned OpSize)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

### isFloatingPoint\_32or64() {#ae95be4c38f3628d7f7b9272cb00b4448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsRegisterBankInfo::isFloatingPoint_32or64 (InstType InstTy, unsigned OpSize)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

### isFloatingPoint\_64() {#a0fc8ba74e796b08ddd1f7f32c6814a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsRegisterBankInfo::isFloatingPoint_64 (InstType InstTy, unsigned OpSize)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

### isInteger\_32() {#af4016fc717db22e999b0654bd9b16b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsRegisterBankInfo::isInteger_32 (InstType InstTy, unsigned OpSize)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp">MipsRegisterBankInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-h">MipsRegisterBankInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
