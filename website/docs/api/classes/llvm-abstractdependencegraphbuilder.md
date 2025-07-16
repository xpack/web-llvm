---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/abstractdependencegraphbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AbstractDependenceGraphBuilder` Class Template Reference

<p>This abstract builder class defines a set of high-level steps for creating DDG-like graphs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class GraphType&gt;
class llvm::AbstractDependenceGraphBuilder&lt;GraphType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">llvm/Analysis/DependenceGraphBuilder.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a98fe94e87e392a7b217baab63cfbe821">ClassesType</a> = <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac6158af6f5ec713149c0547d07d6cabe">NodeListType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; NodeType *, 4 &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b2bdc5e87a8bb28088f7af9ec9201ab">BasicBlockListType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a17ddea5e93745f0f45f79a33964caa18">InstToNodeMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, NodeType * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map types to map instructions to nodes used when populating the graph. <a href="#a17ddea5e93745f0f45f79a33964caa18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb8f7ff0ddb759dcbf5768f6c225a8f8">InstToOrdinalMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, size_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map Types to map instruction/nodes to an ordinal number. <a href="#aeb8f7ff0ddb759dcbf5768f6c225a8f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a77f48b546fbaf209b15da0255e8468ee">NodeToOrdinalMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; NodeType *, size_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa150570f7614f558d3bc16152421504">NodeType</a> = typename GraphType::NodeType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c6b74a8b3e367638281a0320fded7c7">EdgeType</a> = typename GraphType::EdgeType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7b91f6ee87fdd6c6992b19918a51a8fc">AbstractDependenceGraphBuilder</a> (GraphType &amp;G, DependenceInfo &amp;D, const BasicBlockListType &amp;BBs)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a923889e18d18e7f53ace52a374a70597">~AbstractDependenceGraphBuilder</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa6cc092387721c9933bb8ec763767c3d">populate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The main entry to the graph construction algorithm. <a href="#aa6cc092387721c9933bb8ec763767c3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a022f8d18fe9e9e880c51db47e2f372db">computeInstructionOrdinals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute ordinal numbers for each instruction and store them in a map for future look up. <a href="#a022f8d18fe9e9e880c51db47e2f372db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56732d193d3946d953c77a80e07ef61a">createFineGrainedNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create fine grained nodes. <a href="#a56732d193d3946d953c77a80e07ef61a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac76acbd497d18c7306f8120c6f11fb51">createDefUseEdges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the def-use chains and create edges from the nodes containing definitions to the nodes containing the uses. <a href="#ac76acbd497d18c7306f8120c6f11fb51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c4196edca24d644ff96e55945abd207">createMemoryDependencyEdges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze data dependencies that exist between memory loads or stores, in the graph nodes and create edges between them. <a href="#a9c4196edca24d644ff96e55945abd207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a008891a00a9aec8710d95ec82fd72196">createAndConnectRootNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a root node and add edges such that each node in the graph is reachable from the root. <a href="#a008891a00a9aec8710d95ec82fd72196">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afba90b653098f15528a273ced632683a">createPiBlocks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply graph abstraction to groups of nodes that belong to a strongly connected component of the graph to create larger compound nodes called pi-blocks. <a href="#afba90b653098f15528a273ced632683a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa58986a6df89ded5c86fc981ad2bf53c">simplify</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go through all the nodes in the graph and collapse any two nodes 'a' and 'b' if all of the following are true: <a href="#aa58986a6df89ded5c86fc981ad2bf53c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ca7af382aa1a34576aee355f364447c">sortNodesTopologically</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Topologically sort the graph nodes. <a href="#a2ca7af382aa1a34576aee355f364447c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d0ad7c2f9c9bd805cf19a4b8936e6ae">createRootNode</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the root node of the graph. <a href="#a6d0ad7c2f9c9bd805cf19a4b8936e6ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49a5519e92004994b7d31bdded9fa0d9">createFineGrainedNode</a> (Instruction &amp;I)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an atomic node in the graph given a single instruction. <a href="#a49a5519e92004994b7d31bdded9fa0d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a692ad63098f0ae1d0a7e87cee6dedd6a">createPiBlock</a> (const NodeListType &amp;L)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pi-block node in the graph representing a group of nodes in an SCC of the graph. <a href="#a692ad63098f0ae1d0a7e87cee6dedd6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">EdgeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8745968d747fee2b8c98819422bd172e">createDefUseEdge</a> (NodeType &amp;Src, NodeType &amp;Tgt)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a def-use edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>. <a href="#a8745968d747fee2b8c98819422bd172e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">EdgeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0db1eaa1d590ee67f96ee2118af4e5b7">createMemoryEdge</a> (NodeType &amp;Src, NodeType &amp;Tgt)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a memory dependence edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>. <a href="#a0db1eaa1d590ee67f96ee2118af4e5b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">EdgeType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a550d05205fe4e217c45862cd0455386e">createRootedEdge</a> (NodeType &amp;Src, NodeType &amp;Tgt)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a rooted edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span> . <a href="#a550d05205fe4e217c45862cd0455386e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ac6158af6f5ec713149c0547d07d6cabe">NodeListType</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05e33cd36780875465c50c22d1a85ddd">getNodesInPiBlock</a> (const NodeType &amp;N)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a pi-block node, return a vector of all the nodes contained within it. <a href="#a05e33cd36780875465c50c22d1a85ddd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d2445b044da844555d1f25db33979ce">destroyEdge</a> (EdgeType &amp;E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate memory of edge <span class="doxyComputerOutput">E</span>. <a href="#a0d2445b044da844555d1f25db33979ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab95e08bc6b6b4d0e95caada63521ad6d">destroyNode</a> (NodeType &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate memory of node <span class="doxyComputerOutput">N</span>. <a href="#ab95e08bc6b6b4d0e95caada63521ad6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0efe68c840fb839433af923abcf4f98a">shouldCreatePiBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if creation of pi-blocks are supported and desired, and false otherwise. <a href="#a0efe68c840fb839433af923abcf4f98a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16d76d7fa8623d797dc380af58f7c22e">shouldSimplify</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if graph simplification step is requested, and false otherwise. <a href="#a16d76d7fa8623d797dc380af58f7c22e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4e8f893add52ec0fef867263cf6982f">areNodesMergeable</a> (const NodeType &amp;A, const NodeType &amp;B) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's safe to merge the two nodes. <a href="#af4e8f893add52ec0fef867263cf6982f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa203d4dd4a4b21ce9f1769684ead617a">mergeNodes</a> (NodeType &amp;A, NodeType &amp;B)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the content of node <span class="doxyComputerOutput">B</span> into node <span class="doxyComputerOutput">A</span> and remove <span class="doxyComputerOutput">B</span> and the edge between <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> from the graph. <a href="#aa203d4dd4a4b21ce9f1769684ead617a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac47f2ea1faaea3efe3e33337c0738c2f">getOrdinal</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an instruction <span class="doxyComputerOutput">I</span> return its associated ordinal number. <a href="#ac47f2ea1faaea3efe3e33337c0738c2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac987bb4640feeb3e68c416f1bba3d8e3">getOrdinal</a> (NodeType &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a node <span class="doxyComputerOutput">N</span> return its associated ordinal number. <a href="#ac987bb4640feeb3e68c416f1bba3d8e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">GraphType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adfe1af074dc71e900744bf6e4fbe3356">Graph</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the graph that gets built by a concrete implementation of this builder. <a href="#adfe1af074dc71e900744bf6e4fbe3356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa209c1bf2741fdb9c4f7faf9428004cb">DI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> information used to create memory dependence edges in the graph. <a href="#aa209c1bf2741fdb9c4f7faf9428004cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3b2bdc5e87a8bb28088f7af9ec9201ab">BasicBlockListType</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa3998e38833526aca81deca3aa8bef8">BBList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of basic blocks to consider when building the graph. <a href="#aaa3998e38833526aca81deca3aa8bef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a17ddea5e93745f0f45f79a33964caa18">InstToNodeMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaba43f6de0784dea46cb0cab896cb63a">IMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from instructions to the corresponding nodes in the graph. <a href="#aaba43f6de0784dea46cb0cab896cb63a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aeb8f7ff0ddb759dcbf5768f6c225a8f8">InstToOrdinalMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76b252b935930d919653b4b647c06fed">InstOrdinalMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from each instruction to an ordinal number. <a href="#a76b252b935930d919653b4b647c06fed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class GraphType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a77f48b546fbaf209b15da0255e8468ee">NodeToOrdinalMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace3dba236f7832e89050397843bc5deb">NodeOrdinalMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from nodes to an ordinal number. <a href="#ace3dba236f7832e89050397843bc5deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This abstract builder class defines a set of high-level steps for creating DDG-like graphs.</p>


<p>The client code is expected to inherit from this class and define concrete implementation for each of the pure virtual functions used in the high-level algorithm.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ClassesType {#a98fe94e87e392a7b217baab63cfbe821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::ClassesType =  EquivalenceClasses&lt;BasicBlock *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### NodeListType {#ac6158af6f5ec713149c0547d07d6cabe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::NodeListType =  SmallVector&lt;NodeType *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Typedefs

### BasicBlockListType {#a3b2bdc5e87a8bb28088f7af9ec9201ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::BasicBlockListType =  SmallVectorImpl&lt;BasicBlock *&gt;</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### InstToNodeMap {#a17ddea5e93745f0f45f79a33964caa18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::InstToNodeMap =  DenseMap&lt;Instruction *, NodeType *&gt;</td>
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

<p>Map types to map instructions to nodes used when populating the graph.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### InstToOrdinalMap {#aeb8f7ff0ddb759dcbf5768f6c225a8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::InstToOrdinalMap =  DenseMap&lt;Instruction *, size_t&gt;</td>
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

<p>Map Types to map instruction/nodes to an ordinal number.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### NodeToOrdinalMap {#a77f48b546fbaf209b15da0255e8468ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::NodeToOrdinalMap =  DenseMap&lt;NodeType *, size_t&gt;</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### EdgeType {#a6c6b74a8b3e367638281a0320fded7c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::EdgeType =  typename GraphType::EdgeType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### NodeType {#aaa150570f7614f558d3bc16152421504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::NodeType =  typename GraphType::NodeType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AbstractDependenceGraphBuilder() {#a7b91f6ee87fdd6c6992b19918a51a8fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::AbstractDependenceGraphBuilder (GraphType &amp; G, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3b2bdc5e87a8bb28088f7af9ec9201ab">BasicBlockListType</a> &amp; BBs)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>References <a href="#aaa3998e38833526aca81deca3aa8bef8">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::BBList</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#aa209c1bf2741fdb9c4f7faf9428004cb">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::DI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::Graph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AbstractDependenceGraphBuilder() {#a923889e18d18e7f53ace52a374a70597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::~AbstractDependenceGraphBuilder ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeInstructionOrdinals() {#a022f8d18fe9e9e880c51db47e2f372db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::computeInstructionOrdinals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute ordinal numbers for each instruction and store them in a map for future look up.</p>


<p>These ordinals are used to compute node ordinals which are in turn used to order nodes that are part of a cycle. <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> ordinals are assigned based on lexical program order.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>References <a href="#aaa3998e38833526aca81deca3aa8bef8">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::BBList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a76b252b935930d919653b4b647c06fed">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::InstOrdinalMap</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

### createAndConnectRootNode() {#a008891a00a9aec8710d95ec82fd72196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::createAndConnectRootNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a root node and add edges such that each node in the graph is reachable from the root.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

### createDefUseEdges() {#ac76acbd497d18c7306f8120c6f11fb51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::createDefUseEdges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the def-use chains and create edges from the nodes containing definitions to the nodes containing the uses.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>References <a href="#a8745968d747fee2b8c98819422bd172e">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createDefUseEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::Graph</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#aaba43f6de0784dea46cb0cab896cb63a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::IMap</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

### createFineGrainedNodes() {#a56732d193d3946d953c77a80e07ef61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::createFineGrainedNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create fine grained nodes.</p>


<p>These are typically atomic nodes that consist of a single instruction.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaa3998e38833526aca81deca3aa8bef8">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::BBList</a>, <a href="#a49a5519e92004994b7d31bdded9fa0d9">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNode</a>, <a href="#ac47f2ea1faaea3efe3e33337c0738c2f">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getOrdinal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aaba43f6de0784dea46cb0cab896cb63a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::IMap</a> and <a href="#ace3dba236f7832e89050397843bc5deb">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::NodeOrdinalMap</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

### createMemoryDependencyEdges() {#a9c4196edca24d644ff96e55945abd207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::createMemoryDependencyEdges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze data dependencies that exist between memory loads or stores, in the graph nodes and create edges between them.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>References <a href="#a0db1eaa1d590ee67f96ee2118af4e5b7">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createMemoryEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#aa209c1bf2741fdb9c4f7faf9428004cb">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::DI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917ad4051c16e1d2336250f8e267c1e03281">llvm::Dependence::DVEntry::EQ</a>, <a href="#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::Graph</a>, <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917a03e1c9598683e23868735e72b8caaabd">llvm::Dependence::DVEntry::GT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917a5796b2f4edcf01eb52e88d01493f1d58">llvm::Dependence::DVEntry::LT</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

### createPiBlocks() {#afba90b653098f15528a273ced632683a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::createPiBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply graph abstraction to groups of nodes that belong to a strongly connected component of the graph to create larger compound nodes called pi-blocks.</p>


<p>The purpose of this abstraction is to isolate sets of program elements that need to stay together during codegen and turn the dependence graph into an acyclic graph.</p>


<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a0efe68c840fb839433af923abcf4f98a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::shouldCreatePiBlocks</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

### populate() {#aa6cc092387721c9933bb8ec763767c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate ()</td>
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

<p>The main entry to the graph construction algorithm.</p>


<p>It starts by creating nodes in increasing order of granularity and then adds def-use and memory edges. As one of the final stages, it also creates pi-block nodes to facilitate codegen in transformations that use dependence graphs.</p>


<p>The algorithmic complexity of this implementation is O(V^2 * I^2), where V is the number of vertecies (nodes) and I is the number of instructions in each node. The total number of instructions, N, is equal to V * I, therefore the worst-case time complexity is O(N^2). The average time complexity is O((N^2)/2).</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>References <a href="#a022f8d18fe9e9e880c51db47e2f372db">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::computeInstructionOrdinals</a>, <a href="#a008891a00a9aec8710d95ec82fd72196">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createAndConnectRootNode</a>, <a href="#ac76acbd497d18c7306f8120c6f11fb51">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createDefUseEdges</a>, <a href="#a56732d193d3946d953c77a80e07ef61a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNodes</a>, <a href="#a9c4196edca24d644ff96e55945abd207">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createMemoryDependencyEdges</a>, <a href="#afba90b653098f15528a273ced632683a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createPiBlocks</a>, <a href="#aa58986a6df89ded5c86fc981ad2bf53c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::simplify</a> and <a href="#a2ca7af382aa1a34576aee355f364447c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::sortNodesTopologically</a>.</p>

</div>
</div>

### simplify() {#aa58986a6df89ded5c86fc981ad2bf53c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::simplify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go through all the nodes in the graph and collapse any two nodes 'a' and 'b' if all of the following are true:</p>


<ul class="doxyList ">
<li>the only edge from 'a' is a def-use edge to 'b' and</li>
<li>the only edge to 'b' is a def-use edge from 'a' and</li>
<li>there is no cyclic edge from 'b' to 'a' and</li>
<li>all instructions in 'a' and 'b' belong to the same basic block and</li>
<li>both 'a' and 'b' are simple (single or multi instruction) nodes.</li>
</ul>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>References <a href="#af4e8f893add52ec0fef867263cf6982f">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::areNodesMergeable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::Graph</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa203d4dd4a4b21ce9f1769684ead617a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::mergeNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a16d76d7fa8623d797dc380af58f7c22e">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::shouldSimplify</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

### sortNodesTopologically() {#a2ca7af382aa1a34576aee355f364447c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractDependenceGraphBuilder::sortNodesTopologically ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Topologically sort the graph nodes.</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>, definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05e33cd36780875465c50c22d1a85ddd">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getNodesInPiBlock</a>, <a href="#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::Graph</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41c4916e8090ce40598db1a8dd2a5d5d">llvm::post_order</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="#a0efe68c840fb839433af923abcf4f98a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::shouldCreatePiBlocks</a>.</p>


<p>Referenced by <a href="#aa6cc092387721c9933bb8ec763767c3d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::populate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### areNodesMergeable() {#af4e8f893add52ec0fef867263cf6982f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::areNodesMergeable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp; B)</td>
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

<p>Return true if it's safe to merge the two nodes.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="#aa58986a6df89ded5c86fc981ad2bf53c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::simplify</a>.</p>

</div>
</div>

### createDefUseEdge() {#a8745968d747fee2b8c98819422bd172e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual EdgeType &amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createDefUseEdge (NodeType &amp; Src, NodeType &amp; Tgt)</td>
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

<p>Create a def-use edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#ac76acbd497d18c7306f8120c6f11fb51">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createDefUseEdges</a>.</p>

</div>
</div>

### createFineGrainedNode() {#a49a5519e92004994b7d31bdded9fa0d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual NodeType &amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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

<p>Create an atomic node in the graph given a single instruction.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a56732d193d3946d953c77a80e07ef61a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNodes</a>.</p>

</div>
</div>

### createMemoryEdge() {#a0db1eaa1d590ee67f96ee2118af4e5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual EdgeType &amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createMemoryEdge (NodeType &amp; Src, NodeType &amp; Tgt)</td>
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

<p>Create a memory dependence edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a9c4196edca24d644ff96e55945abd207">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createMemoryDependencyEdges</a>.</p>

</div>
</div>

### createPiBlock() {#a692ad63098f0ae1d0a7e87cee6dedd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual NodeType &amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createPiBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ac6158af6f5ec713149c0547d07d6cabe">NodeListType</a> &amp; L)</td>
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

<p>Create a pi-block node in the graph representing a group of nodes in an SCC of the graph.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### createRootedEdge() {#a550d05205fe4e217c45862cd0455386e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual EdgeType &amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createRootedEdge (NodeType &amp; Src, NodeType &amp; Tgt)</td>
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

<p>Create a rooted edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span> .</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### createRootNode() {#a6d0ad7c2f9c9bd805cf19a4b8936e6ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual NodeType &amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createRootNode ()</td>
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

<p>Create the root node of the graph.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>

</div>
</div>

### destroyEdge() {#a0d2445b044da844555d1f25db33979ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::destroyEdge (EdgeType &amp; E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocate memory of edge <span class="doxyComputerOutput">E</span>.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>

</div>
</div>

### destroyNode() {#ab95e08bc6b6b4d0e95caada63521ad6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::destroyNode (NodeType &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocate memory of node <span class="doxyComputerOutput">N</span>.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getNodesInPiBlock() {#a05e33cd36780875465c50c22d1a85ddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const NodeListType &amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getNodesInPiBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeType &amp; N)</td>
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

<p>Given a pi-block node, return a vector of all the nodes contained within it.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a2ca7af382aa1a34576aee355f364447c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::sortNodesTopologically</a>.</p>

</div>
</div>

### getOrdinal() {#ac47f2ea1faaea3efe3e33337c0738c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getOrdinal (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an instruction <span class="doxyComputerOutput">I</span> return its associated ordinal number.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a76b252b935930d919653b4b647c06fed">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::InstOrdinalMap</a>.</p>


<p>Referenced by <a href="#a56732d193d3946d953c77a80e07ef61a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNodes</a>.</p>

</div>
</div>

### getOrdinal() {#ac987bb4640feeb3e68c416f1bba3d8e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getOrdinal (NodeType &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a node <span class="doxyComputerOutput">N</span> return its associated ordinal number.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ace3dba236f7832e89050397843bc5deb">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::NodeOrdinalMap</a>.</p>

</div>
</div>

### mergeNodes() {#aa203d4dd4a4b21ce9f1769684ead617a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::mergeNodes (NodeType &amp; A, NodeType &amp; B)</td>
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

<p>Append the content of node <span class="doxyComputerOutput">B</span> into node <span class="doxyComputerOutput">A</span> and remove <span class="doxyComputerOutput">B</span> and the edge between <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> from the graph.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="#aa58986a6df89ded5c86fc981ad2bf53c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::simplify</a>.</p>

</div>
</div>

### shouldCreatePiBlocks() {#a0efe68c840fb839433af923abcf4f98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::shouldCreatePiBlocks ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if creation of pi-blocks are supported and desired, and false otherwise.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#afba90b653098f15528a273ced632683a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createPiBlocks</a> and <a href="#a2ca7af382aa1a34576aee355f364447c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::sortNodesTopologically</a>.</p>

</div>
</div>

### shouldSimplify() {#a16d76d7fa8623d797dc380af58f7c22e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::shouldSimplify ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if graph simplification step is requested, and false otherwise.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#aa58986a6df89ded5c86fc981ad2bf53c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::simplify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BBList {#aaa3998e38833526aca81deca3aa8bef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlockListType&amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::BBList</td>
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

<p>The list of basic blocks to consider when building the graph.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a7b91f6ee87fdd6c6992b19918a51a8fc">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::AbstractDependenceGraphBuilder</a>, <a href="#a022f8d18fe9e9e880c51db47e2f372db">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::computeInstructionOrdinals</a> and <a href="#a56732d193d3946d953c77a80e07ef61a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNodes</a>.</p>

</div>
</div>

### DI {#aa209c1bf2741fdb9c4f7faf9428004cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependenceInfo&amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::DI</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> information used to create memory dependence edges in the graph.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a7b91f6ee87fdd6c6992b19918a51a8fc">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::AbstractDependenceGraphBuilder</a> and <a href="#a9c4196edca24d644ff96e55945abd207">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createMemoryDependencyEdges</a>.</p>

</div>
</div>

### Graph {#adfe1af074dc71e900744bf6e4fbe3356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GraphType&amp; llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::Graph</td>
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

<p>Reference to the graph that gets built by a concrete implementation of this builder.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a7b91f6ee87fdd6c6992b19918a51a8fc">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::AbstractDependenceGraphBuilder</a>, <a href="#ac76acbd497d18c7306f8120c6f11fb51">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createDefUseEdges</a>, <a href="#a9c4196edca24d644ff96e55945abd207">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createMemoryDependencyEdges</a>, <a href="#aa58986a6df89ded5c86fc981ad2bf53c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::simplify</a> and <a href="#a2ca7af382aa1a34576aee355f364447c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::sortNodesTopologically</a>.</p>

</div>
</div>

### IMap {#aaba43f6de0784dea46cb0cab896cb63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstToNodeMap llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::IMap</td>
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

<p>A mapping from instructions to the corresponding nodes in the graph.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#ac76acbd497d18c7306f8120c6f11fb51">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createDefUseEdges</a> and <a href="#a56732d193d3946d953c77a80e07ef61a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNodes</a>.</p>

</div>
</div>

### InstOrdinalMap {#a76b252b935930d919653b4b647c06fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstToOrdinalMap llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::InstOrdinalMap</td>
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

<p>A mapping from each instruction to an ordinal number.</p>


<p>This map is used to populate the <span class="doxyComputerOutput">NodeOrdinalMap</span>.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a022f8d18fe9e9e880c51db47e2f372db">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::computeInstructionOrdinals</a> and <a href="#ac47f2ea1faaea3efe3e33337c0738c2f">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getOrdinal</a>.</p>

</div>
</div>

### NodeOrdinalMap {#ace3dba236f7832e89050397843bc5deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class GraphType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeToOrdinalMap llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::NodeOrdinalMap</td>
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

<p>A mapping from nodes to an ordinal number.</p>


<p>This map is used to sort nodes in a pi-block based on program order.</p>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a56732d193d3946d953c77a80e07ef61a">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createFineGrainedNodes</a> and <a href="#ac987bb4640feeb3e68c416f1bba3d8e3">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getOrdinal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependencegraphbuilder-h">DependenceGraphBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/dependencegraphbuilder-cpp">DependenceGraphBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
