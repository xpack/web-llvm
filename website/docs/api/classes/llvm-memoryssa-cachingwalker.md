---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryssa/cachingwalker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CachingWalker` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> that does <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> walks to disambiguate accesses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemorySSA::CachingWalker { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the generic walker interface for walkers of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>. <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdde325b4f76f437b0f682f3f59d3a6f">CachingWalker</a> (MemorySSA *M, ClobberWalkerBase *W)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0db7e077ab99af203421d92277acd5">~CachingWalker</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf78f71c489b9e76cc8de37f8f67335">getClobberingMemoryAccess</a> (MemoryAccess *MA, BatchAAResults &amp;BAA, unsigned &amp;UWL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a730230666bf49fff62eeb3188c80367e">getClobberingMemoryAccess</a> (MemoryAccess *MA, const MemoryLocation &amp;Loc, BatchAAResults &amp;BAA, unsigned &amp;UWL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b458b62ba5acf372c1572e5d1ebd402">getClobberingMemoryAccessWithoutInvariantGroup</a> (MemoryAccess *MA, BatchAAResults &amp;BAA, unsigned &amp;UWL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3625e84baa96e4e44458e770a9e62b">getClobberingMemoryAccess</a> (MemoryAccess *MA, BatchAAResults &amp;BAA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the same thing as <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess(const Instruction *I)</a>, but takes a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> instead of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#a0c3625e84baa96e4e44458e770a9e62b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99ee53de921a4a3e794e5c137f774fe">getClobberingMemoryAccess</a> (MemoryAccess *MA, const MemoryLocation &amp;Loc, BatchAAResults &amp;BAA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a potentially clobbering memory access and a new location, calling this will give you the nearest dominating clobbering <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> (by skipping non-aliasing def links). <a href="#ad99ee53de921a4a3e794e5c137f774fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a775e17001d1ae4c4af6133518a1eadf0">invalidateInfo</a> (MemoryAccess *MA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a memory access, invalidate anything this walker knows about that access. <a href="#a775e17001d1ae4c4af6133518a1eadf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa/clobberwalkerbase">ClobberWalkerBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2f9f76eb9ec50fd71b6ebdb9cf0e64">Walker</a></td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> that does <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> walks to disambiguate accesses.</p>


<p>It no longer does caching on its own, but the name has been retained for the moment.</p>


<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CachingWalker() {#acdde325b4f76f437b0f682f3f59d3a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemorySSA::CachingWalker::CachingWalker (<a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * M, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/clobberwalkerbase">ClobberWalkerBase</a> * W)</td>
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



<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#a049277aa22bd6d1efded38d340c37960">llvm::MemorySSAWalker::MemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#a3cda9987d773268f1db499ac10de10f3">llvm::MemorySSAWalker::MemorySSAWalker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CachingWalker() {#a8f0db7e077ab99af203421d92277acd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemorySSA::CachingWalker::~CachingWalker ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#a2783df47072c5951e94299a35bc39848">llvm::MemorySSAWalker::getClobberingMemoryAccess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getClobberingMemoryAccess() {#aadf78f71c489b9e76cc8de37f8f67335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::CachingWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA, unsigned &amp; UWL)</td>
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



<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Referenced by <a href="#a0c3625e84baa96e4e44458e770a9e62b">getClobberingMemoryAccess</a> and <a href="#ad99ee53de921a4a3e794e5c137f774fe">getClobberingMemoryAccess</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a730230666bf49fff62eeb3188c80367e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::CachingWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA, unsigned &amp; UWL)</td>
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



<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a0c3625e84baa96e4e44458e770a9e62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::CachingWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
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

<p>Does the same thing as <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess(const Instruction *I)</a>, but takes a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> instead of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>

<p>Definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#aadf78f71c489b9e76cc8de37f8f67335">getClobberingMemoryAccess</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a1436be93fb9caea5d96609596e6ed0b4">MaxCheckLimit</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#ad99ee53de921a4a3e794e5c137f774fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::CachingWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
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

<p>Given a potentially clobbering memory access and a new location, calling this will give you the nearest dominating clobbering <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> (by skipping non-aliasing def links).</p>


<p>This version of the function is mainly used to disambiguate phi translated pointers, where the value of a pointer may have changed from the initial memory access. Note that this expects to be handed either a <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a>, or an already potentially clobbering access. Unlike the above API, if given a <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> that clobbers the pointer as the starting access, it will return that <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a>, whereas the above would return the clobber starting from the use side of the memory def.</p>


<p>Definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#aadf78f71c489b9e76cc8de37f8f67335">getClobberingMemoryAccess</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a1436be93fb9caea5d96609596e6ed0b4">MaxCheckLimit</a>.</p>

</div>
</div>

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


<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### getClobberingMemoryAccessWithoutInvariantGroup() {#a4b458b62ba5acf372c1572e5d1ebd402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::CachingWalker::getClobberingMemoryAccessWithoutInvariantGroup (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA, unsigned &amp; UWL)</td>
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



<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### invalidateInfo() {#a775e17001d1ae4c4af6133518a1eadf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemorySSA::CachingWalker::invalidateInfo (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *)</td>
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


<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Walker {#aec2f9f76eb9ec50fd71b6ebdb9cf0e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClobberWalkerBase* llvm::MemorySSA::CachingWalker::Walker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1013 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

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
