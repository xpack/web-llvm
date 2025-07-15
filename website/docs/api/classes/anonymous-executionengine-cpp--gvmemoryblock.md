---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-executionengine-cpp-/gvmemoryblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GVMemoryBlock` Class Reference

<p>Helper class which uses a value handler to automatically deletes the memory block when the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> is destroyed. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ExecutionEngine.cpp}::GVMemoryBlock { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle with callbacks on RAUW and destruction. <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91ba3a5daf4cb306570a4d402fd1bc7b">GVMemoryBlock</a> (const GlobalVariable *GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd1dac06c22ec594224d3d62d99105c">deleted</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for Value destruction. <a href="#a2bd1dac06c22ec594224d3d62d99105c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cbb49e0b488e91387da02f0396405f7">Create</a> (const GlobalVariable *GV, const DataLayout &amp;TD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> should be written into. <a href="#a2cbb49e0b488e91387da02f0396405f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class which uses a value handler to automatically deletes the memory block when the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> is destroyed.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### GVMemoryBlock() {#a91ba3a5daf4cb306570a4d402fd1bc7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ExecutionEngine.cpp}::GVMemoryBlock::GVMemoryBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deleted() {#a2bd1dac06c22ec594224d3d62d99105c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ExecutionEngine.cpp}::GVMemoryBlock::deleted ()</td>
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

<p>Callback for Value destruction.</p>


<p>Called when this-&gt;<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a> is destroyed, inside ~Value(), so you may call any non-virtual Value method on <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a>, but no subclass methods. If WeakTrackingVH were implemented as a CallbackVH, it would use this method to call setValPtr(NULL). AssertingVH would use this method to cause an assertion failure.</p>


<p>All implementations must remove the reference from this object to the Value that's being destroyed.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a2cbb49e0b488e91387da02f0396405f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * anonymous{ExecutionEngine.cpp}::GVMemoryBlock::Create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; TD)</td>
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

<p>Returns the address the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> should be written into.</p>


<p>The <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/gvmemoryblock">GVMemoryBlock</a> object prefixes that.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#abc7937248226859bf5a5d64a28c8269f">llvm::DataLayout::getPreferredAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aa48b3b7e554b44f4e513d5dd8d9f9343">llvm::DataLayout::getTypeAllocSize</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#ae739336f3ec474f015e91e7698af256b">llvm::ExecutionEngine::getMemoryForGV</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
