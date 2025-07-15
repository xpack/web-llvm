---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/basiclayout
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BasicLayout` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout">BasicLayout</a> simplifies the implementation of JITLinkMemoryManagers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::BasicLayout { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">llvm/ExecutionEngine/JITLink/JITLinkMemoryManager.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e637b4398423ac58812c51bf965c3b">SegmentMap</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/allocgroupsmallmap">orc::AllocGroupSmallMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout/segment">Segment</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3fa75b45aafa6c528042df53446d8e1">BasicLayout</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198fecf47eeb21d990c10a372527df12">getGraph</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the graph this allocation was created from. <a href="#a198fecf47eeb21d990c10a372527df12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/jitlink/basiclayout/contiguouspagebasedlayoutsizes">ContiguousPageBasedLayoutSizes</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd4dbd21630dedd3eac2bf9c6932a88">getContiguousPageBasedLayoutSizes</a> (uint64_t PageSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the total number of required to allocate all segments (with each segment padded out to page size) for all standard segments, and all finalize segments. <a href="#adbd4dbd21630dedd3eac2bf9c6932a88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/allocgroupsmallmap/#aff85d3f14d78a8c608e4a23e1b2a8b9b">SegmentMap::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f0db658acaeff82c1f097f5dde15e4">segments</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator over the segments of the layout. <a href="#ae7f0db658acaeff82c1f097f5dde15e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6118016e682bb76a031f3857dc3627f">apply</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the layout to the graph. <a href="#ac6118016e682bb76a031f3857dc3627f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a6da0b5cb8e68a6cc791a183d9d38aae0">orc::shared::AllocActions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025352e474cbac473d4ca121501d0272">graphAllocActions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the AllocActions in the graph. <a href="#a025352e474cbac473d4ca121501d0272">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203fbc369cde940f8931da4922b156cb">G</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/allocgroupsmallmap">SegmentMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c28706b8be57c82c7a3008a5cbefb9a">Segments</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout">BasicLayout</a> simplifies the implementation of JITLinkMemoryManagers.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout">BasicLayout</a> groups Sections into Segments based on their memory protection and deallocation policies. JITLinkMemoryManagers can construct a <a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout">BasicLayout</a> from a Graph, and then assign working memory and addresses to each of the Segments. These addreses will be mapped back onto the Graph blocks in the apply method.</p>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### SegmentMap {#aa2e637b4398423ac58812c51bf965c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::BasicLayout::SegmentMap =  orc::AllocGroupSmallMap&lt;Segment&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BasicLayout() {#af3fa75b45aafa6c528042df53446d8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::BasicLayout::BasicLayout (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### apply() {#ac6118016e682bb76a031f3857dc3627f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::BasicLayout::apply ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the layout to the graph.</p>

<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a55d344744db3064ded4e8706e28110e1">llvm::jitlink::alignToBlock</a>, <a href="#ac6118016e682bb76a031f3857dc3627f">apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ac6118016e682bb76a031f3857dc3627f">apply</a>.</p>

</div>
</div>

### getContiguousPageBasedLayoutSizes() {#adbd4dbd21630dedd3eac2bf9c6932a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; BasicLayout::ContiguousPageBasedLayoutSizes &gt; llvm::jitlink::BasicLayout::getContiguousPageBasedLayoutSizes (uint64_t PageSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the total number of required to allocate all segments (with each segment padded out to page size) for all standard segments, and all finalize segments.</p>


<p>This is a convenience function for the common case where the segments will be allocated contiguously.</p>


<p>This function will return an error if any segment has an alignment that is higher than a page.</p>


<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/basiclayout/contiguouspagebasedlayoutsizes/#a440fa7e03f2c1ba7ba957a5900739f55">llvm::jitlink::BasicLayout::ContiguousPageBasedLayoutSizes::FinalizeSegs</a>, <a href="#adbd4dbd21630dedd3eac2bf9c6932a88">getContiguousPageBasedLayoutSizes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a>, <a href="#ae7f0db658acaeff82c1f097f5dde15e4">segments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abdd6ae2070338087f3d5d54200d708d6aeb6d8ae6f20283755b339c0dc273988b">llvm::orc::Standard</a> and <a href="/web-llvm/docs/api/structs/llvm/jitlink/basiclayout/contiguouspagebasedlayoutsizes/#afa977ceaa4668bc11669c3d849fba617">llvm::jitlink::BasicLayout::ContiguousPageBasedLayoutSizes::StandardSegs</a>.</p>


<p>Referenced by <a href="#adbd4dbd21630dedd3eac2bf9c6932a88">getContiguousPageBasedLayoutSizes</a>.</p>

</div>
</div>

### getGraph() {#a198fecf47eeb21d990c10a372527df12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraph &amp; llvm::jitlink::BasicLayout::getGraph ()</td>
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

<p>Return a reference to the graph this allocation was created from.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### graphAllocActions() {#a025352e474cbac473d4ca121501d0272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::shared::AllocActions &amp; llvm::jitlink::BasicLayout::graphAllocActions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a reference to the AllocActions in the graph.</p>


<p>This convenience function saves callers from having to #include LinkGraph.h if all they need are allocation actions.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>


<p>Reference <a href="#a025352e474cbac473d4ca121501d0272">graphAllocActions</a>.</p>


<p>Referenced by <a href="#a025352e474cbac473d4ca121501d0272">graphAllocActions</a>.</p>

</div>
</div>

### segments() {#ae7f0db658acaeff82c1f097f5dde15e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SegmentMap::iterator &gt; llvm::jitlink::BasicLayout::segments ()</td>
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

<p>Returns an iterator over the segments of the layout.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>


<p>Referenced by <a href="#adbd4dbd21630dedd3eac2bf9c6932a88">getContiguousPageBasedLayoutSizes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### G {#a203fbc369cde940f8931da4922b156cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraph&amp; llvm::jitlink::BasicLayout::G</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### Segments {#a1c28706b8be57c82c7a3008a5cbefb9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SegmentMap llvm::jitlink::BasicLayout::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
