---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dotgraphtraits-e5b50eb34ec0db639bdb467f977dace6
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DOTGraphTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::DOTGraphTraits&lt;RegionInfo *&gt; { ... }
</div>

## Base structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a> - This class provides the default implementations of all of the <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits">DOTGraphTraits</a> methods. <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-a54b3e8998714e8c0ac78d7291bb6d5c">DOTGraphTraits&lt;RegionNode *&gt;</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801bf3b310bd962f28714ccfdff27561">DOTGraphTraits</a> (bool isSimple=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449f9c0f319e2ea072f4e6a49412cef4">getNodeLabel</a> (RegionNode *Node, RegionInfo *G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe81aa588d38fa5cde97367d0cfc478">getEdgeAttributes</a> (RegionNode *srcNode, GraphTraits&lt; RegionInfo * &gt;::ChildIteratorType CI, RegionInfo *G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff853f9e678d20649c326eb9a0794864">getGraphName</a> (const RegionInfo *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3512588955bf7f5a4c5b088979022c0">printRegionCluster</a> (const Region &amp;R, GraphWriter&lt; RegionInfo * &gt; &amp;GW, unsigned depth=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dac0abee0dfd6123d667bba86a0035e">addCustomGraphFeatures</a> (const RegionInfo *G, GraphWriter&lt; RegionInfo * &gt; &amp;GW)</td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DOTGraphTraits() {#a801bf3b310bd962f28714ccfdff27561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraits&lt; RegionInfo * &gt;::DOTGraphTraits (bool isSimple=false)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>References <a href="#a801bf3b310bd962f28714ccfdff27561">DOTGraphTraits</a> and <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#ae8629cdc360910256304238ca5db1a45">llvm::DefaultDOTGraphTraits::isSimple</a>.</p>


<p>Referenced by <a href="#a801bf3b310bd962f28714ccfdff27561">DOTGraphTraits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEdgeAttributes() {#a8fe81aa588d38fa5cde97367d0cfc478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; RegionInfo * &gt;::getEdgeAttributes (<a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * srcNode, <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * &gt;<a href="/web-llvm/docs/api/structs/llvm/graphtraits">::ChildIteratorType</a> CI, <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * G)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#ac7a247b3585a3954ab1281e92de480bc">llvm::RegionNodeBase&lt; Tr &gt;::getNodeAs</a> and <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#a5c6251a6a2d27bec3ef89b0f6b3ad188">llvm::RegionNodeBase&lt; Tr &gt;::isSubRegion</a>.</p>

</div>
</div>

### getNodeLabel() {#a449f9c0f319e2ea072f4e6a49412cef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; RegionInfo * &gt;::getNodeLabel (<a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * G)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#a748e27397b601b36da4ff8689fe1d231">llvm::DefaultDOTGraphTraits::getNodeLabel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addCustomGraphFeatures() {#a2dac0abee0dfd6123d667bba86a0035e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DOTGraphTraits&lt; RegionInfo * &gt;::addCustomGraphFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * G, <a href="/web-llvm/docs/api/classes/llvm/graphwriter">GraphWriter</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * &gt; &amp; GW)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/graphwriter/#add17ddeb292024653fb5f09460be60ec">llvm::GraphWriter&lt; GraphType &gt;::getOStream</a> and <a href="#ab3512588955bf7f5a4c5b088979022c0">printRegionCluster</a>.</p>

</div>
</div>

### getGraphName() {#aff853f9e678d20649c326eb9a0794864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; RegionInfo * &gt;::getGraphName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> *)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>

</div>
</div>

### printRegionCluster() {#ab3512588955bf7f5a4c5b088979022c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DOTGraphTraits&lt; RegionInfo * &gt;::printRegionCluster (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/graphwriter">GraphWriter</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * &gt; &amp; GW, unsigned depth=0)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/graphwriter/#add17ddeb292024653fb5f09460be60ec">llvm::GraphWriter&lt; GraphType &gt;::getOStream</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a7100d3aafc08a45cc49421f186a0db6c">llvm::RegionInfoBase&lt; Tr &gt;::getRegionFor</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a5e825c7a51956c5d602ebff45036b1a9">llvm::RegionInfoBase&lt; Tr &gt;::getTopLevelRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a8e3080da2954744c200327ca1575c882">onlySimpleRegions</a> and <a href="#ab3512588955bf7f5a4c5b088979022c0">printRegionCluster</a>.</p>


<p>Referenced by <a href="#a2dac0abee0dfd6123d667bba86a0035e">addCustomGraphFeatures</a> and <a href="#ab3512588955bf7f5a4c5b088979022c0">printRegionCluster</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
