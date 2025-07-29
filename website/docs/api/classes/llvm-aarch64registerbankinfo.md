---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64registerbankinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64RegisterBankInfo` Class

<p>This class provides the information for the target register banks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AArch64RegisterBankInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">Target/AArch64/GISel/AArch64RegisterBankInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo">AArch64GenRegisterBankInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c46e5a35a9df5b131a85976d8d70af0">AArch64RegisterBankInfo</a> (const TargetRegisterInfo &amp;TRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46356aea545c24e293171816eca04255">copyCost</a> (const RegisterBank &amp;A, const RegisterBank &amp;B, TypeSize Size) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the cost of a copy from <span class="doxyComputerOutput">B</span> to <span class="doxyComputerOutput">A</span>, or put differently, get the cost of A = COPY B. <a href="#a46356aea545c24e293171816eca04255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764ae29d6f969d21006942e066524217">getRegBankFromRegClass</a> (const TargetRegisterClass &amp;RC, LLT Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a register bank that covers <span class="doxyComputerOutput">RC</span>. <a href="#a764ae29d6f969d21006942e066524217">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">InstructionMappings</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4bf9736903f31820c978bdb1b6810f">getInstrAlternativeMappings</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alternative mappings for <span class="doxyComputerOutput">MI</span>. <a href="#a3f4bf9736903f31820c978bdb1b6810f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d2615f7c9c9159d1e883ba8dd8eab7">getInstrMapping</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the mapping of the different operands of <span class="doxyComputerOutput">MI</span> on the register bank. <a href="#ab3d2615f7c9c9159d1e883ba8dd8eab7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4cd7c504faff5c45f9dbd46f1107d7">applyMappingImpl</a> (MachineIRBuilder &amp;Builder, const OperandsMapper &amp;OpdMapper) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a0c85003f2e4060a7b61ebff7c2fb33cd">RegisterBankInfo::applyMapping</a>. <a href="#aaa4cd7c504faff5c45f9dbd46f1107d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64d705ae92f4f775fc640499be210f7">getSameKindOfOperandsMapping</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an instruction mapping where all the operands map to the same register bank and have similar size. <a href="#af64d705ae92f4f775fc640499be210f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a59651669400ea6a55cac08c9d3674a">isPHIWithFPContraints</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI, unsigned Depth=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b0e26f3341360c88b8a64e5abed0f36">hasFPConstraints</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI, unsigned Depth=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773e3e2ffea2d81a088c5102fdd015ae">onlyUsesFP</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI, unsigned Depth=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae029d15a73f61f7b4734b13d9a4ffee6">onlyDefinesFP</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI, unsigned Depth=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba402fa31442da62e7eb0cf482504c1">isLoadFromFPType</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae1fd3d1d23b8cf0d9d016da10e4517">MaxFPRSearchDepth</a> = 2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum recursion depth for hasFPConstraints. <a href="#a8ae1fd3d1d23b8cf0d9d016da10e4517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class provides the information for the target register banks.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64RegisterBankInfo() {#a8c46e5a35a9df5b131a85976d8d70af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64RegisterBankInfo::AArch64RegisterBankInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp/#a7ee08f92cb230b0868894e79f73d0826">CHECK_PARTIALMAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp/#a1082f58d2ba0dc63586bb64672ce70ed">CHECK_VALUEMAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp/#a34ab22f7d8d6c0e402b18475af142aa8">CHECK_VALUEMAP_3OPS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp/#a9eb5f0fd303482e35fa61ddecf7d8c91">CHECK_VALUEMAP_CROSSREGCPY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp/#ac078ca3a2ab72240bc9925d17c35d2f5">CHECK_VALUEMAP_FPEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a5815052cc039d0e029b6aebf81614419">llvm::AArch64GenRegisterBankInfo::checkPartialMappingIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#aa0393eeb48bb9235b4fc40b19ebb52f1">llvm::RegisterBank::covers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a587c39adeaa08f2c374d7bc55731513a">FPR</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a86c7cb8b065aaa7ceace9c9218ace573">llvm::RegisterBankInfo::getMaximumSize</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a5204b837734b0428ff3bc7d07c5620ad">llvm::AArch64GenRegisterBankInfo::PMI_FirstFPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a6f05aa805febfc871072ccfaeab73947">llvm::AArch64GenRegisterBankInfo::PMI_FirstGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a74b3fe0416b1909c5f09e250e80e4443">llvm::AArch64GenRegisterBankInfo::PMI_FPR128</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a7d0f4c1015d1380e8813dd5b6a07d5be">llvm::AArch64GenRegisterBankInfo::PMI_FPR16</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a9a036a733dc1c145a8f3607b799b87d8">llvm::AArch64GenRegisterBankInfo::PMI_FPR256</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a57ade2e8c7009c5b3daa35e6373c2dea">llvm::AArch64GenRegisterBankInfo::PMI_FPR32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9aebf52e13aa4d38c631d9e5376578b4b3">llvm::AArch64GenRegisterBankInfo::PMI_FPR512</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a0b8bca96f9b583cbfaf7448edc60ef89">llvm::AArch64GenRegisterBankInfo::PMI_FPR64</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a5046c1b33042e6e139dfe42d4c2a836d">llvm::AArch64GenRegisterBankInfo::PMI_GPR128</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a3affacb0ea6b477fc5b6a5331ae1a0dc">llvm::AArch64GenRegisterBankInfo::PMI_GPR32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a15443bb0e40040577432ba71db504125">llvm::AArch64GenRegisterBankInfo::PMI_GPR64</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9af741e39026b897179f21ab69f6fd83ea">llvm::AArch64GenRegisterBankInfo::PMI_LastFPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9abd8d169cb7433122c1b4bfbbbe835b9a">llvm::AArch64GenRegisterBankInfo::PMI_LastGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyCost() {#a46356aea545c24e293171816eca04255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64RegisterBankInfo::copyCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size)</td>
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

<p>Get the cost of a copy from <span class="doxyComputerOutput">B</span> to <span class="doxyComputerOutput">A</span>, or put differently, get the cost of A = COPY B.</p>


<p>Since register banks may cover different size, <span class="doxyComputerOutput">Size</span> specifies what will be the size in bits that will be copied around.</p>



:::info
<p>Since this is a copy, both registers have the same size.</p>
:::


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ace62a3b4e043e1740264ffd8a6b6cfb5">llvm::RegisterBankInfo::copyCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a3f4bf9736903f31820c978bdb1b6810f">getInstrAlternativeMappings</a> and <a href="#ab3d2615f7c9c9159d1e883ba8dd8eab7">getInstrMapping</a>.</p>

</div>
</div>

### getInstrAlternativeMappings() {#a3f4bf9736903f31820c978bdb1b6810f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterBankInfo::InstructionMappings AArch64RegisterBankInfo::getInstrAlternativeMappings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Get the alternative mappings for <span class="doxyComputerOutput">MI</span>.</p>


<p>Alternative in the sense different from getInstrMapping.</p>


<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a46356aea545c24e293171816eca04255">copyCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a52505890f7e825cd589db0e54395e9e5">llvm::AArch64GenRegisterBankInfo::getCopyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a104c33de0485a9518a9cae99b7023c84">llvm::RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#ace6c7f8d7dc748c8c3e5e4d3e230c71c">llvm::AArch64GenRegisterBankInfo::getValueMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a5204b837734b0428ff3bc7d07c5620ad">llvm::AArch64GenRegisterBankInfo::PMI_FirstFPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a6f05aa805febfc871072ccfaeab73947">llvm::AArch64GenRegisterBankInfo::PMI_FirstGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getInstrMapping() {#ab3d2615f7c9c9159d1e883ba8dd8eab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AArch64RegisterBankInfo::getInstrMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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


<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a46356aea545c24e293171816eca04255">copyCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp/#a76bb7e313bac1bca54c0442c2a9391ab">CustomMappingID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#abe7d332de484fcc6cdc4c2a5e7bdd31b">llvm::RegisterBankInfo::DefaultMappingID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a52505890f7e825cd589db0e54395e9e5">llvm::AArch64GenRegisterBankInfo::getCopyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#aa2c869b663eb82158eb929290dd29f67">llvm::AArch64GenRegisterBankInfo::getFPExtMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a640c554d91abd68270b79cdef71b99a2">llvm::RegisterBankInfo::getInvalidInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#ace6c7f8d7dc748c8c3e5e4d3e230c71c">llvm::AArch64GenRegisterBankInfo::getValueMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac96e94b58836a8c283b78c423b96f5bc">llvm::isPreISelGenericFloatingPointOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cdb63ce3baf9ea9a1f86aed27f40fe8">llvm::isPreISelGenericOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#af484a43d5e4fa2ff1f1790d06f2ca94d">llvm::RegisterBankInfo::InstructionMapping::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a7bccd695609f957457acb1eaa984045c">llvm::AArch64GenRegisterBankInfo::PartMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a5204b837734b0428ff3bc7d07c5620ad">llvm::AArch64GenRegisterBankInfo::PMI_FirstFPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9a6f05aa805febfc871072ccfaeab73947">llvm::AArch64GenRegisterBankInfo::PMI_FirstGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a0ce0a1e8370bfd2d2f95eec99db57bd9ada6aa4fc496e081101afcb7ca2c8a373">llvm::AArch64GenRegisterBankInfo::PMI_None</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#a5bc25a8a7793e62e97276637b1f5bfcaaa633b88dcc41c33fb9989f39237c1b8a">llvm::AArch64GenRegisterBankInfo::Shift64Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64genregisterbankinfo/#ad8ba357b7ffb47400eba332bcc7a3653">llvm::AArch64GenRegisterBankInfo::ValMappings</a>.</p>

</div>
</div>

### getRegBankFromRegClass() {#a764ae29d6f969d21006942e066524217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBank &amp; AArch64RegisterBankInfo::getRegBankFromRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Get a register bank that covers <span class="doxyComputerOutput">RC</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">RC</span> is a user-defined register class (as opposed as one generated by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>).</p></dd>
</dl>



:::info
<p>The mapping RC -&gt; RegBank could be built while adding the coverage for the register banks. However, we do not do it, because, at least for now, we only need this information for register classes that are used in the description of instruction. In other words, there are just a handful of them and we do not want to waste space.</p>
:::


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-llvm/docs/api/pages/todo/#_todo000003>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>This should be <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'ed.</p>
</dd>
</dl>
</div>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9a3a4079fc2830c334da4406288bce24">llvm::RegisterBankInfo::getRegBankFromRegClass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyMappingImpl() {#aaa4cd7c504faff5c45f9dbd46f1107d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64RegisterBankInfo::applyMappingImpl (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
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

<p>See <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a0c85003f2e4060a7b61ebff7c2fb33cd">RegisterBankInfo::applyMapping</a>.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### getSameKindOfOperandsMapping() {#af64d705ae92f4f775fc640499be210f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AArch64RegisterBankInfo::getSameKindOfOperandsMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an instruction mapping where all the operands map to the same register bank and have similar size.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.getNumOperands() &lt;= 3</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">InstructionMappings</a> with a statically allocated OperandsMapping.</p></dd>
</dl>


<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### hasFPConstraints() {#a2b0e26f3341360c88b8a64e5abed0f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterBankInfo::hasFPConstraints (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, unsigned Depth=0)</td>
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


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### isLoadFromFPType() {#a0ba402fa31442da62e7eb0cf482504c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterBankInfo::isLoadFromFPType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the load <span class="doxyComputerOutput">MI</span> is likely loading from a floating-point type.</p></dd>
</dl>


<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### isPHIWithFPContraints() {#a2a59651669400ea6a55cac08c9d3674a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterBankInfo::isPHIWithFPContraints (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> is a PHI that its def is used by any instruction that onlyUsesFP.</p></dd>
</dl>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### onlyDefinesFP() {#ae029d15a73f61f7b4734b13d9a4ffee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterBankInfo::onlyDefinesFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, unsigned Depth=0)</td>
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


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### onlyUsesFP() {#a773e3e2ffea2d81a088c5102fdd015ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterBankInfo::onlyUsesFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, unsigned Depth=0)</td>
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


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>, definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MaxFPRSearchDepth {#a8ae1fd3d1d23b8cf0d9d016da10e4517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::AArch64RegisterBankInfo::MaxFPRSearchDepth = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum recursion depth for hasFPConstraints.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-cpp">AArch64RegisterBankInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
