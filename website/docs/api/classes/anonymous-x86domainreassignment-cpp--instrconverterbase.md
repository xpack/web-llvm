---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86domainreassignment-cpp-/instrconverterbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrConverterBase` Class

<p>Abstract <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86DomainReassignment.cpp}::InstrConverterBase { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrignore">InstrIgnore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter which ignores the given instruction. <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrignore/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacewithcopy">InstrReplaceWithCopy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter which replaces an instruction with a COPY. <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacewithcopy/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacerdstcopy">InstrReplacerDstCOPY</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter which replaces an instruction with another, and adds a COPY from the new instruction's destination to the old one's. <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacerdstcopy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeccf0370e28d8967d63b6d88e05801a">InstrConverterBase</a> (unsigned SrcOpcode)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54062d3a6cb9e409612672d7591a0dcf">~InstrConverterBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf87f482d23e11802eaedb7b44efa253">isLegal</a> (const MachineInstr *MI, const TargetInstrInfo *TII) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe23d966c5e12e5efe7ed64bcbffba9d">convertInstr</a> (MachineInstr *MI, const TargetInstrInfo *TII, MachineRegisterInfo *MRI) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Applies conversion to <span class="doxyComputerOutput">MI</span>. <a href="#abe23d966c5e12e5efe7ed64bcbffba9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174516e304dd743a5d475cdf142ce064">getExtraCost</a> (const MachineInstr *MI, MachineRegisterInfo *MRI) const =0</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04f41858eb348f66a91224d1b4f19a1">SrcOpcode</a></td>
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

<p>Abstract <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converter class.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrConverterBase() {#adeccf0370e28d8967d63b6d88e05801a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86DomainReassignment.cpp}::InstrConverterBase::InstrConverterBase (unsigned SrcOpcode)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>Reference <a href="#ab04f41858eb348f66a91224d1b4f19a1">SrcOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrignore/#a07eba1bed09f0286654d76a715c3f203">anonymous{X86DomainReassignment.cpp}::InstrIgnore::InstrIgnore</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer/#a152c712261b073bd315324f416be3bc2">anonymous{X86DomainReassignment.cpp}::InstrReplacer::InstrReplacer</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacerdstcopy/#a57cd14ee01a4a9abeafccc1d1e8b2e2e">anonymous{X86DomainReassignment.cpp}::InstrReplacerDstCOPY::InstrReplacerDstCOPY</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacewithcopy/#aa6ad9963ed060bca7754002213fe7d0e">anonymous{X86DomainReassignment.cpp}::InstrReplaceWithCopy::InstrReplaceWithCopy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InstrConverterBase() {#a54062d3a6cb9e409612672d7591a0dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{X86DomainReassignment.cpp}::InstrConverterBase::~InstrConverterBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertInstr() {#abe23d966c5e12e5efe7ed64bcbffba9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{X86DomainReassignment.cpp}::InstrConverterBase::convertInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
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


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getExtraCost() {#a174516e304dd743a5d475cdf142ce064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual double anonymous{X86DomainReassignment.cpp}::InstrConverterBase::getExtraCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the cost increment incurred by converting <span class="doxyComputerOutput">MI</span>.</p></dd>
</dl>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isLegal() {#adf87f482d23e11802eaedb7b44efa253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{X86DomainReassignment.cpp}::InstrConverterBase::isLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
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


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ab04f41858eb348f66a91224d1b4f19a1">SrcOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrignore/#a969ac489b17e53afc77b4a95058bc3e5">anonymous{X86DomainReassignment.cpp}::InstrIgnore::convertInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacerdstcopy/#a3a3c75969a49f4cec641a3af56b4bc37">anonymous{X86DomainReassignment.cpp}::InstrReplacerDstCOPY::convertInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacewithcopy/#ae1da1f845036d0455d283680da1e614b">anonymous{X86DomainReassignment.cpp}::InstrReplaceWithCopy::convertInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrcopyreplacer/#ae9856bdc6cd6e8cadf3b67fad21cb839">anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer::isLegal</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer/#a8d0c49c0ca17d4b990caa2e9b04c7132">anonymous{X86DomainReassignment.cpp}::InstrReplacer::isLegal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### SrcOpcode {#ab04f41858eb348f66a91224d1b4f19a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86DomainReassignment.cpp}::InstrConverterBase::SrcOpcode</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>Referenced by <a href="#adeccf0370e28d8967d63b6d88e05801a">InstrConverterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrcopyreplacer/#a7b14eef5eef546bf941967abf3a4a2a8">anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer::InstrCOPYReplacer</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrignore/#a07eba1bed09f0286654d76a715c3f203">anonymous{X86DomainReassignment.cpp}::InstrIgnore::InstrIgnore</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer/#a152c712261b073bd315324f416be3bc2">anonymous{X86DomainReassignment.cpp}::InstrReplacer::InstrReplacer</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacerdstcopy/#a57cd14ee01a4a9abeafccc1d1e8b2e2e">anonymous{X86DomainReassignment.cpp}::InstrReplacerDstCOPY::InstrReplacerDstCOPY</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacewithcopy/#aa6ad9963ed060bca7754002213fe7d0e">anonymous{X86DomainReassignment.cpp}::InstrReplaceWithCopy::InstrReplaceWithCopy</a> and <a href="#adf87f482d23e11802eaedb7b44efa253">isLegal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
