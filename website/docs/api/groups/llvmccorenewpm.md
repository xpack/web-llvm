---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccorenewpm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The New Pass Manager Reference



## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">typedefLLVM_C_EXTERN_C_BEGIN struct LLVMOpaquePassBuilderOptions * <a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of options passed which are attached to the Pass Manager upon run. <a href="#gab96a23e2cec5c8e689f952c7c9daadb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae3e632706254c18142e979ad1aec63a9">LLVMRunPasses</a> (LLVMModuleRef M, const char *Passes, LLVMTargetMachineRef TM, LLVMPassBuilderOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct and run a set of passes over a module. <a href="#gae3e632706254c18142e979ad1aec63a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf31caae4259f8aaaac2d6cc296a3c952">LLVMRunPassesOnFunction</a> (LLVMValueRef F, const char *Passes, LLVMTargetMachineRef TM, LLVMPassBuilderOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct and run a set of passes over a function. <a href="#gaf31caae4259f8aaaac2d6cc296a3c952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0fe3fac04d1cb0d18d24b194794678ac">LLVMCreatePassBuilderOptions</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new set of options for a PassBuilder. <a href="#ga0fe3fac04d1cb0d18d24b194794678ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1f4b0b26dccab6bd18dc0461a4655758">LLVMPassBuilderOptionsSetVerifyEach</a> (LLVMPassBuilderOptionsRef Options, LLVMBool VerifyEach)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle adding the VerifierPass for the PassBuilder, ensuring all functions inside the module is valid. <a href="#ga1f4b0b26dccab6bd18dc0461a4655758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0e6798311686167ea8c6d52d2c68245b">LLVMPassBuilderOptionsSetDebugLogging</a> (LLVMPassBuilderOptionsRef Options, LLVMBool DebugLogging)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle debug logging when running the PassBuilder. <a href="#ga0e6798311686167ea8c6d52d2c68245b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab90315ff95335ee7bd709a1d57096083">LLVMPassBuilderOptionsSetAAPipeline</a> (LLVMPassBuilderOptionsRef Options, const char *AAPipeline)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify a custom alias analysis pipeline for the PassBuilder to be used instead of the default one. <a href="#gab90315ff95335ee7bd709a1d57096083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gade89b3aed22dd6f3616c0578828dfc07">LLVMPassBuilderOptionsSetLoopInterleaving</a> (LLVMPassBuilderOptionsRef Options, LLVMBool LoopInterleaving)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5fd1b2ca28ad492f2cab4a189b56c222">LLVMPassBuilderOptionsSetLoopVectorization</a> (LLVMPassBuilderOptionsRef Options, LLVMBool LoopVectorization)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4a8f0bbc064a868e343595d6ffdfb0b1">LLVMPassBuilderOptionsSetSLPVectorization</a> (LLVMPassBuilderOptionsRef Options, LLVMBool SLPVectorization)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7063db6cd5a828b75a830a75011c7313">LLVMPassBuilderOptionsSetLoopUnrolling</a> (LLVMPassBuilderOptionsRef Options, LLVMBool LoopUnrolling)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacfd7457e6582843ca42e6011418be891">LLVMPassBuilderOptionsSetForgetAllSCEVInLoopUnroll</a> (LLVMPassBuilderOptionsRef Options, LLVMBool ForgetAllSCEVInLoopUnroll)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga27d8155739262738247c2e10be936e68">LLVMPassBuilderOptionsSetLicmMssaOptCap</a> (LLVMPassBuilderOptionsRef Options, unsigned LicmMssaOptCap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga394cea3608ff09d97f3a164704ef78ce">LLVMPassBuilderOptionsSetLicmMssaNoAccForPromotionCap</a> (LLVMPassBuilderOptionsRef Options, unsigned LicmMssaNoAccForPromotionCap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5d2827f09e9253bff90efda50f8646ba">LLVMPassBuilderOptionsSetCallGraphProfile</a> (LLVMPassBuilderOptionsRef Options, LLVMBool CallGraphProfile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0a26bfce0c16b662c57b619fef542bde">LLVMPassBuilderOptionsSetMergeFunctions</a> (LLVMPassBuilderOptionsRef Options, LLVMBool MergeFunctions)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga48b51173f261a787eb243c86b5a012e4">LLVMPassBuilderOptionsSetInlinerThreshold</a> (LLVMPassBuilderOptionsRef Options, int Threshold)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2845b29f9e47f8fea2befeca45b07e79">LLVMDisposePassBuilderOptions</a> (LLVMPassBuilderOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a heap-allocated PassBuilderOptions instance. <a href="#ga2845b29f9e47f8fea2befeca45b07e79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### LLVMPassBuilderOptionsRef {#gab96a23e2cec5c8e689f952c7c9daadb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef typedefLLVM_C_EXTERN_C_BEGIN struct LLVMOpaquePassBuilderOptions* LLVMPassBuilderOptionsRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of options passed which are attached to the Pass Manager upon run.</p>


