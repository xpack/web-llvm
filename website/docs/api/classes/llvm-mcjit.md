---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcjit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCJIT` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCJIT { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">ExecutionEngine/MCJIT/MCJIT.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for implementation execution of LLVM modules, designed to support both interpreter and just-in-time (JIT) compiler implementations. <a href="/web-llvm/docs/api/classes/llvm/executionengine/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">llvm::SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *, 4 &gt; <a href="#a5ebdb637cb8631131be02f68b69b22b4">ModulePtrSet</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88718d5cc71b9f594ae489ead7d227cd">MCJIT</a> (std::unique_ptr&lt; Module &gt; M, std::unique_ptr&lt; TargetMachine &gt; tm, std::shared_ptr&lt; MCJITMemoryManager &gt; MemMgr, std::shared_ptr&lt; LegacyJITSymbolResolver &gt; Resolver)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1170b9779b23ea493913c303731067">~MCJIT</a> () override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd7b996229ea235ab7e507d3056e8a3b">FindFunctionNamedInModulePtrSet</a> (StringRef FnName, ModulePtrSet::iterator I, ModulePtrSet::iterator E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd530d57252fe45424a6ef3d92bdbf2a">FindGlobalVariableNamedInModulePtrSet</a> (StringRef Name, bool AllowInternal, ModulePtrSet::iterator I, ModulePtrSet::iterator E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ff1d93574d158f344b35fe15a0bb0d3">runStaticConstructorsDestructorsInModulePtrSet</a> (bool isDtors, ModulePtrSet::iterator I, ModulePtrSet::iterator E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51112ceb36ffa34aac4b0543dc8560d9">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a510dbf2f1604e48352b281178447c733">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager">MCJITMemoryManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec308928d4a1339ae380a0613e3de397">MemMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/linkingsymbolresolver">LinkingSymbolResolver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174c0775b08ddb9465bea160339fad8a">Resolver</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f537fd9f2f52f247d6ef7f8e958d5c2">Dyld</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa12d65abe3c11a36a2952a8f4b1095">EventListeners</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">OwningModuleContainer</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2972a0fc4756fbeae49eb7e719723563">OwnedModules</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5143014ab9bf21a0e1309c8a22723d">Archives</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28eb94d43021593885af4679adfba145">Buffers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05de5e745d6d8f2aa7791b34c54abef7">LoadedObjects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objectcache">ObjectCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7009273692f5dc792f96a24fb7fba397">ObjCache</a></td>
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

## ExecutionEngine interface implementation Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ce1da6819f73ca2445152d98c9c48d">addModule</a> (std::unique_ptr&lt; Module &gt; M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to the list of modules that we can JIT from. <a href="#af6ce1da6819f73ca2445152d98c9c48d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63edbda22f0a1ab7ed361f27b5ff6145">addObjectFile</a> (std::unique_ptr&lt; object::ObjectFile &gt; O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addObjectFile - Add an <a href="/web-llvm/docs/api/classes/llvm/objectfile">ObjectFile</a> to the execution engine. <a href="#a63edbda22f0a1ab7ed361f27b5ff6145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7c8df2dff7cbbc59ee68d122f4d01d">addObjectFile</a> (object::OwningBinary&lt; object::ObjectFile &gt; O) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d30954df16f2628d44d0132737f996">addArchive</a> (object::OwningBinary&lt; object::Archive &gt; O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addArchive - Add an Archive to the execution engine. <a href="#a35d30954df16f2628d44d0132737f996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b3e346826c4d15f691fc6d6b9de5f1">removeModule</a> (Module *M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeModule - Removes a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> from the list of modules, but does not free the module's memory. <a href="#aa6b3e346826c4d15f691fc6d6b9de5f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b1949864f1c23210a57aa9edafe19b">FindFunctionNamed</a> (StringRef FnName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindFunctionNamed - Search all of the active modules to find the function that defines FnName. <a href="#a38b1949864f1c23210a57aa9edafe19b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c0265b94d36957565220a4932326e2">FindGlobalVariableNamed</a> (StringRef Name, bool AllowInternal=false) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindGlobalVariableNamed - Search all of the active modules to find the global variable that defines Name. <a href="#ab2c0265b94d36957565220a4932326e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb99f9a5f472aeeb2f5b3e1b279e1853">setObjectCache</a> (ObjectCache *manager) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the object manager that <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> should use to avoid compilation. <a href="#aeb99f9a5f472aeeb2f5b3e1b279e1853">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033df96c8b46bf1abba4a183718623c2">setProcessAllSections</a> (bool ProcessAllSections) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setProcessAllSections (<a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> Only): By default, only sections that are "required for execution" are passed to the <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a>, and other sections are discarded. <a href="#a033df96c8b46bf1abba4a183718623c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5236c37b672e45c22ef2ebb47518871e">generateCodeForModule</a> (Module *M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>generateCodeForModule - Run code generation for the specified module and load it into memory. <a href="#a5236c37b672e45c22ef2ebb47518871e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46de6cc1d24bff3fd2ae2006c8b35456">finalizeObject</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>finalizeObject - ensure the module is fully processed and is usable. <a href="#a46de6cc1d24bff3fd2ae2006c8b35456">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc54665978b90bea2376f8cf50f48cc">finalizeModule</a> (Module *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c711730384b07b067887e93931004a8">finalizeLoadedModules</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2611f76a93e6574c879ba5b5b9fd9dc7">runStaticConstructorsDestructors</a> (bool isDtors) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runStaticConstructorsDestructors - This method is used to execute all of the static constructors or destructors for a program. <a href="#a2611f76a93e6574c879ba5b5b9fd9dc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b6b618b65cd7355f31652c566c8e3c">getPointerToFunction</a> (Function *F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToFunction - The different EE's represent function bodies in different ways. <a href="#ae9b6b618b65cd7355f31652c566c8e3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0198943262fb715d77dfd24ef32f9399">runFunction</a> (Function *F, ArrayRef&lt; GenericValue &gt; ArgValues) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runFunction - Execute the specified function with the specified arguments, and return the result. <a href="#a0198943262fb715d77dfd24ef32f9399">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f1cd53696dbd8b28129c519e8bd65d">getPointerToNamedFunction</a> (StringRef Name, bool AbortOnFailure=true) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToNamedFunction - This method returns the address of the specified function by using the dlsym function call. <a href="#a14f1cd53696dbd8b28129c519e8bd65d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2fc842610d091ab018233b9db03761">mapSectionAddress</a> (const void *LocalAddress, uint64_t TargetAddress) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mapSectionAddress - map a section to its target address space value. <a href="#aaf2fc842610d091ab018233b9db03761">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f6be37761ee5769051ea3fd2982e65">RegisterJITEventListener</a> (JITEventListener *L) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers a listener to be called back on various events within the JIT. <a href="#a18f6be37761ee5769051ea3fd2982e65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b80bb13abeaf36df96b8a7afdb2339d">UnregisterJITEventListener</a> (JITEventListener *L) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7bbc6d6aecb6d04aa719a85b7020089">getGlobalValueAddress</a> (const std::string &amp;Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalValueAddress - Return the address of the specified global value. <a href="#ab7bbc6d6aecb6d04aa719a85b7020089">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628b993cb94eed2150b435bcb25ae009">getFunctionAddress</a> (const std::string &amp;Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFunctionAddress - Return the address of the specified function. <a href="#a628b993cb94eed2150b435bcb25ae009">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879fe4618f17facf9c24886eca53d03f">getTargetMachine</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target machine (if available). <a href="#a879fe4618f17facf9c24886eca53d03f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## (Private) Registration Interfaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e58d02f5553c707ac40497b0e9cf26">findSymbol</a> (const std::string &amp;Name, bool CheckFunctionsOnly)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a66732fec3f835f54f4bb8f5388389">getSymbolAddress</a> (const std::string &amp;Name, bool CheckFunctionsOnly)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c441ad61800b9fe204a455ae36298d">Register</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224802805182e755345184d485c164b8">createJIT</a> (std::unique_ptr&lt; Module &gt; M, std::string *ErrorStr, std::shared_ptr&lt; MCJITMemoryManager &gt; MemMgr, std::shared_ptr&lt; LegacyJITSymbolResolver &gt; Resolver, std::unique_ptr&lt; TargetMachine &gt; TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba8a53658ba2413897f0b674d06faec">emitObject</a> (Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitObject – Generate a JITed object in memory from the specified module Currently, <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> only supports a single module and the module passed to this function call is expected to be the contained module. <a href="#a6ba8a53658ba2413897f0b674d06faec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c77fd10082d414ff13ef63a7655fde6">notifyObjectLoaded</a> (const object::ObjectFile &amp;Obj, const RuntimeDyld::LoadedObjectInfo &amp;L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9945d0e32337f9101716f572df0885">notifyFreeingObject</a> (const object::ObjectFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20dd7532d54078744493a662f741061">findExistingSymbol</a> (const std::string &amp;Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28cc3d07256589bd54f2d22eb12bafad">findModuleForSymbol</a> (const std::string &amp;Name, bool CheckFunctionsOnly)</td>
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


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ModulePtrSet {#a5ebdb637cb8631131be02f68b69b22b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef llvm::SmallPtrSet&lt;Module *, 4&gt; llvm::MCJIT::ModulePtrSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MCJIT() {#a88718d5cc71b9f594ae489ead7d227cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCJIT::MCJIT (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt; tm, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager">MCJITMemoryManager</a> &gt; MemMgr, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver">LegacyJITSymbolResolver</a> &gt; Resolver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCJIT() {#a3b1170b9779b23ea493913c303731067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCJIT::~MCJIT ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a> and <a href="#ace9945d0e32337f9101716f572df0885">notifyFreeingObject</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### FindFunctionNamedInModulePtrSet() {#afd7b996229ea235ab7e507d3056e8a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * MCJIT::FindFunctionNamedInModulePtrSet (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#aa1c0b29f447eccfd6c43dc236148e609">ModulePtrSet::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#aa1c0b29f447eccfd6c43dc236148e609">ModulePtrSet::iterator</a> E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

### FindGlobalVariableNamedInModulePtrSet() {#abd530d57252fe45424a6ef3d92bdbf2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * MCJIT::FindGlobalVariableNamedInModulePtrSet (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AllowInternal, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#aa1c0b29f447eccfd6c43dc236148e609">ModulePtrSet::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#aa1c0b29f447eccfd6c43dc236148e609">ModulePtrSet::iterator</a> E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

### runStaticConstructorsDestructorsInModulePtrSet() {#a6ff1d93574d158f344b35fe15a0bb0d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::runStaticConstructorsDestructorsInModulePtrSet (bool isDtors, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#aa1c0b29f447eccfd6c43dc236148e609">ModulePtrSet::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#aa1c0b29f447eccfd6c43dc236148e609">ModulePtrSet::iterator</a> E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Archives {#a0c5143014ab9bf21a0e1309c8a22723d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;object::OwningBinary&lt;object::Archive&gt;, 2&gt; llvm::MCJIT::Archives</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### Buffers {#a28eb94d43021593885af4679adfba145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;MemoryBuffer&gt;, 2&gt; llvm::MCJIT::Buffers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### Ctx {#a510dbf2f1604e48352b281178447c733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext* llvm::MCJIT::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### Dyld {#a0f537fd9f2f52f247d6ef7f8e958d5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyld llvm::MCJIT::Dyld</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### EventListeners {#a8fa12d65abe3c11a36a2952a8f4b1095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;JITEventListener*&gt; llvm::MCJIT::EventListeners</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### LoadedObjects {#a05de5e745d6d8f2aa7791b34c54abef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;object::ObjectFile&gt;, 2&gt; llvm::MCJIT::LoadedObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### MemMgr {#aec308928d4a1339ae380a0613e3de397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;MCJITMemoryManager&gt; llvm::MCJIT::MemMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### ObjCache {#a7009273692f5dc792f96a24fb7fba397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectCache* llvm::MCJIT::ObjCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### OwnedModules {#a2972a0fc4756fbeae49eb7e719723563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OwningModuleContainer llvm::MCJIT::OwnedModules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### Resolver {#a174c0775b08ddb9465bea160339fad8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkingSymbolResolver llvm::MCJIT::Resolver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### TM {#a51112ceb36ffa34aac4b0543dc8560d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetMachine&gt; llvm::MCJIT::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## ExecutionEngine interface implementation

### addArchive {#a35d30954df16f2628d44d0132737f996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::addArchive (<a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt; A)</td>
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


<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### addModule {#af6ce1da6819f73ca2445152d98c9c48d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::addModule (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M)</td>
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

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to the list of modules that we can JIT from.</p>

<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>

</div>
</div>

### addObjectFile {#a63edbda22f0a1ab7ed361f27b5ff6145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::addObjectFile (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O)</td>
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


<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="#a4c77fd10082d414ff13ef63a7655fde6">notifyObjectLoaded</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a7e7c8df2dff7cbbc59ee68d122f4d01d">addObjectFile</a> and <a href="#ae7e58d02f5553c707ac40497b0e9cf26">findSymbol</a>.</p>

</div>
</div>

### addObjectFile {#a7e7c8df2dff7cbbc59ee68d122f4d01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::addObjectFile (<a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O)</td>
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



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="#a63edbda22f0a1ab7ed361f27b5ff6145">addObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary/#a8184b8ac734dace4ca9883a6f18ee53f">llvm::object::OwningBinary&lt; T &gt;::takeBinary</a>.</p>

</div>
</div>

### finalizeLoadedModules {#a4c711730384b07b067887e93931004a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::finalizeLoadedModules ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a4eeec03dbb296860e68cfa3714117628">llvm::ExecutionEngine::ErrMsg</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>


<p>Referenced by <a href="#adcc54665978b90bea2376f8cf50f48cc">finalizeModule</a>, <a href="#a46de6cc1d24bff3fd2ae2006c8b35456">finalizeObject</a>, <a href="#a628b993cb94eed2150b435bcb25ae009">getFunctionAddress</a> and <a href="#ab7bbc6d6aecb6d04aa719a85b7020089">getGlobalValueAddress</a>.</p>

</div>
</div>

### finalizeModule {#adcc54665978b90bea2376f8cf50f48cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::finalizeModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c711730384b07b067887e93931004a8">finalizeLoadedModules</a>, <a href="#a5236c37b672e45c22ef2ebb47518871e">generateCodeForModule</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>


<p>Referenced by <a href="#a0198943262fb715d77dfd24ef32f9399">runFunction</a>.</p>

</div>
</div>

### finalizeObject {#a46de6cc1d24bff3fd2ae2006c8b35456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::finalizeObject ()</td>
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

<p>finalizeObject - ensure the module is fully processed and is usable.</p>


<p>It is the user-level function for completing the process of making the object usable for execution. It should be called after sections within an object have been relocated using mapSectionAddress. When this method is called the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine will reapply relocations for a loaded object. Is it OK to finalize a set of modules, add modules and finalize again.</p>


<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="#a4c711730384b07b067887e93931004a8">finalizeLoadedModules</a>, <a href="#a5236c37b672e45c22ef2ebb47518871e">generateCodeForModule</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>

</div>
</div>

### FindFunctionNamed {#a38b1949864f1c23210a57aa9edafe19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * MCJIT::FindFunctionNamed (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName)</td>
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


<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### FindGlobalVariableNamed {#ab2c0265b94d36957565220a4932326e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * MCJIT::FindGlobalVariableNamed (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AllowInternal=false)</td>
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


<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

### generateCodeForModule {#a5236c37b672e45c22ef2ebb47518871e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::generateCodeForModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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

<p>generateCodeForModule - Run code generation for the specified module and load it into memory.</p>


<p>When this function has completed, all code and data for the specified module, and any module on which this module depends, will be generated and loaded into memory, but relocations will not yet have been applied and all memory will be readable and writable but not executable.</p>


<p>This function is primarily useful when generating code for an external target, allowing the client an opportunity to remap section addresses before relocations are applied. Clients that intend to execute code locally can use the getFunctionAddress call, which will generate code and apply final preparations all in one step.</p>


<p>This method has no effect for the interpreter.</p>


<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="#a6ba8a53658ba2413897f0b674d06faec">emitObject</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="#a4c77fd10082d414ff13ef63a7655fde6">notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#adcc54665978b90bea2376f8cf50f48cc">finalizeModule</a>, <a href="#a46de6cc1d24bff3fd2ae2006c8b35456">finalizeObject</a>, <a href="#ae7e58d02f5553c707ac40497b0e9cf26">findSymbol</a> and <a href="#ae9b6b618b65cd7355f31652c566c8e3c">getPointerToFunction</a>.</p>

</div>
</div>

### getFunctionAddress {#a628b993cb94eed2150b435bcb25ae009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCJIT::getFunctionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
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

<p>getFunctionAddress - Return the address of the specified function.</p>


<p>This may involve code generation.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="#a4c711730384b07b067887e93931004a8">finalizeLoadedModules</a>, <a href="#ab9a66732fec3f835f54f4bb8f5388389">getSymbolAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>

</div>
</div>

### getGlobalValueAddress {#ab7bbc6d6aecb6d04aa719a85b7020089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCJIT::getGlobalValueAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
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

<p>getGlobalValueAddress - Return the address of the specified global value.</p>


<p>This may involve code generation.</p>


<p>This function should not be called with the interpreter engine.</p>


<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="#a4c711730384b07b067887e93931004a8">finalizeLoadedModules</a>, <a href="#ab9a66732fec3f835f54f4bb8f5388389">getSymbolAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>

</div>
</div>

### getPointerToFunction {#ae9b6b618b65cd7355f31652c566c8e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * MCJIT::getPointerToFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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

<p>getPointerToFunction - The different EE's represent function bodies in different ways.</p>


<p>They should each implement this to say what a function pointer should look like. When F is destroyed, the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> will remove its global mapping and free any machine code. Be sure no threads are running inside F when that happens.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getFunctionAddress instead.</p>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5236c37b672e45c22ef2ebb47518871e">generateCodeForModule</a>, <a href="#a14f1cd53696dbd8b28129c519e8bd65d">getPointerToNamedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#ae66e5ebc951c7d9c88c0c1884bd67872">llvm::ExecutionEngine::updateGlobalMapping</a>.</p>


<p>Referenced by <a href="#a0198943262fb715d77dfd24ef32f9399">runFunction</a>.</p>

</div>
</div>

### getPointerToNamedFunction {#a14f1cd53696dbd8b28129c519e8bd65d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * MCJIT::getPointerToNamedFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AbortOnFailure=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>getPointerToNamedFunction - This method returns the address of the specified function by using the dlsym function call.</p>


<p>As such it is only useful for resolving library symbols, not code generated symbols.</p>


<p>If AbortOnFailure is false and no function with the given name is found, this function silently returns a null pointer. Otherwise, it prints a message to stderr and aborts.</p>


<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/executionengine/#af22d74c24bf5144ae25380ff6abbe2a2">llvm::ExecutionEngine::isSymbolSearchingDisabled</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a7cc176a0cbdab69cff95f1908bb1898d">llvm::ExecutionEngine::LazyFunctionCreator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#ae9b6b618b65cd7355f31652c566c8e3c">getPointerToFunction</a>.</p>

</div>
</div>

### getTargetMachine {#a879fe4618f17facf9c24886eca53d03f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine * llvm::MCJIT::getTargetMachine ()</td>
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

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### mapSectionAddress {#aaf2fc842610d091ab018233b9db03761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCJIT::mapSectionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * LocalAddress, uint64_t TargetAddress)</td>
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


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### RegisterJITEventListener {#a18f6be37761ee5769051ea3fd2982e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::RegisterJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *)</td>
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

<p>Registers a listener to be called back on various events within the JIT.</p>


<p>See <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a> for more details. Does not take ownership of the argument. The argument may be NULL, in which case these functions do nothing.</p>


<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>

</div>
</div>

### removeModule {#aa6b3e346826c4d15f691fc6d6b9de5f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCJIT::removeModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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


<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>

</div>
</div>

### runFunction {#a0198943262fb715d77dfd24ef32f9399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue MCJIT::runFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; ArgValues)</td>
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

<p>runFunction - Execute the specified function with the specified arguments, and return the result.</p>


<p>For <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engines, clients are encouraged to use the "GetFunctionAddress" method (rather than runFunction) and cast the returned uint64_t to the desired function pointer type. However, for backwards compatibility <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>'s implementation can execute 'main-like' function (i.e. those returning void or int, and taking either no arguments or (int, char*[])).</p>


<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#adcc54665978b90bea2376f8cf50f48cc">finalizeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">llvm::Type::FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="#ae9b6b618b65cd7355f31652c566c8e3c">getPointerToFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">llvm::Type::PPC_FP128TyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77905b5e34e8754df1ed4051e0ad9d1a">llvm::PTOGV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520">llvm::Type::VoidTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>.</p>

</div>
</div>

### runStaticConstructorsDestructors {#a2611f76a93e6574c879ba5b5b9fd9dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::runStaticConstructorsDestructors (bool isDtors)</td>
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

<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

### setObjectCache {#aeb99f9a5f472aeeb2f5b3e1b279e1853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::setObjectCache (<a href="/web-llvm/docs/api/classes/llvm/objectcache">ObjectCache</a> * manager)</td>
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

<p>Sets the object manager that <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> should use to avoid compilation.</p>

<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>

</div>
</div>

### setProcessAllSections {#a033df96c8b46bf1abba4a183718623c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCJIT::setProcessAllSections (bool ProcessAllSections)</td>
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


<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### UnregisterJITEventListener {#a9b80bb13abeaf36df96b8a7afdb2339d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::UnregisterJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> * L)</td>
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



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## (Private) Registration Interfaces

### createJIT {#a224802805182e755345184d485c164b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine * MCJIT::createJIT (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M, std::string * ErrorStr, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager">MCJITMemoryManager</a> &gt; MemMgr, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver">LegacyJITSymbolResolver</a> &gt; Resolver, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt; TM)</td>
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



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a53d32d3b3baefdec31d3d94b0586d437">llvm::sys::DynamicLibrary::LoadLibraryPermanently</a>.</p>


<p>Referenced by <a href="#a97c441ad61800b9fe204a455ae36298d">Register</a>.</p>

</div>
</div>

### emitObject {#a6ba8a53658ba2413897f0b674d06faec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; MCJIT::emitObject (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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

<p>emitObject – Generate a JITed object in memory from the specified module Currently, <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> only supports a single module and the module passed to this function call is expected to be the contained module.</p>


<p>The module is passed as a parameter here to prepare for multiple module support in the future.</p>


<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a230693f459e18c3b19615ffc33c23f69">llvm::ExecutionEngine::getVerifyModules</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager/#a2bdbe49f025814f15cd9c82aa08a389b">llvm::legacy::PassManager::run</a>.</p>


<p>Referenced by <a href="#a5236c37b672e45c22ef2ebb47518871e">generateCodeForModule</a>.</p>

</div>
</div>

### findExistingSymbol {#ab20dd7532d54078744493a662f741061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbol MCJIT::findExistingSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
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



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a29b4671f69facc701332f9510ca436aa">llvm::ExecutionEngine::getPointerToGlobalIfAvailable</a>.</p>


<p>Referenced by <a href="#ae7e58d02f5553c707ac40497b0e9cf26">findSymbol</a>.</p>

</div>
</div>

### findModuleForSymbol {#a28cc3d07256589bd54f2d22eb12bafad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * MCJIT::findModuleForSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, bool CheckFunctionsOnly)</td>
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



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#ae7e58d02f5553c707ac40497b0e9cf26">findSymbol</a>.</p>

</div>
</div>

### findSymbol {#ae7e58d02f5553c707ac40497b0e9cf26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbol MCJIT::findSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, bool CheckFunctionsOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a63edbda22f0a1ab7ed361f27b5ff6145">addObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="#ab20dd7532d54078744493a662f741061">findExistingSymbol</a>, <a href="#a28cc3d07256589bd54f2d22eb12bafad">findModuleForSymbol</a>, <a href="#a5236c37b672e45c22ef2ebb47518871e">generateCodeForModule</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a7cc176a0cbdab69cff95f1908bb1898d">llvm::ExecutionEngine::LazyFunctionCreator</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#ab9a66732fec3f835f54f4bb8f5388389">getSymbolAddress</a>.</p>

</div>
</div>

### getSymbolAddress {#ab9a66732fec3f835f54f4bb8f5388389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCJIT::getSymbolAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, bool CheckFunctionsOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="#ae7e58d02f5553c707ac40497b0e9cf26">findSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a628b993cb94eed2150b435bcb25ae009">getFunctionAddress</a> and <a href="#ab7bbc6d6aecb6d04aa719a85b7020089">getGlobalValueAddress</a>.</p>

</div>
</div>

### notifyFreeingObject {#ace9945d0e32337f9101716f572df0885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::notifyFreeingObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
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



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>


<p>Referenced by <a href="#a3b1170b9779b23ea493913c303731067">~MCJIT</a>.</p>

</div>
</div>

### notifyObjectLoaded {#a4c77fd10082d414ff13ef63a7655fde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCJIT::notifyObjectLoaded (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &amp; L)</td>
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



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a5972a6c7bf1cf22a359d9b7987d11dfd">llvm::ExecutionEngine::lock</a>.</p>


<p>Referenced by <a href="#a63edbda22f0a1ab7ed361f27b5ff6145">addObjectFile</a> and <a href="#a5236c37b672e45c22ef2ebb47518871e">generateCodeForModule</a>.</p>

</div>
</div>

### Register {#a97c441ad61800b9fe204a455ae36298d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCJIT::Register ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>


<p>References <a href="#a224802805182e755345184d485c164b8">createJIT</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a6ce88aa01ae7cf17c22e69718cff7299">llvm::ExecutionEngine::MCJITCtor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-mcjit-cpp-/registerjit/#afe025b12ae6998c326bd33a0e8d30036">anonymous{MCJIT.cpp}::RegisterJIT::RegisterJIT</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
