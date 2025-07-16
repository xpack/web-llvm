---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegionInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RegionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regioninfobase">RegionInfoBase&lt;Tr&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analysis that detects all canonical Regions. <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8080a53b6bedf5706b1024b44d4c84b">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/regioninfobase">RegionInfoBase</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/regiontraits">RegionTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2abc011fcb0290f4b6964f9e5da6f3c6">RegionInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ae03c82b0a5bcde395f2d66994ee80">RegionInfo</a> (RegionInfo &amp;&amp;Arg)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c019970926ac2317053ba00f9c933a1">~RegionInfo</a> () override</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e771a831eb9ce6d28ec71b06ea4f5f4">operator=</a> (RegionInfo &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0336f49c52907a530484c2c4a3b2f82">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation explicitly. <a href="#ad0336f49c52907a530484c2c4a3b2f82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ec98b276394802d893ff7cdccd1cd3">updateStatistics</a> (Region *R) final</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a734ee68971d7ac400c77cb4d68e94c71">recalculate</a> (Function &amp;F, DominatorTree *DT, PostDominatorTree *PDT, DominanceFrontier *DF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3450486526981b8bc661900c572fa689">view</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opens a viewer to show the GraphViz visualization of the regions. <a href="#a3450486526981b8bc661900c572fa689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73040699f8b44e373884e6c439b757ac">viewOnly</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opens a viewer to show the GraphViz visualization of this region without instructions in the BasicBlocks. <a href="#a73040699f8b44e373884e6c439b757ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#af8080a53b6bedf5706b1024b44d4c84b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionInfo::Base =  RegionInfoBase&lt;RegionTraits&lt;Function&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegionInfo() {#a2abc011fcb0290f4b6964f9e5da6f3c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfo::RegionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="#a7e771a831eb9ce6d28ec71b06ea4f5f4">operator=</a> and <a href="#a13ae03c82b0a5bcde395f2d66994ee80">RegionInfo</a>.</p>

</div>
</div>

### RegionInfo() {#a13ae03c82b0a5bcde395f2d66994ee80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionInfo::RegionInfo (<a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a2abc011fcb0290f4b6964f9e5da6f3c6">RegionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a1b88e00bca3867246e6678f1b4b9b607">llvm::RegionInfoBase&lt; RegionTraits&lt; Function &gt; &gt;::updateRegionTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RegionInfo() {#a6c019970926ac2317053ba00f9c933a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfo::~RegionInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a7e771a831eb9ce6d28ec71b06ea4f5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfo &amp; llvm::RegionInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a2abc011fcb0290f4b6964f9e5da6f3c6">RegionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a1b88e00bca3867246e6678f1b4b9b607">llvm::RegionInfoBase&lt; RegionTraits&lt; Function &gt; &gt;::updateRegionTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### invalidate() {#ad0336f49c52907a530484c2c4a3b2f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegionInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invalidation explicitly.</p>

<p>Declaration at line 917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### recalculate() {#a734ee68971d7ac400c77cb4d68e94c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfo::recalculate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontier">DominanceFrontier</a> * DF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 923 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#aa2ec98b276394802d893ff7cdccd1cd3">updateStatistics</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regioninfoanalysis/#aeb18bff655e7a0fdfbf8143b8beec782">llvm::RegionInfoAnalysis::run</a>.</p>

</div>
</div>

### updateStatistics() {#aa2ec98b276394802d893ff7cdccd1cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfo::updateStatistics (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>Referenced by <a href="#a734ee68971d7ac400c77cb4d68e94c71">recalculate</a>.</p>

</div>
</div>

### view() {#a3450486526981b8bc661900c572fa689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfo::view ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opens a viewer to show the GraphViz visualization of the regions.</p>


<p>Useful during debugging as an alternative to <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a215b26a0bc3e7048bc79ef21db564b1f">dump()</a>.</p>


<p>Declaration at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aee30bf714c0718589fd36f05351af330">llvm::viewRegion</a>.</p>

</div>
</div>

### viewOnly() {#a73040699f8b44e373884e6c439b757ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfo::viewOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opens a viewer to show the GraphViz visualization of this region without instructions in the BasicBlocks.</p>


<p>Useful during debugging as an alternative to <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a215b26a0bc3e7048bc79ef21db564b1f">dump()</a>.</p>


<p>Declaration at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af3316136f9709117681e6e8ec810955f">llvm::viewRegionOnly</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
