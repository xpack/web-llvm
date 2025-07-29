---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-executionenginebindings-cpp-/simplebindingmemorymanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SimpleBindingMemoryManager` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager { ... }
</div>

## Base class

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02eb46f2fbfa1ec2531bdcc0ecdf8076">SimpleBindingMemoryManager</a> (const SimpleBindingMMFunctions &amp;Functions, void *Opaque)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af91c3556845f7ff4f4a68e1779380b5d">~SimpleBindingMemoryManager</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fb282f7c252a261234d12f582edf3e">allocateCodeSection</a> (uintptr_t Size, unsigned Alignment, unsigned SectionID, StringRef SectionName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of (at least) the given size suitable for executable code. <a href="#ab0fb282f7c252a261234d12f582edf3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e33985e1099c1f555b0f27427d438a2">allocateDataSection</a> (uintptr_t Size, unsigned Alignment, unsigned SectionID, StringRef SectionName, bool isReadOnly) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of (at least) the given size suitable for data. <a href="#a6e33985e1099c1f555b0f27427d438a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b10de17ca3dd22c827efc454627555">finalizeMemory</a> (std::string *ErrMsg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called when object loading is complete and section page permissions can be applied. <a href="#aa4b10de17ca3dd22c827efc454627555">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-executionenginebindings-cpp-/simplebindingmmfunctions">SimpleBindingMMFunctions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11423a13a3066b3e3aca8f94c612bfcf">Functions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa790ea7ab561fe9bf66eff6eab268610">Opaque</a></td>
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


<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SimpleBindingMemoryManager() {#a02eb46f2fbfa1ec2531bdcc0ecdf8076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager::SimpleBindingMemoryManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-executionenginebindings-cpp-/simplebindingmmfunctions">SimpleBindingMMFunctions</a> &amp; Functions, void * Opaque)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SimpleBindingMemoryManager() {#af91c3556845f7ff4f4a68e1779380b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager::~SimpleBindingMemoryManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocateCodeSection() {#ab0fb282f7c252a261234d12f582edf3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager::allocateCodeSection (uintptr_t Size, unsigned Alignment, unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
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


<p>The SectionID is a unique identifier assigned by the RuntimeDyld instance, and optionally recorded by the memory manager to access a loaded section.</p>


<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### allocateDataSection() {#a6e33985e1099c1f555b0f27427d438a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager::allocateDataSection (uintptr_t Size, unsigned Alignment, unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, bool IsReadOnly)</td>
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


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### finalizeMemory() {#aa4b10de17ca3dd22c827efc454627555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager::finalizeMemory (std::string * ErrMsg)</td>
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


<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Functions {#a11423a13a3066b3e3aca8f94c612bfcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimpleBindingMMFunctions anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager::Functions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>

</div>
</div>

### Opaque {#aa790ea7ab561fe9bf66eff6eab268610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* anonymous{ExecutionEngineBindings.cpp}::SimpleBindingMemoryManager::Opaque</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
