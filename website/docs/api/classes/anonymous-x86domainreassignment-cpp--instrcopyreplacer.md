---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86domainreassignment-cpp-/instrcopyreplacer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrCOPYReplacer` Class Reference

<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter for replacing COPY instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer">InstrReplacer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter which replaces an instruction with another. <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b14eef5eef546bf941967abf3a4a2a8">InstrCOPYReplacer</a> (unsigned SrcOpcode, RegDomain DstDomain, unsigned DstOpcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9856bdc6cd6e8cadf3b67fad21cb839">isLegal</a> (const MachineInstr *MI, const TargetInstrInfo *TII) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41fe5aa8ec20faee496a25bcb9d764d8">getExtraCost</a> (const MachineInstr *MI, MachineRegisterInfo *MRI) const override</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a5591a13a87c6247cd8404d747136716a">RegDomain</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53450a04c86e7c6e2796b66cc539a0a2">DstDomain</a></td>
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

<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter for replacing COPY instructions.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrCOPYReplacer() {#a7b14eef5eef546bf941967abf3a4a2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer::InstrCOPYReplacer (unsigned SrcOpcode, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a5591a13a87c6247cd8404d747136716a">RegDomain</a> DstDomain, unsigned DstOpcode)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="#a53450a04c86e7c6e2796b66cc539a0a2">DstDomain</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer/#af0ff31fc6d79dfba75a83711417ebaaa">anonymous{X86DomainReassignment.cpp}::InstrReplacer::DstOpcode</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer/#a152c712261b073bd315324f416be3bc2">anonymous{X86DomainReassignment.cpp}::InstrReplacer::InstrReplacer</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase/#ab04f41858eb348f66a91224d1b4f19a1">anonymous{X86DomainReassignment.cpp}::InstrConverterBase::SrcOpcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExtraCost() {#a41fe5aa8ec20faee496a25bcb9d764d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer::getExtraCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
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


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a53450a04c86e7c6e2796b66cc539a0a2">DstDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a8c825d8718637fb081db2cf8fbade190">getDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isLegal() {#ae9856bdc6cd6e8cadf3b67fad21cb839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer::isLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
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
<dd><p>true if <span class="doxyComputerOutput">MI</span> is legal to convert.</p></dd>
</dl>


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase/#adf87f482d23e11802eaedb7b44efa253">anonymous{X86DomainReassignment.cpp}::InstrConverterBase::isLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DstDomain {#a53450a04c86e7c6e2796b66cc539a0a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegDomain anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer::DstDomain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>Referenced by <a href="#a41fe5aa8ec20faee496a25bcb9d764d8">getExtraCost</a> and <a href="#a7b14eef5eef546bf941967abf3a4a2a8">InstrCOPYReplacer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
