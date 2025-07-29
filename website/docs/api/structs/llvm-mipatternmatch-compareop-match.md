---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mipatternmatch/compareop-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CompareOp_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename Pred_P, typename LHS_P, typename RHS_P, unsigned Opcode, bool Commutable = false&gt;
struct llvm::MIPatternMatch::CompareOp_match&lt;Pred_P, LHS_P, RHS_P, Opcode, Commutable&gt; { ... }
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae5c0954ca3e581f146534c409f86db2c">CompareOp_match</a> (const Pred_P &amp;Pred, const LHS_P &amp;LHS, const RHS_P &amp;RHS)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afdb133294564dd07699c439079f2c1ee">match</a> (const MachineRegisterInfo &amp;MRI, OpTy &amp;&amp;Op)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Pred_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3affb7124a14eb19e99f9b6986cbb9d0">P</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LHS_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a866db1e9a660a79daf2a2736f6f8ac30">L</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RHS_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a337fffa3eb55746d148a323df2b4f3f2">R</a></td>
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


<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CompareOp\_match() {#ae5c0954ca3e581f146534c409f86db2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Pred_P, typename LHS_P, typename RHS_P, unsigned Opcode, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::CompareOp_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Pred_P &amp; Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_P &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_P &amp; RHS)</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>References <a href="#a866db1e9a660a79daf2a2736f6f8ac30">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a3affb7124a14eb19e99f9b6986cbb9d0">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::P</a>, <a href="#a337fffa3eb55746d148a323df2b4f3f2">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::R</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#afdb133294564dd07699c439079f2c1ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, OpTy &amp;&amp; Op)</td>
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



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="#a866db1e9a660a79daf2a2736f6f8ac30">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a3affb7124a14eb19e99f9b6986cbb9d0">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::P</a>, <a href="#a337fffa3eb55746d148a323df2b4f3f2">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::R</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### L {#a866db1e9a660a79daf2a2736f6f8ac30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Pred_P, typename LHS_P, typename RHS_P, unsigned Opcode, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_P llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>Referenced by <a href="#ae5c0954ca3e581f146534c409f86db2c">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::CompareOp_match</a> and <a href="#afdb133294564dd07699c439079f2c1ee">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>.</p>

</div>
</div>

### P {#a3affb7124a14eb19e99f9b6986cbb9d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Pred_P, typename LHS_P, typename RHS_P, unsigned Opcode, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pred_P llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::P</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>Referenced by <a href="#ae5c0954ca3e581f146534c409f86db2c">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::CompareOp_match</a> and <a href="#afdb133294564dd07699c439079f2c1ee">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>.</p>

</div>
</div>

### R {#a337fffa3eb55746d148a323df2b4f3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Pred_P, typename LHS_P, typename RHS_P, unsigned Opcode, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_P llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">MIPatternMatch.h</a>.</p>


<p>Referenced by <a href="#ae5c0954ca3e581f146534c409f86db2c">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::CompareOp_match</a> and <a href="#afdb133294564dd07699c439079f2c1ee">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>.</p>

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
