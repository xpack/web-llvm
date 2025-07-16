---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-codelayout-cpp-/exttspimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExtTSPImpl` Class Reference

<p>The implementation of the ExtTSP algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CodeLayout.cpp}::ExtTSPImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47333daefb26df0fb055e84fc9a77d9d">ExtTSPImpl</a> (ArrayRef&lt; uint64_t &gt; NodeSizes, ArrayRef&lt; uint64_t &gt; NodeCounts, ArrayRef&lt; EdgeCount &gt; EdgeCounts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42779621a7ce56ea05e1319893cbc258">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the algorithm and return an optimized ordering of nodes. <a href="#a42779621a7ce56ea05e1319893cbc258">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b0faf53802cc25a83bc10f7bd8339e">initialize</a> (const ArrayRef&lt; uint64_t &gt; &amp;NodeSizes, const ArrayRef&lt; uint64_t &gt; &amp;NodeCounts, const ArrayRef&lt; EdgeCount &gt; &amp;EdgeCounts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the algorithm's data structures. <a href="#a25b0faf53802cc25a83bc10f7bd8339e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17d718c016c7d338795ab0bffcf4886">mergeForcedPairs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a pair of nodes, A and B, node B is the forced successor of A, if (i) all jumps (based on profile) from A goes to B and (ii) all jumps to B are from A. <a href="#ac17d718c016c7d338795ab0bffcf4886">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6a186e2d6925edeb2d5dde5fd9c585">mergeChainPairs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge pairs of chains while improving the ExtTSP objective. <a href="#a6b6a186e2d6925edeb2d5dde5fd9c585">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d24040cd9cd719da45f09aebceefa6d">mergeColdChains</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge remaining nodes into chains w/o taking jump counts into consideration. <a href="#a5d24040cd9cd719da45f09aebceefa6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6061c4406c704103454ec0aa4e8598ed">extTSPScore</a> (const MergedNodesT &amp;Nodes, const MergedJumpsT &amp;Jumps) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the Ext-TSP score for a given node order and a list of jumps. <a href="#a6061c4406c704103454ec0aa4e8598ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergegaint">MergeGainT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7e30925b3775a5aae43e650d47c9d3">getBestMergeGain</a> (ChainT *ChainPred, ChainT *ChainSucc, ChainEdge *Edge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the gain of merging two chains. <a href="#a1d7e30925b3775a5aae43e650d47c9d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergegaint">MergeGainT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad278c8697a28cb55cca2557b2971b8eb">computeMergeGain</a> (const ChainT *ChainPred, const ChainT *ChainSucc, const MergedJumpsT &amp;Jumps, size_t MergeOffset, MergeTypeT MergeType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the score gain of merging two chains, respecting a given merge 'type' and 'offset'. <a href="#ad278c8697a28cb55cca2557b2971b8eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc2d6712f72cb69e9d0fd6d6754f887">mergeChains</a> (ChainT *Into, ChainT *From, size_t MergeOffset, MergeTypeT MergeType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge chain From into chain Into, update the list of active chains, adjacency information, and the corresponding cached values. <a href="#a2dc2d6712f72cb69e9d0fd6d6754f887">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafd4d98c9fd6cf55b223f790e3f4860">concatChains</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concatenate all chains into the final order. <a href="#acafd4d98c9fd6cf55b223f790e3f4860">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc43d2c0e00177b02fef2b86830064c1">NumNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of nodes in the graph. <a href="#acc43d2c0e00177b02fef2b86830064c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a5f14d6754edcc0d1bec1e0e277b9e">SuccNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Successors of each node. <a href="#a64a5f14d6754edcc0d1bec1e0e277b9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd2d2f98d0e4e9b8ce82034fb8793c48">PredNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Predecessors of each node. <a href="#abd2d2f98d0e4e9b8ce82034fb8793c48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9078fd887a8d327a250e0ca51e91462f">AllNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All nodes (basic blocks) in the graph. <a href="#a9078fd887a8d327a250e0ca51e91462f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/jumpt">JumpT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6627521f2d74b94cf2a3b2b8dbe761">AllJumps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All jumps between the nodes. <a href="#aec6627521f2d74b94cf2a3b2b8dbe761">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc948b69a8c68fe4ce7454e934e51223">AllChains</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All chains of nodes. <a href="#acc948b69a8c68fe4ce7454e934e51223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chainedge">ChainEdge</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d75a568171a03abc9eb67653bc60fc">AllEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All edges between the chains. <a href="#ad5d75a568171a03abc9eb67653bc60fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a784433a71dc47d2a7b24f32e5ab76c">HotChains</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Active chains. The vector gets updated at runtime when chains are merged. <a href="#a3a784433a71dc47d2a7b24f32e5ab76c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The implementation of the ExtTSP algorithm.</p>

<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExtTSPImpl() {#a47333daefb26df0fb055e84fc9a77d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeLayout.cpp}::ExtTSPImpl::ExtTSPImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeSizes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; EdgeCounts)</td>
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



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#ab265fb35ca9607f01d99dae7a386ef77">llvm::codelayout::computeExtTspLayout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a42779621a7ce56ea05e1319893cbc258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::run ()</td>
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

<p>Run the algorithm and return an optimized ordering of nodes.</p>

<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeMergeGain() {#ad278c8697a28cb55cca2557b2971b8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeGainT anonymous{CodeLayout.cpp}::ExtTSPImpl::computeMergeGain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainPred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainSucc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergedjumpst">MergedJumpsT</a> &amp; Jumps, size_t MergeOffset, <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#a891fbaa9000c6c378ce647324830b0e6">MergeTypeT</a> MergeType)</td>
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

<p>Compute the score gain of merging two chains, respecting a given merge 'type' and 'offset'.</p>


<p>The two chains are not modified in the method.</p>


<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### concatChains() {#acafd4d98c9fd6cf55b223f790e3f4860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::concatChains ()</td>
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

<p>Concatenate all chains into the final order.</p>

<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### extTSPScore() {#a6061c4406c704103454ec0aa4e8598ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{CodeLayout.cpp}::ExtTSPImpl::extTSPScore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergednodest">MergedNodesT</a> &amp; Nodes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergedjumpst">MergedJumpsT</a> &amp; Jumps)</td>
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

<p>Compute the Ext-TSP score for a given node order and a list of jumps.</p>

<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### getBestMergeGain() {#a1d7e30925b3775a5aae43e650d47c9d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeGainT anonymous{CodeLayout.cpp}::ExtTSPImpl::getBestMergeGain (<a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainPred, <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainSucc, <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chainedge">ChainEdge</a> * Edge)</td>
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

<p>Compute the gain of merging two chains.</p>


<p>The function considers all possible ways of merging two chains and computes the one having the largest increase in ExtTSP objective. The result is a pair with the first element being the gain and the second element being the corresponding merging type.</p>


<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### initialize() {#a25b0faf53802cc25a83bc10f7bd8339e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::ExtTSPImpl::initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; &amp; NodeSizes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; &amp; NodeCounts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; &amp; EdgeCounts)</td>
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

<p>Initialize the algorithm's data structures.</p>

<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### mergeChainPairs() {#a6b6a186e2d6925edeb2d5dde5fd9c585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::ExtTSPImpl::mergeChainPairs ()</td>
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

<p>Merge pairs of chains while improving the ExtTSP objective.</p>

<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### mergeChains() {#a2dc2d6712f72cb69e9d0fd6d6754f887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::ExtTSPImpl::mergeChains (<a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * Into, <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * From, size_t MergeOffset, <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#a891fbaa9000c6c378ce647324830b0e6">MergeTypeT</a> MergeType)</td>
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

<p>Merge chain From into chain Into, update the list of active chains, adjacency information, and the corresponding cached values.</p>

<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### mergeColdChains() {#a5d24040cd9cd719da45f09aebceefa6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::ExtTSPImpl::mergeColdChains ()</td>
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

<p>Merge remaining nodes into chains w/o taking jump counts into consideration.</p>


<p>This allows to maintain the original node order in the absence of profile data.</p>


<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### mergeForcedPairs() {#ac17d718c016c7d338795ab0bffcf4886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::ExtTSPImpl::mergeForcedPairs ()</td>
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

<p>For a pair of nodes, A and B, node B is the forced successor of A, if (i) all jumps (based on profile) from A goes to B and (ii) all jumps to B are from A.</p>


<p>Such nodes should be adjacent in the optimal ordering; the method finds and merges such pairs of nodes.</p>


<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllChains {#acc948b69a8c68fe4ce7454e934e51223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChainT&gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::AllChains</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All chains of nodes.</p>

<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### AllEdges {#ad5d75a568171a03abc9eb67653bc60fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChainEdge&gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::AllEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All edges between the chains.</p>

<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### AllJumps {#aec6627521f2d74b94cf2a3b2b8dbe761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;JumpT&gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::AllJumps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All jumps between the nodes.</p>

<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### AllNodes {#a9078fd887a8d327a250e0ca51e91462f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;NodeT&gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::AllNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All nodes (basic blocks) in the graph.</p>

<p>Definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### HotChains {#a3a784433a71dc47d2a7b24f32e5ab76c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChainT *&gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::HotChains</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Active chains. The vector gets updated at runtime when chains are merged.</p>

<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### NumNodes {#acc43d2c0e00177b02fef2b86830064c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t anonymous{CodeLayout.cpp}::ExtTSPImpl::NumNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of nodes in the graph.</p>

<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### PredNodes {#abd2d2f98d0e4e9b8ce82034fb8793c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;uint64_t&gt; &gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::PredNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Predecessors of each node.</p>

<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### SuccNodes {#a64a5f14d6754edcc0d1bec1e0e277b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;uint64_t&gt; &gt; anonymous{CodeLayout.cpp}::ExtTSPImpl::SuccNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Successors of each node.</p>

<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
