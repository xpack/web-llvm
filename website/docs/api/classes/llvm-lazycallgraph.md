---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lazycallgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LazyCallGraph` Class

<p>A lazily constructed view of the call graph of a module. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LazyCallGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa8bc41d59b4812a149d09aa82ca6b5">node_stack_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> * &gt;::reverse_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac511b6b6787fe1f73487a49621c85246">node_stack_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; node_stack_iterator &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d534b072f7d0fa5f54ff569bb745ec">LazyCallGraph</a> (Module &amp;M, function_ref&lt; TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a graph for the given module. <a href="#a58d534b072f7d0fa5f54ff569bb745ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726eb1ab5c24c68c029e4378a0a3ce12">LazyCallGraph</a> (LazyCallGraph &amp;&amp;G)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae201589cad3a446f3a6284f02b0df850">operator=</a> (LazyCallGraph &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1129b8892c0b3869793b0354270544">verify</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that every <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is valid. <a href="#aea1129b8892c0b3869793b0354270544">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c105e6215a1507fd7bc89f83e3c62f">invalidate</a> (Module &amp;, const PreservedAnalyses &amp;PA, ModuleAnalysisManager::Invalidator &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence/iterator">EdgeSequence::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d888c3c38a3a21393de743bdba4ca8">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence/iterator">EdgeSequence::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49cb365c243c14974ed197bd1fa50b9">end</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72787ab6acfbe504a11ca1d927513356">buildRefSCCs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/postorder-ref-scc-iterator">postorder_ref_scc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbe38c01c554fabb0f4c37a531a2702">postorder_ref_scc_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/postorder-ref-scc-iterator">postorder_ref_scc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa270ba6d3c8d3c6016e6301cd21f4894">postorder_ref_scc_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/postorder-ref-scc-iterator">postorder_ref_scc_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c39918b16a0755f8e0506ce27bc053">postorder_ref_sccs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb236ae969b97a215e36acd367e34360">lookup</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup a function in the graph which has already been scanned and added. <a href="#afb236ae969b97a215e36acd367e34360">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad234c24f90aaa0fa3f30ac9c750883b6">lookupSCC</a> (Node &amp;N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup a function's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> in the graph. <a href="#ad234c24f90aaa0fa3f30ac9c750883b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b50db13f4a942ed11f2eaaa6e1709f3">lookupRefSCC</a> (Node &amp;N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup a function's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> in the graph. <a href="#a2b50db13f4a942ed11f2eaaa6e1709f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03c103c6345a262195c485df88d2a21">get</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a graph node for a given function, scanning it to populate the graph data as necessary. <a href="#ad03c103c6345a262195c485df88d2a21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa191e5157649aa6b0a2b150f383102c2">getLibFunctions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the sequence of known and defined library functions. <a href="#aa191e5157649aa6b0a2b150f383102c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aec1afa97220e40f3d67a94455b7833">isLibFunction</a> (Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether a function is a known and defined library function tracked by the call graph. <a href="#a0aec1afa97220e40f3d67a94455b7833">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa750c44eea5719f400c4e55464c3b252">insertInto</a> (Function &amp;F, Node *&amp;MappedN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to insert a new function, with an already looked-up entry in the NodeMap. <a href="#aa750c44eea5719f400c4e55464c3b252">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec91d42b6f19dad65f266f92ec34955">initNode</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to initialize a new node created outside of creating SCCs and add it to the NodeMap if necessary. <a href="#a5ec91d42b6f19dad65f266f92ec34955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46dad0943f87e9cbd6b6b7e2daaaa028">updateGraphPtrs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to update pointers back to the graph object during moves. <a href="#a46dad0943f87e9cbd6b6b7e2daaaa028">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a482071fc965d69b5a546e6737b14c56e">createSCC</a> (Ts &amp;&amp;...Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates an <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> and constructs it using the graph allocator. <a href="#a482071fc965d69b5a546e6737b14c56e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cc26f12e4bd55a68d563d2932dc1141">createRefSCC</a> (Ts &amp;&amp;...Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and constructs it using the graph allocator. <a href="#a6cc26f12e4bd55a68d563d2932dc1141">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe2c133298b4aa290e56fe625ab1127">buildSCCs</a> (RefSCC &amp;RC, node_stack_range Nodes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the SCCs for a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> out of a list of nodes. <a href="#aebe2c133298b4aa290e56fe625ab1127">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca387b8365cfbe82a727adfdc8cb15a">getRefSCCIndex</a> (RefSCC &amp;RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the index of a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> within the postorder traversal. <a href="#a3ca387b8365cfbe82a727adfdc8cb15a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af378f7475014c8748695a1016b3b5f1f">BPA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator that holds all the call graph nodes. <a href="#af378f7475014c8748695a1016b3b5f1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d44ee5529e5eb52ceb4d2d894d1a76e">NodeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps function-&gt;node for fast lookup. <a href="#a1d44ee5529e5eb52ceb4d2d894d1a76e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1453d072414939cfd10da48d6ab50d89">EntryEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The entry edges into the graph. <a href="#a1453d072414939cfd10da48d6ab50d89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c071fd0c2d01ada6ae784e7762d1b25">SCCBPA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator that holds all the call graph SCCs. <a href="#a1c071fd0c2d01ada6ae784e7762d1b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> *, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026664578dab3ebc5dde8ff9f1a5a1c2">SCCMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> for fast lookup. <a href="#a026664578dab3ebc5dde8ff9f1a5a1c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4360118d695dd7424583547c0a567c9">RefSCCBPA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator that holds all the call graph RefSCCs. <a href="#ae4360118d695dd7424583547c0a567c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2037bb0adc41d20b991f55a5b182534">PostOrderRefSCCs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The post-order sequence of RefSCCs. <a href="#ae2037bb0adc41d20b991f55a5b182534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb8e96aafc70ff5ace89a5321f8ac4a">RefSCCIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map from <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to the index for it in the postorder sequence of RefSCCs. <a href="#a3bb8e96aafc70ff5ace89a5321f8ac4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62fbd303226d0f6f95e687a07a318577">LibFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defined functions that are also known library functions which the optimizer can reason about and therefore might introduce calls to out of thin air. <a href="#a62fbd303226d0f6f95e687a07a318577">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c5b3c9863fc796c4bc87de4031fac09">buildGenericSCCs</a> (RootsT &amp;&amp;Roots, GetBeginT &amp;&amp;GetBegin, GetEndT &amp;&amp;GetEnd, GetNodeT &amp;&amp;GetNode, FormSCCCallbackT &amp;&amp;FormSCC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common logic for building SCCs from a sequence of roots. <a href="#a3c5b3c9863fc796c4bc87de4031fac09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Pre-SCC Mutation API Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5733cfe65849ae5b7945ee53328ffad9">insertEdge</a> (Node &amp;SourceN, Node &amp;TargetN, Edge::Kind EK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the call graph after inserting a new edge. <a href="#a5733cfe65849ae5b7945ee53328ffad9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5e10df2bb5b64a556a3335799a0c40">insertEdge</a> (Function &amp;Source, Function &amp;Target, Edge::Kind EK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the call graph after inserting a new edge. <a href="#acd5e10df2bb5b64a556a3335799a0c40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeeeb8eb8c4062039f93bb6ae7d2c618">removeEdge</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the call graph after deleting an edge. <a href="#abeeeb8eb8c4062039f93bb6ae7d2c618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a12910e959c604cf4f0e94135efd7e">removeEdge</a> (Function &amp;Source, Function &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the call graph after deleting an edge. <a href="#ac8a12910e959c604cf4f0e94135efd7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## General Mutation API Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b7a3d43f4f6eb3ab16554f56bd0cc4">removeDeadFunctions</a> (ArrayRef&lt; Function * &gt; DeadFs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove dead functions from the call graph. <a href="#a97b7a3d43f4f6eb3ab16554f56bd0cc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85788a67cbcd567d28600d43453e342d">markDeadFunction</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark a function as dead to be removed later by <a href="#a97b7a3d43f4f6eb3ab16554f56bd0cc4">removeDeadFunctions()</a>. <a href="#a85788a67cbcd567d28600d43453e342d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d76834516af3608993c2add103b3a6f">addSplitFunction</a> (Function &amp;OriginalFunction, Function &amp;NewFunction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new function split/outlined from an existing function. <a href="#a8d76834516af3608993c2add103b3a6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952c8adfe8553406e169b98200072a69">addSplitRefRecursiveFunctions</a> (Function &amp;OriginalFunction, ArrayRef&lt; Function * &gt; NewFunctions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add new ref-recursive functions split/outlined from an existing function. <a href="#a952c8adfe8553406e169b98200072a69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Static helpers for code doing updates to the call graph. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778d0494c2f8dec95d60160b1ce89a07">visitReferences</a> (SmallVectorImpl&lt; Constant * &gt; &amp;Worklist, SmallPtrSetImpl&lt; Constant * &gt; &amp;Visited, function_ref&lt; void(Function &amp;)&gt; Callback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively visits the defined functions whose address is reachable from every constant in the <span class="doxyComputerOutput">Worklist</span>. <a href="#a778d0494c2f8dec95d60160b1ce89a07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A lazily constructed view of the call graph of a module.</p>


<p>With the edges of this graph, the motivating constraint that we are attempting to maintain is that function-local optimization, CGSCC-local optimizations, and optimizations transforming a pair of functions connected by an edge in the graph, do not invalidate a bottom-up traversal of the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> DAG. That is, no optimizations will delete, remove, or add an edge such that functions already visited in a bottom-up order of the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> DAG are no longer valid to have visited, or such that functions not yet visited in a bottom-up order of the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> DAG are not required to have already been visited.</p>


<p>Within this constraint, the desire is to minimize the merge points of the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> DAG. The greater the fanout of the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> DAG and the fewer merge points in the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> DAG, the more independence there is in optimizing within it. There is a strong desire to enable parallelization of optimizations over the call graph, and both limited fanout and merge points will (artificially in some cases) limit the scaling of such an effort.</p>


<p>To this end, graph represents both direct and any potential resolution to an indirect call edge. Another way to think about it is that it represents both the direct call edges and any direct call edges that might be formed through static optimizations. Specifically, it considers taking the address of a function to be an edge in the call graph because this might be forwarded to become a direct call by some subsequent function-local optimization. The result is that the graph closely follows the use-def edges for functions. Walking "up" the graph can be done by looking at all of the uses of a function.</p>


<p>The roots of the call graph are the external functions and functions escaped into global variables. Those functions can be called from outside of the module or via unknowable means in the IR – we may not be able to form even a potential call edge from a function body which may dynamically load the function and call it.</p>


<p>This analysis still requires updates to remain valid after optimizations which could potentially change the set of potential callees. The constraints it operates under only make the traversal order remain valid.</p>


<p>The entire analysis must be re-computed if full interprocedural optimizations run at any point. For example, globalopt completely invalidates the information in this analysis.</p>


<p>FIXME: This class is named <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> in a lame attempt to distinguish it from the existing <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a>. At some point, it is expected that this will be the only call graph and it will be renamed accordingly.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### node\_stack\_iterator {#a3aa8bc41d59b4812a149d09aa82ca6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LazyCallGraph::node_stack_iterator =  SmallVectorImpl&lt;Node *&gt;::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### node\_stack\_range {#ac511b6b6787fe1f73487a49621c85246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LazyCallGraph::node_stack_range =  iterator_range&lt;node_stack_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LazyCallGraph() {#a58d534b072f7d0fa5f54ff569bb745ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::LazyCallGraph (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a graph for the given module.</p>


<p>This sets up the graph and computes all of the entry points of the graph. No function definitions are scanned until their nodes in the graph are requested during traversal.</p>


<p>Declaration at line 937 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#aec802e48dd5ef69029e285eddfc4158d">addEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad03c103c6345a262195c485df88d2a21">get</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#af481ee3f81ad12db32ea0df13ec4b0d0">isKnownLibFunction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a> and <a href="#a778d0494c2f8dec95d60160b1ce89a07">visitReferences</a>.</p>


<p>Referenced by <a href="#a726eb1ab5c24c68c029e4378a0a3ce12">LazyCallGraph</a> and <a href="#ae201589cad3a446f3a6284f02b0df850">operator=</a>.</p>

</div>
</div>

### LazyCallGraph() {#a726eb1ab5c24c68c029e4378a0a3ce12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::LazyCallGraph (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp;&amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a58d534b072f7d0fa5f54ff569bb745ec">LazyCallGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae201589cad3a446f3a6284f02b0df850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph &amp; LazyCallGraph::operator= (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a58d534b072f7d0fa5f54ff569bb745ec">LazyCallGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a19d888c3c38a3a21393de743bdba4ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeSequence::iterator llvm::LazyCallGraph::begin ()</td>
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



<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### buildRefSCCs() {#a72787ab6acfbe504a11ca1d927513356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::buildRefSCCs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1935 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#ac62cb27d2f0946c9febb1e1d1e377f55">llvm::LazyCallGraph::RefSCC::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4d05aa2854cf8b7927d9f162180d1a37">llvm::buildTopDownFuncOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#ab389f58bce3bb2dcd1eb8284f46064ee">deduceFunctionAttributeInRPO</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuperfhintanalysis/#ac18130b5f0f65e07855c5e06b2e415c4">llvm::AMDGPUPerfHintAnalysis::run</a> and <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>.</p>

</div>
</div>

### end() {#af49cb365c243c14974ed197bd1fa50b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeSequence::iterator llvm::LazyCallGraph::end ()</td>
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



<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### get() {#ad03c103c6345a262195c485df88d2a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node &amp; llvm::LazyCallGraph::get (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Get a graph node for a given function, scanning it to populate the graph data as necessary.</p>

<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a8d76834516af3608993c2add103b3a6f">addSplitFunction</a>, <a href="#a952c8adfe8553406e169b98200072a69">addSplitRefRecursiveFunctions</a>, <a href="#acd5e10df2bb5b64a556a3335799a0c40">insertEdge</a>, <a href="#a58d534b072f7d0fa5f54ff569bb745ec">LazyCallGraph</a>, <a href="#ac8a12910e959c604cf4f0e94135efd7e">removeEdge</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### getLibFunctions() {#aa191e5157649aa6b0a2b150f383102c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Function * &gt; llvm::LazyCallGraph::getLibFunctions ()</td>
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

<p>Get the sequence of known and defined library functions.</p>


<p>These functions, because they are known to LLVM, can have calls introduced out of thin air from arbitrary IR.</p>


<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### invalidate() {#ae6c105e6215a1507fd7bc89f83e3c62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyCallGraph::invalidate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, ModuleAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### isLibFunction() {#a0aec1afa97220e40f3d67a94455b7833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::isLibFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Test whether a function is a known and defined library function tracked by the call graph.</p>


<p>Because these functions are known to LLVM they are specially modeled in the call graph and even when all IR-level references have been removed remain active and reachable.</p>


<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a85788a67cbcd567d28600d43453e342d">markDeadFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### lookup() {#afb236ae969b97a215e36acd367e34360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * llvm::LazyCallGraph::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Lookup a function in the graph which has already been scanned and added.</p>

<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a8d76834516af3608993c2add103b3a6f">addSplitFunction</a>, <a href="#a952c8adfe8553406e169b98200072a69">addSplitRefRecursiveFunctions</a>, <a href="#a97b7a3d43f4f6eb3ab16554f56bd0cc4">removeDeadFunctions</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### lookupRefSCC() {#a2b50db13f4a942ed11f2eaaa6e1709f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefSCC * llvm::LazyCallGraph::lookupRefSCC (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; N)</td>
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

<p>Lookup a function's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> in the graph.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>null if the function hasn't been assigned a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> via the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> iterator walk.</p></dd>
</dl>


<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ad234c24f90aaa0fa3f30ac9c750883b6">lookupSCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a8d76834516af3608993c2add103b3a6f">addSplitFunction</a>, <a href="#a952c8adfe8553406e169b98200072a69">addSplitRefRecursiveFunctions</a> and <a href="#a97b7a3d43f4f6eb3ab16554f56bd0cc4">removeDeadFunctions</a>.</p>

</div>
</div>

### lookupSCC() {#ad234c24f90aaa0fa3f30ac9c750883b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCC * llvm::LazyCallGraph::lookupSCC (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; N)</td>
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

<p>Lookup a function's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> in the graph.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>null if the function hasn't been assigned an <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> via the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> iterator walk.</p></dd>
</dl>


<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a8d76834516af3608993c2add103b3a6f">addSplitFunction</a>, <a href="#a2b50db13f4a942ed11f2eaaa6e1709f3">lookupRefSCC</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### postorder\_ref\_scc\_begin() {#a9fbe38c01c554fabb0f4c37a531a2702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">postorder_ref_scc_iterator llvm::LazyCallGraph::postorder_ref_scc_begin ()</td>
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



<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ad5c39918b16a0755f8e0506ce27bc053">postorder_ref_sccs</a>.</p>

</div>
</div>

### postorder\_ref\_scc\_end() {#aa270ba6d3c8d3c6016e6301cd21f4894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">postorder_ref_scc_iterator llvm::LazyCallGraph::postorder_ref_scc_end ()</td>
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



<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ad5c39918b16a0755f8e0506ce27bc053">postorder_ref_sccs</a>.</p>

</div>
</div>

### postorder\_ref\_sccs() {#ad5c39918b16a0755f8e0506ce27bc053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; postorder_ref_scc_iterator &gt; llvm::LazyCallGraph::postorder_ref_sccs ()</td>
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



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a9fbe38c01c554fabb0f4c37a531a2702">postorder_ref_scc_begin</a> and <a href="#aa270ba6d3c8d3c6016e6301cd21f4894">postorder_ref_scc_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4d05aa2854cf8b7927d9f162180d1a37">llvm::buildTopDownFuncOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#ab389f58bce3bb2dcd1eb8284f46064ee">deduceFunctionAttributeInRPO</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuperfhintanalysis/#ac18130b5f0f65e07855c5e06b2e415c4">llvm::AMDGPUPerfHintAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a> and <a href="#aea1129b8892c0b3869793b0354270544">verify</a>.</p>

</div>
</div>

### verify() {#aea1129b8892c0b3869793b0354270544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that every <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is valid.</p>

<p>Declaration at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>Reference <a href="#ad5c39918b16a0755f8e0506ce27bc053">postorder_ref_sccs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a01b1581633bb40f86d6dc62a1c1a7f72">llvm::LazyCallGraph::RefSCC::insertIncomingRefEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#aa57986c798b44affab5e4d5953e37727">llvm::LazyCallGraph::RefSCC::insertInternalRefEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a743c2ac21f2f8a8c6af18e1e09f13229">llvm::LazyCallGraph::RefSCC::insertOutgoingEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#aaf3ba7d78f09755223609e4978bebef7">llvm::LazyCallGraph::RefSCC::insertTrivialCallEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a393b4565f554b9d8382c8f610b7f2ce7">llvm::LazyCallGraph::RefSCC::insertTrivialRefEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a87dd1a69c8d8492e78b32708ceacb2c6">llvm::LazyCallGraph::RefSCC::removeInternalRefEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#ab130250bcdaefbfd3c583cad7b120b62">llvm::LazyCallGraph::RefSCC::removeOutgoingEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a70f7f0574edbfc0f75424499133d4ba3">llvm::LazyCallGraph::RefSCC::replaceNodeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a2957918db7f91f405b11d92c1ebf3b0f">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a5cc0541c3ee15c565ac05fe11f5459d2">llvm::LazyCallGraph::RefSCC::switchOutgoingEdgeToCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#adce8df277d53b4d87581583c8269ac71">llvm::LazyCallGraph::RefSCC::switchOutgoingEdgeToRef</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#ae2f9bc7458beec4389ccf7fb88199d4b">llvm::LazyCallGraph::RefSCC::switchTrivialInternalEdgeToRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildSCCs() {#aebe2c133298b4aa290e56fe625ab1127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::buildSCCs (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; RC, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">node_stack_range</a> Nodes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build the SCCs for a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> out of a list of nodes.</p>


<p>Build the internal SCCs for a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> from a sequence of nodes.</p>


<p>Appends the SCCs to the provided vector and updates the map with their indices. Both the vector and map must be empty when passed into this routine.</p>


<p>Declaration at line 1198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1901 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### createRefSCC() {#a6cc26f12e4bd55a68d563d2932dc1141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefSCC * llvm::LazyCallGraph::createRefSCC (Ts &amp;&amp;... Args)</td>
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

<p>Allocates a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and constructs it using the graph allocator.</p>


<p>The arguments are forwarded to the constructor.</p>


<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### createSCC() {#a482071fc965d69b5a546e6737b14c56e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCC * llvm::LazyCallGraph::createSCC (Ts &amp;&amp;... Args)</td>
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

<p>Allocates an <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> and constructs it using the graph allocator.</p>


<p>The arguments are forwarded to the constructor.</p>


<p>Definition at line 1169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### getRefSCCIndex() {#a3ca387b8365cfbe82a727adfdc8cb15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LazyCallGraph::getRefSCCIndex (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; RC)</td>
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

<p>Get the index of a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> within the postorder traversal.</p>


<p>Requires that this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is a valid one in the (perhaps partial) postorder traversed part of the graph.</p>


<p>Definition at line 1204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### initNode() {#a5ec91d42b6f19dad65f266f92ec34955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::Node &amp; LazyCallGraph::initNode (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to initialize a new node created outside of creating SCCs and add it to the NodeMap if necessary.</p>


<p>For example, useful when a function is split.</p>


<p>Declaration at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1799 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### insertInto() {#aa750c44eea5719f400c4e55464c3b252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::Node &amp; LazyCallGraph::insertInto (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> *&amp; MappedN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to insert a new function, with an already looked-up entry in the NodeMap.</p>

<p>Declaration at line 1156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### updateGraphPtrs() {#a46dad0943f87e9cbd6b6b7e2daaaa028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::updateGraphPtrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to update pointers back to the graph object during moves.</p>

<p>Declaration at line 1164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1789 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BPA {#af378f7475014c8748695a1016b3b5f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;Node&gt; llvm::LazyCallGraph::BPA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator that holds all the call graph nodes.</p>

<p>Definition at line 1120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### EntryEdges {#a1453d072414939cfd10da48d6ab50d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeSequence llvm::LazyCallGraph::EntryEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The entry edges into the graph.</p>


<p>These edges are from "external" sources. Put another way, they escape at the module scope.</p>


<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### LibFunctions {#a62fbd303226d0f6f95e687a07a318577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;Function *, 4&gt; llvm::LazyCallGraph::LibFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Defined functions that are also known library functions which the optimizer can reason about and therefore might introduce calls to out of thin air.</p>

<p>Definition at line 1152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### NodeMap {#a1d44ee5529e5eb52ceb4d2d894d1a76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, Node *&gt; llvm::LazyCallGraph::NodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps function-&gt;node for fast lookup.</p>

<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### PostOrderRefSCCs {#ae2037bb0adc41d20b991f55a5b182534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RefSCC *, 16&gt; llvm::LazyCallGraph::PostOrderRefSCCs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The post-order sequence of RefSCCs.</p>


<p>This list is lazily formed the first time we walk the graph.</p>


<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### RefSCCBPA {#ae4360118d695dd7424583547c0a567c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;RefSCC&gt; llvm::LazyCallGraph::RefSCCBPA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator that holds all the call graph RefSCCs.</p>

<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### RefSCCIndices {#a3bb8e96aafc70ff5ace89a5321f8ac4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;RefSCC *, int&gt; llvm::LazyCallGraph::RefSCCIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map from <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to the index for it in the postorder sequence of RefSCCs.</p>

<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### SCCBPA {#a1c071fd0c2d01ada6ae784e7762d1b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;SCC&gt; llvm::LazyCallGraph::SCCBPA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator that holds all the call graph SCCs.</p>

<p>Definition at line 1132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### SCCMap {#a026664578dab3ebc5dde8ff9f1a5a1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Node *, SCC *&gt; llvm::LazyCallGraph::SCCMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> for fast lookup.</p>

<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### buildGenericSCCs() {#a3c5b3c9863fc796c4bc87de4031fac09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RootsT, typename GetBeginT, typename GetEndT, typename GetNodeT, typename FormSCCCallbackT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::buildGenericSCCs (RootsT &amp;&amp; Roots, GetBeginT &amp;&amp; GetBegin, GetEndT &amp;&amp; GetEnd, GetNodeT &amp;&amp; GetNode, FormSCCCallbackT &amp;&amp; FormSCC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common logic for building SCCs from a sequence of roots.</p>


<p>This is a very generic implementation of the depth-first walk and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> formation algorithm. It uses a generic sequence of roots and generic callbacks for each step. This is designed to be used to implement both the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> formation and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> formation with shared logic.</p>


<p>Currently this is a relatively naive implementation of Tarjan's DFS algorithm to form the SCCs.</p>


<p>FIXME: We should consider newer variants such as Nuutila.</p>


<p>Declaration at line 1193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1809 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Pre-SCC Mutation API



<p>These methods are only valid to call prior to forming any SCCs for this call graph. They can be used to update the core node-graph during a node-based inorder traversal that precedes any SCC-based traversal.</p>


<p>Once you begin manipulating a call graph's SCCs, most mutation of the graph must be performed via a <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> method. There are some exceptions below.</p>


### insertEdge {#a5733cfe65849ae5b7945ee53328ffad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::insertEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13">Edge::Kind</a> EK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the call graph after inserting a new edge.</p>

<p>Declaration at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1484 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#acd5e10df2bb5b64a556a3335799a0c40">insertEdge</a>.</p>

</div>
</div>

### insertEdge {#acd5e10df2bb5b64a556a3335799a0c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LazyCallGraph::insertEdge (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Source, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13">Edge::Kind</a> EK)</td>
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

<p>Update the call graph after inserting a new edge.</p>

<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="#ad03c103c6345a262195c485df88d2a21">get</a> and <a href="#a5733cfe65849ae5b7945ee53328ffad9">insertEdge</a>.</p>

</div>
</div>

### removeEdge {#abeeeb8eb8c4062039f93bb6ae7d2c618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::removeEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the call graph after deleting an edge.</p>

<p>Declaration at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1491 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ac8a12910e959c604cf4f0e94135efd7e">removeEdge</a>.</p>

</div>
</div>

### removeEdge {#ac8a12910e959c604cf4f0e94135efd7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LazyCallGraph::removeEdge (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Source, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Target)</td>
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

<p>Update the call graph after deleting an edge.</p>

<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="#ad03c103c6345a262195c485df88d2a21">get</a> and <a href="#abeeeb8eb8c4062039f93bb6ae7d2c618">removeEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## General Mutation API



<p>There are a very limited set of mutations allowed on the graph as a whole once SCCs have started to be formed. These routines have strict contracts but may be called at any point.</p>


### addSplitFunction {#a8d76834516af3608993c2add103b3a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::addSplitFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OriginalFunction, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; NewFunction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new function split/outlined from an existing function.</p>


<p>The new function may only reference other functions that the original function did.</p>


<p>The original function must reference (either directly or indirectly) the new function.</p>


<p>The new function may also reference the original function. It may end up in a parent <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> in the case that the original function's edge to the new function is a ref edge, and the edge back is a call edge.</p>


<p>Declaration at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1622 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a13b74fdca959e0c5da734f789b298cf6">llvm::LazyCallGraph::Edge::Call</a>, <a href="#ad03c103c6345a262195c485df88d2a21">get</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#ad7483d245bba8b6658b4dbd429f14313">getEdgeKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#afb236ae969b97a215e36acd367e34360">lookup</a>, <a href="#a2b50db13f4a942ed11f2eaaa6e1709f3">lookupRefSCC</a>, <a href="#ad234c24f90aaa0fa3f30ac9c750883b6">lookupSCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a1d6bceebc19a80123ae26670c7645d1a">updateCallGraphAfterCoroutineSplit</a>.</p>

</div>
</div>

### addSplitRefRecursiveFunctions {#a952c8adfe8553406e169b98200072a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::addSplitRefRecursiveFunctions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OriginalFunction, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; NewFunctions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add new ref-recursive functions split/outlined from an existing function.</p>


<p>The new functions may only reference other functions that the original function did. The new functions may reference (not call) the original function.</p>


<p>The original function must reference (not call) all new functions. All new functions must reference (not call) each other.</p>


<p>Declaration at line 1090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#ad03c103c6345a262195c485df88d2a21">get</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#ad7483d245bba8b6658b4dbd429f14313">getEdgeKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a6adb0d1326681c19a5f14a745e17bc32">llvm::LazyCallGraph::Edge::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence/#af575c6f13e2a60386becb2929bec1940">llvm::LazyCallGraph::EdgeSequence::lookup</a>, <a href="#afb236ae969b97a215e36acd367e34360">lookup</a>, <a href="#a2b50db13f4a942ed11f2eaaa6e1709f3">lookupRefSCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a1d6bceebc19a80123ae26670c7645d1a">updateCallGraphAfterCoroutineSplit</a>.</p>

</div>
</div>

### markDeadFunction {#a85788a67cbcd567d28600d43453e342d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::markDeadFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark a function as dead to be removed later by <a href="#a97b7a3d43f4f6eb3ab16554f56bd0cc4">removeDeadFunctions()</a>.</p>


<p>The function body should have no incoming or outgoing call or ref edges. For example, a function with a single "unreachable" instruction.</p>


<p>Declaration at line 1067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1500 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a0aec1afa97220e40f3d67a94455b7833">isLibFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### removeDeadFunctions {#a97b7a3d43f4f6eb3ab16554f56bd0cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::removeDeadFunctions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; DeadFs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove dead functions from the call graph.</p>


<p>These functions should have already been passed to <a href="#a85788a67cbcd567d28600d43453e342d">markDeadFunction()</a>. This is done as a batch to prevent compile time blowup as a result of handling a single function at a time.</p>


<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1523 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#acc4aeec51553504ba50594d9fb8ac4b1">llvm::LazyCallGraph::RefSCC::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#afb236ae969b97a215e36acd367e34360">lookup</a>, <a href="#a2b50db13f4a942ed11f2eaaa6e1709f3">lookupRefSCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#ac62cb27d2f0946c9febb1e1d1e377f55">llvm::LazyCallGraph::RefSCC::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Static helpers for code doing updates to the call graph.



<p>These helpers are used to implement parts of the call graph but are also useful to code doing updates or otherwise wanting to walk the IR in the same patterns as when we build the call graph.</p>


### visitReferences {#a778d0494c2f8dec95d60160b1ce89a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::visitReferences (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; Callback)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively visits the defined functions whose address is reachable from every constant in the <span class="doxyComputerOutput">Worklist</span>.</p>


<p>Doesn't recurse through any constants already in the <span class="doxyComputerOutput">Visited</span> set, and updates that set with every constant visited.</p>


<p>For each defined function, calls <span class="doxyComputerOutput">Callback</span> with that function.</p>


<p>Declaration at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1973 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#ad7483d245bba8b6658b4dbd429f14313">getEdgeKind</a>, <a href="#a58d534b072f7d0fa5f54ff569bb745ec">LazyCallGraph</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
