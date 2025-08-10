---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sdpatternmatch/maxmin-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MaxMin_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename LHS_P, typename RHS_P, typename Pred_t, bool Commutable = false, bool ExcludeChain = false&gt;
struct llvm::SDPatternMatch::MaxMin_match&lt;LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">llvm/CodeGen/SDPatternMatch.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb2890018bd72d1af73a4d35bde94fe9">PredType</a> = Pred_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a9bba0e99a1ab6572508c8a0de9ce3f56">MaxMin_match</a> (const LHS_P &amp;L, const RHS_P &amp;R)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MatchContext&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe20fb3ab3d91632fb61aee9810d28c5">match</a> (const MatchContext &amp;Ctx, SDValue N)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LHS_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5e409de0e66c9bc967ede32f8d8f47d">LHS</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RHS_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ffbc71c3e39c4399dda0a5851cb4f78">RHS</a></td>
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


<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PredType {#aeb2890018bd72d1af73a4d35bde94fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, typename Pred_t, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::PredType =  Pred_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MaxMin\_match() {#a9bba0e99a1ab6572508c8a0de9ce3f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, typename Pred_t, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::MaxMin_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_P &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_P &amp; R)</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="#ad5e409de0e66c9bc967ede32f8d8f47d">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::LHS</a> and <a href="#a4ffbc71c3e39c4399dda0a5851cb4f78">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#afe20fb3ab3d91632fb61aee9810d28c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MatchContext&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatchContext &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a006f515fed3d399b72bd8868c4e66a9d">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::FirstIndex</a>, <a href="#ad5e409de0e66c9bc967ede32f8d8f47d">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a04ca771721b0090c8fbe9586a2d444f3">llvm::SDPatternMatch::m_Opc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a4ffbc71c3e39c4399dda0a5851cb4f78">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#af8425e06dcc0a862a898887c9baca083">llvm::SDPatternMatch::sd_context_match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a51dd9986ea8bee28540b1df8a63b3248">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LHS {#ad5e409de0e66c9bc967ede32f8d8f47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, typename Pred_t, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_P llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#afe20fb3ab3d91632fb61aee9810d28c5">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::match</a> and <a href="#a9bba0e99a1ab6572508c8a0de9ce3f56">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::MaxMin_match</a>.</p>

</div>
</div>

### RHS {#a4ffbc71c3e39c4399dda0a5851cb4f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, typename Pred_t, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_P llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#afe20fb3ab3d91632fb61aee9810d28c5">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::match</a> and <a href="#a9bba0e99a1ab6572508c8a0de9ce3f56">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::MaxMin_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
