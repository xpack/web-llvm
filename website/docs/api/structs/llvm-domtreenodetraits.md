---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/domtreenodetraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DomTreeNodeTraits` Struct Template Reference

<p>Default <a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> traits for NodeT. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename NodeT&gt;
struct llvm::DomTreeNodeTraits&lt;NodeT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">llvm/Support/GenericDomTree.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f4a8f1e3f372682f0bc52c828c28160">NodeType</a> = NodeT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6438844cf5e526b96bcfb705557326a">NodePtr</a> = NodeT *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac36af8e8bb30f50952a2f054f2c355c9">ParentPtr</a> = decltype(std::declval&lt; <a href="#ab6438844cf5e526b96bcfb705557326a">NodePtr</a> &gt;() -&gt;<a href="#a8f9e8de70b85652f39faf9f172e2f6ed">getParent</a>())</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83105f5177c39c1a9adfed93b33db8a5">ParentType</a> = std::remove_pointer_t&lt; <a href="#ac36af8e8bb30f50952a2f054f2c355c9">ParentPtr</a> &gt;</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4131d2483296222e1cfb1378b3dfeb5d">getEntryNode</a> (ParentPtr Parent)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#ac36af8e8bb30f50952a2f054f2c355c9">ParentPtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8f9e8de70b85652f39faf9f172e2f6ed">getParent</a> (NodePtr BB)</td>
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

<p>Default <a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> traits for NodeT.</p>


<p>The default implementation assume a Function-like NodeT. Can be specialized to support different node types.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NodePtr {#ab6438844cf5e526b96bcfb705557326a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeNodeTraits&lt; NodeT &gt;::NodePtr =  NodeT *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### NodeType {#a3f4a8f1e3f372682f0bc52c828c28160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeNodeTraits&lt; NodeT &gt;::NodeType =  NodeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### ParentPtr {#ac36af8e8bb30f50952a2f054f2c355c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeNodeTraits&lt; NodeT &gt;::ParentPtr =  decltype(std::declval&lt;NodePtr&gt;()-&gt;getParent())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### ParentType {#a83105f5177c39c1a9adfed93b33db8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeNodeTraits&lt; NodeT &gt;::ParentType =  std::remove_pointer_t&lt;ParentPtr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEntryNode() {#a4131d2483296222e1cfb1378b3dfeb5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT * llvm::DomTreeNodeTraits&lt; NodeT &gt;::getEntryNode (<a href="#ac36af8e8bb30f50952a2f054f2c355c9">ParentPtr</a> Parent)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a26cf1d2b810e0413369fda9759618123">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>.</p>

</div>
</div>

### getParent() {#a8f9e8de70b85652f39faf9f172e2f6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParentPtr llvm::DomTreeNodeTraits&lt; NodeT &gt;::getParent (<a href="#ab6438844cf5e526b96bcfb705557326a">NodePtr</a> BB)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ab0f09aefdf088f84a0bff7cba86454b4">llvm::DominatorTreeBase&lt; BlockT, false &gt;::deleteEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a26cf1d2b810e0413369fda9759618123">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; BlockT, false &gt;::getNode</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a51145a3ae24ea73b3692a17088edea7b">llvm::DominatorTreeBase&lt; BlockT, false &gt;::insertEdge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
