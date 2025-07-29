---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/graph/nodeentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NodeEntry` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PBQP::Graph::NodeEntry { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f40d853ab21647a425daae22dbb0b05">AdjEdgeList</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367b965faabf02fbdb4f2a41d0d53f94">AdjEdgeIdx</a> = AdjEdgeList::size_type</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a996eb82e5e87e25706bafd75dca95849">AdjEdgeItr</a> = AdjEdgeList::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57cea1a256ef6f20a3ad42561f9035ed">NodeEntry</a> (VectorPtr Costs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AdjEdgeIdx</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474e218432dd82e703f73173e31dde66">addAdjEdgeId</a> (EdgeId EId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce40a8ce0a17c4aed8f8f17556063d7">removeAdjEdgeId</a> (Graph &amp;G, NodeId ThisNId, AdjEdgeIdx Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AdjEdgeList &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ddeae0eb683086cc287e2988bd0907f">getAdjEdgeIds</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#af286e5a878c03492516f4e8431e891a0">VectorPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573bbd958abda042ca0f7d2ef9557ee4">Costs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a8eef6dbaa0ecd31870bf94d9cd831368">NodeMetadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca45fed3c06ec67bb692e8cb9a17bfa7">Metadata</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AdjEdgeList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3511f293cf44cedfc6f5af94cbd69f46">AdjEdgeIds</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static AdjEdgeIdx</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5fb7b69f58258cec2097461f5aa444a">getInvalidAdjEdgeIdx</a> ()</td>
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


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AdjEdgeIdx {#a367b965faabf02fbdb4f2a41d0d53f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::AdjEdgeIdx =  AdjEdgeList::size_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### AdjEdgeItr {#a996eb82e5e87e25706bafd75dca95849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::AdjEdgeItr =  AdjEdgeList::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### AdjEdgeList {#a6f40d853ab21647a425daae22dbb0b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::AdjEdgeList =  std::vector&lt;EdgeId&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### NodeEntry() {#a57cea1a256ef6f20a3ad42561f9035ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::NodeEntry (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#af286e5a878c03492516f4e8431e891a0">VectorPtr</a> Costs)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAdjEdgeId() {#a474e218432dd82e703f73173e31dde66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AdjEdgeIdx llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::addAdjEdgeId (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getAdjEdgeIds() {#a2ddeae0eb683086cc287e2988bd0907f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AdjEdgeList &amp; llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::getAdjEdgeIds ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### removeAdjEdgeId() {#a2ce40a8ce0a17c4aed8f8f17556063d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::removeAdjEdgeId (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">Graph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> ThisNId, AdjEdgeIdx Idx)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Costs {#a573bbd958abda042ca0f7d2ef9557ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorPtr llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::Costs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Metadata {#aca45fed3c06ec67bb692e8cb9a17bfa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeMetadata llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::Metadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AdjEdgeIds {#a3511f293cf44cedfc6f5af94cbd69f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AdjEdgeList llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::AdjEdgeIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getInvalidAdjEdgeIdx() {#ae5fb7b69f58258cec2097461f5aa444a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AdjEdgeIdx llvm::PBQP::Graph&lt; SolverT &gt;::NodeEntry::getInvalidAdjEdgeIdx ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
