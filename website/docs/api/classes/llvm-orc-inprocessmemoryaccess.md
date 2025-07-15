---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/inprocessmemoryaccess
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InProcessMemoryAccess` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::InProcessMemoryAccess { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">llvm/ExecutionEngine/Orc/ExecutorProcessControl.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>APIs for manipulating memory in the target process. <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol">SelfExecutorProcessControl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> implementation targeting the current process. <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol">UnsupportedExecutorProcessControl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance that asserts if any of its methods are used. <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b8eaa1386313ab62e44088a6ccb6356">InProcessMemoryAccess</a> (bool IsArch64Bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14fa49b36b89bca87fb928aa64e76dbf">writeUInt8sAsync</a> (ArrayRef&lt; tpctypes::UInt8Write &gt; Ws, WriteResultFn OnWriteComplete) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b22da944d53023460365031a7525703">writeUInt16sAsync</a> (ArrayRef&lt; tpctypes::UInt16Write &gt; Ws, WriteResultFn OnWriteComplete) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b80e67313b27c06584797a360185bc">writeUInt32sAsync</a> (ArrayRef&lt; tpctypes::UInt32Write &gt; Ws, WriteResultFn OnWriteComplete) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0b68bda47368d41602d9f70834ba0e">writeUInt64sAsync</a> (ArrayRef&lt; tpctypes::UInt64Write &gt; Ws, WriteResultFn OnWriteComplete) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1c2aabe1be663366f019131541ee4b">writeBuffersAsync</a> (ArrayRef&lt; tpctypes::BufferWrite &gt; Ws, WriteResultFn OnWriteComplete) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038b06a69e161afa168e0cf438dc9658">writePointersAsync</a> (ArrayRef&lt; tpctypes::PointerWrite &gt; Ws, WriteResultFn OnWriteComplete) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f291b176ef9e60a0be6fcf9bfaee8e">IsArch64Bit</a></td>
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


<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InProcessMemoryAccess() {#a2b8eaa1386313ab62e44088a6ccb6356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::InProcessMemoryAccess::InProcessMemoryAccess (bool IsArch64Bit)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a19bfb4bd3753f07c39a881a7718e0fac">llvm::orc::UnsupportedExecutorProcessControl::UnsupportedExecutorProcessControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### writeBuffersAsync() {#a8c1c2aabe1be663366f019131541ee4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryAccess::writeBuffersAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/bufferwrite">tpctypes::BufferWrite</a> &gt; Ws, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess/#a9a99834468cbee16771e1a7664c0b966">WriteResultFn</a> OnWriteComplete)</td>
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



<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### writePointersAsync() {#a038b06a69e161afa168e0cf438dc9658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryAccess::writePointersAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/pointerwrite">tpctypes::PointerWrite</a> &gt; Ws, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess/#a9a99834468cbee16771e1a7664c0b966">WriteResultFn</a> OnWriteComplete)</td>
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



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### writeUInt16sAsync() {#a4b22da944d53023460365031a7525703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryAccess::writeUInt16sAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#afb4f0e75a1d8360be6d6c074f1dd7c0d">tpctypes::UInt16Write</a> &gt; Ws, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess/#a9a99834468cbee16771e1a7664c0b966">WriteResultFn</a> OnWriteComplete)</td>
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



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### writeUInt32sAsync() {#a14b80e67313b27c06584797a360185bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryAccess::writeUInt32sAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#abea9220a6f892c0894c498658dc2f270">tpctypes::UInt32Write</a> &gt; Ws, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess/#a9a99834468cbee16771e1a7664c0b966">WriteResultFn</a> OnWriteComplete)</td>
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



<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### writeUInt64sAsync() {#aec0b68bda47368d41602d9f70834ba0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryAccess::writeUInt64sAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a3dabfce3a313ac45a21b3ac0b0fb5fd1">tpctypes::UInt64Write</a> &gt; Ws, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess/#a9a99834468cbee16771e1a7664c0b966">WriteResultFn</a> OnWriteComplete)</td>
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



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### writeUInt8sAsync() {#a14fa49b36b89bca87fb928aa64e76dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryAccess::writeUInt8sAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a76c86732685482aa3cf56ad11a7b91ed">tpctypes::UInt8Write</a> &gt; Ws, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess/#a9a99834468cbee16771e1a7664c0b966">WriteResultFn</a> OnWriteComplete)</td>
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



<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsArch64Bit {#a06f291b176ef9e60a0be6fcf9bfaee8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::InProcessMemoryAccess::IsArch64Bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
