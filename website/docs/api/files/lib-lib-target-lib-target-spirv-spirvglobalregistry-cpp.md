---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SPIRVGlobalRegistry.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirv-h">SPIRV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvbuiltins-h">SPIRVBuiltins.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-h">SPIRVSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-h">SPIRVTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvutils-h">SPIRVUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;cassert&gt;
#include &lt;functional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bdf39332eb22f67b968fd688417964">typeToAddressSpace</a> (const Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a> (MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a15e60c215ba084b8efc539a6ef376">createTypeVReg</a> (MachineIRBuilder &amp;MIRBuilder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cdd09538b5a878eff565f40b9c5776a">GetSpirvImageTypeName</a> (const SPIRVType *Type, MachineIRBuilder &amp;MIRBuilder, const std::string &amp;Prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a> (const SPIRVType *Type, MachineIRBuilder &amp;MIRBuilder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b49090437c0021f09fa86c3965bb855">getAS</a> (SPIRVType *SpvType)</td>
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


<div class="doxySectionDef">

## Functions

### buildSpirvTypeName() {#a665946cb74a98ed20ca7e0acf68d9b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string buildSpirvTypeName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a29e05cd075864928ae65e1751fdc346e">llvm::MachineOperand::getCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a4cdd09538b5a878eff565f40b9c5776a">GetSpirvImageTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0d65d879a707f0fcaa221e60be3a1a54">llvm::SPIRVGlobalRegistry::getOrCreateGlobalVariableWithBinding</a> and <a href="#a4cdd09538b5a878eff565f40b9c5776a">GetSpirvImageTypeName</a>.</p>

</div>
</div>

### createTypeVReg() {#a22e9703f8897754ae0ff79ce70b211eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register createTypeVReg (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#ac2a15e60c215ba084b8efc539a6ef376">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a69f73e1b5f8a3e376c63293408b6786e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abeddeff35f8dd231213915a6f77f0920">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeDeviceEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4cd2c03c778450920cd3b53acdcb4fba">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0067190a151de0ad367e8d1e56c1016a">llvm::SPIRVGlobalRegistry::getOrCreateOpTypePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea914eb511a3b8ebf605c62c07e8ab44">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ae5869468359515f460a588357f1737cf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVArrayType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8bdd4c60453b10074293349820f8bdcf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f224f7bdbbd3667e44b205c571b30d2">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVType</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4791c0c5f18aaa298445226456f15547">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>.</p>

</div>
</div>

### createTypeVReg() {#ac2a15e60c215ba084b8efc539a6ef376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register createTypeVReg (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>.</p>

</div>
</div>

### getAS() {#a4b49090437c0021f09fa86c3965bb855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAS (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType)</td>
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



<p>Definition at line 1674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f3d8bc8938733ce077d2fe798d3a49a">llvm::storageClassToAddressSpace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>.</p>

</div>
</div>

### GetSpirvImageTypeName() {#a4cdd09538b5a878eff565f40b9c5776a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string GetSpirvImageTypeName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; Prefix)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af988c2b4f62506108843a0fdc04b43a2">llvm::MachineRegisterInfo::getUniqueVRegDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>.</p>

</div>
</div>

### typeToAddressSpace() {#af3bdf39332eb22f67b968fd688417964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned typeToAddressSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15fe5c2fae3f394855b6290a19a88f59">llvm::isTypedPointerWrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
