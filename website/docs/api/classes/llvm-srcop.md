---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/srcop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SrcOp` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SrcOp { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SrcType { <a href="#a0173b34b2346b5bfdfb06974b064c857">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae684a1374d2f42a216669bfa033019ab">SrcOp</a> (Register R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6031fcd0b2c94eb19266aaebea9d13e">SrcOp</a> (const MachineOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ae122c8e0e4e469b53f823a1164175">SrcOp</a> (const MachineInstrBuilder &amp;MIB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5473011c1eb76a579bebf6313df5a70b">SrcOp</a> (const CmpInst::Predicate P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd0fb07337450cd9b6f5e3277b13190">SrcOp</a> (unsigned)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> of registers held in unsigned integer variables (or more rarely signed integers) is no longer permitted to avoid ambiguity with upcoming support for immediates. <a href="#abbd0fb07337450cd9b6f5e3277b13190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0b34b1a83f63c128677f1e7223b413">SrcOp</a> (int)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a2e8ae2a27e830498b44b042e52e55">SrcOp</a> (uint64_t V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a478b48de2e1a8f7f0a9f28b6922d22d7">SrcOp</a> (int64_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba93d72255e1239b5209e416a1b7f199">addSrcToMIB</a> (MachineInstrBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fb11458708b57172b6b0df633fd4fc">getLLTTy</a> (const MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae229785d0c8a8ce25d34be18fe150a54">getReg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d76542b7eea45464c3b891c8921b9c8">getPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9370c0de85c12bd0062063b7fcbc64ed">getImm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0173b34b2346b5bfdfb06974b064c857">SrcType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ee9b6cd91527c0ea1464be0f230ded">getSrcOpKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd8d667de3ee1caae80ea2f47b5ee3d">SrcMIB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99215d9557990d1d976f28618ecd792a">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4697e1dbfe5081dfac5a165f35afe4">Pred</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067e0e205c00f8c74dcc209ba216eec1">Imm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/srcop">llvm::SrcOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6a0a0116c9939c9f38901821c33501"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0173b34b2346b5bfdfb06974b064c857">SrcType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30fbf9e578e71e15871af0d2899df48">Ty</a></td>
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


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SrcType {#a0173b34b2346b5bfdfb06974b064c857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::SrcOp::SrcType </td>
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
<td class="doxyEnumItemName">Ty_Reg<a id="a0173b34b2346b5bfdfb06974b064c857aba90cf184fd0f4eddf476f0f1a18a680"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ty_MIB<a id="a0173b34b2346b5bfdfb06974b064c857a1352e1646112ffafb502c772e62c4ebf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ty_Predicate<a id="a0173b34b2346b5bfdfb06974b064c857a2d0e1304ef8d805e2c04c15c53db4e48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ty_Imm<a id="a0173b34b2346b5bfdfb06974b064c857a5c538e40b2a6bf69929364e9fc534507"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SrcOp() {#ae684a1374d2f42a216669bfa033019ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a99215d9557990d1d976f28618ecd792a">Reg</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857aba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>

</div>
</div>

### SrcOp() {#ab6031fcd0b2c94eb19266aaebea9d13e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#ae229785d0c8a8ce25d34be18fe150a54">getReg</a>, <a href="#a99215d9557990d1d976f28618ecd792a">Reg</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857aba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>

</div>
</div>

### SrcOp() {#a28ae122c8e0e4e469b53f823a1164175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a6dd8d667de3ee1caae80ea2f47b5ee3d">SrcMIB</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857a1352e1646112ffafb502c772e62c4ebf">Ty_MIB</a>.</p>

</div>
</div>

### SrcOp() {#a5473011c1eb76a579bebf6313df5a70b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> P)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a8a4697e1dbfe5081dfac5a165f35afe4">Pred</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857a2d0e1304ef8d805e2c04c15c53db4e48">Ty_Predicate</a>.</p>

</div>
</div>

### SrcOp() {#abbd0fb07337450cd9b6f5e3277b13190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (unsigned)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> of registers held in unsigned integer variables (or more rarely signed integers) is no longer permitted to avoid ambiguity with upcoming support for immediates.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### SrcOp() {#a6d0b34b1a83f63c128677f1e7223b413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (int)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### SrcOp() {#a68a2e8ae2a27e830498b44b042e52e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (uint64_t V)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a067e0e205c00f8c74dcc209ba216eec1">Imm</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857a5c538e40b2a6bf69929364e9fc534507">Ty_Imm</a>.</p>

</div>
</div>

### SrcOp() {#a478b48de2e1a8f7f0a9f28b6922d22d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SrcOp::SrcOp (int64_t V)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a067e0e205c00f8c74dcc209ba216eec1">Imm</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857a5c538e40b2a6bf69929364e9fc534507">Ty_Imm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSrcToMIB() {#aba93d72255e1239b5209e416a1b7f199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SrcOp::addSrcToMIB (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6d40d83c14042582354b5d875ed7f2d8">llvm::MachineInstrBuilder::addPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="#a067e0e205c00f8c74dcc209ba216eec1">Imm</a>, <a href="#a8a4697e1dbfe5081dfac5a165f35afe4">Pred</a>, <a href="#a99215d9557990d1d976f28618ecd792a">Reg</a>, <a href="#a6dd8d667de3ee1caae80ea2f47b5ee3d">SrcMIB</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a5c538e40b2a6bf69929364e9fc534507">Ty_Imm</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a1352e1646112ffafb502c772e62c4ebf">Ty_MIB</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a2d0e1304ef8d805e2c04c15c53db4e48">Ty_Predicate</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857aba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adbf5d6125fa84e067907320d93e9fab5">llvm::MachineIRBuilder::buildAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acc22ffc46525708d66c036f878572523">llvm::MachineIRBuilder::buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a497e8884b8ae421c7dadff0f0eea5e3e">llvm::MachineIRBuilder::buildAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6e0f051c17bd6354aec061d308d80841">llvm::MachineIRBuilder::buildBrCond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeede510b1aaac978daaba60dcc2817de">llvm::MachineIRBuilder::buildLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeacc7cca9ff75b34872d7f7099d4261e">llvm::MachineIRBuilder::buildPrefetch</a> and <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a87a7405685118d45876c996318829ceb">llvm::MachineIRBuilder::buildStore</a>.</p>

</div>
</div>

### getImm() {#a9370c0de85c12bd0062063b7fcbc64ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::SrcOp::getImm ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a067e0e205c00f8c74dcc209ba216eec1">Imm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857a5c538e40b2a6bf69929364e9fc534507">Ty_Imm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad8e9b54f022eddc33ee49305e85d6b7f">llvm::SIInstrInfo::expandMovDPP64</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>.</p>

</div>
</div>

### getLLTTy() {#a99fb11458708b57172b6b0df633fd4fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::SrcOp::getLLTTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a99215d9557990d1d976f28618ecd792a">Reg</a>, <a href="#a6dd8d667de3ee1caae80ea2f47b5ee3d">SrcMIB</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a5c538e40b2a6bf69929364e9fc534507">Ty_Imm</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a1352e1646112ffafb502c772e62c4ebf">Ty_MIB</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a2d0e1304ef8d805e2c04c15c53db4e48">Ty_Predicate</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857aba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adbf5d6125fa84e067907320d93e9fab5">llvm::MachineIRBuilder::buildAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acc22ffc46525708d66c036f878572523">llvm::MachineIRBuilder::buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a497e8884b8ae421c7dadff0f0eea5e3e">llvm::MachineIRBuilder::buildAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6e0f051c17bd6354aec061d308d80841">llvm::MachineIRBuilder::buildBrCond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeede510b1aaac978daaba60dcc2817de">llvm::MachineIRBuilder::buildLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7aae2634e3c0980c4f68983738b90ff7">llvm::MachineIRBuilder::buildPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aded2b440bea348970816da1ecd40f2c1">llvm::MachineIRBuilder::buildShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a87a7405685118d45876c996318829ceb">llvm::MachineIRBuilder::buildStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aea1b43a8ad482493c4b6898bf120a176">llvm::MachineIRBuilder::buildStore</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a92bad93a924413adf3652db02e467a21">llvm::LegalizerHelper::createStackStoreLoad</a>.</p>

</div>
</div>

### getPredicate() {#a7d76542b7eea45464c3b891c8921b9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate llvm::SrcOp::getPredicate ()</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a8a4697e1dbfe5081dfac5a165f35afe4">Pred</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857a2d0e1304ef8d805e2c04c15c53db4e48">Ty_Predicate</a>.</p>

</div>
</div>

### getReg() {#ae229785d0c8a8ce25d34be18fe150a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SrcOp::getReg ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a99215d9557990d1d976f28618ecd792a">Reg</a>, <a href="#a6dd8d667de3ee1caae80ea2f47b5ee3d">SrcMIB</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a5c538e40b2a6bf69929364e9fc534507">Ty_Imm</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a1352e1646112ffafb502c772e62c4ebf">Ty_MIB</a>, <a href="#a0173b34b2346b5bfdfb06974b064c857a2d0e1304ef8d805e2c04c15c53db4e48">Ty_Predicate</a> and <a href="#a0173b34b2346b5bfdfb06974b064c857aba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a77d3589f9460c3f08bc6afc49a9985c6">buildSplatSplitS64WithVL</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad049a79d46df2c25561d90e9d80fb5e3">convertImageAddrToPacked</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo/#a5132c278b17bb5c9fdf3f3af76250b2a">llvm::SPIRVInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad8e9b54f022eddc33ee49305e85d6b7f">llvm::SIInstrInfo::expandMovDPP64</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#aba8269780a1b283db0509e18d3f99d92">llvm::AMDGPURegisterBankInfo::getDefaultMappingSOP</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8e8f884db0a3faadefc981023902a1ec">llvm::SIInstrInfo::getInstructionUniformity</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#afbd23f1436bf2680a83324a63b37dbe4">anonymous{HexagonRDFOpt.cpp}::HexagonCP::interpretAsCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#aaa2bd04c34b59b5b2a2c0189c58bc55b">isCopyOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0022aa73e6337684561159d1f7929966">packImage16bitOpsToDwords</a>, <a href="#ab6031fcd0b2c94eb19266aaebea9d13e">SrcOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getSrcOpKind() {#a83ee9b6cd91527c0ea1464be0f230ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SrcType llvm::SrcOp::getSrcOpKind ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Imm {#a067e0e205c00f8c74dcc209ba216eec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::SrcOp::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#aba93d72255e1239b5209e416a1b7f199">addSrcToMIB</a>, <a href="#a9370c0de85c12bd0062063b7fcbc64ed">getImm</a>, <a href="#a478b48de2e1a8f7f0a9f28b6922d22d7">SrcOp</a> and <a href="#a68a2e8ae2a27e830498b44b042e52e55">SrcOp</a>.</p>

</div>
</div>

### Pred {#a8a4697e1dbfe5081dfac5a165f35afe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate llvm::SrcOp::Pred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#aba93d72255e1239b5209e416a1b7f199">addSrcToMIB</a>, <a href="#a7d76542b7eea45464c3b891c8921b9c8">getPredicate</a> and <a href="#a5473011c1eb76a579bebf6313df5a70b">SrcOp</a>.</p>

</div>
</div>

### Reg {#a99215d9557990d1d976f28618ecd792a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SrcOp::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#aba93d72255e1239b5209e416a1b7f199">addSrcToMIB</a>, <a href="#a99fb11458708b57172b6b0df633fd4fc">getLLTTy</a>, <a href="#ae229785d0c8a8ce25d34be18fe150a54">getReg</a>, <a href="#ab6031fcd0b2c94eb19266aaebea9d13e">SrcOp</a> and <a href="#ae684a1374d2f42a216669bfa033019ab">SrcOp</a>.</p>

</div>
</div>

### SrcMIB {#a6dd8d667de3ee1caae80ea2f47b5ee3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::SrcOp::SrcMIB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#aba93d72255e1239b5209e416a1b7f199">addSrcToMIB</a>, <a href="#a99fb11458708b57172b6b0df633fd4fc">getLLTTy</a>, <a href="#ae229785d0c8a8ce25d34be18fe150a54">getReg</a> and <a href="#a28ae122c8e0e4e469b53f823a1164175">SrcOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#aaf6a0a0116c9939c9f38901821c33501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SrcOp llvm::SrcOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### Ty {#ae30fbf9e578e71e15871af0d2899df48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SrcType llvm::SrcOp::Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
