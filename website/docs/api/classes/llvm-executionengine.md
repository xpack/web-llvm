---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/executionengine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExecutionEngine` Class Reference

<p>Abstract interface for implementation execution of LLVM modules, designed to support both interpreter and just-in-time (JIT) compiler implementations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ExecutionEngine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">llvm/ExecutionEngine/ExecutionEngine.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interpreter">Interpreter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba576ac4fb51534183fcf896dd51be68">EngineBuilder</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92eef8691cfbe4446ee15d34258c3185">ExecutionEngine</a> (DataLayout DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3462fd165e3dcb3236dc69650d68ce6b">ExecutionEngine</a> (DataLayout DL, std::unique_ptr&lt; Module &gt; M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f9ec8ba2ed8dbf9b9c7f0bba1828402">ExecutionEngine</a> (std::unique_ptr&lt; Module &gt; M)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae854ad96a2f8cf76b7f4aef063bf19ce">~ExecutionEngine</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628a513b3b717f80fdc8e937cc503f26">addModule</a> (std::unique_ptr&lt; Module &gt; M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to the list of modules that we can JIT from. <a href="#a628a513b3b717f80fdc8e937cc503f26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec095fb0a6b58427bed62c3fa52fdc0">addObjectFile</a> (std::unique_ptr&lt; object::ObjectFile &gt; O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addObjectFile - Add an <a href="/web-llvm/docs/api/classes/llvm/objectfile">ObjectFile</a> to the execution engine. <a href="#a9ec095fb0a6b58427bed62c3fa52fdc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1c5c7eb8f616ebaec8be5d350d7ff8">addObjectFile</a> (object::OwningBinary&lt; object::ObjectFile &gt; O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc50fba7c734a3f4f2463826385ee3a">addArchive</a> (object::OwningBinary&lt; object::Archive &gt; A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addArchive - Add an Archive to the execution engine. <a href="#a2cc50fba7c734a3f4f2463826385ee3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a514dfa1719bb6dadcc8bb7b71619805e">removeModule</a> (Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeModule - Removes a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> from the list of modules, but does not free the module's memory. <a href="#a514dfa1719bb6dadcc8bb7b71619805e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af652436173a739833e0e382f181b2870">FindFunctionNamed</a> (StringRef FnName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindFunctionNamed - Search all of the active modules to find the function that defines FnName. <a href="#af652436173a739833e0e382f181b2870">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc4f77c7dbf7ed1f581b3773bc0f2df">FindGlobalVariableNamed</a> (StringRef Name, bool AllowInternal=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindGlobalVariableNamed - Search all of the active modules to find the global variable that defines Name. <a href="#abcc4f77c7dbf7ed1f581b3773bc0f2df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65a03b7fbdb7acd7be0bae506238c9d">runFunction</a> (Function *F, ArrayRef&lt; GenericValue &gt; ArgValues)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runFunction - Execute the specified function with the specified arguments, and return the result. <a href="#ac65a03b7fbdb7acd7be0bae506238c9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c7ab2f89968276b54abf516e3e37cb">getPointerToNamedFunction</a> (StringRef Name, bool AbortOnFailure=true)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToNamedFunction - This method returns the address of the specified function by using the dlsym function call. <a href="#ae8c7ab2f89968276b54abf516e3e37cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8771c83fc5aaa938bfa479cb99492335">mapSectionAddress</a> (const void *LocalAddress, uint64_t TargetAddress)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mapSectionAddress - map a section to its target address space value. <a href="#a8771c83fc5aaa938bfa479cb99492335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c3a5d438306a20122987aa04363f02">generateCodeForModule</a> (Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>generateCodeForModule - Run code generation for the specified module and load it into memory. <a href="#a63c3a5d438306a20122987aa04363f02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2973f596de3b640bdc087bf2d46bcfa">finalizeObject</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>finalizeObject - ensure the module is fully processed and is usable. <a href="#ab2973f596de3b640bdc087bf2d46bcfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8148bbdde0eb101f768526757cb754c8">hasError</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if an error has been recorded. <a href="#a8148bbdde0eb101f768526757cb754c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37455f3715f92a4bbc9d0ade8348374f">clearErrorMessage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the error message. <a href="#a37455f3715f92a4bbc9d0ade8348374f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3678bf0330f2bc1970117b384045616b">getErrorMessage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the most recent error message. <a href="#a3678bf0330f2bc1970117b384045616b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a34c6c082dc999d12f1f191b4108513">runStaticConstructorsDestructors</a> (bool isDtors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runStaticConstructorsDestructors - This method is used to execute all of the static constructors or destructors for a program. <a href="#a6a34c6c082dc999d12f1f191b4108513">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60823e6b4ff77b319b51c9eb634241e2">runStaticConstructorsDestructors</a> (Module &amp;module, bool isDtors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used to execute all of the static constructors or destructors for a particular module. <a href="#a60823e6b4ff77b319b51c9eb634241e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97bbf524ee03354bb73dce9614b0e959">runFunctionAsMain</a> (Function *Fn, const std::vector&lt; std::string &gt; &amp;argv, const char *const *envp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runFunctionAsMain - This is a helper function which wraps runFunction to handle the common task of starting up main with the specified argc, argv, and envp parameters. <a href="#a97bbf524ee03354bb73dce9614b0e959">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a805704b52a327cc6b37aebf9cba14169">addGlobalMapping</a> (const GlobalValue *GV, void *Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addGlobalMapping - Tell the execution engine that the specified global is at the specified location. <a href="#a805704b52a327cc6b37aebf9cba14169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd00b43a7e3416795b7a32d8e5c7131">addGlobalMapping</a> (StringRef Name, uint64_t Addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f60ea31c2022f7f13fab8faf988705">clearAllGlobalMappings</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearAllGlobalMappings - Clear all global mappings and start over again, for use in dynamic compilation scenarios to move globals. <a href="#a29f60ea31c2022f7f13fab8faf988705">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9565a2a404ec3802e545beb8f63fe347">clearGlobalMappingsFromModule</a> (Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearGlobalMappingsFromModule - Clear all global mappings that came from a particular module, because it has been removed from the JIT. <a href="#a9565a2a404ec3802e545beb8f63fe347">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae66e5ebc951c7d9c88c0c1884bd67872">updateGlobalMapping</a> (const GlobalValue *GV, void *Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateGlobalMapping - Replace an existing mapping for GV with a new address. <a href="#ae66e5ebc951c7d9c88c0c1884bd67872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb0a4c1d63616267c10b09286b36e8c">updateGlobalMapping</a> (StringRef Name, uint64_t Addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f6e6505348cc3f784771e75092c602">getAddressToGlobalIfAvailable</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAddressToGlobalIfAvailable - This returns the address of the specified global symbol. <a href="#ab2f6e6505348cc3f784771e75092c602">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b4671f69facc701332f9510ca436aa">getPointerToGlobalIfAvailable</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToGlobalIfAvailable - This returns the address of the specified global value if it is has already been codegen'd, otherwise it returns null. <a href="#a29b4671f69facc701332f9510ca436aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d335340f7ac093e81c965ba69a7aac">getPointerToGlobalIfAvailable</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9656c73d0da235ba5b99c14804175943">getPointerToGlobal</a> (const GlobalValue *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToGlobal - This returns the address of the specified global value. <a href="#a9656c73d0da235ba5b99c14804175943">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f6dc15011951227ed4065f2e934f90">getPointerToFunction</a> (Function *F)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToFunction - The different EE's represent function bodies in different ways. <a href="#a54f6dc15011951227ed4065f2e934f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aae274d0f4e7b494ee7807374f5c32b">getPointerToFunctionOrStub</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToFunctionOrStub - If the specified function has been code-gen'd, return a pointer to the function. <a href="#a3aae274d0f4e7b494ee7807374f5c32b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a966d4ff307d844ac32c737a521bbecd5">getGlobalValueAddress</a> (const std::string &amp;Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalValueAddress - Return the address of the specified global value. <a href="#a966d4ff307d844ac32c737a521bbecd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ddd3e40138980c68a2e1c4dadaed31">getFunctionAddress</a> (const std::string &amp;Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFunctionAddress - Return the address of the specified function. <a href="#a56ddd3e40138980c68a2e1c4dadaed31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8796e9969f3352978e7f26f3c6b3cbd7">getGlobalValueAtAddress</a> (void *Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalValueAtAddress - Return the LLVM global value object that starts at the specified address. <a href="#a8796e9969f3352978e7f26f3c6b3cbd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ed33d3b3f8b9e21167918d5de40014">StoreValueToMemory</a> (const GenericValue &amp;Val, GenericValue *Ptr, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StoreValueToMemory - Stores the data in Val of type Ty at address Ptr. <a href="#a08ed33d3b3f8b9e21167918d5de40014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38079cd1d3c8bc5f3aef1d3420c3b855">InitializeMemory</a> (const Constant *Init, void *Addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab06dbc788612fabca42c90bf2516afe">getOrEmitGlobalVariable</a> (const GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrEmitGlobalVariable - Return the address of the specified global variable, possibly emitting it to memory if needed. <a href="#aab06dbc788612fabca42c90bf2516afe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd2b4b92ca38812ca31640b0da14927">RegisterJITEventListener</a> (JITEventListener *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers a listener to be called back on various events within the JIT. <a href="#afcd2b4b92ca38812ca31640b0da14927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb965ebc64ac31d5906cc843c6c9eaa9">UnregisterJITEventListener</a> (JITEventListener *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8bd52d620507ca7a12622b0d9047c3">setObjectCache</a> (ObjectCache *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the pre-compiled object cache. <a href="#abc8bd52d620507ca7a12622b0d9047c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aaf43bf637f85420de8d9fbd23fc6da">setProcessAllSections</a> (bool ProcessAllSections)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setProcessAllSections (<a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> Only): By default, only sections that are "required for execution" are passed to the <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a>, and other sections are discarded. <a href="#a1aaf43bf637f85420de8d9fbd23fc6da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe62294b33c61da1c1a4aa42eb28dd4">getTargetMachine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target machine (if available). <a href="#aabe62294b33c61da1c1a4aa42eb28dd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5169a202e9263a61fa11236953e50bb7">DisableLazyCompilation</a> (bool Disabled=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DisableLazyCompilation - When lazy compilation is off (the default), the JIT will eagerly compile every function reachable from the argument to getPointerToFunction. <a href="#a5169a202e9263a61fa11236953e50bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f85c9fd7538e8db65bf07459090b6c6">isCompilingLazily</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34fc6d4cb8d45ff9b7ee30d1252f19ed">DisableGVCompilation</a> (bool Disabled=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DisableGVCompilation - If called, the JIT will abort if it's asked to allocate space and populate a <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> that is not internal to the module. <a href="#a34fc6d4cb8d45ff9b7ee30d1252f19ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33a27ffdc2af41c8d091798b79e9af7">isGVCompilationDisabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af062585affb7cd16bab9867b706ea460">DisableSymbolSearching</a> (bool Disabled=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DisableSymbolSearching - If called, the JIT will not try to lookup unknown symbols with dlsym. <a href="#af062585affb7cd16bab9867b706ea460">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22d74c24bf5144ae25380ff6abbe2a2">isSymbolSearchingDisabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f6219fb693e81805662dd4bb42e6e9">setVerifyModules</a> (bool Verify)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable/Disable IR module verification. <a href="#a05f6219fb693e81805662dd4bb42e6e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a230693f459e18c3b19615ffc33c23f69">getVerifyModules</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a748aecbad479192aad27aa48b448e">InstallLazyFunctionCreator</a> (FunctionCreator C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InstallLazyFunctionCreator - If an unknown function is needed, the specified function pointer is invoked to create it. <a href="#a95a748aecbad479192aad27aa48b448e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae739336f3ec474f015e91e7698af256b">getMemoryForGV</a> (const GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMemoryforGV - Allocate memory for a global variable. <a href="#ae739336f3ec474f015e91e7698af256b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b63142ca24145028afa3a5bdf3fe7fb">getMangledName</a> (const GlobalValue *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMangledName - Get mangled name. <a href="#a3b63142ca24145028afa3a5bdf3fe7fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca88a09e03611e624c1b6ac0aad41ce3">emitGlobals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitGlobals - Emit all of the global variables to memory, storing their addresses into GlobalAddress. <a href="#aca88a09e03611e624c1b6ac0aad41ce3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a> (const GlobalVariable *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a724dad58a66f883d1b88115237ae00">getConstantValue</a> (const Constant *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts a Constant* into a <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a>, including handling of <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> values. <a href="#a0a724dad58a66f883d1b88115237ae00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec0e730f80de19f31127faedf39008c">LoadValueFromMemory</a> (GenericValue &amp;Result, GenericValue *Ptr, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FIXME: document. <a href="#adec0e730f80de19f31127faedf39008c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9f920ff578d34b92b9aa3349e90420">Init</a> (std::unique_ptr&lt; Module &gt; M)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52d48084c5b60251870b6118e4670fee">sys::Mutex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lock - This lock protects the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> and <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> classes. <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of Modules that we are JIT'ing from. <a href="#a82d981b08b138a888cf49e5c19c2c54d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a91e4f29f98fae74159c32fa3d51a0bf9">FunctionCreator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc176a0cbdab69cff95f1908bb1898d">LazyFunctionCreator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LazyFunctionCreator - If an unknown function is needed, this function pointer is invoked to create it. <a href="#a7cc176a0cbdab69cff95f1908bb1898d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eeec03dbb296860e68cfa3714117628">ErrMsg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/executionenginestate">ExecutionEngineState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634cead6c5502412859336f7c5e273b4">EEState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The state object holding the global address mapping, which must be accessed synchronously. <a href="#a634cead6c5502412859336f7c5e273b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f0e7640eb70f43958b0f0b925f1e06f">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The target data for the platform for which execution is being performed. <a href="#a5f0e7640eb70f43958b0f0b925f1e06f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519f9db8367dcfe4a6c03ead4263002a">CompilingLazily</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether lazy JIT compilation is enabled. <a href="#a519f9db8367dcfe4a6c03ead4263002a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea352c3f22cad92577f9fe4c190ddbd">GVCompilationDisabled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether JIT compilation of external global variables is allowed. <a href="#a2ea352c3f22cad92577f9fe4c190ddbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c888d00b8334076b0b9571a9e3cd41">SymbolSearchingDisabled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the JIT should perform lookups of external symbols (e.g., using dlsym). <a href="#a63c888d00b8334076b0b9571a9e3cd41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5922582ba35f54c2820ed5a5e2caf46">VerifyModules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the JIT should verify IR modules during compilation. <a href="#ae5922582ba35f54c2820ed5a5e2caf46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> *(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce88aa01ae7cf17c22e69718cff7299">MCJITCtor</a>)(std::unique_ptr< Module > M, std::string *ErrorStr, std::shared_ptr< MCJITMemoryManager > MM, std::shared_ptr< LegacyJITSymbolResolver > SR, std::unique_ptr< TargetMachine > TM) = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> *(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6947cede6cdd00042e82b3597606a515">InterpCtor</a>)(std::unique_ptr< Module > M, std::string *ErrorStr) =nullptr</td>
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

<p>Abstract interface for implementation execution of LLVM modules, designed to support both interpreter and just-in-time (JIT) compiler implementations.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<div class="doxySectionDef">

## Friends

### EngineBuilder {#aba576ac4fb51534183fcf896dd51be68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#aba576ac4fb51534183fcf896dd51be68">EngineBuilder</a>.</p>


<p>Referenced by <a href="#aba576ac4fb51534183fcf896dd51be68">EngineBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ExecutionEngine() {#a92eef8691cfbe4446ee15d34258c3185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ExecutionEngine::ExecutionEngine (<a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#aec4c8f10c02e58107d0372b5de57b819">llvm::Interpreter::create</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a742cab06ece0dfaa5fb512243e616bcc">llvm::Interpreter::Interpreter</a>.</p>

</div>
</div>

### ExecutionEngine() {#a3462fd165e3dcb3236dc69650d68ce6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine::ExecutionEngine (<a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> DL, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a7cc176a0cbdab69cff95f1908bb1898d">LazyFunctionCreator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### ExecutionEngine() {#a1f9ec8ba2ed8dbf9b9c7f0bba1828402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine::ExecutionEngine (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a> and <a href="#a7cc176a0cbdab69cff95f1908bb1898d">LazyFunctionCreator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ExecutionEngine() {#ae854ad96a2f8cf76b7f4aef063bf19ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine::~ExecutionEngine ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>Reference <a href="#a29f60ea31c2022f7f13fab8faf988705">clearAllGlobalMappings</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addArchive() {#a2cc50fba7c734a3f4f2463826385ee3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::addArchive (<a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt; A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addArchive - Add an Archive to the execution engine.</p>


<p>This method is only supported by <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>. <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> will use the archive to resolve external symbols in objects it is loading. If a symbol is found in the Archive the contained object file will be extracted (in memory) and loaded for possible execution.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### addGlobalMapping() {#a805704b52a327cc6b37aebf9cba14169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::addGlobalMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, void * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addGlobalMapping - Tell the execution engine that the specified global is at the specified location.</p>


<p>This is used internally as functions are JIT'd and as global variables are laid out in memory. It can and should also be used by clients of the EE that want to have an LLVM global overlay existing data in memory. Values to be mapped should be named, and have external or weak linkage. Mappings are automatically removed when their <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is destroyed.</p>


<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a805704b52a327cc6b37aebf9cba14169">addGlobalMapping</a>, <a href="#a3b63142ca24145028afa3a5bdf3fe7fb">getMangledName</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>


<p>Referenced by <a href="#a805704b52a327cc6b37aebf9cba14169">addGlobalMapping</a>, <a href="#aca88a09e03611e624c1b6ac0aad41ce3">emitGlobals</a> and <a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a>.</p>

</div>
</div>

### addGlobalMapping() {#a3cd00b43a7e3416795b7a32d8e5c7131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::addGlobalMapping (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>

</div>
</div>

### addModule() {#a628a513b3b717f80fdc8e937cc503f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::addModule (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to the list of modules that we can JIT from.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a>.</p>

</div>
</div>

### addObjectFile() {#a9ec095fb0a6b58427bed62c3fa52fdc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::addObjectFile (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addObjectFile - Add an <a href="/web-llvm/docs/api/classes/llvm/objectfile">ObjectFile</a> to the execution engine.</p>


<p>This method is only supported by <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>. <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> will immediately load the object into memory and adds its symbols to the list used to resolve external symbols while preparing other objects for execution.</p>


<p>Objects added using this function will not be made executable until needed by another object.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> will take ownership of the <a href="/web-llvm/docs/api/classes/llvm/objectfile">ObjectFile</a>.</p>


<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### addObjectFile() {#afa1c5c7eb8f616ebaec8be5d350d7ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::addObjectFile (<a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### clearAllGlobalMappings() {#a29f60ea31c2022f7f13fab8faf988705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::clearAllGlobalMappings ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clearAllGlobalMappings - Clear all global mappings and start over again, for use in dynamic compilation scenarios to move globals.</p>

<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>Reference <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>


<p>Referenced by <a href="#ae854ad96a2f8cf76b7f4aef063bf19ce">~ExecutionEngine</a>.</p>

</div>
</div>

### clearErrorMessage() {#a37455f3715f92a4bbc9d0ade8348374f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ExecutionEngine::clearErrorMessage ()</td>
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

<p>Clear the error message.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a4eeec03dbb296860e68cfa3714117628">ErrMsg</a>.</p>

</div>
</div>

### clearGlobalMappingsFromModule() {#a9565a2a404ec3802e545beb8f63fe347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::clearGlobalMappingsFromModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clearGlobalMappingsFromModule - Clear all global mappings that came from a particular module, because it has been removed from the JIT.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a3b63142ca24145028afa3a5bdf3fe7fb">getMangledName</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>


<p>Referenced by <a href="#a514dfa1719bb6dadcc8bb7b71619805e">removeModule</a>.</p>

</div>
</div>

### DisableGVCompilation() {#a34fc6d4cb8d45ff9b7ee30d1252f19ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ExecutionEngine::DisableGVCompilation (bool Disabled=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>DisableGVCompilation - If called, the JIT will abort if it's asked to allocate space and populate a <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> that is not internal to the module.</p>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafab9f5c797ebbf55adccdd8539a65a0241">llvm::Disabled</a>.</p>

</div>
</div>

### DisableLazyCompilation() {#a5169a202e9263a61fa11236953e50bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ExecutionEngine::DisableLazyCompilation (bool Disabled=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>DisableLazyCompilation - When lazy compilation is off (the default), the JIT will eagerly compile every function reachable from the argument to getPointerToFunction.</p>


<p>If lazy compilation is turned on, the JIT will only compile the one function and emit stubs to compile the rest when they're first called. If lazy compilation is turned off again while some lazy stubs are still around, and one of those stubs is called, the program will abort.</p>


<p>In order to safely compile lazily in a threaded program, the user must ensure that 1) only one thread at a time can call any particular lazy stub, and 2) any thread modifying LLVM IR must hold the JIT's lock (<a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">ExecutionEngine::lock</a>) or otherwise ensure that no other thread calls a lazy stub. See <a href="http://llvm.org/PR5184">http://llvm.org/PR5184</a> for details.</p>


<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafab9f5c797ebbf55adccdd8539a65a0241">llvm::Disabled</a>.</p>

</div>
</div>

### DisableSymbolSearching() {#af062585affb7cd16bab9867b706ea460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ExecutionEngine::DisableSymbolSearching (bool Disabled=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>DisableSymbolSearching - If called, the JIT will not try to lookup unknown symbols with dlsym.</p>


<p>A client can still use InstallLazyFunctionCreator to resolve symbols in a custom way.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafab9f5c797ebbf55adccdd8539a65a0241">llvm::Disabled</a>.</p>

</div>
</div>

### finalizeObject() {#ab2973f596de3b640bdc087bf2d46bcfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::finalizeObject ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>finalizeObject - ensure the module is fully processed and is usable.</p>


<p>It is the user-level function for completing the process of making the object usable for execution. It should be called after sections within an object have been relocated using mapSectionAddress. When this method is called the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine will reapply relocations for a loaded object. This method has no effect for the interpreter.</p>


<p>Returns true on success, false on failure. <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> messages can be retrieved by calling <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ad73113c3c3a7bfb64703238645f6fc1e">getError()</a>;</p>


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### FindFunctionNamed() {#af652436173a739833e0e382f181b2870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * ExecutionEngine::FindFunctionNamed (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FindFunctionNamed - Search all of the active modules to find the function that defines FnName.</p>


<p>This is very slow operation and shouldn't be used for general code.</p>


<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a>.</p>

</div>
</div>

### FindGlobalVariableNamed() {#abcc4f77c7dbf7ed1f581b3773bc0f2df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * ExecutionEngine::FindGlobalVariableNamed (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AllowInternal=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FindGlobalVariableNamed - Search all of the active modules to find the global variable that defines Name.</p>


<p>This is very slow operation and shouldn't be used for general code.</p>


<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a> and <a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a>.</p>

</div>
</div>

### generateCodeForModule() {#a63c3a5d438306a20122987aa04363f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::generateCodeForModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>generateCodeForModule - Run code generation for the specified module and load it into memory.</p>


<p>When this function has completed, all code and data for the specified module, and any module on which this module depends, will be generated and loaded into memory, but relocations will not yet have been applied and all memory will be readable and writable but not executable.</p>


<p>This function is primarily useful when generating code for an external target, allowing the client an opportunity to remap section addresses before relocations are applied. Clients that intend to execute code locally can use the getFunctionAddress call, which will generate code and apply final preparations all in one step.</p>


<p>This method has no effect for the interpreter.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### getAddressToGlobalIfAvailable() {#ab2f6e6505348cc3f784771e75092c602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ExecutionEngine::getAddressToGlobalIfAvailable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAddressToGlobalIfAvailable - This returns the address of the specified global symbol.</p>

<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>


<p>Referenced by <a href="#a29b4671f69facc701332f9510ca436aa">getPointerToGlobalIfAvailable</a>.</p>

</div>
</div>

### getDataLayout() {#a221f82626a9fd6d8dc7c76e097940b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::ExecutionEngine::getDataLayout ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcjit/#af6ce1da6819f73ca2445152d98c9c48d">llvm::MCJIT::addModule</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac90cfcdb0c2a25c0969106ebff1be9f8">llvm::Interpreter::callExternalFunction</a>, <a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a>, <a href="#a1f9ec8ba2ed8dbf9b9c7f0bba1828402">ExecutionEngine</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a28cc3d07256589bd54f2d22eb12bafad">llvm::MCJIT::findModuleForSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a5236c37b672e45c22ef2ebb47518871e">llvm::MCJIT::generateCodeForModule</a>, <a href="#a3b63142ca24145028afa3a5bdf3fe7fb">getMangledName</a>, <a href="#ae739336f3ec474f015e91e7698af256b">getMemoryForGV</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ab9a66732fec3f835f54f4bb8f5388389">llvm::MCJIT::getSymbolAddress</a>, <a href="#a38079cd1d3c8bc5f3aef1d3420c3b855">InitializeMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a742cab06ece0dfaa5fb512243e616bcc">llvm::Interpreter::Interpreter</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp/#a3ad6b5d121ac7d090c7670c699ac3b93">isTargetNullPtr</a>, <a href="#adec0e730f80de19f31127faedf39008c">LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/argvarray/#a3b5f64c809ca91e2a09b5b97d80e23a7">anonymous{ExecutionEngine.cpp}::ArgvArray::reset</a>, <a href="#a08ed33d3b3f8b9e21167918d5de40014">StoreValueToMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1ce4069e58167789a23552d4cab66114">llvm::Interpreter::visitAllocaInst</a>.</p>

</div>
</div>

### getErrorMessage() {#a3678bf0330f2bc1970117b384045616b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::ExecutionEngine::getErrorMessage ()</td>
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

<p>Returns the most recent error message.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a4eeec03dbb296860e68cfa3714117628">ErrMsg</a>.</p>

</div>
</div>

### getFunctionAddress() {#a56ddd3e40138980c68a2e1c4dadaed31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::ExecutionEngine::getFunctionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFunctionAddress - Return the address of the specified function.</p>


<p>This may involve code generation.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### getGlobalValueAddress() {#a966d4ff307d844ac32c737a521bbecd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::ExecutionEngine::getGlobalValueAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getGlobalValueAddress - Return the address of the specified global value.</p>


<p>This may involve code generation.</p>


<p>This function should not be called with the interpreter engine.</p>


<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### getGlobalValueAtAddress() {#a8796e9969f3352978e7f26f3c6b3cbd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue * ExecutionEngine::getGlobalValueAtAddress (void * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getGlobalValueAtAddress - Return the LLVM global value object that starts at the specified address.</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a> and <a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a>.</p>

</div>
</div>

### getOrEmitGlobalVariable() {#aab06dbc788612fabca42c90bf2516afe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void * llvm::ExecutionEngine::getOrEmitGlobalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrEmitGlobalVariable - Return the address of the specified global variable, possibly emitting it to memory if needed.</p>


<p>This is used by the Emitter.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getGlobalValueAddress instead.</p>


<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a9656c73d0da235ba5b99c14804175943">getPointerToGlobal</a>.</p>


<p>Referenced by <a href="#a0a724dad58a66f883d1b88115237ae00">getConstantValue</a>.</p>

</div>
</div>

### getPointerToFunction() {#a54f6dc15011951227ed4065f2e934f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void * llvm::ExecutionEngine::getPointerToFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPointerToFunction - The different EE's represent function bodies in different ways.</p>


<p>They should each implement this to say what a function pointer should look like. When F is destroyed, the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> will remove its global mapping and free any machine code. Be sure no threads are running inside F when that happens.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getFunctionAddress instead.</p>


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a3aae274d0f4e7b494ee7807374f5c32b">getPointerToFunctionOrStub</a> and <a href="#a9656c73d0da235ba5b99c14804175943">getPointerToGlobal</a>.</p>

</div>
</div>

### getPointerToFunctionOrStub() {#a3aae274d0f4e7b494ee7807374f5c32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void * llvm::ExecutionEngine::getPointerToFunctionOrStub (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPointerToFunctionOrStub - If the specified function has been code-gen'd, return a pointer to the function.</p>


<p>If not, compile it, or use a stub to implement lazy compilation if available. See getPointerToFunction for the requirements on destroying F.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getFunctionAddress instead.</p>


<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a54f6dc15011951227ed4065f2e934f90">getPointerToFunction</a>.</p>


<p>Referenced by <a href="#a0a724dad58a66f883d1b88115237ae00">getConstantValue</a>.</p>

</div>
</div>

### getPointerToGlobal() {#a9656c73d0da235ba5b99c14804175943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * ExecutionEngine::getPointerToGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPointerToGlobal - This returns the address of the specified global value.</p>


<p>This may involve code generation if it's a function.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getGlobalValueAddress instead.</p>


<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a54f6dc15011951227ed4065f2e934f90">getPointerToFunction</a>, <a href="#a29b4671f69facc701332f9510ca436aa">getPointerToGlobalIfAvailable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#aab06dbc788612fabca42c90bf2516afe">getOrEmitGlobalVariable</a>.</p>

</div>
</div>

### getPointerToGlobalIfAvailable() {#a29b4671f69facc701332f9510ca436aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * ExecutionEngine::getPointerToGlobalIfAvailable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPointerToGlobalIfAvailable - This returns the address of the specified global value if it is has already been codegen'd, otherwise it returns null.</p>

<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#ab2f6e6505348cc3f784771e75092c602">getAddressToGlobalIfAvailable</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac90cfcdb0c2a25c0969106ebff1be9f8">llvm::Interpreter::callExternalFunction</a>, <a href="#aca88a09e03611e624c1b6ac0aad41ce3">emitGlobals</a>, <a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ab20dd7532d54078744493a662f741061">llvm::MCJIT::findExistingSymbol</a>, <a href="#a9656c73d0da235ba5b99c14804175943">getPointerToGlobal</a> and <a href="#aa5d335340f7ac093e81c965ba69a7aac">getPointerToGlobalIfAvailable</a>.</p>

</div>
</div>

### getPointerToGlobalIfAvailable() {#aa5d335340f7ac093e81c965ba69a7aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * ExecutionEngine::getPointerToGlobalIfAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a3b63142ca24145028afa3a5bdf3fe7fb">getMangledName</a>, <a href="#a29b4671f69facc701332f9510ca436aa">getPointerToGlobalIfAvailable</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>

</div>
</div>

### getPointerToNamedFunction() {#ae8c7ab2f89968276b54abf516e3e37cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void * llvm::ExecutionEngine::getPointerToNamedFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AbortOnFailure=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPointerToNamedFunction - This method returns the address of the specified function by using the dlsym function call.</p>


<p>As such it is only useful for resolving library symbols, not code generated symbols.</p>


<p>If AbortOnFailure is false and no function with the given name is found, this function silently returns a null pointer. Otherwise, it prints a message to stderr and aborts.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### getTargetMachine() {#aabe62294b33c61da1c1a4aa42eb28dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual TargetMachine * llvm::ExecutionEngine::getTargetMachine ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the target machine (if available).</p>

<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### getVerifyModules() {#a230693f459e18c3b19615ffc33c23f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::getVerifyModules ()</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a6ba8a53658ba2413897f0b674d06faec">llvm::MCJIT::emitObject</a>.</p>

</div>
</div>

### hasError() {#a8148bbdde0eb101f768526757cb754c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::hasError ()</td>
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

<p>Returns true if an error has been recorded.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a4eeec03dbb296860e68cfa3714117628">ErrMsg</a>.</p>

</div>
</div>

### InitializeMemory() {#a38079cd1d3c8bc5f3aef1d3420c3b855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::InitializeMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Init, void * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0a724dad58a66f883d1b88115237ae00">getConstantValue</a>, <a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a61135fb8666f0b7a37b4e1bbcf1db131">llvm::DataLayout::getStructLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aa48b3b7e554b44f4e513d5dd8d9f9343">llvm::DataLayout::getTypeAllocSize</a>, <a href="#a38079cd1d3c8bc5f3aef1d3420c3b855">InitializeMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a08ed33d3b3f8b9e21167918d5de40014">StoreValueToMemory</a>.</p>


<p>Referenced by <a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a> and <a href="#a38079cd1d3c8bc5f3aef1d3420c3b855">InitializeMemory</a>.</p>

</div>
</div>

### InstallLazyFunctionCreator() {#a95a748aecbad479192aad27aa48b448e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ExecutionEngine::InstallLazyFunctionCreator (<a href="/web-llvm/docs/api/namespaces/llvm/#a91e4f29f98fae74159c32fa3d51a0bf9">FunctionCreator</a> C)</td>
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

<p>InstallLazyFunctionCreator - If an unknown function is needed, the specified function pointer is invoked to create it.</p>


<p>If it returns null, the JIT will abort.</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a7cc176a0cbdab69cff95f1908bb1898d">LazyFunctionCreator</a>.</p>

</div>
</div>

### isCompilingLazily() {#a0f85c9fd7538e8db65bf07459090b6c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::isCompilingLazily ()</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### isGVCompilationDisabled() {#ae33a27ffdc2af41c8d091798b79e9af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::isGVCompilationDisabled ()</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### isSymbolSearchingDisabled() {#af22d74c24bf5144ae25380ff6abbe2a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::isSymbolSearchingDisabled ()</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a14f1cd53696dbd8b28129c519e8bd65d">llvm::MCJIT::getPointerToNamedFunction</a>.</p>

</div>
</div>

### mapSectionAddress() {#a8771c83fc5aaa938bfa479cb99492335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::mapSectionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * LocalAddress, uint64_t TargetAddress)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>mapSectionAddress - map a section to its target address space value.</p>


<p>Map the address of a JIT section as returned from the memory manager to the address in the target process as the running code will see it. This is the address which will be used for relocation resolution.</p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### RegisterJITEventListener() {#afcd2b4b92ca38812ca31640b0da14927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::RegisterJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers a listener to be called back on various events within the JIT.</p>


<p>See <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a> for more details. Does not take ownership of the argument. The argument may be NULL, in which case these functions do nothing.</p>


<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### removeModule() {#a514dfa1719bb6dadcc8bb7b71619805e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ExecutionEngine::removeModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeModule - Removes a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> from the list of modules, but does not free the module's memory.</p>


<p>Returns true if M is found, in which case the caller assumes responsibility for deleting the module.</p>


<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a9565a2a404ec3802e545beb8f63fe347">clearGlobalMappingsFromModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a>.</p>

</div>
</div>

### runFunction() {#ac65a03b7fbdb7acd7be0bae506238c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual GenericValue llvm::ExecutionEngine::runFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; ArgValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runFunction - Execute the specified function with the specified arguments, and return the result.</p>


<p>For <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engines, clients are encouraged to use the "GetFunctionAddress" method (rather than runFunction) and cast the returned uint64_t to the desired function pointer type. However, for backwards compatibility <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>'s implementation can execute 'main-like' function (i.e. those returning void or int, and taking either no arguments or (int, char*[])).</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a97bbf524ee03354bb73dce9614b0e959">runFunctionAsMain</a> and <a href="#a60823e6b4ff77b319b51c9eb634241e2">runStaticConstructorsDestructors</a>.</p>

</div>
</div>

### runFunctionAsMain() {#a97bbf524ee03354bb73dce9614b0e959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ExecutionEngine::runFunctionAsMain (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; argv, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * envp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runFunctionAsMain - This is a helper function which wraps runFunction to handle the common task of starting up main with the specified argc, argv, and envp parameters.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp/#a3ad6b5d121ac7d090c7670c699ac3b93">isTargetNullPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77905b5e34e8754df1ed4051e0ad9d1a">llvm::PTOGV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#ac65a03b7fbdb7acd7be0bae506238c9d">runFunction</a>.</p>

</div>
</div>

### runStaticConstructorsDestructors() {#a6a34c6c082dc999d12f1f191b4108513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::runStaticConstructorsDestructors (bool isDtors)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runStaticConstructorsDestructors - This method is used to execute all of the static constructors or destructors for a program.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">isDtors</td>
<td class="doxyParamItemDescription"><p>- Run the destructors instead of constructors.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a> and <a href="#a6a34c6c082dc999d12f1f191b4108513">runStaticConstructorsDestructors</a>.</p>


<p>Referenced by <a href="#a6a34c6c082dc999d12f1f191b4108513">runStaticConstructorsDestructors</a>.</p>

</div>
</div>

### runStaticConstructorsDestructors() {#a60823e6b4ff77b319b51c9eb634241e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::runStaticConstructorsDestructors (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; module, bool isDtors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is used to execute all of the static constructors or destructors for a particular module.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">isDtors</td>
<td class="doxyParamItemDescription"><p>- Run the destructors instead of constructors.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a> and <a href="#ac65a03b7fbdb7acd7be0bae506238c9d">runFunction</a>.</p>

</div>
</div>

### setObjectCache() {#abc8bd52d620507ca7a12622b0d9047c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::setObjectCache (<a href="/web-llvm/docs/api/classes/llvm/objectcache">ObjectCache</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the pre-compiled object cache.</p>


<p>The ownership of the <a href="/web-llvm/docs/api/classes/llvm/objectcache">ObjectCache</a> is not changed. Supported by <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> but not the interpreter.</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### setProcessAllSections() {#a1aaf43bf637f85420de8d9fbd23fc6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::setProcessAllSections (bool ProcessAllSections)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setProcessAllSections (<a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> Only): By default, only sections that are "required for execution" are passed to the <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a>, and other sections are discarded.</p>


<p>Passing 'true' to this method will cause <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> to pass all sections to its <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a> regardless of whether they are "required to execute" in the usual sense.</p>


<p>Rationale: Some <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> clients want to be able to inspect metadata sections (e.g. Dwarf, Stack-maps) to enable functionality or analyze performance. Passing these sections to the memory manager allows the client to make policy about the relevant sections, rather than having <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> do it.</p>


<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### setVerifyModules() {#a05f6219fb693e81805662dd4bb42e6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ExecutionEngine::setVerifyModules (bool Verify)</td>
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

<p>Enable/Disable IR module verification.</p>


<p>Note: <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> verification is enabled by default in Debug builds, and disabled by default in Release. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this method to override the default.</p>


<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#af775bc7e1e968734ced732bfceae8c57">llvm::EngineBuilder::create</a>.</p>

</div>
</div>

### StoreValueToMemory() {#a08ed33d3b3f8b9e21167918d5de40014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::StoreValueToMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Val, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>StoreValueToMemory - Stores the data in Val of type Ty at address Ptr.</p>


<p>Ptr is the address of the memory at which to store Val, cast to <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> *. It is not a pointer to a <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> containing the address at which to store Val.</p>


<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada7af1de63a848b2f452d63958de39fe">llvm::APInt::getRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acfcd22eb38dbfe1acbf138754297437a">llvm::DataLayout::getTypeStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a23f8c75218aea0cfcfe0f3e4223d3b02">llvm::GenericValue::PointerVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a126453035cc98d97d01233bc532b32aa">llvm::StoreIntToMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>.</p>


<p>Referenced by <a href="#a38079cd1d3c8bc5f3aef1d3420c3b855">InitializeMemory</a>, <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/argvarray/#a3b5f64c809ca91e2a09b5b97d80e23a7">anonymous{ExecutionEngine.cpp}::ArgvArray::reset</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a552ef98be3146773854e33c8548d202b">llvm::Interpreter::visitStoreInst</a>.</p>

</div>
</div>

### UnregisterJITEventListener() {#abb965ebc64ac31d5906cc843c6c9eaa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ExecutionEngine::UnregisterJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### updateGlobalMapping() {#ae66e5ebc951c7d9c88c0c1884bd67872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ExecutionEngine::updateGlobalMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, void * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>updateGlobalMapping - Replace an existing mapping for GV with a new address.</p>


<p>This updates both maps as required. If "Addr" is null, the entry for the global is removed from the mappings. This returns the old value of the pointer, or null if it was not in the map.</p>


<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a3b63142ca24145028afa3a5bdf3fe7fb">getMangledName</a>, <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a> and <a href="#ae66e5ebc951c7d9c88c0c1884bd67872">updateGlobalMapping</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ae9b6b618b65cd7355f31652c566c8e3c">llvm::MCJIT::getPointerToFunction</a> and <a href="#ae66e5ebc951c7d9c88c0c1884bd67872">updateGlobalMapping</a>.</p>

</div>
</div>

### updateGlobalMapping() {#a7cb0a4c1d63616267c10b09286b36e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ExecutionEngine::updateGlobalMapping (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### emitGlobals() {#aca88a09e03611e624c1b6ac0aad41ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::emitGlobals ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitGlobals - Emit all of the global variables to memory, storing their addresses into GlobalAddress.</p>


<p>This must make sure to copy the contents of their initializers into the memory.</p>


<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 1213 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a805704b52a327cc6b37aebf9cba14169">addGlobalMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a>, <a href="#ae739336f3ec474f015e91e7698af256b">getMemoryForGV</a>, <a href="#a29b4671f69facc701332f9510ca436aa">getPointerToGlobalIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a1847e956a0087fefdb49e2a9583c7d18">llvm::GlobalValue::hasExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a51af265dc931258cdb8ffb37ee6decee">llvm::GlobalValue::hasExternalWeakLinkage</a>, <a href="#a82d981b08b138a888cf49e5c19c2c54d">Modules</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#ae003d16a33e81b88943d3e3aa179fcc4">llvm::sys::DynamicLibrary::SearchForAddressOfSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a742cab06ece0dfaa5fb512243e616bcc">llvm::Interpreter::Interpreter</a>.</p>

</div>
</div>

### emitGlobalVariable() {#ab98a836a506bb90245c243f8e4da3162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::emitGlobalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 1310 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="#a805704b52a327cc6b37aebf9cba14169">addGlobalMapping</a>, <a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a>, <a href="#ae739336f3ec474f015e91e7698af256b">getMemoryForGV</a>, <a href="#a29b4671f69facc701332f9510ca436aa">getPointerToGlobalIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aa48b3b7e554b44f4e513d5dd8d9f9343">llvm::DataLayout::getTypeAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="#a38079cd1d3c8bc5f3aef1d3420c3b855">InitializeMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a239427c2c3a01e23bd15b29633696536">llvm::GlobalValue::isThreadLocal</a>.</p>


<p>Referenced by <a href="#aca88a09e03611e624c1b6ac0aad41ce3">emitGlobals</a> and <a href="#a9656c73d0da235ba5b99c14804175943">getPointerToGlobal</a>.</p>

</div>
</div>

### getConstantValue() {#a0a724dad58a66f883d1b88115237ae00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue ExecutionEngine::getConstantValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts a Constant* into a <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a>, including handling of <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> values.</p>

<p>Declaration at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a44602b2ea058f08b290a8fa0185909d1">llvm::APFloat::add</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">llvm::Type::ArrayTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acda0d1f0e4b7b739aff9601d8b4ef4e3">llvm::APInt::bitsToDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aaefac1a605f4e104e7c7a20ab0856889">llvm::APInt::bitsToFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a7a046fe3d1230e4804494ce18bae1175">llvm::APFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aae1f09de4bf1aab27149a7d328715e30">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a107d394b970c9f03a486a15cdd08f0df">llvm::APFloat::divide</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac174a45e376a00ec9b2e9e8730f982c0">llvm::APInt::doubleToBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4b160c2704ee3819d8fda70345b4d19f">llvm::APInt::floatToBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">llvm::Type::FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="#a0a724dad58a66f883d1b88115237ae00">getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a22122dfa4eb5cb8169bcaf58e2137a91">llvm::ConstantDataSequential::getElementAsDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a74d6406a9173092c1d8042fd3d741d16">llvm::ConstantDataSequential::getElementAsFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9409db5c707242fc05b7b2abeba38506">llvm::ConstantDataSequential::getElementAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#ac0d41ea0afa3131e1a0838e07c111c0e">llvm::ConstantDataSequential::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#aa1bb0403aefc1f09b73e96d9243d3673">llvm::ConstantDataSequential::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#aab06dbc788612fabca42c90bf2516afe">getOrEmitGlobalVariable</a>, <a href="#a3aae274d0f4e7b494ee7807374f5c32b">getPointerToFunctionOrStub</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#aceab85623e5be346f2c3b6cfd456a151a1d37e04976c5b79594e646502e66f818">llvm::TargetExtType::HasZeroInit</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1f68c27188f1836737bf22a62c558354">llvm::Type::isX86_FP80Ty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac3126d0302ebe7754bf962fdaa25e286">llvm::APFloat::mod</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a82567bb6632fa71c7c727b9464368173">llvm::APFloat::multiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a23f8c75218aea0cfcfe0f3e4223d3b02">llvm::GenericValue::PointerVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">llvm::Type::PPC_FP128TyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77905b5e34e8754df1ed4051e0ad9d1a">llvm::PTOGV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a9f1937c6b659f3758dae8adca513fcd2">llvm::APIntOps::RoundDoubleToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a96a156e9aa11bdecdea9f8c0d6e5c5d2">llvm::APIntOps::RoundFloatToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae5dfa02c3403baa3d057b6264eed687d">llvm::APInt::roundToDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a71f7f6e3a4774296efc7274196a74793">llvm::APInt::sdiv</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aae8a216000ce553ed7e8d4c3a9bd1542">llvm::APInt::signedRoundToDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac131d830427393332e440e1d6e3013b6">llvm::APInt::srem</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a27bc3a1b1f84258afe7e981fb707f646">llvm::APFloat::subtract</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a4830aff0741b3cd7a3920826ae6c0ece">llvm::APFloatBase::x87DoubleExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>


<p>Referenced by <a href="#a0a724dad58a66f883d1b88115237ae00">getConstantValue</a> and <a href="#a38079cd1d3c8bc5f3aef1d3420c3b855">InitializeMemory</a>.</p>

</div>
</div>

### getMangledName() {#a3b63142ca24145028afa3a5bdf3fe7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ExecutionEngine::getMangledName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMangledName - Get mangled name.</p>

<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a37e51b287c7a168b4ee35e4854dcf299">llvm::DataLayout::isDefault</a> and <a href="#a5972a6c7bf1cf22a359d9b7987d11dfd">lock</a>.</p>


<p>Referenced by <a href="#a805704b52a327cc6b37aebf9cba14169">addGlobalMapping</a>, <a href="#a9565a2a404ec3802e545beb8f63fe347">clearGlobalMappingsFromModule</a>, <a href="#aa5d335340f7ac093e81c965ba69a7aac">getPointerToGlobalIfAvailable</a> and <a href="#ae66e5ebc951c7d9c88c0c1884bd67872">updateGlobalMapping</a>.</p>

</div>
</div>

### getMemoryForGV() {#ae739336f3ec474f015e91e7698af256b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * ExecutionEngine::getMemoryForGV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMemoryforGV - Allocate memory for a global variable.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/gvmemoryblock/#a2cbb49e0b488e91387da02f0396405f7">anonymous{ExecutionEngine.cpp}::GVMemoryBlock::Create</a> and <a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a>.</p>


<p>Referenced by <a href="#aca88a09e03611e624c1b6ac0aad41ce3">emitGlobals</a> and <a href="#ab98a836a506bb90245c243f8e4da3162">emitGlobalVariable</a>.</p>

</div>
</div>

### LoadValueFromMemory() {#adec0e730f80de19f31127faedf39008c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::LoadValueFromMemory (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &amp; Result, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FIXME: document.</p>

<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="#a221f82626a9fd6d8dc7c76e097940b07">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acfcd22eb38dbfe1acbf138754297437a">llvm::DataLayout::getTypeStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6d662507305e17aef5ce4361a349ad8">llvm::LoadIntFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7d9427c6aacb65d962854ea8bfe5c23b">llvm::Interpreter::visitLoadInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Init() {#a4a9f920ff578d34b92b9aa3349e90420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionEngine::Init (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### lock {#a5972a6c7bf1cf22a359d9b7987d11dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::Mutex llvm::ExecutionEngine::lock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>lock - This lock protects the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> and <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> classes.</p>


<p>It must be held while changing the internal state of any of those classes.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="#a805704b52a327cc6b37aebf9cba14169">addGlobalMapping</a>, <a href="#a3cd00b43a7e3416795b7a32d8e5c7131">addGlobalMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#af6ce1da6819f73ca2445152d98c9c48d">llvm::MCJIT::addModule</a>, <a href="#a29f60ea31c2022f7f13fab8faf988705">clearAllGlobalMappings</a>, <a href="#a9565a2a404ec3802e545beb8f63fe347">clearGlobalMappingsFromModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a6ba8a53658ba2413897f0b674d06faec">llvm::MCJIT::emitObject</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a4c711730384b07b067887e93931004a8">llvm::MCJIT::finalizeLoadedModules</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#adcc54665978b90bea2376f8cf50f48cc">llvm::MCJIT::finalizeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a46de6cc1d24bff3fd2ae2006c8b35456">llvm::MCJIT::finalizeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a28cc3d07256589bd54f2d22eb12bafad">llvm::MCJIT::findModuleForSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ae7e58d02f5553c707ac40497b0e9cf26">llvm::MCJIT::findSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a5236c37b672e45c22ef2ebb47518871e">llvm::MCJIT::generateCodeForModule</a>, <a href="#ab2f6e6505348cc3f784771e75092c602">getAddressToGlobalIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a628b993cb94eed2150b435bcb25ae009">llvm::MCJIT::getFunctionAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ab7bbc6d6aecb6d04aa719a85b7020089">llvm::MCJIT::getGlobalValueAddress</a>, <a href="#a8796e9969f3352978e7f26f3c6b3cbd7">getGlobalValueAtAddress</a>, <a href="#a3b63142ca24145028afa3a5bdf3fe7fb">getMangledName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ae9b6b618b65cd7355f31652c566c8e3c">llvm::MCJIT::getPointerToFunction</a>, <a href="#a9656c73d0da235ba5b99c14804175943">getPointerToGlobal</a>, <a href="#aa5d335340f7ac093e81c965ba69a7aac">getPointerToGlobalIfAvailable</a>, <a href="#a29b4671f69facc701332f9510ca436aa">getPointerToGlobalIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ace9945d0e32337f9101716f572df0885">llvm::MCJIT::notifyFreeingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a4c77fd10082d414ff13ef63a7655fde6">llvm::MCJIT::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a18f6be37761ee5769051ea3fd2982e65">llvm::MCJIT::RegisterJITEventListener</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#aa6b3e346826c4d15f691fc6d6b9de5f1">llvm::MCJIT::removeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#aeb99f9a5f472aeeb2f5b3e1b279e1853">llvm::MCJIT::setObjectCache</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a9b80bb13abeaf36df96b8a7afdb2339d">llvm::MCJIT::UnregisterJITEventListener</a>, <a href="#ae66e5ebc951c7d9c88c0c1884bd67872">updateGlobalMapping</a>, <a href="#a7cb0a4c1d63616267c10b09286b36e8c">updateGlobalMapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a3b1170b9779b23ea493913c303731067">llvm::MCJIT::~MCJIT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ErrMsg {#a4eeec03dbb296860e68cfa3714117628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ExecutionEngine::ErrMsg</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="#a37455f3715f92a4bbc9d0ade8348374f">clearErrorMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a4c711730384b07b067887e93931004a8">llvm::MCJIT::finalizeLoadedModules</a>, <a href="#a3678bf0330f2bc1970117b384045616b">getErrorMessage</a> and <a href="#a8148bbdde0eb101f768526757cb754c8">hasError</a>.</p>

</div>
</div>

### LazyFunctionCreator {#a7cc176a0cbdab69cff95f1908bb1898d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCreator llvm::ExecutionEngine::LazyFunctionCreator</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LazyFunctionCreator - If an unknown function is needed, this function pointer is invoked to create it.</p>


<p>If this returns null, the JIT will abort.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="#a3462fd165e3dcb3236dc69650d68ce6b">ExecutionEngine</a>, <a href="#a1f9ec8ba2ed8dbf9b9c7f0bba1828402">ExecutionEngine</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ae7e58d02f5553c707ac40497b0e9cf26">llvm::MCJIT::findSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a14f1cd53696dbd8b28129c519e8bd65d">llvm::MCJIT::getPointerToNamedFunction</a> and <a href="#a95a748aecbad479192aad27aa48b448e">InstallLazyFunctionCreator</a>.</p>

</div>
</div>

### Modules {#a82d981b08b138a888cf49e5c19c2c54d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;Module&gt;, 1&gt; llvm::ExecutionEngine::Modules</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of Modules that we are JIT'ing from.</p>


<p>We use a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> to optimize for the case where there is only one module.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="#a628a513b3b717f80fdc8e937cc503f26">addModule</a>, <a href="#aca88a09e03611e624c1b6ac0aad41ce3">emitGlobals</a>, <a href="#af652436173a739833e0e382f181b2870">FindFunctionNamed</a>, <a href="#abcc4f77c7dbf7ed1f581b3773bc0f2df">FindGlobalVariableNamed</a>, <a href="#a8796e9969f3352978e7f26f3c6b3cbd7">getGlobalValueAtAddress</a>, <a href="#a514dfa1719bb6dadcc8bb7b71619805e">removeModule</a> and <a href="#a6a34c6c082dc999d12f1f191b4108513">runStaticConstructorsDestructors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CompilingLazily {#a519f9db8367dcfe4a6c03ead4263002a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::CompilingLazily</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether lazy JIT compilation is enabled.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### DL {#a5f0e7640eb70f43958b0f0b925f1e06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout llvm::ExecutionEngine::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The target data for the platform for which execution is being performed.</p>


<p>Note: the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> is <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> specific because it has an internal cache based on type pointers. It makes unsafe to reuse the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> across context, we don't enforce this rule but undefined behavior can occurs if the user tries to do it.</p>


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### EEState {#a634cead6c5502412859336f7c5e273b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngineState llvm::ExecutionEngine::EEState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The state object holding the global address mapping, which must be accessed synchronously.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### GVCompilationDisabled {#a2ea352c3f22cad92577f9fe4c190ddbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::GVCompilationDisabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether JIT compilation of external global variables is allowed.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### SymbolSearchingDisabled {#a63c888d00b8334076b0b9571a9e3cd41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::SymbolSearchingDisabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the JIT should perform lookups of external symbols (e.g., using dlsym).</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### VerifyModules {#ae5922582ba35f54c2820ed5a5e2caf46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ExecutionEngine::VerifyModules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the JIT should verify IR modules during compilation.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### InterpCtor {#a6947cede6cdd00042e82b3597606a515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine *(* ExecutionEngine::InterpCtor)(std::unique_ptr&lt; Module &gt; M, std::string *ErrorStr) =nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#af775bc7e1e968734ced732bfceae8c57">llvm::EngineBuilder::create</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a152334c0d8a032d91d4c90b5197cb902">llvm::Interpreter::Register</a>.</p>

</div>
</div>

### MCJITCtor {#a6ce88aa01ae7cf17c22e69718cff7299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine *(* ExecutionEngine::MCJITCtor)(std::unique_ptr&lt; Module &gt; M, std::string *ErrorStr, std::shared_ptr&lt; MCJITMemoryManager &gt; MemMgr, std::shared_ptr&lt; LegacyJITSymbolResolver &gt; Resolver, std::unique_ptr&lt; TargetMachine &gt; TM) = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#af775bc7e1e968734ced732bfceae8c57">llvm::EngineBuilder::create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a97c441ad61800b9fe204a455ae36298d">llvm::MCJIT::Register</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
