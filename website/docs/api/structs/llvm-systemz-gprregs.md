---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/systemz/gprregs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GPRRegs` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::SystemZ::GPRRegs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinefunctioninfo-h">Target/SystemZ/SystemZMachineFunctionInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167ae5b7cbffd3f6d946ad277ee5a95e">GPRRegs</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f113efcd05970b283ecc2cd99a91379">LowGPR</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e605731741359de2b6b05844f8e61db">HighGPR</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a864aaacf976eb30999ce0d740e5657a5">GPROffset</a> = 0</td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinefunctioninfo-h">SystemZMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GPRRegs() {#a167ae5b7cbffd3f6d946ad277ee5a95e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SystemZ::GPRRegs::GPRRegs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinefunctioninfo-h">SystemZMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### GPROffset {#a864aaacf976eb30999ce0d740e5657a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZ::GPRRegs::GPROffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinefunctioninfo-h">SystemZMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### HighGPR {#a5e605731741359de2b6b05844f8e61db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZ::GPRRegs::HighGPR = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinefunctioninfo-h">SystemZMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### LowGPR {#a0f113efcd05970b283ecc2cd99a91379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZ::GPRRegs::LowGPR = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinefunctioninfo-h">SystemZMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a8aa8ef70d3b7b3f9c421b488302f563a">llvm::SystemZELFFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a4bd38718f81e97d49ac056306d2efbab">llvm::SystemZXPLINKFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinefunctioninfo-h">SystemZMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
