---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sdpatternmatch/effectiveoperands
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `EffectiveOperands` Struct Template Reference

<p>Provide number of operands that are not chain or glue, as well as the first index of such operand. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;bool ExcludeChain&gt;
struct llvm::SDPatternMatch::EffectiveOperands&lt;ExcludeChain&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">llvm/CodeGen/SDPatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MatchContext&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0c5e6b6524b2a56ddeba10b0c5c4b7c1">EffectiveOperands</a> (SDValue N, const MatchContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool ExcludeChain&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51dd9986ea8bee28540b1df8a63b3248">Size</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool ExcludeChain&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a006f515fed3d399b72bd8868c4e66a9d">FirstIndex</a> = 0</td>
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

<p>Provide number of operands that are not chain or glue, as well as the first index of such operand.</p>

<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EffectiveOperands() {#a0c5e6b6524b2a56ddeba10b0c5c4b7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MatchContext&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::EffectiveOperands (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatchContext &amp; Ctx)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="#a006f515fed3d399b72bd8868c4e66a9d">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::FirstIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a51dd9986ea8bee28540b1df8a63b3248">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FirstIndex {#a006f515fed3d399b72bd8868c4e66a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool ExcludeChain&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::FirstIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a0c5e6b6524b2a56ddeba10b0c5c4b7c1">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::EffectiveOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/binaryopc-match/#a1a5a03d05823f04a24f6f7b509f55882">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/maxmin-match/#afe20fb3ab3d91632fb61aee9810d28c5">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/ternaryopc-match/#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match</a> and <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/unaryopc-match/#aa82cb4ad7ffa228901bd32582599254b">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::match</a>.</p>

</div>
</div>

### Size {#a51dd9986ea8bee28540b1df8a63b3248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool ExcludeChain&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a0c5e6b6524b2a56ddeba10b0c5c4b7c1">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::EffectiveOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/binaryopc-match/#a1a5a03d05823f04a24f6f7b509f55882">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/maxmin-match/#afe20fb3ab3d91632fb61aee9810d28c5">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/ternaryopc-match/#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match</a> and <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/unaryopc-match/#aa82cb4ad7ffa228901bd32582599254b">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
