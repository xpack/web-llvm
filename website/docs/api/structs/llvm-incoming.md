---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/incoming
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Incoming` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> for lane maks phi as machine instruction, incoming register <span class="doxyComputerOutput">Reg</span> and incoming block <span class="doxyComputerOutput">Block</span> are taken from machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Incoming { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">Target/AMDGPU/SILowerI1Copies.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58bc441bdf9da355b3394b9fb003d69">Incoming</a> (Register Reg, MachineBasicBlock *Block, Register UpdatedReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0311bdcdd42cf92009abbc6c209df6">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff0731632db5e52bc5ea3fdba5dbd8d">Block</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf98eddaedb122096fd002bc09fc9b76">UpdatedReg</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> for lane maks phi as machine instruction, incoming register <span class="doxyComputerOutput">Reg</span> and incoming block <span class="doxyComputerOutput">Block</span> are taken from machine instruction.</p>


<p><span class="doxyComputerOutput">UpdatedReg</span> (if valid) is <span class="doxyComputerOutput">Reg</span> lane mask merged with another lane mask.</p>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Incoming() {#ad58bc441bdf9da355b3394b9fb003d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Incoming::Incoming (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Block, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> UpdatedReg)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>References <a href="#abff0731632db5e52bc5ea3fdba5dbd8d">Block</a>, <a href="#add0311bdcdd42cf92009abbc6c209df6">Reg</a> and <a href="#adf98eddaedb122096fd002bc09fc9b76">UpdatedReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Block {#abff0731632db5e52bc5ea3fdba5dbd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::Incoming::Block</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/phiincominganalysis/#a223f44f36f65f70b6e7f23b59baffd15">anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::analyze</a>, <a href="#ad58bc441bdf9da355b3394b9fb003d69">Incoming</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a>.</p>

</div>
</div>

### Reg {#add0311bdcdd42cf92009abbc6c209df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::Incoming::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="#ad58bc441bdf9da355b3394b9fb003d69">Incoming</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a>.</p>

</div>
</div>

### UpdatedReg {#adf98eddaedb122096fd002bc09fc9b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::Incoming::UpdatedReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a>.</p>


<p>Referenced by <a href="#ad58bc441bdf9da355b3394b9fb003d69">Incoming</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-h">SILowerI1Copies.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
