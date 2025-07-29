---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mipatternmatch/ternaryop-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TernaryOp_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename Src0Ty, typename Src1Ty, typename Src2Ty, unsigned Opcode&gt;
struct llvm::MIPatternMatch::TernaryOp_match&lt;Src0Ty, Src1Ty, Src2Ty, Opcode&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">llvm/CodeGen/GlobalISel/MIPatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7dc3615c76c266e4d07cd2e45954d65c">TernaryOp_match</a> (const Src0Ty &amp;Src0, const Src1Ty &amp;Src1, const Src2Ty &amp;Src2)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OpTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0fd9be9076c83aab0325acd8d4ef55fd">match</a> (const MachineRegisterInfo &amp;MRI, OpTy &amp;&amp;Op)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Src0Ty</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51e51f87339f872bd79c8562396c5e63">Src0</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Src1Ty</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1fdf666193d32ee1a8d8c2ae38e32de6">Src1</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Src2Ty</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a17d69509aa1d0d22f1b729daa9d03da3">Src2</a></td>
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


<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TernaryOp\_match() {#a7dc3615c76c266e4d07cd2e45954d65c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Src0Ty, typename Src1Ty, typename Src2Ty, unsigned Opcode&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::TernaryOp_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Src0Ty &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Src1Ty &amp; Src1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Src2Ty &amp; Src2)</td>
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



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>References <a href="#a51e51f87339f872bd79c8562396c5e63">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src0</a>, <a href="#a1fdf666193d32ee1a8d8c2ae38e32de6">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src1</a> and <a href="#a17d69509aa1d0d22f1b729daa9d03da3">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src2</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a0fd9be9076c83aab0325acd8d4ef55fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, OpTy &amp;&amp; Op)</td>
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



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a51e51f87339f872bd79c8562396c5e63">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src0</a>, <a href="#a1fdf666193d32ee1a8d8c2ae38e32de6">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src1</a> and <a href="#a17d69509aa1d0d22f1b729daa9d03da3">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src2</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Src0 {#a51e51f87339f872bd79c8562396c5e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Src0Ty, typename Src1Ty, typename Src2Ty, unsigned Opcode&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Src0Ty llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a0fd9be9076c83aab0325acd8d4ef55fd">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match</a> and <a href="#a7dc3615c76c266e4d07cd2e45954d65c">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::TernaryOp_match</a>.</p>

</div>
</div>

### Src1 {#a1fdf666193d32ee1a8d8c2ae38e32de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Src0Ty, typename Src1Ty, typename Src2Ty, unsigned Opcode&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Src1Ty llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a0fd9be9076c83aab0325acd8d4ef55fd">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match</a> and <a href="#a7dc3615c76c266e4d07cd2e45954d65c">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::TernaryOp_match</a>.</p>

</div>
</div>

### Src2 {#a17d69509aa1d0d22f1b729daa9d03da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Src0Ty, typename Src1Ty, typename Src2Ty, unsigned Opcode&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Src2Ty llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::Src2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a0fd9be9076c83aab0325acd8d4ef55fd">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match</a> and <a href="#a7dc3615c76c266e4d07cd2e45954d65c">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::TernaryOp_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
