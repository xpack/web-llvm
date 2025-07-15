---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccoretypefunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Function Types Reference



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8b0c32e7322e5c6c1bf7eb95b0961707">LLVMFunctionType</a> (LLVMTypeRef ReturnType, LLVMTypeRef *ParamTypes, unsigned ParamCount, LLVMBool IsVarArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a function type consisting of a specified signature. <a href="#ga8b0c32e7322e5c6c1bf7eb95b0961707">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2970f0f4d9ee8a0f811f762fb2fa7f82">LLVMIsFunctionVarArg</a> (LLVMTypeRef FunctionTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether a function type is variadic. <a href="#ga2970f0f4d9ee8a0f811f762fb2fa7f82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacfa4594cbff421733add602a413cae9f">LLVMGetReturnType</a> (LLVMTypeRef FunctionTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the Type this function Type returns. <a href="#gacfa4594cbff421733add602a413cae9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga44fa41d22ed1f589b8202272f54aad77">LLVMCountParamTypes</a> (LLVMTypeRef FunctionTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the number of parameters this function accepts. <a href="#ga44fa41d22ed1f589b8202272f54aad77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga83dd3a49a0f3f017f4233fc0d667bda2">LLVMGetParamTypes</a> (LLVMTypeRef FunctionTy, LLVMTypeRef *Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the types of a function's parameters. <a href="#ga83dd3a49a0f3f017f4233fc0d667bda2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### LLVMCountParamTypes() {#ga44fa41d22ed1f589b8202272f54aad77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMCountParamTypes (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> FunctionTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the number of parameters this function accepts.</p>

<p>Declaration at line 1428 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMFunctionType() {#ga8b0c32e7322e5c6c1bf7eb95b0961707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTypeRef LLVMFunctionType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> ReturnType, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> * ParamTypes, unsigned ParamCount, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a function type consisting of a specified signature.</p>


<p>The function is defined as a tuple of a return Type, a list of parameter types, and whether the function is variadic.</p>


<p>Declaration at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetParamTypes() {#ga83dd3a49a0f3f017f4233fc0d667bda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMGetParamTypes (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> FunctionTy, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> * Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the types of a function's parameters.</p>


<p>The Dest parameter should point to a pre-allocated array of <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> at least <a href="#ga44fa41d22ed1f589b8202272f54aad77">LLVMCountParamTypes()</a> large. On return, the first <a href="#ga44fa41d22ed1f589b8202272f54aad77">LLVMCountParamTypes()</a> entries in the array will be populated with <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> instances.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FunctionTy</td>
<td class="doxyParamItemDescription"><p>The function type to operate on.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dest</td>
<td class="doxyParamItemDescription"><p>Memory address of an array to be filled with result.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1441 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetReturnType() {#gacfa4594cbff421733add602a413cae9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTypeRef LLVMGetReturnType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> FunctionTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the Type this function Type returns.</p>

<p>Declaration at line 1423 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMIsFunctionVarArg() {#ga2970f0f4d9ee8a0f811f762fb2fa7f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMIsFunctionVarArg (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> FunctionTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether a function type is variadic.</p>

<p>Declaration at line 1418 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
