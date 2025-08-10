---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sdpatternmatch/binaryopc-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BinaryOpc_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename LHS_P, typename RHS_P, bool Commutable = false, bool ExcludeChain = false&gt;
struct llvm::SDPatternMatch::BinaryOpc_match&lt;LHS_P, RHS_P, Commutable, ExcludeChain&gt; { ... }
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a6e39a6cd9def7dd08dd19634a92ccc2b">BinaryOpc_match</a> (unsigned Opc, const LHS_P &amp;L, const RHS_P &amp;R, std::optional&lt; SDNodeFlags &gt; Flgs=std::nullopt)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a5a03d05823f04a24f6f7b509f55882">match</a> (const MatchContext &amp;Ctx, SDValue N)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a38a705622904979f9fd4537ae5fe3599">Opcode</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LHS_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab195cd9942224df18b06ecd73f9ed825">LHS</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa53f680d7745f1cd14f6bc1df1b0538">RHS</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e29d36c0cf7c6a4b16e0c954fe2a457">Flags</a></td>
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


<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinaryOpc\_match() {#a6e39a6cd9def7dd08dd19634a92ccc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::BinaryOpc_match (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LHS_P &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RHS_P &amp; R, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> &gt; Flgs=std::nullopt)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="#a2e29d36c0cf7c6a4b16e0c954fe2a457">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::Flags</a>, <a href="#ab195cd9942224df18b06ecd73f9ed825">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::LHS</a>, <a href="#a38a705622904979f9fd4537ae5fe3599">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::Opcode</a> and <a href="#aaa53f680d7745f1cd14f6bc1df1b0538">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a1a5a03d05823f04a24f6f7b509f55882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MatchContext&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatchContext &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a006f515fed3d399b72bd8868c4e66a9d">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::FirstIndex</a>, <a href="#a2e29d36c0cf7c6a4b16e0c954fe2a457">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::Flags</a>, <a href="#ab195cd9942224df18b06ecd73f9ed825">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a04ca771721b0090c8fbe9586a2d444f3">llvm::SDPatternMatch::m_Opc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a38a705622904979f9fd4537ae5fe3599">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::Opcode</a>, <a href="#aaa53f680d7745f1cd14f6bc1df1b0538">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#af8425e06dcc0a862a898887c9baca083">llvm::SDPatternMatch::sd_context_match</a> and <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a51dd9986ea8bee28540b1df8a63b3248">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a2e29d36c0cf7c6a4b16e0c954fe2a457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;SDNodeFlags&gt; llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a6e39a6cd9def7dd08dd19634a92ccc2b">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::BinaryOpc_match</a> and <a href="#a1a5a03d05823f04a24f6f7b509f55882">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match</a>.</p>

</div>
</div>

### LHS {#ab195cd9942224df18b06ecd73f9ed825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LHS_P llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a6e39a6cd9def7dd08dd19634a92ccc2b">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::BinaryOpc_match</a> and <a href="#a1a5a03d05823f04a24f6f7b509f55882">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match</a>.</p>

</div>
</div>

### Opcode {#a38a705622904979f9fd4537ae5fe3599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a6e39a6cd9def7dd08dd19634a92ccc2b">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::BinaryOpc_match</a> and <a href="#a1a5a03d05823f04a24f6f7b509f55882">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match</a>.</p>

</div>
</div>

### RHS {#aaa53f680d7745f1cd14f6bc1df1b0538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LHS_P, typename RHS_P, bool Commutable = false, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RHS_P llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#a6e39a6cd9def7dd08dd19634a92ccc2b">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::BinaryOpc_match</a> and <a href="#a1a5a03d05823f04a24f6f7b509f55882">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match</a>.</p>

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
