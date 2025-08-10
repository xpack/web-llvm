---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccoreoperandbundle
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# Operand Bundles

<p>Functions in this group operate on <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a> instances that correspond to <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">llvm::OperandBundleDef</a> instances. <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga88a3896e64681d5a2978c71a9f07c95a">LLVMCreateOperandBundle</a> (const char *Tag, size_t TagLen, LLVMValueRef *Args, unsigned NumArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new operand bundle. <a href="#ga88a3896e64681d5a2978c71a9f07c95a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac37d053548cccbe37540b265ac187f91">LLVMDisposeOperandBundle</a> (LLVMOperandBundleRef Bundle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy an operand bundle. <a href="#gac37d053548cccbe37540b265ac187f91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad1417e9134fb0bc33e6cb0db083caadd">LLVMGetOperandBundleTag</a> (LLVMOperandBundleRef Bundle, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the tag of an operand bundle as a string. <a href="#gad1417e9134fb0bc33e6cb0db083caadd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga807b9252593720aa8d4a514e05551752">LLVMGetNumOperandBundleArgs</a> (LLVMOperandBundleRef Bundle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the number of operands for an operand bundle. <a href="#ga807b9252593720aa8d4a514e05551752">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4736de0180c9462663ed4c7097cd825a">LLVMGetOperandBundleArgAtIndex</a> (LLVMOperandBundleRef Bundle, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the operand for an operand bundle at the given index. <a href="#ga4736de0180c9462663ed4c7097cd825a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Functions in this group operate on <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a> instances that correspond to <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">llvm::OperandBundleDef</a> instances.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">llvm::OperandBundleDef</a></p></dd>
</dl>


<div class="doxySectionDef">

## Functions

### LLVMCreateOperandBundle() {#ga88a3896e64681d5a2978c71a9f07c95a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOperandBundleRef LLVMCreateOperandBundle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Tag, size_t TagLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> * Args, unsigned NumArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new operand bundle.</p>


<p>Every invocation should be paired with <a href="#gac37d053548cccbe37540b265ac187f91">LLVMDisposeOperandBundle()</a> or memory will be leaked.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tag</td>
<td class="doxyParamItemDescription"><p>Tag name of the operand bundle</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TagLen</td>
<td class="doxyParamItemDescription"><p>Length of Tag</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Args</td>
<td class="doxyParamItemDescription"><p>Memory address of an array of bundle operands</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumArgs</td>
<td class="doxyParamItemDescription"><p>Length of Args</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3274 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2745 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDisposeOperandBundle() {#gac37d053548cccbe37540b265ac187f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeOperandBundle (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a> Bundle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy an operand bundle.</p>


<p>This must be called for every created operand bundle or memory will be leaked.</p>


<p>Declaration at line 3284 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2752 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetNumOperandBundleArgs() {#ga807b9252593720aa8d4a514e05551752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetNumOperandBundleArgs (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a> Bundle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the number of operands for an operand bundle.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bundle</td>
<td class="doxyParamItemDescription"><p>Operand bundle to obtain operand count of.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of operands.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>OperandBundleDef::input_size()</p></dd>
</dl>


<p>Declaration at line 3303 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2762 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetOperandBundleArgAtIndex() {#ga4736de0180c9462663ed4c7097cd825a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetOperandBundleArgAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a> Bundle, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the operand for an operand bundle at the given index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bundle</td>
<td class="doxyParamItemDescription"><p>Operand bundle to obtain operand of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Index</td>
<td class="doxyParamItemDescription"><p>An operand index, must be less than <a href="#ga807b9252593720aa8d4a514e05551752">LLVMGetNumOperandBundleArgs()</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The operand.</p></dd>
</dl>


<p>Declaration at line 3313 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2766 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetOperandBundleTag() {#gad1417e9134fb0bc33e6cb0db083caadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetOperandBundleTag (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a> Bundle, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the tag of an operand bundle as a string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bundle</td>
<td class="doxyParamItemDescription"><p>Operand bundle to obtain tag of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>Out parameter which holds the length of the returned string.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The tag name of Bundle.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>OperandBundleDef::getTag()</p></dd>
</dl>


<p>Declaration at line 3294 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2756 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
