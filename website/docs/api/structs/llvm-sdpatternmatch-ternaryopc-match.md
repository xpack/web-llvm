---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sdpatternmatch/ternaryopc-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TernaryOpc_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename T0_P, typename T1_P, typename T2_P, bool Commutable = false, bool ExcludeChain = false&gt;
struct llvm::SDPatternMatch::TernaryOpc_match&lt;T0_P, T1_P, T2_P, Commutable, ExcludeChain&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">llvm/CodeGen/SDPatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa6a08fff25c7f537f6f650d22e583d4f">TernaryOpc_match</a> (unsigned Opc, const T0_P &amp;Op0, const T1_P &amp;Op1, const T2_P &amp;Op2)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">match</a> (const MatchContext &amp;Ctx, SDValue N)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8cbd698f7ff18e6efa4dff0834273895">Opcode</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T0_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af988d82b1f5da0cd478c56230eca60f9">Op0</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T1_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63f8a1e8b6227eb47580d07c4967ea44">Op1</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T2_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6b5aa0865fbbcef3d1e2bab302b476d">Op2</a></td>
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


<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TernaryOpc\_match() {#aa6a08fff25c7f537f6f650d22e583d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0_P, typename T1_P, typename T2_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::TernaryOpc_match (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T0_P &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T1_P &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T2_P &amp; Op2)</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="#af988d82b1f5da0cd478c56230eca60f9">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op0</a>, <a href="#a63f8a1e8b6227eb47580d07c4967ea44">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op1</a>, <a href="#af6b5aa0865fbbcef3d1e2bab302b476d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op2</a> and <a href="#a8cbd698f7ff18e6efa4dff0834273895">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Opcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MatchContext&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatchContext &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a006f515fed3d399b72bd8868c4e66a9d">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::FirstIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a04ca771721b0090c8fbe9586a2d444f3">llvm::SDPatternMatch::m_Opc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#af988d82b1f5da0cd478c56230eca60f9">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op0</a>, <a href="#a63f8a1e8b6227eb47580d07c4967ea44">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op1</a>, <a href="#af6b5aa0865fbbcef3d1e2bab302b476d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op2</a>, <a href="#a8cbd698f7ff18e6efa4dff0834273895">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Opcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#af8425e06dcc0a862a898887c9baca083">llvm::SDPatternMatch::sd_context_match</a> and <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a51dd9986ea8bee28540b1df8a63b3248">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Op0 {#af988d82b1f5da0cd478c56230eca60f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0_P, typename T1_P, typename T2_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T0_P llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match</a> and <a href="#aa6a08fff25c7f537f6f650d22e583d4f">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::TernaryOpc_match</a>.</p>

</div>
</div>

### Op1 {#a63f8a1e8b6227eb47580d07c4967ea44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0_P, typename T1_P, typename T2_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T1_P llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match</a> and <a href="#aa6a08fff25c7f537f6f650d22e583d4f">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::TernaryOpc_match</a>.</p>

</div>
</div>

### Op2 {#af6b5aa0865fbbcef3d1e2bab302b476d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0_P, typename T1_P, typename T2_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T2_P llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Op2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match</a> and <a href="#aa6a08fff25c7f537f6f650d22e583d4f">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::TernaryOpc_match</a>.</p>

</div>
</div>

### Opcode {#a8cbd698f7ff18e6efa4dff0834273895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0_P, typename T1_P, typename T2_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match</a> and <a href="#aa6a08fff25c7f537f6f650d22e583d4f">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::TernaryOpc_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
