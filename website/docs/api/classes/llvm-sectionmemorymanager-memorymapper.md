---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sectionmemorymanager/memorymapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemoryMapper` Class Reference

<p>Implementations of this interface are used by <a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager">SectionMemoryManager</a> to request pages from the operating system. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SectionMemoryManager::MemoryMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/sectionmemorymanager-h">llvm/ExecutionEngine/SectionMemoryManager.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-sectionmemorymanager-cpp-/defaultmmapper">DefaultMMapper</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d89f052a2a35640380e0f5e13c770c8">~MemoryMapper</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde0a4f446b881cf0417f861d025066f">allocateMappedMemory</a> (AllocationPurpose Purpose, size_t NumBytes, const sys::MemoryBlock *const NearBlock, unsigned Flags, std::error_code &amp;EC)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method attempts to allocate <span class="doxyComputerOutput">NumBytes</span> bytes of virtual memory for <span class="doxyComputerOutput">Purpose</span>. <a href="#adde0a4f446b881cf0417f861d025066f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7f6733e8af2f2911c2ff4832b5d693">protectMappedMemory</a> (const sys::MemoryBlock &amp;Block, unsigned Flags)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method sets the protection flags for a block of memory to the state specified by <span class="doxyComputerOutput">Flags</span>. <a href="#a1f7f6733e8af2f2911c2ff4832b5d693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae2a1c0635ac55f4ca9fc83bb46463ac">releaseMappedMemory</a> (sys::MemoryBlock &amp;M)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method releases a block of memory that was allocated with the allocateMappedMemory method. <a href="#aae2a1c0635ac55f4ca9fc83bb46463ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Implementations of this interface are used by <a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager">SectionMemoryManager</a> to request pages from the operating system.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/sectionmemorymanager-h">SectionMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~MemoryMapper() {#a4d89f052a2a35640380e0f5e13c770c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SectionMemoryManager::MemoryMapper::~MemoryMapper ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/sectionmemorymanager-h">SectionMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocateMappedMemory() {#adde0a4f446b881cf0417f861d025066f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual sys::MemoryBlock llvm::SectionMemoryManager::MemoryMapper::allocateMappedMemory (<a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager/#a0cdbe52ddf56f7c9188174848e9423a4">AllocationPurpose</a> Purpose, size_t NumBytes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NearBlock, unsigned Flags, std::error_code &amp; EC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method attempts to allocate <span class="doxyComputerOutput">NumBytes</span> bytes of virtual memory for <span class="doxyComputerOutput">Purpose</span>.</p>


<p><span class="doxyComputerOutput">NearBlock</span> may point to an existing allocation, in which case an attempt is made to allocate more memory near the existing block. The actual allocated address is not guaranteed to be near the requested address. <span class="doxyComputerOutput">Flags</span> is used to set the initial protection flags for the block of the memory. <span class="doxyComputerOutput">EC</span> [out] returns an object describing any error that occurs.</p>


<p>This method may allocate more than the number of bytes requested. The actual number of bytes allocated is indicated in the returned <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a>.</p>


<p>The start of the allocated block must be aligned with the system allocation granularity (64K on Windows, page size on Linux). If the address following <span class="doxyComputerOutput">NearBlock</span> is not so aligned, it will be rounded up to the next allocation granularity boundary.</p>


<p>\r a non-null <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> if the function was successful, otherwise a null <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> with <span class="doxyComputerOutput">EC</span> describing the error.</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/sectionmemorymanager-h">SectionMemoryManager.h</a>.</p>

</div>
</div>

### protectMappedMemory() {#a1f7f6733e8af2f2911c2ff4832b5d693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::SectionMemoryManager::MemoryMapper::protectMappedMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a> &amp; Block, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method sets the protection flags for a block of memory to the state specified by <span class="doxyComputerOutput">Flags</span>.</p>


<p>The behavior is not specified if the memory was not allocated using the allocateMappedMemory method. <span class="doxyComputerOutput">Block</span> describes the memory block to be protected. <span class="doxyComputerOutput">Flags</span> specifies the new protection state to be assigned to the block.</p>


<p>If <span class="doxyComputerOutput">Flags</span> is MF_WRITE, the actual behavior varies with the operating system (i.e. MF_READ | MF_WRITE on Windows) and the target architecture (i.e. MF_WRITE -&gt; MF_READ | MF_WRITE on i386).</p>


<p>\r error_success if the function was successful, or an error_code describing the failure if an error occurred.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/sectionmemorymanager-h">SectionMemoryManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>.</p>

</div>
</div>

### releaseMappedMemory() {#aae2a1c0635ac55f4ca9fc83bb46463ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::SectionMemoryManager::MemoryMapper::releaseMappedMemory (<a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method releases a block of memory that was allocated with the allocateMappedMemory method.</p>


<p>It should not be used to release any memory block allocated any other way. <span class="doxyComputerOutput">Block</span> describes the memory to be released.</p>


<p>\r error_success if the function was successful, or an error_code describing the failure if an error occurred.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/sectionmemorymanager-h">SectionMemoryManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/sectionmemorymanager-h">SectionMemoryManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
