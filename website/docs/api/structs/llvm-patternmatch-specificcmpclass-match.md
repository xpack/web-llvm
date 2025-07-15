---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/specificcmpclass-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SpecificCmpClass_match` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;
struct llvm::PatternMatch::SpecificCmpClass_match&lt;LHS_t, RHS_t, Class, Commutable&gt; { ... }
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad7be59326d419379643238c61a33f09b">SpecificCmpClass_match</a> (CmpPredicate Pred, const LHS_t &amp;LHS, const RHS_t &amp;RHS)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abdf52120ea04ad8f64878bf7f4e96069">match</a> (OpTy *V)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae3b92179d90e3e098da3cca2cf3a96e0">Predicate</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ff67133cdbdf185b98d8b53ca24526e">L</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15d3708d43593d11f314a2fb51fc8d96">R</a></td>
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


<p>Definition at line 1657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SpecificCmpClass\_match() {#ad7be59326d419379643238c61a33f09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::SpecificCmpClass_match (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_t &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_t &amp; RHS)</td>
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



<p>Definition at line 1662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#a7ff67133cdbdf185b98d8b53ca24526e">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#ae3b92179d90e3e098da3cca2cf3a96e0">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::Predicate</a>, <a href="#a15d3708d43593d11f314a2fb51fc8d96">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::R</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#abdf52120ea04ad8f64878bf7f4e96069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match (OpTy * V)</td>
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



<p>Definition at line 1665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#a68d75142cb41d5119af994e4e71c451d">llvm::CmpPredicate::get</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#a1c29fdc79aad7e92c7f850bbd0faa208">llvm::CmpPredicate::getMatching</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#ad155f02dd1653e10da9e766a5c0a90c7">llvm::CmpPredicate::getSwapped</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7ff67133cdbdf185b98d8b53ca24526e">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::L</a>, <a href="#ae3b92179d90e3e098da3cca2cf3a96e0">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::Predicate</a> and <a href="#a15d3708d43593d11f314a2fb51fc8d96">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::R</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### L {#a7ff67133cdbdf185b98d8b53ca24526e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_t llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#abdf52120ea04ad8f64878bf7f4e96069">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a> and <a href="#ad7be59326d419379643238c61a33f09b">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::SpecificCmpClass_match</a>.</p>

</div>
</div>

### Predicate {#ae3b92179d90e3e098da3cca2cf3a96e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CmpPredicate llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::Predicate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#abdf52120ea04ad8f64878bf7f4e96069">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a> and <a href="#ad7be59326d419379643238c61a33f09b">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::SpecificCmpClass_match</a>.</p>

</div>
</div>

### R {#a15d3708d43593d11f314a2fb51fc8d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Class, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_t llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#abdf52120ea04ad8f64878bf7f4e96069">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a> and <a href="#ad7be59326d419379643238c61a33f09b">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::SpecificCmpClass_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
