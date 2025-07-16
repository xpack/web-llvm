---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryssa/skipselfwalker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SkipSelfWalker` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MemorySSA::SkipSelfWalker { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe29855a2ec8d6cc4977c397b646e591">SkipSelfWalker</a> (MemorySSA *M, ClobberWalkerBase *W)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64147a79aaac7db360bbe04da925f70d">~SkipSelfWalker</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3a24827685dc65781fd3c4074708ba">getClobberingMemoryAccess</a> (MemoryAccess *MA, BatchAAResults &amp;BAA, unsigned &amp;UWL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a35d3092cac539ee12dcd4988eb870b">getClobberingMemoryAccess</a> (MemoryAccess *MA, const MemoryLocation &amp;Loc, BatchAAResults &amp;BAA, unsigned &amp;UWL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0de4d92d12aba524bd8ea3eac01a24a">getClobberingMemoryAccess</a> (MemoryAccess *MA, BatchAAResults &amp;BAA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the same thing as <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess(const Instruction *I)</a>, but takes a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> instead of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#ad0de4d92d12aba524bd8ea3eac01a24a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a436216f6ed38b7dc7a985eb697ea63f0">getClobberingMemoryAccess</a> (MemoryAccess *MA, const MemoryLocation &amp;Loc, BatchAAResults &amp;BAA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a potentially clobbering memory access and a new location, calling this will give you the nearest dominating clobbering <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> (by skipping non-aliasing def links). <a href="#a436216f6ed38b7dc7a985eb697ea63f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b567bc09d96e972d2f2636374a8bd7">invalidateInfo</a> (MemoryAccess *MA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a memory access, invalidate anything this walker knows about that access. <a href="#af6b567bc09d96e972d2f2636374a8bd7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c910ce8d46bf803c4cb24e66e7f702f">Walker</a></td>
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


<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SkipSelfWalker() {#abe29855a2ec8d6cc4977c397b646e591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemorySSA::SkipSelfWalker::SkipSelfWalker (<a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * M, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/clobberwalkerbase">ClobberWalkerBase</a> * W)</td>
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



<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#a049277aa22bd6d1efded38d340c37960">llvm::MemorySSAWalker::MemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#a3cda9987d773268f1db499ac10de10f3">llvm::MemorySSAWalker::MemorySSAWalker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SkipSelfWalker() {#a64147a79aaac7db360bbe04da925f70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemorySSA::SkipSelfWalker::~SkipSelfWalker ()</td>
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



<p>Definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#a2783df47072c5951e94299a35bc39848">llvm::MemorySSAWalker::getClobberingMemoryAccess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getClobberingMemoryAccess() {#a8a3a24827685dc65781fd3c4074708ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::SkipSelfWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA, unsigned &amp; UWL)</td>
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



<p>Definition at line 1065 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Referenced by <a href="#ad0de4d92d12aba524bd8ea3eac01a24a">getClobberingMemoryAccess</a> and <a href="#a436216f6ed38b7dc7a985eb697ea63f0">getClobberingMemoryAccess</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a5a35d3092cac539ee12dcd4988eb870b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::SkipSelfWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA, unsigned &amp; UWL)</td>
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



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#ad0de4d92d12aba524bd8ea3eac01a24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::SkipSelfWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
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

<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#a8a3a24827685dc65781fd3c4074708ba">getClobberingMemoryAccess</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a1436be93fb9caea5d96609596e6ed0b4">MaxCheckLimit</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a436216f6ed38b7dc7a985eb697ea63f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::SkipSelfWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
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


<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#a8a3a24827685dc65781fd3c4074708ba">getClobberingMemoryAccess</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a1436be93fb9caea5d96609596e6ed0b4">MaxCheckLimit</a>.</p>

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


<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>, definition at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### invalidateInfo() {#af6b567bc09d96e972d2f2636374a8bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemorySSA::SkipSelfWalker::invalidateInfo (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *)</td>
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


<p>Definition at line 1087 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Walker {#a5c910ce8d46bf803c4cb24e66e7f702f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClobberWalkerBase* llvm::MemorySSA::SkipSelfWalker::Walker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

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
