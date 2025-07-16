---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/mapperjitlinkmemorymanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MapperJITLinkMemoryManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::MapperJITLinkMemoryManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">llvm/ExecutionEngine/Orc/MapperJITLinkMemoryManager.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Manages allocations of JIT memory. <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae02dd845c5c239b6b53928a5a734b37">AvailableMemoryMap</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8af341940c4fd14e1e43490ba2af1da1">MapperJITLinkMemoryManager</a> (size_t ReservationGranularity, std::unique_ptr&lt; MemoryMapper &gt; Mapper)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af90b0682d3c07f33a625349305a4be61">allocate</a> (const jitlink::JITLinkDylib *JD, jitlink::LinkGraph &amp;G, OnAllocatedFunction OnAllocated) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start the allocation process. <a href="#af90b0682d3c07f33a625349305a4be61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16536e0ae009cb70f4440f6877828693">deallocate</a> (std::vector&lt; FinalizedAlloc &gt; Allocs, OnDeallocatedFunction OnDeallocated) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate a list of allocation objects. <a href="#a16536e0ae009cb70f4440f6877828693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa635bd971ac0110d4b4a57e0eb0552db">Mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3eaa0474038d9deb20e77dbce142f1">ReservationUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a6b645fcc5ae44b9a8e2fef275890ae4b">AvailableMemoryMap::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e315702a3aa92d15e91c3d718fd3757">AMAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab890c1cfba62265faca5260557d8b642">AvailableMemory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">ExecutorAddrDiff</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c98355a990803dd633c508c355dfb5b">UsedMemory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper">MemoryMapper</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e531749c41c3f2499222bccdef2cab">Mapper</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class MemoryMapperType, class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a407a61cd317e5738a1f65807f7e4cb5c">CreateWithMapper</a> (size_t ReservationGranularity, Args &amp;&amp;...A) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager">MapperJITLinkMemoryManager</a> &gt; &gt;</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AvailableMemoryMap {#aae02dd845c5c239b6b53928a5a734b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MapperJITLinkMemoryManager::AvailableMemoryMap =  IntervalMap&lt;ExecutorAddr, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MapperJITLinkMemoryManager() {#a8af341940c4fd14e1e43490ba2af1da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MapperJITLinkMemoryManager::MapperJITLinkMemoryManager (size_t ReservationGranularity, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper">MemoryMapper</a> &gt; Mapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager/inflightalloc/#a2bf0f3f3b1bea06f498f4cf21fe9f601">llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::InFlightAlloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocate() {#af90b0682d3c07f33a625349305a4be61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MapperJITLinkMemoryManager::allocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">jitlink::JITLinkDylib</a> * JD, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a80d1ed0619748c7b87067a81109943bd">OnAllocatedFunction</a> OnAllocated)</td>
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

<p>Start the allocation process.</p>


<p>If the initial allocation is successful then the OnAllocated function will be called with a std::unique_ptr&lt;InFlightAlloc&gt; value. If the assocation is unsuccessful then the OnAllocated function will be called with an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>.</p>


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange/#a1499cfc155304deba85e0ef92ede92f4">llvm::orc::ExecutorAddrRange::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>

</div>
</div>

### deallocate() {#a16536e0ae009cb70f4440f6877828693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MapperJITLinkMemoryManager::deallocate (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt; Allocs, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a8891e6f8e95eeb639c2b15036283bab1">OnDeallocatedFunction</a> OnDeallocated)</td>
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

<p>Deallocate a list of allocation objects.</p>


<p>Dealloc actions will be run in reverse order (from the end of the vector to the start).</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AMAllocator {#a4e315702a3aa92d15e91c3d718fd3757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableMemoryMap::Allocator llvm::orc::MapperJITLinkMemoryManager::AMAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>

</div>
</div>

### AvailableMemory {#ab890c1cfba62265faca5260557d8b642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMap&lt;ExecutorAddr, bool&gt; llvm::orc::MapperJITLinkMemoryManager::AvailableMemory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>

</div>
</div>

### Mapper {#a82e531749c41c3f2499222bccdef2cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryMapper&gt; llvm::orc::MapperJITLinkMemoryManager::Mapper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>

</div>
</div>

### Mutex {#aa635bd971ac0110d4b4a57e0eb0552db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::MapperJITLinkMemoryManager::Mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>

</div>
</div>

### ReservationUnits {#aff3eaa0474038d9deb20e77dbce142f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::MapperJITLinkMemoryManager::ReservationUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>

</div>
</div>

### UsedMemory {#a9c98355a990803dd633c508c355dfb5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExecutorAddr, ExecutorAddrDiff&gt; llvm::orc::MapperJITLinkMemoryManager::UsedMemory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateWithMapper() {#a407a61cd317e5738a1f65807f7e4cb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class MemoryMapperType, class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MapperJITLinkMemoryManager &gt; &gt; llvm::orc::MapperJITLinkMemoryManager::CreateWithMapper (size_t ReservationGranularity, Args &amp;&amp;... A)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mapperjitlinkmemorymanager-h">MapperJITLinkMemoryManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mapperjitlinkmemorymanager-cpp">MapperJITLinkMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
