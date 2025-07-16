---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallsiteContextGraph` Class Template Reference

<p>CRTP base for graphs built from either IR or ThinLTO summary index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;
class anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt;DerivedCCG, FuncTy, CallTy&gt; { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac533932253580a11deeb9414654910aa">EdgeIter</a> = typename std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &gt; &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a99a93c3c92863b0f779dc91de9c463dd">GraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acbfb3d954ea87d753abdcf53da9b2931">DOTGraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e3629b9531f0e5bae3ecce592301d78">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a24a25f8f197ec2041fd2a9efcd4160b1">CallsiteContextGraph</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abedaf92f4f8a7e776d7eaffc9128d5c0">CallsiteContextGraph</a> (const CallsiteContextGraph &amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a936cde44d743c355f2492c732396dd80">CallsiteContextGraph</a> (CallsiteContextGraph &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4652a942c3bcd94d6540e3fb0238d356">process</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main entry point to perform analysis and transformations on graph. <a href="#a4652a942c3bcd94d6540e3fb0238d356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35fd3a36d7623912363f7bc2550aef0b">identifyClones</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform cloning on the graph necessary to uniquely identify the allocation behavior of an allocation based on its context. <a href="#a35fd3a36d7623912363f7bc2550aef0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af222e51d6efae0aeb9ea76cac1b46300">assignFunctions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign callsite clones to functions, cloning functions as needed to accommodate the combinations of their callsite clones reached by callers. <a href="#af222e51d6efae0aeb9ea76cac1b46300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa59e482dfde65bd15ecf6621e9ffaf48">dump</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b182ff5e447c562a7d45505c4b5a63a">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa295e87dfe1eb5dff19dbbe08e8f464">printTotalSizes</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae120eda05be009e7e1124ac882412cad">exportToDot</a> (std::string Label) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5dde305bd14a5c36d35bd957840a1f95">removeNoneTypeCalleeEdges</a> (ContextNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helpers to remove edges that have allocation type None (due to not carrying any context ids) after transformations. <a href="#a5dde305bd14a5c36d35bd957840a1f95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a43cb53754d087a71a26425013204ade4">removeNoneTypeCallerEdges</a> (ContextNode *Node)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7ab368586256d87584451074a8956f3">recursivelyRemoveNoneTypeCalleeEdges</a> (ContextNode *Node, DenseSet&lt; const ContextNode * &gt; &amp;Visited)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT, class IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c04d483e66e81efc4812a2d38b93a8d">addStackNodesForMIB</a> (ContextNode *AllocNode, CallStack&lt; NodeT, IteratorT &gt; &amp;StackContext, CallStack&lt; NodeT, IteratorT &gt; &amp;CallsiteContext, AllocationType AllocType, ArrayRef&lt; ContextTotalSize &gt; ContextSizeInfo)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT, class IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa50d8bf14e4945e56c0cd33548c25ff">getStackIdsWithContextNodes</a> (CallStack&lt; NodeT, IteratorT &gt; &amp;CallsiteContext) -&gt; std::vector&lt; uint64_t &gt;</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT, class IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa50d8bf14e4945e56c0cd33548c25ff">getStackIdsWithContextNodes</a> (CallStack&lt; NodeT, IteratorT &gt; &amp;CallsiteContext) -&gt; std::vector&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a list of nodes corresponding to the stack ids in the given callsite context. <a href="#afa50d8bf14e4945e56c0cd33548c25ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf8f8ad14c08099e793ca64a0768c96a">addAllocNode</a> (CallInfo Call, const FuncTy *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds nodes for the given allocation and any stack ids on its memprof MIB metadata (or summary). <a href="#adf8f8ad14c08099e793ca64a0768c96a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT, class IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c04d483e66e81efc4812a2d38b93a8d">addStackNodesForMIB</a> (ContextNode *AllocNode, CallStack&lt; NodeT, IteratorT &gt; &amp;StackContext, CallStack&lt; NodeT, IteratorT &gt; &amp;CallsiteContext, AllocationType AllocType, ArrayRef&lt; ContextTotalSize &gt; ContextSizeInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds nodes for the given MIB stack ids. <a href="#a3c04d483e66e81efc4812a2d38b93a8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6e0e5a23aea2cd0d2bc271342e6e5c34">updateStackNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Matches all callsite metadata (or summary) to the nodes created for allocation memprof MIB metadata, synthesizing new nodes to reflect any inlining performed on those callsite instructions. <a href="#a6e0e5a23aea2cd0d2bc271342e6e5c34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f3bc3cacc5c440fc83d37726a3af8aa">handleCallsitesWithMultipleTargets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update graph to conservatively handle any callsite stack nodes that target multiple different callee target functions. <a href="#a9f3bc3cacc5c440fc83d37726a3af8aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa262bc6616e27d0c699be16373b96b60">partitionCallsByCallee</a> (ContextNode *Node, ArrayRef&lt; CallInfo &gt; AllCalls, std::vector&lt; std::pair&lt; CallInfo, ContextNode * &gt; &gt; &amp;NewCallToNode)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad73d64678c87dadc606598bbd5fa3a5b">removeEdgeFromGraph</a> (ContextEdge *Edge, EdgeIter *EI=nullptr, bool CalleeIter=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to remove edge from graph, updating edge iterator if it is provided (in which case CalleeIter indicates which edge list is being iterated). <a href="#ad73d64678c87dadc606598bbd5fa3a5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3cc1c4cac072b9ce1d6c79f67ef43e28">assignStackNodesPostOrder</a> (ContextNode *Node, DenseSet&lt; const ContextNode * &gt; &amp;Visited, DenseMap&lt; uint64_t, std::vector&lt; CallContextInfo &gt; &gt; &amp;StackIdToMatchingCalls, DenseMap&lt; CallInfo, CallInfo &gt; &amp;CallToMatchingCall)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns the given <a href="/web-llvm/docs/api/classes/node">Node</a> to calls at or inlined into the location with the <a href="/web-llvm/docs/api/classes/node">Node</a>'s stack id, after post order traversing and processing its caller nodes. <a href="#a3cc1c4cac072b9ce1d6c79f67ef43e28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a2af362f4ae5b5d2852e63f52dbe2bd">duplicateContextIds</a> (const DenseSet&lt; uint32_t &gt; &amp;StackSequenceContextIds, DenseMap&lt; uint32_t, DenseSet&lt; uint32_t &gt; &gt; &amp;OldToNewContextIds) -&gt; <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Duplicates the given set of context ids, updating the provided map from each original id with the newly generated context ids, and returning the new duplicated id set. <a href="#a4a2af362f4ae5b5d2852e63f52dbe2bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae14599e9efb3555b1fdcae80df618d5c">propagateDuplicateContextIds</a> (const DenseMap&lt; uint32_t, DenseSet&lt; uint32_t &gt; &gt; &amp;OldToNewContextIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagates all duplicated context ids across the graph. <a href="#ae14599e9efb3555b1fdcae80df618d5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8adace7955ca256257de26a58df7f00c">connectNewNode</a> (ContextNode *NewNode, ContextNode *OrigNode, bool TowardsCallee, DenseSet&lt; uint32_t &gt; RemainingContextIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Connect the NewNode to OrigNode's callees if TowardsCallee is true, else to its callers. <a href="#a8adace7955ca256257de26a58df7f00c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a95c50766a3bdb199b6d4b99a3a5de523">getStackId</a> (uint64_t IdOrIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the stack id corresponding to the given Id or Index (for IR this will return itself, for a summary index this will return the id recorded in the index for that stack id index value). <a href="#a95c50766a3bdb199b6d4b99a3a5de523">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a969677b7f4458b91551562a2753e92dc">calleesMatch</a> (CallTy Call, EdgeIter &amp;EI, MapVector&lt; CallInfo, ContextNode * &gt; &amp;TailCallToContextNodeMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given call targets the callee of the given edge, or if we were able to identify the call chain through intermediate tail calls. <a href="#a969677b7f4458b91551562a2753e92dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a569d913cca671ac5b2e655aee53d4a41">getCalleeFunc</a> (CallTy Call)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62201839051ee83b40ba20f56fa10ea9">calleeMatchesFunc</a> (CallTy Call, const FuncTy *Func, const FuncTy *CallerFunc, std::vector&lt; std::pair&lt; CallTy, FuncTy * &gt; &gt; &amp;FoundCalleeChain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given call targets the given function, or if we were able to identify the call chain through intermediate tail calls (in which case FoundCalleeChain will be populated). <a href="#a62201839051ee83b40ba20f56fa10ea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6555dee9d1c5f9159b12aedacb3ca033">sameCallee</a> (CallTy Call1, CallTy Call2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if both call instructions have the same callee. <a href="#a6555dee9d1c5f9159b12aedacb3ca033">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af278458be7bedb58014c6e1e491efcd6">getStackIdsWithContextNodesForCall</a> (CallTy Call) -&gt; std::vector&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a list of nodes corresponding to the stack ids in the given callsite's context. <a href="#af278458be7bedb58014c6e1e491efcd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae424a749ecf27d9c15e69d6be3cb276f">getLastStackId</a> (CallTy Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the last stack id in the context for callsite. <a href="#ae424a749ecf27d9c15e69d6be3cb276f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75a2f26d9acccb65a6de28e6085f6389">updateAllocationCall</a> (CallInfo &amp;Call, AllocationType AllocType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the allocation call to record type of allocated memory. <a href="#a75a2f26d9acccb65a6de28e6085f6389">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24622e13e7c21ec4f423f7bb03256499">getAllocationCallType</a> (const CallInfo &amp;Call) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> assigned to the given allocation instruction clone. <a href="#a24622e13e7c21ec4f423f7bb03256499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30785569ce64e11d87b7e2133275e4b8">updateCall</a> (CallInfo &amp;CallerCall, FuncInfo CalleeFunc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update non-allocation call to invoke (possibly cloned) function CalleeFunc. <a href="#a30785569ce64e11d87b7e2133275e4b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/funcinfo">FuncInfo</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae77a8a5f4ff5dd895df0b2a2e5808a28">cloneFunctionForCallsite</a> (FuncInfo &amp;Func, CallInfo &amp;Call, std::map&lt; CallInfo, CallInfo &gt; &amp;CallMap, std::vector&lt; CallInfo &gt; &amp;CallsWithMetadataInFunc, unsigned CloneNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the given function for the given callsite, recording mapping of all of the functions tracked calls to their new versions in the CallMap. <a href="#ae77a8a5f4ff5dd895df0b2a2e5808a28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3dd2335b3998bacdd9bc225312b4eb76">getLabel</a> (const FuncTy *Func, const CallTy Call, unsigned CloneNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets a label to use in the dot graph for the given call clone in the given function. <a href="#a3dd2335b3998bacdd9bc225312b4eb76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16b574cb6107f8227477a7a041263d8a">createNewNode</a> (bool IsAllocation, const FuncTy *F=nullptr, CallInfo C=CallInfo())</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aabee1b7480b1c587a1563385af84237d">getNodeForInst</a> (const CallInfo &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helpers to find the node corresponding to the given call or stackid. <a href="#aabee1b7480b1c587a1563385af84237d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ee77ad870abd263f7b58c02127374c0">getNodeForAlloc</a> (const CallInfo &amp;C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04e61c75e7deb8f99dc08bec3a1db412">getNodeForStackId</a> (uint64_t StackId)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adc48b29f5e4ecf2536eab361040355af">computeAllocType</a> (DenseSet&lt; uint32_t &gt; &amp;ContextIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the alloc type corresponding to the given context ids, by unioning their recorded alloc types. <a href="#adc48b29f5e4ecf2536eab361040355af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae43ce096237287ba9a1d990fa5e34639">intersectAllocTypesImpl</a> (const DenseSet&lt; uint32_t &gt; &amp;Node1Ids, const DenseSet&lt; uint32_t &gt; &amp;Node2Ids)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the allocation type of the intersection of the contexts of two nodes (based on their provided context id sets), optimized for the case when Node1Ids is smaller than Node2Ids. <a href="#ae43ce096237287ba9a1d990fa5e34639">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2c2356b9ad9fdc8410a5fba26c47a0a3">intersectAllocTypes</a> (const DenseSet&lt; uint32_t &gt; &amp;Node1Ids, const DenseSet&lt; uint32_t &gt; &amp;Node2Ids)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the allocation type of the intersection of the contexts of two nodes (based on their provided context id sets). <a href="#a2c2356b9ad9fdc8410a5fba26c47a0a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae34504725352592044ab30d9f4de5cf5">moveEdgeToNewCalleeClone</a> (const std::shared_ptr&lt; ContextEdge &gt; &amp;Edge, DenseSet&lt; uint32_t &gt; ContextIdsToMove={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone of Edge's callee and move Edge to that new callee node, performing the necessary context id and allocation type updates. <a href="#ae34504725352592044ab30d9f4de5cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad57247d61c2f6c1ae4f2db10d216cdf5">moveEdgeToExistingCalleeClone</a> (const std::shared_ptr&lt; ContextEdge &gt; &amp;Edge, ContextNode *NewCallee, bool NewClone=false, DenseSet&lt; uint32_t &gt; ContextIdsToMove={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the callee of Edge to existing callee clone NewCallee, performing the necessary context id and allocation type updates. <a href="#ad57247d61c2f6c1ae4f2db10d216cdf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0694d8f9165217e5ca8e3c4eddec5db3">moveCalleeEdgeToNewCaller</a> (const std::shared_ptr&lt; ContextEdge &gt; &amp;Edge, ContextNode *NewCaller)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the caller of the edge at the given callee edge iterator to be NewCaller, performing the necessary context id and allocation type updates. <a href="#a0694d8f9165217e5ca8e3c4eddec5db3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49817ed3e2ef162d4f365cdaa5a43837">identifyClones</a> (ContextNode *Node, DenseSet&lt; const ContextNode * &gt; &amp;Visited, const DenseSet&lt; uint32_t &gt; &amp;AllocContextIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively perform cloning on the graph for the given <a href="/web-llvm/docs/api/classes/node">Node</a> and its callers, in order to uniquely identify the allocation behavior of an allocation given its context. <a href="#a49817ed3e2ef162d4f365cdaa5a43837">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c30254400cf964764267b34458a24e2">check</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform sanity checks on graph when requested. <a href="#a8c30254400cf964764267b34458a24e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; FuncTy *, std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19492f5e9a4b13d1b78b56c75b1f58a8">FuncToCallsWithMetadata</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save lists of calls with MemProf metadata in each function, for faster iteration. <a href="#a19492f5e9a4b13d1b78b56c75b1f58a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncTy * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf9d501260ea6a430e980b52e0c940f0">NodeToCallingFunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from callsite node to the enclosing caller function. <a href="#abf9d501260ea6a430e980b52e0c940f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a529c3fa1373c4ea7c038b9824a4a3652">ContextIdToAllocationType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from each context <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> assigned to that context. <a href="#a529c3fa1373c4ea7c038b9824a4a3652">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/contexttotalsize">ContextTotalSize</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a424a2d841e289fc09e5418c0a2f5b1ff">ContextIdToContextSizeInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from each contextID to the profiled full contexts and their total sizes (there may be more than one due to context trimming), optionally populated when requested (via MemProfReportHintedSizes or MinClonedColdBytePercent). <a href="#a424a2d841e289fc09e5418c0a2f5b1ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a1ac7395640b7c8d401d4571857a652">StackEntryIdToContextNodeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies the context node created for a stack id when adding the MIB contexts to the graph. <a href="#a7a1ac7395640b7c8d401d4571857a652">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f23511ae6bb5a1f9118a69bc251423d">AllocationCallToContextNodeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps to track the calls to their corresponding nodes in the graph. <a href="#a2f23511ae6bb5a1f9118a69bc251423d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe820c56129b3e3cf5046aa3677f9125">NonAllocationCallToContextNodeMap</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a534d96be94f956b05deab39082114c29">NodeOwner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Owner of all <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> unique_ptrs. <a href="#a534d96be94f956b05deab39082114c29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f0b5f2fd1a54a09bb304edafca0d02c">LastContextId</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of the last unique context id assigned. <a href="#a1f0b5f2fd1a54a09bb304edafca0d02c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>CRTP base for graphs built from either IR or ThinLTO summary index.</p>


<p>The graph represents the call contexts in all memprof metadata on allocation calls, with nodes for the allocations themselves, as well as for the calls in each context. The graph is initially built from the allocation memprof metadata (or summary) MIBs. It is then updated to match calls with callsite metadata onto the nodes, updating it to reflect any inlining performed on those calls.</p>


<p>Each MIB (representing an allocation's call context with allocation behavior) is assigned a unique context id during the graph build. The edges and nodes in the graph are decorated with the context ids they carry. This is used to correctly update the graph when cloning is performed so that we can uniquify the context for a single (possibly cloned) allocation.</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### EdgeIter {#ac533932253580a11deeb9414654910aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::EdgeIter =  typename std::vector&lt;std::shared_ptr&lt;ContextEdge&gt;&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DOTGraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; \* &gt; {#acbfb3d954ea87d753abdcf53da9b2931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits">DOTGraphTraits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph</a>&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a> and <a href="#a9b182ff5e447c562a7d45505c4b5a63a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::print</a>.</p>

</div>
</div>

### GraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; \* &gt; {#a99a93c3c92863b0f779dc91de9c463dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph</a>&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a7e3629b9531f0e5bae3ecce592301d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph</a> &amp; CCG</td>
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


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CallsiteContextGraph() {#a24a25f8f197ec2041fd2a9efcd4160b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph ()</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a65c09e3b6dd0ad4eada5aeb000e6b43f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::addOrUpdateCallerEdge</a>, <a href="#a936cde44d743c355f2492c732396dd80">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="#abedaf92f4f8a7e776d7eaffc9128d5c0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="#acbfb3d954ea87d753abdcf53da9b2931">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::DOTGraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge/#aa5857119fe2945f58e00ac6d95feda0b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#af75089d03f37e5a0401e2ebf85133ba6">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#affae140ed481aa061f54e9acd2ab7100">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::eraseCalleeEdge</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#ab34ce9ab779bd29faf752c7a91f364a6">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::eraseCallerEdge</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a3ce81b07a0aafa3672824164e18fd7ff">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::findEdgeFromCallee</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#ad7a94fea6eeece35ff273e7c7bf0d293">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::findEdgeFromCaller</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge/#ab6c023223ec2c5481dd82c860deed2f8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>, <a href="#a9b182ff5e447c562a7d45505c4b5a63a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::print</a> and <a href="#aaa295e87dfe1eb5dff19dbbe08e8f464">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::printTotalSizes</a>.</p>

</div>
</div>

### CallsiteContextGraph() {#abedaf92f4f8a7e776d7eaffc9128d5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph</a> &amp;)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>.</p>

</div>
</div>

### CallsiteContextGraph() {#a936cde44d743c355f2492c732396dd80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph (<a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph</a> &amp;&amp;)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addStackNodesForMIB() {#a3c04d483e66e81efc4812a2d38b93a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT, class IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::addStackNodesForMIB (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * AllocNode, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstack">CallStack</a>&lt; NodeT, IteratorT &gt; &amp; StackContext, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstack">CallStack</a>&lt; NodeT, IteratorT &gt; &amp; CallsiteContext, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/contexttotalsize">ContextTotalSize</a> &gt; ContextSizeInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### assignFunctions() {#af222e51d6efae0aeb9ea76cac1b46300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallsiteContextGraph::assignFunctions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign callsite clones to functions, cloning functions as needed to accommodate the combinations of their callsite clones reached by callers.</p>


<p>For regular LTO this clones functions and callsites in the IR, but for ThinLTO the cloning decisions are noted in the summaries and later applied in applyImport.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a2f5bb5c9a5b60b75cc7e80a72d1711da">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::AllocTypes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a20c00c2a87e53869acc65017497e9fe2">anonymous{MemProfContextDisambiguation.cpp}::allocTypeToUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#aab8eeabd26ce6b92243a5f349e323256">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#ab6a774bfe473897840683fe5c52e200f">checkNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a1a3c2e99e572ec71d3820d0363d90742">llvm::Cold</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#a19492f5e9a4b13d1b78b56c75b1f58a8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::FuncToCallsWithMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#ade739c46ca314fc9fc3cf4c9089f048b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::MatchingCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#af7e93a7f4bbea37887b3fc9be720b8d0">MinClonedColdBytePercent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ad814aa38fbac7f6d03b30741366aae56">llvm::NotCold</a>, <a href="#a5dde305bd14a5c36d35bd957840a1f95">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::removeNoneTypeCalleeEdges</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a3ad507e0575b074da4f909f338c7bab4">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::setCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo/#a2804f29c7c74811f26da7326fc142fc6">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallInfo::setCloneNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#aadb6dc3c4ec78048014fdbb22a247ee7">VerifyCCG</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#af3a6c5634d5eb4b762f53497d495c4b2">VerifyNodes</a>.</p>


<p>Referenced by <a href="#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a>.</p>

</div>
</div>

### dump() {#aa59e482dfde65bd15ecf6621e9ffaf48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a9b182ff5e447c562a7d45505c4b5a63a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::print</a>.</p>

</div>
</div>

### exportToDot() {#ae120eda05be009e7e1124ac882412cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::exportToDot (std::string Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#ae3aebd4fa3b5e0d3a952fd4543bde380">DotFilePathPrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a45fc498e695e5b2061ab5e6ec8e604a1">llvm::WriteGraph</a>.</p>


<p>Referenced by <a href="#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a>.</p>

</div>
</div>

### getStackIdsWithContextNodes() {#afa50d8bf14e4945e56c0cd33548c25ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT, class IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getStackIdsWithContextNodes (<a href="/web-llvm/docs/api/classes/llvm/memprof/callstack">CallStack</a>&lt; NodeT, IteratorT &gt; &amp; CallsiteContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### identifyClones() {#a35fd3a36d7623912363f7bc2550aef0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::identifyClones ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform cloning on the graph necessary to uniquely identify the allocation behavior of an allocation based on its context.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1fbf4d66a9eeaa9ade03e8febee097ee">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::clear</a>, <a href="#a35fd3a36d7623912363f7bc2550aef0b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::identifyClones</a>, <a href="#ab7ab368586256d87584451074a8956f3">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::recursivelyRemoveNoneTypeCalleeEdges</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#aadb6dc3c4ec78048014fdbb22a247ee7">VerifyCCG</a>.</p>


<p>Referenced by <a href="#a35fd3a36d7623912363f7bc2550aef0b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::identifyClones</a> and <a href="#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a>.</p>

</div>
</div>

### print() {#a9b182ff5e447c562a7d45505c4b5a63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#aaa253dd3e56c37edd403113782c0ef94">nodes</a> and <a href="/web-llvm/docs/api/classes/node/#a05779201e7fa0913e5b50fdbc5c49135">Node::print</a>.</p>


<p>Referenced by <a href="#acbfb3d954ea87d753abdcf53da9b2931">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::DOTGraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge/#aa5857119fe2945f58e00ac6d95feda0b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::dump</a> and <a href="#aa59e482dfde65bd15ecf6621e9ffaf48">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::dump</a>.</p>

</div>
</div>

### printTotalSizes() {#aaa295e87dfe1eb5dff19dbbe08e8f464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::printTotalSizes (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a20c00c2a87e53869acc65017497e9fe2">anonymous{MemProfContextDisambiguation.cpp}::allocTypeToUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad7dc7318244359268414719e0959346e">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::begin</a>, <a href="#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a8cd802dcaed35e1f28ea3cbe4af4eff5">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a78e5652d529e02da75e8087017930e28">getAllocTypeString</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#aaa253dd3e56c37edd403113782c0ef94">nodes</a>.</p>


<p>Referenced by <a href="#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a>.</p>

</div>
</div>

### process() {#a4652a942c3bcd94d6540e3fb0238d356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallsiteContextGraph::process ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Main entry point to perform analysis and transformations on graph.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#af4908b838f5705fa3d04d8884821a574">DumpCCG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a3f48d17e9412f965032b446536238a61">ExportToDot</a>, <a href="#ae120eda05be009e7e1124ac882412cad">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::exportToDot</a>, <a href="#a35fd3a36d7623912363f7bc2550aef0b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::identifyClones</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a696467f077d0e94dc6b3f171acc6be25">MemProfReportHintedSizes</a>, <a href="#aaa295e87dfe1eb5dff19dbbe08e8f464">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::printTotalSizes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#aadb6dc3c4ec78048014fdbb22a247ee7">VerifyCCG</a>.</p>

</div>
</div>

### recursivelyRemoveNoneTypeCalleeEdges() {#ab7ab368586256d87584451074a8956f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::recursivelyRemoveNoneTypeCalleeEdges (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#ab7ab368586256d87584451074a8956f3">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::recursivelyRemoveNoneTypeCalleeEdges</a> and <a href="#a5dde305bd14a5c36d35bd957840a1f95">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::removeNoneTypeCalleeEdges</a>.</p>


<p>Referenced by <a href="#a35fd3a36d7623912363f7bc2550aef0b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::identifyClones</a> and <a href="#ab7ab368586256d87584451074a8956f3">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::recursivelyRemoveNoneTypeCalleeEdges</a>.</p>

</div>
</div>

### removeNoneTypeCalleeEdges() {#a5dde305bd14a5c36d35bd957840a1f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::removeNoneTypeCalleeEdges (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helpers to remove edges that have allocation type None (due to not carrying any context ids) after transformations.</p>

<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a> and <a href="#ab7ab368586256d87584451074a8956f3">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::recursivelyRemoveNoneTypeCalleeEdges</a>.</p>

</div>
</div>

### removeNoneTypeCallerEdges() {#a43cb53754d087a71a26425013204ade4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::removeNoneTypeCallerEdges (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#aa262bc6616e27d0c699be16373b96b60">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::partitionCallsByCallee</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addAllocNode() {#adf8f8ad14c08099e793ca64a0768c96a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode * CallsiteContextGraph::addAllocNode (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncTy * F)</td>
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

<p>Adds nodes for the given allocation and any stack ids on its memprof MIB metadata (or summary).</p>

<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a2f5bb5c9a5b60b75cc7e80a72d1711da">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::AllocTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#aef8270c7f9cb86c77eae179db3c54a92">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::OrigStackOrAllocId</a>.</p>

</div>
</div>

### addStackNodesForMIB() {#a3c04d483e66e81efc4812a2d38b93a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT, class IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::addStackNodesForMIB (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * AllocNode, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstack">CallStack</a>&lt; NodeT, IteratorT &gt; &amp; StackContext, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstack">CallStack</a>&lt; NodeT, IteratorT &gt; &amp; CallsiteContext, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/contexttotalsize">ContextTotalSize</a> &gt; ContextSizeInfo)</td>
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

<p>Adds nodes for the given MIB stack ids.</p>

<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getStackIdsWithContextNodes() {#afa50d8bf14e4945e56c0cd33548c25ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT, class IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getStackIdsWithContextNodes (<a href="/web-llvm/docs/api/classes/llvm/memprof/callstack">CallStack</a>&lt; NodeT, IteratorT &gt; &amp; CallsiteContext)</td>
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

<p>Get a list of nodes corresponding to the stack ids in the given callsite context.</p>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### handleCallsitesWithMultipleTargets() {#a9f3bc3cacc5c440fc83d37726a3af8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::handleCallsitesWithMultipleTargets ()</td>
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

<p>Update graph to conservatively handle any callsite stack nodes that target multiple different callee target functions.</p>

<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9f3bc3cacc5c440fc83d37726a3af8aa">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::handleCallsitesWithMultipleTargets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="#abf9d501260ea6a430e980b52e0c940f0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::NodeToCallingFunc</a>, <a href="#aa262bc6616e27d0c699be16373b96b60">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::partitionCallsByCallee</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a862208c77d7ea13b440b4ff84911c1a4">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::remove_if</a>.</p>


<p>Referenced by <a href="#a9f3bc3cacc5c440fc83d37726a3af8aa">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::handleCallsitesWithMultipleTargets</a>.</p>

</div>
</div>

### partitionCallsByCallee() {#aa262bc6616e27d0c699be16373b96b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallsiteContextGraph::partitionCallsByCallee (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &gt; AllCalls, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt; &gt; &amp; NewCallToNode)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#abf9d501260ea6a430e980b52e0c940f0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::NodeToCallingFunc</a> and <a href="#a43cb53754d087a71a26425013204ade4">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::removeNoneTypeCallerEdges</a>.</p>


<p>Referenced by <a href="#a9f3bc3cacc5c440fc83d37726a3af8aa">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::handleCallsitesWithMultipleTargets</a>.</p>

</div>
</div>

### updateStackNodes() {#a6e0e5a23aea2cd0d2bc271342e6e5c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::updateStackNodes ()</td>
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

<p>Matches all callsite metadata (or summary) to the nodes created for allocation memprof MIB metadata, synthesizing new nodes to reflect any inlining performed on those callsite instructions.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#aab8eeabd26ce6b92243a5f349e323256">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1fbf4d66a9eeaa9ade03e8febee097ee">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#ad7a94fea6eeece35ff273e7c7bf0d293">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::findEdgeFromCaller</a>, <a href="#a19492f5e9a4b13d1b78b56c75b1f58a8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::FuncToCallsWithMetadata</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a14ae478e63dbd2596e224ab2e88e1d3b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getContextIds</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a8d1422c851165b12a95d0cff1c7a1162">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Recursive</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#ae292a4b96e7f74eb95a4176ddba7b821">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::reserve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2162d123f222998300d308bdefdb38b9">llvm::set_intersect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e1137200d6e86367be1d605fdc14e6c">llvm::set_subtract</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a025cb106832026cd05c2b4648a699f">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#aadb6dc3c4ec78048014fdbb22a247ee7">VerifyCCG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignStackNodesPostOrder() {#a3cc1c4cac072b9ce1d6c79f67ef43e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::assignStackNodesPostOrder (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, std::vector&lt; CallContextInfo &gt; &gt; &amp; StackIdToMatchingCalls, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &gt; &amp; CallToMatchingCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assigns the given <a href="/web-llvm/docs/api/classes/node">Node</a> to calls at or inlined into the location with the <a href="/web-llvm/docs/api/classes/node">Node</a>'s stack id, after post order traversing and processing its caller nodes.</p>


<p>Uses the call information recorded in the given StackIdToMatchingCalls map, and creates new nodes for inlined sequences as needed. Called by updateStackNodes which sets up the given StackIdToMatchingCalls map.</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### calleeMatchesFunc() {#a62201839051ee83b40ba20f56fa10ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::calleeMatchesFunc (CallTy Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncTy * Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncTy * CallerFunc, std::vector&lt; std::pair&lt; CallTy, FuncTy * &gt; &gt; &amp; FoundCalleeChain)</td>
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

<p>Returns true if the given call targets the given function, or if we were able to identify the call chain through intermediate tail calls (in which case FoundCalleeChain will be populated).</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### calleesMatch() {#a969677b7f4458b91551562a2753e92dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallsiteContextGraph::calleesMatch (CallTy Call, EdgeIter &amp; EI, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt; &amp; TailCallToContextNodeMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the given call targets the callee of the given edge, or if we were able to identify the call chain through intermediate tail calls.</p>


<p>In the latter case new context nodes are added to the graph for the identified tail calls, and their synthesized nodes are added to TailCallToContextNodeMap. The EdgeIter is updated in the latter case for the updated edges and to prepare it for an increment in the caller.</p>


<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### check() {#a8c30254400cf964764267b34458a24e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::check ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform sanity checks on graph when requested.</p>

<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### cloneFunctionForCallsite() {#ae77a8a5f4ff5dd895df0b2a2e5808a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncInfo anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::cloneFunctionForCallsite (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/funcinfo">FuncInfo</a> &amp; Func, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &amp; Call, std::map&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &gt; &amp; CallMap, std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &gt; &amp; CallsWithMetadataInFunc, unsigned CloneNo)</td>
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

<p>Clone the given function for the given callsite, recording mapping of all of the functions tracked calls to their new versions in the CallMap.</p>


<p>Assigns new clones to clone number CloneNo.</p>


<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### computeAllocType() {#adc48b29f5e4ecf2536eab361040355af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t CallsiteContextGraph::computeAllocType (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp; ContextIds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the alloc type corresponding to the given context ids, by unioning their recorded alloc types.</p>

<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### connectNewNode() {#a8adace7955ca256257de26a58df7f00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::connectNewNode (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * NewNode, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * OrigNode, bool TowardsCallee, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; RemainingContextIds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Connect the NewNode to OrigNode's callees if TowardsCallee is true, else to its callers.</p>


<p>Also updates OrigNode's edges to remove any context ids moved to the newly created edge.</p>


<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### createNewNode() {#a16b574cb6107f8227477a7a041263d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode * anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::createNewNode (bool IsAllocation, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncTy * F=nullptr, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> C=<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>())</td>
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



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### duplicateContextIds() {#a4a2af362f4ae5b5d2852e63f52dbe2bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt; uint32_t &gt; CallsiteContextGraph::duplicateContextIds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp; StackSequenceContextIds, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &gt; &amp; OldToNewContextIds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Duplicates the given set of context ids, updating the provided map from each original id with the newly generated context ids, and returning the new duplicated id set.</p>

<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getAllocationCallType() {#a24622e13e7c21ec4f423f7bb03256499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocationType anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getAllocationCallType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &amp; Call)</td>
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

<p>Get the <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> assigned to the given allocation instruction clone.</p>

<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getCalleeFunc() {#a569d913cca671ac5b2e655aee53d4a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FuncTy * anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getCalleeFunc (CallTy Call)</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getLabel() {#a3dd2335b3998bacdd9bc225312b4eb76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncTy * Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CallTy Call, unsigned CloneNo)</td>
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

<p>Gets a label to use in the dot graph for the given call clone in the given function.</p>

<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getLastStackId() {#ae424a749ecf27d9c15e69d6be3cb276f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getLastStackId (CallTy Call)</td>
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

<p>Get the last stack id in the context for callsite.</p>

<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getNodeForAlloc() {#a7ee77ad870abd263f7b58c02127374c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode * CallsiteContextGraph::getNodeForAlloc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getNodeForInst() {#aabee1b7480b1c587a1563385af84237d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode * CallsiteContextGraph::getNodeForInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helpers to find the node corresponding to the given call or stackid.</p>

<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getNodeForStackId() {#a04e61c75e7deb8f99dc08bec3a1db412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode * CallsiteContextGraph::getNodeForStackId (uint64_t StackId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getStackId() {#a95c50766a3bdb199b6d4b99a3a5de523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getStackId (uint64_t IdOrIndex)</td>
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

<p>Get the stack id corresponding to the given Id or Index (for IR this will return itself, for a summary index this will return the id recorded in the index for that stack id index value).</p>

<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getStackIdsWithContextNodesForCall() {#af278458be7bedb58014c6e1e491efcd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::getStackIdsWithContextNodesForCall (CallTy Call)</td>
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

<p>Get a list of nodes corresponding to the stack ids in the given callsite's context.</p>

<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### identifyClones() {#a49817ed3e2ef162d4f365cdaa5a43837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::identifyClones (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp; AllocContextIds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively perform cloning on the graph for the given <a href="/web-llvm/docs/api/classes/node">Node</a> and its callers, in order to uniquely identify the allocation behavior of an allocation given its context.</p>


<p>The context ids of the allocation being processed are given in AllocContextIds.</p>


<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### intersectAllocTypes() {#a2c2356b9ad9fdc8410a5fba26c47a0a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t CallsiteContextGraph::intersectAllocTypes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp; Node1Ids, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp; Node2Ids)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the allocation type of the intersection of the contexts of two nodes (based on their provided context id sets).</p>

<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### intersectAllocTypesImpl() {#ae43ce096237287ba9a1d990fa5e34639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t CallsiteContextGraph::intersectAllocTypesImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp; Node1Ids, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp; Node2Ids)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the allocation type of the intersection of the contexts of two nodes (based on their provided context id sets), optimized for the case when Node1Ids is smaller than Node2Ids.</p>

<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### moveCalleeEdgeToNewCaller() {#a0694d8f9165217e5ca8e3c4eddec5db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::moveCalleeEdgeToNewCaller (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &gt; &amp; Edge, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * NewCaller)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the caller of the edge at the given callee edge iterator to be NewCaller, performing the necessary context id and allocation type updates.</p>


<p>This is similar to the above moveEdgeToExistingCalleeClone, but a simplified version of it as we always move the given edge and all of its context ids.</p>


<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### moveEdgeToExistingCalleeClone() {#ad57247d61c2f6c1ae4f2db10d216cdf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::moveEdgeToExistingCalleeClone (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &gt; &amp; Edge, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * NewCallee, bool NewClone=false, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; ContextIdsToMove={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the callee of Edge to existing callee clone NewCallee, performing the necessary context id and allocation type updates.</p>


<p>If ContextIdsToMove is non-empty, only that subset of Edge's ids are moved to an edge to the new callee.</p>


<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### moveEdgeToNewCalleeClone() {#ae34504725352592044ab30d9f4de5cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode * CallsiteContextGraph::moveEdgeToNewCalleeClone (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &gt; &amp; Edge, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; ContextIdsToMove={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a clone of Edge's callee and move Edge to that new callee node, performing the necessary context id and allocation type updates.</p>


<p>If ContextIdsToMove is non-empty, only that subset of Edge's ids are moved to an edge to the new callee.</p>


<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### propagateDuplicateContextIds() {#ae14599e9efb3555b1fdcae80df618d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::propagateDuplicateContextIds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &gt; &amp; OldToNewContextIds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Propagates all duplicated context ids across the graph.</p>

<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### removeEdgeFromGraph() {#ad73d64678c87dadc606598bbd5fa3a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::removeEdgeFromGraph (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> * Edge, EdgeIter * EI=nullptr, bool CalleeIter=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to remove edge from graph, updating edge iterator if it is provided (in which case CalleeIter indicates which edge list is being iterated).</p>


<p>This will also perform the necessary clearing of the <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> members to enable later checking if the edge has been removed (since we may have other copies of the shared_ptr in existence, and in fact rely on this to enable removal while iterating over a copy of a node's edge list).</p>


<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### sameCallee() {#a6555dee9d1c5f9159b12aedacb3ca033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::sameCallee (CallTy Call1, CallTy Call2)</td>
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

<p>Returns true if both call instructions have the same callee.</p>

<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### updateAllocationCall() {#a75a2f26d9acccb65a6de28e6085f6389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateAllocationCall (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &amp; Call, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType)</td>
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

<p>Update the allocation call to record type of allocated memory.</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### updateCall() {#a30785569ce64e11d87b7e2133275e4b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateCall (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> &amp; CallerCall, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/funcinfo">FuncInfo</a> CalleeFunc)</td>
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

<p>Update non-allocation call to invoke (possibly cloned) function CalleeFunc.</p>

<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### FuncToCallsWithMetadata {#a19492f5e9a4b13d1b78b56c75b1f58a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;FuncTy *, std::vector&lt;CallInfo&gt; &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::FuncToCallsWithMetadata</td>
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

<p>Save lists of calls with MemProf metadata in each function, for faster iteration.</p>

<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a> and <a href="#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateStackNodes</a>.</p>

</div>
</div>

### NodeToCallingFunc {#abf9d501260ea6a430e980b52e0c940f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;const ContextNode *, const FuncTy *&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::NodeToCallingFunc</td>
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

<p>Map from callsite node to the enclosing caller function.</p>

<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a9f3bc3cacc5c440fc83d37726a3af8aa">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::handleCallsitesWithMultipleTargets</a> and <a href="#aa262bc6616e27d0c699be16373b96b60">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::partitionCallsByCallee</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocationCallToContextNodeMap {#a2f23511ae6bb5a1f9118a69bc251423d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;CallInfo, ContextNode *&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::AllocationCallToContextNodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps to track the calls to their corresponding nodes in the graph.</p>

<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### ContextIdToAllocationType {#a529c3fa1373c4ea7c038b9824a4a3652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint32_t, AllocationType&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextIdToAllocationType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from each context <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> assigned to that context.</p>

<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### ContextIdToContextSizeInfos {#a424a2d841e289fc09e5418c0a2f5b1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint32_t, std::vector&lt;ContextTotalSize&gt; &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextIdToContextSizeInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from each contextID to the profiled full contexts and their total sizes (there may be more than one due to context trimming), optionally populated when requested (via MemProfReportHintedSizes or MinClonedColdBytePercent).</p>

<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### LastContextId {#a1f0b5f2fd1a54a09bb304edafca0d02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::LastContextId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of the last unique context id assigned.</p>

<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### NodeOwner {#a534d96be94f956b05deab39082114c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ContextNode&gt; &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::NodeOwner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Owner of all <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> unique_ptrs.</p>

<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### NonAllocationCallToContextNodeMap {#abe820c56129b3e3cf5046aa3677f9125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;CallInfo, ContextNode *&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::NonAllocationCallToContextNodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### StackEntryIdToContextNodeMap {#a7a1ac7395640b7c8d401d4571857a652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, ContextNode *&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::StackEntryIdToContextNodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies the context node created for a stack id when adding the MIB contexts to the graph.</p>


<p>This is used to locate the context nodes when trying to assign the corresponding callsites with those stack ids to these nodes.</p>


<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
