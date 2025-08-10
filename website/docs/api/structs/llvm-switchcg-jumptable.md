---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/switchcg/jumptable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `JumpTable` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::SwitchCG::JumpTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">llvm/CodeGen/SwitchLoweringUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc72d39f36310199d3c245d129cd3b8">JumpTable</a> (Register R, unsigned J, MachineBasicBlock *M, MachineBasicBlock *D, std::optional&lt; SDLoc &gt; SL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aae69d18d61ae2edd245cfd09649dab">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The virtual register containing the index of the jump table entry to jump to. <a href="#a0aae69d18d61ae2edd245cfd09649dab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f130e5f025a2c6aa66e3048d772a9a">JTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The JumpTableIndex for this jump table in the function. <a href="#a47f130e5f025a2c6aa66e3048d772a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792ccaf7e1548c2a8c804112cca75bb1">MBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The MBB into which to emit the code for the indirect jump. <a href="#a792ccaf7e1548c2a8c804112cca75bb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dda6a3c6d97db67ae344cbe8d5a2842">Default</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The MBB of the default bb, which is a successor of the range check MBB. <a href="#a1dda6a3c6d97db67ae344cbe8d5a2842">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f65724ee11fe49305d69aad1a1c954">SL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The debug location of the instruction this <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptable">JumpTable</a> was produced from. <a href="#af4f65724ee11fe49305d69aad1a1c954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### JumpTable() {#acfc72d39f36310199d3c245d129cd3b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwitchCG::JumpTable::JumpTable (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, unsigned J, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * M, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * D, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &gt; SL)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a1dda6a3c6d97db67ae344cbe8d5a2842">Default</a>, <a href="#a47f130e5f025a2c6aa66e3048d772a9a">JTI</a>, <a href="#a792ccaf7e1548c2a8c804112cca75bb1">MBB</a>, <a href="#a0aae69d18d61ae2edd245cfd09649dab">Reg</a> and <a href="#af4f65724ee11fe49305d69aad1a1c954">SL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Default {#a1dda6a3c6d97db67ae344cbe8d5a2842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SwitchCG::JumpTable::Default</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The MBB of the default bb, which is a successor of the range check MBB.</p>


<p>This is when updating PHI nodes in successors.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#acfc72d39f36310199d3c245d129cd3b8">JumpTable</a>.</p>

</div>
</div>

### JTI {#a47f130e5f025a2c6aa66e3048d772a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwitchCG::JumpTable::JTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The JumpTableIndex for this jump table in the function.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#acfc72d39f36310199d3c245d129cd3b8">JumpTable</a>.</p>

</div>
</div>

### MBB {#a792ccaf7e1548c2a8c804112cca75bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SwitchCG::JumpTable::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The MBB into which to emit the code for the indirect jump.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#acfc72d39f36310199d3c245d129cd3b8">JumpTable</a>.</p>

</div>
</div>

### Reg {#a0aae69d18d61ae2edd245cfd09649dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SwitchCG::JumpTable::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The virtual register containing the index of the jump table entry to jump to.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#acfc72d39f36310199d3c245d129cd3b8">JumpTable</a>.</p>

</div>
</div>

### SL {#af4f65724ee11fe49305d69aad1a1c954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;SDLoc&gt; llvm::SwitchCG::JumpTable::SL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The debug location of the instruction this <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptable">JumpTable</a> was produced from.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#acfc72d39f36310199d3c245d129cd3b8">JumpTable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
