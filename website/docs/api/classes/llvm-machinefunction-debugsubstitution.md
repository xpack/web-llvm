---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinefunction/debugsubstitution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugSubstitution` Class

<p>Replacement definition for a debug instruction reference. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineFunction::DebugSubstitution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d963e8c26325e2cf8e1ee13fbae2e6">DebugSubstitution</a> (const DebugInstrOperandPair &amp;Src, const DebugInstrOperandPair &amp;Dest, unsigned Subreg)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c032085319694b27f0bcdf8f43b202a">operator&lt;</a> (const DebugSubstitution &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Order only by source instruction / operand pair: there should never be duplicate entries for the same source in any collection. <a href="#a0c032085319694b27f0bcdf8f43b202a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2097b2a990ffa425c1885d12a5e33ef8">DebugInstrOperandPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c4f2137a7bc2503a8ad60056f60a3b6">Src</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source instruction / operand pair. <a href="#a8c4f2137a7bc2503a8ad60056f60a3b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2097b2a990ffa425c1885d12a5e33ef8">DebugInstrOperandPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640a084df58de4540d63d9a561f6c0c5">Dest</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replacement instruction / operand pair. <a href="#a640a084df58de4540d63d9a561f6c0c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af613616871c642bab1dfd9c82459981e">Subreg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Qualifier for which part of Dest is read. <a href="#af613616871c642bab1dfd9c82459981e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Replacement definition for a debug instruction reference.</p>


<p>Made up of a source instruction / operand pair, destination pair, and a qualifying subregister indicating what bits in the operand make up the substitution. of %1: %0:gr32 = someinst, debug-instr-number 1 %1:gr16 = %0.some_16_bit_subreg, debug-instr-number 2 Would receive the substitution {{2, 0}, {1, 0}, $subreg}, where $subreg is the subregister number for some_16_bit_subreg.</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugSubstitution() {#ab2d963e8c26325e2cf8e1ee13fbae2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineFunction::DebugSubstitution::DebugSubstitution (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2097b2a990ffa425c1885d12a5e33ef8">DebugInstrOperandPair</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2097b2a990ffa425c1885d12a5e33ef8">DebugInstrOperandPair</a> &amp; Dest, unsigned Subreg)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="#a640a084df58de4540d63d9a561f6c0c5">Dest</a>, <a href="#a8c4f2137a7bc2503a8ad60056f60a3b6">Src</a> and <a href="#af613616871c642bab1dfd9c82459981e">Subreg</a>.</p>


<p>Referenced by <a href="#a0c032085319694b27f0bcdf8f43b202a">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a0c032085319694b27f0bcdf8f43b202a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFunction::DebugSubstitution::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction/debugsubstitution">DebugSubstitution</a> &amp; Other)</td>
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

<p>Order only by source instruction / operand pair: there should never be duplicate entries for the same source in any collection.</p>

<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="#ab2d963e8c26325e2cf8e1ee13fbae2e6">DebugSubstitution</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a8c4f2137a7bc2503a8ad60056f60a3b6">Src</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Dest {#a640a084df58de4540d63d9a561f6c0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugInstrOperandPair llvm::MachineFunction::DebugSubstitution::Dest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replacement instruction / operand pair.</p>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="#ab2d963e8c26325e2cf8e1ee13fbae2e6">DebugSubstitution</a>.</p>

</div>
</div>

### Src {#a8c4f2137a7bc2503a8ad60056f60a3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugInstrOperandPair llvm::MachineFunction::DebugSubstitution::Src</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source instruction / operand pair.</p>

<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="#ab2d963e8c26325e2cf8e1ee13fbae2e6">DebugSubstitution</a> and <a href="#a0c032085319694b27f0bcdf8f43b202a">operator&lt;</a>.</p>

</div>
</div>

### Subreg {#af613616871c642bab1dfd9c82459981e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineFunction::DebugSubstitution::Subreg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Qualifier for which part of Dest is read.</p>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="#ab2d963e8c26325e2cf8e1ee13fbae2e6">DebugSubstitution</a>.</p>

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
