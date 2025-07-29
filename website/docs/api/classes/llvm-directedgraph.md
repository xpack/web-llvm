---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/directedgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DirectedGraph` Class Template

<p>Directed graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class NodeType, class EdgeType&gt;
class llvm::DirectedGraph&lt;NodeType, EdgeType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">llvm/ADT/DirectedGraph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac534088d4291ab854b63852ef2933a0e">iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">NodeListTy::iterator</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae450056d0541a0f2c92e2473ff9af0fd">const_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">NodeListTy::const_iterator</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae83d0831094229c006eee20c9a5a72a6">DGraphType</a> = <a href="/web-llvm/docs/api/classes/llvm/directedgraph">DirectedGraph</a>&lt; NodeType, EdgeType &gt;</td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a09f1993428448a8de6bf9061fd2034">NodeListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; NodeType *, 10 &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6afc6e56fb2d2de2ba5af33d78c86a4">EdgeListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; EdgeType *, 10 &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0702aea15e571527a7c8d8e991cf67aa">DirectedGraph</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af366bb2bb3a0b9a3d598a7ef58a05cd9">DirectedGraph</a> (NodeType &amp;N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afdf2f9523f80ce6f2c2bc3a41eabb1f3">DirectedGraph</a> (const DGraphType &amp;G)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac3926ad81b31b0030b212004f39b48a6">DirectedGraph</a> (DGraphType &amp;&amp;RHS)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae83d0831094229c006eee20c9a5a72a6">DGraphType</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ee052efd18140d0ddd528b107bc7fc3">operator=</a> (const DGraphType &amp;G)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae83d0831094229c006eee20c9a5a72a6">DGraphType</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15db37ef11444b1003a146fe6f981d76">operator=</a> (const DGraphType &amp;&amp;G)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae450056d0541a0f2c92e2473ff9af0fd">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5fdc2ae48087c2151d0ed6308d8b108">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae450056d0541a0f2c92e2473ff9af0fd">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab3c0979fab335e15b513420e0172bc2b">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ac534088d4291ab854b63852ef2933a0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27dadbce95ff10d0cb2ef04db532ac23">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ac534088d4291ab854b63852ef2933a0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bcdfd492bbe1bc88f18d8f22ca21f6d">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a177554653612aab6bc81185ca4cbb486">front</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a60ddabb94d5c0af7b8fd1f0c7820ca">front</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5463e4bf3ca6c89b6da34864d96fb856">back</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a349584d25113989f5f61ebf6095daac2">back</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e0b3a14471573dd16fad10439867b67">size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae450056d0541a0f2c92e2473ff9af0fd">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd2c323f0a073d8d2f7d1fe0d622967e">findNode</a> (const NodeType &amp;N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the given node <span class="doxyComputerOutput">N</span> in the table. <a href="#afd2c323f0a073d8d2f7d1fe0d622967e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ac534088d4291ab854b63852ef2933a0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8701256ecdf4d3b262d725798e38426">findNode</a> (const NodeType &amp;N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee99ddb71edafb342c13876e76e583b6">addNode</a> (NodeType &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given node <span class="doxyComputerOutput">N</span> to the graph if it is not already present. <a href="#aee99ddb71edafb342c13876e76e583b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a803c71157136a4df79e5422f83ae2c92">findIncomingEdgesToNode</a> (const NodeType &amp;N, SmallVectorImpl&lt; EdgeType * &gt; &amp;EL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect in <span class="doxyComputerOutput">EL</span> all edges that are coming into node <span class="doxyComputerOutput">N</span>. <a href="#a803c71157136a4df79e5422f83ae2c92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3d77f0eb55733fc66d9a8df01deeffb">removeNode</a> (NodeType &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the given node <span class="doxyComputerOutput">N</span> from the graph. <a href="#af3d77f0eb55733fc66d9a8df01deeffb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c10f9c736f10a83ae05b904bd2dbc5e">connect</a> (NodeType &amp;Src, NodeType &amp;Dst, EdgeType &amp;E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming nodes <span class="doxyComputerOutput">Src</span> and <span class="doxyComputerOutput">Dst</span> are already in the graph, connect node <span class="doxyComputerOutput">Src</span> to node <span class="doxyComputerOutput">Dst</span> using the provided edge <span class="doxyComputerOutput">E</span>. <a href="#a5c10f9c736f10a83ae05b904bd2dbc5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeType, class EdgeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a7a09f1993428448a8de6bf9061fd2034">NodeListTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d87b9ed8fcf69c438b9b82e7e07249f">Nodes</a></td>
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

<p>Directed graph.</p>


<p>The graph is represented by a table of nodes. Each node contains a (possibly empty) list of outgoing edges. Each edge contains the target node it connects to.</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ae450056d0541a0f2c92e2473ff9af0fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::const_iterator =  typename NodeListTy::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### DGraphType {#ae83d0831094229c006eee20c9a5a72a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::DGraphType =  DirectedGraph&lt;NodeType, EdgeType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### iterator {#ac534088d4291ab854b63852ef2933a0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::iterator =  typename NodeListTy::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Typedefs

### EdgeListTy {#af6afc6e56fb2d2de2ba5af33d78c86a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::EdgeListTy =  SmallVector&lt;EdgeType *, 10&gt;</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### NodeListTy {#a7a09f1993428448a8de6bf9061fd2034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::NodeListTy =  SmallVector&lt;NodeType *, 10&gt;</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DirectedGraph() {#a0702aea15e571527a7c8d8e991cf67aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::DirectedGraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### DirectedGraph() {#af366bb2bb3a0b9a3d598a7ef58a05cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::DirectedGraph (NodeType &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### DirectedGraph() {#afdf2f9523f80ce6f2c2bc3a41eabb1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::DirectedGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae83d0831094229c006eee20c9a5a72a6">DGraphType</a> &amp; G)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### DirectedGraph() {#ac3926ad81b31b0030b212004f39b48a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::DirectedGraph (<a href="#ae83d0831094229c006eee20c9a5a72a6">DGraphType</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a7ee052efd18140d0ddd528b107bc7fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DGraphType &amp; llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae83d0831094229c006eee20c9a5a72a6">DGraphType</a> &amp; G)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### operator=() {#a15db37ef11444b1003a146fe6f981d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DGraphType &amp; llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae83d0831094229c006eee20c9a5a72a6">DGraphType</a> &amp;&amp; G)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addNode() {#aee99ddb71edafb342c13876e76e583b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::addNode (NodeType &amp; N)</td>
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

<p>Add the given node <span class="doxyComputerOutput">N</span> to the graph if it is not already present.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>


<p>Referenced by <a href="#af366bb2bb3a0b9a3d598a7ef58a05cd9">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::DirectedGraph</a>.</p>

</div>
</div>

### back() {#a5463e4bf3ca6c89b6da34864d96fb856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeType &amp; llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::back ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### back() {#a349584d25113989f5f61ebf6095daac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeType &amp; llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::back ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### begin() {#aa5fdc2ae48087c2151d0ed6308d8b108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::begin ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-38f0d9ee1aa7305ed5af87e756e7c47c/#a106f0bc3178f2ec98666279ea184ceed">llvm::GraphTraits&lt; const DataDependenceGraph * &gt;::nodes_begin</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0fccf2316ed206f9ebb51a7519867590/#aa13c9afe0ffadf2ee5a733c6534d8010">llvm::GraphTraits&lt; DataDependenceGraph * &gt;::nodes_begin</a>.</p>

</div>
</div>

### begin() {#a27dadbce95ff10d0cb2ef04db532ac23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::begin ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### connect() {#a5c10f9c736f10a83ae05b904bd2dbc5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::connect (NodeType &amp; Src, NodeType &amp; Dst, EdgeType &amp; E)</td>
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

<p>Assuming nodes <span class="doxyComputerOutput">Src</span> and <span class="doxyComputerOutput">Dst</span> are already in the graph, connect node <span class="doxyComputerOutput">Src</span> to node <span class="doxyComputerOutput">Dst</span> using the provided edge <span class="doxyComputerOutput">E</span>.</p>


<p>Return true if <span class="doxyComputerOutput">Src</span> is not already connected to <span class="doxyComputerOutput">Dst</span> via <span class="doxyComputerOutput">E</span>, and false otherwise.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### end() {#ab3c0979fab335e15b513420e0172bc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::end ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-38f0d9ee1aa7305ed5af87e756e7c47c/#aa34956bede11bda28a23e87f6d84e0af">llvm::GraphTraits&lt; const DataDependenceGraph * &gt;::nodes_end</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0fccf2316ed206f9ebb51a7519867590/#a5d3263d4531caf414dc83680124225c4">llvm::GraphTraits&lt; DataDependenceGraph * &gt;::nodes_end</a>.</p>

</div>
</div>

### end() {#a2bcdfd492bbe1bc88f18d8f22ca21f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::end ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### findIncomingEdgesToNode() {#a803c71157136a4df79e5422f83ae2c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::findIncomingEdgesToNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp; N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; EdgeType * &gt; &amp; EL)</td>
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

<p>Collect in <span class="doxyComputerOutput">EL</span> all edges that are coming into node <span class="doxyComputerOutput">N</span>.</p>


<p>Return true if at least one edge was found, and false otherwise.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### findNode() {#afd2c323f0a073d8d2f7d1fe0d622967e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::findNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp; N)</td>
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

<p>Find the given node <span class="doxyComputerOutput">N</span> in the table.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>


<p>Referenced by <a href="#aee99ddb71edafb342c13876e76e583b6">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::addNode</a>, <a href="#a5c10f9c736f10a83ae05b904bd2dbc5e">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::connect</a> and <a href="#af3d77f0eb55733fc66d9a8df01deeffb">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::removeNode</a>.</p>

</div>
</div>

### findNode() {#af8701256ecdf4d3b262d725798e38426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::findNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp; N)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### front() {#a177554653612aab6bc81185ca4cbb486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeType &amp; llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::front ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### front() {#a5a60ddabb94d5c0af7b8fd1f0c7820ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeType &amp; llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::front ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### removeNode() {#af3d77f0eb55733fc66d9a8df01deeffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::removeNode (NodeType &amp; N)</td>
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

<p>Remove the given node <span class="doxyComputerOutput">N</span> from the graph.</p>


<p>If the node has incoming or outgoing edges, they are also removed. Return true if the node was found and then removed, and false if the node was not found in the graph to begin with.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

### size() {#a2e0b3a14471573dd16fad10439867b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::size ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Nodes {#a1d87b9ed8fcf69c438b9b82e7e07249f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeType, class EdgeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeListTy llvm::DirectedGraph&lt; NodeType, EdgeType &gt;::Nodes</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/directedgraph-h">DirectedGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
