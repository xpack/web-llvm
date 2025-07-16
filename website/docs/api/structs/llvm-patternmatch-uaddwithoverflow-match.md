---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/uaddwithoverflow-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `UAddWithOverflow_match` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;
struct llvm::PatternMatch::UAddWithOverflow_match&lt;LHS_t, RHS_t, Sum_t&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a391f54b705bff839009503fe4579d161">UAddWithOverflow_match</a> (const LHS_t &amp;L, const RHS_t &amp;R, const Sum_t &amp;S)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9fc7ef15bae578ae18f341e9530a182a">match</a> (OpTy *V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LHS_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad61d97152bf56fc05f31dce52409a662">L</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RHS_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa127a0c5bda97dd27a8effec993d149b">R</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Sum_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd60415f63287d17936dd6aef938503d">S</a></td>
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


<p>Definition at line 2484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UAddWithOverflow\_match() {#a391f54b705bff839009503fe4579d161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::UAddWithOverflow_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_t &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_t &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Sum_t &amp; S)</td>
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



<p>Definition at line 2489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#ad61d97152bf56fc05f31dce52409a662">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::L</a>, <a href="#aa127a0c5bda97dd27a8effec993d149b">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::R</a> and <a href="#afd60415f63287d17936dd6aef938503d">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::S</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a9fc7ef15bae578ae18f341e9530a182a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::match (OpTy * V)</td>
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



<p>Definition at line 2492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#ad61d97152bf56fc05f31dce52409a662">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a>, <a href="#a9fc7ef15bae578ae18f341e9530a182a">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::match</a>, <a href="#aa127a0c5bda97dd27a8effec993d149b">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::R</a> and <a href="#afd60415f63287d17936dd6aef938503d">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::S</a>.</p>


<p>Referenced by <a href="#a9fc7ef15bae578ae18f341e9530a182a">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::match</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### L {#ad61d97152bf56fc05f31dce52409a662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_t llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a9fc7ef15bae578ae18f341e9530a182a">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::match</a> and <a href="#a391f54b705bff839009503fe4579d161">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::UAddWithOverflow_match</a>.</p>

</div>
</div>

### R {#aa127a0c5bda97dd27a8effec993d149b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_t llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a9fc7ef15bae578ae18f341e9530a182a">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::match</a> and <a href="#a391f54b705bff839009503fe4579d161">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::UAddWithOverflow_match</a>.</p>

</div>
</div>

### S {#afd60415f63287d17936dd6aef938503d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_t, typename RHS_t, typename Sum_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sum_t llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a9fc7ef15bae578ae18f341e9530a182a">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::match</a> and <a href="#a391f54b705bff839009503fe4579d161">llvm::PatternMatch::UAddWithOverflow_match&lt; LHS_t, RHS_t, Sum_t &gt;::UAddWithOverflow_match</a>.</p>

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
