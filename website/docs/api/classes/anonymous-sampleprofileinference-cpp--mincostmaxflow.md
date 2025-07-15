---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MinCostMaxFlow` Class Reference

<p>The minimum-cost maximum flow algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SampleProfileInference.cpp}::MinCostMaxFlow { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246fc8776a1383f88a74fad1a98450fb">MinCostMaxFlow</a> (const ProfiParams &amp;Params)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf43214acfd3c95a6e28d1db4989d91">initialize</a> (uint64_t NodeCount, uint64_t SourceNode, uint64_t SinkNode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523a13976e6717de53ffbcc67d521617">run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2945517bec92f190ee791baa19050289">addEdge</a> (uint64_t Src, uint64_t Dst, int64_t Capacity, int64_t Cost)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adding an edge to the network with a specified capacity and a cost. <a href="#a2945517bec92f190ee791baa19050289">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5911bffb6d89dea9124aec1644932c4">addEdge</a> (uint64_t Src, uint64_t Dst, int64_t Cost)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adding an edge to the network of infinite capacity and a given cost. <a href="#af5911bffb6d89dea9124aec1644932c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; uint64_t, int64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1fc02088c9f278b02f219d2d64c82c">getFlow</a> (uint64_t Src) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total flow from a given source node. <a href="#aca1fc02088c9f278b02f219d2d64c82c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa7a29ff74835aa8da3d59e395d95b4">getFlow</a> (uint64_t Src, uint64_t Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total flow between a pair of nodes. <a href="#afaa7a29ff74835aa8da3d59e395d95b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef68dd52f08322a962433107eed100cc">applyFlowAugmentation</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteratively find an augmentation path/dag in the network and send the flow along its edges. <a href="#aef68dd52f08322a962433107eed100cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2748a9a1ed369983795fd6fc282cae2b">computeAugmentingPathCapacity</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the capacity of the cannonical augmenting path. <a href="#a2748a9a1ed369983795fd6fc282cae2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9a928e195e4be90457dd2a17f0533b">findAugmentingPath</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check for existence of an augmenting path with a positive capacity. <a href="#a3f9a928e195e4be90457dd2a17f0533b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2468f5bb186703fa1943a17a6e461a57">augmentFlowAlongPath</a> (uint64_t PathCapacity)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the current flow along the augmenting path. <a href="#a2468f5bb186703fa1943a17a6e461a57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad76f42ee447785f2436b9ded0f0c3a0">findAugmentingDAG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find an Augmenting DAG order using a modified version of DFS in which we can visit a node multiple times. <a href="#aad76f42ee447785f2436b9ded0f0c3a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5387d7de7e63ccb89f482b119fb52222">augmentFlowAlongDAG</a> (const std::vector&lt; uint64_t &gt; &amp;AugmentingOrder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the current flow along the given (acyclic) subgraph specified by the vertex order, AugmentingOrder. <a href="#a5387d7de7e63ccb89f482b119fb52222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0605d36ceacd9ef0d53748fb28e476">identifyShortestEdges</a> (uint64_t PathCapacity)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify candidate (shortest) edges for augmentation. <a href="#a9b0605d36ceacd9ef0d53748fb28e476">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/node">Node</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e69159b112b786357c8f8048cfabf52">Nodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of network nodes. <a href="#a2e69159b112b786357c8f8048cfabf52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; Edge &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b848fbac978603aa1b213ddc8410b89">Edges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of network edges. <a href="#a7b848fbac978603aa1b213ddc8410b89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c950ca6d118d64d1e4a7111fc9ec739">Source</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source node of the flow. <a href="#a6c950ca6d118d64d1e4a7111fc9ec739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9279a125a3ea836cc82b68b32043a8e">Target</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target (sink) node of the flow. <a href="#ac9279a125a3ea836cc82b68b32043a8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; Edge * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9219671395e0dcaa3493286d7637b01a">AugmentingEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Augmenting edges. <a href="#a9219671395e0dcaa3493286d7637b01a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b7d438ce3d47bc39798813e7ef4d56">Params</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Params for flow computation. <a href="#a57b7d438ce3d47bc39798813e7ef4d56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae226adc746dc6caf9d94121f567c91ae">MaxDfsCalls</a> = 10</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum number of DFS iterations for DAG finding. <a href="#ae226adc746dc6caf9d94121f567c91ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The minimum-cost maximum flow algorithm.</p>


<p>The algorithm finds the maximum flow of minimum cost on a given (directed) network using a modified version of the classical Moore-Bellman-Ford approach. The algorithm applies a number of augmentation iterations in which flow is sent along paths of positive capacity from the source to the sink. The worst-case time complexity of the implementation is O(v(f)*m*n), where where m is the number of edges, n is the number of vertices, and v(f) is the value of the maximum flow. However, the observed running time on typical instances is sub-quadratic, that is, o(n^2).</p>


<p>The input is a set of edges with specified costs and capacities, and a pair of nodes (source and sink). The output is the flow along each edge of the minimum total cost respecting the given edge capacities.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MinCostMaxFlow() {#a246fc8776a1383f88a74fad1a98450fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::MinCostMaxFlow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp; Params)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEdge() {#a2945517bec92f190ee791baa19050289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::addEdge (uint64_t Src, uint64_t Dst, int64_t Capacity, int64_t Cost)</td>
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

<p>Adding an edge to the network with a specified capacity and a cost.</p>


<p>Multiple edges between a pair of nodes are allowed but self-edges are not supported.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">anonymous{SampleProfileInference.cpp}::initializeNetwork</a>.</p>

</div>
</div>

### addEdge() {#af5911bffb6d89dea9124aec1644932c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::addEdge (uint64_t Src, uint64_t Dst, int64_t Cost)</td>
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

<p>Adding an edge to the network of infinite capacity and a given cost.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#aec802e48dd5ef69029e285eddfc4158d">addEdge</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a001dbf74fedb2ab9b6f541f6943dea14">anonymous{SampleProfileInference.cpp}::INF</a>.</p>

</div>
</div>

### getFlow() {#aca1fc02088c9f278b02f219d2d64c82c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::pair&lt; uint64_t, int64_t &gt; &gt; anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::getFlow (uint64_t Src)</td>
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

<p>Get the total flow from a given source node.</p>


<p>Returns a list of pairs (target node, amount of flow to the target).</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siannotatecontrolflow-cpp/#acf797fa91d5b7065dfb68a2492df28c1">Flow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ae9165b166eac58ea95367c58bf55795e">anonymous{SampleProfileInference.cpp}::extractWeights</a>.</p>

</div>
</div>

### getFlow() {#afaa7a29ff74835aa8da3d59e395d95b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::getFlow (uint64_t Src, uint64_t Dst)</td>
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

<p>Get the total flow between a pair of nodes.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siannotatecontrolflow-cpp/#acf797fa91d5b7065dfb68a2492df28c1">Flow</a>.</p>

</div>
</div>

### initialize() {#acbf43214acfd3c95a6e28d1db4989d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::initialize (uint64_t NodeCount, uint64_t SourceNode, uint64_t SinkNode)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">anonymous{SampleProfileInference.cpp}::initializeNetwork</a>.</p>

</div>
</div>

### run() {#a523a13976e6717de53ffbcc67d521617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::run ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyFlowAugmentation() {#aef68dd52f08322a962433107eed100cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::applyFlowAugmentation ()</td>
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

<p>Iteratively find an augmentation path/dag in the network and send the flow along its edges.</p>


<p>The method returns the number of applied iterations.</p>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### augmentFlowAlongDAG() {#a5387d7de7e63ccb89f482b119fb52222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::augmentFlowAlongDAG (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; uint64_t &gt; &amp; AugmentingOrder)</td>
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

<p>Update the current flow along the given (acyclic) subgraph specified by the vertex order, AugmentingOrder.</p>


<p>The objective is to send as much flow as possible while evenly distributing flow among successors of each node. After the update at least one edge is saturated.</p>


<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### augmentFlowAlongPath() {#a2468f5bb186703fa1943a17a6e461a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::augmentFlowAlongPath (uint64_t PathCapacity)</td>
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

<p>Update the current flow along the augmenting path.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### computeAugmentingPathCapacity() {#a2748a9a1ed369983795fd6fc282cae2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::computeAugmentingPathCapacity ()</td>
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

<p>Compute the capacity of the cannonical augmenting path.</p>


<p>If the path is saturated (that is, no flow can be sent along the path), then return 0.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### findAugmentingDAG() {#aad76f42ee447785f2436b9ded0f0c3a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::findAugmentingDAG ()</td>
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

<p>Find an Augmenting DAG order using a modified version of DFS in which we can visit a node multiple times.</p>


<p>In the DFS search, when scanning each edge out of a node, continue search at <a href="/web-llvm/docs/api/structs/anonymous-modulesummaryindex-cpp-/edge/#aaae441e39be0d08f5cddcfbc180ec105">Edge.Dst</a> endpoint if it has not been discovered yet and its NumCalls &lt; MaxDfsCalls. The algorithm runs in O(MaxDfsCalls * |Edges| + |Nodes|) time. It returns an Augmenting Order (Taken nodes in decreasing Finish time) that starts with Source and ends with Target.</p>


<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### findAugmentingPath() {#a3f9a928e195e4be90457dd2a17f0533b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::findAugmentingPath ()</td>
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

<p>Check for existence of an augmenting path with a positive capacity.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### identifyShortestEdges() {#a9b0605d36ceacd9ef0d53748fb28e476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::identifyShortestEdges (uint64_t PathCapacity)</td>
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

<p>Identify candidate (shortest) edges for augmentation.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AugmentingEdges {#a9219671395e0dcaa3493286d7637b01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;Edge *&gt; &gt; anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::AugmentingEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Augmenting edges.</p>

<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Edges {#a7b848fbac978603aa1b213ddc8410b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;Edge&gt; &gt; anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of network edges.</p>

<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Nodes {#a2e69159b112b786357c8f8048cfabf52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Node&gt; anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Nodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of network nodes.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Params {#a57b7d438ce3d47bc39798813e7ef4d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProfiParams&amp; anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Params for flow computation.</p>

<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Source {#a6c950ca6d118d64d1e4a7111fc9ec739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Source</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source node of the flow.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Target {#ac9279a125a3ea836cc82b68b32043a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target (sink) node of the flow.</p>

<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### MaxDfsCalls {#ae226adc746dc6caf9d94121f567c91ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::MaxDfsCalls = 10</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum number of DFS iterations for DAG finding.</p>

<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
