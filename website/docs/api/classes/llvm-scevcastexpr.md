---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scevcastexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCEVCastExpr` Class Reference

<p>This is the base class for unary cast operator classes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCEVCastExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents an analyzed expression in the program. <a href="/web-llvm/docs/api/classes/llvm/scev/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevintegralcastexpr">SCEVIntegralCastExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for unary integral cast operator classes. <a href="/web-llvm/docs/api/classes/llvm/scevintegralcastexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevptrtointexpr">SCEVPtrToIntExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a cast from a pointer to a pointer-sized integer value. <a href="/web-llvm/docs/api/classes/llvm/scevptrtointexpr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb400ab122ec2c7e1222c7dc7eac079e">SCEVCastExpr</a> (const FoldingSetNodeIDRef ID, SCEVTypes SCEVTy, const SCEV *op, Type *ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c2fb358d83304761d3848aa70ee5d6">getOperand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f00d09bfec103f4a500db452aaace2">getOperand</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db227a019667232017d00f15cb09d0a">operands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec9b9276cd8d2d0a74548bc9d913d59">getNumOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53e251228db4e03f1134e39b89a80f7">getType</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c8ad1c65d2d43770b4b6a2290bcbed5">Op</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0422a5af1687cb7b0572000de74997be">Ty</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea85e11db3d72c739df477f88e3e1913">classof</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#aea85e11db3d72c739df477f88e3e1913">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is the base class for unary cast operator classes.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### SCEVCastExpr() {#acb400ab122ec2c7e1222c7dc7eac079e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVCastExpr::SCEVCastExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeidref">FoldingSetNodeIDRef</a> ID, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> SCEVTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ty)</td>
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



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>, definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3d8e1e329cf813ca2b411957a4d11d5d">llvm::computeExpressionSize</a>, <a href="#a2c8ad1c65d2d43770b4b6a2290bcbed5">Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#ace7f137cfb19ce8073b78b85f819430c">llvm::SCEV::SCEV</a> and <a href="#a0422a5af1687cb7b0572000de74997be">Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevintegralcastexpr/#a8da5e068d45d31d39f6f449efd8d1d9e">llvm::SCEVIntegralCastExpr::SCEVIntegralCastExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNumOperands() {#a5ec9b9276cd8d2d0a74548bc9d913d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SCEVCastExpr::getNumOperands ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>

</div>
</div>

### getOperand() {#ab6c2fb358d83304761d3848aa70ee5d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVCastExpr::getOperand ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="#a2c8ad1c65d2d43770b4b6a2290bcbed5">Op</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#ace7f137cfb19ce8073b78b85f819430c">llvm::SCEV::SCEV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54c5a810b1d6fbe75255674e7e9c40ba">BuildConstantFromSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ad5a0854a75b9e8d760fd95387759569c">isSimpleCastedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1ca111e154e97420c537cd07a983144c">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a6d82a4b5dcc63a42638f2ee9b9c2e876">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitSignExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a0b7753d0b14b645772a41d77a7da007f">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSignExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a9d079aeac19c207d95a14dd01553ca04">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitTruncateExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a169c4e815b26d46ffdd9e079a89461b8">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitZeroExtendExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a2e90f20113c5f4bc14a84396a22077c1">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitZeroExtendExpr</a>.</p>

</div>
</div>

### getOperand() {#a23f00d09bfec103f4a500db452aaace2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVCastExpr::getOperand (unsigned i)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2c8ad1c65d2d43770b4b6a2290bcbed5">Op</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#ace7f137cfb19ce8073b78b85f819430c">llvm::SCEV::SCEV</a>.</p>

</div>
</div>

### getType() {#ae53e251228db4e03f1134e39b89a80f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::SCEVCastExpr::getType ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Reference <a href="#a0422a5af1687cb7b0572000de74997be">Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54c5a810b1d6fbe75255674e7e9c40ba">BuildConstantFromSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ad5a0854a75b9e8d760fd95387759569c">isSimpleCastedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1ca111e154e97420c537cd07a983144c">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a6d82a4b5dcc63a42638f2ee9b9c2e876">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitSignExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a0b7753d0b14b645772a41d77a7da007f">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSignExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a9d079aeac19c207d95a14dd01553ca04">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitTruncateExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a169c4e815b26d46ffdd9e079a89461b8">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitZeroExtendExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a2e90f20113c5f4bc14a84396a22077c1">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitZeroExtendExpr</a>.</p>

</div>
</div>

### operands() {#a4db227a019667232017d00f15cb09d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const SCEV * &gt; llvm::SCEVCastExpr::operands ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Reference <a href="#a2c8ad1c65d2d43770b4b6a2290bcbed5">Op</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Op {#a2c8ad1c65d2d43770b4b6a2290bcbed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* llvm::SCEVCastExpr::Op</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Referenced by <a href="#ab6c2fb358d83304761d3848aa70ee5d6">getOperand</a>, <a href="#a23f00d09bfec103f4a500db452aaace2">getOperand</a>, <a href="#a4db227a019667232017d00f15cb09d0a">operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevptrtointexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVPtrToIntExpr::ScalarEvolution</a> and <a href="#acb400ab122ec2c7e1222c7dc7eac079e">SCEVCastExpr</a>.</p>

</div>
</div>

### Ty {#a0422a5af1687cb7b0572000de74997be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::SCEVCastExpr::Ty</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Referenced by <a href="#ae53e251228db4e03f1134e39b89a80f7">getType</a> and <a href="#acb400ab122ec2c7e1222c7dc7eac079e">SCEVCastExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aea85e11db3d72c739df477f88e3e1913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVCastExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#ad4f956914bf94bdcd1058badb5bd90e6">llvm::SCEV::getSCEVType</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#ace7f137cfb19ce8073b78b85f819430c">llvm::SCEV::SCEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eae996cdd31b3e2df5dbd55ff638d2d456">llvm::scPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3656bcc84af213cc488acb56c60de22">llvm::scTruncate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>.</p>

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
