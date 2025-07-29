---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcgenericrtdyldmemorymanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EPCGenericRTDyldMemoryManager` Class

<p>Remote-mapped RuntimeDyld-compatible memory manager. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCGenericRTDyldMemoryManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">llvm/ExecutionEngine/Orc/EPCGenericRTDyldMemoryManager.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">MemoryManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Management. <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54891df581eb69a8f247f83276b198d5">EPCGenericRTDyldMemoryManager</a> (ExecutorProcessControl &amp;EPC, SymbolAddrs SAs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> using the given EPC and symbol addrs. <a href="#a54891df581eb69a8f247f83276b198d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01a50dd9ebc260690faa963fdd8ce45">EPCGenericRTDyldMemoryManager</a> (const EPCGenericRTDyldMemoryManager &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae923cac315ce0f199658520836b727ea">EPCGenericRTDyldMemoryManager</a> (EPCGenericRTDyldMemoryManager &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484cb5a168161b0ae8fe06f025cacfc4">~EPCGenericRTDyldMemoryManager</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1684c3bfffa0e45c4a05893daeaca5c">operator=</a> (const EPCGenericRTDyldMemoryManager &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba86ba8da8f58989301105fa012979da">operator=</a> (EPCGenericRTDyldMemoryManager &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad061fb8659f1733fe5d0cdc941dded41">allocateCodeSection</a> (uintptr_t Size, unsigned Alignment, unsigned SectionID, StringRef SectionName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of (at least) the given size suitable for executable code. <a href="#ad061fb8659f1733fe5d0cdc941dded41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066426b3a4a3a7318049886d4f0e6c70">allocateDataSection</a> (uintptr_t Size, unsigned Alignment, unsigned SectionID, StringRef SectionName, bool IsReadOnly) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of (at least) the given size suitable for data. <a href="#a066426b3a4a3a7318049886d4f0e6c70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fba4cc154f5345cbdc0c32c70f8155c">reserveAllocationSpace</a> (uintptr_t CodeSize, Align CodeAlign, uintptr_t RODataSize, Align RODataAlign, uintptr_t RWDataSize, Align RWDataAlign) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the memory manager about the total amount of memory required to allocate all sections to be loaded: <span class="doxyComputerOutput">CodeSize</span> - the total size of all code sections <span class="doxyComputerOutput">DataSizeRO</span> - the total size of all read-only data sections <span class="doxyComputerOutput">DataSizeRW</span> - the total size of all read-write data sections. <a href="#a7fba4cc154f5345cbdc0c32c70f8155c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243b945941375d1231aed64262c787d9">needsToReserveAllocationSpace</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override to return true to enable the reserveAllocationSpace callback. <a href="#a243b945941375d1231aed64262c787d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83038edc3ba4948f540e15ae36d04098">registerEHFrames</a> (uint8_t *Addr, uint64_t LoadAddr, size_t Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the EH frames with the runtime so that c++ exceptions work. <a href="#a83038edc3ba4948f540e15ae36d04098">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79a52f4bf6d08101166dc7db74c66ce">deregisterEHFrames</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42b4fb322847e9ed79832fc94be6016">notifyObjectLoaded</a> (RuntimeDyld &amp;Dyld, const object::ObjectFile &amp;Obj) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called after an object has been loaded into memory but before relocations are applied to the loaded sections. <a href="#aa42b4fb322847e9ed79832fc94be6016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db7d447f814afaee65a64c0419805dd">finalizeMemory</a> (std::string *ErrMsg=nullptr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called when object loading is complete and section page permissions can be applied. <a href="#a0db7d447f814afaee65a64c0419805dd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d523e00901731edde35f02786e0d5b0">mapAllocsToRemoteAddrs</a> (RuntimeDyld &amp;Dyld, std::vector&lt; SectionAlloc &gt; &amp;SecAllocs, ExecutorAddr NextAddr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38759403b2e8eae32a84069ff890afd1">EPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/epcgenericrtdyldmemorymanager/symboladdrs">SymbolAddrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a342cee080c6547db7a2c7d7fd661fb9a">SAs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1812b18b47c877024b8ebfe6af1cc6ff">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; SectionAllocGroup &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826bb2e13f9b36f884f002d6a861919a">Unmapped</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; SectionAllocGroup &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3937a374a490b5693f4e3b7f66260656">Unfinalized</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf090309fc311c662b02cb6c0c22072f">FinalizedAllocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bbbbf4a4607972feab1a5e9f4abedc">ErrMsg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5055d28d284af499b28f3a649ea33562">CreateWithDefaultBootstrapSymbols</a> (ExecutorProcessControl &amp;EPC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> using the given EPC, looking up the default symbol names in the bootstrap symbol set. <a href="#a5055d28d284af499b28f3a649ea33562">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Remote-mapped RuntimeDyld-compatible memory manager.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EPCGenericRTDyldMemoryManager() {#a54891df581eb69a8f247f83276b198d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCGenericRTDyldMemoryManager::EPCGenericRTDyldMemoryManager (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC, <a href="/web-llvm/docs/api/structs/llvm/orc/epcgenericrtdyldmemorymanager/symboladdrs">SymbolAddrs</a> SAs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> using the given EPC and symbol addrs.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a54891df581eb69a8f247f83276b198d5">EPCGenericRTDyldMemoryManager</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#ae01a50dd9ebc260690faa963fdd8ce45">EPCGenericRTDyldMemoryManager</a>, <a href="#ae923cac315ce0f199658520836b727ea">EPCGenericRTDyldMemoryManager</a>, <a href="#a54891df581eb69a8f247f83276b198d5">EPCGenericRTDyldMemoryManager</a>, <a href="#ae1684c3bfffa0e45c4a05893daeaca5c">operator=</a> and <a href="#aba86ba8da8f58989301105fa012979da">operator=</a>.</p>

</div>
</div>

### EPCGenericRTDyldMemoryManager() {#ae01a50dd9ebc260690faa963fdd8ce45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCGenericRTDyldMemoryManager::EPCGenericRTDyldMemoryManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>


<p>Reference <a href="#a54891df581eb69a8f247f83276b198d5">EPCGenericRTDyldMemoryManager</a>.</p>

</div>
</div>

### EPCGenericRTDyldMemoryManager() {#ae923cac315ce0f199658520836b727ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCGenericRTDyldMemoryManager::EPCGenericRTDyldMemoryManager (<a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>


<p>Reference <a href="#a54891df581eb69a8f247f83276b198d5">EPCGenericRTDyldMemoryManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~EPCGenericRTDyldMemoryManager() {#a484cb5a168161b0ae8fe06f025cacfc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCGenericRTDyldMemoryManager::~EPCGenericRTDyldMemoryManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae1684c3bfffa0e45c4a05893daeaca5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EPCGenericRTDyldMemoryManager &amp; llvm::orc::EPCGenericRTDyldMemoryManager::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>


<p>Reference <a href="#a54891df581eb69a8f247f83276b198d5">EPCGenericRTDyldMemoryManager</a>.</p>

</div>
</div>

### operator=() {#aba86ba8da8f58989301105fa012979da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EPCGenericRTDyldMemoryManager &amp; llvm::orc::EPCGenericRTDyldMemoryManager::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>


<p>References <a href="#a54891df581eb69a8f247f83276b198d5">EPCGenericRTDyldMemoryManager</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager/#aeb53f44bd8403ff24cbf2fe93c004935">llvm::RuntimeDyld::MemoryManager::RuntimeDyld</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocateCodeSection() {#ad061fb8659f1733fe5d0cdc941dded41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * llvm::orc::EPCGenericRTDyldMemoryManager::allocateCodeSection (uintptr_t Size, unsigned Alignment, unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
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

<p>Allocate a memory block of (at least) the given size suitable for executable code.</p>


<p>The SectionID is a unique identifier assigned by the <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance, and optionally recorded by the memory manager to access a loaded section.</p>


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### allocateDataSection() {#a066426b3a4a3a7318049886d4f0e6c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * llvm::orc::EPCGenericRTDyldMemoryManager::allocateDataSection (uintptr_t Size, unsigned Alignment, unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, bool IsReadOnly)</td>
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

<p>Allocate a memory block of (at least) the given size suitable for data.</p>


<p>The SectionID is a unique identifier assigned by the JIT engine, and optionally recorded by the memory manager to access a loaded section.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### deregisterEHFrames() {#aa79a52f4bf6d08101166dc7db74c66ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericRTDyldMemoryManager::deregisterEHFrames ()</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>

</div>
</div>

### finalizeMemory() {#a0db7d447f814afaee65a64c0419805dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::EPCGenericRTDyldMemoryManager::finalizeMemory (std::string * ErrMsg=nullptr)</td>
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

<p>This method is called when object loading is complete and section page permissions can be applied.</p>


<p>It is up to the memory manager implementation to decide whether or not to act on this method. The memory manager will typically allocate all sections as read-write and then apply specific permissions when this method is called. Code sections cannot be executed until this function has been called. In addition, any cache coherency operations needed to reliably use the memory are also performed.</p>


<p>Returns true if an error occurred, false otherwise.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/finalizerequest/#aa85c28825544c150ba63349d9c0cb7ce">llvm::orc::tpctypes::FinalizeRequest::Actions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall/#ac924edcd8ad4ceeebcbcea4ca04a793b">llvm::orc::shared::WrapperFunctionCall::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a953feeff1e20f40677fb7f77c073b3be">llvm::orc::Exec</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/finalizerequest/#aa7cb8653a6dc958e3aaf84d92fc08b69">llvm::orc::tpctypes::FinalizeRequest::Segments</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange/#a3bdf4fc0018782943ace850c8aeaaa69">llvm::orc::ExecutorAddrRange::Start</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a1129c0e4d43f2d121652a7302712cff6">llvm::orc::Write</a>.</p>

</div>
</div>

### needsToReserveAllocationSpace() {#a243b945941375d1231aed64262c787d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::EPCGenericRTDyldMemoryManager::needsToReserveAllocationSpace ()</td>
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

<p>Override to return true to enable the reserveAllocationSpace callback.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>

</div>
</div>

### notifyObjectLoaded() {#aa42b4fb322847e9ed79832fc94be6016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericRTDyldMemoryManager::notifyObjectLoaded (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> &amp; RTDyld, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
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

<p>This method is called after an object has been loaded into memory but before relocations are applied to the loaded sections.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> managers which are preparing code for execution in an external address space can use this call to remap the section addresses for the newly loaded object.</p>


<p>For clients that do not need access to an <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> instance this method should be preferred to its cousin <a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager/#a20044c6b32c19b606470dba740867e18">MCJITMemoryManager::notifyObjectLoaded</a> as this method is compatible with ORC JIT stacks.</p>


<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager/#aeb53f44bd8403ff24cbf2fe93c004935">llvm::RuntimeDyld::MemoryManager::RuntimeDyld</a>.</p>

</div>
</div>

### registerEHFrames() {#a83038edc3ba4948f540e15ae36d04098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericRTDyldMemoryManager::registerEHFrames (uint8_t * Addr, uint64_t LoadAddr, size_t Size)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the EH frames with the runtime so that c++ exceptions work.</p>


<p><span class="doxyComputerOutput">Addr</span> parameter provides the local address of the EH frame section data, while <span class="doxyComputerOutput">LoadAddr</span> provides the address of the data in the target address space. If the section has not been remapped (which will usually be the case for local execution) these two values will be the same.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### reserveAllocationSpace() {#a7fba4cc154f5345cbdc0c32c70f8155c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericRTDyldMemoryManager::reserveAllocationSpace (uintptr_t CodeSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> CodeAlign, uintptr_t RODataSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> RODataAlign, uintptr_t RWDataSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> RWDataAlign)</td>
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

<p>Inform the memory manager about the total amount of memory required to allocate all sections to be loaded: <span class="doxyComputerOutput">CodeSize</span> - the total size of all code sections <span class="doxyComputerOutput">DataSizeRO</span> - the total size of all read-only data sections <span class="doxyComputerOutput">DataSizeRW</span> - the total size of all read-write data sections.</p>


<p>Note that by default the callback is disabled. To enable it redefine the method needsToReserveAllocationSpace to return true.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### mapAllocsToRemoteAddrs() {#a7d523e00901731edde35f02786e0d5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericRTDyldMemoryManager::mapAllocsToRemoteAddrs (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> &amp; Dyld, std::vector&lt; SectionAlloc &gt; &amp; SecAllocs, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> NextAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EPC {#a38759403b2e8eae32a84069ff890afd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl&amp; llvm::orc::EPCGenericRTDyldMemoryManager::EPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>

</div>
</div>

### ErrMsg {#a16bbbbf4a4607972feab1a5e9f4abedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::EPCGenericRTDyldMemoryManager::ErrMsg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>

</div>
</div>

### FinalizedAllocs {#acf090309fc311c662b02cb6c0c22072f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ExecutorAddr&gt; llvm::orc::EPCGenericRTDyldMemoryManager::FinalizedAllocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>

</div>
</div>

### M {#a1812b18b47c877024b8ebfe6af1cc6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::EPCGenericRTDyldMemoryManager::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>

</div>
</div>

### SAs {#a342cee080c6547db7a2c7d7fd661fb9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolAddrs llvm::orc::EPCGenericRTDyldMemoryManager::SAs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>

</div>
</div>

### Unfinalized {#a3937a374a490b5693f4e3b7f66260656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SectionAllocGroup&gt; llvm::orc::EPCGenericRTDyldMemoryManager::Unfinalized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>

</div>
</div>

### Unmapped {#a826bb2e13f9b36f884f002d6a861919a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SectionAllocGroup&gt; llvm::orc::EPCGenericRTDyldMemoryManager::Unmapped</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateWithDefaultBootstrapSymbols() {#a5055d28d284af499b28f3a649ea33562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; EPCGenericRTDyldMemoryManager &gt; &gt; llvm::orc::EPCGenericRTDyldMemoryManager::CreateWithDefaultBootstrapSymbols (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager">EPCGenericRTDyldMemoryManager</a> using the given EPC, looking up the default symbol names in the bootstrap symbol set.</p>

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericrtdyldmemorymanager-h">EPCGenericRTDyldMemoryManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericrtdyldmemorymanager-cpp">EPCGenericRTDyldMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
