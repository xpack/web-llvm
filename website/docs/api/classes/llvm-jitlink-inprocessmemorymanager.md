---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/inprocessmemorymanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InProcessMemoryManager` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> that allocates in-process memory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::InProcessMemoryManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">llvm/ExecutionEngine/JITLink/JITLinkMemoryManager.h</a>"
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea18d073433e3ab5a2e05383beee681">InProcessMemoryManager</a> (uint64_t PageSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance using the given page size. <a href="#acea18d073433e3ab5a2e05383beee681">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f8e852fe43d6fd7d73092c820f89981">allocate</a> (const JITLinkDylib *JD, LinkGraph &amp;G, OnAllocatedFunction OnAllocated) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start the allocation process. <a href="#a9f8e852fe43d6fd7d73092c820f89981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5599aaf8c94c775d12080e3401796fd2">deallocate</a> (std::vector&lt; FinalizedAlloc &gt; Alloc, OnDeallocatedFunction OnDeallocated) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate a list of allocation objects. <a href="#a5599aaf8c94c775d12080e3401796fd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#aa2136b4624343f68668753cdb4122aab">AllocResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e12d4f3354f57e1f559b994e2bdd23c">allocate</a> (const JITLinkDylib *JD, LinkGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for blocking allocation. <a href="#a1e12d4f3354f57e1f559b994e2bdd23c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f254cde6a8b332bb4621e150832db1">deallocate</a> (FinalizedAlloc Alloc, OnDeallocatedFunction OnDeallocated)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for deallocation of a single alloc. <a href="#a23f254cde6a8b332bb4621e150832db1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f33899da0fe62dd01fd45313157ccb">deallocate</a> (std::vector&lt; FinalizedAlloc &gt; Allocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for blocking deallocation. <a href="#a66f33899da0fe62dd01fd45313157ccb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c6622ac0f4f231ff10c4ef5729743c">deallocate</a> (FinalizedAlloc Alloc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for blocking deallocation of a single alloc. <a href="#a60c6622ac0f4f231ff10c4ef5729743c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa5c9ec376f5aea86b403e74fc3a1be">createFinalizedAlloc</a> (sys::MemoryBlock StandardSegments, std::vector&lt; orc::shared::WrapperFunctionCall &gt; DeallocActions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a2d0442d704206ded2ae353998deed">PageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4943b9f5e70e6fa81fc6811f42b2417">FinalizedAllocsMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recyclingallocator">RecyclingAllocator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a>, FinalizedAllocInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7851c7001f471568088f503f423797ec">FinalizedAllocInfos</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager">InProcessMemoryManager</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4033076ae4631e6acd10a0d94e8307d1">Create</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to auto-detect the host page size. <a href="#a4033076ae4631e6acd10a0d94e8307d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> that allocates in-process memory.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InProcessMemoryManager() {#acea18d073433e3ab5a2e05383beee681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::InProcessMemoryManager::InProcessMemoryManager (uint64_t PageSize)</td>
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

<p>Create an instance using the given page size.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/ipinflightalloc/#ace304cf438c0e5ea82ef13a1fc01e310">llvm::jitlink::InProcessMemoryManager::IPInFlightAlloc::IPInFlightAlloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocate() {#a9f8e852fe43d6fd7d73092c820f89981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::InProcessMemoryManager::allocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> * JD, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a80d1ed0619748c7b87067a81109943bd">OnAllocatedFunction</a> OnAllocated)</td>
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


<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock/#a60a5600193f728ca1a0bcc9be953b158">llvm::sys::MemoryBlock::allocatedSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a1326dd13b23711e68ade413fbc57b9f6">llvm::sys::Memory::allocateMappedMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock/#a334b65a8b14eb0f90d3eb7c368ee07b2">llvm::sys::MemoryBlock::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a02cae455b05abf1bfb1de69095e66417">llvm::sys::Memory::MF_READ</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a83e34a8267f7acd88563e9d5a3ee7c25">llvm::sys::Memory::MF_WRITE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abdd6ae2070338087f3d5d54200d708d6aeb6d8ae6f20283755b339c0dc273988b">llvm::orc::Standard</a>.</p>

</div>
</div>

### allocate() {#a1e12d4f3354f57e1f559b994e2bdd23c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocResult llvm::jitlink::JITLinkMemoryManager::allocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> * JD, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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

<p>Convenience function for blocking allocation.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### deallocate() {#a5599aaf8c94c775d12080e3401796fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::InProcessMemoryManager::deallocate (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt; Allocs, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a8891e6f8e95eeb639c2b15036283bab1">OnDeallocatedFunction</a> OnDeallocated)</td>
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


<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a042d24349a4b6a5ce475309cce529ae0">llvm::sys::Memory::releaseMappedMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### deallocate() {#a23f254cde6a8b332bb4621e150832db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::JITLinkMemoryManager::deallocate (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> Alloc, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a8891e6f8e95eeb639c2b15036283bab1">OnDeallocatedFunction</a> OnDeallocated)</td>
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

<p>Convenience function for deallocation of a single alloc.</p>

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### deallocate() {#a66f33899da0fe62dd01fd45313157ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::JITLinkMemoryManager::deallocate (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt; Allocs)</td>
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

<p>Convenience function for blocking deallocation.</p>

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### deallocate() {#a60c6622ac0f4f231ff10c4ef5729743c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::JITLinkMemoryManager::deallocate (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> Alloc)</td>
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

<p>Convenience function for blocking deallocation of a single alloc.</p>

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createFinalizedAlloc() {#adaa5c9ec376f5aea86b403e74fc3a1be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITLinkMemoryManager::FinalizedAlloc llvm::jitlink::InProcessMemoryManager::createFinalizedAlloc (<a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a> StandardSegments, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">orc::shared::WrapperFunctionCall</a> &gt; DeallocActions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FinalizedAllocInfos {#a7851c7001f471568088f503f423797ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecyclingAllocator&lt;BumpPtrAllocator, FinalizedAllocInfo&gt; llvm::jitlink::InProcessMemoryManager::FinalizedAllocInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### FinalizedAllocsMutex {#ae4943b9f5e70e6fa81fc6811f42b2417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::jitlink::InProcessMemoryManager::FinalizedAllocsMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

### PageSize {#a40a2d0442d704206ded2ae353998deed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::InProcessMemoryManager::PageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a4033076ae4631e6acd10a0d94e8307d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InProcessMemoryManager &gt; &gt; llvm::jitlink::InProcessMemoryManager::Create ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to auto-detect the host page size.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlinkmemorymanager-h">JITLinkMemoryManager.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlinkmemorymanager-cpp">JITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a2b6f374dc4eb2a7f84cc346e5630e132">llvm::sys::Process::getPageSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
