---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/llvmcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LLVMContext` Class

<p>This is an important class for using LLVM in a threaded context. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LLVMContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmcontext">LTOLLVMContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A derived class of <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> that initializes itself according to a given <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> object. <a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmcontext/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8671da9544d8cfdf4ccc798e560bdccc">YieldCallbackTy</a> = void(*)(<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> *Context, void *OpaqueHandle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines the type of a yield callback. <a href="#a8671da9544d8cfdf4ccc798e560bdccc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#ae6b7fe8103c181ad71f37cb721f9d012">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a44d727ac5fccf852bfb2bae3e06adc9c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Known operand bundle tag IDs, which always have the same value. <a href="#a44d727ac5fccf852bfb2bae3e06adc9c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f639900c480510650969df9c74d17d">Module</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa870462b440fc28995544656ce2de912">LLVMContext</a> (const LLVMContext &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4127987cdf74291dd97e24b20bfae4">~LLVMContext</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66594adfbdd1dada452f8e0a1852dac7">operator=</a> (const LLVMContext &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d94b2a186954951025cfb593c91e0a9">getMDKindID</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMDKindID - Return a unique non-zero <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the specified metadata kind. <a href="#a3d94b2a186954951025cfb593c91e0a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6962c8dd837a66164fe0a9031a42f8">getMDKindNames</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMDKindNames - Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the name for custom metadata IDs registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#acc6962c8dd837a66164fe0a9031a42f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf44b2e823883b2709ad2341b211f36">getOperandBundleTags</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOperandBundleTags - Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the bundle tags registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#aadf44b2e823883b2709ad2341b211f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; uint32_t &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a624ccf92d0c47b9a2da6534870b007b0">getOrInsertBundleTag</a> (StringRef TagName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrInsertBundleTag - Returns the Tag to use for an operand bundle of name TagName. <a href="#a624ccf92d0c47b9a2da6534870b007b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf5d4ba3822ef0e75e953a9d19734a5">getOperandBundleTagID</a> (StringRef Tag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOperandBundleTagID - Maps a bundle tag to an integer <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a1bf5d4ba3822ef0e75e953a9d19734a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc484415b469ae5d438c3fd803ca3a4f">getOrInsertSyncScopeID</a> (StringRef SSN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrInsertSyncScopeID - Maps synchronization scope name to synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#adc484415b469ae5d438c3fd803ca3a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1d554403d05394caf57d2d28a9eab4">getSyncScopeNames</a> (SmallVectorImpl&lt; StringRef &gt; &amp;SSNs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSyncScopeNames - Populates client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#afb1d554403d05394caf57d2d28a9eab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157535565c5f11bb8f5cdd794a2466f3">getSyncScopeName</a> (SyncScope::ID Id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSyncScopeName - Returns the name of a <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>, if any. <a href="#a157535565c5f11bb8f5cdd794a2466f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef9b45006f2acede8b5bf5611bda4bf">setGC</a> (const Function &amp;Fn, std::string GCName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define the GC for a function. <a href="#a7ef9b45006f2acede8b5bf5611bda4bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b0fe84c19fe8fc528449d8357ebc19">getGC</a> (const Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the GC for a function. <a href="#a28b0fe84c19fe8fc528449d8357ebc19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d685b1711fe6b13bd0f161b39e5e9a">deleteGC</a> (const Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the GC for a function. <a href="#a26d685b1711fe6b13bd0f161b39e5e9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865b245ad9c5dc10922481c736ed4a4a">shouldDiscardValueNames</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the Context runtime configuration is set to discard all value names. <a href="#a865b245ad9c5dc10922481c736ed4a4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f1ae83b6064a4d27b44857afd71100">setDiscardValueNames</a> (bool Discard)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the Context runtime configuration to discard all value name (but <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>). <a href="#ab9f1ae83b6064a4d27b44857afd71100">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d7bf0d39222f8aba5ebf358076ce50">isODRUniquingDebugTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether there is a string map for uniquing debug info identifiers across the context. <a href="#a89d7bf0d39222f8aba5ebf358076ce50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a495179fcb4553807d7aa184d083dde47">enableDebugTypeODRUniquing</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d9ff84a5c16855014bf7f39eb4fa63">disableDebugTypeODRUniquing</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3fc4eac917915c6286b56b9afe721f">generateMachineFunctionNum</a> (Function &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>generateMachineFunctionNum - Get a unique number for <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> that associated with the given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. <a href="#a8b3fc4eac917915c6286b56b9afe721f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06ffcbda11c36a9204cabe23496e0f5">setDiagnosticHandlerCallBack</a> (DiagnosticHandler::DiagnosticHandlerTy DiagHandler, void *DiagContext=nullptr, bool RespectFilters=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setDiagnosticHandlerCallBack - This method sets a handler call back that is invoked when the backend needs to report anything to the user. <a href="#ab06ffcbda11c36a9204cabe23496e0f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00a4d3e0ec33c889e807f9e507493ee">setDiagnosticHandler</a> (std::unique_ptr&lt; DiagnosticHandler &gt; &amp;&amp;DH, bool RespectFilters=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setDiagnosticHandler - This method sets unique_ptr to object of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> to provide custom diagnostic handling. <a href="#af00a4d3e0ec33c889e807f9e507493ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#a57d9f9fb9d6c947611fd905b718e4bbb">DiagnosticHandler::DiagnosticHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2459c010c6f6bfbc617d01e1be3d47">getDiagnosticHandlerCallBack</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDiagnosticHandlerCallBack - Return the diagnostic handler call back set by setDiagnosticHandlerCallBack. <a href="#a2f2459c010c6f6bfbc617d01e1be3d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ecbe561bca3dd04cba8938401b6ddf">getDiagnosticContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDiagnosticContext - Return the diagnostic context set by setDiagnosticContext. <a href="#ad5ecbe561bca3dd04cba8938401b6ddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae41647cc74ff350acbad9b809ec7da0b">getDiagHandlerPtr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDiagHandlerPtr - Returns const raw pointer of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> set by setDiagnosticHandler. <a href="#ae41647cc74ff350acbad9b809ec7da0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4156ebce5aa9a4cfebfe8f31cfc743">getDiagnosticHandler</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDiagnosticHandler - transfers ownership of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> unique_ptr to caller. <a href="#a4c4156ebce5aa9a4cfebfe8f31cfc743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519d4ef4f38535aa7f415e7ef707b0a7">getDiagnosticsHotnessRequested</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if a code hotness metric should be included in optimization diagnostics. <a href="#a519d4ef4f38535aa7f415e7ef707b0a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5cdc65da56899e9ecc1c6cc0c9cdfd">setDiagnosticsHotnessRequested</a> (bool Requested)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if a code hotness metric should be included in optimization diagnostics. <a href="#a6e5cdc65da56899e9ecc1c6cc0c9cdfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a8308662fa241f81a8bd424f6ce5ee">getMisExpectWarningRequested</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff91f53ad0f1341dc76b0b9ee5f69a0">setMisExpectWarningRequested</a> (bool Requested)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90df2509baaedb1e9759a63c979b92ba">setDiagnosticsMisExpectTolerance</a> (std::optional&lt; uint32_t &gt; Tolerance)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe71303f670173ad9ac988daddda59dc">getDiagnosticsMisExpectTolerance</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded771687bdc915d3b992cbbee8c22c7">getDiagnosticsHotnessThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimum hotness value a diagnostic would need in order to be included in optimization diagnostics. <a href="#aded771687bdc915d3b992cbbee8c22c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548a7ce94692e18623fd0403c39da044">setDiagnosticsHotnessThreshold</a> (std::optional&lt; uint64_t &gt; Threshold)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the minimum hotness value a diagnostic needs in order to be included in optimization diagnostics. <a href="#a548a7ce94692e18623fd0403c39da044">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1a7e759ef595c8db5457bb93e27833">isDiagnosticsHotnessThresholdSetFromPSI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if hotness threshold is requested from PSI. <a href="#a5d1a7e759ef595c8db5457bb93e27833">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/remarks/remarkstreamer">remarks::RemarkStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d22ad9c5c31e15059a4eb4b347629c">getMainRemarkStreamer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The "main remark streamer" used by all the specialized remark streamers. <a href="#a19d22ad9c5c31e15059a4eb4b347629c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/remarks/remarkstreamer">remarks::RemarkStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad52da421f89d0f77c5725c5f711bca01">getMainRemarkStreamer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b57e6e3f238092351a966c04e371a94">setMainRemarkStreamer</a> (std::unique_ptr&lt; remarks::RemarkStreamer &gt; MainRemarkStreamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmremarkstreamer">LLVMRemarkStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fb1ca09e123b005bc539d4ebaaadaf">getLLVMRemarkStreamer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The "LLVM remark streamer" used by LLVM to serialize remark diagnostics comming from IR and MIR passes. <a href="#af6fb1ca09e123b005bc539d4ebaaadaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmremarkstreamer">LLVMRemarkStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0c73264cd4fcd0f600b71308fdf9f2">getLLVMRemarkStreamer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a373d2d3edfb167ce47d9997d8ae9a9c6">setLLVMRemarkStreamer</a> (std::unique_ptr&lt; LLVMRemarkStreamer &gt; RemarkStreamer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad03ef5cfbe6e7cad076d9e45ba06592">diagnose</a> (const DiagnosticInfo &amp;DI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report a message to the currently installed diagnostic handler. <a href="#aad03ef5cfbe6e7cad076d9e45ba06592">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b9a4decea0c52a7225bc63c8166f90">setYieldCallback</a> (YieldCallbackTy Callback, void *OpaqueHandle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers a yield callback with the given context. <a href="#a26b9a4decea0c52a7225bc63c8166f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547073a4bb4e2577f0bcee9a2173d349">yield</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls the yield callback (if applicable). <a href="#a547073a4bb4e2577f0bcee9a2173d349">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4447dfc5ac5a8784a0a933a5be56bbf5">emitError</a> (const Instruction *I, const Twine &amp;ErrorStr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitError - Emit an error message to the currently installed error handler with optional location information. <a href="#a4447dfc5ac5a8784a0a933a5be56bbf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0efca1b5beae14d13898306e047bf0">emitError</a> (const Twine &amp;ErrorStr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optpassgate">OptPassGate</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d61e3562bd75e0ab4e30c0216c8516">getOptPassGate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access the object which can disable optional passes and individual optimizations at compile time. <a href="#af0d61e3562bd75e0ab4e30c0216c8516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f12c10ec3ba201f3f78cd995ff9426">setOptPassGate</a> (OptPassGate &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the object which can disable optional passes and individual optimizations at compile time. <a href="#a61f12c10ec3ba201f3f78cd995ff9426">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac597b14eb5cde4587d18c61a0b23c850">getDefaultTargetCPU</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or set the current "default" target CPU (target-cpu function attribute). <a href="#ac597b14eb5cde4587d18c61a0b23c850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e79f7a36eb1aa4e5e904de7fe1aa0e1">setDefaultTargetCPU</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbb89b7df36f3e448e0411a58ede944">getDefaultTargetFeatures</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to {get,set}DefaultTargetCPU() but for default target-features. <a href="#a8cbb89b7df36f3e448e0411a58ede944">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fa004c6e896ddc528a051155a7c630">setDefaultTargetFeatures</a> (StringRef Features)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4549f98d447b1faa519f13b49984df3">addModule</a> (Module *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addModule - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a module as being instantiated in this context. <a href="#ad4549f98d447b1faa519f13b49984df3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace7397766acb1cfc4db7bdb5386e1a02">removeModule</a> (Module *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeModule - Unregister a module from this context. <a href="#ace7397766acb1cfc4db7bdb5386e1a02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485257992bf797584a7143388f500d64">getDiagnosticMessagePrefix</a> (DiagnosticSeverity Severity)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the prefix that should be printed in front of a diagnostic of the given <span class="doxyComputerOutput">Severity</span>. <a href="#a485257992bf797584a7143388f500d64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is an important class for using LLVM in a threaded context.</p>


<p>It (opaquely) owns and manages the core "global" data of LLVM's core infrastructure, including the type and constant uniquing tables. <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> itself provides no locking guarantees, so you should be careful to have one context per thread.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### YieldCallbackTy {#a8671da9544d8cfdf4ccc798e560bdccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContext::YieldCallbackTy =  void (*)(LLVMContext *Context, void *OpaqueHandle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Defines the type of a yield callback.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a26b9a4decea0c52a7225bc63c8166f90">LLVMContext::setYieldCallback</a>.</p></dd>
</dl>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ae6b7fe8103c181ad71f37cb721f9d012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>

</div>
</div>

### anonymous enum  {#a44d727ac5fccf852bfb2bae3e06adc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Known operand bundle tag IDs, which always have the same value.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_deopt<a id="a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_funclet<a id="a44d727ac5fccf852bfb2bae3e06adc9ca8997c6b0930e2c05209e95e7172c6cf3"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_gc_transition<a id="a44d727ac5fccf852bfb2bae3e06adc9ca3adfd6f3291adf59a7977597741211c6"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_cfguardtarget<a id="a44d727ac5fccf852bfb2bae3e06adc9ca7ccabf0c8cf51c267c1e0cd9a66261d8"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_preallocated<a id="a44d727ac5fccf852bfb2bae3e06adc9ca1ad9f9f842cf7ba87b3db9b1d8870b9f"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_gc_live<a id="a44d727ac5fccf852bfb2bae3e06adc9caf85bb6bcf02a05fdd35f660e57d82534"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_clang_arc_attachedcall<a id="a44d727ac5fccf852bfb2bae3e06adc9ca6c03d5e52bbdefc8c392e3ed77c7d6a1"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_ptrauth<a id="a44d727ac5fccf852bfb2bae3e06adc9cadd4d7ff61cc637f50c78417fc8e67c15"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_kcfi<a id="a44d727ac5fccf852bfb2bae3e06adc9cadb925bc2eb2c117b3ec0b76d1e267127"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_convergencectrl<a id="a44d727ac5fccf852bfb2bae3e06adc9cacdf8ff962c6163eb5fae1f9b2fb5142a"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

</table>
</dd>
</dl>


<p>All operand bundle tags that LLVM has special knowledge of are listed here. Additionally, this scheme allows LLVM to efficiently check for specific operand bundle tags without comparing strings. Keep this in sync with <a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext::LLVMContext()</a>.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Module {#a21f639900c480510650969df9c74d17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/module">Module</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>


<p>Reference <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>


<p>Referenced by <a href="#a8b3fc4eac917915c6286b56b9afe721f">generateMachineFunctionNum</a> and <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LLVMContext() {#a4eb1cb06b47255ef63fa4212866849e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext::LLVMContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3d94b2a186954951025cfb593c91e0a9">getMDKindID</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp/#a604c7971b866313ef6904cd9184e02f5">knownBundleName</a>, <a href="#a44d727ac5fccf852bfb2bae3e06adc9cacdf8ff962c6163eb5fae1f9b2fb5142a">OB_convergencectrl</a>, <a href="#a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a">OB_deopt</a>, <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6ca6ee3fb8ea1d8946ee1f96ab1947b294a">llvm::SyncScope::SingleThread</a> and <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>.</p>


<p>Referenced by <a href="#a6e0c73264cd4fcd0f600b71308fdf9f2">getLLVMRemarkStreamer</a>, <a href="#ad52da421f89d0f77c5725c5f711bca01">getMainRemarkStreamer</a>, <a href="#aa870462b440fc28995544656ce2de912">LLVMContext</a> and <a href="#a66594adfbdd1dada452f8e0a1852dac7">operator=</a>.</p>

</div>
</div>

### LLVMContext() {#aa870462b440fc28995544656ce2de912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LLVMContext::LLVMContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>


<p>Reference <a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LLVMContext() {#a4c4127987cdf74291dd97e24b20bfae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext::~LLVMContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a66594adfbdd1dada452f8e0a1852dac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::LLVMContext::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>


<p>Reference <a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deleteGC() {#a26d685b1711fe6b13bd0f161b39e5e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::deleteGC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the GC for a function.</p>

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### diagnose() {#aad03ef5cfbe6e7cad076d9e45ba06592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::diagnose (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> &amp; DI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report a message to the currently installed diagnostic handler.</p>


<p>This function returns, in particular in the case of error reporting (DI.Severity == <em>DS_Error</em>), so the caller should leave the compilation process in a self-consistent state, even though the generated code need not be correct.</p>


<p>The diagnostic message will be implicitly prefixed with a severity keyword according to <span class="doxyComputerOutput">DI.getSeverity()</span>, i.e., "error: " for <em>DS_Error</em>, "warning: " for <em>DS_Warning</em>, and "note: " for <em>DS_Note</em>.</p>


<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a485257992bf797584a7143388f500d64">getDiagnosticMessagePrefix</a>, <a href="#af6fb1ca09e123b005bc539d4ebaaadaf">getLLVMRemarkStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a442499cb808b8d5b55eec9087eaf3f3f">llvm::DiagnosticInfo::getSeverity</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp/#a2e53e3ea2d7a997e3c84e6235a5f54c0">isDiagnosticEnabled</a>, <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#afe1ba88d90b63845116236a764a670a3">llvm::DiagnosticInfo::print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuprintfruntimebinding-cpp/#a0ed7b2c2e7da5af8cafe5996248e4889">diagnoseInvalidFormatString</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a216ca57e8763ecd488951398b30386b1">anonymous{SIMemoryLegalizer.cpp}::diagnoseUnknownMMRAASName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitter/#a22cabb597d4f9e140fa9184491f7a33f">llvm::MachineOptimizationRemarkEmitter::emit</a>, <a href="#a4447dfc5ac5a8784a0a933a5be56bbf5">emitError</a>, <a href="#a8a0efca1b5beae14d13898306e047bf0">emitError</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aaee16070891b230788ad237d5ba6476d">llvm::MachineInstr::emitGenericError</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad72245681f0ae02a2d4574d434bc813d">llvm::MachineInstr::emitInlineAsmError</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad490267fed2fa5bb019d67a72b952c08">emitNonHSAIntrinsicError</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#af1341504caf3572196ced637deb8fc1c">emitRemovedIntrinsicError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a3d3173a10a3471dbb8834bf4933607f6">emitUnsupportedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a9df9cc3269d03373740e69dcb005d729">errorUnsupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a4c5cfc7017213115dd9821ec2a70e19c">fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#ab7b83683f756fc7e9bd5c88e3d8c4b23">InstrumentAllFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad47eb141a735c9c43d062fe6f931b31b">llvm::AMDGPUTargetLowering::LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a9b7674e7758bfe4a7b4f66ab59c89611">llvm::NVPTXTargetLowering::LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6a5658766cf2558d59b0344bb48f0754">llvm::AMDGPUTargetLowering::LowerGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a71eb7875f97d55a666dd9a08d0a85526">llvm::NVPTXTargetLowering::LowerSTACKRESTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a526eb44ec7e4e3fdcd581c783a9d2426">llvm::NVPTXTargetLowering::LowerSTACKSAVE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a76e8066b76cac14a0fcadde226f9bf9d">verifyLoadedModule</a>.</p>

</div>
</div>

### disableDebugTypeODRUniquing() {#a25d9ff84a5c16855014bf7f39eb4fa63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::disableDebugTypeODRUniquing ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### emitError() {#a4447dfc5ac5a8784a0a933a5be56bbf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::emitError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrorStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>emitError - Emit an error message to the currently installed error handler with optional location information.</p>


<p>This function returns, so code should be prepared to drop the erroneous construct on the floor and "not crash". The generated code need not be correct. The error message will be implicitly prefixed with "error: " and should not end with a ".".</p>


<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aad03ef5cfbe6e7cad076d9e45ba06592">diagnose</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a3b656c080dc0e99bfad373567b257687">checkIntrinsicImmArg</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a86ad8db657f0a7ace4758548f09ef59a">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::determineRegsForWWMAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a36eb02ea70b6f7df1795c2df0b297f16">emitErrorAndReplaceIntrinsicResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86pretileconfig-cpp/#afe92e56d6295b035b78b03a69f64bf41">emitErrorMsg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a25b01daa2e6da05e0e134ae05d3f590a">emitIntrinsicErrorMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a8f33f90bc9da08bc3886953e60715d6e">emitIntrinsicWithChainErrorMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a07c54e53e4d7a7ec84aa30d37f888f62">getBBAddrMapFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a8c7bf8aca4fd6a415c67f9b565203032">legalizeIntrinsicImmArg</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a55d9cc47f7041c1afad87f88ec5c7636">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstantPtrAuth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ae4606620c1b4162cef84781678953b3f">lowerVectorBitClearImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a6b3401ff0fd3212bdf794979558b50c9">lowerVectorBitRevImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a5a880b31811be9159307e8b14bf3acbc">lowerVectorBitSetImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#aa55c0421a55a968b85f611e3124cb170">lowerVectorSplatImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a43d3fe2699745c950168939ee8f0d5cb">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::normalizeInfiniteLoopExit</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### emitError() {#a8a0efca1b5beae14d13898306e047bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::emitError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrorStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aad03ef5cfbe6e7cad076d9e45ba06592">diagnose</a>.</p>

</div>
</div>

### enableDebugTypeODRUniquing() {#a495179fcb4553807d7aa184d083dde47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::enableDebugTypeODRUniquing ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmcontext/#afce6014f3756bf479e3592ed2ae5f769">llvm::lto::LTOLLVMContext::LTOLLVMContext</a>.</p>

</div>
</div>

### generateMachineFunctionNum() {#a8b3fc4eac917915c6286b56b9afe721f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMContext::generateMachineFunctionNum (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>generateMachineFunctionNum - Get a unique number for <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> that associated with the given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>.</p>

<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a21f639900c480510650969df9c74d17d">Module</a> and <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getDefaultTargetCPU() {#ac597b14eb5cde4587d18c61a0b23c850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LLVMContext::getDefaultTargetCPU ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or set the current "default" target CPU (target-cpu function attribute).</p>


<p>The intent is that compiler frontends will set this to a value that reflects the attribute that a function would get "by default" without any specific function attributes, and compiler passes will attach the attribute to newly created functions that are not associated with a particular function, such as global initializers. <a href="/web-llvm/docs/api/classes/llvm/function/#a5dfae571c803bc1e2cd79bf98cc1951f">Function::createWithDefaultAttr()</a> will create functions with this attribute. This function should only be called by passes that run at compile time and not by the backend or LTO passes.</p>


<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getDefaultTargetFeatures() {#a8cbb89b7df36f3e448e0411a58ede944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LLVMContext::getDefaultTargetFeatures ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to {get,set}DefaultTargetCPU() but for default target-features.</p>

<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getDiagHandlerPtr() {#ae41647cc74ff350acbad9b809ec7da0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DiagnosticHandler * LLVMContext::getDiagHandlerPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getDiagHandlerPtr - Returns const raw pointer of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> set by setDiagnosticHandler.</p>

<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#a39d9cdb595768f3e86c3f86f4ba33c00">llvm::MachineOptimizationRemark::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a21c55fb64c1decb01f6dfe60ba7b6c1d">llvm::MachineOptimizationRemarkAnalysis::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#a22479d91f2c90bb3032810dfa2864527">llvm::MachineOptimizationRemarkMissed::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a551a7d26da872a1e686a9d0d4a72d49b">llvm::OptimizationRemark::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a0f1ed99116e727b8a7af8cf48889e7b6">llvm::OptimizationRemarkAnalysis::isEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#aafff42ca513f5f2e742201442cb299ef">llvm::OptimizationRemarkMissed::isEnabled</a>.</p>

</div>
</div>

### getDiagnosticContext() {#ad5ecbe561bca3dd04cba8938401b6ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * LLVMContext::getDiagnosticContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getDiagnosticContext - Return the diagnostic context set by setDiagnosticContext.</p>

<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getDiagnosticHandler() {#a4c4156ebce5aa9a4cfebfe8f31cfc743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; DiagnosticHandler &gt; LLVMContext::getDiagnosticHandler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getDiagnosticHandler - transfers ownership of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> unique_ptr to caller.</p>

<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getDiagnosticHandlerCallBack() {#a2f2459c010c6f6bfbc617d01e1be3d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticHandler::DiagnosticHandlerTy LLVMContext::getDiagnosticHandlerCallBack ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getDiagnosticHandlerCallBack - Return the diagnostic handler call back set by setDiagnosticHandlerCallBack.</p>

<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getDiagnosticsHotnessRequested() {#a519d4ef4f38535aa7f415e7ef707b0a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLVMContext::getDiagnosticsHotnessRequested ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return if a code hotness metric should be included in optimization diagnostics.</p>

<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitteranalysis/#a362fbd1b0bdfc30a7b45a625fcf582c5">llvm::MachineOptimizationRemarkEmitterAnalysis::run</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitterpass/#abaf47a746ff0c09836ffb448d4287287">llvm::MachineOptimizationRemarkEmitterPass::runOnMachineFunction</a>.</p>

</div>
</div>

### getDiagnosticsHotnessThreshold() {#aded771687bdc915d3b992cbbee8c22c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMContext::getDiagnosticsHotnessThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the minimum hotness value a diagnostic would need in order to be included in optimization diagnostics.</p>


<p>Three possible return values: 0 - threshold is disabled. Everything will be printed out. positive int - threshold is set. UINT64_MAX - threshold is not yet set, and needs to be synced from profile summary. Note that in case of missing profile summary, threshold will be kept at "MAX", effectively suppresses all remarks output.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>

</div>
</div>

### getDiagnosticsMisExpectTolerance() {#afe71303f670173ad9ac988daddda59dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMContext::getDiagnosticsMisExpectTolerance ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getGC() {#a28b0fe84c19fe8fc528449d8357ebc19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; LLVMContext::getGC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the GC for a function.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getLLVMRemarkStreamer() {#af6fb1ca09e123b005bc539d4ebaaadaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkStreamer * LLVMContext::getLLVMRemarkStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The "LLVM remark streamer" used by LLVM to serialize remark diagnostics comming from IR and MIR passes.</p>


<p>If it does not exist, diagnostics are not saved in a file but only emitted via the diagnostic handler.</p>


<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="#aad03ef5cfbe6e7cad076d9e45ba06592">diagnose</a> and <a href="#a6e0c73264cd4fcd0f600b71308fdf9f2">getLLVMRemarkStreamer</a>.</p>

</div>
</div>

### getLLVMRemarkStreamer() {#a6e0c73264cd4fcd0f600b71308fdf9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLVMRemarkStreamer * LLVMContext::getLLVMRemarkStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="#af6fb1ca09e123b005bc539d4ebaaadaf">getLLVMRemarkStreamer</a> and <a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext</a>.</p>

</div>
</div>

### getMainRemarkStreamer() {#a19d22ad9c5c31e15059a4eb4b347629c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">remarks::RemarkStreamer * LLVMContext::getMainRemarkStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The "main remark streamer" used by all the specialized remark streamers.</p>


<p>This streamer keeps generic remark metadata in memory throughout the life of the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. This metadata may be emitted in a section in object files depending on the format requirements.</p>


<p>All specialized remark streamers should convert remarks to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">llvm::remarks::Remark</a> and emit them through this streamer.</p>


<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="#ad52da421f89d0f77c5725c5f711bca01">getMainRemarkStreamer</a>.</p>

</div>
</div>

### getMainRemarkStreamer() {#ad52da421f89d0f77c5725c5f711bca01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const remarks::RemarkStreamer * LLVMContext::getMainRemarkStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="#a19d22ad9c5c31e15059a4eb4b347629c">getMainRemarkStreamer</a> and <a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext</a>.</p>

</div>
</div>

### getMDKindID() {#a3d94b2a186954951025cfb593c91e0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMContext::getMDKindID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMDKindID - Return a unique non-zero <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the specified metadata kind.</p>


<p>Return a unique non-zero <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the specified metadata kind.</p>


<p>This <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> is uniqued across modules in the current <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#a8c4c0580bdb7ccc8210222c7b22522b7">llvm::Value::getMetadata</a> and <a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext</a>.</p>

</div>
</div>

### getMDKindNames() {#acc6962c8dd837a66164fe0a9031a42f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::getMDKindNames (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMDKindNames - Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the name for custom metadata IDs registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>getHandlerNames - Populate client-supplied smallvector using custom metadata name and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getMisExpectWarningRequested() {#a53a8308662fa241f81a8bd424f6ce5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLVMContext::getMisExpectWarningRequested ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getOperandBundleTagID() {#a1bf5d4ba3822ef0e75e953a9d19734a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMContext::getOperandBundleTagID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOperandBundleTagID - Maps a bundle tag to an integer <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Every bundle tag registered with an <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> has an unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### getOperandBundleTags() {#aadf44b2e823883b2709ad2341b211f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::getOperandBundleTags (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOperandBundleTags - Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the bundle tags registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>The bundle tags are ordered by increasing bundle IDs.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a1bf5d4ba3822ef0e75e953a9d19734a5">LLVMContext::getOperandBundleTagID</a></p></dd>
</dl>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getOptPassGate() {#af0d61e3562bd75e0ab4e30c0216c8516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptPassGate &amp; LLVMContext::getOptPassGate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access the object which can disable optional passes and individual optimizations at compile time.</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getOrInsertBundleTag() {#a624ccf92d0c47b9a2da6534870b007b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry&lt; uint32_t &gt; * LLVMContext::getOrInsertBundleTag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TagName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrInsertBundleTag - Returns the Tag to use for an operand bundle of name TagName.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getOrInsertSyncScopeID() {#adc484415b469ae5d438c3fd803ca3a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID LLVMContext::getOrInsertSyncScopeID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SSN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrInsertSyncScopeID - Maps synchronization scope name to synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Every synchronization scope registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> has unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> except pre-defined ones.</p>


<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinemoduleinfo/#ae8cd76b599873138cddf10f91e7bcad0">llvm::AMDGPUMachineModuleInfo::AMDGPUMachineModuleInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>.</p>

</div>
</div>

### getSyncScopeName() {#a157535565c5f11bb8f5cdd794a2466f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; LLVMContext::getSyncScopeName (<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSyncScopeName - Returns the name of a <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>, if any.</p>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### getSyncScopeNames() {#afb1d554403d05394caf57d2d28a9eab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::getSyncScopeNames (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; SSNs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSyncScopeNames - Populates client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>Synchronization scope names are ordered by increasing synchronization scope IDs.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### isDiagnosticsHotnessThresholdSetFromPSI() {#a5d1a7e759ef595c8db5457bb93e27833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLVMContext::isDiagnosticsHotnessThresholdSetFromPSI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return if hotness threshold is requested from PSI.</p>

<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### isODRUniquingDebugTypes() {#a89d7bf0d39222f8aba5ebf358076ce50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLVMContext::isODRUniquingDebugTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether there is a string map for uniquing debug info identifiers across the context.</p>


<p>Off by default.</p>


<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setDefaultTargetCPU() {#a4e79f7a36eb1aa4e5e904de7fe1aa0e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDefaultTargetCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setDefaultTargetFeatures() {#ae1fa004c6e896ddc528a051155a7c630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDefaultTargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Features)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setDiagnosticHandler() {#af00a4d3e0ec33c889e807f9e507493ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDiagnosticHandler (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> &gt; &amp;&amp; DH, bool RespectFilters=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setDiagnosticHandler - This method sets unique_ptr to object of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> to provide custom diagnostic handling.</p>


<p>The first argument is unique_ptr of object of type <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> or a derived of that. The second argument should be set to true if the handler only expects enabled diagnostics.</p>


<p>Ownership of this pointer is moved to <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a>.</p>


<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass/#adc024cb6ba7c097538e6a07d54405639">llvm::MachineModuleInfoWrapperPass::doInitialization</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmcontext/#afce6014f3756bf479e3592ed2ae5f769">llvm::lto::LTOLLVMContext::LTOLLVMContext</a> and <a href="/web-llvm/docs/api/classes/llvm/machinemoduleanalysis/#a9bb288703564662b1a43b5cd441c7429">llvm::MachineModuleAnalysis::run</a>.</p>

</div>
</div>

### setDiagnosticHandlerCallBack() {#ab06ffcbda11c36a9204cabe23496e0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDiagnosticHandlerCallBack (<a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#a57d9f9fb9d6c947611fd905b718e4bbb">DiagnosticHandler::DiagnosticHandlerTy</a> DiagHandler, void * DiagContext=nullptr, bool RespectFilters=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setDiagnosticHandlerCallBack - This method sets a handler call back that is invoked when the backend needs to report anything to the user.</p>


<p>The first argument is a function pointer and the second is a context pointer that gets passed into the DiagHandler. The third argument should be set to true if the handler only expects enabled diagnostics.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> doesn't take ownership or interpret either of these pointers.</p>


<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setDiagnosticsHotnessRequested() {#a6e5cdc65da56899e9ecc1c6cc0c9cdfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDiagnosticsHotnessRequested (bool Requested)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set if a code hotness metric should be included in optimization diagnostics.</p>

<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setDiagnosticsHotnessThreshold() {#a548a7ce94692e18623fd0403c39da044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDiagnosticsHotnessThreshold (std::optional&lt; uint64_t &gt; Threshold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the minimum hotness value a diagnostic needs in order to be included in optimization diagnostics.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setDiagnosticsMisExpectTolerance() {#a90df2509baaedb1e9759a63c979b92ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDiagnosticsMisExpectTolerance (std::optional&lt; uint32_t &gt; Tolerance)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setDiscardValueNames() {#ab9f1ae83b6064a4d27b44857afd71100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setDiscardValueNames (bool Discard)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the Context runtime configuration to discard all value name (but <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>).</p>


<p>Clients can use this flag to save memory and runtime, especially in release mode.</p>


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmcontext/#afce6014f3756bf479e3592ed2ae5f769">llvm::lto::LTOLLVMContext::LTOLLVMContext</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### setGC() {#a7ef9b45006f2acede8b5bf5611bda4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setGC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, std::string GCName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define the GC for a function.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setLLVMRemarkStreamer() {#a373d2d3edfb167ce47d9997d8ae9a9c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setLLVMRemarkStreamer (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/llvmremarkstreamer">LLVMRemarkStreamer</a> &gt; RemarkStreamer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setMainRemarkStreamer() {#a5b57e6e3f238092351a966c04e371a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setMainRemarkStreamer (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/remarks/remarkstreamer">remarks::RemarkStreamer</a> &gt; MainRemarkStreamer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setMisExpectWarningRequested() {#a0ff91f53ad0f1341dc76b0b9ee5f69a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setMisExpectWarningRequested (bool Requested)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setOptPassGate() {#a61f12c10ec3ba201f3f78cd995ff9426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setOptPassGate (<a href="/web-llvm/docs/api/classes/llvm/optpassgate">OptPassGate</a> &amp; OPG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the object which can disable optional passes and individual optimizations at compile time.</p>


<p>The lifetime of the object must be guaranteed to extend as long as the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> is used by compilation.</p>


<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### setYieldCallback() {#a26b9a4decea0c52a7225bc63c8166f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::setYieldCallback (<a href="#a8671da9544d8cfdf4ccc798e560bdccc">YieldCallbackTy</a> Callback, void * OpaqueHandle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers a yield callback with the given context.</p>


<p>The yield callback function may be called by LLVM to transfer control back to the client that invoked the LLVM compilation. This can be used to yield control of the thread, or perform periodic work needed by the client. There is no guaranteed frequency at which callbacks must occur; in fact, the client is not guaranteed to ever receive this callback. It is at the sole discretion of LLVM to do so and only if it can guarantee that suspending the thread won't block any forward progress in other LLVM contexts in the same process.</p>


<p>At a suspend point, the state of the current LLVM context is intentionally undefined. No assumptions about it can or should be made. Only LLVM context API calls that explicitly state that they can be used during a yield callback are allowed to be used. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> other API calls into the context are not supported until the yield callback function returns control to LLVM. Other LLVM contexts are unaffected by this restriction.</p>


<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### shouldDiscardValueNames() {#a865b245ad9c5dc10922481c736ed4a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLVMContext::shouldDiscardValueNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the Context runtime configuration is set to discard all value names.</p>


<p>When true, only <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> names will be available in the IR.</p>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

### yield() {#a547073a4bb4e2577f0bcee9a2173d349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::yield ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calls the yield callback (if applicable).</p>


<p>This transfers control of the current thread back to the client, which may suspend the current thread. Only call this method when LLVM doesn't hold any global mutex or cannot block the execution in another LLVM context.</p>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>Reference <a href="#aa142c8c536b95dd8e8a243cb67b57a80">pImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addModule() {#ad4549f98d447b1faa519f13b49984df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::addModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addModule - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a module as being instantiated in this context.</p>


<p>If the context is deleted, the module will be deleted as well.</p>


<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>

</div>
</div>

### removeModule() {#ace7397766acb1cfc4db7bdb5386e1a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContext::removeModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeModule - Unregister a module from this context.</p>

<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### pImpl {#aa142c8c536b95dd8e8a243cb67b57a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContextImpl* const llvm::LLVMContext::pImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#aa1b0638c63ba711320b3bb9c69367ed6">llvm::Value::addMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad151fceb9a0e77a8a8017d4f68791811">llvm::Value::clearMetadata</a>, <a href="#a26d685b1711fe6b13bd0f161b39e5e9a">deleteGC</a>, <a href="#aad03ef5cfbe6e7cad076d9e45ba06592">diagnose</a>, <a href="#a25d9ff84a5c16855014bf7f39eb4fa63">disableDebugTypeODRUniquing</a>, <a href="#a495179fcb4553807d7aa184d083dde47">enableDebugTypeODRUniquing</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d88e21e9caa53945e903fd8c8700b4f">llvm::Value::eraseMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab1198eef44b311a7984cfc8fc97fac6d">llvm::Value::eraseMetadataIf</a>, <a href="#a8b3fc4eac917915c6286b56b9afe721f">generateMachineFunctionNum</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab00c6dc5086df2a37cd2e78715968861">llvm::ConstantExpr::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dsolocalequivalent/#a552470933dc4c1724248d9773e36b4de">llvm::DSOLocalEquivalent::get</a>, <a href="/web-llvm/docs/api/classes/llvm/nocfivalue/#a12b8ccc251129b734bf00e84515d2711">llvm::NoCFIValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3d200b1568f70b28ae0eb9bec58d6690">llvm::Value::getAllMetadata</a>, <a href="#ac597b14eb5cde4587d18c61a0b23c850">getDefaultTargetCPU</a>, <a href="#a8cbb89b7df36f3e448e0411a58ede944">getDefaultTargetFeatures</a>, <a href="#ae41647cc74ff350acbad9b809ec7da0b">getDiagHandlerPtr</a>, <a href="#ad5ecbe561bca3dd04cba8938401b6ddf">getDiagnosticContext</a>, <a href="#a4c4156ebce5aa9a4cfebfe8f31cfc743">getDiagnosticHandler</a>, <a href="#a2f2459c010c6f6bfbc617d01e1be3d47">getDiagnosticHandlerCallBack</a>, <a href="#a519d4ef4f38535aa7f415e7ef707b0a7">getDiagnosticsHotnessRequested</a>, <a href="#aded771687bdc915d3b992cbbee8c22c7">getDiagnosticsHotnessThreshold</a>, <a href="#afe71303f670173ad9ac988daddda59dc">getDiagnosticsMisExpectTolerance</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="#a28b0fe84c19fe8fc528449d8357ebc19">getGC</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="#af6fb1ca09e123b005bc539d4ebaaadaf">getLLVMRemarkStreamer</a>, <a href="#a19d22ad9c5c31e15059a4eb4b347629c">getMainRemarkStreamer</a>, <a href="#a3d94b2a186954951025cfb593c91e0a9">getMDKindID</a>, <a href="#acc6962c8dd837a66164fe0a9031a42f8">getMDKindNames</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aa8b1bc6f9347dade1932d5e0a0be7904">llvm::Value::getMetadata</a>, <a href="#a53a8308662fa241f81a8bd424f6ce5ee">getMisExpectWarningRequested</a>, <a href="#a1bf5d4ba3822ef0e75e953a9d19734a5">getOperandBundleTagID</a>, <a href="#aadf44b2e823883b2709ad2341b211f36">getOperandBundleTags</a>, <a href="#af0d61e3562bd75e0ab4e30c0216c8516">getOptPassGate</a>, <a href="#a624ccf92d0c47b9a2da6534870b007b0">getOrInsertBundleTag</a>, <a href="#adc484415b469ae5d438c3fd803ca3a4f">getOrInsertSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a72237a63b5edcf78a32453822139f1d5">llvm::GlobalValue::getPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a10dbf1e2be9c60af49efb9bfded99225">llvm::GlobalValue::getSanitizerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="#a157535565c5f11bb8f5cdd794a2466f3">getSyncScopeName</a>, <a href="#afb1d554403d05394caf57d2d28a9eab4">getSyncScopeNames</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a262bd33fc97cc729eb9418cc281dc69d">llvm::DIArgList::handleChangedOperand</a>, <a href="#a5d1a7e759ef595c8db5457bb93e27833">isDiagnosticsHotnessThresholdSetFromPSI</a>, <a href="#a89d7bf0d39222f8aba5ebf358076ce50">isODRUniquingDebugTypes</a>, <a href="#a4eb1cb06b47255ef63fa4212866849e1">LLVMContext</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a93f122dff654f8336680531a3898375c">llvm::CallBase::populateBundleOperandInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a1b8db417ccdc447464add1a3d9358759">llvm::GlobalValue::removeSanitizerMetadata</a>, <a href="#a4e79f7a36eb1aa4e5e904de7fe1aa0e1">setDefaultTargetCPU</a>, <a href="#ae1fa004c6e896ddc528a051155a7c630">setDefaultTargetFeatures</a>, <a href="#af00a4d3e0ec33c889e807f9e507493ee">setDiagnosticHandler</a>, <a href="#ab06ffcbda11c36a9204cabe23496e0f5">setDiagnosticHandlerCallBack</a>, <a href="#a6e5cdc65da56899e9ecc1c6cc0c9cdfd">setDiagnosticsHotnessRequested</a>, <a href="#a548a7ce94692e18623fd0403c39da044">setDiagnosticsHotnessThreshold</a>, <a href="#a90df2509baaedb1e9759a63c979b92ba">setDiagnosticsMisExpectTolerance</a>, <a href="#ab9f1ae83b6064a4d27b44857afd71100">setDiscardValueNames</a>, <a href="#a7ef9b45006f2acede8b5bf5611bda4bf">setGC</a>, <a href="#a373d2d3edfb167ce47d9997d8ae9a9c6">setLLVMRemarkStreamer</a>, <a href="#a5b57e6e3f238092351a966c04e371a94">setMainRemarkStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a338590123630c357df6340c38d066572">llvm::Value::setMetadata</a>, <a href="#a0ff91f53ad0f1341dc76b0b9ee5f69a0">setMisExpectWarningRequested</a>, <a href="#a61f12c10ec3ba201f3f78cd995ff9426">setOptPassGate</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aff8740863a5ee2650339400236b6224b">llvm::GlobalValue::setPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#add48ed79a5cd63c7165f3f4da102b9fd">llvm::GlobalValue::setSanitizerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a959c99adbdc7f8375cf866916c6b60f2">llvm::GlobalObject::setSection</a>, <a href="#a26b9a4decea0c52a7225bc63c8166f90">setYieldCallback</a>, <a href="#a865b245ad9c5dc10922481c736ed4a4a">shouldDiscardValueNames</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a478c26e31b9b99fab1ba3036f966f5c9">llvm::MDNode::storeDistinctInContext</a>, <a href="#a547073a4bb4e2577f0bcee9a2173d349">yield</a>, <a href="#a4c4127987cdf74291dd97e24b20bfae4">~LLVMContext</a> and <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#aa8f5b66c1e3e1c2f0740764818920442">llvm::MetadataAsValue::~MetadataAsValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDiagnosticMessagePrefix() {#a485257992bf797584a7143388f500d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMContext::getDiagnosticMessagePrefix (<a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5c">DiagnosticSeverity</a> Severity)</td>
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

<p>Get the prefix that should be printed in front of a diagnostic of the given <span class="doxyComputerOutput">Severity</span>.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca320faa3dfbce0b3e99c5c255d45da362">llvm::DS_Note</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#aad03ef5cfbe6e7cad076d9e45ba06592">diagnose</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">LLVMContext.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontext-cpp">LLVMContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
