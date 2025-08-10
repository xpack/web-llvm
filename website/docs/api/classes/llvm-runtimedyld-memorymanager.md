---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyld/memorymanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemoryManager` Class

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Management. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyld::MemoryManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">llvm/ExecutionEngine/RuntimeDyld.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager">MCJITMemoryManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remote-mapped RuntimeDyld-compatible memory manager. <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb53f44bd8403ff24cbf2fe93c004935">RuntimeDyld</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11fcc23e1236167e9335a635772fa9c1">MemoryManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926f7c6e1cd73838fc19eecf5e169348">~MemoryManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa63dd49bc491d2da811c84dd9b4c0e">allocateCodeSection</a> (uintptr_t Size, unsigned Alignment, unsigned SectionID, StringRef SectionName)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of (at least) the given size suitable for executable code. <a href="#aaaa63dd49bc491d2da811c84dd9b4c0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762c2ef812ed069620da3bba0e65bba5">allocateDataSection</a> (uintptr_t Size, unsigned Alignment, unsigned SectionID, StringRef SectionName, bool IsReadOnly)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of (at least) the given size suitable for data. <a href="#a762c2ef812ed069620da3bba0e65bba5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/runtimedyld/memorymanager/tlssection">TLSSection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912b68c8deb0c59194e0e1c99f3d3438">allocateTLSSection</a> (uintptr_t Size, unsigned Alignment, unsigned SectionID, StringRef SectionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of (at least) the given size to be used for thread-local storage (TLS). <a href="#a912b68c8deb0c59194e0e1c99f3d3438">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10401be6f4a60bfb003221c8976049ce">reserveAllocationSpace</a> (uintptr_t CodeSize, Align CodeAlign, uintptr_t RODataSize, Align RODataAlign, uintptr_t RWDataSize, Align RWDataAlign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the memory manager about the total amount of memory required to allocate all sections to be loaded: <span class="doxyComputerOutput">CodeSize</span> - the total size of all code sections <span class="doxyComputerOutput">DataSizeRO</span> - the total size of all read-only data sections <span class="doxyComputerOutput">DataSizeRW</span> - the total size of all read-write data sections. <a href="#a10401be6f4a60bfb003221c8976049ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141903e7bb948a4214fc0f74f94eb231">needsToReserveAllocationSpace</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override to return true to enable the reserveAllocationSpace callback. <a href="#a141903e7bb948a4214fc0f74f94eb231">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae51ee7c626f5408381f946809f534313">allowStubAllocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override to return false to tell LLVM no stub space will be needed. <a href="#ae51ee7c626f5408381f946809f534313">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0234bb22e2af160137c5ea5df0843c1">registerEHFrames</a> (uint8_t *Addr, uint64_t LoadAddr, size_t Size)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the EH frames with the runtime so that c++ exceptions work. <a href="#ad0234bb22e2af160137c5ea5df0843c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf91ad2a1e825696e27be105941b03e1">deregisterEHFrames</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd33e61ef93ebdd7c7b40c62f43f71b3">finalizeMemory</a> (std::string *ErrMsg=nullptr)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called when object loading is complete and section page permissions can be applied. <a href="#abd33e61ef93ebdd7c7b40c62f43f71b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756f07a293e917107262ff4ee2bb64e0">notifyObjectLoaded</a> (RuntimeDyld &amp;RTDyld, const object::ObjectFile &amp;Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called after an object has been loaded into memory but before relocations are applied to the loaded sections. <a href="#a756f07a293e917107262ff4ee2bb64e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f02282939f7965ab6bf8673c78e30f">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b624061500506b26ddb02f527db1256">FinalizationLocked</a> = false</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Management.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<div class="doxySectionDef">

## Friends

### RuntimeDyld {#aeb53f44bd8403ff24cbf2fe93c004935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="#aeb53f44bd8403ff24cbf2fe93c004935">RuntimeDyld</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#aa42b4fb322847e9ed79832fc94be6016">llvm::orc::EPCGenericRTDyldMemoryManager::notifyObjectLoaded</a>, <a href="#a756f07a293e917107262ff4ee2bb64e0">notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#aba86ba8da8f58989301105fa012979da">llvm::orc::EPCGenericRTDyldMemoryManager::operator=</a> and <a href="#aeb53f44bd8403ff24cbf2fe93c004935">RuntimeDyld</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryManager() {#a11fcc23e1236167e9335a635772fa9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyld::MemoryManager::MemoryManager ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MemoryManager() {#a926f7c6e1cd73838fc19eecf5e169348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::RuntimeDyld::MemoryManager::~MemoryManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocateCodeSection() {#aaaa63dd49bc491d2da811c84dd9b4c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint8_t * llvm::RuntimeDyld::MemoryManager::allocateCodeSection (uintptr_t Size, unsigned Alignment, unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a memory block of (at least) the given size suitable for executable code.</p>


<p>The SectionID is a unique identifier assigned by the <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance, and optionally recorded by the memory manager to access a loaded section.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#ga4aaa19f070d761e54fee2069127e8ee0">LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks</a>.</p>

</div>
</div>

### allocateDataSection() {#a762c2ef812ed069620da3bba0e65bba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint8_t * llvm::RuntimeDyld::MemoryManager::allocateDataSection (uintptr_t Size, unsigned Alignment, unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, bool IsReadOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a memory block of (at least) the given size suitable for data.</p>


<p>The SectionID is a unique identifier assigned by the JIT engine, and optionally recorded by the memory manager to access a loaded section.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#ga4aaa19f070d761e54fee2069127e8ee0">LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks</a>.</p>

</div>
</div>

### allocateTLSSection() {#a912b68c8deb0c59194e0e1c99f3d3438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyld::MemoryManager::TLSSection llvm::RuntimeDyld::MemoryManager::allocateTLSSection (uintptr_t Size, unsigned Alignment, unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
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

<p>Allocate a memory block of (at least) the given size to be used for thread-local storage (TLS).</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1298 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### allowStubAllocation() {#ae51ee7c626f5408381f946809f534313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RuntimeDyld::MemoryManager::allowStubAllocation ()</td>
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

<p>Override to return false to tell LLVM no stub space will be needed.</p>


<p>This requires some guarantees depending on architecuture, but when you know what you are doing it saves allocated space.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### deregisterEHFrames() {#aaf91ad2a1e825696e27be105941b03e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RuntimeDyld::MemoryManager::deregisterEHFrames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### finalizeMemory() {#abd33e61ef93ebdd7c7b40c62f43f71b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RuntimeDyld::MemoryManager::finalizeMemory (std::string * ErrMsg=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called when object loading is complete and section page permissions can be applied.</p>


<p>It is up to the memory manager implementation to decide whether or not to act on this method. The memory manager will typically allocate all sections as read-write and then apply specific permissions when this method is called. Code sections cannot be executed until this function has been called. In addition, any cache coherency operations needed to reliably use the memory are also performed.</p>


<p>Returns true if an error occurred, false otherwise.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#ga4aaa19f070d761e54fee2069127e8ee0">LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks</a>.</p>

</div>
</div>

### needsToReserveAllocationSpace() {#a141903e7bb948a4214fc0f74f94eb231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RuntimeDyld::MemoryManager::needsToReserveAllocationSpace ()</td>
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

<p>Override to return true to enable the reserveAllocationSpace callback.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### notifyObjectLoaded() {#a756f07a293e917107262ff4ee2bb64e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RuntimeDyld::MemoryManager::notifyObjectLoaded (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> &amp; RTDyld, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
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

<p>This method is called after an object has been loaded into memory but before relocations are applied to the loaded sections.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> managers which are preparing code for execution in an external address space can use this call to remap the section addresses for the newly loaded object.</p>


<p>For clients that do not need access to an <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> instance this method should be preferred to its cousin <a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager/#a20044c6b32c19b606470dba740867e18">MCJITMemoryManager::notifyObjectLoaded</a> as this method is compatible with ORC JIT stacks.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="#aeb53f44bd8403ff24cbf2fe93c004935">RuntimeDyld</a>.</p>

</div>
</div>

### registerEHFrames() {#ad0234bb22e2af160137c5ea5df0843c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RuntimeDyld::MemoryManager::registerEHFrames (uint8_t * Addr, uint64_t LoadAddr, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the EH frames with the runtime so that c++ exceptions work.</p>


<p><span class="doxyComputerOutput">Addr</span> parameter provides the local address of the EH frame section data, while <span class="doxyComputerOutput">LoadAddr</span> provides the address of the data in the target address space. If the section has not been remapped (which will usually be the case for local execution) these two values will be the same.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### reserveAllocationSpace() {#a10401be6f4a60bfb003221c8976049ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RuntimeDyld::MemoryManager::reserveAllocationSpace (uintptr_t CodeSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> CodeAlign, uintptr_t RODataSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> RODataAlign, uintptr_t RWDataSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> RWDataAlign)</td>
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

<p>Inform the memory manager about the total amount of memory required to allocate all sections to be loaded: <span class="doxyComputerOutput">CodeSize</span> - the total size of all code sections <span class="doxyComputerOutput">DataSizeRO</span> - the total size of all read-only data sections <span class="doxyComputerOutput">DataSizeRW</span> - the total size of all read-write data sections.</p>


<p>Note that by default the callback is disabled. To enable it redefine the method needsToReserveAllocationSpace to return true.</p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a39f02282939f7965ab6bf8673c78e30f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::MemoryManager::anchor ()</td>
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



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1305 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FinalizationLocked {#a6b624061500506b26ddb02f527db1256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyld::MemoryManager::FinalizationLocked = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
