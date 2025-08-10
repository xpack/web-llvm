---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/orcee-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `OrcEE.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">llvm-c/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">llvm-c/ExecutionEngine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/orc-h">llvm-c/Orc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/targetmachine-h">llvm-c/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#a68b9796c5bc7b233ab00d43212ee21c3">LLVMMemoryManagerNotifyTerminatingCallback</a>)(void *CtxCtx)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#gaea24c520fba0be17841bb8c022a39822">LLVMOrcCreateRTDyldObjectLinkingLayerWithSectionMemoryManager</a> (LLVMOrcExecutionSessionRef ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a RTDyldObjectLinkingLayer instance using the standard SectionMemoryManager for memory management. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#gaea24c520fba0be17841bb8c022a39822">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#ga4aaa19f070d761e54fee2069127e8ee0">LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks</a> (LLVMOrcExecutionSessionRef ES, void *CreateContextCtx, LLVMMemoryManagerCreateContextCallback CreateContext, LLVMMemoryManagerNotifyTerminatingCallback NotifyTerminating, LLVMMemoryManagerAllocateCodeSectionCallback AllocateCodeSection, LLVMMemoryManagerAllocateDataSectionCallback AllocateDataSection, LLVMMemoryManagerFinalizeMemoryCallback FinalizeMemory, LLVMMemoryManagerDestroyCallback Destroy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a RTDyldObjectLinkingLayer instance using MCJIT-memory-manager-like callbacks. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#ga4aaa19f070d761e54fee2069127e8ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#gaf7055d3c420852e38b0037e7b9bba492">LLVMOrcRTDyldObjectLinkingLayerRegisterJITEventListener</a> (LLVMOrcObjectLayerRef RTDyldObjLinkingLayer, LLVMJITEventListenerRef Listener)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given listener to the given RTDyldObjectLinkingLayer. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#gaf7055d3c420852e38b0037e7b9bba492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h/#a4789aaabaa5bf3b7a549171b47cc4d4a">LLVM_C_EXTERN_C_BEGIN</a> typedef void *(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1ef8b8fddd2a92750f2ce99978e47e">LLVMMemoryManagerCreateContextCallback</a>)(void *CtxCtx)</td>
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


<div class="doxySectionDef">

## Typedefs

### LLVMMemoryManagerNotifyTerminatingCallback {#a68b9796c5bc7b233ab00d43212ee21c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* LLVMMemoryManagerNotifyTerminatingCallback) (void *CtxCtx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h">OrcEE.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### LLVMMemoryManagerCreateContextCallback {#a1f1ef8b8fddd2a92750f2ce99978e47e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_C_EXTERN_C_BEGIN typedef void *(* LLVMMemoryManagerCreateContextCallback) (void *CtxCtx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h">OrcEE.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee/#ga4aaa19f070d761e54fee2069127e8ee0">LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
