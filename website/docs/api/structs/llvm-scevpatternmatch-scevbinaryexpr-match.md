---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/scevpatternmatch/scevbinaryexpr-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SCEVBinaryExpr_match` Struct Template Reference

<p>Match a binary <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;
struct llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt;SCEVTy, Op0_t, Op1_t&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionpatternmatch-h">llvm/Analysis/ScalarEvolutionPatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a53c723a3c53d0699bd638fe830b8d72e">SCEVBinaryExpr_match</a> (Op0_t Op0, Op1_t Op1)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4757ee4c341aa3a17e34a76f9b7eec6">match</a> (const SCEV *S)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Op0_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03bff5c3802ccf2d2451976262a30fb8">Op0</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Op1_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4d9a7d52798ba4a183fd9b3d45596db">Op1</a></td>
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

<p>Match a binary <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionpatternmatch-h">ScalarEvolutionPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SCEVBinaryExpr\_match() {#a53c723a3c53d0699bd638fe830b8d72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::SCEVBinaryExpr_match (Op0_t Op0, Op1_t Op1)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionpatternmatch-h">ScalarEvolutionPatternMatch.h</a>.</p>


<p>References <a href="#a03bff5c3802ccf2d2451976262a30fb8">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::Op0</a> and <a href="#ab4d9a7d52798ba4a183fd9b3d45596db">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::Op1</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#af4757ee4c341aa3a17e34a76f9b7eec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionpatternmatch-h">ScalarEvolutionPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a03bff5c3802ccf2d2451976262a30fb8">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::Op0</a> and <a href="#ab4d9a7d52798ba4a183fd9b3d45596db">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::Op1</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Op0 {#a03bff5c3802ccf2d2451976262a30fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Op0_t llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::Op0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionpatternmatch-h">ScalarEvolutionPatternMatch.h</a>.</p>


<p>Referenced by <a href="#af4757ee4c341aa3a17e34a76f9b7eec6">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::match</a> and <a href="#a53c723a3c53d0699bd638fe830b8d72e">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::SCEVBinaryExpr_match</a>.</p>

</div>
</div>

### Op1 {#ab4d9a7d52798ba4a183fd9b3d45596db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SCEVTy, typename Op0_t, typename Op1_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Op1_t llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::Op1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionpatternmatch-h">ScalarEvolutionPatternMatch.h</a>.</p>


<p>Referenced by <a href="#af4757ee4c341aa3a17e34a76f9b7eec6">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::match</a> and <a href="#a53c723a3c53d0699bd638fe830b8d72e">llvm::SCEVPatternMatch::SCEVBinaryExpr_match&lt; SCEVTy, Op0_t, Op1_t &gt;::SCEVBinaryExpr_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionpatternmatch-h">ScalarEvolutionPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
