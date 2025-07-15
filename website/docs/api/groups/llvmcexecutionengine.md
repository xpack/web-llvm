---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcexecutionengine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Execution Engine Reference



## Topics Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">&nbsp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit">LLJIT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">&nbsp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc">On-Request-Compilation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">&nbsp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorcee">ExecutionEngine-based ORC Utils</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmmcjitcompileroptions">LLVMMCJITCompilerOptions</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueGenericValue * <a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueExecutionEngine * <a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueMCJITMemoryManager * <a href="#ga47d080c636e2513b2a5f6df4e5089331">LLVMMCJITMemoryManagerRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint8_t *(* <a href="#gad54344e18e0839b6b3f39d598c5598f0">LLVMMemoryManagerAllocateCodeSectionCallback</a>)(void *Opaque, uintptr_t Size, unsigned Alignment, unsigned SectionID, const char *SectionName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint8_t *(* <a href="#gabe63644e7847066c1ac90ad487040e26">LLVMMemoryManagerAllocateDataSectionCallback</a>)(void *Opaque, uintptr_t Size, unsigned Alignment, unsigned SectionID, const char *SectionName, LLVMBool IsReadOnly)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a>(* <a href="#gaa3aa0817f65b3ec44e6e3b797570f05e">LLVMMemoryManagerFinalizeMemoryCallback</a>)(void *Opaque, char **ErrMsg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#ga4e9770ff745f02b2bf2e473b3f5a7c58">LLVMMemoryManagerDestroyCallback</a>)(void *Opaque)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf1eab65125720bae634fafd85a8ec3cc">LLVMLinkInMCJIT</a> (void)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacfb50cdd5f90d54ad40791117dfdc182">LLVMLinkInInterpreter</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga49e6ddbb4ef1d059831f3dc1e82141d9">LLVMCreateGenericValueOfInt</a> (LLVMTypeRef Ty, unsigned long long N, LLVMBool IsSigned)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga06ad92a8617a97e7e453ff49d90c6b71">LLVMCreateGenericValueOfPointer</a> (void *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabdeddb888028f5efec64d710a5c70e83">LLVMCreateGenericValueOfFloat</a> (LLVMTypeRef Ty, double N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa421945b748ce861b4da63b752d71dd0">LLVMGenericValueIntWidth</a> (LLVMGenericValueRef GenValRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned long long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaca63029362a3a1da53f00e79b6423aac">LLVMGenericValueToInt</a> (LLVMGenericValueRef GenVal, LLVMBool IsSigned)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa3416adf40900123d7b89636ddcbdcc5">LLVMGenericValueToPointer</a> (LLVMGenericValueRef GenVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga07086a2b6347e7f7e96a841331c7e55b">LLVMGenericValueToFloat</a> (LLVMTypeRef TyRef, LLVMGenericValueRef GenVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf707d95b406db806bc8eb204f7700864">LLVMDisposeGenericValue</a> (LLVMGenericValueRef GenVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6f420f2ade2b50519ec53fd459a8f267">LLVMCreateExecutionEngineForModule</a> (LLVMExecutionEngineRef *OutEE, LLVMModuleRef M, char **OutError)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf1bf484a8108f125ccdb6ab37e317541">LLVMCreateInterpreterForModule</a> (LLVMExecutionEngineRef *OutInterp, LLVMModuleRef M, char **OutError)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga34adfbd03647338dab2a1eb687bed23f">LLVMCreateJITCompilerForModule</a> (LLVMExecutionEngineRef *OutJIT, LLVMModuleRef M, unsigned OptLevel, char **OutError)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga309aa3e39fc7798d20b6bf9515e3e036">LLVMInitializeMCJITCompilerOptions</a> (struct LLVMMCJITCompilerOptions *Options, size_t SizeOfOptions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a> (LLVMExecutionEngineRef *OutJIT, LLVMModuleRef M, struct LLVMMCJITCompilerOptions *Options, size_t SizeOfOptions, char **OutError)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an MCJIT execution engine for a module, with the given options. <a href="#gaa97dff3ed910ce2e0fc7c96b50b1c897">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5b8653e541777c1a7c16ceaa6a700d63">LLVMDisposeExecutionEngine</a> (LLVMExecutionEngineRef EE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa7141f3cda4991efbe28e61b2dbd08b5">LLVMRunStaticConstructors</a> (LLVMExecutionEngineRef EE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga33568bc0f7c510480c433d4df8d04abe">LLVMRunStaticDestructors</a> (LLVMExecutionEngineRef EE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacd0ee27ebf14f85b6c60a2719aa3d6cb">LLVMRunFunctionAsMain</a> (LLVMExecutionEngineRef EE, LLVMValueRef F, unsigned ArgC, const char *const *ArgV, const char *const *EnvP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4fa484f1f82bf67cdc7448dcdf552c5c">LLVMRunFunction</a> (LLVMExecutionEngineRef EE, LLVMValueRef F, unsigned NumArgs, LLVMGenericValueRef *Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf43ee3a0904d16f0aded9e5c5a265479">LLVMFreeMachineCodeForFunction</a> (LLVMExecutionEngineRef EE, LLVMValueRef F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8436d8ec5b8a5c275741b80a184a84a9">LLVMAddModule</a> (LLVMExecutionEngineRef EE, LLVMModuleRef M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8575599668ea7c9ab24a07f284a3f5d8">LLVMRemoveModule</a> (LLVMExecutionEngineRef EE, LLVMModuleRef M, LLVMModuleRef *OutMod, char **OutError)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4562a52ab9452ea52ad2ba0e4431f0f5">LLVMFindFunction</a> (LLVMExecutionEngineRef EE, const char *Name, LLVMValueRef *OutFn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5ebfce0fa79382f31cc8ac7c94fe1005">LLVMRecompileAndRelinkFunction</a> (LLVMExecutionEngineRef EE, LLVMValueRef Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gace7868f675950a8dfc3338b14652c686">LLVMTargetDataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga52b77fb8b762e79ee2fe122ef444c9c7">LLVMGetExecutionEngineTargetData</a> (LLVMExecutionEngineRef EE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafc2049f7f859e0a4aed11e867875199a">LLVMGetExecutionEngineTargetMachine</a> (LLVMExecutionEngineRef EE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad9a0b1cd6cdb55a36b5a89d51c854d18">LLVMAddGlobalMapping</a> (LLVMExecutionEngineRef EE, LLVMValueRef Global, void *Addr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad2874f2c79dbf2e6c54b12243c42b503">LLVMGetPointerToGlobal</a> (LLVMExecutionEngineRef EE, LLVMValueRef Global)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7bf19b4c7ba456f6dd359b85080cdf5f">LLVMGetGlobalValueAddress</a> (LLVMExecutionEngineRef EE, const char *Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6c8351b64eefd171f885fd22fb04d04f">LLVMGetFunctionAddress</a> (LLVMExecutionEngineRef EE, const char *Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga26a3a9d6a21587133d8feb6f4fd9900a">LLVMExecutionEngineGetErrMsg</a> (LLVMExecutionEngineRef EE, char **OutError)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true on error, false on success. <a href="#ga26a3a9d6a21587133d8feb6f4fd9900a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga47d080c636e2513b2a5f6df4e5089331">LLVMMCJITMemoryManagerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2b8d8487e4ecc0bc175b2964fd70d502">LLVMCreateSimpleMCJITMemoryManager</a> (void *Opaque, LLVMMemoryManagerAllocateCodeSectionCallback AllocateCodeSection, LLVMMemoryManagerAllocateDataSectionCallback AllocateDataSection, LLVMMemoryManagerFinalizeMemoryCallback FinalizeMemory, LLVMMemoryManagerDestroyCallback Destroy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a simple custom MCJIT memory manager. <a href="#ga2b8d8487e4ecc0bc175b2964fd70d502">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4cbc77344aa766fc78145ea1472c0547">LLVMDisposeMCJITMemoryManager</a> (LLVMMCJITMemoryManagerRef MM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad4bf262b53178061f7b936e3d1ff43bf">LLVMJITEventListenerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9ff6e0b848af7f64c654c8240e1fb4ab">LLVMCreateGDBRegistrationListener</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad4bf262b53178061f7b936e3d1ff43bf">LLVMJITEventListenerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8feedaf2301fb3a7dc2e7e5f66328bba">LLVMCreateIntelJITEventListener</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad4bf262b53178061f7b936e3d1ff43bf">LLVMJITEventListenerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga07411f28dc370e0ece91597b7449f764">LLVMCreateOProfileJITEventListener</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad4bf262b53178061f7b936e3d1ff43bf">LLVMJITEventListenerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5b912f524525c4df3780b8cb3629b9d7">LLVMCreatePerfJITEventListener</a> (void)</td>
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

