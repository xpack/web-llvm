---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/forwarddominancefrontierbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ForwardDominanceFrontierBase` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/dominancefrontier">DominanceFrontier</a> Class - Concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierbase">DominanceFrontierBase</a> that is used to compute a forward dominator frontiers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class BlockT&gt;
class llvm::ForwardDominanceFrontierBase&lt;BlockT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">llvm/Analysis/DominanceFrontier.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominancefrontierbase">DominanceFrontierBase&lt;BlockT, IsPostDom&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dominancefrontierbase">DominanceFrontierBase</a> - Common base class for computing forward and inverse dominance frontiers for a function. <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae84b3634196c2de69e55ecb00e91df41">DomTreeT</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a763915fd0a536cc2d1ebe99595e3eeaf">DomTreeBase</a>&lt; BlockT &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af065017878424f9b3de1ceb1a993771b">DomTreeNodeT</a> = <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; BlockT &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae31d0f6fdc554301489b6c46bfc54389">DomSetType</a> = typename <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierbase">DominanceFrontierBase</a>&lt; BlockT, false &gt;::DomSetType</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2fa49cebc5f0cf0c983c09c2a4b43e4d">BlockTraits</a> = <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; BlockT * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b11dff80facdebb843d875cee482164">analyze</a> (DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae31d0f6fdc554301489b6c46bfc54389">DomSetType</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63025518f7389e16eca9b9fa4400fed7">calculate</a> (const DomTreeT &amp;DT, const DomTreeNodeT *Node)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dominancefrontier">DominanceFrontier</a> Class - Concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierbase">DominanceFrontierBase</a> that is used to compute a forward dominator frontiers.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DomSetType {#ae31d0f6fdc554301489b6c46bfc54389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::DomSetType =  typename DominanceFrontierBase&lt;BlockT, false&gt;::DomSetType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a>.</p>

</div>
</div>

### DomTreeNodeT {#af065017878424f9b3de1ceb1a993771b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::DomTreeNodeT =  DomTreeNodeBase&lt;BlockT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a>.</p>

</div>
</div>

### DomTreeT {#ae84b3634196c2de69e55ecb00e91df41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::DomTreeT =  DomTreeBase&lt;BlockT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### BlockTraits {#a2fa49cebc5f0cf0c983c09c2a4b43e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::BlockTraits =  GraphTraits&lt;BlockT *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyze() {#a7b11dff80facdebb843d875cee482164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::analyze (<a href="#ae84b3634196c2de69e55ecb00e91df41">DomTreeT</a> &amp; DT)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a63025518f7389e16eca9b9fa4400fed7">llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a81f7fe4844c408d799428082f599c40b">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a35f8ede9f06d54f789edb2507f174701">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::root_size</a> and <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierbase/#a76c88d34854e3ad810f148be417749bf">llvm::DominanceFrontierBase&lt; BlockT, false &gt;::Roots</a>.</p>

</div>
</div>

### calculate() {#a63025518f7389e16eca9b9fa4400fed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ForwardDominanceFrontierBase&lt; BlockT &gt;::DomSetType &amp; llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::calculate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae84b3634196c2de69e55ecb00e91df41">DomTreeT</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af065017878424f9b3de1ceb1a993771b">DomTreeNodeT</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a>.</p>


<p>Referenced by <a href="#a7b11dff80facdebb843d875cee482164">llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::analyze</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">DominanceFrontier.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontierimpl-h">DominanceFrontierImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
