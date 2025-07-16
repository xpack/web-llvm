---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sipeepholesdwa-cpp-/sdwasrcoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SDWASrcOperand` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand">SDWAOperand</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343cdc89d09f22bb5b38c4aba41e5ac3">SDWASrcOperand</a> (MachineOperand *TargetOp, MachineOperand *ReplacedOp, SdwaSel SrcSel_=DWORD, bool Abs_=false, bool Neg_=false, bool Sext_=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2319e3588e98e73879945fdc62b25b">potentialToConvert</a> (const SIInstrInfo *TII, const GCNSubtarget &amp;ST, SDWAOperandsMap *PotentialMatches=nullptr) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8257623efa7db9d91500e6ea06cb9027">convertToSDWA</a> (MachineInstr &amp;MI, const SIInstrInfo *TII) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0a">SdwaSel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d02710c9c91ace63a9d7d456b8f35e5">getSrcSel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad20b22734ec206b6f0427be8c1c08ab7">getAbs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5cb82054f4004da129744b265ed286">getNeg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586e6550b76ae91e1a67ad41ca71476b">getSext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c68256cc9ae18cd75c21521bc7f8c51">getSrcMods</a> (const SIInstrInfo *TII, const MachineOperand *SrcOp) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d77f830cb8a6fd05f8057796771152d">print</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0a">SdwaSel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98665dc9e3505ae4d8e71f7eef1f1ffc">SrcSel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bbb1691ea4e7ef36f7c649707dbe56b">Abs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a681a9c7c4c3d49da43a626bcabfc965c">Neg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afed5651c5f221a12fe7d501dd7fa11ac">Sext</a></td>
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


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SDWASrcOperand() {#a343cdc89d09f22bb5b38c4aba41e5ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::SDWASrcOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * TargetOp, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * ReplacedOp, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0a">SdwaSel</a> SrcSel_=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">DWORD</a>, bool Abs_=false, bool Neg_=false, bool Sext_=false)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">llvm::AMDGPU::SDWA::DWORD</a> and <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#ac837226d2f0817f52497e4f8a05f027f">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::SDWAOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertToSDWA() {#a8257623efa7db9d91500e6ea06cb9027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDWASrcOperand::convertToSDWA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#ac1298e19de485440c2caeb29b9e63609">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getReplacedOperand</a>, <a href="#a8c68256cc9ae18cd75c21521bc7f8c51">getSrcMods</a>, <a href="#a7d02710c9c91ace63a9d7d456b8f35e5">getSrcSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a2a655c25bfbbaa657d430fe07389c0ce">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getTargetOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a5c223bc99892ed1d57b7050b97ffca91">isSameReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6a58f19664e2b69107495d2085514f7874">llvm::AMDGPU::SDWA::UNUSED_PRESERVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaf4e7a9b6898b774104bfcd24a211d7e3">llvm::AMDGPU::SDWA::WORD_0</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aa3bd07eb171e650bc021c8e2517e175d0">llvm::AMDGPU::SDWA::WORD_1</a>.</p>

</div>
</div>

### getAbs() {#ad20b22734ec206b6f0427be8c1c08ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::getAbs ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>Referenced by <a href="#a2d77f830cb8a6fd05f8057796771152d">print</a>.</p>

</div>
</div>

### getNeg() {#aea5cb82054f4004da129744b265ed286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::getNeg ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>Referenced by <a href="#a2d77f830cb8a6fd05f8057796771152d">print</a>.</p>

</div>
</div>

### getSext() {#a586e6550b76ae91e1a67ad41ca71476b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::getSext ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>Referenced by <a href="#a2d77f830cb8a6fd05f8057796771152d">print</a>.</p>

</div>
</div>

### getSrcMods() {#a8c68256cc9ae18cd75c21521bc7f8c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SDWASrcOperand::getSrcMods (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * SrcOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a1be8a1ab79f4d1830526cc8d48960168">llvm::SISrcMods::ABS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af1ceb53a1b47dab205dc19070b47a1a6">llvm::SISrcMods::NEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a0842f25a9552eadbca3c10f9af0a36fe">llvm::SISrcMods::SEXT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a8257623efa7db9d91500e6ea06cb9027">convertToSDWA</a>.</p>

</div>
</div>

### getSrcSel() {#a7d02710c9c91ace63a9d7d456b8f35e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SdwaSel anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::getSrcSel ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>Referenced by <a href="#a8257623efa7db9d91500e6ea06cb9027">convertToSDWA</a> and <a href="#a2d77f830cb8a6fd05f8057796771152d">print</a>.</p>

</div>
</div>

### potentialToConvert() {#a7f2319e3588e98e73879945fdc62b25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SDWASrcOperand::potentialToConvert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/namespaces/anonymous-sipeepholesdwa-cpp-/#aa998279f86784f6bbf2a88d25d051172">SDWAOperandsMap</a> * PotentialMatches=nullptr)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a349ccb69c0901c3188afbce59873f56b">findSingleRegUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a0c6990b6699e777df2f4021f237cbc5e">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#ac1298e19de485440c2caeb29b9e63609">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getReplacedOperand</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sipeepholesdwa-cpp-/#a2bc160bdefcc7e1d3000ac78dcec0e0d">anonymous{SIPeepholeSDWA.cpp}::isConvertibleToSDWA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a5c223bc99892ed1d57b7050b97ffca91">isSameReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### print() {#a2d77f830cb8a6fd05f8057796771152d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDWASrcOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="#ad20b22734ec206b6f0427be8c1c08ab7">getAbs</a>, <a href="#aea5cb82054f4004da129744b265ed286">getNeg</a>, <a href="#a586e6550b76ae91e1a67ad41ca71476b">getSext</a>, <a href="#a7d02710c9c91ace63a9d7d456b8f35e5">getSrcSel</a> and <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a2a655c25bfbbaa657d430fe07389c0ce">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getTargetOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Abs {#a2bbb1691ea4e7ef36f7c649707dbe56b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::Abs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>

</div>
</div>

### Neg {#a681a9c7c4c3d49da43a626bcabfc965c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::Neg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>

</div>
</div>

### Sext {#afed5651c5f221a12fe7d501dd7fa11ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::Sext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>

</div>
</div>

### SrcSel {#a98665dc9e3505ae4d8e71f7eef1f1ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SdwaSel anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::SrcSel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
