---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lazycallgraph/node
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Node` Class

<p>A node in the call graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LazyCallGraph::Node { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e22ce88e85bef8152cacbdecaaa03e">LazyCallGraph::RefSCC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ddc9b5d662f44fe1796351ca5390f5">operator&lt;&lt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the name of this node's function. <a href="#aa6ddc9b5d662f44fe1796351ca5390f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9c9f3f43b2d478db29d5ed038b6037">Node</a> (LazyCallGraph &amp;G, Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic constructor implements the scanning of F into Edges and EdgeIndexMap. <a href="#a0f9c9f3f43b2d478db29d5ed038b6037">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa308f33c44766d2ff81d7ff7928a1791">operator==</a> (const Node &amp;N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality is defined as address equality. <a href="#aa308f33c44766d2ff81d7ff7928a1791">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990f347b1a7291ed845028292f17b2c1">operator!=</a> (const Node &amp;N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33b38d2a05cc85bee72d21a709196ee">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8172e011b74705ed66e052e0d1f41d0">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45fef512ab3e0ce0202d03ac40fc6550">getGraph</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae636d5bc5dff8a979202c9f523fa0786">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ce8f49d154b3b8d75352711b37e24d">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6297d99bec8e2784ff5c35932d9386">isPopulated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the node has been populated with edges. <a href="#a9f6297d99bec8e2784ff5c35932d9386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661c722d795d4bb92a2a7520e0d4dc9d">isDead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether this is actually a dead node and no longer valid. <a href="#a661c722d795d4bb92a2a7520e0d4dc9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62430f7b0d0d86666133852851d2afdb">populate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the edges of this node if necessary. <a href="#a62430f7b0d0d86666133852851d2afdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e879267e3a1434ad27fd3b9ded3b45c">populateSlow</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of the scan when populating. <a href="#a5e879267e3a1434ad27fd3b9ded3b45c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08b37016c2f35defdbc8f8487de3c73">replaceFunction</a> (Function &amp;NewF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal helper to directly replace the function with a new one. <a href="#ad08b37016c2f35defdbc8f8487de3c73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae71560c47c93517ae42e3b910fb47074">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6aa8d354efaad1a49577422d63509e9">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the name of this node's function to stderr. <a href="#ae6aa8d354efaad1a49577422d63509e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c411ca4838e0b99276bf9d55a6235c">G</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a818b4574e5bd975cef52c689cca7aee2">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b8bd130d748c7d9250394a938ea970">DFSNumber</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab497d51b116b4d742766970fa4abbc6b">LowLink</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cdcac6682ba6003dac6990cc8d5275a">Edges</a></td>
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

<p>A node in the call graph.</p>


<p>This represents a single node. Its primary roles are to cache the list of callees, de-duplicate and provide fast testing of whether a function is a callee, and facilitate iteration of child nodes in the graph.</p>


<p>The node works much like an optional in order to lazily populate the edges of each node. Until populated, there are no edges. Once populated, you can access the edges by dereferencing the node or using the <span class="doxyComputerOutput">-&gt;</span> operator as if the node was an <span class="doxyComputerOutput">std::optional&lt;<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a>&gt;</span>.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LazyCallGraph {#a81774ea46253e6427d63a610bd624c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>.</p>


<p>Referenced by <a href="#a45fef512ab3e0ce0202d03ac40fc6550">getGraph</a> and <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>.</p>

</div>
</div>

### LazyCallGraph::RefSCC {#a17e22ce88e85bef8152cacbdecaaa03e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">LazyCallGraph::RefSCC</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### operator&lt;&lt; {#aa6ddc9b5d662f44fe1796351ca5390f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; N</td>
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

<p>Print the name of this node's function.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Node() {#a0f9c9f3f43b2d478db29d5ed038b6037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LazyCallGraph::Node::Node (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Basic constructor implements the scanning of F into Edges and EdgeIndexMap.</p>

<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-&gt;() {#ac8172e011b74705ed66e052e0d1f41d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeSequence * llvm::LazyCallGraph::Node::operator-&gt; ()</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### operator!=() {#a990f347b1a7291ed845028292f17b2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::Node::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; N)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#aa308f33c44766d2ff81d7ff7928a1791">operator==</a>.</p>

</div>
</div>

### operator\*() {#ae33b38d2a05cc85bee72d21a709196ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeSequence &amp; llvm::LazyCallGraph::Node::operator* ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### operator==() {#aa308f33c44766d2ff81d7ff7928a1791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::Node::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; N)</td>
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

<p>Equality is defined as address equality.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a990f347b1a7291ed845028292f17b2c1">operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFunction() {#ae636d5bc5dff8a979202c9f523fa0786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function &amp; llvm::LazyCallGraph::Node::getFunction ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### getGraph() {#a45fef512ab3e0ce0202d03ac40fc6550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph &amp; llvm::LazyCallGraph::Node::getGraph ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>.</p>

</div>
</div>

### getName() {#ad3ce8f49d154b3b8d75352711b37e24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LazyCallGraph::Node::getName ()</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### isDead() {#a661c722d795d4bb92a2a7520e0d4dc9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::Node::isDead ()</td>
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

<p>Tests whether this is actually a dead node and no longer valid.</p>


<p>Users rarely interact with nodes in this state and other methods are invalid. This is used to model a node in an edge list where the function has been completely removed.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### isPopulated() {#a9f6297d99bec8e2784ff5c35932d9386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::Node::isPopulated ()</td>
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

<p>Tests whether the node has been populated with edges.</p>

<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### populate() {#a62430f7b0d0d86666133852851d2afdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeSequence &amp; llvm::LazyCallGraph::Node::populate ()</td>
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

<p>Populate the edges of this node if necessary.</p>


<p>The first time this is called it will populate the edges for this node in the graph. It does this by scanning the underlying function, so once this is done, any changes to that function must be explicitly reflected in updates to the graph.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the populated <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence">EdgeSequence</a></span> to simplify walking it.</p></dd>
</dl>


<p>This will not update or re-scan anything if called repeatedly. Instead, the edge sequence is cached and returned immediately on subsequent calls.</p>


<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### clear() {#ae71560c47c93517ae42e3b910fb47074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LazyCallGraph::Node::clear ()</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### dump() {#ae6aa8d354efaad1a49577422d63509e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LazyCallGraph::Node::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the name of this node's function to stderr.</p>

<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### populateSlow() {#a5e879267e3a1434ad27fd3b9ded3b45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::EdgeSequence &amp; LazyCallGraph::Node::populateSlow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementation of the scan when populating.</p>

<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### replaceFunction() {#ad08b37016c2f35defdbc8f8487de3c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::Node::replaceFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; NewF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Internal helper to directly replace the function with a new one.</p>


<p>This is used to facilitate transformations which need to replace the formal <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> object but directly move the body and users from one to the other.</p>


<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DFSNumber {#a43b8bd130d748c7d9250394a938ea970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LazyCallGraph::Node::DFSNumber = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### Edges {#a4cdcac6682ba6003dac6990cc8d5275a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;EdgeSequence&gt; llvm::LazyCallGraph::Node::Edges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### F {#a818b4574e5bd975cef52c689cca7aee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::LazyCallGraph::Node::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### G {#ab7c411ca4838e0b99276bf9d55a6235c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph* llvm::LazyCallGraph::Node::G</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### LowLink {#ab497d51b116b4d742766970fa4abbc6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LazyCallGraph::Node::LowLink = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
