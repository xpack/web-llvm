---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadervtune-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `JITLoaderVTune.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">llvm/ExecutionEngine/Orc/Shared/WrapperFunctionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include &lt;cstdint&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LLVM_ABI <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613afc00d323ade895afec5d579f21f3">llvm_orc_registerVTuneImpl</a> (const char *Data, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LLVM_ABI <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b3375bfac2cdb8bc007765276ce5e8">llvm_orc_unregisterVTuneImpl</a> (const char *Data, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LLVM_ABI <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de26932e77d5016828d574a1b1007ce">llvm_orc_test_registerVTuneImpl</a> (const char *Data, uint64_t Size)</td>
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

## Functions

### llvm\_orc\_registerVTuneImpl() {#a613afc00d323ade895afec5d579f21f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ABI llvm::orc::shared::CWrapperFunctionResult llvm_orc_registerVTuneImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadervtune-h">JITLoaderVTune.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadervtune-cpp">JITLoaderVTune.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadervtune-cpp/#a31ba992df2793ad95393f21cbfeaf0dc">unsupportedBatch</a>.</p>

</div>
</div>

### llvm\_orc\_test\_registerVTuneImpl() {#a8de26932e77d5016828d574a1b1007ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ABI llvm::orc::shared::CWrapperFunctionResult llvm_orc_test_registerVTuneImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadervtune-h">JITLoaderVTune.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadervtune-cpp">JITLoaderVTune.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadervtune-cpp/#a31ba992df2793ad95393f21cbfeaf0dc">unsupportedBatch</a>.</p>

</div>
</div>

### llvm\_orc\_unregisterVTuneImpl() {#a12b3375bfac2cdb8bc007765276ce5e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ABI llvm::orc::shared::CWrapperFunctionResult llvm_orc_unregisterVTuneImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadervtune-h">JITLoaderVTune.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadervtune-cpp">JITLoaderVTune.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadervtune-cpp/#ae2e3c946b03c742aeb13dfd06b8333fa">unsuppported</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
