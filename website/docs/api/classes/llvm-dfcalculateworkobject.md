---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dfcalculateworkobject
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DFCalculateWorkObject` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;class BlockT&gt;
class llvm::DFCalculateWorkObject&lt;BlockT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">llvm/Analysis/DominanceFrontierImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab02d6c0a90783a1dfc8b8fd75579c493">DomTreeNodeT</a> = <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; BlockT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1132cf43c02abb0420eab44af77251f1">DFCalculateWorkObject</a> (BlockT *B, BlockT *P, const DomTreeNodeT *N, const DomTreeNodeT *PN)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b3b092b3c1c141ae74dd8d70ebdfde8">currentBB</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5ac197048620957a1ed454a3dc17f53">parentBB</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab02d6c0a90783a1dfc8b8fd75579c493">DomTreeNodeT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae183a7156a64a865c49ff67d117fd3bd">Node</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab02d6c0a90783a1dfc8b8fd75579c493">DomTreeNodeT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2798432847aeceedbd0d17b99d75ca58">parentNode</a></td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DomTreeNodeT {#ab02d6c0a90783a1dfc8b8fd75579c493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DFCalculateWorkObject&lt; BlockT &gt;::DomTreeNodeT =  DomTreeNodeBase&lt;BlockT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DFCalculateWorkObject() {#a1132cf43c02abb0420eab44af77251f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DFCalculateWorkObject&lt; BlockT &gt;::DFCalculateWorkObject (BlockT * B, BlockT * P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab02d6c0a90783a1dfc8b8fd75579c493">DomTreeNodeT</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab02d6c0a90783a1dfc8b8fd75579c493">DomTreeNodeT</a> * PN)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1b3b092b3c1c141ae74dd8d70ebdfde8">llvm::DFCalculateWorkObject&lt; BlockT &gt;::currentBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ae183a7156a64a865c49ff67d117fd3bd">llvm::DFCalculateWorkObject&lt; BlockT &gt;::Node</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#af5ac197048620957a1ed454a3dc17f53">llvm::DFCalculateWorkObject&lt; BlockT &gt;::parentBB</a> and <a href="#a2798432847aeceedbd0d17b99d75ca58">llvm::DFCalculateWorkObject&lt; BlockT &gt;::parentNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### currentBB {#a1b3b092b3c1c141ae74dd8d70ebdfde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT* llvm::DFCalculateWorkObject&lt; BlockT &gt;::currentBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>


<p>Referenced by <a href="#a1132cf43c02abb0420eab44af77251f1">llvm::DFCalculateWorkObject&lt; BlockT &gt;::DFCalculateWorkObject</a>.</p>

</div>
</div>

### Node {#ae183a7156a64a865c49ff67d117fd3bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DomTreeNodeT* llvm::DFCalculateWorkObject&lt; BlockT &gt;::Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>


<p>Referenced by <a href="#a1132cf43c02abb0420eab44af77251f1">llvm::DFCalculateWorkObject&lt; BlockT &gt;::DFCalculateWorkObject</a>.</p>

</div>
</div>

### parentBB {#af5ac197048620957a1ed454a3dc17f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT* llvm::DFCalculateWorkObject&lt; BlockT &gt;::parentBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>


<p>Referenced by <a href="#a1132cf43c02abb0420eab44af77251f1">llvm::DFCalculateWorkObject&lt; BlockT &gt;::DFCalculateWorkObject</a>.</p>

</div>
</div>

### parentNode {#a2798432847aeceedbd0d17b99d75ca58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DomTreeNodeT* llvm::DFCalculateWorkObject&lt; BlockT &gt;::parentNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>


<p>Referenced by <a href="#a1132cf43c02abb0420eab44af77251f1">llvm::DFCalculateWorkObject&lt; BlockT &gt;::DFCalculateWorkObject</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
