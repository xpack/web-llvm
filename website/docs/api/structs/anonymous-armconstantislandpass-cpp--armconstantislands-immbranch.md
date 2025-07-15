---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-armconstantislandpass-cpp-/armconstantislands/immbranch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ImmBranch` Struct Reference

<p>ImmBranch - One per immediate branch, keeping the machine instruction pointer, conditional or unconditional, the max displacement, and (if isCond is true) the corresponding unconditional branch opcode. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ImmBranch { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49110bedbc851a5b9ed342dbd2517348">ImmBranch</a> (MachineInstr *mi, unsigned maxdisp, bool cond, unsigned ubr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d75478897fdd2a9c61bca55479fe15">MI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b958a1ab5480b24726c40f010c83c1">MaxDisp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e76883357b021366f4b242153e4c4f9">isCond</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64e402a23c3759f93e2d6aa497b60fb">UncondBr</a></td>
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

<p>ImmBranch - One per immediate branch, keeping the machine instruction pointer, conditional or unconditional, the max displacement, and (if isCond is true) the corresponding unconditional branch opcode.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ImmBranch() {#a49110bedbc851a5b9ed342dbd2517348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ImmBranch::ImmBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * mi, unsigned maxdisp, bool cond, unsigned ubr)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### isCond {#a5e76883357b021366f4b242153e4c4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ImmBranch::isCond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MaxDisp {#a71b958a1ab5480b24726c40f010c83c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ImmBranch::MaxDisp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### MI {#a64d75478897fdd2a9c61bca55479fe15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ImmBranch::MI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

### UncondBr {#ae64e402a23c3759f93e2d6aa497b60fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::ImmBranch::UncondBr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp">ARMConstantIslandPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
