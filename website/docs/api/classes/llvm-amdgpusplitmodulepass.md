---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpusplitmodulepass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUSplitModulePass` Class Reference

<p>Splits the module M into N linkable partitions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUSplitModulePass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">Target/AMDGPU/AMDGPUSplitModule.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942d2f73ab20f73f1a0a4ec25b6c4ee7">ModuleCreationCallback</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; MPart)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3f035b68b07684b1943c4e0296c0fd1">AMDGPUSplitModulePass</a> (unsigned N, ModuleCreationCallback ModuleCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fdf4ead69288861f3151e0f035a9877">run</a> (Module &amp;M, ModuleAnalysisManager &amp;MAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34f21565b2efd00ed2df350a6fbff19">N</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a942d2f73ab20f73f1a0a4ec25b6c4ee7">ModuleCreationCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3a2fa1aa3b0c6be775c7ab02bedc7c">ModuleCallback</a></td>
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

<p>Splits the module M into N linkable partitions.</p>


<p>The function ModuleCallback is called N times passing each individual partition as the MPart argument.</p>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">AMDGPUSplitModule.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ModuleCreationCallback {#a942d2f73ab20f73f1a0a4ec25b6c4ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPUSplitModulePass::ModuleCreationCallback = 
      function_ref&lt;void(std::unique_ptr&lt;Module&gt; MPart)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">AMDGPUSplitModule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AMDGPUSplitModulePass() {#ab3f035b68b07684b1943c4e0296c0fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPUSplitModulePass::AMDGPUSplitModulePass (unsigned N, <a href="#a942d2f73ab20f73f1a0a4ec25b6c4ee7">ModuleCreationCallback</a> ModuleCallback)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">AMDGPUSplitModule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a5fdf4ead69288861f3151e0f035a9877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::AMDGPUSplitModulePass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">AMDGPUSplitModule.h</a>, definition at line 1527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a1fcefc1a8c747197b9ee8b5e99d732fca5efdb4b665559526df56fb2634198440">llvm::LockFileManager::LFS_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a1fcefc1a8c747197b9ee8b5e99d732fca78582d1ab0d9e0abbed2abbea232f529">llvm::LockFileManager::LFS_Owned</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a1fcefc1a8c747197b9ee8b5e99d732fcabfd64c399ca341b115a17cf25bf161a2">llvm::LockFileManager::LFS_Shared</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a03797a73044a81cbc6a3409d6c72ee8f">llvm::PreservedAnalyses::none</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a9973b06ec4b8e2f93a9308b85c1b8b30ae933c5a1f2e505b61d59df1e3937adef">llvm::LockFileManager::Res_OwnerDied</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a9973b06ec4b8e2f93a9308b85c1b8b30a213a07aec4e7e7d016b3bd594daf9cc5">llvm::LockFileManager::Res_Success</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a9973b06ec4b8e2f93a9308b85c1b8b30a2b00d68ed92fa7423fd1e18f31945d53">llvm::LockFileManager::Res_Timeout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0706966ac4f391854346bebfcda816fa">llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa676374c59d0f44d25f9eab4bb824e5a">llvm::sys::path::system_temp_directory</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a69275e764ccafbee027de7780fa72e4a">llvm::LockFileManager::unsafeRemoveLockFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a9e9d93a9c62f28bebeefb524a30f1d93">llvm::anonymous{AMDGPUSplitModule.cpp}::UseLockFile</a> and <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a8a975a4bfeea746f3269211bd72a02e2">llvm::LockFileManager::waitForUnlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ModuleCallback {#a7a3a2fa1aa3b0c6be775c7ab02bedc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleCreationCallback llvm::AMDGPUSplitModulePass::ModuleCallback</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">AMDGPUSplitModule.h</a>.</p>

</div>
</div>

### N {#ab34f21565b2efd00ed2df350a6fbff19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPUSplitModulePass::N</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">AMDGPUSplitModule.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-h">AMDGPUSplitModule.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
