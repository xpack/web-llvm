---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcoperandinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCOperandInfo` Class Reference

<p>This holds information about one operand of a machine instruction, indicating the register class for register operands, etc. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCOperandInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa06263df7b83bda632ddd30a94436f36">isLookupPtrRegClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if this operand is a pointer value and it requires a callback to look up its register class. <a href="#aa06263df7b83bda632ddd30a94436f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade84daa4d8f66c88a1b29d060c088474">isPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if this is one of the operands that made up of the predicate operand that controls an isPredicable() instruction. <a href="#ade84daa4d8f66c88a1b29d060c088474">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560b9033e7d2c267cf51dbf4244ecf10">isOptionalDef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if this operand is a optional def. <a href="#a560b9033e7d2c267cf51dbf4244ecf10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645052256fc8dcac496a22893a49a0ce">isBranchTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if this operand is a branch target. <a href="#a645052256fc8dcac496a22893a49a0ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad95d345f2d5b7df2949328fb02b44e28">isGenericType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41442bb3685624e934583206ea432ac9">getGenericTypeIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1638924a550d2ff67480600ecded509">isGenericImm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b6f01b343333fe66f541a2e51e57d9">getGenericImmIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3abf78805559fecd7642d0c57032c56">RegClass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This specifies the register class enumeration of the operand if the operand is a register. <a href="#ad3abf78805559fecd7642d0c57032c56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7ac8273e4047b06765295253bea8d7">Flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are flags from the <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#a998e4790d0be1c768cbd5bb476686876">MCOI::OperandFlags</a> enum. <a href="#aae7ac8273e4047b06765295253bea8d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9173ff0e651bbc7ce633a7c4b83d9586">OperandType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about the type of the operand. <a href="#a9173ff0e651bbc7ce633a7c4b83d9586">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8505d3393e96652f88958b860e42197a">Constraints</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Operand constraints (see OperandConstraint enum). <a href="#a8505d3393e96652f88958b860e42197a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This holds information about one operand of a machine instruction, indicating the register class for register operands, etc.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getGenericImmIndex() {#a62b6f01b343333fe66f541a2e51e57d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCOperandInfo::getGenericImmIndex ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1638924a550d2ff67480600ecded509">isGenericImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96dabc8440cd13a43eecdbd002b4f2779140">llvm::MCOI::OPERAND_FIRST_GENERIC_IMM</a> and <a href="#a9173ff0e651bbc7ce633a7c4b83d9586">OperandType</a>.</p>

</div>
</div>

### getGenericTypeIndex() {#a41442bb3685624e934583206ea432ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCOperandInfo::getGenericTypeIndex ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad95d345f2d5b7df2949328fb02b44e28">isGenericType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da9c1b4fee0481848b7ede086f9bba9ded">llvm::MCOI::OPERAND_FIRST_GENERIC</a> and <a href="#a9173ff0e651bbc7ce633a7c4b83d9586">OperandType</a>.</p>

</div>
</div>

### isBranchTarget() {#a645052256fc8dcac496a22893a49a0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCOperandInfo::isBranchTarget ()</td>
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

<p>Set if this operand is a branch target.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#a998e4790d0be1c768cbd5bb476686876a7214f80b52abfda8216712827a8743a4">llvm::MCOI::BranchTarget</a> and <a href="#aae7ac8273e4047b06765295253bea8d7">Flags</a>.</p>

</div>
</div>

### isGenericImm() {#ad1638924a550d2ff67480600ecded509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCOperandInfo::isGenericImm ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96dabc8440cd13a43eecdbd002b4f2779140">llvm::MCOI::OPERAND_FIRST_GENERIC_IMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96dac75b98f7dd3d0cfc2a89eed680e66f27">llvm::MCOI::OPERAND_LAST_GENERIC_IMM</a> and <a href="#a9173ff0e651bbc7ce633a7c4b83d9586">OperandType</a>.</p>


<p>Referenced by <a href="#a62b6f01b343333fe66f541a2e51e57d9">getGenericImmIndex</a>.</p>

</div>
</div>

### isGenericType() {#ad95d345f2d5b7df2949328fb02b44e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCOperandInfo::isGenericType ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da9c1b4fee0481848b7ede086f9bba9ded">llvm::MCOI::OPERAND_FIRST_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da8b1f03c574eba95352f9e531dbad42b4">llvm::MCOI::OPERAND_LAST_GENERIC</a> and <a href="#a9173ff0e651bbc7ce633a7c4b83d9586">OperandType</a>.</p>


<p>Referenced by <a href="#a41442bb3685624e934583206ea432ac9">getGenericTypeIndex</a>.</p>

</div>
</div>

### isLookupPtrRegClass() {#aa06263df7b83bda632ddd30a94436f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCOperandInfo::isLookupPtrRegClass ()</td>
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

<p>Set if this operand is a pointer value and it requires a callback to look up its register class.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#aae7ac8273e4047b06765295253bea8d7">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#a998e4790d0be1c768cbd5bb476686876a3f4613c966a25662474f5d1645af6b00">llvm::MCOI::LookupPtrRegClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>.</p>

</div>
</div>

### isOptionalDef() {#a560b9033e7d2c267cf51dbf4244ecf10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCOperandInfo::isOptionalDef ()</td>
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

<p>Set if this operand is a optional def.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#aae7ac8273e4047b06765295253bea8d7">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#a998e4790d0be1c768cbd5bb476686876a45389b0b54f87d8dd6451e607463e2f1">llvm::MCOI::OptionalDef</a>.</p>

</div>
</div>

### isPredicate() {#ade84daa4d8f66c88a1b29d060c088474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCOperandInfo::isPredicate ()</td>
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

<p>Set if this is one of the operands that made up of the predicate operand that controls an isPredicable() instruction.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#aae7ac8273e4047b06765295253bea8d7">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#a998e4790d0be1c768cbd5bb476686876ab1461a089ae820c837ae97bc8c612dc8">llvm::MCOI::Predicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Constraints {#a8505d3393e96652f88958b860e42197a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCOperandInfo::Constraints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Operand constraints (see OperandConstraint enum).</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>.</p>

</div>
</div>

### Flags {#aae7ac8273e4047b06765295253bea8d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MCOperandInfo::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These are flags from the <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#a998e4790d0be1c768cbd5bb476686876">MCOI::OperandFlags</a> enum.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a645052256fc8dcac496a22893a49a0ce">isBranchTarget</a>, <a href="#aa06263df7b83bda632ddd30a94436f36">isLookupPtrRegClass</a>, <a href="#a560b9033e7d2c267cf51dbf4244ecf10">isOptionalDef</a> and <a href="#ade84daa4d8f66c88a1b29d060c088474">isPredicate</a>.</p>

</div>
</div>

### OperandType {#a9173ff0e651bbc7ce633a7c4b83d9586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MCOperandInfo::OperandType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information about the type of the operand.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#abe6772bd0f8b4b1bc3186473a7205dfe">llvm::RISCVInstrInfo::createMIROperandComment</a>, <a href="#a62b6f01b343333fe66f541a2e51e57d9">getGenericImmIndex</a>, <a href="#a41442bb3685624e934583206ea432ac9">getGenericTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adddee5b33e7c032620042dfdb9fa1634">llvm::AMDGPU::getOperandSize</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0df02605d5e00cad00c3b7f4aef3aa14">llvm::SIInstrInfo::getOpSize</a>, <a href="#ad1638924a550d2ff67480600ecded509">isGenericImm</a>, <a href="#ad95d345f2d5b7df2949328fb02b44e28">isGenericType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a835ce544e7ae111f1889501136ea6b3d">llvm::SIInstrInfo::isImmOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a937968cca64524eb49e6b3ae31398da7">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#acbbc2f6b22e0c1dfd00546ef61cc0ac3">llvm::SIInstrInfo::isLegalToSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a7ec597eb70645748d7299e7a05faa4a5">needsExpandMemInst</a>.</p>

</div>
</div>

### RegClass {#ad3abf78805559fecd7642d0c57032c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t llvm::MCOperandInfo::RegClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This specifies the register class enumeration of the operand if the operand is a register.</p>


<p>If isLookupPtrRegClass is set, then this is an index that is passed to TargetRegisterInfo::getPointerRegClass(x) to get a dynamic register class.</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0df02605d5e00cad00c3b7f4aef3aa14">llvm::SIInstrInfo::getOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a835ce544e7ae111f1889501136ea6b3d">llvm::SIInstrInfo::isImmOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#acbbc2f6b22e0c1dfd00546ef61cc0ac3">llvm::SIInstrInfo::isLegalToSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
