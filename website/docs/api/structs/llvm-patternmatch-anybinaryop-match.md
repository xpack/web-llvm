---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/anybinaryop-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AnyBinaryOp_match` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename LHS_t, typename RHS_t, bool Commutable = false&gt;
struct llvm::PatternMatch::AnyBinaryOp_match&lt;LHS_t, RHS_t, Commutable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LHS_t, typename RHS_t, bool Commutable = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a6e7825bd6c6b1b6e1eccd1a3a33fe28c">AnyBinaryOp_match</a> (const LHS_t &amp;LHS, const RHS_t &amp;RHS)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeebc618b9a8e2d5b55e3d98f07530ba2">match</a> (OpTy *V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LHS_t, typename RHS_t, bool Commutable = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LHS_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad33e73eb8ce0a3d269b6e2ea67660f56">L</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LHS_t, typename RHS_t, bool Commutable = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RHS_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d35d727a28b2e14eb91aa61a592789c">R</a></td>
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


<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AnyBinaryOp\_match() {#a6e7825bd6c6b1b6e1eccd1a3a33fe28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::AnyBinaryOp_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_t &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_t &amp; RHS)</td>
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



<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#ad33e73eb8ce0a3d269b6e2ea67660f56">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a1d35d727a28b2e14eb91aa61a592789c">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::R</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#aeebc618b9a8e2d5b55e3d98f07530ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::match (OpTy * V)</td>
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



<p>Definition at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad33e73eb8ce0a3d269b6e2ea67660f56">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::L</a> and <a href="#a1d35d727a28b2e14eb91aa61a592789c">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::R</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### L {#ad33e73eb8ce0a3d269b6e2ea67660f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_t llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a6e7825bd6c6b1b6e1eccd1a3a33fe28c">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::AnyBinaryOp_match</a> and <a href="#aeebc618b9a8e2d5b55e3d98f07530ba2">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::match</a>.</p>

</div>
</div>

### R {#a1d35d727a28b2e14eb91aa61a592789c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_t llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a6e7825bd6c6b1b6e1eccd1a3a33fe28c">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::AnyBinaryOp_match</a> and <a href="#aeebc618b9a8e2d5b55e3d98f07530ba2">llvm::PatternMatch::AnyBinaryOp_match&lt; LHS_t, RHS_t, Commutable &gt;::match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