## Typedefs

### LLVMExecutionEngineRef {#ga6b6396d4d249f6d63508014b66c3507e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueExecutionEngine* LLVMExecutionEngineRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### LLVMGenericValueRef {#ga9fcd660f552e45f95f767b26c16843c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueGenericValue* LLVMGenericValueRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### LLVMMCJITMemoryManagerRef {#ga47d080c636e2513b2a5f6df4e5089331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueMCJITMemoryManager* LLVMMCJITMemoryManagerRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### LLVMMemoryManagerAllocateCodeSectionCallback {#gad54344e18e0839b6b3f39d598c5598f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint8_t *(* LLVMMemoryManagerAllocateCodeSectionCallback) (void *Opaque, uintptr_t Size, unsigned Alignment, unsigned SectionID, const char *SectionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### LLVMMemoryManagerAllocateDataSectionCallback {#gabe63644e7847066c1ac90ad487040e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint8_t *(* LLVMMemoryManagerAllocateDataSectionCallback) (void *Opaque, uintptr_t Size, unsigned Alignment, unsigned SectionID, const char *SectionName, LLVMBool IsReadOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### LLVMMemoryManagerDestroyCallback {#ga4e9770ff745f02b2bf2e473b3f5a7c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* LLVMMemoryManagerDestroyCallback) (void *Opaque)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### LLVMMemoryManagerFinalizeMemoryCallback {#gaa3aa0817f65b3ec44e6e3b797570f05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef LLVMBool(* LLVMMemoryManagerFinalizeMemoryCallback) (void *Opaque, char **ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMAddGlobalMapping() {#gad9a0b1cd6cdb55a36b5a89d51c854d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAddGlobalMapping (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Global, void * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMAddModule() {#ga8436d8ec5b8a5c275741b80a184a84a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAddModule (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMCreateExecutionEngineForModule() {#ga6f420f2ade2b50519ec53fd459a8f267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMCreateExecutionEngineForModule (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> * OutEE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, char ** OutError)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#aaccaa0649b2f09dfcb7123300ccd3d19">llvm::EngineBuilder::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#abb7d2ddf5905447f9b10f887bfe6d27d">llvm::EngineKind::Either</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a960c0e2e27d0ccef2db82f261a475ef9">llvm::EngineBuilder::setEngineKind</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a8537e02128a9b4bd244dcb08f0da1fbe">llvm::EngineBuilder::setErrorStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateGDBRegistrationListener() {#ga9ff6e0b848af7f64c654c8240e1fb4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMJITEventListenerRef LLVMCreateGDBRegistrationListener (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#a004abbb5a0d48ac376dfbe3e3c97c306">llvm::JITEventListener::createGDBRegistrationListener</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateGenericValueOfFloat() {#gabdeddb888028f5efec64d710a5c70e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMGenericValueRef LLVMCreateGenericValueOfFloat (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> Ty, double N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a62734f5491c71583869b1da8d274dc45">getTypeID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateGenericValueOfInt() {#ga49e6ddbb4ef1d059831f3dc1e82141d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMGenericValueRef LLVMCreateGenericValueOfInt (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> Ty, unsigned long long N, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateGenericValueOfPointer() {#ga06ad92a8617a97e7e453ff49d90c6b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMGenericValueRef LLVMCreateGenericValueOfPointer (void * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a23f8c75218aea0cfcfe0f3e4223d3b02">llvm::GenericValue::PointerVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateIntelJITEventListener() {#ga8feedaf2301fb3a7dc2e7e5f66328bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMJITEventListenerRef LLVMCreateIntelJITEventListener (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#a8fc9cd1088989682b3d72a2560d0c577">llvm::JITEventListener::createIntelJITEventListener</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateInterpreterForModule() {#gaf1bf484a8108f125ccdb6ab37e317541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMCreateInterpreterForModule (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> * OutInterp, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, char ** OutError)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#aaccaa0649b2f09dfcb7123300ccd3d19">llvm::EngineBuilder::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441acbd7ec5d01190e525d2f938b169b9a81">llvm::EngineKind::Interpreter</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a960c0e2e27d0ccef2db82f261a475ef9">llvm::EngineBuilder::setEngineKind</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a8537e02128a9b4bd244dcb08f0da1fbe">llvm::EngineBuilder::setErrorStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateJITCompilerForModule() {#ga34adfbd03647338dab2a1eb687bed23f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMCreateJITCompilerForModule (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> * OutJIT, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, unsigned OptLevel, char ** OutError)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#aaccaa0649b2f09dfcb7123300ccd3d19">llvm::EngineBuilder::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441a41413991d9e4a8c017e9d83f8446d875">llvm::EngineKind::JIT</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a960c0e2e27d0ccef2db82f261a475ef9">llvm::EngineBuilder::setEngineKind</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a8537e02128a9b4bd244dcb08f0da1fbe">llvm::EngineBuilder::setErrorStr</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a4908930f1022471c7a7f366c94b52032">llvm::EngineBuilder::setOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateMCJITCompilerForModule() {#gaa97dff3ed910ce2e0fc7c96b50b1c897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMCreateMCJITCompilerForModule (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> * OutJIT, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, struct <a href="/web-llvm/docs/api/structs/llvmmcjitcompileroptions">LLVMMCJITCompilerOptions</a> * Options, size_t SizeOfOptions, char ** OutError)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an MCJIT execution engine for a module, with the given options.</p>


