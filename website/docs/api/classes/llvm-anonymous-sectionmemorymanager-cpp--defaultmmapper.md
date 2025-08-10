---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/anonymous-sectionmemorymanager-cpp-/defaultmmapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DefaultMMapper` Class



## Declaration

<div class="doxyDeclaration">
class llvm::anonymous{SectionMemoryManager.cpp}::DefaultMMapper { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager/memorymapper">MemoryMapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this interface are used by <a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager">SectionMemoryManager</a> to request pages from the operating system. <a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager/memorymapper/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e4ae90301d45b22f7c283d13a2e832">allocateMappedMemory</a> (SectionMemoryManager::AllocationPurpose Purpose, size_t NumBytes, const sys::MemoryBlock *const NearBlock, unsigned Flags, std::error_code &amp;EC) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method attempts to allocate <span class="doxyComputerOutput">NumBytes</span> bytes of virtual memory for <span class="doxyComputerOutput">Purpose</span>. <a href="#ae4e4ae90301d45b22f7c283d13a2e832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f9c28a81a61c5f292d14dbd7a9b2766">protectMappedMemory</a> (const sys::MemoryBlock &amp;Block, unsigned Flags) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method sets the protection flags for a block of memory to the state specified by <span class="doxyComputerOutput">Flags</span>. <a href="#a7f9c28a81a61c5f292d14dbd7a9b2766">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6722b1a014fa1278361232a6a8ccc1">releaseMappedMemory</a> (sys::MemoryBlock &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method releases a block of memory that was allocated with the allocateMappedMemory method. <a href="#abe6722b1a014fa1278361232a6a8ccc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/sectionmemorymanager-cpp">SectionMemoryManager.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### allocateMappedMemory() {#ae4e4ae90301d45b22f7c283d13a2e832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::MemoryBlock llvm::anonymous{SectionMemoryManager.cpp}::DefaultMMapper::allocateMappedMemory (<a href="/web-llvm/docs/api/classes/llvm/sectionmemorymanager/#a0cdbe52ddf56f7c9188174848e9423a4">SectionMemoryManager::AllocationPurpose</a> Purpose, size_t NumBytes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NearBlock, unsigned Flags, std::error_code &amp; EC)</td>
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

<p>This method attempts to allocate <span class="doxyComputerOutput">NumBytes</span> bytes of virtual memory for <span class="doxyComputerOutput">Purpose</span>.</p>


<p><span class="doxyComputerOutput">NearBlock</span> may point to an existing allocation, in which case an attempt is made to allocate more memory near the existing block. The actual allocated address is not guaranteed to be near the requested address. <span class="doxyComputerOutput">Flags</span> is used to set the initial protection flags for the block of the memory. <span class="doxyComputerOutput">EC</span> [out] returns an object describing any error that occurs.</p>


<p>This method may allocate more than the number of bytes requested. The actual number of bytes allocated is indicated in the returned <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a>.</p>


<p>The start of the allocated block must be aligned with the system allocation granularity (64K on Windows, page size on Linux). If the address following <span class="doxyComputerOutput">NearBlock</span> is not so aligned, it will be rounded up to the next allocation granularity boundary.</p>


<p>\r a non-null <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> if the function was successful, otherwise a null <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">MemoryBlock</a> with <span class="doxyComputerOutput">EC</span> describing the error.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/sectionmemorymanager-cpp">SectionMemoryManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a1326dd13b23711e68ade413fbc57b9f6">llvm::sys::Memory::allocateMappedMemory</a>.</p>

</div>
</div>

### protectMappedMemory() {#a7f9c28a81a61c5f292d14dbd7a9b2766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::anonymous{SectionMemoryManager.cpp}::DefaultMMapper::protectMappedMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a> &amp; Block, unsigned Flags)</td>
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

<p>This method sets the protection flags for a block of memory to the state specified by <span class="doxyComputerOutput">Flags</span>.</p>


<p>The behavior is not specified if the memory was not allocated using the allocateMappedMemory method. <span class="doxyComputerOutput">Block</span> describes the memory block to be protected. <span class="doxyComputerOutput">Flags</span> specifies the new protection state to be assigned to the block.</p>


<p>If <span class="doxyComputerOutput">Flags</span> is MF_WRITE, the actual behavior varies with the operating system (i.e. MF_READ | MF_WRITE on Windows) and the target architecture (i.e. MF_WRITE -&gt; MF_READ | MF_WRITE on i386).</p>


<p>\r error_success if the function was successful, or an error_code describing the failure if an error occurred.</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/sectionmemorymanager-cpp">SectionMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#ae27409ddee7e191f33392283ca826703">llvm::sys::Memory::protectMappedMemory</a>.</p>

</div>
</div>

### releaseMappedMemory() {#abe6722b1a014fa1278361232a6a8ccc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::anonymous{SectionMemoryManager.cpp}::DefaultMMapper::releaseMappedMemory (<a href="/web-llvm/docs/api/classes/llvm/sys/memoryblock">sys::MemoryBlock</a> &amp; M)</td>
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

<p>This method releases a block of memory that was allocated with the allocateMappedMemory method.</p>


<p>It should not be used to release any memory block allocated any other way. <span class="doxyComputerOutput">Block</span> describes the memory to be released.</p>


<p>\r error_success if the function was successful, or an error_code describing the failure if an error occurred.</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/sectionmemorymanager-cpp">SectionMemoryManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a042d24349a4b6a5ce475309cce529ae0">llvm::sys::Memory::releaseMappedMemory</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/sectionmemorymanager-cpp">SectionMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
