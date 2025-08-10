---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SDWADstOperand` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand { ... }
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand">SDWADstPreserveOperand</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc566f341eefa0781239ca4da66e76d">SDWADstOperand</a> (MachineOperand *TargetOp, MachineOperand *ReplacedOp, SdwaSel DstSel_=DWORD, DstUnused DstUn_=UNUSED_PAD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cbad20def038be01a642ef5bc5a0360">potentialToConvert</a> (const SIInstrInfo *TII, const GCNSubtarget &amp;ST, SDWAOperandsMap *PotentialMatches=nullptr) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86f2900b76b99dd19e12c819c5449cd">convertToSDWA</a> (MachineInstr &amp;MI, const SIInstrInfo *TII) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509e8f9a7308d84ece391cd80de5cff1">getDstSel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6">DstUnused</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54c3dc38b186c4cb96257f50bd9a86f">getDstUnused</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213e8ef31e225fbef1972c4fe2610aa5">print</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67aaa2a4fe55d8bf62272b287c52d00">DstSel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6">DstUnused</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7acf3ff91d9656a1da60ce7b3ee225c8">DstUn</a></td>
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


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SDWADstOperand() {#a8cc566f341eefa0781239ca4da66e76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::SDWADstOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * TargetOp, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * ReplacedOp, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0a">SdwaSel</a> DstSel_=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">DWORD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6">DstUnused</a> DstUn_=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6aa32d1badbd5e9ff382591dfe33772591">UNUSED_PAD</a>)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">llvm::AMDGPU::SDWA::DWORD</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#ac837226d2f0817f52497e4f8a05f027f">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::SDWAOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6aa32d1badbd5e9ff382591dfe33772591">llvm::AMDGPU::SDWA::UNUSED_PAD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand/#a7eb7450a08fb8d9eda5f50524db47281">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::SDWADstPreserveOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertToSDWA() {#ae86f2900b76b99dd19e12c819c5449cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDWADstOperand::convertToSDWA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">llvm::AMDGPU::SDWA::DWORD</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="#a509e8f9a7308d84ece391cd80de5cff1">getDstSel</a>, <a href="#af54c3dc38b186c4cb96257f50bd9a86f">getDstUnused</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a5bfbd2de15729b28a19c4816c280878a">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getParentInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#ac1298e19de485440c2caeb29b9e63609">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getReplacedOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a2a655c25bfbbaa657d430fe07389c0ce">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getTargetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a5c223bc99892ed1d57b7050b97ffca91">isSameReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand/#a9899e618878cac6bb75eafe4d46810f4">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::convertToSDWA</a>.</p>

</div>
</div>

### getDstSel() {#a509e8f9a7308d84ece391cd80de5cff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SdwaSel anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::getDstSel ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>Referenced by <a href="#ae86f2900b76b99dd19e12c819c5449cd">convertToSDWA</a>, <a href="#a213e8ef31e225fbef1972c4fe2610aa5">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand/#a986e46cf2ebea176ec667cd87e91a46c">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::print</a>.</p>

</div>
</div>

### getDstUnused() {#af54c3dc38b186c4cb96257f50bd9a86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DstUnused anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::getDstUnused ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>Referenced by <a href="#ae86f2900b76b99dd19e12c819c5449cd">convertToSDWA</a> and <a href="#a213e8ef31e225fbef1972c4fe2610aa5">print</a>.</p>

</div>
</div>

### potentialToConvert() {#a2cbad20def038be01a642ef5bc5a0360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SDWADstOperand::potentialToConvert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/namespaces/anonymous-sipeepholesdwa-cpp-/#aa998279f86784f6bbf2a88d25d051172">SDWAOperandsMap</a> * PotentialMatches=nullptr)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a1d85560fff9b526eda51892cd899e098">findSingleRegDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a0c6990b6699e777df2f4021f237cbc5e">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a5bfbd2de15729b28a19c4816c280878a">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getParentInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#ac1298e19de485440c2caeb29b9e63609">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getReplacedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### print() {#a213e8ef31e225fbef1972c4fe2610aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDWADstOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="#a509e8f9a7308d84ece391cd80de5cff1">getDstSel</a>, <a href="#af54c3dc38b186c4cb96257f50bd9a86f">getDstUnused</a> and <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a2a655c25bfbbaa657d430fe07389c0ce">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getTargetOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DstSel {#aa67aaa2a4fe55d8bf62272b287c52d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SdwaSel anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::DstSel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>

</div>
</div>

### DstUn {#a7acf3ff91d9656a1da60ce7b3ee225c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DstUnused anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::DstUn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