<p>It is the responsibility of the caller to ensure that all fields in Options up to the given SizeOfOptions are initialized. It is correct to pass a smaller value of SizeOfOptions that omits some fields. The canonical way of using this is:</p>


<p><a href="/web-llvm/docs/api/structs/llvmmcjitcompileroptions">LLVMMCJITCompilerOptions</a> options; LLVMInitializeMCJITCompilerOptions(&amp;options, sizeof(options)); ... fill in those options you care about LLVMCreateMCJITCompilerForModule(&amp;jit, mod, &amp;options, sizeof(options),
                                 &amp;error);</p>


<p>Note that this is also correct, though possibly suboptimal:</p>


<p>LLVMCreateMCJITCompilerForModule(&amp;jit, mod, 0, 0, &amp;error);</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#aaccaa0649b2f09dfcb7123300ccd3d19">llvm::EngineBuilder::create</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ab26d50483184808463759bea1da917f8">llvm::TargetOptions::EnableFastISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441a41413991d9e4a8c017e9d83f8446d875">llvm::EngineKind::JIT</a>, <a href="#ga309aa3e39fc7798d20b6bf9515e3e036">LLVMInitializeMCJITCompilerOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a387f51a24c0f1df5c0337ba630eb8f54">llvm::EngineBuilder::setCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a960c0e2e27d0ccef2db82f261a475ef9">llvm::EngineBuilder::setEngineKind</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a8537e02128a9b4bd244dcb08f0da1fbe">llvm::EngineBuilder::setErrorStr</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a158be06e8bc0c3e9caafba69adadaaa4">llvm::EngineBuilder::setMCJITMemoryManager</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a4908930f1022471c7a7f366c94b52032">llvm::EngineBuilder::setOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a08c232e2416c85bdc2e479bb8f77448f">llvm::EngineBuilder::setTargetOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateOProfileJITEventListener() {#ga07411f28dc370e0ece91597b7449f764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMJITEventListenerRef LLVMCreateOProfileJITEventListener (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#ada1f87075221bc4d64d42c15b6e47e54">llvm::JITEventListener::createOProfileJITEventListener</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreatePerfJITEventListener() {#ga5b912f524525c4df3780b8cb3629b9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMJITEventListenerRef LLVMCreatePerfJITEventListener (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#acaa6e4061784b1c2064eafe1adaef7e5">llvm::JITEventListener::createPerfJITEventListener</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateSimpleMCJITMemoryManager() {#ga2b8d8487e4ecc0bc175b2964fd70d502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMCJITMemoryManagerRef LLVMCreateSimpleMCJITMemoryManager (void * Opaque, <a href="#gad54344e18e0839b6b3f39d598c5598f0">LLVMMemoryManagerAllocateCodeSectionCallback</a> AllocateCodeSection, <a href="#gabe63644e7847066c1ac90ad487040e26">LLVMMemoryManagerAllocateDataSectionCallback</a> AllocateDataSection, <a href="#gaa3aa0817f65b3ec44e6e3b797570f05e">LLVMMemoryManagerFinalizeMemoryCallback</a> FinalizeMemory, <a href="#ga4e9770ff745f02b2bf2e473b3f5a7c58">LLVMMemoryManagerDestroyCallback</a> Destroy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a simple custom MCJIT memory manager.</p>


