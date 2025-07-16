---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccorepassmanagers
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Pass Managers Reference



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabcb01c2a5ba65b4ebb0e4ca8b11e0920">LLVMCreatePassManager</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a new whole-module pass pipeline. <a href="#gabcb01c2a5ba65b4ebb0e4ca8b11e0920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf677b98752f2afd5fb25906c33bc237c">LLVMCreateFunctionPassManagerForModule</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a new function-by-function pass pipeline over the module provider. <a href="#gaf677b98752f2afd5fb25906c33bc237c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7e63986f39ff78682a387dca7dad83c1">LLVMCreateFunctionPassManager</a> (LLVMModuleProviderRef MP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMCreateFunctionPassManagerForModule instead. <a href="#ga7e63986f39ff78682a387dca7dad83c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga59bfa857c4ed502aeed6a39bcb1cbbce">LLVMRunPassManager</a> (LLVMPassManagerRef PM, LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes, executes on the provided module, and finalizes all of the passes scheduled in the pass manager. <a href="#ga59bfa857c4ed502aeed6a39bcb1cbbce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaee481997fd1d27186cfd044cba6c576f">LLVMInitializeFunctionPassManager</a> (LLVMPassManagerRef FPM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes all of the function passes scheduled in the function pass manager. <a href="#gaee481997fd1d27186cfd044cba6c576f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacace2d072a4735931738af64cc6fc170">LLVMRunFunctionPassManager</a> (LLVMPassManagerRef FPM, LLVMValueRef F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Executes all of the function passes scheduled in the function pass manager on the provided function. <a href="#gacace2d072a4735931738af64cc6fc170">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacaac4e1b3d3f4314d4f2fabdb0de856e">LLVMFinalizeFunctionPassManager</a> (LLVMPassManagerRef FPM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalizes all of the function passes scheduled in the function pass manager. <a href="#gacaac4e1b3d3f4314d4f2fabdb0de856e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabd99e3acfdfa7bcbd83772f326217189">LLVMDisposePassManager</a> (LLVMPassManagerRef PM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees the memory of a pass pipeline. <a href="#gabd99e3acfdfa7bcbd83772f326217189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### LLVMCreateFunctionPassManager() {#ga7e63986f39ff78682a387dca7dad83c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMPassManagerRef LLVMCreateFunctionPassManager (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad77f13d71e9aebc385324cde314d9ac6">LLVMModuleProviderRef</a> MP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMCreateFunctionPassManagerForModule instead.</p>

<p>Declaration at line 4778 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4563 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#gaf677b98752f2afd5fb25906c33bc237c">LLVMCreateFunctionPassManagerForModule</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### LLVMCreateFunctionPassManagerForModule() {#gaf677b98752f2afd5fb25906c33bc237c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMPassManagerRef LLVMCreateFunctionPassManagerForModule (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs a new function-by-function pass pipeline over the module provider.</p>


<p>It does not take ownership of the module provider. This type of pipeline is suitable for code generation and JIT compilation tasks.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::FunctionPassManager::FunctionPassManager</p></dd>
</dl>


<p>Declaration at line 4775 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4559 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>


<p>Referenced by <a href="#ga7e63986f39ff78682a387dca7dad83c1">LLVMCreateFunctionPassManager</a>.</p>

</div>
</div>

### LLVMCreatePassManager() {#gabcb01c2a5ba65b4ebb0e4ca8b11e0920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMPassManagerRef LLVMCreatePassManager (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs a new whole-module pass pipeline.</p>


<p>This type of pipeline is suitable for link-time optimization and whole-module transformations.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/passmanager/#a8feea6425d71b06eb9eea6dfb60dcf4e">llvm::PassManager::PassManager</a></p></dd>
</dl>


<p>Declaration at line 4769 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4555 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDisposePassManager() {#gabd99e3acfdfa7bcbd83772f326217189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposePassManager (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a> PM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Frees the memory of a pass pipeline.</p>


<p>For function pipelines, does not free the module provider.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/passmanagerbase/#a4e678f968a8f574109cb78eee4d3d756">llvm::PassManagerBase::~PassManagerBase</a>.</p></dd>
</dl>


<p>Declaration at line 4805 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4584 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMFinalizeFunctionPassManager() {#gacaac4e1b3d3f4314d4f2fabdb0de856e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMFinalizeFunctionPassManager (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a> FPM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalizes all of the function passes scheduled in the function pass manager.</p>


<p>Returns 1 if any of the passes modified the module, 0 otherwise.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::FunctionPassManager::doFinalization</p></dd>
</dl>


<p>Declaration at line 4800 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4580 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMInitializeFunctionPassManager() {#gaee481997fd1d27186cfd044cba6c576f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMInitializeFunctionPassManager (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a> FPM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializes all of the function passes scheduled in the function pass manager.</p>


<p>Returns 1 if any of the passes modified the module, 0 otherwise.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::FunctionPassManager::doInitialization</p></dd>
</dl>


<p>Declaration at line 4789 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4572 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRunFunctionPassManager() {#gacace2d072a4735931738af64cc6fc170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMRunFunctionPassManager (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a> FPM, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Executes all of the function passes scheduled in the function pass manager on the provided function.</p>


<p>Returns 1 if any of the passes modified the function, false otherwise.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::FunctionPassManager::run(Function&amp;)</p></dd>
</dl>


<p>Declaration at line 4795 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4576 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRunPassManager() {#ga59bfa857c4ed502aeed6a39bcb1cbbce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMRunPassManager (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a> PM, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializes, executes on the provided module, and finalizes all of the passes scheduled in the pass manager.</p>


<p>Returns 1 if any of the passes modified the module, 0 otherwise.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::PassManager::run(Module&amp;)</p></dd>
</dl>


<p>Declaration at line 4784 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 4568 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
