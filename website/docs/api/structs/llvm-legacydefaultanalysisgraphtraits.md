---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/legacydefaultanalysisgraphtraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LegacyDefaultAnalysisGraphTraits` Struct Template Reference

<p>Default traits class for extracting a graph from an analysis pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename AnalysisT, typename GraphT = AnalysisT *&gt;
struct llvm::LegacyDefaultAnalysisGraphTraits&lt;AnalysisT, GraphT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">llvm/Analysis/DOTGraphTraitsPass.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisT, typename GraphT = AnalysisT *&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static GraphT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25bb060af631f8ce1962b733c87d25ab">getGraph</a> (AnalysisT *A)</td>
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

## Description {#details}

<p>Default traits class for extracting a graph from an analysis pass.</p>


<p>This assumes that 'GraphT' is 'AnalysisT *' and so just passes it through.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getGraph() {#a25bb060af631f8ce1962b733c87d25ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, typename GraphT = AnalysisT *&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GraphT llvm::LegacyDefaultAnalysisGraphTraits&lt; AnalysisT, GraphT &gt;::getGraph (AnalysisT * A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
