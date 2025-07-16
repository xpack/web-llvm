---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/idfcalculator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IDFCalculator` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;bool IsPostDom&gt;
class llvm::IDFCalculator&lt;IsPostDom&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/iterateddominancefrontier-h">llvm/Analysis/IteratedDominanceFrontier.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase">IDFCalculatorBase&lt;NodeTy, IsPostDom&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the iterated dominance frontier, given a set of defining blocks, and optionally, a set of live-in blocks. <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c8385fc8ca6c3265d127bcaee28960b">IDFCalculatorBase</a> = typename <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase">llvm::IDFCalculatorBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, IsPostDom &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a444f8a1ae9f8992d2fe39129805d3485">ChildrenGetterTy</a> = typename <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#ad53b6924f735860e99160efbe46fc23f">IDFCalculatorBase::ChildrenGetterTy</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0db3df213f6c428f2c8e330f792f6e82">IDFCalculator</a> (DominatorTreeBase&lt; BasicBlock, IsPostDom &gt; &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a06a83596a30ab20bff2f075ddba087db">IDFCalculator</a> (DominatorTreeBase&lt; BasicBlock, IsPostDom &gt; &amp;DT, const GraphDiff&lt; BasicBlock *, IsPostDom &gt; *GD)</td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/iterateddominancefrontier-h">IteratedDominanceFrontier.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ChildrenGetterTy {#a444f8a1ae9f8992d2fe39129805d3485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IDFCalculator&lt; IsPostDom &gt;::ChildrenGetterTy =  typename IDFCalculatorBase::ChildrenGetterTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/iterateddominancefrontier-h">IteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### IDFCalculatorBase {#a1c8385fc8ca6c3265d127bcaee28960b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IDFCalculator&lt; IsPostDom &gt;::IDFCalculatorBase = 
      typename llvm::IDFCalculatorBase&lt;BasicBlock, IsPostDom&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/iterateddominancefrontier-h">IteratedDominanceFrontier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IDFCalculator() {#a0db3df213f6c428f2c8e330f792f6e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IDFCalculator&lt; IsPostDom &gt;::IDFCalculator (<a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, IsPostDom &gt; &amp; DT)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/iterateddominancefrontier-h">IteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### IDFCalculator() {#a06a83596a30ab20bff2f075ddba087db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IDFCalculator&lt; IsPostDom &gt;::IDFCalculator (<a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, IsPostDom &gt; &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, IsPostDom &gt; * GD)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/iterateddominancefrontier-h">IteratedDominanceFrontier.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/iterateddominancefrontier-h">IteratedDominanceFrontier.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
