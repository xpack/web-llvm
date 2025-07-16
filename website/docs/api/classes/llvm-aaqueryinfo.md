---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aaqueryinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AAQueryInfo` Class Reference

<p>This class stores info we want to provide to or retain within an alias query. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AAQueryInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simpleaaqueryinfo">SimpleAAQueryInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> that uses <a href="/web-llvm/docs/api/classes/llvm/simplecaptureanalysis">SimpleCaptureAnalysis</a>. <a href="/web-llvm/docs/api/classes/llvm/simpleaaqueryinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac26caa587121d6621b82a9abe6016e6">LocPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/aacacheloc">AACacheLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/aacacheloc">AACacheLoc</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2519589ae7c7622078803c01182f768">AliasCacheT</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="#aac26caa587121d6621b82a9abe6016e6">LocPair</a>, <a href="/web-llvm/docs/api/structs/llvm/aaqueryinfo/cacheentry">CacheEntry</a>, 8 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1525f3f478b7fdf84ecc44e48040301f">AAQueryInfo</a> (AAResults &amp;AAR, CaptureAnalysis *CA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2549faec6e0b8dccf4df76fac37539b0">AAR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac2519589ae7c7622078803c01182f768">AliasCacheT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0790216d22061cace53c8b890faf69">AliasCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/captureanalysis">CaptureAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ff9779ff74e343bf51489c3bc0e563">CA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56080b59269d2c473d269614dfe68e7b">Depth</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query depth used to distinguish recursive queries. <a href="#a56080b59269d2c473d269614dfe68e7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a0539d2cf9c0e654fb4390f657e28b">NumAssumptionUses</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How many active NoAlias assumption uses there are. <a href="#aa8a0539d2cf9c0e654fb4390f657e28b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#aac26caa587121d6621b82a9abe6016e6">AAQueryInfo::LocPair</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d6c3ba0b6bb1c1ba16bd2f0aa059a5">AssumptionBasedResults</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Location pairs for which an assumption based result is currently stored. <a href="#a26d6c3ba0b6bb1c1ba16bd2f0aa059a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad146481f5f2cf1cad3e6174f4398ecbe">MayBeCrossIteration</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks whether the accesses may be on different cycle iterations. <a href="#ad146481f5f2cf1cad3e6174f4398ecbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7404d4af32aa9dd0f032762f5b4592b2">UseDominatorTree</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether alias analysis is allowed to use the dominator tree, for use by passes that lazily update the DT while performing <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> queries. <a href="#a7404d4af32aa9dd0f032762f5b4592b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class stores info we want to provide to or retain within an alias query.</p>


<p>By default, the root query is stateless and starts with a freshly constructed info object. Specific alias analyses can use this query info to store per-query state that is important for recursive or nested queries to avoid recomputing. To enable preserving this state across multiple queries where safe (due to the IR not changing), use a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a></span> wrapper. The information stored in an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a></span> is currently limitted to the caches used by <a href="/web-llvm/docs/api/classes/llvm/basicaa">BasicAA</a>, but can further be extended to fit other <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> needs.</p>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AliasCacheT {#ac2519589ae7c7622078803c01182f768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AAQueryInfo::AliasCacheT =  SmallDenseMap&lt;LocPair, CacheEntry, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### LocPair {#aac26caa587121d6621b82a9abe6016e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AAQueryInfo::LocPair =  std::pair&lt;AACacheLoc, AACacheLoc&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAQueryInfo() {#a1525f3f478b7fdf84ecc44e48040301f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAQueryInfo::AAQueryInfo (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AAR, <a href="/web-llvm/docs/api/structs/llvm/captureanalysis">CaptureAnalysis</a> * CA)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>References <a href="#a2549faec6e0b8dccf4df76fac37539b0">AAR</a> and <a href="#ad9ff9779ff74e343bf51489c3bc0e563">CA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simpleaaqueryinfo/#a4928d3290259b610a9e87fa579a5b4ae">llvm::SimpleAAQueryInfo::SimpleAAQueryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AAR {#a2549faec6e0b8dccf4df76fac37539b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults&amp; llvm::AAQueryInfo::AAR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="#a1525f3f478b7fdf84ecc44e48040301f">AAQueryInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#ab0468b18b8866896e7c3aa99700c6a97">llvm::BasicAAResult::getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#a43a53dbe445a968ef8851f1a257d4d7c">llvm::BasicAAResult::getModRefInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleaaqueryinfo/#a4928d3290259b610a9e87fa579a5b4ae">llvm::SimpleAAQueryInfo::SimpleAAQueryInfo</a>.</p>

</div>
</div>

### AliasCache {#abb0790216d22061cace53c8b890faf69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasCacheT llvm::AAQueryInfo::AliasCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### AssumptionBasedResults {#a26d6c3ba0b6bb1c1ba16bd2f0aa059a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AAQueryInfo::LocPair, 4&gt; llvm::AAQueryInfo::AssumptionBasedResults</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Location pairs for which an assumption based result is currently stored.</p>


<p>Used to remove all potentially incorrect results from the cache if an assumption is disproven.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### CA {#ad9ff9779ff74e343bf51489c3bc0e563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaptureAnalysis* llvm::AAQueryInfo::CA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="#a1525f3f478b7fdf84ecc44e48040301f">AAQueryInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#a43a53dbe445a968ef8851f1a257d4d7c">llvm::BasicAAResult::getModRefInfo</a>.</p>

</div>
</div>

### Depth {#a56080b59269d2c473d269614dfe68e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AAQueryInfo::Depth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query depth used to distinguish recursive queries.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a12e37baab16d8f80dd44998ea6df7b8d">llvm::AAResults::alias</a>.</p>

</div>
</div>

### MayBeCrossIteration {#ad146481f5f2cf1cad3e6174f4398ecbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAQueryInfo::MayBeCrossIteration = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tracks whether the accesses may be on different cycle iterations.</p>


<p>When interpret "Value" pointer equality as value equality we need to make sure that the "Value" is not part of a cycle. Otherwise, two uses could come from different "iterations" of a cycle and see different values for the same "Value" pointer.</p>


<p>The following example shows the problem: p = phi(alloca1, addr2) l = load ptr addr1 = gep, alloca2, 0, l addr2 = gep alloca2, 0, (l + 1) alias(p, addr1) -&gt; MayAlias ! store l, ...</p>


<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### NumAssumptionUses {#aa8a0539d2cf9c0e654fb4390f657e28b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AAQueryInfo::NumAssumptionUses = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How many active NoAlias assumption uses there are.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### UseDominatorTree {#a7404d4af32aa9dd0f032762f5b4592b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAQueryInfo::UseDominatorTree = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether alias analysis is allowed to use the dominator tree, for use by passes that lazily update the DT while performing <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> queries.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
