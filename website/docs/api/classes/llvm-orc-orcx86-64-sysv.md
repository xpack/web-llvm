---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/orcx86-64-sysv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OrcX86_64_SysV` Class Reference

<p>X86_64 support for SysV ABI (Linux, MacOSX). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::OrcX86_64_SysV { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/orcabisupport-h">llvm/ExecutionEngine/Orc/OrcABISupport.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/orcx86-64-base">OrcX86_64_Base</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86_64 code that's common to all ABIs. <a href="/web-llvm/docs/api/classes/llvm/orc/orcx86-64-base/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e54c6d22c5d35f3dced631e08b8fa1">writeResolverCode</a> (char *ResolverWorkingMem, ExecutorAddr ResolverTargetAddress, ExecutorAddr ReentryFnAddr, ExecutorAddr ReentryCtxAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the resolver code into the given memory. <a href="#ac5e54c6d22c5d35f3dced631e08b8fa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a875332045e826c7d866d057678ed08">ResolverCodeSize</a> = 0x6C</td>
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

<p>X86_64 support for SysV ABI (Linux, MacOSX).</p>


<p>X86_64_SysV supports lazy JITing.</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/orcabisupport-h">OrcABISupport.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### writeResolverCode() {#ac5e54c6d22c5d35f3dced631e08b8fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::OrcX86_64_SysV::writeResolverCode (char * ResolverWorkingMem, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ResolverTargetAddress, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ReentryFnAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ReentryCtxAddr)</td>
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

<p>Write the resolver code into the given memory.</p>


<p>The user is responsible for allocating the memory and setting permissions.</p>


<p>ReentryFnAddr should be the address of a function whose signature matches void* (*)(void *TrampolineAddr, void *ReentryCtxAddr). The ReentryCtxAddr argument of writeResolverCode will be passed as the second argument to the function at ReentryFnAddr.</p>


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/orcabisupport-h">OrcABISupport.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcabisupport-cpp">OrcABISupport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ResolverCodeSize {#a6a875332045e826c7d866d057678ed08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::orc::OrcX86_64_SysV::ResolverCodeSize = 0x6C</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/orcabisupport-h">OrcABISupport.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/orcabisupport-h">OrcABISupport.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcabisupport-cpp">OrcABISupport.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
