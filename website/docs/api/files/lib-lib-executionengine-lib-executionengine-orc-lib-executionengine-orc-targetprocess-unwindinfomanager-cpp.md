---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `UnwindInfoManager.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">llvm/ExecutionEngine/Orc/TargetProcess/UnwindInfoManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">llvm/ExecutionEngine/Orc/Shared/OrcRTBridge.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">llvm/ExecutionEngine/Orc/Shared/WrapperFunctionUtils.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc">orc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff8aeb48d20e809b4a16fbd321ac7e2">llvm_orc_rt_alt_UnwindInfoManager_register</a> (const char *Data, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b640b8a6b047c09de51d6e52697d6fe">llvm_orc_rt_alt_UnwindInfoManager_deregister</a> (const char *Data, uint64_t Size)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"orc"</td>
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

### llvm\_orc\_rt\_alt\_UnwindInfoManager\_deregister() {#a2b640b8a6b047c09de51d6e52697d6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::shared::CWrapperFunctionResult llvm_orc_rt_alt_UnwindInfoManager_deregister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, uint64_t Size)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#a77962f30a5593b989924def76d5ea7a7">llvm::orc::UnwindInfoManager::deregisterSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#a6cfb7c36eddb6eeab4a0dbece2b7f21c">llvm::orc::UnwindInfoManager::addBootstrapSymbols</a>.</p>

</div>
</div>

### llvm\_orc\_rt\_alt\_UnwindInfoManager\_register() {#abff8aeb48d20e809b4a16fbd321ac7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::shared::CWrapperFunctionResult llvm_orc_rt_alt_UnwindInfoManager_register (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, uint64_t Size)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#afdda747ca74c5dfd5f79c296d5d60332">llvm::orc::UnwindInfoManager::registerSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#a6cfb7c36eddb6eeab4a0dbece2b7f21c">llvm::orc::UnwindInfoManager::addBootstrapSymbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"orc"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
