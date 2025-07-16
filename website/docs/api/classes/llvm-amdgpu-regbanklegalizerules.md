---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpu/regbanklegalizerules
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegBankLegalizeRules` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPU::RegBankLegalizeRules { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">Target/AMDGPU/AMDGPURegBankLegalizeRules.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b79850edbd4118074e95097dca45fa5">RegBankLegalizeRules</a> (const GCNSubtarget &amp;ST, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad867bfe9924fe817ad4d885f3013f369">refreshRefs</a> (const GCNSubtarget &amp;_ST, MachineRegisterInfo &amp;_MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpu/setofrulesforopcode">SetOfRulesForOpcode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9252e07afc4bab4136f6c4c970f8e70b">getRulesForOpc</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuleSetInitializer</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfdd43b4ce9df4e1750301fe5e1a258e">addRulesForGOpcs</a> (std::initializer_list&lt; unsigned &gt; OpcList, FastRulesTypes FastTypes=NoFastRules)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuleSetInitializer</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd8918a3bf7fd24401f04b8fef4483e">addRulesForIOpcs</a> (std::initializer_list&lt; unsigned &gt; OpcList, FastRulesTypes FastTypes=NoFastRules)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c8337169ae4dba313302c26ac68625">ST</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abbea9269ece07b3ffac858c66238d3">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, unsigned, 256 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d4fe825d5493e476573daa5ed8629f">GRulesAlias</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/setofrulesforopcode">SetOfRulesForOpcode</a>, 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc322199ead732d8f892b18303ea0b73">GRules</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, unsigned, 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d39a749bcbd59cdc427655bb0f3ec6">IRulesAlias</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/setofrulesforopcode">SetOfRulesForOpcode</a>, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51d7480a769dbf1a0c04676a3e5ed88">IRules</a></td>
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


<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegBankLegalizeRules() {#a4b79850edbd4118074e95097dca45fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegBankLegalizeRules::RegBankLegalizeRules (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420aae917c4fa3b371b4952af2cefe97e856">llvm::AMDGPU::_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420aa6f2e5339ef0a03a1aac1a2ded70ee88">llvm::AMDGPU::B32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a6177319f039156724113f1ef7ed40b0c">llvm::AMDGPU::B64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420acd02fd0cdd6fbc43d3761d3bbcae7f7a">llvm::AMDGPU::DivB256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a9add2fdc05b41903b41ec3336a2fddd1">llvm::AMDGPU::DivB32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a2c1df13b184923afc2cb79b16c766f57">llvm::AMDGPU::DivP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ac6b534a26350aaeb0d0217c420def52b">llvm::AMDGPU::DivP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420afb78a782d068759a523da387da91d882">llvm::AMDGPU::DivS1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a9b162f0022f1653589cf67c3b072f9cb">llvm::AMDGPU::DivS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a4403259502320119000750de688b1afb">llvm::AMDGPU::DivS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0a3edacf17439555cbba7826bdba8dac44">llvm::AMDGPU::Ext32To64</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3f583e2bb417139560bde043214d064a">llvm::MachineMemOperand::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abc15369ab4cc583332950b913e2ef1dd">llvm::MachineMemOperand::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca26badaa8162c42e49ab3d5999a65f580">llvm::AMDGPU::IntrId</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstrinfo/#aa510d94632f7a11fd571d2c2271fb2b5">llvm::AMDGPUInstrInfo::isUniformMMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a615f4542f26ca7383f06e780996f8ef3">llvm::MONoClobber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcabcb5a7bc1ba76faa744b3d1c460fed56">llvm::AMDGPU::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a16c3a14a4de3fbf61469a9c80a01a9ed">llvm::AMDGPU::P1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a42cbb5784c00f3dd0212fc7bfeebbe90">llvm::AMDGPU::P5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a9fd6d43097151f643d4c212315e145a9">llvm::AMDGPU::S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a31b15cbedf64ec9894b8d52503e11de5">llvm::AMDGPU::S16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a718b53a09511fefc3f83047f21a1d33c">llvm::AMDGPU::S32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a234298685e8cccf9a4436f3ed81f1c8f">llvm::AMDGPU::S64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca152e43abebb05d1b0d8856d01c17e488">llvm::AMDGPU::Sgpr16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcaf5211bf8888c60fbe1b269d2c24f75f9">llvm::AMDGPU::Sgpr32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca832de20e9d87b94efdfc354458787573">llvm::AMDGPU::Sgpr32AExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca59eb781daac7d3a0694f5d4d6af0cd26">llvm::AMDGPU::Sgpr32AExtBoolInReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcabb770ecb61a0f3d900d5f8dab5598664">llvm::AMDGPU::Sgpr32SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca0a3015745b751740a381cc5534bb2131">llvm::AMDGPU::Sgpr32Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcab14bb58a8b905c6b5194f17ccc9b4877">llvm::AMDGPU::Sgpr64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca8a3118ddf3eeb3aa68d372298dd66e6b">llvm::AMDGPU::SgprB256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcaed59e0c4309b4b465702c47267f56c4a">llvm::AMDGPU::SgprB32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca4d3a75d0f42b09bb2a6aaa8e29bd7f35">llvm::AMDGPU::SgprB512</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca7cb70457b9a7f2d4e550cd18490aec03">llvm::AMDGPU::SgprB96</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca74a3a93e203357fddc16a866f46af38b">llvm::AMDGPU::SgprP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcadc2a6054a110a79fdc0ef91b50cf15f1">llvm::AMDGPU::SgprP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca95fe7cbc0903e9839f85044e0d1943ce">llvm::AMDGPU::SgprP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca9da9b63817b975b16e2146f45e746227">llvm::AMDGPU::SgprV4S32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0a43420bdf35c2ae2bf5a867752427a5dd">llvm::AMDGPU::SplitLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0ab1f9f4af76fd81ab378c91c4b00950b6">llvm::AMDGPU::SplitTo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262abce3f99fab69ba4801804b8c28f73a34">llvm::AMDGPU::Standard</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262a3cb60658cac73d7fe29209ac74ec4e14">llvm::AMDGPU::StandardB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420af6e9d4a12a2dcf16f084720a1ef87941">llvm::AMDGPU::UniB256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a4f7512b2db0c88a026ac6b312a2e20ef">llvm::AMDGPU::UniB32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a3a4a82361555b80d3c6297236c83b7e2">llvm::AMDGPU::UniB512</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a9bb212a131349c1db3f88ca6ee67434b">llvm::AMDGPU::UniB96</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0a9cffdde746ee4022f8e90107fe51f8d1">llvm::AMDGPU::UniCstExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0afd81666d5ed77c2111bd783faa875198">llvm::AMDGPU::UniExtToSel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcafa044f776f82a3c6275a148ad5fef896">llvm::AMDGPU::UniInVcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca696d170f169ad14b2536d2373ec41829">llvm::AMDGPU::UniInVgprB256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca3d22e6dc456ca3e7eed8fb46ebc60fd0">llvm::AMDGPU::UniInVgprB32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca4e7b2533f0aa894335ee546703e014bf">llvm::AMDGPU::UniInVgprB512</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcaa8af1c3a9b1b0e0a977ee3f1a32b5a22">llvm::AMDGPU::UniInVgprS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcab55475fbaf6c160e90a5029936664b6c">llvm::AMDGPU::UniInVgprV4S32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a988754bd8189f1fe50f0c35fcd4fe89a">llvm::AMDGPU::UniP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ae746790acf7e929808a4600690d1b58d">llvm::AMDGPU::UniP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ae7d7ff3ebc4c6919fe11d44e42e2ffdd">llvm::AMDGPU::UniP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a7a410554c7d5aec017fb84e95b95ffff">llvm::AMDGPU::UniS1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420add4a306f664c8209ecf726d99b5704fd">llvm::AMDGPU::UniS16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a26f1c53b64b980b589c64fd9f61ec50f">llvm::AMDGPU::UniS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a4a917415d28aa004b6b5390d58c36401">llvm::AMDGPU::UniS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ab547a3c88483f9165fa181394d29953d">llvm::AMDGPU::V4S32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca6669439c12cd7ae7c8fed15359a81e18">llvm::AMDGPU::Vcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262a571f015306694174addcb54842a15ac7">llvm::AMDGPU::Vector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca1b281c0f05b475aaae25ea8c7f4aea7b">llvm::AMDGPU::Vgpr32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca12ef34ac724150aac8ccb203eff11009">llvm::AMDGPU::Vgpr64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcaadd1145675e4849c6bb045cabb65bf9d">llvm::AMDGPU::VgprB256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcaed25bff8fc6f6613575977db519d9a19">llvm::AMDGPU::VgprB32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca3b3e22f9c912ea74f69e0ff0dd6de812">llvm::AMDGPU::VgprB64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca3dd150ca6fcb2e3465d27226d7053555">llvm::AMDGPU::VgprP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcac042ac321dadb1b230afaadeb4816057">llvm::AMDGPU::VgprP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae1f96ab0b266e8039e3d455732e08020">llvm::AMDGPU::VgprP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca95600d5ac08bd4789e3aceb6e7939054">llvm::AMDGPU::VgprP5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0a725b926ea23c39c30c19e60233e8020b">llvm::AMDGPU::VgprToVccCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dca17343bb745e934dcc1bcf450ff706ca5">llvm::AMDGPU::VgprV4S32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae9d530191589ddeb8892e3839cd65ad0a25f529d266f0d999cd8a687aa220a2f4">llvm::AMDGPU::WidenLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRulesForOpc() {#a9252e07afc4bab4136f6c4c970f8e70b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SetOfRulesForOpcode &amp; RegBankLegalizeRules::getRulesForOpc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### refreshRefs() {#ad867bfe9924fe817ad4d885f3013f369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::RegBankLegalizeRules::refreshRefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; _ST, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; _MRI)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRulesForGOpcs() {#acfdd43b4ce9df4e1750301fe5e1a258e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegBankLegalizeRules::RuleSetInitializer RegBankLegalizeRules::addRulesForGOpcs (std::initializer_list&lt; unsigned &gt; OpcList, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262">FastRulesTypes</a> FastTypes=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262a5f6d4bc34de12684ca978bf780f01db6">NoFastRules</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>

</div>
</div>

### addRulesForIOpcs() {#accd8918a3bf7fd24401f04b8fef4483e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegBankLegalizeRules::RuleSetInitializer RegBankLegalizeRules::addRulesForIOpcs (std::initializer_list&lt; unsigned &gt; OpcList, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262">FastRulesTypes</a> FastTypes=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262a5f6d4bc34de12684ca978bf780f01db6">NoFastRules</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GRules {#abc322199ead732d8f892b18303ea0b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;unsigned, SetOfRulesForOpcode, 128&gt; llvm::AMDGPU::RegBankLegalizeRules::GRules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### GRulesAlias {#a05d4fe825d5493e476573daa5ed8629f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;unsigned, unsigned, 256&gt; llvm::AMDGPU::RegBankLegalizeRules::GRulesAlias</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### IRules {#aa51d7480a769dbf1a0c04676a3e5ed88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;unsigned, SetOfRulesForOpcode, 64&gt; llvm::AMDGPU::RegBankLegalizeRules::IRules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### IRulesAlias {#a84d39a749bcbd59cdc427655bb0f3ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;unsigned, unsigned, 128&gt; llvm::AMDGPU::RegBankLegalizeRules::IRulesAlias</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### MRI {#a7abbea9269ece07b3ffac858c66238d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::AMDGPU::RegBankLegalizeRules::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### ST {#a90c8337169ae4dba313302c26ac68625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* llvm::AMDGPU::RegBankLegalizeRules::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
