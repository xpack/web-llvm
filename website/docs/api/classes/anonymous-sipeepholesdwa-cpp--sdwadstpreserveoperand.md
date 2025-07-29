---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SDWADstPreserveOperand` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand">SDWADstOperand</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb7450a08fb8d9eda5f50524db47281">SDWADstPreserveOperand</a> (MachineOperand *TargetOp, MachineOperand *ReplacedOp, MachineOperand *PreserveOp, SdwaSel DstSel_=DWORD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9899e618878cac6bb75eafe4d46810f4">convertToSDWA</a> (MachineInstr &amp;MI, const SIInstrInfo *TII) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa285274b6554e01b7a2b86959b0b93a0">getPreservedOperand</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a986e46cf2ebea176ec667cd87e91a46c">print</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a289041fb50b7c40b789495cbaa907430">Preserve</a></td>
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


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SDWADstPreserveOperand() {#a7eb7450a08fb8d9eda5f50524db47281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::SDWADstPreserveOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * TargetOp, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * ReplacedOp, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * PreserveOp, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0a">SdwaSel</a> DstSel_=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">DWORD</a>)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">llvm::AMDGPU::SDWA::DWORD</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand/#a8cc566f341eefa0781239ca4da66e76d">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::SDWADstOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6a58f19664e2b69107495d2085514f7874">llvm::AMDGPU::SDWA::UNUSED_PRESERVE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertToSDWA() {#a9899e618878cac6bb75eafe4d46810f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDWADstPreserveOperand::convertToSDWA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a3da9727b1d452d6dcab08fde547ab634">llvm::MachineRegisterInfo::clearKillFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand/#ae86f2900b76b99dd19e12c819c5449cd">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a0c6990b6699e777df2f4021f237cbc5e">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getMRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a5bfbd2de15729b28a19c4816c280878a">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getParentInst</a>, <a href="#aa285274b6554e01b7a2b86959b0b93a0">getPreservedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acff74dc04327bef6824ecb2e3648d0f0">llvm::RegState::ImplicitKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getPreservedOperand() {#aa285274b6554e01b7a2b86959b0b93a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::getPreservedOperand ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>Referenced by <a href="#a9899e618878cac6bb75eafe4d46810f4">convertToSDWA</a> and <a href="#a986e46cf2ebea176ec667cd87e91a46c">print</a>.</p>

</div>
</div>

### print() {#a986e46cf2ebea176ec667cd87e91a46c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDWADstPreserveOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand/#a509e8f9a7308d84ece391cd80de5cff1">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::getDstSel</a>, <a href="#aa285274b6554e01b7a2b86959b0b93a0">getPreservedOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a2a655c25bfbbaa657d430fe07389c0ce">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getTargetOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Preserve {#a289041fb50b7c40b789495cbaa907430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand* anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::Preserve</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp">SIPeepholeSDWA.cpp</a>.</p>

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
