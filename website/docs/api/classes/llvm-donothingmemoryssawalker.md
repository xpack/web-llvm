---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/donothingmemoryssawalker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DoNothingMemorySSAWalker` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> that does no alias queries, or anything else. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DoNothingMemorySSAWalker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">llvm/Analysis/MemorySSA.h</a>"
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57722bcbe1bd2c1790af9bc8453a2f80">getClobberingMemoryAccess</a> (MemoryAccess *, BatchAAResults &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the same thing as <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess(const Instruction *I)</a>, but takes a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> instead of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#a57722bcbe1bd2c1790af9bc8453a2f80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a06a2393ac5f2a1ce4fe2c7ab9b4457">getClobberingMemoryAccess</a> (MemoryAccess *, const MemoryLocation &amp;, BatchAAResults &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a potentially clobbering memory access and a new location, calling this will give you the nearest dominating clobbering <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> (by skipping non-aliasing def links). <a href="#a3a06a2393ac5f2a1ce4fe2c7ab9b4457">More...</a></p>
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

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> that does no alias queries, or anything else.</p>


<p>It simply returns the links as they were constructed by the builder.</p>


<p>Definition at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getClobberingMemoryAccess() {#a57722bcbe1bd2c1790af9bc8453a2f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * DoNothingMemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does the same thing as <a href="#a9da2890c2f44bf0d822421285e9331b6">getClobberingMemoryAccess(const Instruction *I)</a>, but takes a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> instead of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>

<p>Declaration at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2615 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### getClobberingMemoryAccess() {#a3a06a2393ac5f2a1ce4fe2c7ab9b4457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * DoNothingMemorySSAWalker::getClobberingMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a potentially clobbering memory access and a new location, calling this will give you the nearest dominating clobbering <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> (by skipping non-aliasing def links).</p>


<p>This version of the function is mainly used to disambiguate phi translated pointers, where the value of a pointer may have changed from the initial memory access. Note that this expects to be handed either a <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a>, or an already potentially clobbering access. Unlike the above API, if given a <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> that clobbers the pointer as the starting access, it will return that <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a>, whereas the above would return the clobber starting from the use side of the memory def.</p>


<p>Declaration at line 1111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2622 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

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


<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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



<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