<p>This corresponds to an <a href="/web-llvm/docs/api/classes/llvm/llvmpassbuilderoptions">llvm::LLVMPassBuilderOptions</a> instance</p>


<p>The details for how the different properties of this structure are used can be found in the source for LLVMRunPasses</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMCreatePassBuilderOptions() {#ga0fe3fac04d1cb0d18d24b194794678ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMPassBuilderOptionsRef LLVMCreatePassBuilderOptions (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new set of options for a PassBuilder.</p>


<p>Ownership of the returned instance is given to the client, and they are responsible for it. The client should call LLVMDisposePassBuilderOptions to free the pass builder options.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDisposePassBuilderOptions() {#ga2845b29f9e47f8fea2befeca45b07e79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposePassBuilderOptions (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispose of a heap-allocated PassBuilderOptions instance.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetAAPipeline() {#gab90315ff95335ee7bd709a1d57096083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetAAPipeline (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * AAPipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specify a custom alias analysis pipeline for the PassBuilder to be used instead of the default one.</p>


<p>The string argument is not copied; the caller is responsible for ensuring it outlives the PassBuilderOptions instance.</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetCallGraphProfile() {#ga5d2827f09e9253bff90efda50f8646ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetCallGraphProfile (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> CallGraphProfile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetDebugLogging() {#ga0e6798311686167ea8c6d52d2c68245b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetDebugLogging (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> DebugLogging)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Toggle debug logging when running the PassBuilder.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetForgetAllSCEVInLoopUnroll() {#gacfd7457e6582843ca42e6011418be891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetForgetAllSCEVInLoopUnroll (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> ForgetAllSCEVInLoopUnroll)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetInlinerThreshold() {#ga48b51173f261a787eb243c86b5a012e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetInlinerThreshold (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, int Threshold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetLicmMssaNoAccForPromotionCap() {#ga394cea3608ff09d97f3a164704ef78ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetLicmMssaNoAccForPromotionCap (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, unsigned LicmMssaNoAccForPromotionCap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetLicmMssaOptCap() {#ga27d8155739262738247c2e10be936e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetLicmMssaOptCap (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, unsigned LicmMssaOptCap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetLoopInterleaving() {#gade89b3aed22dd6f3616c0578828dfc07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetLoopInterleaving (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> LoopInterleaving)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetLoopUnrolling() {#ga7063db6cd5a828b75a830a75011c7313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetLoopUnrolling (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> LoopUnrolling)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetLoopVectorization() {#ga5fd1b2ca28ad492f2cab4a189b56c222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetLoopVectorization (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> LoopVectorization)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetMergeFunctions() {#ga0a26bfce0c16b662c57b619fef542bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetMergeFunctions (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> MergeFunctions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetSLPVectorization() {#ga4a8f0bbc064a868e343595d6ffdfb0b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetSLPVectorization (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> SLPVectorization)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPassBuilderOptionsSetVerifyEach() {#ga1f4b0b26dccab6bd18dc0461a4655758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMPassBuilderOptionsSetVerifyEach (<a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> VerifyEach)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Toggle adding the VerifierPass for the PassBuilder, ensuring all functions inside the module is valid.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acf9a76b441b49648ba97e4a40c3ad5f6">VerifyEach</a>.</p>

</div>
</div>

### LLVMRunPasses() {#gae3e632706254c18142e979ad1aec63a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMRunPasses (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Passes, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a> TM, <a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct and run a set of passes over a module.</p>


<p>This function takes a string with the passes that should be used. The format of this string is the same as opt's -passes argument for the new pass manager. Individual passes may be specified, separated by commas. Full pipelines may also be invoked using <span class="doxyComputerOutput">default&lt;O3&gt;</span> and friends. See opt for full reference of the Passes format.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4a1f52f59d0b4cc188f43fbfdccf6c54">Passes</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRunPassesOnFunction() {#gaf31caae4259f8aaaac2d6cc296a3c952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMRunPassesOnFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Passes, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a> TM, <a href="#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a> Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct and run a set of passes over a function.</p>


<p>This function behaves the same as LLVMRunPasses, but operates on a single function instead of an entire module.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">PassBuilder.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#aec1db240440db5948a5f72be2665b8c5">Fun</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4a1f52f59d0b4cc188f43fbfdccf6c54">Passes</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
