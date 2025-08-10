---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/cmpclass-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CmpClass_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;
struct llvm::PatternMatch::CmpClass_match&lt;LHS_t, RHS_t, Class, Commutable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2f0003f17bb6c1e8cea304785e32f983">CmpClass_match</a> (CmpPredicate &amp;Pred, const LHS_t &amp;LHS, const RHS_t &amp;RHS)</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7ce4982530dbba0365164fe0bfbb8f17">CmpClass_match</a> (const LHS_t &amp;LHS, const RHS_t &amp;RHS)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1fceeb78aaeef3d5d59989489d5a31ac">match</a> (OpTy *V)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5967a1c39ebb1a6091ff7050d0654d00">Predicate</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LHS_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2880c8b480b373d014830b083bf08c1a">L</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RHS_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0a9f82e7d4a18b81d8946dc7d0ab28ca">R</a></td>
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


<p>Definition at line 1590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CmpClass\_match() {#a2f0003f17bb6c1e8cea304785e32f983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> &amp; Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_t &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_t &amp; RHS)</td>
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



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#a2880c8b480b373d014830b083bf08c1a">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a5967a1c39ebb1a6091ff7050d0654d00">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::Predicate</a>, <a href="#a0a9f82e7d4a18b81d8946dc7d0ab28ca">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::R</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CmpClass\_match() {#a7ce4982530dbba0365164fe0bfbb8f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_t &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_t &amp; RHS)</td>
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



<p>Definition at line 1599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#a2880c8b480b373d014830b083bf08c1a">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a5967a1c39ebb1a6091ff7050d0654d00">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::Predicate</a>, <a href="#a0a9f82e7d4a18b81d8946dc7d0ab28ca">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::R</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a1fceeb78aaeef3d5d59989489d5a31ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match (OpTy * V)</td>
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



<p>Definition at line 1602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#a68d75142cb41d5119af994e4e71c451d">llvm::CmpPredicate::get</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#ad155f02dd1653e10da9e766a5c0a90c7">llvm::CmpPredicate::getSwapped</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a2880c8b480b373d014830b083bf08c1a">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::L</a>, <a href="#a5967a1c39ebb1a6091ff7050d0654d00">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::Predicate</a> and <a href="#a0a9f82e7d4a18b81d8946dc7d0ab28ca">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::R</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### L {#a2880c8b480b373d014830b083bf08c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_t llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a2f0003f17bb6c1e8cea304785e32f983">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match</a>, <a href="#a7ce4982530dbba0365164fe0bfbb8f17">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match</a> and <a href="#a1fceeb78aaeef3d5d59989489d5a31ac">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a>.</p>

</div>
</div>

### Predicate {#a5967a1c39ebb1a6091ff7050d0654d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate* llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::Predicate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a2f0003f17bb6c1e8cea304785e32f983">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match</a>, <a href="#a7ce4982530dbba0365164fe0bfbb8f17">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match</a> and <a href="#a1fceeb78aaeef3d5d59989489d5a31ac">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a>.</p>

</div>
</div>

### R {#a0a9f82e7d4a18b81d8946dc7d0ab28ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_t llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a2f0003f17bb6c1e8cea304785e32f983">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match</a>, <a href="#a7ce4982530dbba0365164fe0bfbb8f17">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::CmpClass_match</a> and <a href="#a1fceeb78aaeef3d5d59989489d5a31ac">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
