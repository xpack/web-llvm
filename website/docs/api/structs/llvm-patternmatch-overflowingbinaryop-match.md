---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/overflowingbinaryop-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `OverflowingBinaryOp_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename LHS_t, typename RHS_t, unsigned Opcode, unsigned WrapFlags = 0, bool Commutable = false&gt;
struct llvm::PatternMatch::OverflowingBinaryOp_match&lt;LHS_t, RHS_t, Opcode, WrapFlags, Commutable&gt; { ... }
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7977129bc3822e79b00bd96e97f8bd5c">OverflowingBinaryOp_match</a> (const LHS_t &amp;LHS, const RHS_t &amp;RHS)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a57c230e2134bfe324d8ad2e5cfaad220">match</a> (OpTy *V)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LHS_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8913a9b3982a7ef847dd13100f08b18a">L</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a898be37c70a0ad2c0fab2c99ecd62cbf">R</a></td>
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


<p>Definition at line 1253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OverflowingBinaryOp\_match() {#a7977129bc3822e79b00bd96e97f8bd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, unsigned Opcode, unsigned WrapFlags = 0, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::OverflowingBinaryOp_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_t &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_t &amp; RHS)</td>
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



<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#a8913a9b3982a7ef847dd13100f08b18a">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a898be37c70a0ad2c0fab2c99ecd62cbf">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::R</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a57c230e2134bfe324d8ad2e5cfaad220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::match (OpTy * V)</td>
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



<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8913a9b3982a7ef847dd13100f08b18a">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::L</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aac3172f238278728e355fc9a87c439dd5">llvm::OverflowingBinaryOperator::NoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aa7d34304df400cdb020e71e182ac06cb7">llvm::OverflowingBinaryOperator::NoUnsignedWrap</a> and <a href="#a898be37c70a0ad2c0fab2c99ecd62cbf">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::R</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### L {#a8913a9b3982a7ef847dd13100f08b18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, unsigned Opcode, unsigned WrapFlags = 0, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_t llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a57c230e2134bfe324d8ad2e5cfaad220">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::match</a> and <a href="#a7977129bc3822e79b00bd96e97f8bd5c">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::OverflowingBinaryOp_match</a>.</p>

</div>
</div>

### R {#a898be37c70a0ad2c0fab2c99ecd62cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, unsigned Opcode, unsigned WrapFlags = 0, bool Commutable = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_t llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a57c230e2134bfe324d8ad2e5cfaad220">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::match</a> and <a href="#a7977129bc3822e79b00bd96e97f8bd5c">llvm::PatternMatch::OverflowingBinaryOp_match&lt; LHS_t, RHS_t, Opcode, WrapFlags, Commutable &gt;::OverflowingBinaryOp_match</a>.</p>

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
