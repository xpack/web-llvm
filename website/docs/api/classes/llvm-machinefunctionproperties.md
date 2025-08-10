---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinefunctionproperties
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineFunctionProperties` Class

<p>Properties which a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> may have at a given point in time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineFunctionProperties { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Property : unsigned { <a href="#ad85237c6c667e4713efe8921e9c32ac1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacef05f16d3e71703f08bb4677e1d7a2">hasProperty</a> (Property P) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7780563d7ca260d0ae67d957b56427f">set</a> (Property P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f789465ed765ac2795381e8b91b902">reset</a> (Property P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698a4b70d19dda206a6833f55aa8eb5a">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset all the properties. <a href="#a698a4b70d19dda206a6833f55aa8eb5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca914d21baa1199b852d881703be322">set</a> (const MachineFunctionProperties &amp;MFP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb794337d64759de26149254a3d3ff2">reset</a> (const MachineFunctionProperties &amp;MFP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e4aa663bae5cd9d0b8331dd1e05450">verifyRequiredProperties</a> (const MachineFunctionProperties &amp;V) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8437f33fa9e1911e5080f42413c30987">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> in human-readable form. <a href="#a8437f33fa9e1911e5080f42413c30987">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; static_cast&lt; unsigned &gt;(<a href="#ad85237c6c667e4713efe8921e9c32ac1a92df88d953a47d76d0ac44a3c70cf88c">Property::LastProperty</a>)+1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9ff37b42d7fe4c282f4ecca3c8a87d">Properties</a></td>
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

<p>Properties which a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> may have at a given point in time.</p>


<p>Each of these has checking code in the MachineVerifier, and passes can require that a property be set.</p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Property {#ad85237c6c667e4713efe8921e9c32ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::MachineFunctionProperties::Property : unsigned</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsSSA<a id="ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoPHIs<a id="ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TracksLiveness<a id="ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoVRegs<a id="ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FailedISel<a id="ad85237c6c667e4713efe8921e9c32ac1a8014afd87e04236365d1796e38bc15f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Legalized<a id="ad85237c6c667e4713efe8921e9c32ac1aefa6e814420e5fc1dfad353869159a37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegBankSelected<a id="ad85237c6c667e4713efe8921e9c32ac1a062927be2f9d18d9995e64b0779c3dcf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Selected<a id="ad85237c6c667e4713efe8921e9c32ac1a91b442d385b54e1418d81adc34871053"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TiedOpsRewritten<a id="ad85237c6c667e4713efe8921e9c32ac1a2e0aa187d296e1330d12a948094f601b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FailsVerification<a id="ad85237c6c667e4713efe8921e9c32ac1a006012900aff2102a22e6424f2994592"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FailedRegAlloc<a id="ad85237c6c667e4713efe8921e9c32ac1a84c7a981b331eae0f00669f3775ab3ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TracksDebugUserValues<a id="ad85237c6c667e4713efe8921e9c32ac1a76b22d924565975a49b2283fa838e5f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastProperty<a id="ad85237c6c667e4713efe8921e9c32ac1a92df88d953a47d76d0ac44a3c70cf88c"></a></td>
<td class="doxyEnumItemDescription"> (= TracksDebugUserValues)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasProperty() {#aacef05f16d3e71703f08bb4677e1d7a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFunctionProperties::hasProperty (<a href="#ad85237c6c667e4713efe8921e9c32ac1">Property</a> P)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a366a7f426707271b798b4355c12ce57d">llvm::AArch64RegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa13f60350a3e19e1791fd628b694da36">llvm::MachineBasicBlock::liveout_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineverifierpass/#a8f6669235c21d5e639d04b8859f74d95">llvm::MachineVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagiselpass/#afbe031a5b54a7910faf25270aeeac0dc">llvm::SelectionDAGISelPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a7cf6d1c87b479dd800293a9194aaff9a">runFixI1Copies</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64postselectoptimize-cpp-/aarch64postselectoptimize/#af49f0a980846fa603bc9009a7135008a">anonymous{AArch64PostSelectOptimize.cpp}::AArch64PostSelectOptimize::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#ad1210df2e489436f417f18f10180ea44">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#abceb824dea15a0f50ab19fc7126f618f">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifierlegacypass/#a11b302b39fa3845b19fad010fae1e7ea">anonymous{MachineVerifier.cpp}::MachineVerifierLegacyPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombiner/#a19ada2e0d9fd32ef5cafea3f4581bab0">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombiner::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-resetmachinefunctionpass-cpp-/resetmachinefunction/#a1ca062be17e509ab43e062b6ccbed2e1">anonymous{ResetMachineFunctionPass.cpp}::ResetMachineFunction::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a98e4a98a0db786235d78fce93ad4a72f">llvm::InstructionSelect::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/localizer/#ac696e5096a6db4c18e884c119cb50446">llvm::Localizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ae245b9ebf2973a3e982ccd16c9bf93f1">llvm::RegBankSelect::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisellegacy/#a32f14bc31f9990134e480ee3e0e0bd11">llvm::SelectionDAGISelLegacy::runOnMachineFunction</a>.</p>

</div>
</div>

### print() {#a8437f33fa9e1911e5080f42413c30987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineFunctionProperties::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> in human-readable form.</p>

<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a>.</p>

</div>
</div>

### reset() {#af2f789465ed765ac2795381e8b91b902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties &amp; llvm::MachineFunctionProperties::reset (<a href="#ad85237c6c667e4713efe8921e9c32ac1">Property</a> P)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#af2f789465ed765ac2795381e8b91b902">reset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="#a698a4b70d19dda206a6833f55aa8eb5a">reset</a> and <a href="#af2f789465ed765ac2795381e8b91b902">reset</a>.</p>

</div>
</div>

### reset() {#a698a4b70d19dda206a6833f55aa8eb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties &amp; llvm::MachineFunctionProperties::reset ()</td>
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

<p>Reset all the properties.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Reference <a href="#af2f789465ed765ac2795381e8b91b902">reset</a>.</p>

</div>
</div>

### reset() {#a8bb794337d64759de26149254a3d3ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties &amp; llvm::MachineFunctionProperties::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp; MFP)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

### set() {#aa7780563d7ca260d0ae67d957b56427f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties &amp; llvm::MachineFunctionProperties::set (<a href="#ad85237c6c667e4713efe8921e9c32ac1">Property</a> P)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#aa7780563d7ca260d0ae67d957b56427f">set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#abc18ea423bfb8352df7af014ecdca412">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ac79a13892c2153a0d4b515450c8103ec">anonymous{RegAllocBasic.cpp}::RABasic::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/regallocfast/#aaa3b5d7ae9fba1719f6554c2f98dd784">anonymous{RegAllocFast.cpp}::RegAllocFast::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#ab0cf5c8feca35339f23d35c321a380ac">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#a7d6fd0a43420aacdcb844afc48c3b9cb">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#ae154d0dbe18405320d8f4c6714033e43">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspillslegacy/#a680fbbf46622ab9b7d1019fcf29565c1">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpillsLegacy::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverangelegacy/#ac53e8af16ea744f989d915430ff14acf">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRangeLegacy::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#a0e70cafc2f3de81ad5694d37b97e3172">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/earlytailduplicatelegacy/#a8fc82cbde6f3e173bb42e9cd396c5835">anonymous{TailDuplication.cpp}::EarlyTailDuplicateLegacy::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/earlytailduplicatepass/#a70508b2cf128b6204b111917e3f047f5">llvm::EarlyTailDuplicatePass::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a4826fbc92fee0ed4c9a1c2c14f264a61">llvm::Legalizer::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a2157525b0c1a0284c11b859dc69a392c">llvm::RAGreedy::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocfastpass/#a84e483144c06ca65da7a2960e3eb330e">llvm::RegAllocFastPass::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a2c817913c3f5dbcf0c09a97e0bbedcbb">llvm::RegBankSelect::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/silowersgprspillspass/#a029a714b2110886cb7578c9d19d22348">llvm::SILowerSGPRSpillsPass::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/sioptimizevgprliverangepass/#a1ca6917416a4fe28606a6a0529e5e1f4">llvm::SIOptimizeVGPRLiveRangePass::getClearedProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64a53fix835769-cpp-/aarch64a53fix835769/#a5c667e2db3808f770a6740663b80d798">anonymous{AArch64A53Fix835769.cpp}::AArch64A53Fix835769::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64a57fploadbalancing-cpp-/aarch64a57fploadbalancing/#af71ca2acb17fa779e9ad679eddee5b26">anonymous{AArch64A57FPLoadBalancing.cpp}::AArch64A57FPLoadBalancing::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a239bd67732b5c643f09c036418e8475a">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64compressjumptables-cpp-/aarch64compressjumptables/#a3e3826e83b96ac79e1552b09b3218983">anonymous{AArch64CompressJumpTables.cpp}::AArch64CompressJumpTables::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkorhwpffix/#a07e1fdfb287d176e5fdc7bfeae03a454">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorHWPFFix::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#ae292d6670e0f9100e1d2e1cf7f1614e8">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#ac0692527750baf6879a2bc82d7221cd2">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#a8e87361befd343a840e87d2ef988269e">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-armexpandpseudoinsts-cpp-/armexpandpseudo/#a0840dfa45efcd82c52270fdf92e3ee75">anonymous{ARMExpandPseudoInsts.cpp}::ARMExpandPseudo::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#a39bb49d7ec44552cca435cda61b7bf4d">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-armloadstoreoptimizer-cpp-/armloadstoreopt/#a736df1b5edb86baaa058b68de0a2c0c1">anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/armlowoverheadloops/#ace7f979f618a440c4d623c5b09d525a8">anonymous{ARMLowOverheadLoops.cpp}::ARMLowOverheadLoops::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-armoptimizebarrierspass-cpp-/armoptimizebarrierspass/#a5052a36bac9d94a785795c22a07e1a86">anonymous{ARMOptimizeBarriersPass.cpp}::ARMOptimizeBarriersPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-branchfolding-cpp-/branchfolderpass/#ab85f98c7f1e25360f7dbcde936ae8403">anonymous{BranchFolding.cpp}::BranchFolderPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a1c7f4adf2824a37fb41489767a871fcc">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#ae316937ce3cb26fef8a112eaef95f2e7">anonymous{DelaySlotFiller.cpp}::Filler::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-funcletlayout-cpp-/funcletlayout/#a6ef7b06ee2b91f6ba8794585e960910e">anonymous{FuncletLayout.cpp}::FuncletLayout::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcndppcombine-cpp-/gcndppcombinelegacy/#ac9d602f888c401412235ef42509a47c2">anonymous{GCNDPPCombine.cpp}::GCNDPPCombineLegacy::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#ad6f7afaf9e44f6f8399069027b00ce70">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopytocombine-cpp-/hexagoncopytocombine/#aadc8e059f60b864553708654def47460">anonymous{HexagonCopyToCombine.cpp}::HexagonCopyToCombine::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonfixuphwloops-cpp-/hexagonfixuphwloops/#a8ec75b638d1478e7557a9c15c4a66f7d">anonymous{HexagonFixupHwLoops.cpp}::HexagonFixupHwLoops::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonframelowering-cpp-/hexagoncallframeinformation/#a8380dea8e9bc4e7e76aa42e555c859fc">anonymous{HexagonFrameLowering.cpp}::HexagonCallFrameInformation::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenmux-cpp-/hexagongenmux/#a63e7022adc30a897d098b5b4761de91c">anonymous{HexagonGenMux.cpp}::HexagonGenMux::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a35854d75fd4924111614daddbc6f39c1">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#afb9746b7b921e0f8dde35b5ab9e611ea">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonsplitconst32andconst64-cpp-/hexagonsplitconst32andconst64/#a1eea254a91e55d8d13dfe0c407aaa72c">anonymous{HexagonSplitConst32AndConst64.cpp}::HexagonSplitConst32AndConst64::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvliwpacketizer-cpp-/hexagonpacketizer/#a056be6d86112076b9fe409db2b29b1f5">anonymous{HexagonVLIWPacketizer.cpp}::HexagonPacketizer::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-ifconversion-cpp-/ifconverter/#a55a60b717a250f6623209945ca4eef7e">anonymous{IfConversion.cpp}::IfConverter::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks/#abea1dc15403c395ed6ec0b7e31bc4f1d">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#a3e40f7a3f113c9b8786ed5f3aa57a1f7">anonymous{LanaiDelaySlotFiller.cpp}::Filler::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaimemalucombiner-cpp-/lanaimemalucombiner/#a2e706ecfb59a360fd96ac56c845d31e0">anonymous{LanaiMemAluCombiner.cpp}::LanaiMemAluCombiner::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a79228e36897aedf01e7d43f322618cc5">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kexpandpseudo-cpp-/m68kexpandpseudo/#a181344ea95e906414a8bdb93255008c3">anonymous{M68kExpandPseudo.cpp}::M68kExpandPseudo::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/machinecopypropagation/#a8382a49ec29bcd75d6f509039774baff">anonymous{MachineCopyPropagation.cpp}::MachineCopyPropagation::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecselegacy/#ae354595ac92707a6c19749ff6b2b7624">anonymous{MachineCSE.cpp}::MachineCSELegacy::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelateinstrscleanup-cpp-/machinelateinstrscleanup/#a814daa857e9c7302c755a961c409f6d0">anonymous{MachineLateInstrsCleanup.cpp}::MachineLateInstrsCleanup::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/postramachinesinking/#a3b73158cd3f0c7068d84d401ff29edf3">anonymous{MachineSink.cpp}::PostRAMachineSinking::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsbranchexpansion-cpp-/mipsbranchexpansion/#a48c8239225d0a839cb10c1812b69d64b">anonymous{MipsBranchExpansion.cpp}::MipsBranchExpansion::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#aeed0ecac46a557ab2e45f837ad079795">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#ac2214ef0e9d9e5faa984b84304ac8886">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsexpandpseudo-cpp-/mipsexpandpseudo/#a61a4f270fb76e86ae3d21156697e921e">anonymous{MipsExpandPseudo.cpp}::MipsExpandPseudo::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmulmulbugpass-cpp-/mipsmulmulbugfix/#a15be19c96d4682701e3b6d7f6f1c1f06">anonymous{MipsMulMulBugPass.cpp}::MipsMulMulBugFix::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430branchselector-cpp-/msp430bsel/#a299a270842e7c7f0df6b709df87f0a3c">anonymous{MSP430BranchSelector.cpp}::MSP430BSel::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvevptblockpass-cpp-/mvevptblock/#aff51fb0a79d0b98fda6538e8cb701ad7">anonymous{MVEVPTBlockPass.cpp}::MVEVPTBlock::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/requireallmachinefunctionpropertiespass/#a51d415d436970a5983265860e4e68fb7">anonymous{PassBuilder.cpp}::RequireAllMachineFunctionPropertiesPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a24c817ab327773df1bab899f9b04aa25">anonymous{PatchableFunction.cpp}::PatchableFunction::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizerlegacy/#a15d9a96552a67917680357fe6d8b4179">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizerLegacy::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/postrascheduler/#ad2b5d1b9b79745514bd882fbed8219b1">anonymous{PostRASchedulerList.cpp}::PostRAScheduler::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a6f015a14545478d7bb7ca6308851d378">anonymous{PPCBranchSelector.cpp}::PPCBSel::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#a40be9759a2ed8e79a4bacea30cd3e06f">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a6a589636762ce9996d9e1b9da27a8ae7">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-processimplicitdefs-cpp-/processimplicitdefs/#a1401f248633e69bad4858389676799a0">anonymous{ProcessImplicitDefs.cpp}::ProcessImplicitDefs::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600optimizevectorregisters-cpp-/r600vectorregmerger/#a1a1532d9cf4834656588bf27b4810a62">anonymous{R600OptimizeVectorRegisters.cpp}::R600VectorRegMerger::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a1d3638f49d5e7210b0d1441aaf6ba1e6">anonymous{RegAllocBasic.cpp}::RABasic::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/regallocfast/#a6d44c9d06500f50c6c53fedf4fdf3002">anonymous{RegAllocFast.cpp}::RegAllocFast::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#aecbbbec3b6fe5b83726bbd7494283b35">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a875accebce58c4a6f4e9d7f8cc5949d3">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvredundantcopyelimination-cpp-/riscvredundantcopyelimination/#ab577686a92c686764bff6f2014c72072">anonymous{RISCVRedundantCopyElimination.cpp}::RISCVRedundantCopyElimination::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvvectorpeephole-cpp-/riscvvectorpeephole/#a6c1d9aceab566744f98039d0e55cec14">anonymous{RISCVVectorPeephole.cpp}::RISCVVectorPeephole::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#ac14d58b234f78072b3f0f63b642e5bd1">anonymous{ShrinkWrap.cpp}::ShrinkWrap::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizerlegacy/#a8a0df6f19a09ac14c864854d746ccadd">anonymous{SILoadStoreOptimizer.cpp}::SILoadStoreOptimizerLegacy::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverangelegacy/#a078447a30cacbeb6a45627a607bf8a30">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRangeLegacy::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackmaplivenessanalysis-cpp-/stackmapliveness/#a2278e9abea3d9800525cc49e19ab4b8f">anonymous{StackMapLivenessAnalysis.cpp}::StackMapLiveness::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelimcompare-cpp-/systemzelimcompare/#a8d16912b4d6ae094b77b3545fe14287a">anonymous{SystemZElimCompare.cpp}::SystemZElimCompare::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzlongbranch-cpp-/systemzlongbranch/#a320113a8db3f87f6939f66de64a5b90f">anonymous{SystemZLongBranch.cpp}::SystemZLongBranch::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzshorteninst-cpp-/systemzshorteninst/#ab78c1eb0f8a0c24c06e76f44bd4687f1">anonymous{SystemZShortenInst.cpp}::SystemZShortenInst::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-thumb2itblockpass-cpp-/thumb2itblock/#a0a4add9709c81ee8fb4a6b44be86b7b2">anonymous{Thumb2ITBlockPass.cpp}::Thumb2ITBlock::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-thumb2sizereduction-cpp-/thumb2sizereduce/#a963afaa954042a5b102dc3acb3556355">anonymous{Thumb2SizeReduction.cpp}::Thumb2SizeReduce::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86compressevex-cpp-/compressevexpass/#aac8ffeb05b15be8e6c0e256f5ef62f83">anonymous{X86CompressEVEX.cpp}::CompressEVEXPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86expandpseudo-cpp-/x86expandpseudo/#ad8baad9a9c7f014e0a53fe03fc824f14">anonymous{X86ExpandPseudo.cpp}::X86ExpandPseudo::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fasttileconfig-cpp-/x86fasttileconfig/#a174ffa5e97def08d2192ba2e14048565">anonymous{X86FastTileConfig.cpp}::X86FastTileConfig::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupbwinsts-cpp-/fixupbwinstpass/#ac2f8f35a6671c8b081cb647487a544ec">anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupinsttuning-cpp-/x86fixupinsttuningpass/#afd3d2e9ce27455a0e03a759cfd8afb34">anonymous{X86FixupInstTuning.cpp}::X86FixupInstTuningPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupleas-cpp-/fixupleapass/#aed931331edde96e113fbd89b74ff86eb">anonymous{X86FixupLEAs.cpp}::FixupLEAPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupvectorconstants-cpp-/x86fixupvectorconstantspass/#ab2855a2342636cc427471148b69abb13">anonymous{X86FixupVectorConstants.cpp}::X86FixupVectorConstantsPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86floatingpoint-cpp-/fps/#adae4a852548988170c652dc40b1fe143">anonymous{X86FloatingPoint.cpp}::FPS::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86padshortfunction-cpp-/padshortfunc/#ab71e75c9e9440cb43172936ea5b5cf4c">anonymous{X86PadShortFunction.cpp}::PadShortFunc::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a043ee13f693a1420cd0be1d12b42c279">anonymous{X86TileConfig.cpp}::X86TileConfig::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86vzeroupper-cpp-/vzeroupperinserter/#accbbd1d2ca7f88495dfdf4d9f3a5fa15">anonymous{X86VZeroUpper.cpp}::VZeroUpperInserter::getRequiredProperties</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoreframetoargsoffsetelim-cpp-/xcoreftaoelim/#a1aff51c9e49f25c34932c1c2cb29d0c8">anonymous{XCoreFrameToArgsOffsetElim.cpp}::XCoreFTAOElim::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/breakfalsedeps/#a3ab7ee3a2d7fe2ee12b7b0604c3de817">llvm::BreakFalseDeps::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix/#a26657d3f8a330b3b43c90710cdc98cdf">llvm::ExecutionDomainFix::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndppcombinepass/#af3f2fb487749944f256072d4d4543297">llvm::GCNDPPCombinePass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a4113dc3a4dee739e9400d16e9dcbf9d0">llvm::InstructionSelect::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#af8d8a33af0652e0eda72e0a0c701cf3c">llvm::Legalizer::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstoreopt/#a78d104dee4d5b8643256ca1e9713df46">llvm::LoadStoreOpt::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/localizer/#a813d394fbe924136a6f5b60c45e35046">llvm::Localizer::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinecsepass/#a9e15e63d9aa597896a30708cf535ce56">llvm::MachineCSEPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/peepholeoptimizerpass/#aee6cbae8ff342084325d1ade32999846">llvm::PeepholeOptimizerPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a36c2bd8ddd9e9e08a4674b0ba60f864a">llvm::RAGreedy::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#ad96c8d05f6a14c1009a4db5a7e710f8b">llvm::ReachingDefAnalysis::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocfastpass/#a272fc4be2ca71d2286c70b8134345ab7">llvm::RegAllocFastPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a4f33cb36edf1eebe70860431e8ce5cf9">llvm::RegBankSelect::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/siloadstoreoptimizerpass/#aa07c3674a20ab6612e185e3fa58da6c9">llvm::SILoadStoreOptimizerPass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/sioptimizevgprliverangepass/#a9f7f8d196e661538ac73970531b018c1">llvm::SIOptimizeVGPRLiveRangePass::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a8930a179607146f20d980c6bcbac9d7b">RemoveLoadsIntoFakeUses::getRequiredProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#a25845d21dc6229f66a8689680c0be12f">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-phielimination-cpp-/phielimination/#abfd142a81282861575acbcda9e862fe9">anonymous{PHIElimination.cpp}::PHIElimination::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/regallocfast/#a5f180a98b30588ebfe0a89e97030b37f">anonymous{RegAllocFast.cpp}::RegAllocFast::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtregmap-cpp-/virtregrewriter/#ad2a3758c830fe565d74f3984ce0e6054">anonymous{VirtRegMap.cpp}::VirtRegRewriter::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#ac4635774286a80c256b30d359162cc17">llvm::InstructionSelect::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a9cbff24b02e27a4be63947ede539122a">llvm::Legalizer::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariablesanalysis/#a85b6d20f8f68e4ec295c61abc38daf9c">llvm::LiveDebugVariablesAnalysis::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariableswrapperlegacy/#a9ecafb669b86ef9b6da0c0bd11a07503">llvm::LiveDebugVariablesWrapperLegacy::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocfastpass/#aa252c6c0d012f62532213ea4f862c2d6">llvm::RegAllocFastPass::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a32e55cc7580b5fb9e05ff84001d5fd1a">llvm::RegBankSelect::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/twoaddressinstructionpass/#a82c8664e171cdd038671bf485f32793e">llvm::TwoAddressInstructionPass::getSetProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b804856a2e313abeef6f32c3c6f61eb">llvm::reportGISelFailure</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#a477b123c7ac80e57d0c8ac4abb0ff293">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-phielimination-cpp-/phieliminationimpl/#aab3db5c9e390ca00331b7d432c735dcd">anonymous{PHIElimination.cpp}::PHIEliminationImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvliwpacketizer-cpp-/hexagonpacketizer/#a84914fb49b671ec22a8cb348237182c7">anonymous{HexagonVLIWPacketizer.cpp}::HexagonPacketizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a18192ed7893e8738ddd38e7f75bb3bf7">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3003dfad609a8e6f0a38214ef5623841">llvm::scavengeFrameVirtualRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a> and <a href="#aa7780563d7ca260d0ae67d957b56427f">set</a>.</p>

</div>
</div>

### set() {#a7ca914d21baa1199b852d881703be322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties &amp; llvm::MachineFunctionProperties::set (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp; MFP)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

### verifyRequiredProperties() {#a87e4aa663bae5cd9d0b8331dd1e05450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFunctionProperties::verifyRequiredProperties (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a> &amp; V)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Properties {#a8d9ff37b42d7fe4c282f4ecca3c8a87d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;static_cast&lt;unsigned&gt;(Property::LastProperty) + 1&gt; llvm::MachineFunctionProperties::Properties</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
