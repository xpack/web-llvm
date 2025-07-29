---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/mapperjitlinkmemorymanager/inflightalloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InFlightAlloc` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc">InFlightAlloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an allocation which has not been finalized yet. <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf0f3f3b1bea06f498f4cf21fe9f601">InFlightAlloc</a> (MapperJITLinkMemoryManager &amp;Parent, LinkGraph &amp;G, ExecutorAddr AllocAddr, std::vector&lt; MemoryMapper::AllocInfo::SegInfo &gt; Segs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a96a71e0a19bc870ccc43952e2b74e1">finalize</a> (OnFinalizedFunction OnFinalize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to transfer working memory to the target and apply finalization. <a href="#a5a96a71e0a19bc870ccc43952e2b74e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac67c274a02173e4e17bb33aabfe71b5c">abandon</a> (OnAbandonedFunction OnFinalize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called prior to finalization if the allocation should be abandoned. <a href="#ac67c274a02173e4e17bb33aabfe71b5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager">MapperJITLinkMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437074fcf8dc62601855f37fd9857963">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423c59884bedc93474820767837683ac">G</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190aee416145ad6126b3e551508dfd93">AllocAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/seginfo">MemoryMapper::AllocInfo::SegInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c8fb2da1d7adf56654b20aaa3cd249">Segs</a></td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InFlightAlloc() {#a2bf0f3f3b1bea06f498f4cf21fe9f601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::InFlightAlloc (<a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager">MapperJITLinkMemoryManager</a> &amp; Parent, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> AllocAddr, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/seginfo">MemoryMapper::AllocInfo::SegInfo</a> &gt; Segs)</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager/#a8af341940c4fd14e1e43490ba2af1da1">llvm::orc::MapperJITLinkMemoryManager::MapperJITLinkMemoryManager</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### abandon() {#ac67c274a02173e4e17bb33aabfe71b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::abandon (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc/#a4f3c1cf1871e9e99843174f7b8992849">OnAbandonedFunction</a> OnAbandoned)</td>
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

<p>Called prior to finalization if the allocation should be abandoned.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

### finalize() {#a5a96a71e0a19bc870ccc43952e2b74e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::finalize (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc/#a9f4c74c3c51697683582571ffc39d987">OnFinalizedFunction</a> OnFinalized)</td>
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

<p>Called to transfer working memory to the target and apply finalization.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#aa83c8c10a9eb18cd233eed2ecf12ca71">llvm::orc::MemoryMapper::AllocInfo::Actions</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#a8ae25e2221d662f2fbffc49d0b172b3a">llvm::orc::MemoryMapper::AllocInfo::MappingBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#a6b6dcea60d496fc8de6d65188804b995">llvm::orc::MemoryMapper::AllocInfo::Segments</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocAddr {#a190aee416145ad6126b3e551508dfd93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::AllocAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

### G {#a423c59884bedc93474820767837683ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraph&amp; llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::G</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

### Parent {#a437074fcf8dc62601855f37fd9857963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapperJITLinkMemoryManager&amp; llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

### Segs {#ad5c8fb2da1d7adf56654b20aaa3cd249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MemoryMapper::AllocInfo::SegInfo&gt; llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::Segs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
