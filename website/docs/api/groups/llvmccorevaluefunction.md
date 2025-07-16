---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccorevaluefunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Function values Reference

<p>Functions in this group operate on <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> instances that correspond to <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> instances. <a href="#details">More...</a></p>

## Topics Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">&nbsp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters">Function Parameters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functions in this group relate to arguments/parameters on functions. <a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">&nbsp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc">IFuncs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functions in this group relate to indirect functions. <a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa8acedb950255bbb2d3465a0f8566c7b">LLVMDeleteFunction</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a function from its containing module and deletes it. <a href="#gaa8acedb950255bbb2d3465a0f8566c7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga218b6abe1cb0d17a4b391c469f83e41c">LLVMHasPersonalityFn</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether the given function has a personality function. <a href="#ga218b6abe1cb0d17a4b391c469f83e41c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7670a34dfeaa752ade4fe558ffb66461">LLVMGetPersonalityFn</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the personality function attached to the function. <a href="#ga7670a34dfeaa752ade4fe558ffb66461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga88008596c85da600f6f1dabaddca0cbb">LLVMSetPersonalityFn</a> (LLVMValueRef Fn, LLVMValueRef PersonalityFn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the personality function attached to the function. <a href="#ga88008596c85da600f6f1dabaddca0cbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga23bc095aa18029df12ab92ba5a318c6f">LLVMLookupIntrinsicID</a> (const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the intrinsic ID number which matches the given function name. <a href="#ga23bc095aa18029df12ab92ba5a318c6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafc1954804ac052d9f6e4d83b3bf84883">LLVMGetIntrinsicID</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the ID number from a function instance. <a href="#gafc1954804ac052d9f6e4d83b3bf84883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae31cd442e48be38030a97c21a2c49867">LLVMGetIntrinsicDeclaration</a> (LLVMModuleRef Mod, unsigned ID, LLVMTypeRef *ParamTypes, size_t ParamCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or insert the declaration of an intrinsic. <a href="#gae31cd442e48be38030a97c21a2c49867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf963d0f39f7ed2d8442308e89f1d8440">LLVMIntrinsicGetType</a> (LLVMContextRef Ctx, unsigned ID, LLVMTypeRef *ParamTypes, size_t ParamCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the type of an intrinsic. <a href="#gaf963d0f39f7ed2d8442308e89f1d8440">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga309eb2a3dcfda4477f7361333f099569">LLVMIntrinsicGetName</a> (unsigned ID, size_t *NameLength)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the name of an intrinsic. <a href="#ga309eb2a3dcfda4477f7361333f099569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6171239b06f741cd21a74f4d45b751f6">LLVMIntrinsicCopyOverloadedName</a> (unsigned ID, LLVMTypeRef *ParamTypes, size_t ParamCount, size_t *NameLength)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMIntrinsicCopyOverloadedName2 instead. <a href="#ga6171239b06f741cd21a74f4d45b751f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9537e3801e0a920c4af76a4360baa99b">LLVMIntrinsicCopyOverloadedName2</a> (LLVMModuleRef Mod, unsigned ID, LLVMTypeRef *ParamTypes, size_t ParamCount, size_t *NameLength)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copies the name of an overloaded intrinsic identified by a given list of parameter types. <a href="#ga9537e3801e0a920c4af76a4360baa99b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8cfe249fbfe5f06962902b9dfa596268">LLVMIntrinsicIsOverloaded</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain if the intrinsic identified by the given ID is overloaded. <a href="#ga8cfe249fbfe5f06962902b9dfa596268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga36902516d7b958ce09642cfe8a96c887">LLVMGetFunctionCallConv</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the calling function of a function. <a href="#ga36902516d7b958ce09642cfe8a96c887">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad649aa9c83658568b13b0e7a923907a5">LLVMSetFunctionCallConv</a> (LLVMValueRef Fn, unsigned CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the calling convention of a function. <a href="#gad649aa9c83658568b13b0e7a923907a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga05dd91862aa31de6fddf862b2da61e0e">LLVMGetGC</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the name of the garbage collector to use during code generation. <a href="#ga05dd91862aa31de6fddf862b2da61e0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga02331e7467a65a33635143508c8eea6f">LLVMSetGC</a> (LLVMValueRef Fn, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define the garbage collector to use during code generation. <a href="#ga02331e7467a65a33635143508c8eea6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4246ace908088874d94aafd138383253">LLVMGetPrefixData</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the prefix data associated with a function. <a href="#ga4246ace908088874d94aafd138383253">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac4424192929aa410302a3bb672cbe39f">LLVMHasPrefixData</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if a given function has prefix data. <a href="#gac4424192929aa410302a3bb672cbe39f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6003a8e4114eb6e5975e268da0b5fdd6">LLVMSetPrefixData</a> (LLVMValueRef Fn, LLVMValueRef prefixData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the prefix data for the function. <a href="#ga6003a8e4114eb6e5975e268da0b5fdd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga065a12d4e9ebdd23c2f8c1a1f5483017">LLVMGetPrologueData</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the prologue data associated with a function. <a href="#ga065a12d4e9ebdd23c2f8c1a1f5483017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac33481c70e71efbd95b0ea799f97f912">LLVMHasPrologueData</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if a given function has prologue data. <a href="#gac33481c70e71efbd95b0ea799f97f912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac1b0cb00b05cd522c3dc8e5bcb9bb819">LLVMSetPrologueData</a> (LLVMValueRef Fn, LLVMValueRef prologueData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the prologue data for the function. <a href="#gac1b0cb00b05cd522c3dc8e5bcb9bb819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga90464bc79586959d90c20b021635e01f">LLVMAddAttributeAtIndex</a> (LLVMValueRef F, LLVMAttributeIndex Idx, LLVMAttributeRef A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute to a function. <a href="#ga90464bc79586959d90c20b021635e01f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1206bbcd0f9766ef1c245bcbc73ea3ce">LLVMGetAttributeCountAtIndex</a> (LLVMValueRef F, LLVMAttributeIndex Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac4ce54a01b54fa96b25aa786f6337876">LLVMGetAttributesAtIndex</a> (LLVMValueRef F, LLVMAttributeIndex Idx, LLVMAttributeRef *Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga17bcea87da25c658e082bec6009c6f88">LLVMAttributeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae931207c3ff590265efce7523fa2b0c2">LLVMGetEnumAttributeAtIndex</a> (LLVMValueRef F, LLVMAttributeIndex Idx, unsigned KindID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga17bcea87da25c658e082bec6009c6f88">LLVMAttributeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga755ae285a2445962f3ce85ad2b39b05b">LLVMGetStringAttributeAtIndex</a> (LLVMValueRef F, LLVMAttributeIndex Idx, const char *K, unsigned KLen)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga068463181807646a4d6219af88754a9e">LLVMRemoveEnumAttributeAtIndex</a> (LLVMValueRef F, LLVMAttributeIndex Idx, unsigned KindID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga47a0cb109be33a5646bebd995b065d92">LLVMRemoveStringAttributeAtIndex</a> (LLVMValueRef F, LLVMAttributeIndex Idx, const char *K, unsigned KLen)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaebff9c76379397445b16d0fa92720fb8">LLVMAddTargetDependentFunctionAttr</a> (LLVMValueRef Fn, const char *A, const char *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a target-dependent attribute to a function. <a href="#gaebff9c76379397445b16d0fa92720fb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Functions in this group operate on <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> instances that correspond to <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> instances.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a></p></dd>
</dl>


