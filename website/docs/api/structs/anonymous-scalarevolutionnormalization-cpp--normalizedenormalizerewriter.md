---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-scalarevolutionnormalization-cpp-/normalizedenormalizerewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NormalizeDenormalizeRewriter` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{ScalarEvolutionNormalization.cpp}::NormalizeDenormalizeRewriter { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor">SCEVRewriteVisitor&lt;SC&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This visitor recursively visits a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression and re-writes it. <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ff24376d20a01f53bd2edc7747d00a6">NormalizeDenormalizeRewriter</a> (TransformKind Kind, NormalizePredTy Pred, ScalarEvolution &amp;SE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9bcd9133d19e4e656a82dd8e900d3f8">visitAddRecExpr</a> (const SCEVAddRecExpr *Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp/#afd925d64a119671c81c42f09b7507534">TransformKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee40644eb54dbce87191fb2df07ae4c">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a7ae68e475882c08a262b0857df469b73">NormalizePredTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae266031b37cb00fe1c9f63ec04148f5a">Pred</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp">ScalarEvolutionNormalization.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NormalizeDenormalizeRewriter() {#a5ff24376d20a01f53bd2edc7747d00a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScalarEvolutionNormalization.cpp}::NormalizeDenormalizeRewriter::NormalizeDenormalizeRewriter (<a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp/#afd925d64a119671c81c42f09b7507534">TransformKind</a> Kind, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ae68e475882c08a262b0857df469b73">NormalizePredTy</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp">ScalarEvolutionNormalization.cpp</a>.</p>


<p>References <a href="#a6ee40644eb54dbce87191fb2df07ae4c">Kind</a>, <a href="#a5ff24376d20a01f53bd2edc7747d00a6">NormalizeDenormalizeRewriter</a>, <a href="#ae266031b37cb00fe1c9f63ec04148f5a">Pred</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a402d133bc2a8069432f15be4dd517589">llvm::SCEVRewriteVisitor&lt; NormalizeDenormalizeRewriter &gt;::SCEVRewriteVisitor</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; NormalizeDenormalizeRewriter &gt;::SE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6fb1355b48afff4e97045b546b5f6415">llvm::denormalizeForPostIncUse</a>, <a href="#a5ff24376d20a01f53bd2edc7747d00a6">NormalizeDenormalizeRewriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99237ea99bf8618b7d29b5ca6185069b">llvm::normalizeForPostIncUse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adb2ce7b0fb87c632dac34aa98feabb82">llvm::normalizeForPostIncUseIf</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitAddRecExpr() {#ac9bcd9133d19e4e656a82dd8e900d3f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * NormalizeDenormalizeRewriter::visitAddRecExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp">ScalarEvolutionNormalization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp/#afd925d64a119671c81c42f09b7507534ab0c4c0de3e04f91deb80528ae0e2a4a6">Denormalize</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#a6ee40644eb54dbce87191fb2df07ae4c">Kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp/#afd925d64a119671c81c42f09b7507534a4f6bc3e35432a7e20c757280be0d1f6b">Normalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#ae266031b37cb00fe1c9f63ec04148f5a">Pred</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; NormalizeDenormalizeRewriter &gt;::SE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Kind {#a6ee40644eb54dbce87191fb2df07ae4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TransformKind anonymous{ScalarEvolutionNormalization.cpp}::NormalizeDenormalizeRewriter::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp">ScalarEvolutionNormalization.cpp</a>.</p>


<p>Referenced by <a href="#a5ff24376d20a01f53bd2edc7747d00a6">NormalizeDenormalizeRewriter</a> and <a href="#ac9bcd9133d19e4e656a82dd8e900d3f8">visitAddRecExpr</a>.</p>

</div>
</div>

### Pred {#ae266031b37cb00fe1c9f63ec04148f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NormalizePredTy anonymous{ScalarEvolutionNormalization.cpp}::NormalizeDenormalizeRewriter::Pred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp">ScalarEvolutionNormalization.cpp</a>.</p>


<p>Referenced by <a href="#a5ff24376d20a01f53bd2edc7747d00a6">NormalizeDenormalizeRewriter</a> and <a href="#ac9bcd9133d19e4e656a82dd8e900d3f8">visitAddRecExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp">ScalarEvolutionNormalization.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
