---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/graph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Graph` Class Template

<p><a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">Graph</a> class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SolverT&gt;
class llvm::PBQP::Graph&lt;SolverT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">llvm/CodeGen/PBQP/Graph.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase">GraphBase</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaba6fd85cbf88fa0fcec25a7803862da">RawVector</a> = typename SolverT::RawVector</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9833a63eae70b8c2beb33f0627ea0032">RawMatrix</a> = typename SolverT::RawMatrix</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c3f9369a1480cb8a90a3b124c89bea3">Vector</a> = typename SolverT::Vector</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a54b655b53285c4bce6adc9359087a7c3">Matrix</a> = typename SolverT::Matrix</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af286e5a878c03492516f4e8431e891a0">VectorPtr</a> = typename CostAllocator::VectorPtr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9552f7f8f52886fc473e6b6010f3388d">MatrixPtr</a> = typename CostAllocator::MatrixPtr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8eef6dbaa0ecd31870bf94d9cd831368">NodeMetadata</a> = typename SolverT::NodeMetadata</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a46616e7b1626ceb313977add2657cf">EdgeMetadata</a> = typename SolverT::EdgeMetadata</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b4311ed4a57ef1150d10b23d683e439">GraphMetadata</a> = typename SolverT::GraphMetadata</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abc9cbae0487a2766aa1b4c9050c906b8">AdjEdgeItr</a> = typename NodeEntry::AdjEdgeItr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a31bf5b1e36cc6878ba9c21fa5d0d0307">CostAllocator</a> = typename SolverT::CostAllocator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c4c384c9936284b35d90ce07276119c">NodeVector</a> = std::vector&lt; NodeEntry &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af2ffe0f5decf7b908aa4dafe2e987429">FreeNodeVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ea02c80b7f104382abc0ae4df41dcd4">EdgeVector</a> = std::vector&lt; EdgeEntry &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2daa7a73cf83fee4d6f8c4e4a9447569">FreeEdgeVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a51b411ba1e7da55498b4eacd7185c5c1">Graph</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> graph. <a href="#a51b411ba1e7da55498b4eacd7185c5c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac1b8aade7a27183542a1dc10a34d28ef">Graph</a> (GraphMetadata Metadata)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> graph with the given graph metadata. <a href="#ac1b8aade7a27183542a1dc10a34d28ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afc8f5be86c543390843498a70efa630c">Graph</a> (const Graph &amp;Other)</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4dd1398fb1223769737eff421bd1768">operator=</a> (const Graph &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1b4311ed4a57ef1150d10b23d683e439">GraphMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed0054f4566fed7f8dbb7090b58d5e38">getMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the graph metadata. <a href="#aed0054f4566fed7f8dbb7090b58d5e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a1b4311ed4a57ef1150d10b23d683e439">GraphMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b5d794cba9a4308aad0f5970412b500">getMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a const-reference to the graph metadata. <a href="#a1b5d794cba9a4308aad0f5970412b500">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89f92ffd256a37d37726145b00d09b77">setSolver</a> (SolverT &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lock this graph to the given solver instance in preparation for running the solver. <a href="#a89f92ffd256a37d37726145b00d09b77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0277999b64eeab12e9dcb9bc6d965b4c">unsetSolver</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release from solver instance. <a href="#a0277999b64eeab12e9dcb9bc6d965b4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OtherVectorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7ac2dc045a204de18d1b15863dd037b">addNode</a> (OtherVectorT Costs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a node with the given costs. <a href="#ae7ac2dc045a204de18d1b15863dd037b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OtherVectorPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a805fead02ff04e6e3a0d954f69e2715d">addNodeBypassingCostAllocator</a> (OtherVectorPtrT Costs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a node bypassing the cost allocator. <a href="#a805fead02ff04e6e3a0d954f69e2715d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OtherVectorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ab6eaf5107c20d53800ff047fab2a1f">addEdge</a> (NodeId N1Id, NodeId N2Id, OtherVectorT Costs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an edge between the given nodes with the given costs. <a href="#a1ab6eaf5107c20d53800ff047fab2a1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OtherMatrixPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afcecda660b0c5e6a15096abc9e1dffb9">addEdgeBypassingCostAllocator</a> (NodeId N1Id, NodeId N2Id, OtherMatrixPtrT Costs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an edge bypassing the cost allocator. <a href="#afcecda660b0c5e6a15096abc9e1dffb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85129c038b865c64ac42f3dfdbdb7f00">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the graph is empty. <a href="#a85129c038b865c64ac42f3dfdbdb7f00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/nodeidset">NodeIdSet</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a84ff7ee5d27c3a8173490fb89d7a7379">nodeIds</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/edgeidset">EdgeIdSet</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb740fccb3ee61c6176f946bb22e9b1a">edgeIds</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/adjedgeidset">AdjEdgeIdSet</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4936340a88a6f1856e6edab7357d1270">adjEdgeIds</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59a3e13db8ff61909707722da7b55e3c">getNumNodes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of nodes in the graph. <a href="#a59a3e13db8ff61909707722da7b55e3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0a17252c96d810a4272a3994361edbe">getNumEdges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of edges in the graph. <a href="#af0a17252c96d810a4272a3994361edbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OtherVectorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a171ef72f7fc0872c5cbd27c6dab4dde6">setNodeCosts</a> (NodeId NId, OtherVectorT Costs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a node's cost vector. <a href="#a171ef72f7fc0872c5cbd27c6dab4dde6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af286e5a878c03492516f4e8431e891a0">VectorPtr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3e3669f962d4de3cca2e2074bef5c43">getNodeCostsPtr</a> (NodeId NId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="#af286e5a878c03492516f4e8431e891a0">VectorPtr</a> to a node's cost vector. <a href="#af3e3669f962d4de3cca2e2074bef5c43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a7c3f9369a1480cb8a90a3b124c89bea3">Vector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae767e0396e22226e0aaf4de035412297">getNodeCosts</a> (NodeId NId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a node's cost vector. <a href="#ae767e0396e22226e0aaf4de035412297">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a8eef6dbaa0ecd31870bf94d9cd831368">NodeMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a07b15a89b5588d3317aa15be9a653541">getNodeMetadata</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a8eef6dbaa0ecd31870bf94d9cd831368">NodeMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0b8674ce0cfc9dae0fceab0cce174d4">getNodeMetadata</a> (NodeId NId) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeEntry::AdjEdgeList::size_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a066d67b24af2c015b3617d063aad5ada">getNodeDegree</a> (NodeId NId) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OtherMatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b5ff78bd6b4f33df1abab6fa7cfe7cd">updateEdgeCosts</a> (EdgeId EId, OtherMatrixT Costs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update an edge's cost matrix. <a href="#a8b5ff78bd6b4f33df1abab6fa7cfe7cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9552f7f8f52886fc473e6b6010f3388d">MatrixPtr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a95929a267d5d647d094931164fdad3ab">getEdgeCostsPtr</a> (EdgeId EId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="#a9552f7f8f52886fc473e6b6010f3388d">MatrixPtr</a> to a node's cost matrix. <a href="#a95929a267d5d647d094931164fdad3ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a54b655b53285c4bce6adc9359087a7c3">Matrix</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7917827865b8d4c4001a7adc0266eb40">getEdgeCosts</a> (EdgeId EId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an edge's cost matrix. <a href="#a7917827865b8d4c4001a7adc0266eb40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a2a46616e7b1626ceb313977add2657cf">EdgeMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e6b9dedf1abdbe825090ad617c23db2">getEdgeMetadata</a> (EdgeId EId)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2a46616e7b1626ceb313977add2657cf">EdgeMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad554650f05467f29f7187bb8108ae694">getEdgeMetadata</a> (EdgeId EId) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c5ac6071bfedd2049e3351a3c17ca22">getEdgeNode1Id</a> (EdgeId EId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the first node connected to this edge. <a href="#a5c5ac6071bfedd2049e3351a3c17ca22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a55617005b3dfcab29cd97f7efe8a679d">getEdgeNode2Id</a> (EdgeId EId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the second node connected to this edge. <a href="#a55617005b3dfcab29cd97f7efe8a679d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3fc350aed201496737e62751a8ad95f4">getEdgeOtherNodeId</a> (EdgeId EId, NodeId NId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the "other" node connected to this edge. <a href="#a3fc350aed201496737e62751a8ad95f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af449d12acdd9eb3a734ed2d89be6287a">findEdge</a> (NodeId N1Id, NodeId N2Id)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the edge connecting two nodes. <a href="#af449d12acdd9eb3a734ed2d89be6287a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e5eaf57399d0311f0c20896a43283ef">removeNode</a> (NodeId NId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a node from the graph. <a href="#a2e5eaf57399d0311f0c20896a43283ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0fc861a44ceb8e7b9ad83ff1376990b8">disconnectEdge</a> (EdgeId EId, NodeId NId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disconnect an edge from the given node. <a href="#a0fc861a44ceb8e7b9ad83ff1376990b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac3a81ba1d3a9b9fd110dd0f5114b5189">disconnectAllNeighborsFromNode</a> (NodeId NId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method to disconnect all neighbours from the given node. <a href="#ac3a81ba1d3a9b9fd110dd0f5114b5189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7c7346dbc788cb3913012430e538011">reconnectEdge</a> (EdgeId EId, NodeId NId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Re-attach an edge to its nodes. <a href="#ac7c7346dbc788cb3913012430e538011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae588c35f459a7e4925b870ece5849a8b">removeEdge</a> (EdgeId EId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an edge from the graph. <a href="#ae588c35f459a7e4925b870ece5849a8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa23dfa6d17e0a66e9d2ceffc5e57812d">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all nodes and edges from the graph. <a href="#aa23dfa6d17e0a66e9d2ceffc5e57812d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeEntry &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a403ec7e4d6f0365bceed4c9e83b5bf2e">getNode</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeEntry &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa839b8bb6024802ff2ec5be68dd356cf">getNode</a> (NodeId NId) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">EdgeEntry &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acdf6f3c600da91e4d80cac57120f747d">getEdge</a> (EdgeId EId)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> EdgeEntry &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46b102fd0db8cb717fcbbddc09e5b080">getEdge</a> (EdgeId EId) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b13440bfe19a2ccda1f1e11bd512aec">addConstructedNode</a> (NodeEntry N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58fdcbe2b28c54109c4df739356edbe8">addConstructedEdge</a> (EdgeEntry E)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1b4311ed4a57ef1150d10b23d683e439">GraphMetadata</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4c8b6787b7cb88b9976fe6b3fed613a4">Metadata</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">CostAllocator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac34920b2e4f9a3fc649f7f9218ad75f9">CostAlloc</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SolverT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa36801f13d76bdc1a370d4868f4d2d04">Solver</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeVector</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a53df7ebe9ae5a30ca98b764be4b71d01">Nodes</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">FreeNodeVector</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1fe9ce2596f29fe623d2dee0b362d93">FreeNodeIds</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">EdgeVector</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb6cd7df98cf4dbd70804d3872dd24e6">Edges</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SolverT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">FreeEdgeVector</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a203ec21dbd200c05e94264410b528857">FreeEdgeIds</a></td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">Graph</a> class.</p>


<p>Instances of this class describe <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> problems.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AdjEdgeItr {#abc9cbae0487a2766aa1b4c9050c906b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::AdjEdgeItr =  typename NodeEntry::AdjEdgeItr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### EdgeMetadata {#a2a46616e7b1626ceb313977add2657cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::EdgeMetadata =  typename SolverT::EdgeMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### GraphMetadata {#a1b4311ed4a57ef1150d10b23d683e439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::GraphMetadata =  typename SolverT::GraphMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Matrix {#a54b655b53285c4bce6adc9359087a7c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::Matrix =  typename SolverT::Matrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### MatrixPtr {#a9552f7f8f52886fc473e6b6010f3388d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::MatrixPtr =  typename CostAllocator::MatrixPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### NodeMetadata {#a8eef6dbaa0ecd31870bf94d9cd831368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::NodeMetadata =  typename SolverT::NodeMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### RawMatrix {#a9833a63eae70b8c2beb33f0627ea0032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::RawMatrix =  typename SolverT::RawMatrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### RawVector {#aaba6fd85cbf88fa0fcec25a7803862da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::RawVector =  typename SolverT::RawVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Vector {#a7c3f9369a1480cb8a90a3b124c89bea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::Vector =  typename SolverT::Vector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### VectorPtr {#af286e5a878c03492516f4e8431e891a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::VectorPtr =  typename CostAllocator::VectorPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### CostAllocator {#a31bf5b1e36cc6878ba9c21fa5d0d0307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::CostAllocator =  typename SolverT::CostAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### EdgeVector {#a2ea02c80b7f104382abc0ae4df41dcd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::EdgeVector =  std::vector&lt;EdgeEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### FreeEdgeVector {#a2daa7a73cf83fee4d6f8c4e4a9447569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::FreeEdgeVector =  std::vector&lt;EdgeId&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### FreeNodeVector {#af2ffe0f5decf7b908aa4dafe2e987429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::FreeNodeVector =  std::vector&lt;NodeId&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### NodeVector {#a3c4c384c9936284b35d90ce07276119c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::Graph&lt; SolverT &gt;::NodeVector =  std::vector&lt;NodeEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Graph() {#a51b411ba1e7da55498b4eacd7185c5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Graph&lt; SolverT &gt;::Graph ()</td>
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

<p>Construct an empty <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> graph.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Graph() {#ac1b8aade7a27183542a1dc10a34d28ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Graph&lt; SolverT &gt;::Graph (<a href="#a1b4311ed4a57ef1150d10b23d683e439">GraphMetadata</a> Metadata)</td>
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

<p>Construct an empty <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> graph with the given graph metadata.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Graph() {#afc8f5be86c543390843498a70efa630c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Graph&lt; SolverT &gt;::Graph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">Graph</a> &amp; Other)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#ad4dd1398fb1223769737eff421bd1768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">Graph</a> &amp; Other)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEdge() {#a1ab6eaf5107c20d53800ff047fab2a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OtherVectorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeId llvm::PBQP::Graph&lt; SolverT &gt;::addEdge (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> N1Id, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> N2Id, OtherVectorT Costs)</td>
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

<p>Add an edge between the given nodes with the given costs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N1Id</td>
<td class="doxyParamItemDescription"><p>First node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">N2Id</td>
<td class="doxyParamItemDescription"><p>Second node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Costs</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> matrix for new edge.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Edge iterator for the added edge.</p></dd>
</dl>


<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### addEdgeBypassingCostAllocator() {#afcecda660b0c5e6a15096abc9e1dffb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OtherMatrixPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::PBQP::Graph&lt; SolverT &gt;::addEdgeBypassingCostAllocator (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> N1Id, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> N2Id, OtherMatrixPtrT Costs)</td>
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

<p>Add an edge bypassing the cost allocator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N1Id</td>
<td class="doxyParamItemDescription"><p>First node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">N2Id</td>
<td class="doxyParamItemDescription"><p>Second node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Costs</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> matrix for new edge.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Edge iterator for the added edge.</p></dd>
</dl>


<p>This method allows for fast addition of an edge whose costs don't need to be passed through the cost allocator. The most common use case for this is when duplicating costs from an existing edge (when using a pooling allocator). These have already been uniqued, so we can avoid re-constructing and re-uniquing them by attaching them directly to the new edge.</p>


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### addNode() {#ae7ac2dc045a204de18d1b15863dd037b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OtherVectorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::PBQP::Graph&lt; SolverT &gt;::addNode (OtherVectorT Costs)</td>
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

<p>Add a node with the given costs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Costs</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> vector for the new node.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/node">Node</a> iterator for the added node.</p></dd>
</dl>


<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### addNodeBypassingCostAllocator() {#a805fead02ff04e6e3a0d954f69e2715d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OtherVectorPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::PBQP::Graph&lt; SolverT &gt;::addNodeBypassingCostAllocator (OtherVectorPtrT Costs)</td>
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

<p>Add a node bypassing the cost allocator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Costs</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> vector ptr for the new node (must be convertible to <a href="#af286e5a878c03492516f4e8431e891a0">VectorPtr</a>).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/node">Node</a> iterator for the added node.</p></dd>
</dl>


<p>This method allows for fast addition of a node whose costs don't need to be passed through the cost allocator. The most common use case for this is when duplicating costs from an existing node (when using a pooling allocator). These have already been uniqued, so we can avoid re-constructing and re-uniquing them by attaching them directly to the new node.</p>


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### adjEdgeIds() {#a4936340a88a6f1856e6edab7357d1270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AdjEdgeIdSet llvm::PBQP::Graph&lt; SolverT &gt;::adjEdgeIds (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#ac3a81ba1d3a9b9fd110dd0f5114b5189">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::disconnectAllNeighborsFromNode</a> and <a href="#af449d12acdd9eb3a734ed2d89be6287a">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::findEdge</a>.</p>

</div>
</div>

### clear() {#aa23dfa6d17e0a66e9d2ceffc5e57812d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::clear ()</td>
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

<p>Remove all nodes and edges from the graph.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### disconnectAllNeighborsFromNode() {#ac3a81ba1d3a9b9fd110dd0f5114b5189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::disconnectAllNeighborsFromNode (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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

<p>Convenience method to disconnect all neighbours from the given node.</p>

<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### disconnectEdge() {#a0fc861a44ceb8e7b9ad83ff1376990b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::disconnectEdge (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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

<p>Disconnect an edge from the given node.</p>


<p>Removes the given edge from the adjacency list of the given node. This operation leaves the edge in an 'asymmetric' state: It will no longer appear in an iteration over the given node's (NId's) edges, but will appear in an iteration over the 'other', unnamed node's edges.</p>


<p>This does not correspond to any normal graph operation, but exists to support efficient <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> graph-reduction based solvers. It is used to 'effectively' remove the unnamed node from the graph while the solver is performing the reduction. The solver will later call reconnectNode to restore the edge in the named node's adjacency list.</p>


<p>Since the degree of a node is the number of connected edges, disconnecting an edge from a node 'u' will cause the degree of 'u' to drop by 1.</p>


<p>A disconnected edge WILL still appear in an iteration over the graph edges.</p>


<p>A disconnected edge should not be removed from the graph, it should be reconnected first.</p>


<p>A disconnected edge can be reconnected by calling the reconnectEdge method.</p>


<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#ac3a81ba1d3a9b9fd110dd0f5114b5189">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::disconnectAllNeighborsFromNode</a>.</p>

</div>
</div>

### edgeIds() {#afb740fccb3ee61c6176f946bb22e9b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeIdSet llvm::PBQP::Graph&lt; SolverT &gt;::edgeIds ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#a89f92ffd256a37d37726145b00d09b77">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::setSolver</a>.</p>

</div>
</div>

### empty() {#a85129c038b865c64ac42f3dfdbdb7f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PBQP::Graph&lt; SolverT &gt;::empty ()</td>
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

<p>Returns true if the graph is empty.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### findEdge() {#af449d12acdd9eb3a734ed2d89be6287a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeId llvm::PBQP::Graph&lt; SolverT &gt;::findEdge (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> N1Id, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> N2Id)</td>
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

<p>Get the edge connecting two nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N1Id</td>
<td class="doxyParamItemDescription"><p>First node id.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">N2Id</td>
<td class="doxyParamItemDescription"><p>Second node id.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An id for edge (N1Id, N2Id) if such an edge exists, otherwise returns an invalid edge id.</p></dd>
</dl>


<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getEdgeCosts() {#a7917827865b8d4c4001a7adc0266eb40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Matrix &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getEdgeCosts (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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

<p>Get an edge's cost matrix.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EId</td>
<td class="doxyParamItemDescription"><p>Edge id.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Edge cost matrix.</p></dd>
</dl>


<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getEdgeCostsPtr() {#a95929a267d5d647d094931164fdad3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MatrixPtr &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getEdgeCostsPtr (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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

<p>Get a <a href="#a9552f7f8f52886fc473e6b6010f3388d">MatrixPtr</a> to a node's cost matrix.</p>


<p>Rarely useful - use getEdgeCosts where possible.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EId</td>
<td class="doxyParamItemDescription"><p>Edge id.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="#a9552f7f8f52886fc473e6b6010f3388d">MatrixPtr</a> to edge cost matrix.</p></dd>
</dl>


<p>This method is primarily useful for duplicating costs quickly by bypassing the cost allocator. See addNodeBypassingCostAllocator. Prefer getEdgeCosts when dealing with edge cost values.</p>


<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getEdgeMetadata() {#a5e6b9dedf1abdbe825090ad617c23db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeMetadata &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getEdgeMetadata (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getEdgeMetadata() {#ad554650f05467f29f7187bb8108ae694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EdgeMetadata &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getEdgeMetadata (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getEdgeNode1Id() {#a5c5ac6071bfedd2049e3351a3c17ca22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::PBQP::Graph&lt; SolverT &gt;::getEdgeNode1Id (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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

<p>Get the first node connected to this edge.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EId</td>
<td class="doxyParamItemDescription"><p>Edge id.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The first node connected to the given edge.</p></dd>
</dl>


<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#af449d12acdd9eb3a734ed2d89be6287a">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::findEdge</a>.</p>

</div>
</div>

### getEdgeNode2Id() {#a55617005b3dfcab29cd97f7efe8a679d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::PBQP::Graph&lt; SolverT &gt;::getEdgeNode2Id (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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

<p>Get the second node connected to this edge.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EId</td>
<td class="doxyParamItemDescription"><p>Edge id.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The second node connected to the given edge.</p></dd>
</dl>


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#af449d12acdd9eb3a734ed2d89be6287a">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::findEdge</a>.</p>

</div>
</div>

### getEdgeOtherNodeId() {#a3fc350aed201496737e62751a8ad95f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::PBQP::Graph&lt; SolverT &gt;::getEdgeOtherNodeId (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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

<p>Get the "other" node connected to this edge.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EId</td>
<td class="doxyParamItemDescription"><p>Edge id.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NId</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> id for the "given" node.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The iterator for the "other" node connected to this edge.</p></dd>
</dl>


<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#ac3a81ba1d3a9b9fd110dd0f5114b5189">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::disconnectAllNeighborsFromNode</a>.</p>

</div>
</div>

### getMetadata() {#aed0054f4566fed7f8dbb7090b58d5e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GraphMetadata &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getMetadata ()</td>
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

<p>Get a reference to the graph metadata.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getMetadata() {#a1b5d794cba9a4308aad0f5970412b500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GraphMetadata &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getMetadata ()</td>
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

<p>Get a const-reference to the graph metadata.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getNodeCosts() {#ae767e0396e22226e0aaf4de035412297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Vector &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getNodeCosts (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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

<p>Get a node's cost vector.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NId</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> id.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/node">Node</a> cost vector.</p></dd>
</dl>


<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#a1ab6eaf5107c20d53800ff047fab2a1f">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::addEdge</a> and <a href="#afcecda660b0c5e6a15096abc9e1dffb9">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::addEdgeBypassingCostAllocator</a>.</p>

</div>
</div>

### getNodeCostsPtr() {#af3e3669f962d4de3cca2e2074bef5c43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VectorPtr &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getNodeCostsPtr (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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

<p>Get a <a href="#af286e5a878c03492516f4e8431e891a0">VectorPtr</a> to a node's cost vector.</p>


<p>Rarely useful - use getNodeCosts where possible.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NId</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> id.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="#af286e5a878c03492516f4e8431e891a0">VectorPtr</a> to node cost vector.</p></dd>
</dl>


<p>This method is primarily useful for duplicating costs quickly by bypassing the cost allocator. See addNodeBypassingCostAllocator. Prefer getNodeCosts when dealing with node cost values.</p>


<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#ae767e0396e22226e0aaf4de035412297">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getNodeCosts</a>.</p>

</div>
</div>

### getNodeDegree() {#a066d67b24af2c015b3617d063aad5ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeEntry::AdjEdgeList::size_type llvm::PBQP::Graph&lt; SolverT &gt;::getNodeDegree (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getNodeMetadata() {#a07b15a89b5588d3317aa15be9a653541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeMetadata &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getNodeMetadata (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getNodeMetadata() {#ab0b8674ce0cfc9dae0fceab0cce174d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeMetadata &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getNodeMetadata (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getNumEdges() {#af0a17252c96d810a4272a3994361edbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::Graph&lt; SolverT &gt;::getNumEdges ()</td>
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

<p>Get the number of edges in the graph.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of edges in the graph.</p></dd>
</dl>


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getNumNodes() {#a59a3e13db8ff61909707722da7b55e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::Graph&lt; SolverT &gt;::getNumNodes ()</td>
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

<p>Get the number of nodes in the graph.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of nodes in the graph.</p></dd>
</dl>


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### nodeIds() {#a84ff7ee5d27c3a8173490fb89d7a7379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIdSet llvm::PBQP::Graph&lt; SolverT &gt;::nodeIds ()</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#a89f92ffd256a37d37726145b00d09b77">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::setSolver</a>.</p>

</div>
</div>

### reconnectEdge() {#ac7c7346dbc788cb3913012430e538011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::reconnectEdge (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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

<p>Re-attach an edge to its nodes.</p>


<p>Adds an edge that had been previously disconnected back into the adjacency set of the nodes that the edge connects.</p>


<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### removeEdge() {#ae588c35f459a7e4925b870ece5849a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::removeEdge (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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

<p>Remove an edge from the graph.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EId</td>
<td class="doxyParamItemDescription"><p>Edge id.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>


<p>Referenced by <a href="#a2e5eaf57399d0311f0c20896a43283ef">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::removeNode</a>.</p>

</div>
</div>

### removeNode() {#a2e5eaf57399d0311f0c20896a43283ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::removeNode (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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

<p>Remove a node from the graph.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NId</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> id.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### setNodeCosts() {#a171ef72f7fc0872c5cbd27c6dab4dde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OtherVectorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::setNodeCosts (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId, OtherVectorT Costs)</td>
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

<p>Set a node's cost vector.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NId</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to update.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Costs</td>
<td class="doxyParamItemDescription"><p>New costs to set.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### setSolver() {#a89f92ffd256a37d37726145b00d09b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::setSolver (SolverT &amp; S)</td>
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

<p>Lock this graph to the given solver instance in preparation for running the solver.</p>


<p>This method will call solver.handleAddNode for each node in the graph, and handleAddEdge for each edge, to give the solver an opportunity to set up any requried metadata.</p>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### unsetSolver() {#a0277999b64eeab12e9dcb9bc6d965b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::unsetSolver ()</td>
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

<p>Release from solver instance.</p>

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### updateEdgeCosts() {#a8b5ff78bd6b4f33df1abab6fa7cfe7cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OtherMatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::Graph&lt; SolverT &gt;::updateEdgeCosts (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId, OtherMatrixT Costs)</td>
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

<p>Update an edge's cost matrix.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EId</td>
<td class="doxyParamItemDescription"><p>Edge id.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Costs</td>
<td class="doxyParamItemDescription"><p>New cost matrix.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addConstructedEdge() {#a58fdcbe2b28c54109c4df739356edbe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeId llvm::PBQP::Graph&lt; SolverT &gt;::addConstructedEdge (EdgeEntry E)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### addConstructedNode() {#a2b13440bfe19a2ccda1f1e11bd512aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::PBQP::Graph&lt; SolverT &gt;::addConstructedNode (NodeEntry N)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getEdge() {#acdf6f3c600da91e4d80cac57120f747d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeEntry &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getEdge (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getEdge() {#a46b102fd0db8cb717fcbbddc09e5b080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EdgeEntry &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getEdge (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">EdgeId</a> EId)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getNode() {#a403ec7e4d6f0365bceed4c9e83b5bf2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeEntry &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getNode (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### getNode() {#aa839b8bb6024802ff2ec5be68dd356cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeEntry &amp; llvm::PBQP::Graph&lt; SolverT &gt;::getNode (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">NodeId</a> NId)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CostAlloc {#ac34920b2e4f9a3fc649f7f9218ad75f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostAllocator llvm::PBQP::Graph&lt; SolverT &gt;::CostAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Edges {#aeb6cd7df98cf4dbd70804d3872dd24e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeVector llvm::PBQP::Graph&lt; SolverT &gt;::Edges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### FreeEdgeIds {#a203ec21dbd200c05e94264410b528857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FreeEdgeVector llvm::PBQP::Graph&lt; SolverT &gt;::FreeEdgeIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### FreeNodeIds {#ad1fe9ce2596f29fe623d2dee0b362d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FreeNodeVector llvm::PBQP::Graph&lt; SolverT &gt;::FreeNodeIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Metadata {#a4c8b6787b7cb88b9976fe6b3fed613a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GraphMetadata llvm::PBQP::Graph&lt; SolverT &gt;::Metadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Nodes {#a53df7ebe9ae5a30ca98b764be4b71d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeVector llvm::PBQP::Graph&lt; SolverT &gt;::Nodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

</div>
</div>

### Solver {#aa36801f13d76bdc1a370d4868f4d2d04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SolverT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SolverT* llvm::PBQP::Graph&lt; SolverT &gt;::Solver = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/graph-h">Graph.h</a>.</p>

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
