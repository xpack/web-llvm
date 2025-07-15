---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-codelayout-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{CodeLayout.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{CodeLayout.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/cdsortimpl">CDSortImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The implementation of the Cache-Directed Sort (CDSort) algorithm for ordering functions represented by a call graph. <a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/cdsortimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chainedge">ChainEdge</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An edge in the graph representing jumps between two chains. <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chainedge/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint">ChainT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A chain (ordered sequence) of nodes in the graph. <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/chaint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/exttspimpl">ExtTSPImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The implementation of the ExtTSP algorithm. <a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/exttspimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/jumpt">JumpT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An arc in the graph, typically corresponding to a jump between two nodes. <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/jumpt/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergedjumpst">MergedJumpsT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around two concatenated vectors (chains) of jumps. <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergedjumpst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergednodest">MergedNodesT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around three concatenated vectors (chains) of nodes; it is used to avoid extra instantiation of the vectors. <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergednodest/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergegaint">MergeGainT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The gain of merging two chains, that is, the Ext-TSP score of the merge together with the corresponding merge 'type' and 'offset'. <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergegaint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A node in the graph, typically corresponding to a basic block in the CFG or a function in the call graph. <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MergeTypeT : int { <a href="#a891fbaa9000c6c378ce647324830b0e6">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A type of merging two chains, X and Y. <a href="#a891fbaa9000c6c378ce647324830b0e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc82cef9cbd4dab51921209f2a1ac14b">jumpExtTSPScore</a> (uint64_t JumpDist, uint64_t JumpMaxDist, uint64_t Count, double Weight)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ace5af72b93aedcb782ef65032c4de">extTSPScore</a> (uint64_t SrcAddr, uint64_t SrcSize, uint64_t DstAddr, uint64_t Count, bool IsConditional)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergednodest">MergedNodesT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800ced24f890a965660badbbd70800d2">mergeNodes</a> (const std::vector&lt; NodeT * &gt; &amp;X, const std::vector&lt; NodeT * &gt; &amp;Y, size_t MergeOffset, MergeTypeT MergeType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge two chains of nodes respecting a given 'type' and 'offset'. <a href="#a800ced24f890a965660badbbd70800d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e44545b673b6c107d44e7e2fa75727">EPS</a> = 1e-8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba7008c22659d027ed7e2987a9e4be2">EmptyList</a></td>
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


<div class="doxySectionDef">

## Typedefs

### NodeIter {#ada0856182ddb592b34f37da3f4dc1eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{CodeLayout.cpp}::NodeIter =  std::vector&lt;NodeT *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### MergeTypeT {#a891fbaa9000c6c378ce647324830b0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{CodeLayout.cpp}::MergeTypeT : int</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A type of merging two chains, X and Y.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X_Y<a id="a891fbaa9000c6c378ce647324830b0e6a72fa45c61dc40121aa4b4dcc30e90820"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Y_X<a id="a891fbaa9000c6c378ce647324830b0e6afeb017af50619530f4425e4e3589daf4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X1_Y_X2<a id="a891fbaa9000c6c378ce647324830b0e6ae2695a1ee61f06b989afe801282dd43d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Y_X2_X1<a id="a891fbaa9000c6c378ce647324830b0e6a72f1dd34dd1257167754a0d65ae72a49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X2_X1_Y<a id="a891fbaa9000c6c378ce647324830b0e6a9d20ddbb9d2f9e8166a4269812114e0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>The former chain is split into X1 and X2 and then concatenated with Y in the order specified by the type.</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### extTSPScore() {#a70ace5af72b93aedcb782ef65032c4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{CodeLayout.cpp}::extTSPScore (uint64_t SrcAddr, uint64_t SrcSize, uint64_t DstAddr, uint64_t Count, bool IsConditional)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#a45811f65f5bf5edbaedfd1d7b630b97e">BackwardDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#a491b555b7858327d05029fe52447d992">BackwardWeightCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#aea9eb0f6bac1ade99a6def26c68141c3">BackwardWeightUncond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#affece2ac80f379d7d409a19b3ed0aa2e">FallthroughWeightCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#ad029d20cd37f39d5567cddbbbacc220f">FallthroughWeightUncond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#a3f9f8ed4aa3937e607d43118dc83fa93">ForwardDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#aef83fc9a3d17150b7f143b1b2e7ab041">ForwardWeightCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#a69a7dfa5bfc081b957bae5cfe5d05d99">ForwardWeightUncond</a> and <a href="#acc82cef9cbd4dab51921209f2a1ac14b">jumpExtTSPScore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a70c3cab5f18ff0a00d4ad43ec3287021">llvm::codelayout::calcExtTspScore</a>.</p>

</div>
</div>

### jumpExtTSPScore() {#acc82cef9cbd4dab51921209f2a1ac14b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{CodeLayout.cpp}::jumpExtTSPScore (uint64_t JumpDist, uint64_t JumpMaxDist, uint64_t Count, double Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>


<p>Referenced by <a href="#a70ace5af72b93aedcb782ef65032c4de">extTSPScore</a>.</p>

</div>
</div>

### mergeNodes() {#a800ced24f890a965660badbbd70800d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergedNodesT anonymous{CodeLayout.cpp}::mergeNodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> * &gt; &amp; X, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> * &gt; &amp; Y, size_t MergeOffset, <a href="#a891fbaa9000c6c378ce647324830b0e6">MergeTypeT</a> MergeType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge two chains of nodes respecting a given 'type' and 'offset'.</p>


<p>If MergeType == 0, then the result is a concatenation of two chains. Otherwise, the first chain is cut into two sub-chains at the offset, and merged using all possible ways of concatenating three chains.</p>


<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergednodest/#a8d2c3cd8495ebf14693cbf159e16e7a0">anonymous{CodeLayout.cpp}::MergedNodesT::MergedNodesT</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="#a891fbaa9000c6c378ce647324830b0e6ae2695a1ee61f06b989afe801282dd43d">X1_Y_X2</a>, <a href="#a891fbaa9000c6c378ce647324830b0e6a9d20ddbb9d2f9e8166a4269812114e0d">X2_X1_Y</a>, <a href="#a891fbaa9000c6c378ce647324830b0e6a72fa45c61dc40121aa4b4dcc30e90820">X_Y</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, <a href="#a891fbaa9000c6c378ce647324830b0e6afeb017af50619530f4425e4e3589daf4">Y_X</a> and <a href="#a891fbaa9000c6c378ce647324830b0e6a72f1dd34dd1257167754a0d65ae72a49">Y_X2_X1</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EmptyList {#adba7008c22659d027ed7e2987a9e4be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;NodeT *&gt; anonymous{CodeLayout.cpp}::EmptyList</td>
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



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergednodest/#a8d2c3cd8495ebf14693cbf159e16e7a0">anonymous{CodeLayout.cpp}::MergedNodesT::MergedNodesT</a>.</p>

</div>
</div>

### EPS {#ab9e44545b673b6c107d44e7e2fa75727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{CodeLayout.cpp}::EPS = 1e-8</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/mergegaint/#a3d7ae80327993d7cd89c969f30c17a4c">anonymous{CodeLayout.cpp}::MergeGainT::operator&lt;</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
