---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86domainreassignment-cpp-/instrignore
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrIgnore` Class

<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter which ignores the given instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86DomainReassignment.cpp}::InstrIgnore { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase">InstrConverterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter class. <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07eba1bed09f0286654d76a715c3f203">InstrIgnore</a> (unsigned SrcOpcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a969ac489b17e53afc77b4a95058bc3e5">convertInstr</a> (MachineInstr *MI, const TargetInstrInfo *TII, MachineRegisterInfo *MRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Applies conversion to <span class="doxyComputerOutput">MI</span>. <a href="#a969ac489b17e53afc77b4a95058bc3e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48991537e1d24358ecc67d4466507d63">getExtraCost</a> (const MachineInstr *MI, MachineRegisterInfo *MRI) const override</td>
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

<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter which ignores the given instruction.</p>


<p>For example, PHI instructions can be safely ignored since only the registers need to change.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrIgnore() {#a07eba1bed09f0286654d76a715c3f203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86DomainReassignment.cpp}::InstrIgnore::InstrIgnore (unsigned SrcOpcode)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase/#adeccf0370e28d8967d63b6d88e05801a">anonymous{X86DomainReassignment.cpp}::InstrConverterBase::InstrConverterBase</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase/#ab04f41858eb348f66a91224d1b4f19a1">anonymous{X86DomainReassignment.cpp}::InstrConverterBase::SrcOpcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertInstr() {#a969ac489b17e53afc77b4a95058bc3e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86DomainReassignment.cpp}::InstrIgnore::convertInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Applies conversion to <span class="doxyComputerOutput">MI</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> is no longer need, and can be deleted.</p></dd>
</dl>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase/#adf87f482d23e11802eaedb7b44efa253">anonymous{X86DomainReassignment.cpp}::InstrConverterBase::isLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getExtraCost() {#a48991537e1d24358ecc67d4466507d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{X86DomainReassignment.cpp}::InstrIgnore::getExtraCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the cost increment incurred by converting <span class="doxyComputerOutput">MI</span>.</p></dd>
</dl>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
