---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inlineasmlowering-cpp-/giselasmoperandinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GISelAsmOperandInfo` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-inlineasmlowering-cpp-/giselasmoperandinfo">GISelAsmOperandInfo</a> - This contains information for each constraint that we are lowering. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InlineAsmLowering.cpp}::GISelAsmOperandInfo { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetLowering::AsmOperandInfo</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa888e39776b90cf8d172a051ee8f7a4c">GISelAsmOperandInfo</a> (const TargetLowering::AsmOperandInfo &amp;Info)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5837b0fa21caf7f6f45f503ea32cc756">Regs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Regs - If this is a register or register class operand, this contains the set of assigned registers corresponding to the operand. <a href="#a5837b0fa21caf7f6f45f503ea32cc756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-inlineasmlowering-cpp-/giselasmoperandinfo">GISelAsmOperandInfo</a> - This contains information for each constraint that we are lowering.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GISelAsmOperandInfo() {#aa888e39776b90cf8d172a051ee8f7a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineAsmLowering.cpp}::GISelAsmOperandInfo::GISelAsmOperandInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TargetLowering::AsmOperandInfo &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Regs {#a5837b0fa21caf7f6f45f503ea32cc756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 1&gt; anonymous{InlineAsmLowering.cpp}::GISelAsmOperandInfo::Regs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Regs - If this is a register or register class operand, this contains the set of assigned registers corresponding to the operand.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
