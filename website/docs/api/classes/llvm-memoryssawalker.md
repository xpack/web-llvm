---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryssawalker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemorySSAWalker` Class Reference

<p>This is the generic walker interface for walkers of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemorySSAWalker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">llvm/Analysis/MemorySSA.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/donothingmemoryssawalker">DoNothingMemorySSAWalker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> that does no alias queries, or anything else. <a href="/web-llvm/docs/api/classes/llvm/donothingmemoryssawalker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker">CachingWalker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> that does <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> walks to disambiguate accesses. <a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa/skipselfwalker">SkipSelfWalker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a039ffa93cf728edc3399834d754a4a72">MemoryAccessSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, 8 &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049277aa22bd6d1efded38d340c37960">MemorySSA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cda9987d773268f1db499ac10de10f3">MemorySSAWalker</a> (MemorySSA *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d37dfce50a3a6f2f6f7ba75107feba7">~MemorySSAWalker</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2783df47072c5951e94299a35bc39848">getClobberingMemoryAccess</a> (const Instruction *I, BatchAAResults &amp;AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a memory Mod/Ref/ModRef'ing instruction, calling this will give you the nearest dominating <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> that Mod's the location the instruction accesses (by skipping any def which <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> can prove does not alias the location(s) accessed by the instruction given). <a href="#a2783df47072c5951e94299a35bc39848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9179c244f769791e913859444184354b">getClobberingMemoryAccess</a> (MemoryAccess *, BatchAAResults &amp;AA)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the same thing as <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess(const Instruction *I)</a>, but takes a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> instead of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#a9179c244f769791e913859444184354b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c156c9461c62eb99b3fd2590c2cf1df">getClobberingMemoryAccess</a> (MemoryAccess *, const MemoryLocation &amp;, BatchAAResults &amp;AA)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a potentially clobbering memory access and a new location, calling this will give you the nearest dominating clobbering <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> (by skipping non-aliasing def links). <a href="#a8c156c9461c62eb99b3fd2590c2cf1df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde4cbc4c203124d73b4279c8de814aa">getClobberingMemoryAccess</a> (MemoryAccess *MA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71362ef59d62d38c5a5719770282d756">getClobberingMemoryAccess</a> (MemoryAccess *MA, const MemoryLocation &amp;Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb8d1cc3b3a95d81ee75395cadf83c3">invalidateInfo</a> (MemoryAccess *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a memory access, invalidate anything this walker knows about that access. <a href="#a8bb8d1cc3b3a95d81ee75395cadf83c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2bda54c0424b0321a4ffbc28e7cd9f">MSSA</a></td>
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

<p>This is the generic walker interface for walkers of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>.</p>


<p>Walkers are used to be able to further disambiguate the def-use chains <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> gives you, or otherwise produce better info than <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> gives you. In particular, while the def-use chains provide basic information, and are guaranteed to give, for example, the nearest may-aliasing <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> for a <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a> as <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> considers it, a user mant want better or other information. In particular, they may want to use <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> info to further disambiguate memory accesses, or they may want the nearest dominating may-aliasing <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> for a call or a store. This API enables a standardized interface to getting and using that info.</p>


<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MemoryAccessSet {#a039ffa93cf728edc3399834d754a4a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemorySSAWalker::MemoryAccessSet =  SmallVector&lt;MemoryAccess *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MemorySSA {#a049277aa22bd6d1efded38d340c37960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1096 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a049277aa22bd6d1efded38d340c37960">MemorySSA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker/#acdde325b4f76f437b0f682f3f59d3a6f">llvm::MemorySSA::CachingWalker::CachingWalker</a>, <a href="#a049277aa22bd6d1efded38d340c37960">MemorySSA</a>, <a href="#a3cda9987d773268f1db499ac10de10f3">MemorySSAWalker</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/skipselfwalker/#abe29855a2ec8d6cc4977c397b646e591">llvm::MemorySSA::SkipSelfWalker::SkipSelfWalker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemorySSAWalker() {#a3cda9987d773268f1db499ac10de10f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAWalker::MemorySSAWalker (<a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2445 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#a049277aa22bd6d1efded38d340c37960">MemorySSA</a> and <a href="#a1c2bda54c0424b0321a4ffbc28e7cd9f">MSSA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker/#acdde325b4f76f437b0f682f3f59d3a6f">llvm::MemorySSA::CachingWalker::CachingWalker</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/skipselfwalker/#abe29855a2ec8d6cc4977c397b646e591">llvm::MemorySSA::SkipSelfWalker::SkipSelfWalker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MemorySSAWalker() {#a6d37dfce50a3a6f2f6f7ba75107feba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::MemorySSAWalker::~MemorySSAWalker ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getClobberingMemoryAccess() {#a2783df47072c5951e94299a35bc39848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
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

<p>Given a memory Mod/Ref/ModRef'ing instruction, calling this will give you the nearest dominating <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> that Mod's the location the instruction accesses (by skipping any def which <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> can prove does not alias the location(s) accessed by the instruction given).</p>


<p>Note that this will return a single access, and it must dominate the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, so if an operand of a <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> node Mod's the instruction, this will return the <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a>, not the operand. This means that given: if (a) { 1 = MemoryDef(liveOnEntry) store a } else { 2 = MemoryDef(liveOnEntry) store b } 3 = MemoryPhi(2, 1) MemoryUse(3) load a</p>


<p>calling this API on load(a) will return the <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a>, not the <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> in the if (a) branch.</p>


<p>Definition at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2783df47072c5951e94299a35bc39848">getClobberingMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1c2bda54c0424b0321a4ffbc28e7cd9f">MSSA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a329ad21a549f7f43ad50b65f4d3ca487">getClobberingMemoryAccess</a>, <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess</a>, <a href="#a2783df47072c5951e94299a35bc39848">getClobberingMemoryAccess</a>, <a href="#abde4cbc4c203124d73b4279c8de814aa">getClobberingMemoryAccess</a>, <a href="#a71362ef59d62d38c5a5719770282d756">getClobberingMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a92bfc4d7aa6add742c2a82b2e8f61455">getMatchingValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af55cf9792d5f9186df02c58b337a1511">llvm::AMDGPU::isClobberedInFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#ab06d3147949b764919b5ad90014afdfd">writtenBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker/#a8f0db7e077ab99af203421d92277acd5">llvm::MemorySSA::CachingWalker::~CachingWalker</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/skipselfwalker/#a64147a79aaac7db360bbe04da925f70d">llvm::MemorySSA::SkipSelfWalker::~SkipSelfWalker</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a9179c244f769791e913859444184354b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemoryAccess * llvm::MemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does the same thing as <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess(const Instruction *I)</a>, but takes a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> instead of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>

<p>Definition at line 1054 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a8c156c9461c62eb99b3fd2590c2cf1df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemoryAccess * llvm::MemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a potentially clobbering memory access and a new location, calling this will give you the nearest dominating clobbering <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> (by skipping non-aliasing def links).</p>


<p>This version of the function is mainly used to disambiguate phi translated pointers, where the value of a pointer may have changed from the initial memory access. Note that this expects to be handed either a <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a>, or an already potentially clobbering access. Unlike the above API, if given a <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> that clobbers the pointer as the starting access, it will return that <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a>, whereas the above would return the clobber starting from the use side of the memory def.</p>


<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a9da2890c2f44bf0d822421285e9331b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="#a2783df47072c5951e94299a35bc39848">getClobberingMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1c2bda54c0424b0321a4ffbc28e7cd9f">MSSA</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#abde4cbc4c203124d73b4279c8de814aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA)</td>
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



<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="#a2783df47072c5951e94299a35bc39848">getClobberingMemoryAccess</a> and <a href="#a1c2bda54c0424b0321a4ffbc28e7cd9f">MSSA</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a71362ef59d62d38c5a5719770282d756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc)</td>
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



<p>Definition at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="#a2783df47072c5951e94299a35bc39848">getClobberingMemoryAccess</a> and <a href="#a1c2bda54c0424b0321a4ffbc28e7cd9f">MSSA</a>.</p>

</div>
</div>

### invalidateInfo() {#a8bb8d1cc3b3a95d81ee75395cadf83c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MemorySSAWalker::invalidateInfo (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a memory access, invalidate anything this walker knows about that access.</p>


<p>This API is used by walkers that store information to perform basic cache invalidation. This will be called by <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> at appropriate times for the walker it uses or returns.</p>


<p>Definition at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#acd0427b84adce00e5b26f993c7aa48c8">llvm::MemorySSA::removeFromLookups</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MSSA {#a1c2bda54c0424b0321a4ffbc28e7cd9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA* llvm::MemorySSAWalker::MSSA</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Referenced by <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess</a>, <a href="#a2783df47072c5951e94299a35bc39848">getClobberingMemoryAccess</a>, <a href="#abde4cbc4c203124d73b4279c8de814aa">getClobberingMemoryAccess</a>, <a href="#a71362ef59d62d38c5a5719770282d756">getClobberingMemoryAccess</a> and <a href="#a3cda9987d773268f1db499ac10de10f3">MemorySSAWalker</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
