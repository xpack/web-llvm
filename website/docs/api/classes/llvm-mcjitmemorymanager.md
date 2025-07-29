---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcjitmemorymanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCJITMemoryManager` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCJITMemoryManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/rtdyldmemorymanager-h">llvm/ExecutionEngine/RTDyldMemoryManager.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20044c6b32c19b606470dba740867e18">notifyObjectLoaded</a> (ExecutionEngine *EE, const object::ObjectFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called after an object has been loaded into memory but before relocations are applied to the loaded sections. <a href="#a20044c6b32c19b606470dba740867e18">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bac1c8b518072c6152cafedf6a989a1">anchor</a> () override</td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/rtdyldmemorymanager-h">RTDyldMemoryManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### notifyObjectLoaded() {#a20044c6b32c19b606470dba740867e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCJITMemoryManager::notifyObjectLoaded (<a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> * EE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp;)</td>
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


<p>The object load may have been initiated by <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> to resolve an external symbol for another object that is being finalized. In that case, the object about which the memory manager is being notified will be finalized immediately after the memory manager returns from this call.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> managers which are preparing code for execution in an external address space can use this call to remap the section addresses for the newly loaded object.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/rtdyldmemorymanager-h">RTDyldMemoryManager.h</a>.</p>

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


<p>For clients that do not need access to an <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> instance this method should be preferred to its cousin <a href="#a20044c6b32c19b606470dba740867e18">MCJITMemoryManager::notifyObjectLoaded</a> as this method is compatible with ORC JIT stacks.</p>


<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/rtdyldmemorymanager-h">RTDyldMemoryManager.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a6bac1c8b518072c6152cafedf6a989a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCJITMemoryManager::anchor ()</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/rtdyldmemorymanager-h">RTDyldMemoryManager.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/rtdyldmemorymanager-cpp">RTDyldMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/rtdyldmemorymanager-h">RTDyldMemoryManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/rtdyldmemorymanager-cpp">RTDyldMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
