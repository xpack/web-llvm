---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinefunction/debugphiregallocpos
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DebugPHIRegallocPos` Class Reference

<p>Location of a PHI instruction that is also a debug-info variable value, for the duration of register allocation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineFunction::DebugPHIRegallocPos { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0888f168426a9f54fff9fff0daecce26">DebugPHIRegallocPos</a> (MachineBasicBlock *MBB, Register Reg, unsigned SubReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f61a3b096ae5fae69f3c414c4076e8">MBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Block where this PHI was originally located. <a href="#ad3f61a3b096ae5fae69f3c414c4076e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0faa1268cb2c0bf46b928cb1ee343586">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VReg where the control-flow-merge happens. <a href="#a0faa1268cb2c0bf46b928cb1ee343586">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d75380207a6ca6becd8a21ab33700e">SubReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional subreg qualifier within Reg. <a href="#a79d75380207a6ca6becd8a21ab33700e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Location of a PHI instruction that is also a debug-info variable value, for the duration of register allocation.</p>


<p>Loaded by the PHI-elimination pass, and emitted as DBG_PHI instructions during VirtRegRewriter, with maintenance applied by intermediate passes that edit registers (such as coalescing and the allocator passes).</p>


<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugPHIRegallocPos() {#a0888f168426a9f54fff9fff0daecce26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineFunction::DebugPHIRegallocPos::DebugPHIRegallocPos (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned SubReg)</td>
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



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="#ad3f61a3b096ae5fae69f3c414c4076e8">MBB</a>, <a href="#a0faa1268cb2c0bf46b928cb1ee343586">Reg</a> and <a href="#a79d75380207a6ca6becd8a21ab33700e">SubReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MBB {#ad3f61a3b096ae5fae69f3c414c4076e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::MachineFunction::DebugPHIRegallocPos::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Block where this PHI was originally located.</p>

<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="#a0888f168426a9f54fff9fff0daecce26">DebugPHIRegallocPos</a>.</p>

</div>
</div>

### Reg {#a0faa1268cb2c0bf46b928cb1ee343586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::MachineFunction::DebugPHIRegallocPos::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VReg where the control-flow-merge happens.</p>

<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="#a0888f168426a9f54fff9fff0daecce26">DebugPHIRegallocPos</a>.</p>

</div>
</div>

### SubReg {#a79d75380207a6ca6becd8a21ab33700e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineFunction::DebugPHIRegallocPos::SubReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optional subreg qualifier within Reg.</p>

<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="#a0888f168426a9f54fff9fff0daecce26">DebugPHIRegallocPos</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
