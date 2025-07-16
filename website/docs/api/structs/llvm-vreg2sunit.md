---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vreg2sunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VReg2SUnit` Struct Reference

<p>An individual mapping from virtual register number to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VReg2SUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">llvm/CodeGen/ScheduleDAGInstrs.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vreg2sunitoperidx">VReg2SUnitOperIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from virtual register to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> including an operand index. <a href="/web-llvm/docs/api/structs/llvm/vreg2sunitoperidx/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac87037fa013ed9cc1effcc8bfcf8075e">VReg2SUnit</a> (unsigned VReg, LaneBitmask LaneMask, SUnit *SU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8888c23f68696106ebdc5a796f330f49">getSparseSetIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a419258ce1004e465d7ac330fa721ab77">VirtReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aea32ab12cb63c145f279b7eb768203">LaneMask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62cea84ba15a90f1f6c497f16d8eeda3">SU</a></td>
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

<p>An individual mapping from virtual register number to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VReg2SUnit() {#ac87037fa013ed9cc1effcc8bfcf8075e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VReg2SUnit::VReg2SUnit (unsigned VReg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="#a4aea32ab12cb63c145f279b7eb768203">LaneMask</a>, <a href="#a62cea84ba15a90f1f6c497f16d8eeda3">SU</a> and <a href="#a419258ce1004e465d7ac330fa721ab77">VirtReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vreg2sunitoperidx/#ae20f8cba1a27a2ffcb64658161865a27">llvm::VReg2SUnitOperIdx::VReg2SUnitOperIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSparseSetIndex() {#a8888c23f68696106ebdc5a796f330f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VReg2SUnit::getSparseSetIndex ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="#a419258ce1004e465d7ac330fa721ab77">VirtReg</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#a4df23dddc646b6a4b36ff483063a4ff8">llvm::Register::virtReg2Index</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LaneMask {#a4aea32ab12cb63c145f279b7eb768203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask llvm::VReg2SUnit::LaneMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ac87037fa013ed9cc1effcc8bfcf8075e">VReg2SUnit</a> and <a href="/web-llvm/docs/api/structs/llvm/vreg2sunitoperidx/#ae20f8cba1a27a2ffcb64658161865a27">llvm::VReg2SUnitOperIdx::VReg2SUnitOperIdx</a>.</p>

</div>
</div>

### SU {#a62cea84ba15a90f1f6c497f16d8eeda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::VReg2SUnit::SU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a920652e64042f72e913f81f9660b4f2f">llvm::ScheduleDAGMILive::collectVRegUses</a>, <a href="#ac87037fa013ed9cc1effcc8bfcf8075e">VReg2SUnit</a> and <a href="/web-llvm/docs/api/structs/llvm/vreg2sunitoperidx/#ae20f8cba1a27a2ffcb64658161865a27">llvm::VReg2SUnitOperIdx::VReg2SUnitOperIdx</a>.</p>

</div>
</div>

### VirtReg {#a419258ce1004e465d7ac330fa721ab77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VReg2SUnit::VirtReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a8888c23f68696106ebdc5a796f330f49">getSparseSetIndex</a> and <a href="#ac87037fa013ed9cc1effcc8bfcf8075e">VReg2SUnit</a>.</p>

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
