---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vreg2sunitoperidx
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VReg2SUnitOperIdx` Struct

<p>Mapping from virtual register to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> including an operand index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VReg2SUnitOperIdx { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">llvm/CodeGen/ScheduleDAGInstrs.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vreg2sunit">VReg2SUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An individual mapping from virtual register number to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="/web-llvm/docs/api/structs/llvm/vreg2sunit/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20f8cba1a27a2ffcb64658161865a27">VReg2SUnitOperIdx</a> (unsigned VReg, LaneBitmask LaneMask, unsigned OperandIndex, SUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0bf384b273cad5dc56e2a34ef25ec9b">OperandIndex</a></td>
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

<p>Mapping from virtual register to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> including an operand index.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VReg2SUnitOperIdx() {#ae20f8cba1a27a2ffcb64658161865a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VReg2SUnitOperIdx::VReg2SUnitOperIdx (unsigned VReg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, unsigned OperandIndex, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/vreg2sunit/#a4aea32ab12cb63c145f279b7eb768203">llvm::VReg2SUnit::LaneMask</a>, <a href="#af0bf384b273cad5dc56e2a34ef25ec9b">OperandIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/vreg2sunit/#a62cea84ba15a90f1f6c497f16d8eeda3">llvm::VReg2SUnit::SU</a> and <a href="/web-llvm/docs/api/structs/llvm/vreg2sunit/#ac87037fa013ed9cc1effcc8bfcf8075e">llvm::VReg2SUnit::VReg2SUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OperandIndex {#af0bf384b273cad5dc56e2a34ef25ec9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VReg2SUnitOperIdx::OperandIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ae20f8cba1a27a2ffcb64658161865a27">VReg2SUnitOperIdx</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
