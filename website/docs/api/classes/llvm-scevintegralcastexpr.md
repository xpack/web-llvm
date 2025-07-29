---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scevintegralcastexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SCEVIntegralCastExpr` Class

<p>This is the base class for unary integral cast operator classes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCEVIntegralCastExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevcastexpr">SCEVCastExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for unary cast operator classes. <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevsignextendexpr">SCEVSignExtendExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a sign extension of a small integer value to a larger integer value. <a href="/web-llvm/docs/api/classes/llvm/scevsignextendexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevtruncateexpr">SCEVTruncateExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a truncation of an integer value to a smaller integer value. <a href="/web-llvm/docs/api/classes/llvm/scevtruncateexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevzeroextendexpr">SCEVZeroExtendExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a zero extension of a small integer value to a larger integer value. <a href="/web-llvm/docs/api/classes/llvm/scevzeroextendexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da5e068d45d31d39f6f449efd8d1d9e">SCEVIntegralCastExpr</a> (const FoldingSetNodeIDRef ID, SCEVTypes SCEVTy, const SCEV *op, Type *ty)</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b71fdad3c03ecb7064beceb718ebea">classof</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#ab8b71fdad3c03ecb7064beceb718ebea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is the base class for unary integral cast operator classes.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### SCEVIntegralCastExpr() {#a8da5e068d45d31d39f6f449efd8d1d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVIntegralCastExpr::SCEVIntegralCastExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeidref">FoldingSetNodeIDRef</a> ID, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> SCEVTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>, definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> and <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#acb400ab122ec2c7e1222c7dc7eac079e">llvm::SCEVCastExpr::SCEVCastExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ab8b71fdad3c03ecb7064beceb718ebea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVIntegralCastExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#ad4f956914bf94bdcd1058badb5bd90e6">llvm::SCEV::getSCEVType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3656bcc84af213cc488acb56c60de22">llvm::scTruncate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