<div class="doxySectionDef">

## Functions

### LLVMAddAttributeAtIndex() {#ga90464bc79586959d90c20b021635e01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAddAttributeAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga579ba60395e1b097079def796ba16369">LLVMAttributeIndex</a> Idx, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga17bcea87da25c658e082bec6009c6f88">LLVMAttributeRef</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an attribute to a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::Function::addAttribute()</p></dd>
</dl>


<p>Declaration at line 2939 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2571 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMAddTargetDependentFunctionAttr() {#gaebff9c76379397445b16d0fa92720fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAddTargetDependentFunctionAttr (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a target-dependent attribute to a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a59d23ba2e7eac46cbc6cd3086e013b49">llvm::AttrBuilder::addAttribute()</a></p></dd>
</dl>


<p>Declaration at line 2959 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2612 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDeleteFunction() {#gaa8acedb950255bbb2d3465a0f8566c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDeleteFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a function from its containing module and deletes it.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a8969dec86d24dd579f8ecc963e1dc8b4">llvm::Function::eraseFromParent()</a></p></dd>
</dl>


<p>Declaration at line 2772 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2438 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetAttributeCountAtIndex() {#ga1206bbcd0f9766ef1c245bcbc73ea3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetAttributeCountAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga579ba60395e1b097079def796ba16369">LLVMAttributeIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2941 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2576 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetAttributesAtIndex() {#gac4ce54a01b54fa96b25aa786f6337876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMGetAttributesAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga579ba60395e1b097079def796ba16369">LLVMAttributeIndex</a> Idx, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga17bcea87da25c658e082bec6009c6f88">LLVMAttributeRef</a> * Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2942 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2581 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetEnumAttributeAtIndex() {#gae931207c3ff590265efce7523fa2b0c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMAttributeRef LLVMGetEnumAttributeAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga579ba60395e1b097079def796ba16369">LLVMAttributeIndex</a> Idx, unsigned KindID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2944 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2588 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetFunctionCallConv() {#ga36902516d7b958ce09642cfe8a96c887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetFunctionCallConv (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the calling function of a function.</p>


<p>The returned value corresponds to the <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga6bd315e1c1c05eb625e59a9f748e924f">LLVMCallConv</a> enumeration.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv()</a></p></dd>
</dl>


<p>Declaration at line 2869 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2517 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetGC() {#ga05dd91862aa31de6fddf862b2da61e0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetGC (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the name of the garbage collector to use during code generation.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#aa180549a789e99a98e599e8e183c4773">llvm::Function::getGC()</a></p></dd>
</dl>


<p>Declaration at line 2887 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2526 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetIntrinsicDeclaration() {#gae31cd442e48be38030a97c21a2c49867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetIntrinsicDeclaration (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> Mod, unsigned ID, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> * ParamTypes, size_t ParamCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or insert the declaration of an intrinsic.</p>


<p>For overloaded intrinsics, parameter types must be provided to uniquely identify an overload.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration()</a></p></dd>
</dl>


<p>Declaration at line 2815 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2466 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a7ff1aa840178d50242fcc198d2f9e399">llvm_map_to_intrinsic_id</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetIntrinsicID() {#gafc1954804ac052d9f6e4d83b3bf84883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetIntrinsicID (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the ID number from a function instance.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">llvm::Function::getIntrinsicID()</a></p></dd>
</dl>


<p>Declaration at line 2807 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2455 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetPersonalityFn() {#ga7670a34dfeaa752ade4fe558ffb66461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetPersonalityFn (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the personality function attached to the function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a6f77e4e800ba4dffd63e8ddb330062aa">llvm::Function::getPersonalityFn()</a></p></dd>
</dl>


<p>Declaration at line 2786 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2446 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetPrefixData() {#ga4246ace908088874d94aafd138383253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetPrefixData (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the prefix data associated with a function.</p>


<p>Only valid on functions, and only if LLVMHasPrefixData returns true. See <a href="https://llvm.org/docs/LangRef.html#prefix-data">https://llvm.org/docs/LangRef.html#prefix-data</a></p>


<p>Declaration at line 2901 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2539 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetPrologueData() {#ga065a12d4e9ebdd23c2f8c1a1f5483017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetPrologueData (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the prologue data associated with a function.</p>


<p>Only valid on functions, and only if LLVMHasPrologueData returns true. See <a href="https://llvm.org/docs/LangRef.html#prologue-data">https://llvm.org/docs/LangRef.html#prologue-data</a></p>


<p>Declaration at line 2920 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2555 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetStringAttributeAtIndex() {#ga755ae285a2445962f3ce85ad2b39b05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMAttributeRef LLVMGetStringAttributeAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga579ba60395e1b097079def796ba16369">LLVMAttributeIndex</a> Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * K, unsigned KLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2947 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2595 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMHasPersonalityFn() {#ga218b6abe1cb0d17a4b391c469f83e41c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMHasPersonalityFn (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether the given function has a personality function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a6a0f6312963ee6fb0969243607174949">llvm::Function::hasPersonalityFn()</a></p></dd>
</dl>


<p>Declaration at line 2779 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2442 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMHasPrefixData() {#gac4424192929aa410302a3bb672cbe39f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMHasPrefixData (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if a given function has prefix data.</p>


<p>Only valid on functions. See <a href="https://llvm.org/docs/LangRef.html#prefix-data">https://llvm.org/docs/LangRef.html#prefix-data</a></p>


<p>Declaration at line 2907 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2544 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMHasPrologueData() {#gac33481c70e71efbd95b0ea799f97f912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMHasPrologueData (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if a given function has prologue data.</p>


<p>Only valid on functions. See <a href="https://llvm.org/docs/LangRef.html#prologue-data">https://llvm.org/docs/LangRef.html#prologue-data</a></p>


<p>Declaration at line 2926 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2560 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMIntrinsicCopyOverloadedName() {#ga6171239b06f741cd21a74f4d45b751f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * LLVMIntrinsicCopyOverloadedName (unsigned ID, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> * ParamTypes, size_t ParamCount, size_t * NameLength)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMIntrinsicCopyOverloadedName2 instead.</p>

<p>Declaration at line 2837 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2489 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a3b2b24ea2831ebf75ab12501d3ca89e8">llvm::Intrinsic::getNameNoUnnamedTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a7ff1aa840178d50242fcc198d2f9e399">llvm_map_to_intrinsic_id</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMIntrinsicCopyOverloadedName2() {#ga9537e3801e0a920c4af76a4360baa99b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * LLVMIntrinsicCopyOverloadedName2 (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> Mod, unsigned ID, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> * ParamTypes, size_t ParamCount, size_t * NameLength)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copies the name of an overloaded intrinsic identified by a given list of parameter types.</p>


<p>Unlike LLVMIntrinsicGetName, the caller is responsible for freeing the returned string.</p>


<p>This version also supports unnamed types.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7157f9fa9dd11f234ec3c58517cb6d96">llvm::Intrinsic::getName()</a></p></dd>
</dl>


<p>Declaration at line 2851 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2498 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7157f9fa9dd11f234ec3c58517cb6d96">llvm::Intrinsic::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a7ff1aa840178d50242fcc198d2f9e399">llvm_map_to_intrinsic_id</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMIntrinsicGetName() {#ga309eb2a3dcfda4477f7361333f099569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMIntrinsicGetName (unsigned ID, size_t * NameLength)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves the name of an intrinsic.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7157f9fa9dd11f234ec3c58517cb6d96">llvm::Intrinsic::getName()</a></p></dd>
</dl>


<p>Declaration at line 2834 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2475 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7157f9fa9dd11f234ec3c58517cb6d96">llvm::Intrinsic::getName</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a7ff1aa840178d50242fcc198d2f9e399">llvm_map_to_intrinsic_id</a>.</p>

</div>
</div>

### LLVMIntrinsicGetType() {#gaf963d0f39f7ed2d8442308e89f1d8440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTypeRef LLVMIntrinsicGetType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> Ctx, unsigned ID, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> * ParamTypes, size_t ParamCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves the type of an intrinsic.</p>


<p>For overloaded intrinsics, parameter types must be provided to uniquely identify an overload.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType()</a></p></dd>
</dl>


<p>Declaration at line 2826 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2482 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a7ff1aa840178d50242fcc198d2f9e399">llvm_map_to_intrinsic_id</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMIntrinsicIsOverloaded() {#ga8cfe249fbfe5f06962902b9dfa596268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMIntrinsicIsOverloaded (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain if the intrinsic identified by the given ID is overloaded.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#ab2d91e185087b0ac1f22ef439a170c7f">llvm::Intrinsic::isOverloaded()</a></p></dd>
</dl>


<p>Declaration at line 2860 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2512 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#ab2d91e185087b0ac1f22ef439a170c7f">llvm::Intrinsic::isOverloaded</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a7ff1aa840178d50242fcc198d2f9e399">llvm_map_to_intrinsic_id</a>.</p>

</div>
</div>

### LLVMLookupIntrinsicID() {#ga23bc095aa18029df12ab92ba5a318c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMLookupIntrinsicID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the intrinsic ID number which matches the given function name.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a821cf516da0409f54e4cd8a5b7478ea7">llvm::Intrinsic::lookupIntrinsicID()</a></p></dd>
</dl>


<p>Declaration at line 2800 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2508 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a821cf516da0409f54e4cd8a5b7478ea7">llvm::Intrinsic::lookupIntrinsicID</a>.</p>

</div>
</div>

### LLVMRemoveEnumAttributeAtIndex() {#ga068463181807646a4d6219af88754a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRemoveEnumAttributeAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga579ba60395e1b097079def796ba16369">LLVMAttributeIndex</a> Idx, unsigned KindID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2950 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2602 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemoveStringAttributeAtIndex() {#ga47a0cb109be33a5646bebd995b065d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRemoveStringAttributeAtIndex (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga579ba60395e1b097079def796ba16369">LLVMAttributeIndex</a> Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * K, unsigned KLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2952 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2607 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetFunctionCallConv() {#gad649aa9c83658568b13b0e7a923907a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetFunctionCallConv (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, unsigned CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the calling convention of a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#ae6db8746934e6feae3649a8709fce3cc">llvm::Function::setCallingConv()</a></p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>Function to operate on</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CC</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga6bd315e1c1c05eb625e59a9f748e924f">LLVMCallConv</a> to set calling convention to</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2879 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetGC() {#ga02331e7467a65a33635143508c8eea6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetGC (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define the garbage collector to use during code generation.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a455032eb7bfb230b908159d9b1c1fbf1">llvm::Function::setGC()</a></p></dd>
</dl>


<p>Declaration at line 2894 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2531 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetPersonalityFn() {#ga88008596c85da600f6f1dabaddca0cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetPersonalityFn (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> PersonalityFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the personality function attached to the function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a6f9ba62511c44dd991c6cd7485098d15">llvm::Function::setPersonalityFn()</a></p></dd>
</dl>


<p>Declaration at line 2793 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2450 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetPrefixData() {#ga6003a8e4114eb6e5975e268da0b5fdd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetPrefixData (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> prefixData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the prefix data for the function.</p>


<p>Only valid on functions. See <a href="https://llvm.org/docs/LangRef.html#prefix-data">https://llvm.org/docs/LangRef.html#prefix-data</a></p>


<p>Declaration at line 2913 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2549 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetPrologueData() {#gac1b0cb00b05cd522c3dc8e5bcb9bb819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetPrologueData (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> prologueData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the prologue data for the function.</p>


<p>Only valid on functions. See <a href="https://llvm.org/docs/LangRef.html#prologue-data">https://llvm.org/docs/LangRef.html#prologue-data</a></p>


<p>Declaration at line 2932 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2565 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
