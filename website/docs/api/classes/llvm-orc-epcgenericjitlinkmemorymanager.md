---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcgenericjitlinkmemorymanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EPCGenericJITLinkMemoryManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCGenericJITLinkMemoryManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">llvm/ExecutionEngine/Orc/EPCGenericJITLinkMemoryManager.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802082bc67d1af66487f8e6feae2334f">EPCGenericJITLinkMemoryManager</a> (ExecutorProcessControl &amp;EPC, SymbolAddrs SAs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager">EPCGenericJITLinkMemoryManager</a> instance from a given set of function addrs. <a href="#a802082bc67d1af66487f8e6feae2334f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78faafd56c5a0f566519e357c5c585b2">allocate</a> (const jitlink::JITLinkDylib *JD, jitlink::LinkGraph &amp;G, OnAllocatedFunction OnAllocated) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start the allocation process. <a href="#a78faafd56c5a0f566519e357c5c585b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379e638ec80c39dbc014d5032b959ff6">deallocate</a> (std::vector&lt; FinalizedAlloc &gt; Allocs, OnDeallocatedFunction OnDeallocated) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate a list of allocation objects. <a href="#a379e638ec80c39dbc014d5032b959ff6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4183ae565756d358570872dd7810ba58">completeAllocation</a> (ExecutorAddr AllocAddr, jitlink::BasicLayout BL, OnAllocatedFunction OnAllocated)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eba7f50e1dcf26617706ac90de23752">EPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/epcgenericjitlinkmemorymanager/symboladdrs">SymbolAddrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5516fc66f774616b76d357c41b6a87db">SAs</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EPCGenericJITLinkMemoryManager() {#a802082bc67d1af66487f8e6feae2334f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCGenericJITLinkMemoryManager::EPCGenericJITLinkMemoryManager (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC, <a href="/web-llvm/docs/api/structs/llvm/orc/epcgenericjitlinkmemorymanager/symboladdrs">SymbolAddrs</a> SAs)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager">EPCGenericJITLinkMemoryManager</a> instance from a given set of function addrs.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager/inflightalloc/#a6f99cffd10c253ae6ce5da12de53383a">llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::InFlightAlloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocate() {#a78faafd56c5a0f566519e357c5c585b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericJITLinkMemoryManager::allocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">jitlink::JITLinkDylib</a> * JD, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a80d1ed0619748c7b87067a81109943bd">OnAllocatedFunction</a> OnAllocated)</td>
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


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### deallocate() {#a379e638ec80c39dbc014d5032b959ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericJITLinkMemoryManager::deallocate (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt; Allocs, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a8891e6f8e95eeb639c2b15036283bab1">OnDeallocatedFunction</a> OnDeallocated)</td>
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


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### completeAllocation() {#a4183ae565756d358570872dd7810ba58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericJITLinkMemoryManager::completeAllocation (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> AllocAddr, <a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout">jitlink::BasicLayout</a> BL, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a80d1ed0619748c7b87067a81109943bd">OnAllocatedFunction</a> OnAllocated)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EPC {#a0eba7f50e1dcf26617706ac90de23752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl&amp; llvm::orc::EPCGenericJITLinkMemoryManager::EPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a>.</p>

</div>
</div>

### SAs {#a5516fc66f774616b76d357c41b6a87db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolAddrs llvm::orc::EPCGenericJITLinkMemoryManager::SAs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericjitlinkmemorymanager-h">EPCGenericJITLinkMemoryManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
