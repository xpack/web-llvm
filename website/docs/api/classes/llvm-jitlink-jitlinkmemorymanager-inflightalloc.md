---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InFlightAlloc` Class

<p>Represents an allocation which has not been finalized yet. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::JITLinkMemoryManager::InFlightAlloc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">llvm/ExecutionEngine/JITLink/JITLinkMemoryManager.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/ipinflightalloc">IPInFlightAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager/inflightalloc">InFlightAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager/inflightalloc">InFlightAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4c74c3c51697683582571ffc39d987">OnFinalizedFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3c1cf1871e9e99843174f7b8992849">OnAbandonedFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3117ce87541f6bedaa36d3316a03909">~InFlightAlloc</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1ec6968b3cef7a9ef6011238bb6f17">abandon</a> (OnAbandonedFunction OnAbandoned)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called prior to finalization if the allocation should be abandoned. <a href="#a5d1ec6968b3cef7a9ef6011238bb6f17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c79270b3e2a8590fda6a9919c12eae1">finalize</a> (OnFinalizedFunction OnFinalized)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to transfer working memory to the target and apply finalization. <a href="#a2c79270b3e2a8590fda6a9919c12eae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620e9f96a43c66ac377eeb031d5e3646">finalize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Synchronous convenience version of finalize. <a href="#a620e9f96a43c66ac377eeb031d5e3646">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents an allocation which has not been finalized yet.</p>


<p>InFlightAllocs manage both executor memory allocations and working memory allocations.</p>


<p>On finalization, the <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc">InFlightAlloc</a> should transfer the content of working memory into executor memory, apply memory protections, and run any finalization functions.</p>


<p>Working memory should be kept alive at least until one of the following happens: (1) the <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc">InFlightAlloc</a> instance is destroyed, (2) the <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc">InFlightAlloc</a> is abandoned, (3) finalized target memory is destroyed.</p>


<p>If abandon is called then working memory and executor memory should both be freed.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### OnAbandonedFunction {#a4f3c1cf1871e9e99843174f7b8992849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::JITLinkMemoryManager::InFlightAlloc::OnAbandonedFunction =  unique_function&lt;void(Error)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### OnFinalizedFunction {#a9f4c74c3c51697683582571ffc39d987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::JITLinkMemoryManager::InFlightAlloc::OnFinalizedFunction =  unique_function&lt;void(Expected&lt;FinalizedAlloc&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InFlightAlloc() {#aa3117ce87541f6bedaa36d3316a03909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::JITLinkMemoryManager::InFlightAlloc::~InFlightAlloc ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### abandon() {#a5d1ec6968b3cef7a9ef6011238bb6f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::jitlink::JITLinkMemoryManager::InFlightAlloc::abandon (<a href="#a4f3c1cf1871e9e99843174f7b8992849">OnAbandonedFunction</a> OnAbandoned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called prior to finalization if the allocation should be abandoned.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### finalize() {#a2c79270b3e2a8590fda6a9919c12eae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::jitlink::JITLinkMemoryManager::InFlightAlloc::finalize (<a href="#a9f4c74c3c51697683582571ffc39d987">OnFinalizedFunction</a> OnFinalized)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called to transfer working memory to the target and apply finalization.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### finalize() {#a620e9f96a43c66ac377eeb031d5e3646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; FinalizedAlloc &gt; llvm::jitlink::JITLinkMemoryManager::InFlightAlloc::finalize ()</td>
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

<p>Synchronous convenience version of finalize.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>


<p>Reference <a href="#a620e9f96a43c66ac377eeb031d5e3646">finalize</a>.</p>


<p>Referenced by <a href="#a620e9f96a43c66ac377eeb031d5e3646">finalize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
