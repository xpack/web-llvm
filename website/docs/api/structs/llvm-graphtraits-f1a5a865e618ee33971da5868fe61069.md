---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/graphtraits-f1a5a865e618ee33971da5868fe61069
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GraphTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::GraphTraits&lt;ProfiledCallGraph *&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">llvm/Transforms/IPO/ProfiledCallGraph.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-3415cdfe2a550135494395498d7d0793">GraphTraits&lt;ProfiledCallGraphNode *&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> = typename <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph">ProfiledCallGraph</a> *::UnknownGraphTypeError</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34b0507daeb588235560612f44a4062">getEntryNode</a> (ProfiledCallGraph *PCG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/graphtraits-3415cdfe2a550135494395498d7d0793/#ac4ca5700b772116f64af6da61a94a7cb">ChildIteratorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2cb75bfde47d5fa2eb96ccfb96292f">nodes_begin</a> (ProfiledCallGraph *PCG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/graphtraits-3415cdfe2a550135494395498d7d0793/#ac4ca5700b772116f64af6da61a94a7cb">ChildIteratorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba229770fe3c5e039e0fe34fa3a541f8">nodes_end</a> (ProfiledCallGraph *PCG)</td>
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


<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NodeRef {#a741f7d63af17a7bd0bcf63f68e8658bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; ProfiledCallGraph * &gt;::NodeRef = </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEntryNode() {#aa34b0507daeb588235560612f44a4062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::GraphTraits&lt; ProfiledCallGraph * &gt;::getEntryNode (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph">ProfiledCallGraph</a> * PCG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#a4afbf3b4aab03e1777b67fd657d03cb5">llvm::sampleprof::ProfiledCallGraph::getEntryNode</a>.</p>

</div>
</div>

### nodes\_begin() {#adc2cb75bfde47d5fa2eb96ccfb96292f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIteratorType llvm::GraphTraits&lt; ProfiledCallGraph * &gt;::nodes_begin (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph">ProfiledCallGraph</a> * PCG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#ae0ddc9bdb077cf643f29ddd1320bafb4">llvm::sampleprof::ProfiledCallGraph::begin</a>.</p>

</div>
</div>

### nodes\_end() {#aba229770fe3c5e039e0fe34fa3a541f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIteratorType llvm::GraphTraits&lt; ProfiledCallGraph * &gt;::nodes_end (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph">ProfiledCallGraph</a> * PCG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#add34fd6645cc6eb20b5210117cd4f767">llvm::sampleprof::ProfiledCallGraph::end</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
