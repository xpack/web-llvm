---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-codelayout-cpp-/cdsortimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CDSortImpl` Class

<p>The implementation of the Cache-Directed Sort (CDSort) algorithm for ordering functions represented by a call graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CodeLayout.cpp}::CDSortImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a9823d565755fe71d5a54fb0262947">CDSortImpl</a> (const CDSortConfig &amp;Config, ArrayRef&lt; uint64_t &gt; NodeSizes, ArrayRef&lt; uint64_t &gt; NodeCounts, ArrayRef&lt; EdgeCount &gt; EdgeCounts, ArrayRef&lt; uint64_t &gt; EdgeOffsets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562000bf2e945e451f810aac853454ca">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the algorithm and return an ordered set of function clusters. <a href="#a562000bf2e945e451f810aac853454ca">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd1a22e6995272b1766d251eb653ae8">initialize</a> (const ArrayRef&lt; uint64_t &gt; &amp;NodeSizes, const ArrayRef&lt; uint64_t &gt; &amp;NodeCounts, const ArrayRef&lt; EdgeCount &gt; &amp;EdgeCounts, const ArrayRef&lt; uint64_t &gt; &amp;EdgeOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the algorithm's data structures. <a href="#a2dd1a22e6995272b1766d251eb653ae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f74abf2a229a211da405da049065305">mergeChainPairs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge pairs of chains while there is an improvement in the objective. <a href="#a3f74abf2a229a211da405da049065305">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergegaint">MergeGainT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4231b699be14ce7160b86a045c519e">getBestMergeGain</a> (ChainEdge *Edge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the gain of merging two chains. <a href="#a8e4231b699be14ce7160b86a045c519e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergegaint">MergeGainT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10f01169306fd8ff8bd31cb6a5c496c">computeMergeGain</a> (ChainT *ChainPred, ChainT *ChainSucc, const MergedJumpsT &amp;Jumps, MergeTypeT MergeType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the score gain of merging two chains, respecting a given type. <a href="#af10f01169306fd8ff8bd31cb6a5c496c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ccfe4709f9913268b6a42ed1b8c61f">freqBasedLocalityGain</a> (ChainT *ChainPred, ChainT *ChainSucc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the change of the frequency locality after merging the chains. <a href="#a83ccfe4709f9913268b6a42ed1b8c61f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84dfc398189f701b6b9a478a334301c4">distScore</a> (uint64_t SrcAddr, uint64_t DstAddr, uint64_t Count) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the distance locality for a jump / call. <a href="#a84dfc398189f701b6b9a478a334301c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5c5886ca65d5d19ce7e5f83f18ef6b">distBasedLocalityGain</a> (const MergedNodesT &amp;Nodes, const MergedJumpsT &amp;Jumps) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the change of the distance locality after merging the chains. <a href="#a7b5c5886ca65d5d19ce7e5f83f18ef6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbac1a8db10e0f43b9387df38978fa97">mergeChains</a> (ChainT *Into, ChainT *From, size_t MergeOffset, MergeTypeT MergeType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge chain From into chain Into, update the list of active chains, adjacency information, and the corresponding cached values. <a href="#acbac1a8db10e0f43b9387df38978fa97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3278851f51cac767f3255272a4c49dfb">concatChains</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concatenate all chains into the final order. <a href="#a3278851f51cac767f3255272a4c49dfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig">CDSortConfig</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaafffb7a2e6f29e87903d2bc371f58eb">Config</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Config for the algorithm. <a href="#aaafffb7a2e6f29e87903d2bc371f58eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53882b590c1e7790f51822b39fb3809c">NumNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of nodes in the graph. <a href="#a53882b590c1e7790f51822b39fb3809c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b42cd388fe69b477bf5964fe73b8e9c">SuccNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Successors of each node. <a href="#a3b42cd388fe69b477bf5964fe73b8e9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b5ffee5f19ab5054d604cbfd1fc7bf">PredNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Predecessors of each node. <a href="#aa8b5ffee5f19ab5054d604cbfd1fc7bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae707dc7fcf8b45ee57a4f24f63825be7">AllNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All nodes (functions) in the graph. <a href="#ae707dc7fcf8b45ee57a4f24f63825be7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/jumpt">JumpT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494934e26f644797a6f05ae6a4cadd53">AllJumps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All jumps (function calls) between the nodes. <a href="#a494934e26f644797a6f05ae6a4cadd53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300994ff552e61f928050b2734394208">AllChains</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All chains of nodes. <a href="#a300994ff552e61f928050b2734394208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chainedge">ChainEdge</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b7368d433e247974dda78bc1c7b7eb0">AllEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All edges between the chains. <a href="#a0b7368d433e247974dda78bc1c7b7eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d964fbcf587c97edbc5f1c920443c24">TotalSamples</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The total number of samples in the graph. <a href="#a0d964fbcf587c97edbc5f1c920443c24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2baca306cc80775ca5902d35f8baf9e9">TotalSize</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The total size of the nodes in the graph. <a href="#a2baca306cc80775ca5902d35f8baf9e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The implementation of the Cache-Directed Sort (CDSort) algorithm for ordering functions represented by a call graph.</p>

<p>Definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CDSortImpl() {#a68a9823d565755fe71d5a54fb0262947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeLayout.cpp}::CDSortImpl::CDSortImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig">CDSortConfig</a> &amp; Config, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeSizes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; EdgeCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; EdgeOffsets)</td>
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



<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a73e7e6f4b8c90a37295178a56661de2d">llvm::codelayout::computeCacheDirectedLayout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a562000bf2e945e451f810aac853454ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{CodeLayout.cpp}::CDSortImpl::run ()</td>
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

<p>Run the algorithm and return an ordered set of function clusters.</p>

<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeMergeGain() {#af10f01169306fd8ff8bd31cb6a5c496c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeGainT anonymous{CodeLayout.cpp}::CDSortImpl::computeMergeGain (<a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainPred, <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainSucc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergedjumpst">MergedJumpsT</a> &amp; Jumps, <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#a891fbaa9000c6c378ce647324830b0e6">MergeTypeT</a> MergeType)</td>
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

<p>Compute the score gain of merging two chains, respecting a given type.</p>


<p>The two chains are not modified in the method.</p>


<p>Definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### concatChains() {#a3278851f51cac767f3255272a4c49dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; anonymous{CodeLayout.cpp}::CDSortImpl::concatChains ()</td>
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

<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### distBasedLocalityGain() {#a7b5c5886ca65d5d19ce7e5f83f18ef6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{CodeLayout.cpp}::CDSortImpl::distBasedLocalityGain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergednodest">MergedNodesT</a> &amp; Nodes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergedjumpst">MergedJumpsT</a> &amp; Jumps)</td>
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

<p>Compute the change of the distance locality after merging the chains.</p>

<p>Definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### distScore() {#a84dfc398189f701b6b9a478a334301c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{CodeLayout.cpp}::CDSortImpl::distScore (uint64_t SrcAddr, uint64_t DstAddr, uint64_t Count)</td>
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

<p>Compute the distance locality for a jump / call.</p>

<p>Definition at line 1295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### freqBasedLocalityGain() {#a83ccfe4709f9913268b6a42ed1b8c61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{CodeLayout.cpp}::CDSortImpl::freqBasedLocalityGain (<a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainPred, <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * ChainSucc)</td>
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

<p>Compute the change of the frequency locality after merging the chains.</p>

<p>Definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### getBestMergeGain() {#a8e4231b699be14ce7160b86a045c519e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeGainT anonymous{CodeLayout.cpp}::CDSortImpl::getBestMergeGain (<a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chainedge">ChainEdge</a> * Edge)</td>
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


<p>Definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### initialize() {#a2dd1a22e6995272b1766d251eb653ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::CDSortImpl::initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; &amp; NodeSizes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; &amp; NodeCounts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; &amp; EdgeCounts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; &amp; EdgeOffsets)</td>
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

<p>Definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### mergeChainPairs() {#a3f74abf2a229a211da405da049065305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::CDSortImpl::mergeChainPairs ()</td>
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

<p>Merge pairs of chains while there is an improvement in the objective.</p>

<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### mergeChains() {#acbac1a8db10e0f43b9387df38978fa97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::CDSortImpl::mergeChains (<a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * Into, <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a> * From, size_t MergeOffset, <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#a891fbaa9000c6c378ce647324830b0e6">MergeTypeT</a> MergeType)</td>
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

<p>Definition at line 1323 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllChains {#a300994ff552e61f928050b2734394208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChainT&gt; anonymous{CodeLayout.cpp}::CDSortImpl::AllChains</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All chains of nodes.</p>

<p>Definition at line 1396 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### AllEdges {#a0b7368d433e247974dda78bc1c7b7eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChainEdge&gt; anonymous{CodeLayout.cpp}::CDSortImpl::AllEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All edges between the chains.</p>

<p>Definition at line 1399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### AllJumps {#a494934e26f644797a6f05ae6a4cadd53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;JumpT&gt; anonymous{CodeLayout.cpp}::CDSortImpl::AllJumps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All jumps (function calls) between the nodes.</p>

<p>Definition at line 1393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### AllNodes {#ae707dc7fcf8b45ee57a4f24f63825be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;NodeT&gt; anonymous{CodeLayout.cpp}::CDSortImpl::AllNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All nodes (functions) in the graph.</p>

<p>Definition at line 1390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### Config {#aaafffb7a2e6f29e87903d2bc371f58eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CDSortConfig anonymous{CodeLayout.cpp}::CDSortImpl::Config</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Config for the algorithm.</p>

<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### NumNodes {#a53882b590c1e7790f51822b39fb3809c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t anonymous{CodeLayout.cpp}::CDSortImpl::NumNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of nodes in the graph.</p>

<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### PredNodes {#aa8b5ffee5f19ab5054d604cbfd1fc7bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;uint64_t&gt; &gt; anonymous{CodeLayout.cpp}::CDSortImpl::PredNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Predecessors of each node.</p>

<p>Definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### SuccNodes {#a3b42cd388fe69b477bf5964fe73b8e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;uint64_t&gt; &gt; anonymous{CodeLayout.cpp}::CDSortImpl::SuccNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Successors of each node.</p>

<p>Definition at line 1384 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### TotalSamples {#a0d964fbcf587c97edbc5f1c920443c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{CodeLayout.cpp}::CDSortImpl::TotalSamples {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The total number of samples in the graph.</p>

<p>Definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### TotalSize {#a2baca306cc80775ca5902d35f8baf9e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{CodeLayout.cpp}::CDSortImpl::TotalSize {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The total size of the nodes in the graph.</p>

<p>Definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
