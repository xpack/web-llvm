---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xray/graph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Graph` Class Template

<p>A <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a> object represents a Directed <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a> and is used in XRay to compute and store function call graphs and associated statistical information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;
class llvm::xray::Graph&lt;VertexAttribute, EdgeAttribute, VI&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">llvm/XRay/Graph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">VI <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These objects are used to name edges and vertices in the graph. <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">std::pair&lt; VI, VI &gt; <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d690636cf7cdf754037819e22c6eed8">VertexValueType</a> = <a href="/web-llvm/docs/api/structs/llvm/detail/densemappair">detail::DenseMapPair</a>&lt; <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a>, VertexAttribute &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This type is the value_type of all iterators which range over vertices, Determined by the Vertices <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>. <a href="#a9d690636cf7cdf754037819e22c6eed8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> = <a href="/web-llvm/docs/api/structs/llvm/detail/densemappair">detail::DenseMapPair</a>&lt; <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a>, EdgeAttribute &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This type is the value_type of all iterators which range over edges, Determined by the Edges <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>. <a href="#af3591e0d96718a0f1b28a7e3b7d8705a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a54673fcf8298aefa4e10707b86123391">size_type</a> = std::size_t</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5043d96a53eddd19ffcbd9baa4be1f33">ConstInEdgeIterator</a> = NeighborEdgeIteratorT&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A const iterator type for iterating through the set of edges entering a vertex. <a href="#a5043d96a53eddd19ffcbd9baa4be1f33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a66ac965d888a7c7419082546e1270091">InEdgeIterator</a> = NeighborEdgeIteratorT&lt; false, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An iterator type for iterating through the set of edges leaving a vertex. <a href="#a66ac965d888a7c7419082546e1270091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62ab3aace08cd6e4243731012d2eb737">ConstOutEdgeIterator</a> = NeighborEdgeIteratorT&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A const iterator type for iterating through the set of edges entering a vertex. <a href="#a62ab3aace08cd6e4243731012d2eb737">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bc58a2e3704bca6457211da14ea579a">OutEdgeIterator</a> = NeighborEdgeIteratorT&lt; false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An iterator type for iterating through the set of edges leaving a vertex. <a href="#a2bc58a2e3704bca6457211da14ea579a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1b3a96bffc932e4dbedcd66b9951b02">ConstVertexIterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a5784c312872bef21d9344dae0a0e8fc0">VertexMapT::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A const iterator type for iterating through the whole vertex set of the graph. <a href="#ad1b3a96bffc932e4dbedcd66b9951b02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a755f8ce931504b6bde92bd3d9500d0f3">VertexIterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a214e872d61db2ea8cb023f127cafd0b9">VertexMapT::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An iterator type for iterating through the whole vertex set of the graph. <a href="#a755f8ce931504b6bde92bd3d9500d0f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9157284e108b7e443924f66a19e73b0c">ConstEdgeIterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a5784c312872bef21d9344dae0a0e8fc0">EdgeMapT::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A const iterator for iterating through the entire edge set of the graph. <a href="#a9157284e108b7e443924f66a19e73b0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5874033ed1dc6d8d2b4583d3db0c7bf">EdgeIterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a214e872d61db2ea8cb023f127cafd0b9">EdgeMapT::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An iterator for iterating through the entire edge set of the graph. <a href="#ad5874033ed1dc6d8d2b4583d3db0c7bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3295e34dd86dd261fd632f9ffec111ab">EdgeMapT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a>, EdgeAttribute &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type used for storing the EdgeAttribute for each edge in the graph. <a href="#a3295e34dd86dd261fd632f9ffec111ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a86044cbc31bc0804c8280fff6910d706">VertexMapT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a>, VertexAttribute &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type used for storing the VertexAttribute for each vertex in the graph. <a href="#a86044cbc31bc0804c8280fff6910d706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab567d93df9a9d4330e4b2bea80450040">NeighborSetT</a> = <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type used for storing the edges entering a vertex. <a href="#ab567d93df9a9d4330e4b2bea80450040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ec8b44a628767e9f8e6c76903d738fb">NeighborLookupT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/denseset">NeighborSetT</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type storing the InnerInvGraphT corresponding to each vertex in the graph (When a vertex has an incoming edge incident to it) <a href="#a4ec8b44a628767e9f8e6c76903d738fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">VertexAttribute &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd1f5cdb03235fd278b187b33ddc42cf">operator[]</a> (const VertexIdentifier &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up the vertex with identifier I, if it does not exist it default constructs it. <a href="#abd1f5cdb03235fd278b187b33ddc42cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">EdgeAttribute &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0bdb5839e8a3935e3a80373c053dfd87">operator[]</a> (const EdgeIdentifier &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up the edge with identifier I, if it does not exist it default constructs it, if it's endpoints do not exist it also default constructs them. <a href="#a0bdb5839e8a3935e3a80373c053dfd87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4c5b8f18fe884f08a1cb2bb9baf4cea0">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Empty the <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a>. <a href="#a4c5b8f18fe884f08a1cb2bb9baf4cea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a224fda303f76fc909404743b24fda297">vertices</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/vertexview">VertexView</a>&lt; false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a view object allowing iteration over the vertices of the graph. <a href="#a224fda303f76fc909404743b24fda297">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac06ecd496d7ee841363ab0daa9852f83">vertices</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/vertexview">VertexView</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5bf62c6f5a93eed499233f9aeaebeff4">edges</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/edgeview">EdgeView</a>&lt; false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a view object allowing iteration over the edges of the graph. <a href="#a5bf62c6f5a93eed499233f9aeaebeff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d3b1fc5fa1331c92d848ffa165036f0">edges</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/edgeview">EdgeView</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff1b9575f8ffc028ecc11a03752231b6">outEdges</a> (const VertexIdentifier I) -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/inoutedgeview">InOutEdgeView</a>&lt; false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a view object allowing iteration over the edges which start at a vertex I. <a href="#aff1b9575f8ffc028ecc11a03752231b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a397ffcfd063bf829741b7b0491d6ccdb">outEdges</a> (const VertexIdentifier I) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/inoutedgeview">InOutEdgeView</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78beebc3a96e045b525328f2668a98ed">inEdges</a> (const VertexIdentifier I) -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/inoutedgeview">InOutEdgeView</a>&lt; false, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a view object allowing iteration over the edges which point to a vertex I. <a href="#a78beebc3a96e045b525328f2668a98ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7541e92af7bf828643cbf535f6b8bfd">inEdges</a> (const VertexIdentifier I) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/xray/graph/inoutedgeview">InOutEdgeView</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa99875b753d8f7de2424d5a16f4f6311">at</a> (const VertexIdentifier &amp;I) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; VertexAttribute &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up a vertex with Identifier I, or an error if it does not exist. <a href="#aa99875b753d8f7de2424d5a16f4f6311">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4327672d888282e6652fbfd9d2ff453">at</a> (const VertexIdentifier &amp;I) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VertexAttribute &amp; &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc64b3ff5029254a295ae690242f951a">at</a> (const EdgeIdentifier &amp;I) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; EdgeAttribute &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up an edge with Identifier I, or an error if it does not exist. <a href="#afc64b3ff5029254a295ae690242f951a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af994001328142a30b87b6080a057c2cb">at</a> (const EdgeIdentifier &amp;I) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> EdgeAttribute &amp; &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a54673fcf8298aefa4e10707b86123391">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d7a0fc576121934102c3bf9f738e024">count</a> (const VertexIdentifier &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks for a vertex with identifier I, returns 1 if one exists, and 0 otherwise. <a href="#a4d7a0fc576121934102c3bf9f738e024">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a54673fcf8298aefa4e10707b86123391">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b05b885e5ea127c6f75fa5a65c0e3e2">count</a> (const EdgeIdentifier &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks for an edge with Identifier I, returns 1 if one exists and 0 otherwise. <a href="#a4b05b885e5ea127c6f75fa5a65c0e3e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a933fbf8a7ab093dbef65a60ff59f9814">insert</a> (const std::pair&lt; VertexIdentifier, VertexAttribute &gt; &amp;Val) -&gt; std::pair&lt; <a href="#a755f8ce931504b6bde92bd3d9500d0f3">VertexIterator</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts a vertex into the graph with Identifier Val.first, and <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Val.second. <a href="#a933fbf8a7ab093dbef65a60ff59f9814">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1fbed973b7d9d8d38e1ab8112d111f50">insert</a> (std::pair&lt; VertexIdentifier, VertexAttribute &gt; &amp;&amp;Val) -&gt; std::pair&lt; <a href="#a755f8ce931504b6bde92bd3d9500d0f3">VertexIterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b0b00af1e169ae0720380560c6e2610">insert</a> (const std::pair&lt; EdgeIdentifier, EdgeAttribute &gt; &amp;Val) -&gt; std::pair&lt; <a href="#ad5874033ed1dc6d8d2b4583d3db0c7bf">EdgeIterator</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts an edge into the graph with Identifier Val.first, and <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Val.second. <a href="#a0b0b00af1e169ae0720380560c6e2610">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a085b9fe5336c4d3f35328dce8033555d">insert</a> (std::pair&lt; EdgeIdentifier, EdgeAttribute &gt; &amp;&amp;Val) -&gt; std::pair&lt; <a href="#ad5874033ed1dc6d8d2b4583d3db0c7bf">EdgeIterator</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts an edge into the graph with Identifier Val.first, and <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Val.second. <a href="#a085b9fe5336c4d3f35328dce8033555d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">EdgeMapT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a846dc042de180fc8cb58f4ed2d53c139">Edges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the map from the start and end vertex of an edge to it's EdgeAttribute. <a href="#a846dc042de180fc8cb58f4ed2d53c139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">VertexMapT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e3bdf0d646ea2a7b3194dd45d5ca2ed">Vertices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the map from <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> to VertexAttribute. <a href="#a7e3bdf0d646ea2a7b3194dd45d5ca2ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">NeighborLookupT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69eec28d4c653bb5cf11f59100707acd">InNeighbors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows fast lookup for the incoming edge set of any given vertex. <a href="#a69eec28d4c653bb5cf11f59100707acd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">NeighborLookupT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4170c27a500caf5c1c78259661318497">OutNeighbors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows fast lookup for the outgoing edge set of any given vertex. <a href="#a4170c27a500caf5c1c78259661318497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a> object represents a Directed <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a> and is used in XRay to compute and store function call graphs and associated statistical information.</p>


<p>The graph takes in four template parameters, these are:</p>


<ul class="doxyList ">
<li>VertexAttribute, this is a structure which is stored for each vertex. Must be DefaultConstructible, CopyConstructible, CopyAssignable and Destructible.</li>
<li>EdgeAttribute, this is a structure which is stored for each edge Must be DefaultConstructible, CopyConstructible, CopyAssignable and Destructible.</li>
<li>EdgeAttribute, this is a structure which is stored for each variable</li>
<li>VI, this is a type over which <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> is defined and is the type used look up strings, available as <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a>.</li>
<li>If the built in <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> is not defined, provide a specialization class type here.</li>
</ul>

<p><a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a> is CopyConstructible, CopyAssignable, MoveConstructible and MoveAssignable but is not EqualityComparible or LessThanComparible.</p>


<p>Usage Example <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a> with weighted edges and vertices: <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph&lt;int, int, int&gt;</a> G;</p>


<p>G[1] = 0; G[2] = 2; G[{1,2}] = 1; G[{2,1}] = -1; for(const auto &amp;v : G.vertices()){ // Do something with the vertices in the graph; } for(const auto &amp;e : G.edges()){ // Do something with the edges in the graph; }</p>


<p>Usage Example with StrRef keys. <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph&lt;int, double, StrRef&gt;</a> StrG; char va[] = "Vertex A"; char vaa[] = "Vertex A"; char vb[] = "Vertex B"; // Vertices are referenced by String Refs. G[va] = 0; G[vb] = 1; G[{va, vb}] = 1.0; cout() &lt;&lt; G[vaa] &lt;&lt; " " &lt;&lt; G[{vaa, vb}]; //prints "0 1.0".</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ConstEdgeIterator {#a9157284e108b7e443924f66a19e73b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::ConstEdgeIterator =  typename EdgeMapT::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A const iterator for iterating through the entire edge set of the graph.</p>


<p>Has a const <a href="#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> as its value_type</p>


<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### ConstInEdgeIterator {#a5043d96a53eddd19ffcbd9baa4be1f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::ConstInEdgeIterator =  NeighborEdgeIteratorT&lt;true, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A const iterator type for iterating through the set of edges entering a vertex.</p>


<p>Has a const <a href="#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> as its value_type</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### ConstOutEdgeIterator {#a62ab3aace08cd6e4243731012d2eb737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::ConstOutEdgeIterator =  NeighborEdgeIteratorT&lt;true, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A const iterator type for iterating through the set of edges entering a vertex.</p>


<p>Has a const <a href="#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> as its value_type</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### ConstVertexIterator {#ad1b3a96bffc932e4dbedcd66b9951b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::ConstVertexIterator =  typename VertexMapT::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A const iterator type for iterating through the whole vertex set of the graph.</p>


<p>Has a const <a href="#a9d690636cf7cdf754037819e22c6eed8">VertexValueType</a> as its value_type</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### EdgeIdentifier {#af18457e2a495ea45229584fa1c471cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::pair&lt;VI, VI&gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::EdgeIdentifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### EdgeIterator {#ad5874033ed1dc6d8d2b4583d3db0c7bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::EdgeIterator =  typename EdgeMapT::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An iterator for iterating through the entire edge set of the graph.</p>


<p>Has an <a href="#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> as its value_type</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### EdgeValueType {#af3591e0d96718a0f1b28a7e3b7d8705a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::EdgeValueType =  detail::DenseMapPair&lt;EdgeIdentifier, EdgeAttribute&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This type is the value_type of all iterators which range over edges, Determined by the Edges <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### InEdgeIterator {#a66ac965d888a7c7419082546e1270091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::InEdgeIterator =  NeighborEdgeIteratorT&lt;false, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An iterator type for iterating through the set of edges leaving a vertex.</p>


<p>Has an <a href="#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> as its value_type</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### OutEdgeIterator {#a2bc58a2e3704bca6457211da14ea579a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::OutEdgeIterator =  NeighborEdgeIteratorT&lt;false, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An iterator type for iterating through the set of edges leaving a vertex.</p>


<p>Has an <a href="#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> as its value_type</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### size\_type {#a54673fcf8298aefa4e10707b86123391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::size_type =  std::size_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### VertexIdentifier {#aa7d4f1e9198ebd47ab0fc3cef797ac86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef VI llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::VertexIdentifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These objects are used to name edges and vertices in the graph.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### VertexIterator {#a755f8ce931504b6bde92bd3d9500d0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::VertexIterator =  typename VertexMapT::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An iterator type for iterating through the whole vertex set of the graph.</p>


<p>Has a <a href="#a9d690636cf7cdf754037819e22c6eed8">VertexValueType</a> as its value_type</p>


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### VertexValueType {#a9d690636cf7cdf754037819e22c6eed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::VertexValueType = 
      detail::DenseMapPair&lt;VertexIdentifier, VertexAttribute&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This type is the value_type of all iterators which range over vertices, Determined by the Vertices <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### EdgeMapT {#a3295e34dd86dd261fd632f9ffec111ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::EdgeMapT =  DenseMap&lt;EdgeIdentifier, EdgeAttribute&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type used for storing the EdgeAttribute for each edge in the graph.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### NeighborLookupT {#a4ec8b44a628767e9f8e6c76903d738fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborLookupT =  DenseMap&lt;VertexIdentifier, NeighborSetT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type storing the InnerInvGraphT corresponding to each vertex in the graph (When a vertex has an incoming edge incident to it)</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### NeighborSetT {#ab567d93df9a9d4330e4b2bea80450040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborSetT =  DenseSet&lt;VertexIdentifier&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type used for storing the edges entering a vertex.</p>


<p>Indexed by the <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> of the start of the edge. Only used to determine where the incoming edges are, the EdgeIdentifiers are stored in an InnerEdgeMapT.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### VertexMapT {#a86044cbc31bc0804c8280fff6910d706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::VertexMapT =  DenseMap&lt;VertexIdentifier, VertexAttribute&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type used for storing the VertexAttribute for each vertex in the graph.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#abd1f5cdb03235fd278b187b33ddc42cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VertexAttribute &amp; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> &amp; I)</td>
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

<p>Looks up the vertex with identifier I, if it does not exist it default constructs it.</p>

<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### operator\[\]() {#a0bdb5839e8a3935e3a80373c053dfd87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeAttribute &amp; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a> &amp; I)</td>
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

<p>Looks up the edge with identifier I, if it does not exist it default constructs it, if it's endpoints do not exist it also default constructs them.</p>

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### at() {#aa99875b753d8f7de2424d5a16f4f6311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; VertexAttribute &amp; &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::at (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> &amp; I)</td>
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

<p>Looks up a vertex with Identifier I, or an error if it does not exist.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### at() {#aa4327672d888282e6652fbfd9d2ff453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const VertexAttribute &amp; &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::at (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> &amp; I)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### at() {#afc64b3ff5029254a295ae690242f951a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; EdgeAttribute &amp; &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::at (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a> &amp; I)</td>
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

<p>Looks up an edge with Identifier I, or an error if it does not exist.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### at() {#af994001328142a30b87b6080a057c2cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const EdgeAttribute &amp; &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::at (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a> &amp; I)</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### clear() {#a4c5b8f18fe884f08a1cb2bb9baf4cea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::clear ()</td>
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

<p>Empty the <a href="/web-llvm/docs/api/classes/llvm/xray/graph">Graph</a>.</p>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### count() {#a4d7a0fc576121934102c3bf9f738e024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> &amp; I)</td>
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

<p>Looks for a vertex with identifier I, returns 1 if one exists, and 0 otherwise.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### count() {#a4b05b885e5ea127c6f75fa5a65c0e3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a> &amp; I)</td>
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

<p>Looks for an edge with Identifier I, returns 1 if one exists and 0 otherwise.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### edges() {#a5bf62c6f5a93eed499233f9aeaebeff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeView&lt; false &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::edges ()</td>
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

<p>Returns a view object allowing iteration over the edges of the graph.</p>


<p>also allows access to the size of the edge set.</p>


<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### edges() {#a4d3b1fc5fa1331c92d848ffa165036f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeView&lt; true &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::edges ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### inEdges() {#a78beebc3a96e045b525328f2668a98ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InOutEdgeView&lt; false, false &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::inEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> I)</td>
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

<p>Returns a view object allowing iteration over the edges which point to a vertex I.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### inEdges() {#ac7541e92af7bf828643cbf535f6b8bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InOutEdgeView&lt; true, false &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::inEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> I)</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### insert() {#a933fbf8a7ab093dbef65a60ff59f9814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; VertexIterator, bool &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a>, VertexAttribute &gt; &amp; Val)</td>
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

<p>Inserts a vertex into the graph with Identifier Val.first, and <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Val.second.</p>

<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### insert() {#a1fbed973b7d9d8d38e1ab8112d111f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; VertexIterator, bool &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::insert (std::pair&lt; <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a>, VertexAttribute &gt; &amp;&amp; Val)</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### insert() {#a0b0b00af1e169ae0720380560c6e2610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; EdgeIterator, bool &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a>, EdgeAttribute &gt; &amp; Val)</td>
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

<p>Inserts an edge into the graph with Identifier Val.first, and <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Val.second.</p>


<p>If the key is already in the map, it returns false and doesn't update the value.</p>


<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### insert() {#a085b9fe5336c4d3f35328dce8033555d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; EdgeIterator, bool &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::insert (std::pair&lt; <a href="#af18457e2a495ea45229584fa1c471cf6">EdgeIdentifier</a>, EdgeAttribute &gt; &amp;&amp; Val)</td>
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

<p>Inserts an edge into the graph with Identifier Val.first, and <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Val.second.</p>


<p>If the key is already in the map, it returns false and doesn't update the value.</p>


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### outEdges() {#aff1b9575f8ffc028ecc11a03752231b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InOutEdgeView&lt; false, true &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::outEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> I)</td>
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

<p>Returns a view object allowing iteration over the edges which start at a vertex I.</p>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### outEdges() {#a397ffcfd063bf829741b7b0491d6ccdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InOutEdgeView&lt; true, true &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::outEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> I)</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### vertices() {#a224fda303f76fc909404743b24fda297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VertexView&lt; false &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::vertices ()</td>
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

<p>Returns a view object allowing iteration over the vertices of the graph.</p>


<p>also allows access to the size of the vertex set.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### vertices() {#ac06ecd496d7ee841363ab0daa9852f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VertexView&lt; true &gt; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::vertices ()</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Edges {#a846dc042de180fc8cb58f4ed2d53c139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeMapT llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::Edges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the map from the start and end vertex of an edge to it's EdgeAttribute.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### InNeighbors {#a69eec28d4c653bb5cf11f59100707acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NeighborLookupT llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::InNeighbors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allows fast lookup for the incoming edge set of any given vertex.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### OutNeighbors {#a4170c27a500caf5c1c78259661318497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NeighborLookupT llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::OutNeighbors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allows fast lookup for the outgoing edge set of any given vertex.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### Vertices {#a7e3bdf0d646ea2a7b3194dd45d5ca2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VertexAttribute, typename EdgeAttribute, typename VI = int32_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VertexMapT llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::Vertices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the map from <a href="#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> to VertexAttribute.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
