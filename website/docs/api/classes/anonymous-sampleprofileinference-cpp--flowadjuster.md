---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sampleprofileinference-cpp-/flowadjuster
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FlowAdjuster` Class Reference

<p>A post-processing adjustment of the control flow. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SampleProfileInference.cpp}::FlowAdjuster { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04ad58c6ccb8efe2be143e1bf61dd3c">FlowAdjuster</a> (const ProfiParams &amp;Params, FlowFunction &amp;Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8a2f7647fe57cd4d7e265585c4806e">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the post-processing. <a href="#aea8a2f7647fe57cd4d7e265585c4806e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5a87760e40c8c87b1f6885778e9dd8">joinIsolatedComponents</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09efba6c4c63a662771f8e8793c8fbb0">findReachable</a> (uint64_t Src, BitVector &amp;Visited)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run BFS from a given block along the jumps with a positive flow and mark all reachable blocks. <a href="#a09efba6c4c63a662771f8e8793c8fbb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowjump">FlowJump</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7821f8a10d57bc91cb1958d1b48cbcdb">findShortestPath</a> (uint64_t BlockIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the shortest path from the entry block to an exit block passing through a given block. <a href="#a7821f8a10d57bc91cb1958d1b48cbcdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowjump">FlowJump</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dfd969153f2665c12707fd5f3a2e335">findShortestPath</a> (uint64_t Source, uint64_t Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the Dijkstra algorithm to find the shortest path from a given Source to a given <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> block. <a href="#a9dfd969153f2665c12707fd5f3a2e335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046c87b91022769fa8fd1256e4062b21">jumpDistance</a> (FlowJump *Jump) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A distance of a path for a given jump. <a href="#a046c87b91022769fa8fd1256e4062b21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b67a09bd75d5f077dc2b100f17d7c41">NumBlocks</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c34d6fe6945150c4d7d0fdb1a4f39d">rebalanceUnknownSubgraphs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rebalance unknown subgraphs so that the flow is split evenly across the outgoing branches of every block of the subgraph. <a href="#a35c34d6fe6945150c4d7d0fdb1a4f39d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af7f9d8e6d4993f551e48c19f1a9955">canRebalanceAtRoot</a> (const FlowBlock *SrcBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if rebalancing rooted at a given block is possible. <a href="#a6af7f9d8e6d4993f551e48c19f1a9955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257b63aad7f99156ddcb630dbd834594">findUnknownSubgraph</a> (const FlowBlock *SrcBlock, std::vector&lt; FlowBlock * &gt; &amp;KnownDstBlocks, std::vector&lt; FlowBlock * &gt; &amp;UnknownBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find an unknown subgraph starting at block SrcBlock. <a href="#a257b63aad7f99156ddcb630dbd834594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60be1e5c861157c00eea96d24dce9057">canRebalanceSubgraph</a> (const FlowBlock *SrcBlock, const std::vector&lt; FlowBlock * &gt; &amp;KnownDstBlocks, const std::vector&lt; FlowBlock * &gt; &amp;UnknownBlocks, FlowBlock *&amp;DstBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if rebalancing of the subgraph is feasible. <a href="#a60be1e5c861157c00eea96d24dce9057">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79cceb462357992730ee0a0bc717ccc0">ignoreJump</a> (const FlowBlock *SrcBlock, const FlowBlock *DstBlock, const FlowJump *Jump)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decide whether the Jump is ignored while processing an unknown subgraphs rooted at basic block SrcBlock with the destination block, DstBlock. <a href="#a79cceb462357992730ee0a0bc717ccc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1379218f994037ee122b59e8c0b76ae">isAcyclicSubgraph</a> (const FlowBlock *SrcBlock, const FlowBlock *DstBlock, std::vector&lt; FlowBlock * &gt; &amp;UnknownBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if the given unknown subgraph is acyclic, and if yes, reorder UnknownBlocks in the topological order (so that all jumps are "forward"). <a href="#af1379218f994037ee122b59e8c0b76ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a333769a6f8a70e4369c7178a6e45efe1">rebalanceUnknownSubgraph</a> (const FlowBlock *SrcBlock, const FlowBlock *DstBlock, const std::vector&lt; FlowBlock * &gt; &amp;UnknownBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rebalance a given subgraph rooted at SrcBlock, ending at DstBlock and having UnknownBlocks intermediate blocks. <a href="#a333769a6f8a70e4369c7178a6e45efe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484db023b05eaee3c86ea96ce0bbfb87">rebalanceBlock</a> (const FlowBlock *SrcBlock, const FlowBlock *DstBlock, const FlowBlock *Block, uint64_t BlockFlow)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Redistribute flow for a block in a subgraph rooted at SrcBlock, and ending at DstBlock. <a href="#a484db023b05eaee3c86ea96ce0bbfb87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d39f91cdd1d976a4b5843b5aa3caae4">Params</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Params for flow computation. <a href="#a0d39f91cdd1d976a4b5843b5aa3caae4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/flowfunction">FlowFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6823cb871f4430b22fcdcd52aeda47">Func</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function. <a href="#a9f6823cb871f4430b22fcdcd52aeda47">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4485f64d2aae44204ed36457eec0a10">AnyExitBlock</a> = uint64_t(-1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A constant indicating an arbitrary exit block of a function. <a href="#ad4485f64d2aae44204ed36457eec0a10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f5da7fc22ec9e9a2801b3de37bc9bd">MinBaseDistance</a> = 10000</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Minimum BaseDistance for the jump distance values in island joining. <a href="#ad0f5da7fc22ec9e9a2801b3de37bc9bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A post-processing adjustment of the control flow.</p>


<p>It applies two steps by rerouting some flow and making it more realistic:</p>


<ul class="doxyList ">
<li>First, it removes all isolated components ("islands") with a positive flow that are unreachable from the entry block. For every such component, we find the shortest from the entry to an exit passing through the component, and increase the flow by one unit along the path.</li>
<li>Second, it identifies all "unknown subgraphs" consisting of basic blocks with no sampled counts. Then it rebalnces the flow that goes through such a subgraph so that each branch is taken with probability 50%. An unknown subgraph is such that for every two nodes u and v:

<ul class="doxyList ">
<li>u dominates v and u is not unknown;</li>
<li>v post-dominates u; and</li>
<li>all inner-nodes of all (u,v)-paths are unknown.</li>
</ul></li>
</ul>

<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FlowAdjuster() {#ad04ad58c6ccb8efe2be143e1bf61dd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SampleProfileInference.cpp}::FlowAdjuster::FlowAdjuster (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp; Params, <a href="/web-llvm/docs/api/structs/llvm/flowfunction">FlowFunction</a> &amp; Func)</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#aea8a2f7647fe57cd4d7e265585c4806e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::FlowAdjuster::run ()</td>
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

<p>Apply the post-processing.</p>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canRebalanceAtRoot() {#a6af7f9d8e6d4993f551e48c19f1a9955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::FlowAdjuster::canRebalanceAtRoot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * SrcBlock)</td>
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

<p>Verify if rebalancing rooted at a given block is possible.</p>

<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### canRebalanceSubgraph() {#a60be1e5c861157c00eea96d24dce9057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::FlowAdjuster::canRebalanceSubgraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * SrcBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * &gt; &amp; KnownDstBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * &gt; &amp; UnknownBlocks, <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> *&amp; DstBlock)</td>
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

<p>Verify if rebalancing of the subgraph is feasible.</p>


<p>If the checks are successful, set the unique destination block, DstBlock (can be null).</p>


<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### findReachable() {#a09efba6c4c63a662771f8e8793c8fbb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::FlowAdjuster::findReachable (uint64_t Src, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; Visited)</td>
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

<p>Run BFS from a given block along the jumps with a positive flow and mark all reachable blocks.</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### findShortestPath() {#a7821f8a10d57bc91cb1958d1b48cbcdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; FlowJump * &gt; anonymous{SampleProfileInference.cpp}::FlowAdjuster::findShortestPath (uint64_t BlockIdx)</td>
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

<p>Find the shortest path from the entry block to an exit block passing through a given block.</p>

<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### findShortestPath() {#a9dfd969153f2665c12707fd5f3a2e335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; FlowJump * &gt; anonymous{SampleProfileInference.cpp}::FlowAdjuster::findShortestPath (uint64_t Source, uint64_t Target)</td>
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

<p>Apply the Dijkstra algorithm to find the shortest path from a given Source to a given <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> block.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> == -1, then the path ends at an exit block.</p>


<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### findUnknownSubgraph() {#a257b63aad7f99156ddcb630dbd834594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::FlowAdjuster::findUnknownSubgraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * SrcBlock, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * &gt; &amp; KnownDstBlocks, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * &gt; &amp; UnknownBlocks)</td>
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

<p>Find an unknown subgraph starting at block SrcBlock.</p>


<p>The method sets identified destinations, KnownDstBlocks, and intermediate UnknownBlocks.</p>


<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### ignoreJump() {#a79cceb462357992730ee0a0bc717ccc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::FlowAdjuster::ignoreJump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * SrcBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * DstBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowjump">FlowJump</a> * Jump)</td>
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

<p>Decide whether the Jump is ignored while processing an unknown subgraphs rooted at basic block SrcBlock with the destination block, DstBlock.</p>

<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### isAcyclicSubgraph() {#af1379218f994037ee122b59e8c0b76ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::FlowAdjuster::isAcyclicSubgraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * SrcBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * DstBlock, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * &gt; &amp; UnknownBlocks)</td>
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

<p>Verify if the given unknown subgraph is acyclic, and if yes, reorder UnknownBlocks in the topological order (so that all jumps are "forward").</p>

<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### joinIsolatedComponents() {#a8a5a87760e40c8c87b1f6885778e9dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::FlowAdjuster::joinIsolatedComponents ()</td>
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



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### jumpDistance() {#a046c87b91022769fa8fd1256e4062b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::FlowAdjuster::jumpDistance (<a href="/web-llvm/docs/api/structs/llvm/flowjump">FlowJump</a> * Jump)</td>
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

<p>A distance of a path for a given jump.</p>


<p>In order to incite the path to use blocks/jumps with large positive flow, and avoid changing branch probability of outgoing edges drastically, set the jump distance so as:</p>


<ul class="doxyList ">
<li>to minimize the number of unlikely jumps used and subject to that,</li>
<li>to minimize the number of Flow == 0 jumps used and subject to that,</li>
<li>minimizes total multiplicative Flow increase for the remaining edges. To capture this objective with integer distances, we round off fractional parts to a multiple of 1 / BaseDistance.</li>
</ul>

<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### NumBlocks() {#a6b67a09bd75d5f077dc2b100f17d7c41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::FlowAdjuster::NumBlocks ()</td>
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



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### rebalanceBlock() {#a484db023b05eaee3c86ea96ce0bbfb87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::FlowAdjuster::rebalanceBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * SrcBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * DstBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * Block, uint64_t BlockFlow)</td>
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

<p>Redistribute flow for a block in a subgraph rooted at SrcBlock, and ending at DstBlock.</p>

<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### rebalanceUnknownSubgraph() {#a333769a6f8a70e4369c7178a6e45efe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::FlowAdjuster::rebalanceUnknownSubgraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * SrcBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * DstBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> * &gt; &amp; UnknownBlocks)</td>
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

<p>Rebalance a given subgraph rooted at SrcBlock, ending at DstBlock and having UnknownBlocks intermediate blocks.</p>

<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### rebalanceUnknownSubgraphs() {#a35c34d6fe6945150c4d7d0fdb1a4f39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::FlowAdjuster::rebalanceUnknownSubgraphs ()</td>
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

<p>Rebalance unknown subgraphs so that the flow is split evenly across the outgoing branches of every block of the subgraph.</p>


<p>The method iterates over blocks with known weight and identifies unknown subgraphs rooted at the blocks. Then it verifies if flow rebalancing is feasible and applies it.</p>


<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Func {#a9f6823cb871f4430b22fcdcd52aeda47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FlowFunction&amp; anonymous{SampleProfileInference.cpp}::FlowAdjuster::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function.</p>

<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Params {#a0d39f91cdd1d976a4b5843b5aa3caae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProfiParams&amp; anonymous{SampleProfileInference.cpp}::FlowAdjuster::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Params for flow computation.</p>

<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AnyExitBlock {#ad4485f64d2aae44204ed36457eec0a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::FlowAdjuster::AnyExitBlock = uint64_t(-1)</td>
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

<p>A constant indicating an arbitrary exit block of a function.</p>

<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### MinBaseDistance {#ad0f5da7fc22ec9e9a2801b3de37bc9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::FlowAdjuster::MinBaseDistance = 10000</td>
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

<p>Minimum BaseDistance for the jump distance values in island joining.</p>

<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
