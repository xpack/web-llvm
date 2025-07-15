---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dbgvariablelocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DbgVariableLocation` Struct Reference

<p>Represents the location at which a variable is stored. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DbgVariableLocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">llvm/CodeGen/DebugHandlerBase.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabaaa570e6ca27f8c64ac435b0714317">Register</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base register. <a href="#aabaaa570e6ca27f8c64ac435b0714317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int64_t, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5286bc94ab9e13df3361f00a6550c7d">LoadChain</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Chain of offsetted loads necessary to load the value if it lives in memory. <a href="#ac5286bc94ab9e13df3361f00a6550c7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">llvm::DIExpression::FragmentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762275736cd3b83ffb558739648ab670">FragmentInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Present if the location is part of a larger variable. <a href="#a762275736cd3b83ffb558739648ab670">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dbgvariablelocation">DbgVariableLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba45f582b07732ab64d6d518d4b45b12">extractFromMachineInstruction</a> (const MachineInstr &amp;Instruction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a VariableLocation from a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#aba45f582b07732ab64d6d518d4b45b12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents the location at which a variable is stored.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### FragmentInfo {#a762275736cd3b83ffb558739648ab670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::DIExpression::FragmentInfo&gt; llvm::DbgVariableLocation::FragmentInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Present if the location is part of a larger variable.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>

</div>
</div>

### LoadChain {#ac5286bc94ab9e13df3361f00a6550c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int64_t, 1&gt; llvm::DbgVariableLocation::LoadChain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Chain of offsetted loads necessary to load the value if it lives in memory.</p>


<p>Every load except for the last is pointer-sized.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>

</div>
</div>

### Register {#aabaaa570e6ca27f8c64ac435b0714317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DbgVariableLocation::Register</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Base register.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#aba45f582b07732ab64d6d518d4b45b12">extractFromMachineInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### extractFromMachineInstruction() {#aba45f582b07732ab64d6d518d4b45b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DbgVariableLocation &gt; DbgVariableLocation::extractFromMachineInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Instruction)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a VariableLocation from a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>This will only work if <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is a debug value instruction and the associated <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> is in one of the supported forms. If these requirements are not met, the returned Optional will not have a value.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2385d3ed339f953fa0d9ff2bed10483d">llvm::DIExpression::expr_op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a3fa5abf71eb1019c5a31a969ef43bac2">llvm::DIExpression::expr_op_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#aabaaa570e6ca27f8c64ac435b0714317">Register</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
