---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/registerbank
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegisterBank` Class

<p>This class implements the register bank concept. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegisterBank { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">llvm/CodeGen/RegisterBank.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059db666088120960b8f1b235135eb40">RegisterBank</a> (unsigned ID, const char *Name, const uint32_t *CoveredClasses, unsigned NumRegClasses)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72eda1e3512e954a5975578d16079d9">operator==</a> (const RegisterBank &amp;OtherRB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <span class="doxyComputerOutput">OtherRB</span> is the same as this. <a href="#ad72eda1e3512e954a5975578d16079d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf7527a1c6436aa5b35081da3b26490">operator!=</a> (const RegisterBank &amp;OtherRB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea60948498472cef86d66586ded919e">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the identifier of this register bank. <a href="#abea60948498472cef86d66586ded919e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaff74ccaefe7ac1cf0c4c7eb88c85d28">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a user friendly name of this register bank. <a href="#aaff74ccaefe7ac1cf0c4c7eb88c85d28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b158112720b57e5aa9898944c69330">verify</a> (const RegisterBankInfo &amp;RBI, const TargetRegisterInfo &amp;TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this register bank is valid. <a href="#a29b158112720b57e5aa9898944c69330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0393eeb48bb9235b4fc40b19ebb52f1">covers</a> (const TargetRegisterClass &amp;RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this register bank covers <span class="doxyComputerOutput">RC</span>. <a href="#aa0393eeb48bb9235b4fc40b19ebb52f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9908e6684d648ead83a4bab5f1bf7c51">dump</a> (const TargetRegisterInfo *TRI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the register mask on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream. <a href="#a9908e6684d648ead83a4bab5f1bf7c51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f200a149ac3e8669bb616c3b1049ecf">print</a> (raw_ostream &amp;OS, bool IsForDebug=false, const TargetRegisterInfo *TRI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the register mask on OS. <a href="#a2f200a149ac3e8669bb616c3b1049ecf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949f4fbe52cdeccecbb7c231fb021abe">ID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d9635b91d02d5faf9ab5b244c9d7e70">NumRegClasses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94278cae6f0cc561b70e07db8ceaa373">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a62542e5b33db7687d1630b4656c8f">CoveredClasses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a188b2501273ec13e62f58619f33c7ec1">RegisterBankInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only the <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> can initialize <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> properly. <a href="#a188b2501273ec13e62f58619f33c7ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class implements the register bank concept.</p>


<p>Two instances of <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> must have different ID. This property is enforced by the <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> class.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterBank() {#a059db666088120960b8f1b235135eb40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterBank::RegisterBank (unsigned ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * CoveredClasses, unsigned NumRegClasses)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>


<p>Referenced by <a href="#acbf7527a1c6436aa5b35081da3b26490">operator!=</a> and <a href="#ad72eda1e3512e954a5975578d16079d9">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#acbf7527a1c6436aa5b35081da3b26490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegisterBank::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; OtherRB)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>


<p>References <a href="#ad72eda1e3512e954a5975578d16079d9">operator==</a> and <a href="#a059db666088120960b8f1b235135eb40">RegisterBank</a>.</p>

</div>
</div>

### operator==() {#ad72eda1e3512e954a5975578d16079d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterBank::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; OtherRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <span class="doxyComputerOutput">OtherRB</span> is the same as this.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbank-cpp">RegisterBank.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abea60948498472cef86d66586ded919e">getID</a> and <a href="#a059db666088120960b8f1b235135eb40">RegisterBank</a>.</p>


<p>Referenced by <a href="#acbf7527a1c6436aa5b35081da3b26490">operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### covers() {#aa0393eeb48bb9235b4fc40b19ebb52f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterBank::covers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this register bank covers <span class="doxyComputerOutput">RC</span>.</p>


<p>In other words, check if this register bank fully covers the registers that <span class="doxyComputerOutput">RC</span> contains.</p>


<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbank-cpp">RegisterBank.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a8c46e5a35a9df5b131a85976d8d70af0">llvm::AArch64RegisterBankInfo::AArch64RegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#aa2bbc28e24343e76c9a993bed3190ba2">llvm::ARMRegisterBankInfo::ARMRegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a1cfd8b1df608cb89b0acb94d29d447b3">llvm::RegisterBankInfo::constrainGenericRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a96b1c6181f78fcdb7aba634c687d20a7">llvm::RegisterBankInfo::getRegBankFromConstraints</a>, <a href="#a2f200a149ac3e8669bb616c3b1049ecf">print</a>, <a href="#a29b158112720b57e5aa9898944c69330">verify</a> and <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#a09e6becd5a0cf0c041d79f2b42ccb12a">llvm::X86RegisterBankInfo::X86RegisterBankInfo</a>.</p>

</div>
</div>

### dump() {#a9908e6684d648ead83a4bab5f1bf7c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegisterBank::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the register mask on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream.</p>


<p>The dump is verbose.</p>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbank-cpp">RegisterBank.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#a2f200a149ac3e8669bb616c3b1049ecf">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getID() {#abea60948498472cef86d66586ded919e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBank::getID ()</td>
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

<p>Get the identifier of this register bank.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a8c46e5a35a9df5b131a85976d8d70af0">llvm::AArch64RegisterBankInfo::AArch64RegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#aa2bbc28e24343e76c9a993bed3190ba2">llvm::ARMRegisterBankInfo::ARMRegisterBankInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae9dd1e8c6c91a85d71bf41a59985d586">llvm::ARM::checkPartMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a1d33fd387b81b22c1074a78d30192fea">llvm::AMDGPURegisterBankInfo::collectWaterfallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#a7d4da10beff712762d6e9ebbf51b339a">getAnySgprS1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af872da5b171c5a24305ffa536fda2be0">getInsertVecEltOpInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8e8f884db0a3faadefc981023902a1ec">llvm::SIInstrInfo::getInstructionUniformity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a78df0524a69edda72e6325cfefdcb2c1">getMinClassForRegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a496c2822a80bc1f575e662e247f61d77">getMinSizeForRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5bc45f557d3d69066e2c03a39ca51793">llvm::AMDGPURegisterBankInfo::getRegBankID</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a615681753cb320f792b5656571637921">llvm::SIRegisterInfo::getRegClassForSizeOnBank</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a941f1e23c69340ff634ea8bbb015e6d0">llvm::AMDGPURegisterBankInfo::getValueMappingForPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp/#a03caf73bb4e31c215f1b34fa8e5ca364">hashPartialMapping</a>, <a href="/web-llvm/docs/api/classes/amdgpuregbanklegalizecombiner/#a3c10b311bd64612a48062c43193f566a">AMDGPURegBankLegalizeCombiner::isLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a58e94bcde312518e2a3f65be4c2b9a84">isLaneMaskFromSameBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a8c6b6408d508158782ddfaf264a20641">isVectorRegisterBank</a>, <a href="#ad72eda1e3512e954a5975578d16079d9">operator==</a>, <a href="#a2f200a149ac3e8669bb616c3b1049ecf">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a0d70a38e8f0622515630e7e8672df270">selectMergeValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a838cd050490773e0349589c0d78618fc">selectUnmergeValues</a>, <a href="#a29b158112720b57e5aa9898944c69330">verify</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aca0f86b578b560c1ea67d71987c1df57">llvm::RegisterBankInfo::verify</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#a09e6becd5a0cf0c041d79f2b42ccb12a">llvm::X86RegisterBankInfo::X86RegisterBankInfo</a>.</p>

</div>
</div>

### getName() {#aaff74ccaefe7ac1cf0c4c7eb88c85d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::RegisterBank::getName ()</td>
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

<p>Get a user friendly name of this register bank.</p>


<p>Should be used only for debugging purposes.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>


<p>Referenced by <a href="#a2f200a149ac3e8669bb616c3b1049ecf">print</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### print() {#a2f200a149ac3e8669bb616c3b1049ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterBank::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsForDebug=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the register mask on OS.</p>


<p>If IsForDebug is false, then only the name of the register bank is printed. Otherwise, all the fields are printing. TRI is then used to print the name of the register classes that this register bank covers.</p>


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbank-cpp">RegisterBank.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#aa0393eeb48bb9235b4fc40b19ebb52f1">covers</a>, <a href="#abea60948498472cef86d66586ded919e">getID</a>, <a href="#aaff74ccaefe7ac1cf0c4c7eb88c85d28">getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a9908e6684d648ead83a4bab5f1bf7c51">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d61059db828cc74c97149c125638561">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### verify() {#a29b158112720b57e5aa9898944c69330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterBank::verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &amp; RBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this register bank is valid.</p>


<p>In other words, if it has been properly constructed.</p>



:::info
<p>This method does not check anything when assertions are disabled.</p>
:::


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True is the check was successful.</p></dd>
</dl>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbank-cpp">RegisterBank.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa0393eeb48bb9235b4fc40b19ebb52f1">covers</a>, <a href="#abea60948498472cef86d66586ded919e">getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a86c7cb8b065aaa7ceace9c9218ace573">llvm::RegisterBankInfo::getMaximumSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a8ea8ce186fc4a70ad542e74d015d84ed">llvm::TargetRegisterClass::hasSubClassEq</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aca0f86b578b560c1ea67d71987c1df57">llvm::RegisterBankInfo::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CoveredClasses {#af4a62542e5b33db7687d1630b4656c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t* llvm::RegisterBank::CoveredClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>

</div>
</div>

### ID {#a949f4fbe52cdeccecbb7c231fb021abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBank::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>

</div>
</div>

### Name {#a94278cae6f0cc561b70e07db8ceaa373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::RegisterBank::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>

</div>
</div>

### NumRegClasses {#a7d9635b91d02d5faf9ab5b244c9d7e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBank::NumRegClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>

</div>
</div>

### RegisterBankInfo {#a188b2501273ec13e62f58619f33c7ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::RegisterBank::RegisterBankInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only the <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> can initialize <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> properly.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbank-h">RegisterBank.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbank-cpp">RegisterBank.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
