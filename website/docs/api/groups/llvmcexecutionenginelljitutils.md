---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcexecutionenginelljitutils
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The LLJIT Utilities Reference



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7634ccfc36436905cf1dd2dac0d82443">LLVMOrcLLJITEnableDebugSupport</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Install the plugin that submits debug objects to the executor. <a href="#ga7634ccfc36436905cf1dd2dac0d82443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### LLVMOrcLLJITEnableDebugSupport() {#ga7634ccfc36436905cf1dd2dac0d82443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcLLJITEnableDebugSupport (<a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Install the plugin that submits debug objects to the executor.</p>


<p>Executors must expose the llvm_orc_registerJITLoaderGDBWrapper symbol.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljitutils-h">LLJITUtils.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/lljitutilscbindings-cpp">LLJITUtilsCBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad059d61cab7f6bc8ee555ae23acd7b52">llvm::orc::enableDebuggerSupport</a>, <a href="#ga7634ccfc36436905cf1dd2dac0d82443">LLVMOrcLLJITEnableDebugSupport</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>


<p>Referenced by <a href="#ga7634ccfc36436905cf1dd2dac0d82443">LLVMOrcLLJITEnableDebugSupport</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
