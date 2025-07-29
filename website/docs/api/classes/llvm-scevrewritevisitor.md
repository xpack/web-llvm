---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scevrewritevisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SCEVRewriteVisitor` Class Template

<p>This visitor recursively visits a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression and re-writes it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SC&gt;
class llvm::SCEVRewriteVisitor&lt;SC&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scevvisitor">SCEVVisitor&lt;SC, RetVal&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class defines a simple visitor class that may be used for various <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> analysis purposes. <a href="/web-llvm/docs/api/structs/llvm/scevvisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a402d133bc2a8069432f15be4dd517589">SCEVRewriteVisitor</a> (ScalarEvolution &amp;SE)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a242a71a1c3d798925fbaa9faba8bb5a8">visit</a> (const SCEV *S)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af15ca4ace3605f2e0751f4428cdc3910">visitConstant</a> (const SCEVConstant *Constant)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae21a142a1d023d3c43e2bb14593185a0">visitVScale</a> (const SCEVVScale *VScale)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ca111e154e97420c537cd07a983144c">visitPtrToIntExpr</a> (const SCEVPtrToIntExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d079aeac19c207d95a14dd01553ca04">visitTruncateExpr</a> (const SCEVTruncateExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e90f20113c5f4bc14a84396a22077c1">visitZeroExtendExpr</a> (const SCEVZeroExtendExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b7753d0b14b645772a41d77a7da007f">visitSignExtendExpr</a> (const SCEVSignExtendExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a526f03cb420e8f64cd03750939bff699">visitAddExpr</a> (const SCEVAddExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ba1cee011d4868e8966a81a41ffff38">visitMulExpr</a> (const SCEVMulExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acde7ff6691114a38761ff996e9531935">visitUDivExpr</a> (const SCEVUDivExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7723e8cfb7ea733908442f8ef2d5d85">visitAddRecExpr</a> (const SCEVAddRecExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac90f8a765813f19c8c20f90153a7cc82">visitSMaxExpr</a> (const SCEVSMaxExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba42491077efa5e60b2c439f0a59a645">visitUMaxExpr</a> (const SCEVUMaxExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a38b17b6e44b9937c10d4a4277a7abecb">visitSMinExpr</a> (const SCEVSMinExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5481db1a659c011e71a0a75ce7416735">visitUMinExpr</a> (const SCEVUMinExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a27c503b298dbe2a78b945b8c9025f6">visitSequentialUMinExpr</a> (const SCEVSequentialUMinExpr *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36754a06e1e30e147b6854066ea7903d">visitUnknown</a> (const SCEVUnknown *Expr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad78f67a5e9dc7f061b835448dbb8cc38">visitCouldNotCompute</a> (const SCEVCouldNotCompute *Expr)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f75cac3a0eec736a85d996723c70e64">SE</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d3df2fe9a155fd1bc46630a3be5f0ae">RewriteResults</a></td>
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

<p>This visitor recursively visits a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression and re-writes it.</p>


<p>The result from each visit is cached, so it will return the same <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the same input.</p>


<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SCEVRewriteVisitor() {#a402d133bc2a8069432f15be4dd517589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEVRewriteVisitor&lt; SC &gt;::SCEVRewriteVisitor (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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



<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Reference <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visit() {#a242a71a1c3d798925fbaa9faba8bb5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8d3df2fe9a155fd1bc46630a3be5f0ae">llvm::SCEVRewriteVisitor&lt; SC &gt;::RewriteResults</a> and <a href="/web-llvm/docs/api/structs/llvm/scevvisitor/#a1e7a5297e3ded4db5e828ee4bd651b34">llvm::SCEVVisitor&lt; SC, RetVal &gt;::visit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-loopvectorizationlegality-cpp-/scevaddrecforuniformityrewriter/#a23e8bb153583ce2e09b60a7564a89d5a">llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visit</a>, <a href="#a526f03cb420e8f64cd03750939bff699">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddExpr</a>, <a href="#ae7723e8cfb7ea733908442f8ef2d5d85">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddRecExpr</a>, <a href="#a7ba1cee011d4868e8966a81a41ffff38">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitMulExpr</a>, <a href="#a4a27c503b298dbe2a78b945b8c9025f6">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSequentialUMinExpr</a>, <a href="#ac90f8a765813f19c8c20f90153a7cc82">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMaxExpr</a>, <a href="#a38b17b6e44b9937c10d4a4277a7abecb">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMinExpr</a>, <a href="#aba42491077efa5e60b2c439f0a59a645">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMaxExpr</a> and <a href="#a5481db1a659c011e71a0a75ce7416735">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMinExpr</a>.</p>

</div>
</div>

### visitAddExpr() {#a526f03cb420e8f64cd03750939bff699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddexpr">SCEVAddExpr</a> * Expr)</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### visitAddRecExpr() {#ae7723e8cfb7ea733908442f8ef2d5d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddRecExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * Expr)</td>
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



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### visitConstant() {#af15ca4ace3605f2e0751f4428cdc3910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a> * Constant)</td>
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



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>

</div>
</div>

### visitCouldNotCompute() {#ad78f67a5e9dc7f061b835448dbb8cc38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitCouldNotCompute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> * Expr)</td>
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



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>

</div>
</div>

### visitMulExpr() {#a7ba1cee011d4868e8966a81a41ffff38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitMulExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevmulexpr">SCEVMulExpr</a> * Expr)</td>
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



<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### visitPtrToIntExpr() {#a1ca111e154e97420c537cd07a983144c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitPtrToIntExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevptrtointexpr">SCEVPtrToIntExpr</a> * Expr)</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ab6c2fb358d83304761d3848aa70ee5d6">llvm::SCEVCastExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ae53e251228db4e03f1134e39b89a80f7">llvm::SCEVCastExpr::getType</a> and <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a>.</p>

</div>
</div>

### visitSequentialUMinExpr() {#a4a27c503b298dbe2a78b945b8c9025f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSequentialUMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsequentialuminexpr">SCEVSequentialUMinExpr</a> * Expr)</td>
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



<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### visitSignExtendExpr() {#a0b7753d0b14b645772a41d77a7da007f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSignExtendExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsignextendexpr">SCEVSignExtendExpr</a> * Expr)</td>
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



<p>Definition at line 795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ab6c2fb358d83304761d3848aa70ee5d6">llvm::SCEVCastExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ae53e251228db4e03f1134e39b89a80f7">llvm::SCEVCastExpr::getType</a> and <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>.</p>

</div>
</div>

### visitSMaxExpr() {#ac90f8a765813f19c8c20f90153a7cc82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMaxExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsmaxexpr">SCEVSMaxExpr</a> * Expr)</td>
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



<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### visitSMinExpr() {#a38b17b6e44b9937c10d4a4277a7abecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsminexpr">SCEVSMinExpr</a> * Expr)</td>
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



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>.</p>

</div>
</div>

### visitTruncateExpr() {#a9d079aeac19c207d95a14dd01553ca04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitTruncateExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevtruncateexpr">SCEVTruncateExpr</a> * Expr)</td>
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



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ab6c2fb358d83304761d3848aa70ee5d6">llvm::SCEVCastExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ae53e251228db4e03f1134e39b89a80f7">llvm::SCEVCastExpr::getType</a> and <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a>.</p>

</div>
</div>

### visitUDivExpr() {#acde7ff6691114a38761ff996e9531935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUDivExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr">SCEVUDivExpr</a> * Expr)</td>
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



<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a64f39bbc1130d1a36d3824633863dc51">llvm::SCEVUDivExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#ad0fdc55c45a39b722f3d990505b55dd7">llvm::SCEVUDivExpr::getRHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a>.</p>

</div>
</div>

### visitUMaxExpr() {#aba42491077efa5e60b2c439f0a59a645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMaxExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevumaxexpr">SCEVUMaxExpr</a> * Expr)</td>
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



<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### visitUMinExpr() {#a5481db1a659c011e71a0a75ce7416735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevuminexpr">SCEVUMinExpr</a> * Expr)</td>
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



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a> and <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>.</p>

</div>
</div>

### visitUnknown() {#a36754a06e1e30e147b6854066ea7903d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUnknown (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> * Expr)</td>
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



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>

</div>
</div>

### visitVScale() {#ae21a142a1d023d3c43e2bb14593185a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevvscale">SCEVVScale</a> * VScale)</td>
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



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>

</div>
</div>

### visitZeroExtendExpr() {#a2e90f20113c5f4bc14a84396a22077c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVRewriteVisitor&lt; SC &gt;::visitZeroExtendExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevzeroextendexpr">SCEVZeroExtendExpr</a> * Expr)</td>
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



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ab6c2fb358d83304761d3848aa70ee5d6">llvm::SCEVCastExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ae53e251228db4e03f1134e39b89a80f7">llvm::SCEVCastExpr::getType</a> and <a href="#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### RewriteResults {#a8d3df2fe9a155fd1bc46630a3be5f0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;const SCEV *, const SCEV *&gt; llvm::SCEVRewriteVisitor&lt; SC &gt;::RewriteResults</td>
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



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Referenced by <a href="#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### SE {#a1f75cac3a0eec736a85d996723c70e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; llvm::SCEVRewriteVisitor&lt; SC &gt;::SE</td>
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



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Referenced by <a href="#a402d133bc2a8069432f15be4dd517589">llvm::SCEVRewriteVisitor&lt; SC &gt;::SCEVRewriteVisitor</a>, <a href="#a526f03cb420e8f64cd03750939bff699">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddExpr</a>, <a href="#ae7723e8cfb7ea733908442f8ef2d5d85">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddRecExpr</a>, <a href="#a7ba1cee011d4868e8966a81a41ffff38">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitMulExpr</a>, <a href="#a1ca111e154e97420c537cd07a983144c">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitPtrToIntExpr</a>, <a href="#a4a27c503b298dbe2a78b945b8c9025f6">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSequentialUMinExpr</a>, <a href="#a0b7753d0b14b645772a41d77a7da007f">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSignExtendExpr</a>, <a href="#ac90f8a765813f19c8c20f90153a7cc82">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMaxExpr</a>, <a href="#a38b17b6e44b9937c10d4a4277a7abecb">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMinExpr</a>, <a href="#a9d079aeac19c207d95a14dd01553ca04">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitTruncateExpr</a>, <a href="#acde7ff6691114a38761ff996e9531935">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUDivExpr</a>, <a href="#aba42491077efa5e60b2c439f0a59a645">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMaxExpr</a>, <a href="#a5481db1a659c011e71a0a75ce7416735">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMinExpr</a> and <a href="#a2e90f20113c5f4bc14a84396a22077c1">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitZeroExtendExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
