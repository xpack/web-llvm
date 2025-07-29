---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcexecutionengineorcee
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# ExecutionEngine-based ORC Utils



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaea24c520fba0be17841bb8c022a39822">LLVMOrcCreateRTDyldObjectLinkingLayerWithSectionMemoryManager</a> (LLVMOrcExecutionSessionRef ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a RTDyldObjectLinkingLayer instance using the standard SectionMemoryManager for memory management. <a href="#gaea24c520fba0be17841bb8c022a39822">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4aaa19f070d761e54fee2069127e8ee0">LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks</a> (LLVMOrcExecutionSessionRef ES, void *CreateContextCtx, LLVMMemoryManagerCreateContextCallback CreateContext, LLVMMemoryManagerNotifyTerminatingCallback NotifyTerminating, LLVMMemoryManagerAllocateCodeSectionCallback AllocateCodeSection, LLVMMemoryManagerAllocateDataSectionCallback AllocateDataSection, LLVMMemoryManagerFinalizeMemoryCallback FinalizeMemory, LLVMMemoryManagerDestroyCallback Destroy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a RTDyldObjectLinkingLayer instance using MCJIT-memory-manager-like callbacks. <a href="#ga4aaa19f070d761e54fee2069127e8ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf7055d3c420852e38b0037e7b9bba492">LLVMOrcRTDyldObjectLinkingLayerRegisterJITEventListener</a> (LLVMOrcObjectLayerRef RTDyldObjLinkingLayer, LLVMJITEventListenerRef Listener)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given listener to the given RTDyldObjectLinkingLayer. <a href="#gaf7055d3c420852e38b0037e7b9bba492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks() {#ga4aaa19f070d761e54fee2069127e8ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcObjectLayerRef LLVMOrcCreateRTDyldObjectLinkingLayerWithMCJITMemoryManagerLikeCallbacks (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga653c8620112eddd7c75085a0b586c97d">LLVMOrcExecutionSessionRef</a> ES, void * CreateContextCtx, <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h/#a1f1ef8b8fddd2a92750f2ce99978e47e">LLVMMemoryManagerCreateContextCallback</a> CreateContext, <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h/#a68b9796c5bc7b233ab00d43212ee21c3">LLVMMemoryManagerNotifyTerminatingCallback</a> NotifyTerminating, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gad54344e18e0839b6b3f39d598c5598f0">LLVMMemoryManagerAllocateCodeSectionCallback</a> AllocateCodeSection, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gabe63644e7847066c1ac90ad487040e26">LLVMMemoryManagerAllocateDataSectionCallback</a> AllocateDataSection, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa3aa0817f65b3ec44e6e3b797570f05e">LLVMMemoryManagerFinalizeMemoryCallback</a> FinalizeMemory, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga4e9770ff745f02b2bf2e473b3f5a7c58">LLVMMemoryManagerDestroyCallback</a> Destroy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a RTDyldObjectLinkingLayer instance using MCJIT-memory-manager-like callbacks.</p>


<p>This is intended to simplify transitions for existing MCJIT clients. The callbacks used are similar (but not identical) to the callbacks for LLVMCreateSimpleMCJITMemoryManager: Unlike MCJIT, RTDyldObjectLinkingLayer will create a new memory manager for each object linked by calling the given CreateContext callback. This allows for code removal by destroying each allocator individually. Every allocator will be destroyed (if it has not been already) at RTDyldObjectLinkingLayer destruction time, and the NotifyTerminating callback will be called to indicate that no further allocation contexts will be created.</p>


<p>To implement MCJIT-like behavior clients can implement CreateContext, NotifyTerminating, and Destroy as:</p>


<p>void *CreateContext(void *CtxCtx) { return CtxCtx; } void NotifyTerminating(void *CtxCtx) { MyOriginalDestroy(CtxCtx); } void Destroy(void *Ctx) { }</p>


<p>This scheme simply reuses the CreateContextCtx pointer as the one-and-only allocation context.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h">OrcEE.h</a>, definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager/#aaaa63dd49bc491d2da811c84dd9b4c0e">llvm::RuntimeDyld::MemoryManager::allocateCodeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager/#a762c2ef812ed069620da3bba0e65bba5">llvm::RuntimeDyld::MemoryManager::allocateDataSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager/#abd33e61ef93ebdd7c7b40c62f43f71b3">llvm::RuntimeDyld::MemoryManager::finalizeMemory</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h/#a1f1ef8b8fddd2a92750f2ce99978e47e">LLVMMemoryManagerCreateContextCallback</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcCreateRTDyldObjectLinkingLayerWithSectionMemoryManager() {#gaea24c520fba0be17841bb8c022a39822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcObjectLayerRef LLVMOrcCreateRTDyldObjectLinkingLayerWithSectionMemoryManager (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga653c8620112eddd7c75085a0b586c97d">LLVMOrcExecutionSessionRef</a> ES)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a RTDyldObjectLinkingLayer instance using the standard SectionMemoryManager for memory management.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h">OrcEE.h</a>, definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcRTDyldObjectLinkingLayerRegisterJITEventListener() {#gaf7055d3c420852e38b0037e7b9bba492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMOrcRTDyldObjectLinkingLayerRegisterJITEventListener (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a> RTDyldObjLinkingLayer, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad4bf262b53178061f7b936e3d1ff43bf">LLVMJITEventListenerRef</a> Listener)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the given listener to the given RTDyldObjectLinkingLayer.</p>


<p>Note: Layer must be an RTDyldObjectLinkingLayer instance or behavior is undefined.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orcee-h">OrcEE.h</a>, definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
