---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/spillplacement/node
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Node` Struct

<p><a href="/web-llvm/docs/api/classes/node">Node</a> - Each edge bundle corresponds to a Hopfield node. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct SpillPlacement::Node { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa492038a47765ed217bf484825fa0fc8">LinkVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a>, unsigned &gt;, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e88c2cf83e7164d2d0d85ed00f9b31">preferReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>preferReg - Return true when this node prefers to be in a register. <a href="#a15e88c2cf83e7164d2d0d85ed00f9b31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae39aa56454ff85c86ddd1aca307354bd">mustSpill</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mustSpill - Return True if this node is so biased that it must spill. <a href="#ae39aa56454ff85c86ddd1aca307354bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac905ce5783c59de0655d9733cd1f6b83">clear</a> (BlockFrequency Threshold)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Reset per-query data, but preserve frequencies that only depend on the CFG. <a href="#ac905ce5783c59de0655d9733cd1f6b83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414c03213909b5fd790e6f1b505b7099">addLink</a> (unsigned b, BlockFrequency w)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addLink - Add a link to bundle b with weight w. <a href="#a414c03213909b5fd790e6f1b505b7099">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03bf04c760f4e0dc8f8673a6dbbc1f37">addBias</a> (BlockFrequency freq, BorderConstraint direction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addBias - Bias this node. <a href="#a03bf04c760f4e0dc8f8673a6dbbc1f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25feab88416725ad9114fbb86af5dfc1">update</a> (const Node nodes[], BlockFrequency Threshold)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>update - Recompute <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from Bias and Links. <a href="#a25feab88416725ad9114fbb86af5dfc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1f662c46e92ef73f72533ef32887586">getDissentingNeighbors</a> (SparseSet&lt; unsigned &gt; &amp;List, const Node nodes[]) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370ae71068f6725ac2c6b61cf66a05b4">BiasN</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BiasN - Sum of blocks that prefer a spill. <a href="#a370ae71068f6725ac2c6b61cf66a05b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67abf92d6eabc03f37e9a2bd422e290a">BiasP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BiasP - Sum of blocks that prefer a register. <a href="#a67abf92d6eabc03f37e9a2bd422e290a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6155db02c64ef3abd03259a7dba04ea9">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> - Output value of this node computed from the Bias and links. <a href="#a6155db02c64ef3abd03259a7dba04ea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa492038a47765ed217bf484825fa0fc8">LinkVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a13362b22c15eb1235eacd5f8440ed4">Links</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Links - (Weight, BundleNo) for all transparent blocks connecting to other bundles. <a href="#a5a13362b22c15eb1235eacd5f8440ed4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b91674cb12c7e0eb5bddcd71213e4c6">SumLinkWeights</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SumLinkWeights - Cached sum of the weights of all links + ThresHold. <a href="#a2b91674cb12c7e0eb5bddcd71213e4c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/node">Node</a> - Each edge bundle corresponds to a Hopfield node.</p>


<p>The node contains precomputed frequency data that only depends on the CFG, but Bias and Links are computed each time placeSpills is called.</p>


<p>The node <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is positive when the variable should be in a register. The value can change when linked nodes change, but convergence is very fast because all weights are positive.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LinkVector {#aa492038a47765ed217bf484825fa0fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SpillPlacement::Node::LinkVector =  SmallVector&lt;std::pair&lt;BlockFrequency, unsigned&gt;, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBias() {#a03bf04c760f4e0dc8f8673a6dbbc1f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SpillPlacement::Node::addBias (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> freq, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8c">BorderConstraint</a> direction)</td>
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

<p>addBias - Bias this node.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="#a370ae71068f6725ac2c6b61cf66a05b4">llvm::SpillPlacement::Node::BiasN</a>, <a href="#a67abf92d6eabc03f37e9a2bd422e290a">llvm::SpillPlacement::Node::BiasP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a6228da6ce1f2cdae97b17637c061011e">freq</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a5bd2a8de4fde83093df0cc2415db2312">llvm::BlockFrequency::max</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8ca043a091e52f465df92623f5f17477837">llvm::SpillPlacement::MustSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8caca6da2dad218232636b80854d81a6e1c">llvm::SpillPlacement::PrefReg</a> and <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8caf5efe10871d66719c8668d09d768e740">llvm::SpillPlacement::PrefSpill</a>.</p>

</div>
</div>

### addLink() {#a414c03213909b5fd790e6f1b505b7099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SpillPlacement::Node::addLink (unsigned b, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> w)</td>
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

<p>addLink - Add a link to bundle b with weight w.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="#a5a13362b22c15eb1235eacd5f8440ed4">llvm::SpillPlacement::Node::Links</a> and <a href="#a2b91674cb12c7e0eb5bddcd71213e4c6">llvm::SpillPlacement::Node::SumLinkWeights</a>.</p>

</div>
</div>

### clear() {#ac905ce5783c59de0655d9733cd1f6b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SpillPlacement::Node::clear (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Threshold)</td>
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

<p>clear - Reset per-query data, but preserve frequencies that only depend on the CFG.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="#a370ae71068f6725ac2c6b61cf66a05b4">llvm::SpillPlacement::Node::BiasN</a>, <a href="#a67abf92d6eabc03f37e9a2bd422e290a">llvm::SpillPlacement::Node::BiasP</a>, <a href="#a5a13362b22c15eb1235eacd5f8440ed4">llvm::SpillPlacement::Node::Links</a>, <a href="#a2b91674cb12c7e0eb5bddcd71213e4c6">llvm::SpillPlacement::Node::SumLinkWeights</a> and <a href="#a6155db02c64ef3abd03259a7dba04ea9">llvm::SpillPlacement::Node::Value</a>.</p>

</div>
</div>

### getDissentingNeighbors() {#af1f662c46e92ef73f72533ef32887586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SpillPlacement::Node::getDissentingNeighbors (<a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; unsigned &gt; &amp; List, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/spillplacement/node">Node</a> nodes=[])</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="#a5a13362b22c15eb1235eacd5f8440ed4">llvm::SpillPlacement::Node::Links</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="#a6155db02c64ef3abd03259a7dba04ea9">llvm::SpillPlacement::Node::Value</a>.</p>

</div>
</div>

### mustSpill() {#ae39aa56454ff85c86ddd1aca307354bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpillPlacement::Node::mustSpill ()</td>
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

<p>mustSpill - Return True if this node is so biased that it must spill.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="#a370ae71068f6725ac2c6b61cf66a05b4">llvm::SpillPlacement::Node::BiasN</a>, <a href="#a67abf92d6eabc03f37e9a2bd422e290a">llvm::SpillPlacement::Node::BiasP</a> and <a href="#a2b91674cb12c7e0eb5bddcd71213e4c6">llvm::SpillPlacement::Node::SumLinkWeights</a>.</p>

</div>
</div>

### preferReg() {#a15e88c2cf83e7164d2d0d85ed00f9b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpillPlacement::Node::preferReg ()</td>
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

<p>preferReg - Return true when this node prefers to be in a register.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Reference <a href="#a6155db02c64ef3abd03259a7dba04ea9">llvm::SpillPlacement::Node::Value</a>.</p>


<p>Referenced by <a href="#a25feab88416725ad9114fbb86af5dfc1">llvm::SpillPlacement::Node::update</a>.</p>

</div>
</div>

### update() {#a25feab88416725ad9114fbb86af5dfc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpillPlacement::Node::update (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/spillplacement/node">Node</a> nodes=[], <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Threshold)</td>
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

<p>update - Recompute <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from Bias and Links.</p>


<p>Return true when node preference changes.</p>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="#a370ae71068f6725ac2c6b61cf66a05b4">llvm::SpillPlacement::Node::BiasN</a>, <a href="#a67abf92d6eabc03f37e9a2bd422e290a">llvm::SpillPlacement::Node::BiasP</a>, <a href="#a5a13362b22c15eb1235eacd5f8440ed4">llvm::SpillPlacement::Node::Links</a>, <a href="#a15e88c2cf83e7164d2d0d85ed00f9b31">llvm::SpillPlacement::Node::preferReg</a> and <a href="#a6155db02c64ef3abd03259a7dba04ea9">llvm::SpillPlacement::Node::Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BiasN {#a370ae71068f6725ac2c6b61cf66a05b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::SpillPlacement::Node::BiasN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BiasN - Sum of blocks that prefer a spill.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Referenced by <a href="#a03bf04c760f4e0dc8f8673a6dbbc1f37">llvm::SpillPlacement::Node::addBias</a>, <a href="#ac905ce5783c59de0655d9733cd1f6b83">llvm::SpillPlacement::Node::clear</a>, <a href="#ae39aa56454ff85c86ddd1aca307354bd">llvm::SpillPlacement::Node::mustSpill</a> and <a href="#a25feab88416725ad9114fbb86af5dfc1">llvm::SpillPlacement::Node::update</a>.</p>

</div>
</div>

### BiasP {#a67abf92d6eabc03f37e9a2bd422e290a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::SpillPlacement::Node::BiasP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BiasP - Sum of blocks that prefer a register.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Referenced by <a href="#a03bf04c760f4e0dc8f8673a6dbbc1f37">llvm::SpillPlacement::Node::addBias</a>, <a href="#ac905ce5783c59de0655d9733cd1f6b83">llvm::SpillPlacement::Node::clear</a>, <a href="#ae39aa56454ff85c86ddd1aca307354bd">llvm::SpillPlacement::Node::mustSpill</a> and <a href="#a25feab88416725ad9114fbb86af5dfc1">llvm::SpillPlacement::Node::update</a>.</p>

</div>
</div>

### Links {#a5a13362b22c15eb1235eacd5f8440ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkVector llvm::SpillPlacement::Node::Links</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Links - (Weight, BundleNo) for all transparent blocks connecting to other bundles.</p>


<p>The weights are all positive block frequencies.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Referenced by <a href="#a414c03213909b5fd790e6f1b505b7099">llvm::SpillPlacement::Node::addLink</a>, <a href="#ac905ce5783c59de0655d9733cd1f6b83">llvm::SpillPlacement::Node::clear</a>, <a href="#af1f662c46e92ef73f72533ef32887586">llvm::SpillPlacement::Node::getDissentingNeighbors</a> and <a href="#a25feab88416725ad9114fbb86af5dfc1">llvm::SpillPlacement::Node::update</a>.</p>

</div>
</div>

### SumLinkWeights {#a2b91674cb12c7e0eb5bddcd71213e4c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::SpillPlacement::Node::SumLinkWeights</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SumLinkWeights - Cached sum of the weights of all links + ThresHold.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Referenced by <a href="#a414c03213909b5fd790e6f1b505b7099">llvm::SpillPlacement::Node::addLink</a>, <a href="#ac905ce5783c59de0655d9733cd1f6b83">llvm::SpillPlacement::Node::clear</a> and <a href="#ae39aa56454ff85c86ddd1aca307354bd">llvm::SpillPlacement::Node::mustSpill</a>.</p>

</div>
</div>

### Value {#a6155db02c64ef3abd03259a7dba04ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SpillPlacement::Node::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> - Output value of this node computed from the Bias and links.</p>


<p>This is always on of the values {-1, 0, 1}. A positive number means the variable should go in a register through this bundle.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Referenced by <a href="#ac905ce5783c59de0655d9733cd1f6b83">llvm::SpillPlacement::Node::clear</a>, <a href="#af1f662c46e92ef73f72533ef32887586">llvm::SpillPlacement::Node::getDissentingNeighbors</a>, <a href="#a15e88c2cf83e7164d2d0d85ed00f9b31">llvm::SpillPlacement::Node::preferReg</a> and <a href="#a25feab88416725ad9114fbb86af5dfc1">llvm::SpillPlacement::Node::update</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