<p>This memory manager can intercept allocations in a module-oblivious way. This will return NULL if any of the passed functions are NULL.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Opaque</td>
<td class="doxyParamItemDescription"><p>An opaque client object to pass back to the callbacks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocateCodeSection</td>
<td class="doxyParamItemDescription"><p>Allocate a block of memory for executable code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocateDataSection</td>
<td class="doxyParamItemDescription"><p>Allocate a block of memory for data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FinalizeMemory</td>
<td class="doxyParamItemDescription"><p>Set page permissions and flush cache. Return 0 on success, 1 on error.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDisposeExecutionEngine() {#ga5b8653e541777c1a7c16ceaa6a700d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeExecutionEngine (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeGenericValue() {#gaf707d95b406db806bc8eb204f7700864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeGenericValue (<a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a> GenVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeMCJITMemoryManager() {#ga4cbc77344aa766fc78145ea1472c0547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeMCJITMemoryManager (<a href="#ga47d080c636e2513b2a5f6df4e5089331">LLVMMCJITMemoryManagerRef</a> MM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMExecutionEngineGetErrMsg() {#ga26a3a9d6a21587133d8feb6f4fd9900a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMExecutionEngineGetErrMsg (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, char ** OutError)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true on error, false on success.</p>


<p>If true is returned then the error message is copied to OutStr and cleared in the ExecutionEngine instance.</p>


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMFindFunction() {#ga4562a52ab9452ea52ad2ba0e4431f0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMFindFunction (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> * OutFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMFreeMachineCodeForFunction() {#gaf43ee3a0904d16f0aded9e5c5a265479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMFreeMachineCodeForFunction (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### LLVMGenericValueIntWidth() {#gaa421945b748ce861b4da63b752d71dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGenericValueIntWidth (<a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a> GenValRef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGenericValueToFloat() {#ga07086a2b6347e7f7e96a841331c7e55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double LLVMGenericValueToFloat (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> TyRef, <a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a> GenVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a62734f5491c71583869b1da8d274dc45">getTypeID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGenericValueToInt() {#gaca63029362a3a1da53f00e79b6423aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned long long LLVMGenericValueToInt (<a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a> GenVal, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGenericValueToPointer() {#gaa3416adf40900123d7b89636ddcbdcc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * LLVMGenericValueToPointer (<a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a> GenVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetExecutionEngineTargetData() {#ga52b77fb8b762e79ee2fe122ef444c9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTargetDataRef LLVMGetExecutionEngineTargetData (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetExecutionEngineTargetMachine() {#gafc2049f7f859e0a4aed11e867875199a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTargetMachineRef LLVMGetExecutionEngineTargetMachine (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetFunctionAddress() {#ga6c8351b64eefd171f885fd22fb04d04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetFunctionAddress (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetGlobalValueAddress() {#ga7bf19b4c7ba456f6dd359b85080cdf5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetGlobalValueAddress (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetPointerToGlobal() {#gad2874f2c79dbf2e6c54b12243c42b503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * LLVMGetPointerToGlobal (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Global)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMInitializeMCJITCompilerOptions() {#ga309aa3e39fc7798d20b6bf9515e3e036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMInitializeMCJITCompilerOptions (struct <a href="/web-llvm/docs/api/structs/llvmmcjitcompileroptions">LLVMMCJITCompilerOptions</a> * Options, size_t SizeOfOptions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/llvmctarget/#gga333ec2da299d964c0885bee025bef68caaff98ca9c22c3a1e097bd5c84cabbf6b">LLVMCodeModelJITDefault</a>.</p>


<p>Referenced by <a href="#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### LLVMLinkInInterpreter() {#gacfb50cdd5f90d54ad40791117dfdc182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMLinkInInterpreter (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-cpp">Interpreter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-interpreter-h-/forceinterpreterlinking/#a94b284ee30cd1a18ccab6ee37d8302a5">anonymous{Interpreter.h}::ForceInterpreterLinking::ForceInterpreterLinking</a>.</p>

</div>
</div>

### LLVMLinkInMCJIT() {#gaf1eab65125720bae634fafd85a8ec3cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMLinkInMCJIT (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-mcjit-h-/forcemcjitlinking/#af9614b5f07f3f869caa129c49baa2027">anonymous{MCJIT.h}::ForceMCJITLinking::ForceMCJITLinking</a>.</p>

</div>
</div>

### LLVMRecompileAndRelinkFunction() {#ga5ebfce0fa79382f31cc8ac7c94fe1005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * LLVMRecompileAndRelinkFunction (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>

</div>
</div>

### LLVMRemoveModule() {#ga8575599668ea7c9ab24a07f284a3f5d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMRemoveModule (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> * OutMod, char ** OutError)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRunFunction() {#ga4fa484f1f82bf67cdc7448dcdf552c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMGenericValueRef LLVMRunFunction (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, unsigned NumArgs, <a href="#ga9fcd660f552e45f95f767b26c16843c6">LLVMGenericValueRef</a> * Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRunFunctionAsMain() {#gacd0ee27ebf14f85b6c60a2719aa3d6cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLVMRunFunctionAsMain (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> F, unsigned ArgC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * ArgV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * EnvP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRunStaticConstructors() {#gaa7141f3cda4991efbe28e61b2dbd08b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRunStaticConstructors (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRunStaticDestructors() {#ga33568bc0f7c510480c433d4df8d04abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRunStaticDestructors (<a href="#ga6b6396d4d249f6d63508014b66c3507e">LLVMExecutionEngineRef</a> EE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">ExecutionEngine.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp">ExecutionEngineBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
