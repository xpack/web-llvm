---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/memory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Memory` Class

<p>This class provides various memory handling functions that manipulate <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> instances. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::Memory { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">llvm/Support/Memory.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProtectionFlags { <a href="#a548f317b89dc0bba738b89e5ce791395">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1326dd13b23711e68ade413fbc57b9f6">allocateMappedMemory</a> (size_t NumBytes, const MemoryBlock *const NearBlock, unsigned Flags, std::error_code &amp;EC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method allocates a block of memory that is suitable for loading dynamically generated code (e.g. <a href="#a1326dd13b23711e68ade413fbc57b9f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042d24349a4b6a5ce475309cce529ae0">releaseMappedMemory</a> (MemoryBlock &amp;Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method releases a block of memory that was allocated with the allocateMappedMemory method. <a href="#a042d24349a4b6a5ce475309cce529ae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27409ddee7e191f33392283ca826703">protectMappedMemory</a> (const MemoryBlock &amp;Block, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method sets the protection flags for a block of memory to the state specified by /p Flags. <a href="#ae27409ddee7e191f33392283ca826703">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfd4d2a8227a3f9ca0667f42f05f20b">InvalidateInstructionCache</a> (const void *Addr, size_t Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InvalidateInstructionCache - Before the JIT can run a block of code that has been emitted it must invalidate the instruction cache on some platforms. <a href="#a5cfd4d2a8227a3f9ca0667f42f05f20b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class provides various memory handling functions that manipulate <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> instances.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>1.4 An abstraction for memory operations.</p></dd>
</dl>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">Memory.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ProtectionFlags {#a548f317b89dc0bba738b89e5ce791395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::sys::Memory::ProtectionFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MF_READ<a id="a548f317b89dc0bba738b89e5ce791395a02cae455b05abf1bfb1de69095e66417"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MF_WRITE<a id="a548f317b89dc0bba738b89e5ce791395a83e34a8267f7acd88563e9d5a3ee7c25"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MF_EXEC<a id="a548f317b89dc0bba738b89e5ce791395a72200d7026f0978efe86fc34f4cba76e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MF_RWE_MASK<a id="a548f317b89dc0bba738b89e5ce791395a04baa4ca0e4ca865eba075daf1e551f3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MF_HUGE_HINT<a id="a548f317b89dc0bba738b89e5ce791395a1f8e817d37e6406698e099531487e3db"></a></td>
<td class="doxyEnumItemDescription">The <span class="doxyComputerOutput">MF_HUGE_HINT</span> flag is used to indicate that the request for a memory block should be satisfied with large pages if possible (= 0x0000001)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">Memory.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### allocateMappedMemory() {#a1326dd13b23711e68ade413fbc57b9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBlock llvm::sys::Memory::allocateMappedMemory (size_t NumBytes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NearBlock, unsigned Flags, std::error_code &amp; EC)</td>
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

<p>This method allocates a block of memory that is suitable for loading dynamically generated code (e.g.</p>


<p>JIT). An attempt to allocate <span class="doxyComputerOutput">NumBytes</span> bytes of virtual memory is made. <span class="doxyComputerOutput">NearBlock</span> may point to an existing allocation in which case an attempt is made to allocate more memory near the existing block. The actual allocated address is not guaranteed to be near the requested address. <span class="doxyComputerOutput">Flags</span> is used to set the initial protection flags for the block of the memory. <span class="doxyComputerOutput">EC</span> [out] returns an object describing any error that occurs.</p>


<p>This method may allocate more than the number of bytes requested. The actual number of bytes allocated is indicated in the returned <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a>.</p>


<p>The start of the allocated block must be aligned with the system allocation granularity (64K on Windows, page size on Linux). If the address following <span class="doxyComputerOutput">NearBlock</span> is not so aligned, it will be rounded up to the next allocation granularity boundary.</p>


<p>\r a non-null <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> if the function was successful, otherwise a null <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> is with <span class="doxyComputerOutput">EC</span> describing the error.</p>


<p>Allocate mapped memory.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">Memory.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/#a9f8e852fe43d6fd7d73092c820f89981">llvm::jitlink::InProcessMemoryManager::allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a71f5d58b4df8b116ebda816fd6b29a61">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-sectionmemorymanager-cpp-/defaultmmapper/#ae4e4ae90301d45b22f7c283d13a2e832">llvm::anonymous{SectionMemoryManager.cpp}::DefaultMMapper::allocateMappedMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsinfo/#ae74fd50627af3f80c098c4d8737c846d">llvm::orc::LocalIndirectStubsInfo&lt; ORCABI &gt;::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp/#ab567e593dcf755d782527311e9b300fa">createInMemoryBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a7567e026468fa261fb6186a2d30115ff">llvm::orc::InProcessMemoryMapper::reserve</a>.</p>

</div>
</div>

### InvalidateInstructionCache() {#a5cfd4d2a8227a3f9ca0667f42f05f20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::Memory::InvalidateInstructionCache (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Addr, size_t Len)</td>
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

<p>InvalidateInstructionCache - Before the JIT can run a block of code that has been emitted it must invalidate the instruction cache on some platforms.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">Memory.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a492e4d6b2bf660e7c499e22f85b72440">llvm::orc::InProcessMemoryMapper::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#af7f72f04af2ffe1b66adfecb7f881b02">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager/#a64835973f93c4f018aa377870e15ee97">llvm::SectionMemoryManager::invalidateInstructionCache</a>.</p>

</div>
</div>

### protectMappedMemory() {#ae27409ddee7e191f33392283ca826703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sys::Memory::protectMappedMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> &amp; Block, unsigned Flags)</td>
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

<p>This method sets the protection flags for a block of memory to the state specified by /p Flags.</p>


<p>The behavior is not specified if the memory was not allocated using the allocateMappedMemory method. <span class="doxyComputerOutput">Block</span> describes the memory block to be protected. <span class="doxyComputerOutput">Flags</span> specifies the new protection state to be assigned to the block.</p>


<p>If <span class="doxyComputerOutput">Flags</span> is MF_WRITE, the actual behavior varies with the operating system (i.e. MF_READ | MF_WRITE on Windows) and the target architecture (i.e. MF_WRITE -&gt; MF_READ | MF_WRITE on i386).</p>


<p>\r error_success if the function was successful, or an error_code describing the failure if an error occurred.</p>


<p>Set memory protection state.</p>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">Memory.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsinfo/#ae74fd50627af3f80c098c4d8737c846d">llvm::orc::LocalIndirectStubsInfo&lt; ORCABI &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#ac501a4fc8b8826d6451a9ae117ca3e0b">llvm::orc::InProcessMemoryMapper::deinitialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a492e4d6b2bf660e7c499e22f85b72440">llvm::orc::InProcessMemoryMapper::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-sectionmemorymanager-cpp-/defaultmmapper/#a7f9c28a81a61c5f292d14dbd7a9b2766">llvm::anonymous{SectionMemoryManager.cpp}::DefaultMMapper::protectMappedMemory</a>.</p>

</div>
</div>

### releaseMappedMemory() {#a042d24349a4b6a5ce475309cce529ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sys::Memory::releaseMappedMemory (<a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> &amp; Block)</td>
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

<p>This method releases a block of memory that was allocated with the allocateMappedMemory method.</p>


<p>It should not be used to release any memory block allocated any other way. <span class="doxyComputerOutput">Block</span> describes the memory to be released.</p>


<p>\r error_success if the function was successful, or an error_code describing the failure if an error occurred.</p>


<p>Release mapped memory.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">Memory.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/ipinflightalloc/#a2306347d88aa77c28391f5ab7c0585f1">llvm::jitlink::InProcessMemoryManager::IPInFlightAlloc::abandon</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/#a5599aaf8c94c775d12080e3401796fd2">llvm::jitlink::InProcessMemoryManager::deallocate</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/ipinflightalloc/#aff3f5ff953c804874134986a08d84cec">llvm::jitlink::InProcessMemoryManager::IPInFlightAlloc::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#ae7b7c908c1016860ed8c53965f8f167a">llvm::orc::InProcessMemoryMapper::release</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/owningmemoryblock/#af7a38c875a7d4a357b3091ffe97a3bde">llvm::sys::OwningMemoryBlock::release</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-sectionmemorymanager-cpp-/defaultmmapper/#abe6722b1a014fa1278361232a6a8ccc1">llvm::anonymous{SectionMemoryManager.cpp}::DefaultMMapper::releaseMappedMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/owningmemoryblock/#aa88884bb3af957b96bab31e1ebe8f1d9">llvm::sys::OwningMemoryBlock::~OwningMemoryBlock</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">Memory.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
