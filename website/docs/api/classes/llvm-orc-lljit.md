---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/lljit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLJIT` Class Reference

<p>A pre-fabricated ORC JIT stack that can serve as an alternative to <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::LLJIT { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">llvm/ExecutionEngine/Orc/LLJIT.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjit">LLLazyJIT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An extended version of <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> that supports lazy function-at-a-time compilation of LLVM IR. <a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename, typename, typename&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0e42999670094cbbd1ea6ce38df5280">LLJITBuilderSetters</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Configure the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance to scrape modules for llvm.global_ctors and llvm.global_dtors variables and (if present) build initialization and deinitialization functions. <a href="#a392f906e72c6fa022d871e028e6f34b9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a> (LLJITBuilderState &amp;S, Error &amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance with a single compile thread. <a href="#a0dd10d6063d14925c308957d2c642fea">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4098d3bf9b2a95b903a4b4a71c43aa10">~LLJIT</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destruct this instance. <a href="#a4098d3bf9b2a95b903a4b4a71c43aa10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c1b4d9e95a5d56aa3659c9a92bd286">getExecutionSession</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this instance. <a href="#a94c1b4d9e95a5d56aa3659c9a92bd286">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c6b2d9d2593a5231245f9055f126c1">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the triple for this instance. <a href="#a67c6b2d9d2593a5231245f9055f126c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2160b34c7939217c9dd56362e55a2e79">getDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for this instance. <a href="#a2160b34c7939217c9dd56362e55a2e79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8b3f5b157bac218ad8e28090b03161">getMainJITDylib</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> representing the JIT'd main program. <a href="#a1b8b3f5b157bac218ad8e28090b03161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784ec48bdbb34855fde8f7585b00acfe">getProcessSymbolsJITDylib</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ProcessSymbols <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>, which by default reflects non-JIT'd symbols in the host process. <a href="#a784ec48bdbb34855fde8f7585b00acfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc9978d5f162b95f8583c09f4bec702">getPlatformJITDylib</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>, which will contain the ORC runtime (if given) and any platform symbols. <a href="#a4dc9978d5f162b95f8583c09f4bec702">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc811880a5816919a96ee2f2104844d">getJITDylibByName</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with the given name, or nullptr if no <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with that name exists. <a href="#adcc811880a5816919a96ee2f2104844d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ece82000ef0a7c6a9e9947cbdbbd1b9">loadPlatformDynamicLibrary</a> (const char *Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load a (real) dynamic library and make its symbols available through a new <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with the same name. <a href="#a4ece82000ef0a7c6a9e9947cbdbbd1b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa681b188079626ba7d773d29128e3bf">linkStaticLibraryInto</a> (JITDylib &amp;JD, std::unique_ptr&lt; MemoryBuffer &gt; LibBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link a static library into the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#aaa681b188079626ba7d773d29128e3bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7573528896e709770c5e31bdf597555">linkStaticLibraryInto</a> (JITDylib &amp;JD, const char *Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link a static library into the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#aa7573528896e709770c5e31bdf597555">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192875b831c7f43e8050fc5ba6345407">createJITDylib</a> (std::string Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with the given name and return a reference to it. <a href="#a192875b831c7f43e8050fc5ba6345407">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0eb63499f324d046a48ceb152f49ae1">defaultLinkOrder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the default link order for this <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance. <a href="#ad0eb63499f324d046a48ceb152f49ae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae80aa20118c3b2a9fe857c47dd576d44">addIRModule</a> (ResourceTrackerSP RT, ThreadSafeModule TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an IR module with the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>. <a href="#ae80aa20118c3b2a9fe857c47dd576d44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d24430d7198c43adb4bcbb1b3a5040c">addIRModule</a> (JITDylib &amp;JD, ThreadSafeModule TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an IR module to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a5d24430d7198c43adb4bcbb1b3a5040c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286936f266b3ea6e0e0bc495a1908b7e">addIRModule</a> (ThreadSafeModule TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an IR module to the Main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a286936f266b3ea6e0e0bc495a1908b7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18fffdd9e623be562929e8c890b06912">addObjectFile</a> (ResourceTrackerSP RT, std::unique_ptr&lt; MemoryBuffer &gt; Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an object file to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a18fffdd9e623be562929e8c890b06912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2369a3a1c00d13978b3c71bdc133ba86">addObjectFile</a> (JITDylib &amp;JD, std::unique_ptr&lt; MemoryBuffer &gt; Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an object file to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a2369a3a1c00d13978b3c71bdc133ba86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8532fb842fd8229a028f9cfb6c7ec93">addObjectFile</a> (std::unique_ptr&lt; MemoryBuffer &gt; Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an object file to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#aa8532fb842fd8229a028f9cfb6c7ec93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cdf02cb3498619dc90826ff5bf7b64f">lookupLinkerMangled</a> (JITDylib &amp;JD, SymbolStringPtr Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a symbol in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD by the symbol's linker-mangled name (to look up symbols based on their IR name use the lookup function instead). <a href="#a7cdf02cb3498619dc90826ff5bf7b64f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a94949eb4cbd94a2bf88001ce40ab8">lookupLinkerMangled</a> (JITDylib &amp;JD, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a symbol in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD by the symbol's linker-mangled name (to look up symbols based on their IR name use the lookup function instead). <a href="#a34a94949eb4cbd94a2bf88001ce40ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6651526960eb51673b62bf21f33bd63">lookupLinkerMangled</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a symbol in the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> by the symbol's linker-mangled name (to look up symbols based on their IR name use the lookup function instead). <a href="#af6651526960eb51673b62bf21f33bd63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47cad7df0e937b62cd5cf774ca7b718f">lookup</a> (JITDylib &amp;JD, StringRef UnmangledName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a symbol in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD based on its IR symbol name. <a href="#a47cad7df0e937b62cd5cf774ca7b718f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c14de36fc5824a7fd7b2cc0b62d9aa">lookup</a> (StringRef UnmangledName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a symbol in the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> based on its IR symbol name. <a href="#a63c14de36fc5824a7fd7b2cc0b62d9aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b302aa7a486cbfc0bc4f51c44ef5ae">setPlatformSupport</a> (std::unique_ptr&lt; PlatformSupport &gt; PS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport">PlatformSupport</a> instance. <a href="#a04b302aa7a486cbfc0bc4f51c44ef5ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport">PlatformSupport</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f8a774fa37e25fc9b5afbf169cf627d">getPlatformSupport</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport">PlatformSupport</a> instance. <a href="#a7f8a774fa37e25fc9b5afbf169cf627d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c072757f58d375d414672b267b144c">initialize</a> (JITDylib &amp;JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the initializers for the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a22c072757f58d375d414672b267b144c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a537bf263834ac50f5b2fb2684e1d7de9">deinitialize</a> (JITDylib &amp;JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the deinitializers for the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a537bf263834ac50f5b2fb2684e1d7de9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c595f2ceaeed6e7996a984dca44e2b7">getObjLinkingLayer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the ObjLinkingLayer. <a href="#a2c595f2ceaeed6e7996a984dca44e2b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objecttransformlayer">ObjectTransformLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2342b3b908d5a8ba6416f7a957fc004">getObjTransformLayer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the object transform layer. <a href="#ae2342b3b908d5a8ba6416f7a957fc004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer">IRTransformLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425e226668d27e36e3174920d61f4f4a">getIRTransformLayer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the IR transform layer. <a href="#a425e226668d27e36e3174920d61f4f4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer">IRCompileLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3692a02c2202f95f1d161ef4ef11e9ef">getIRCompileLayer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the IR compile layer. <a href="#a3692a02c2202f95f1d161ef4ef11e9ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43dd1528c301e983d792f169a209cfaa">mangle</a> (StringRef UnmangledName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a linker-mangled version of UnmangledName. <a href="#a43dd1528c301e983d792f169a209cfaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee546ce9e614752cf696874ad25505d">mangleAndIntern</a> (StringRef UnmangledName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an interned, linker-mangled version of UnmangledName. <a href="#a9ee546ce9e614752cf696874ad25505d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab837d755651a0abce336798a703de9e4">applyDataLayout</a> (Module &amp;M)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport">PlatformSupport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5184abd0c23393183203ddcd4854a0">PS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec52e740921d55355a3e49c8921abc5">ProcessSymbols</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f50efb4aa497805dfe0d9d3134155ee">Platform</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4403c6d0172443bd06841dc65467d6da">Main</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6bec9147ad1396e3f7bd405bbb181f">DefaultLinks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72c8213f7b5f438014b62005898a0c4">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae385620f3dabad18c226aede346699ce">TT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abef4d04d6ec2ca5605d65c8531eeebbd">ObjLinkingLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/objecttransformlayer">ObjectTransformLayer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3693cddd881c11c8836f3bd273636069">ObjTransformLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer">IRCompileLayer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c30b409d9279e077d210f163d9fcb9">CompileLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer">IRTransformLayer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e958902278f92af9d29e83cb61213c8">TransformLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer">IRTransformLayer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f6fbbda563e86c6a9e6ce39a6f4d5ab">InitHelperTransformLayer</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04042d20ae456e3f4db3e74ae33b7a3b">createObjectLinkingLayer</a> (LLJITBuilderState &amp;S, ExecutionSession &amp;ES)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer/ircompiler">IRCompileLayer::IRCompiler</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e3e5170bf4d4fa25f1b53e1a5925589">createCompileFunction</a> (LLJITBuilderState &amp;S, JITTargetMachineBuilder JTMB)</td>
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

<p>A pre-fabricated ORC JIT stack that can serve as an alternative to <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>.</p>


<p>Create instances using <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilder">LLJITBuilder</a>.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LLJITBuilderSetters {#af0e42999670094cbbd1ea6ce38df5280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuildersetters">LLJITBuilderSetters</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a> and <a href="#af0e42999670094cbbd1ea6ce38df5280">LLJITBuilderSetters</a>.</p>


<p>Referenced by <a href="#af0e42999670094cbbd1ea6ce38df5280">LLJITBuilderSetters</a>.</p>

</div>
</div>

### setUpGenericLLVMIRPlatform {#a392f906e72c6fa022d871e028e6f34b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> &amp; J</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Configure the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance to scrape modules for llvm.global_ctors and llvm.global_dtors variables and (if present) build initialization and deinitialization functions.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> specific initialization configurations should be preferred where available.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a6dfad3bd64c32a0f80f488fee7f637de">llvm::orc::JITDylib::addToLinkOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcehframeregistrar/#a51ea537174eddbd35adc24f8e2388b26">llvm::orc::EPCEHFrameRegistrar::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinforegistrationplugin/#a110ba67632ecd4c507aaf6d63c1ac5b3">llvm::orc::UnwindInfoRegistrationPlugin::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a6576b19a186104b0ee0d910ea472cab2">llvm::orc::ExecutionSession::createBareJITDylib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a7dc6e2659a199f1f2061aa6d2a4facc0">llvm::orc::ExecutionSession::getBootstrapMapValue</a>, <a href="#a94c1b4d9e95a5d56aa3659c9a92bd286">getExecutionSession</a>, <a href="#a2c595f2ceaeed6e7996a984dca44e2b7">getObjLinkingLayer</a>, <a href="#a784ec48bdbb34855fde8f7585b00acfe">getProcessSymbolsJITDylib</a>, <a href="#a67c6b2d9d2593a5231245f9055f126c1">getTargetTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a444e46ff0a17a6c9480eb151bd42c9bc">llvm::Triple::isOSBinFormatMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab6fdf9b428bc3d57837022121c155cbf">llvm::Triple::isOSDarwin</a>, <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="#a04b302aa7a486cbfc0bc4f51c44ef5ae">setPlatformSupport</a>.</p>


<p>Referenced by <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### LLJIT() {#a0dd10d6063d14925c308957d2c642fea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LLJIT::LLJIT (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate">LLJITBuilderState</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance with a single compile thread.</p>

<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a59c30b409d9279e077d210f163d9fcb9">CompileLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ae15684412736f37c545f8f2ec65cce56">llvm::orc::SelfExecutorProcessControl::Create</a>, <a href="#a7e3e5170bf4d4fa25f1b53e1a5925589">createCompileFunction</a>, <a href="#a192875b831c7f43e8050fc5ba6345407">createJITDylib</a>, <a href="#a04042d20ae456e3f4db3e74ae33b7a3b">createObjectLinkingLayer</a>, <a href="#a1e6bec9147ad1396e3f7bd405bbb181f">DefaultLinks</a>, <a href="#aa72c8213f7b5f438014b62005898a0c4">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#abc1d5311f39b7529af5b53394b6bb3c9">llvm::orc::LLJITBuilderState::EPC</a>, <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a6a73b413efad5d5b1192967204c7f153">llvm::orc::LLJITBuilderState::ES</a>, <a href="#a67c6b2d9d2593a5231245f9055f126c1">getTargetTriple</a>, <a href="#a4f6fbbda563e86c6a9e6ce39a6f4d5ab">InitHelperTransformLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#ae05a13fd904ff35d8ed4fe194f49dd37">llvm::orc::LLJITBuilderState::JTMB</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#abb42e681fc0a5b19aad06828cd7208bc">llvm::orc::LLJITBuilderState::LinkProcessSymbolsByDefault</a>, <a href="#a4403c6d0172443bd06841dc65467d6da">Main</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da77fe6095a7470a90a4ae2beafb42efa7">llvm::orc::MatchExportedSymbolsOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#abef4d04d6ec2ca5605d65c8531eeebbd">ObjLinkingLayer</a>, <a href="#a3693cddd881c11c8836f3bd273636069">ObjTransformLayer</a>, <a href="#a8f50efb4aa497805dfe0d9d3134155ee">Platform</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a6cd0d26ba383f998640fa3e044485085">llvm::orc::LLJITBuilderState::PrePlatformSetup</a>, <a href="#a8ec52e740921d55355a3e49c8921abc5">ProcessSymbols</a>, <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#aebdd4345c6d5e331866bd797278704a8">llvm::orc::LLJITBuilderState::SetUpPlatform</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a21c262afe60cbda7b5868adca7e3d8cb">llvm::orc::LLJITBuilderState::SetupProcessSymbolsJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a8d16ea7c133c6f1bc76f35677244a89e">llvm::orc::LLJITBuilderState::SupportConcurrentCompilation</a>, <a href="#a9e958902278f92af9d29e83cb61213c8">TransformLayer</a> and <a href="#ae385620f3dabad18c226aede346699ce">TT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport/#a3488e2a04a2235e6c4ea987734c94d7a">llvm::orc::LLJIT::PlatformSupport::deinitialize</a>, <a href="#af0e42999670094cbbd1ea6ce38df5280">LLJITBuilderSetters</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport/#aa1345bd94ffde180e749a73a35e3156d">llvm::orc::LLJIT::PlatformSupport::setInitTransform</a> and <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LLJIT() {#a4098d3bf9b2a95b903a4b4a71c43aa10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LLJIT::~LLJIT ()</td>
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

<p>Destruct this instance.</p>


<p>If a multi-threaded instance, waits for all compile threads to complete.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>Reference <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addIRModule() {#ae80aa20118c3b2a9fe857c47dd576d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::addIRModule (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an IR module with the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4f6fbbda563e86c6a9e6ce39a6f4d5ab">InitHelperTransformLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule/#a5dc53e9bbda9066a1ade839494fe0cd9">llvm::orc::ThreadSafeModule::withModuleDo</a>.</p>


<p>Referenced by <a href="#a5d24430d7198c43adb4bcbb1b3a5040c">addIRModule</a> and <a href="#a286936f266b3ea6e0e0bc495a1908b7e">addIRModule</a>.</p>

</div>
</div>

### addIRModule() {#a5d24430d7198c43adb4bcbb1b3a5040c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::addIRModule (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an IR module to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="#ae80aa20118c3b2a9fe857c47dd576d44">addIRModule</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae3cfc9a4e792646e7108ebae425804f0">llvm::orc::JITDylib::getDefaultResourceTracker</a>.</p>

</div>
</div>

### addIRModule() {#a286936f266b3ea6e0e0bc495a1908b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::addIRModule (<a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
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

<p>Adds an IR module to the Main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#ae80aa20118c3b2a9fe857c47dd576d44">addIRModule</a> and <a href="#a4403c6d0172443bd06841dc65467d6da">Main</a>.</p>

</div>
</div>

### addObjectFile() {#a18fffdd9e623be562929e8c890b06912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::addObjectFile (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an object file to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 928 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3693cddd881c11c8836f3bd273636069">ObjTransformLayer</a>.</p>


<p>Referenced by <a href="#a2369a3a1c00d13978b3c71bdc133ba86">addObjectFile</a> and <a href="#aa8532fb842fd8229a028f9cfb6c7ec93">addObjectFile</a>.</p>

</div>
</div>

### addObjectFile() {#a2369a3a1c00d13978b3c71bdc133ba86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::addObjectFile (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an object file to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 935 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="#a18fffdd9e623be562929e8c890b06912">addObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae3cfc9a4e792646e7108ebae425804f0">llvm::orc::JITDylib::getDefaultResourceTracker</a>.</p>

</div>
</div>

### addObjectFile() {#aa8532fb842fd8229a028f9cfb6c7ec93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::addObjectFile (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Obj)</td>
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

<p>Adds an object file to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#a18fffdd9e623be562929e8c890b06912">addObjectFile</a> and <a href="#a4403c6d0172443bd06841dc65467d6da">Main</a>.</p>

</div>
</div>

### createJITDylib() {#a192875b831c7f43e8050fc5ba6345407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITDylib &amp; &gt; llvm::orc::LLJIT::createJITDylib (std::string Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with the given name and return a reference to it.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> names must be unique. If the given name is derived from user input or elsewhere in the environment then the client should check (e.g. by calling getJITDylibByName) that the given name is not already in use.</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a6dfad3bd64c32a0f80f488fee7f637de">llvm::orc::JITDylib::addToLinkOrder</a>, <a href="#a1e6bec9147ad1396e3f7bd405bbb181f">DefaultLinks</a> and <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>.</p>


<p>Referenced by <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### defaultLinkOrder() {#ad0eb63499f324d046a48ceb152f49ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibSearchOrder llvm::orc::LLJIT::defaultLinkOrder ()</td>
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

<p>Returns the default link order for this <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance.</p>


<p>This link order will be appended to the link order of JITDylibs created by <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a>'s createJITDylib method.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a1e6bec9147ad1396e3f7bd405bbb181f">DefaultLinks</a>.</p>

</div>
</div>

### deinitialize() {#a537bf263834ac50f5b2fb2684e1d7de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::deinitialize (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>Run the deinitializers for the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib/#a6e20a8eb914e9173e681d176e3171de4">llvm::jitlink::JITLinkDylib::getName</a> and <a href="#acd5184abd0c23393183203ddcd4854a0">PS</a>.</p>

</div>
</div>

### getDataLayout() {#a2160b34c7939217c9dd56362e55a2e79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::orc::LLJIT::getDataLayout ()</td>
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

<p>Returns a reference to the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for this instance.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#aa72c8213f7b5f438014b62005898a0c4">DL</a>.</p>

</div>
</div>

### getExecutionSession() {#a94c1b4d9e95a5d56aa3659c9a92bd286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::LLJIT::getExecutionSession ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this instance.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad059d61cab7f6bc8ee555ae23acd7b52">llvm::orc::enableDebuggerSupport</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a> and <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

### getIRCompileLayer() {#a3692a02c2202f95f1d161ef4ef11e9ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRCompileLayer &amp; llvm::orc::LLJIT::getIRCompileLayer ()</td>
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

<p>Returns a reference to the IR compile layer.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a59c30b409d9279e077d210f163d9fcb9">CompileLayer</a>.</p>

</div>
</div>

### getIRTransformLayer() {#a425e226668d27e36e3174920d61f4f4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRTransformLayer &amp; llvm::orc::LLJIT::getIRTransformLayer ()</td>
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

<p>Returns a reference to the IR transform layer.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a9e958902278f92af9d29e83cb61213c8">TransformLayer</a>.</p>

</div>
</div>

### getJITDylibByName() {#adcc811880a5816919a96ee2f2104844d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib * llvm::orc::LLJIT::getJITDylibByName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with the given name, or nullptr if no <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with that name exists.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>.</p>

</div>
</div>

### getMainJITDylib() {#a1b8b3f5b157bac218ad8e28090b03161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib &amp; llvm::orc::LLJIT::getMainJITDylib ()</td>
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

<p>Returns a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> representing the JIT'd main program.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a4403c6d0172443bd06841dc65467d6da">Main</a>.</p>

</div>
</div>

### getObjLinkingLayer() {#a2c595f2ceaeed6e7996a984dca44e2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLayer &amp; llvm::orc::LLJIT::getObjLinkingLayer ()</td>
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

<p>Returns a reference to the ObjLinkingLayer.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#abef4d04d6ec2ca5605d65c8531eeebbd">ObjLinkingLayer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad059d61cab7f6bc8ee555ae23acd7b52">llvm::orc::enableDebuggerSupport</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a> and <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

### getObjTransformLayer() {#ae2342b3b908d5a8ba6416f7a957fc004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectTransformLayer &amp; llvm::orc::LLJIT::getObjTransformLayer ()</td>
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

<p>Returns a reference to the object transform layer.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a3693cddd881c11c8836f3bd273636069">ObjTransformLayer</a>.</p>

</div>
</div>

### getPlatformJITDylib() {#a4dc9978d5f162b95f8583c09f4bec702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibSP llvm::orc::LLJIT::getPlatformJITDylib ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>, which will contain the ORC runtime (if given) and any platform symbols.</p>


<p>Note: JIT'd code should not be added to the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> or a custom <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> instead.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>Reference <a href="#a8f50efb4aa497805dfe0d9d3134155ee">Platform</a>.</p>

</div>
</div>

### getPlatformSupport() {#a7f8a774fa37e25fc9b5afbf169cf627d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PlatformSupport * llvm::orc::LLJIT::getPlatformSupport ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport">PlatformSupport</a> instance.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#acd5184abd0c23393183203ddcd4854a0">PS</a>.</p>

</div>
</div>

### getProcessSymbolsJITDylib() {#a784ec48bdbb34855fde8f7585b00acfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibSP llvm::orc::LLJIT::getProcessSymbolsJITDylib ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the ProcessSymbols <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>, which by default reflects non-JIT'd symbols in the host process.</p>


<p>Note: JIT'd code should not be added to the ProcessSymbols <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> or a custom <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> instead.</p>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>Reference <a href="#a8ec52e740921d55355a3e49c8921abc5">ProcessSymbols</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad059d61cab7f6bc8ee555ae23acd7b52">llvm::orc::enableDebuggerSupport</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a> and <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

### getTargetTriple() {#a67c6b2d9d2593a5231245f9055f126c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::orc::LLJIT::getTargetTriple ()</td>
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

<p>Returns a reference to the triple for this instance.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#ae385620f3dabad18c226aede346699ce">TT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad059d61cab7f6bc8ee555ae23acd7b52">llvm::orc::enableDebuggerSupport</a>, <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a> and <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

### initialize() {#a22c072757f58d375d414672b267b144c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::initialize (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>Run the initializers for the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib/#a6e20a8eb914e9173e681d176e3171de4">llvm::jitlink::JITLinkDylib::getName</a> and <a href="#acd5184abd0c23393183203ddcd4854a0">PS</a>.</p>

</div>
</div>

### linkStaticLibraryInto() {#aaa681b188079626ba7d773d29128e3bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::linkStaticLibraryInto (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; LibBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link a static library into the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>If the given <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> contains a valid static archive (or a universal binary with an archive slice that fits the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance's platform / architecture) then it will be added to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> using a <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a>.</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 892 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae89dfebe97fc65907c1b9194aafe1ade">llvm::orc::JITDylib::addGenerator</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a6e910497d88200a16108f6849b074ab8">llvm::orc::StaticLibraryDefinitionGenerator::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#abef4d04d6ec2ca5605d65c8531eeebbd">ObjLinkingLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### linkStaticLibraryInto() {#aa7573528896e709770c5e31bdf597555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::linkStaticLibraryInto (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link a static library into the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>If the given <em>host</em> path contains a valid static archive (or a universal binary with an archive slice that fits the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance's platform / architecture) then it will be added to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> using a <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a>.</p>


<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae89dfebe97fc65907c1b9194aafe1ade">llvm::orc::JITDylib::addGenerator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a703cd8845907b2859b4ebdd00c206bc1">llvm::orc::StaticLibraryDefinitionGenerator::Load</a>, <a href="#abef4d04d6ec2ca5605d65c8531eeebbd">ObjLinkingLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### loadPlatformDynamicLibrary() {#a4ece82000ef0a7c6a9e9947cbdbbd1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITDylib &amp; &gt; llvm::orc::LLJIT::loadPlatformDynamicLibrary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load a (real) dynamic library and make its symbols available through a new <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> with the same name.</p>


<p>If the given <em>executor</em> path contains a valid platform dynamic library then that library will be loaded, and a new bare <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> whose name is the given path will be created to make the library's symbols available to JIT'd code.</p>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae89dfebe97fc65907c1b9194aafe1ade">llvm::orc::JITDylib::addGenerator</a>, <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#a0be4b6ee27375703c0be30f0b730d0ba">llvm::orc::EPCDynamicLibrarySearchGenerator::Load</a>.</p>

</div>
</div>

### lookup() {#a47cad7df0e937b62cd5cf774ca7b718f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorAddr &gt; llvm::orc::LLJIT::lookup (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UnmangledName)</td>
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

<p>Look up a symbol in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD based on its IR symbol name.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#a7cdf02cb3498619dc90826ff5bf7b64f">lookupLinkerMangled</a> and <a href="#a43dd1528c301e983d792f169a209cfaa">mangle</a>.</p>


<p>Referenced by <a href="#a63c14de36fc5824a7fd7b2cc0b62d9aa">lookup</a>.</p>

</div>
</div>

### lookup() {#a63c14de36fc5824a7fd7b2cc0b62d9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorAddr &gt; llvm::orc::LLJIT::lookup (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UnmangledName)</td>
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

<p>Look up a symbol in the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> based on its IR symbol name.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#a47cad7df0e937b62cd5cf774ca7b718f">lookup</a> and <a href="#a4403c6d0172443bd06841dc65467d6da">Main</a>.</p>

</div>
</div>

### lookupLinkerMangled() {#a7cdf02cb3498619dc90826ff5bf7b64f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorAddr &gt; llvm::orc::LLJIT::lookupLinkerMangled (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up a symbol in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD by the symbol's linker-mangled name (to look up symbols based on their IR name use the lookup function instead).</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a14f663a8d190b740cfb9cbf0d88a7619">llvm::orc::makeJITDylibSearchOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a47cad7df0e937b62cd5cf774ca7b718f">lookup</a>, <a href="#a34a94949eb4cbd94a2bf88001ce40ab8">lookupLinkerMangled</a> and <a href="#af6651526960eb51673b62bf21f33bd63">lookupLinkerMangled</a>.</p>

</div>
</div>

### lookupLinkerMangled() {#a34a94949eb4cbd94a2bf88001ce40ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorAddr &gt; llvm::orc::LLJIT::lookupLinkerMangled (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Look up a symbol in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD by the symbol's linker-mangled name (to look up symbols based on their IR name use the lookup function instead).</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a> and <a href="#a7cdf02cb3498619dc90826ff5bf7b64f">lookupLinkerMangled</a>.</p>

</div>
</div>

### lookupLinkerMangled() {#af6651526960eb51673b62bf21f33bd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorAddr &gt; llvm::orc::LLJIT::lookupLinkerMangled (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Look up a symbol in the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> by the symbol's linker-mangled name (to look up symbols based on their IR name use the lookup function instead).</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#a7cdf02cb3498619dc90826ff5bf7b64f">lookupLinkerMangled</a> and <a href="#a4403c6d0172443bd06841dc65467d6da">Main</a>.</p>

</div>
</div>

### mangle() {#a43dd1528c301e983d792f169a209cfaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::LLJIT::mangle (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UnmangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a linker-mangled version of UnmangledName.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="#aa72c8213f7b5f438014b62005898a0c4">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>.</p>


<p>Referenced by <a href="#a47cad7df0e937b62cd5cf774ca7b718f">lookup</a> and <a href="#a9ee546ce9e614752cf696874ad25505d">mangleAndIntern</a>.</p>

</div>
</div>

### mangleAndIntern() {#a9ee546ce9e614752cf696874ad25505d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::LLJIT::mangleAndIntern (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UnmangledName)</td>
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

<p>Returns an interned, linker-mangled version of UnmangledName.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a> and <a href="#a43dd1528c301e983d792f169a209cfaa">mangle</a>.</p>

</div>
</div>

### setPlatformSupport() {#a04b302aa7a486cbfc0bc4f51c44ef5ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LLJIT::setPlatformSupport (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport">PlatformSupport</a> &gt; PS)</td>
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

<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport">PlatformSupport</a> instance.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#acd5184abd0c23393183203ddcd4854a0">PS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>, <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a951cd49b7d3614e3165425f597e70616">llvm::orc::setUpInactivePlatform</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abf6ef8f2c7e8631ff2a029a0bbf8e920">llvm::orc::setUpOrcPlatformManually</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### applyDataLayout() {#ab837d755651a0abce336798a703de9e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLJIT::applyDataLayout (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="#aa72c8213f7b5f438014b62005898a0c4">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CompileLayer {#a59c30b409d9279e077d210f163d9fcb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IRCompileLayer&gt; llvm::orc::LLJIT::CompileLayer</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a3692a02c2202f95f1d161ef4ef11e9ef">getIRCompileLayer</a> and <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### DefaultLinks {#a1e6bec9147ad1396e3f7bd405bbb181f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibSearchOrder llvm::orc::LLJIT::DefaultLinks</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a192875b831c7f43e8050fc5ba6345407">createJITDylib</a>, <a href="#ad0eb63499f324d046a48ceb152f49ae1">defaultLinkOrder</a> and <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### DL {#aa72c8213f7b5f438014b62005898a0c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout llvm::orc::LLJIT::DL</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#ab837d755651a0abce336798a703de9e4">applyDataLayout</a>, <a href="#a2160b34c7939217c9dd56362e55a2e79">getDataLayout</a>, <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a> and <a href="#a43dd1528c301e983d792f169a209cfaa">mangle</a>.</p>

</div>
</div>

### ES {#a0db12d7666f843fef6469a3b048ac52e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ExecutionSession&gt; llvm::orc::LLJIT::ES</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a192875b831c7f43e8050fc5ba6345407">createJITDylib</a>, <a href="#a04042d20ae456e3f4db3e74ae33b7a3b">createObjectLinkingLayer</a>, <a href="#a94c1b4d9e95a5d56aa3659c9a92bd286">getExecutionSession</a>, <a href="#adcc811880a5816919a96ee2f2104844d">getJITDylibByName</a>, <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>, <a href="#a4ece82000ef0a7c6a9e9947cbdbbd1b9">loadPlatformDynamicLibrary</a>, <a href="#a34a94949eb4cbd94a2bf88001ce40ab8">lookupLinkerMangled</a>, <a href="#a7cdf02cb3498619dc90826ff5bf7b64f">lookupLinkerMangled</a>, <a href="#a9ee546ce9e614752cf696874ad25505d">mangleAndIntern</a>, <a href="#a392f906e72c6fa022d871e028e6f34b9">setUpGenericLLVMIRPlatform</a> and <a href="#a4098d3bf9b2a95b903a4b4a71c43aa10">~LLJIT</a>.</p>

</div>
</div>

### InitHelperTransformLayer {#a4f6fbbda563e86c6a9e6ce39a6f4d5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IRTransformLayer&gt; llvm::orc::LLJIT::InitHelperTransformLayer</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#ae80aa20118c3b2a9fe857c47dd576d44">addIRModule</a>, <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/platformsupport/#aa1345bd94ffde180e749a73a35e3156d">llvm::orc::LLJIT::PlatformSupport::setInitTransform</a>.</p>

</div>
</div>

### Main {#a4403c6d0172443bd06841dc65467d6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib* llvm::orc::LLJIT::Main = nullptr</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a286936f266b3ea6e0e0bc495a1908b7e">addIRModule</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjit/#a59892e6011cedcd35f68338b72cd5f31">llvm::orc::LLLazyJIT::addLazyIRModule</a>, <a href="#aa8532fb842fd8229a028f9cfb6c7ec93">addObjectFile</a>, <a href="#a1b8b3f5b157bac218ad8e28090b03161">getMainJITDylib</a>, <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>, <a href="#a63c14de36fc5824a7fd7b2cc0b62d9aa">lookup</a> and <a href="#af6651526960eb51673b62bf21f33bd63">lookupLinkerMangled</a>.</p>

</div>
</div>

### ObjLinkingLayer {#abef4d04d6ec2ca5605d65c8531eeebbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ObjectLayer&gt; llvm::orc::LLJIT::ObjLinkingLayer</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a2c595f2ceaeed6e7996a984dca44e2b7">getObjLinkingLayer</a>, <a href="#aa7573528896e709770c5e31bdf597555">linkStaticLibraryInto</a>, <a href="#aaa681b188079626ba7d773d29128e3bf">linkStaticLibraryInto</a> and <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### ObjTransformLayer {#a3693cddd881c11c8836f3bd273636069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ObjectTransformLayer&gt; llvm::orc::LLJIT::ObjTransformLayer</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a18fffdd9e623be562929e8c890b06912">addObjectFile</a>, <a href="#ae2342b3b908d5a8ba6416f7a957fc004">getObjTransformLayer</a> and <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### Platform {#a8f50efb4aa497805dfe0d9d3134155ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib* llvm::orc::LLJIT::Platform = nullptr</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a4dc9978d5f162b95f8583c09f4bec702">getPlatformJITDylib</a> and <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### ProcessSymbols {#a8ec52e740921d55355a3e49c8921abc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib* llvm::orc::LLJIT::ProcessSymbols = nullptr</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a784ec48bdbb34855fde8f7585b00acfe">getProcessSymbolsJITDylib</a> and <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### PS {#acd5184abd0c23393183203ddcd4854a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;PlatformSupport&gt; llvm::orc::LLJIT::PS</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a537bf263834ac50f5b2fb2684e1d7de9">deinitialize</a>, <a href="#a7f8a774fa37e25fc9b5afbf169cf627d">getPlatformSupport</a>, <a href="#a22c072757f58d375d414672b267b144c">initialize</a> and <a href="#a04b302aa7a486cbfc0bc4f51c44ef5ae">setPlatformSupport</a>.</p>

</div>
</div>

### TransformLayer {#a9e958902278f92af9d29e83cb61213c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IRTransformLayer&gt; llvm::orc::LLJIT::TransformLayer</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a425e226668d27e36e3174920d61f4f4a">getIRTransformLayer</a> and <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### TT {#ae385620f3dabad18c226aede346699ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::orc::LLJIT::TT</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#a67c6b2d9d2593a5231245f9055f126c1">getTargetTriple</a>, <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### createCompileFunction() {#a7e3e5170bf4d4fa25f1b53e1a5925589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; IRCompileLayer::IRCompiler &gt; &gt; llvm::orc::LLJIT::createCompileFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate">LLJITBuilderState</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> JTMB)</td>
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



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a8cebba7f0403052a8cc3606e956e2a8a">llvm::orc::LLJITBuilderState::CreateCompileFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder/#ad851482024748222bc5538345ec2bd12">llvm::orc::JITTargetMachineBuilder::createTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a8d16ea7c133c6f1bc76f35677244a89e">llvm::orc::LLJITBuilderState::SupportConcurrentCompilation</a>.</p>


<p>Referenced by <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

### createObjectLinkingLayer() {#a04042d20ae456e3f4db3e74ae33b7a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ObjectLayer &gt; &gt; llvm::orc::LLJIT::createObjectLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate">LLJITBuilderState</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a267c91fd9fda8cc97f6b5584bacfdfbc">llvm::orc::LLJITBuilderState::CreateObjectLinkingLayer</a>, <a href="#a0db12d7666f843fef6469a3b048ac52e">ES</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#ae05a13fd904ff35d8ed4fe194f49dd37">llvm::orc::LLJITBuilderState::JTMB</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>.</p>


<p>Referenced by <a href="#a0dd10d6063d14925c308957d2c642fea">LLJIT</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
