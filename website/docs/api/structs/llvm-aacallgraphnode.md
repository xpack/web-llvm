---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aacallgraphnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AACallGraphNode` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::AACallGraphNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aacalledges">AACallEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract state for querying live call edges. <a href="/web-llvm/docs/api/structs/llvm/aacalledges/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/attributorcallgraph">AttributorCallGraph</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946922d2235f51b664625d2448b86fd1">AACallGraphNode</a> (Attributor &amp;A)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b3e9359b0bb063bea513e490c42377">~AACallGraphNode</a> ()=default</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aacalledgeiterator">AACallEdgeIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79a906eafdc3856ba315f2b6dce76c31">optimisticEdgesBegin</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aacalledgeiterator">AACallEdgeIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad110479c9135ae6d42993c3f20a1a30">optimisticEdgesEnd</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aacalledgeiterator">AACallEdgeIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbc2feeab4e7275d0da6e89c1a5083b">optimisticEdgesRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator range for exploring the call graph. <a href="#a4cbc2feeab4e7275d0da6e89c1a5083b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4ef3ee12c9d4b50e465f0559f11d94">A</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> needed for <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a> implementation. <a href="#acc4ef3ee12c9d4b50e465f0559f11d94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 5473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AACallGraphNode() {#a946922d2235f51b664625d2448b86fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AACallGraphNode::AACallGraphNode (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 5474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#acc4ef3ee12c9d4b50e465f0559f11d94">A</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aacalledges/#a061eb521951a3c4426a92749a949c0c3">llvm::AACallEdges::AACallEdges</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcallgraph/#a478a90d0012e9504327d5956f19c6e5f">llvm::AttributorCallGraph::AttributorCallGraph</a> and <a href="/web-llvm/docs/api/structs/llvm/attributorcallgraph/#a7f82d91f05496a622c3672de633ca06e">llvm::AttributorCallGraph::populateAll</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AACallGraphNode() {#ab0b3e9359b0bb063bea513e490c42377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::AACallGraphNode::~AACallGraphNode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### optimisticEdgesBegin() {#a79a906eafdc3856ba315f2b6dce76c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AACallEdgeIterator llvm::AACallGraphNode::optimisticEdgesBegin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a4cbc2feeab4e7275d0da6e89c1a5083b">optimisticEdgesRange</a>.</p>

</div>
</div>

### optimisticEdgesEnd() {#aad110479c9135ae6d42993c3f20a1a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AACallEdgeIterator llvm::AACallGraphNode::optimisticEdgesEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a4cbc2feeab4e7275d0da6e89c1a5083b">optimisticEdgesRange</a>.</p>

</div>
</div>

### optimisticEdgesRange() {#a4cbc2feeab4e7275d0da6e89c1a5083b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; AACallEdgeIterator &gt; llvm::AACallGraphNode::optimisticEdgesRange ()</td>
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

<p>Iterator range for exploring the call graph.</p>

<p>Definition at line 5481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5301a03dc90d7ac00440e2de4d9149">llvm::iterator_range</a>, <a href="#a79a906eafdc3856ba315f2b6dce76c31">optimisticEdgesBegin</a> and <a href="#aad110479c9135ae6d42993c3f20a1a30">optimisticEdgesEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributorcallgraph/#a7f82d91f05496a622c3672de633ca06e">llvm::AttributorCallGraph::populateAll</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### A {#acc4ef3ee12c9d4b50e465f0559f11d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attributor&amp; llvm::AACallGraphNode::A</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> needed for <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a> implementation.</p>

<p>Definition at line 5488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aacalledges/#a061eb521951a3c4426a92749a949c0c3">llvm::AACallEdges::AACallEdges</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a17d809dc5c92671e1846bb228d41cb8e">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::AACallEdgesCallSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgesfunction/#af445d163b1915c765a6f2f4a394f2821">anonymous{AttributorAttributes.cpp}::AACallEdgesFunction::AACallEdgesFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgesimpl/#a4b7c58e1c2a480ff3b8df2fdf07d4d34">anonymous{AttributorAttributes.cpp}::AACallEdgesImpl::AACallEdgesImpl</a>, <a href="#a946922d2235f51b664625d2448b86fd1">AACallGraphNode</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcallgraph/#a478a90d0012e9504327d5956f19c6e5f">llvm::AttributorCallGraph::AttributorCallGraph</a>, <a href="/web-llvm/docs/api/structs/llvm/aacalledges/#ac78a0034682b59931fdc73f43e2bce2e">llvm::AACallEdges::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgesimpl/#a82a780d19e91d177c7abb03373734f0e">anonymous{AttributorAttributes.cpp}::AACallEdgesImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/llvm/aacalledges/#a5363e1a37771d7d3c63c52414269411d">llvm::AACallEdges::optimisticEdgesBegin</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcallgraph/#a59e93d1dc3aa8adeabf756069f7ff4ea">llvm::AttributorCallGraph::optimisticEdgesBegin</a>, <a href="/web-llvm/docs/api/structs/llvm/aacalledges/#ab4231cc6286e8a21eb5de06bc6b214f6">llvm::AACallEdges::optimisticEdgesEnd</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcallgraph/#a30078bd86c0c23ade478f22f33780f76">llvm::AttributorCallGraph::optimisticEdgesEnd</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgesfunction/#a43bed485775922bde4815519e5f19d12">anonymous{AttributorAttributes.cpp}::AACallEdgesFunction::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
