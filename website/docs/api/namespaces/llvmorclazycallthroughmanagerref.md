---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvmorclazycallthroughmanagerref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `LLVMOrcLazyCallThroughManagerRef` Namespace



## Definition

<div class="doxyDefinition">
namespace LLVMOrcLazyCallThroughManagerRef { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvmorclazycallthroughmanagerref/orccapimaterializationunit">OrcCAPIMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3109cc1cfe3ab7823063aaf1f40b9dc4">toJITSymbolFlags</a> (LLVMJITSymbolFlags F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvmjitsymbolflags">LLVMJITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda88d4895989e55b1d4617274bcb1d0">fromJITSymbolFlags</a> (JITSymbolFlags JSF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ada98b2ca88b7bc4b65b62e3269fdade7">SymbolNameSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e661458a7dbd8e8273e987d25074ac4">toSymbolNameSet</a> (LLVMOrcCSymbolsList Symbols)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7336a1f6736df7ed14f226fb2f789215">toSymbolMap</a> (LLVMOrcCSymbolMapPairs Syms, size_t NumPairs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad4c600dd1184757dace1280e114f5b15">SymbolDependenceMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2cd4bbc01d2cd5cd5ba1cb37b7b4140">toSymbolDependenceMap</a> (LLVMOrcCDependenceMapPairs Pairs, size_t NumPairs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbcd030527b5870272d6f28828693980">toLookupKind</a> (LLVMOrcLookupKind K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1077051dfe1f446fda4004011f513e2f">LLVMOrcLookupKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b56ac33388dcfd2dd767ba72fdc9ea4">fromLookupKind</a> (LookupKind K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a251f1879b77cc5601dfdbd16fa0d1b">toJITDylibLookupFlags</a> (LLVMOrcJITDylibLookupFlags LF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafb8e107655fbfbaa3e0a917891d96d7d">LLVMOrcJITDylibLookupFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6606817f03c87a83601214ac8d81e3">fromJITDylibLookupFlags</a> (JITDylibLookupFlags LF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9ab">SymbolLookupFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb7746ac80b75a2c9e5536bafdf37940">toSymbolLookupFlags</a> (LLVMOrcSymbolLookupFlags SLF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gabd046a5177c36cda183e285788ed6ad6">LLVMOrcSymbolLookupFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe6f13a87e5f14e53cfc451ce653775">fromSymbolLookupFlags</a> (SymbolLookupFlags SLF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvmjitevaluatedsymbol">LLVMJITEvaluatedSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ef4ea37fd470785124fe531d34dd08">fromExecutorSymbolDef</a> (const ExecutorSymbolDef &amp;S)</td>
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

### fromExecutorSymbolDef() {#a25ef4ea37fd470785124fe531d34dd08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMJITEvaluatedSymbol LLVMOrcLazyCallThroughManagerRef::fromExecutorSymbolDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &amp; S)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="#a25ef4ea37fd470785124fe531d34dd08">fromExecutorSymbolDef</a>, <a href="#afda88d4895989e55b1d4617274bcb1d0">fromJITSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef/#af37d28cfc286061fc4faddf19b517e99">llvm::orc::ExecutorSymbolDef::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef/#ad8fb83276d38c4f5d825aae80e8a76e8">llvm::orc::ExecutorSymbolDef::getFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>.</p>


<p>Referenced by <a href="#a25ef4ea37fd470785124fe531d34dd08">fromExecutorSymbolDef</a>.</p>

</div>
</div>

### fromJITDylibLookupFlags() {#a9a6606817f03c87a83601214ac8d81e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcJITDylibLookupFlags LLVMOrcLazyCallThroughManagerRef::fromJITDylibLookupFlags (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> LF)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="#a9a6606817f03c87a83601214ac8d81e3">fromJITDylibLookupFlags</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggafb8e107655fbfbaa3e0a917891d96d7da14e375fd240215bbe64a327b206138a3">LLVMOrcJITDylibLookupFlagsMatchAllSymbols</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggafb8e107655fbfbaa3e0a917891d96d7da9aa2ef9095b2c5d56adac3c6ef9b7387">LLVMOrcJITDylibLookupFlagsMatchExportedSymbolsOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da77fe6095a7470a90a4ae2beafb42efa7">llvm::orc::MatchExportedSymbolsOnly</a>.</p>


<p>Referenced by <a href="#a9a6606817f03c87a83601214ac8d81e3">fromJITDylibLookupFlags</a>.</p>

</div>
</div>

### fromJITSymbolFlags() {#afda88d4895989e55b1d4617274bcb1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMJITSymbolFlags LLVMOrcLazyCallThroughManagerRef::fromJITSymbolFlags (<a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> JSF)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">llvm::JITSymbolFlags::Callable</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#afda88d4895989e55b1d4617274bcb1d0">fromJITSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a1ecfc51509e138b79c775e012e9e0b6e">llvm::JITSymbolFlags::getTargetFlags</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4ac48a02bc1bb0a2abdc52ab8cabdc832f">LLVMJITSymbolGenericFlagsCallable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4a6b6d7103485ffe5f3c66b06c9c73911c">LLVMJITSymbolGenericFlagsExported</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4aff61fa1ead7a3e3ac224c144786c4179">LLVMJITSymbolGenericFlagsMaterializationSideEffectsOnly</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4a1171237acc9feedb9f2b647be4cb1da1">LLVMJITSymbolGenericFlagsWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbab78b49be60a6b5faf277860a45753ea5">llvm::JITSymbolFlags::MaterializationSideEffectsOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">llvm::JITSymbolFlags::Weak</a>.</p>


<p>Referenced by <a href="#a25ef4ea37fd470785124fe531d34dd08">fromExecutorSymbolDef</a> and <a href="#afda88d4895989e55b1d4617274bcb1d0">fromJITSymbolFlags</a>.</p>

</div>
</div>

### fromLookupKind() {#a8b56ac33388dcfd2dd767ba72fdc9ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcLookupKind LLVMOrcLazyCallThroughManagerRef::fromLookupKind (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba39f22930a01d67284b1bc6484b325c72">llvm::orc::DLSym</a>, <a href="#a8b56ac33388dcfd2dd767ba72fdc9ea4">fromLookupKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga1077051dfe1f446fda4004011f513e2fa9f0c0868aa9357723402e1d1afa0e00c">LLVMOrcLookupKindDLSym</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga1077051dfe1f446fda4004011f513e2faa53dd3ddacef8b825e783bdb887db64e">LLVMOrcLookupKindStatic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a>.</p>


<p>Referenced by <a href="#a8b56ac33388dcfd2dd767ba72fdc9ea4">fromLookupKind</a>.</p>

</div>
</div>

### fromSymbolLookupFlags() {#a4fe6f13a87e5f14e53cfc451ce653775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcSymbolLookupFlags LLVMOrcLazyCallThroughManagerRef::fromSymbolLookupFlags (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9ab">SymbolLookupFlags</a> SLF)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="#a4fe6f13a87e5f14e53cfc451ce653775">fromSymbolLookupFlags</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggabd046a5177c36cda183e285788ed6ad6a3117bfd6e182dd2fbfd1c73417c6f339">LLVMOrcSymbolLookupFlagsRequiredSymbol</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggabd046a5177c36cda183e285788ed6ad6abcfefe9f51ebb38a980c3f742249579b">LLVMOrcSymbolLookupFlagsWeaklyReferencedSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9abaa1734373fb555ce75d3e33411f9ea827">llvm::orc::RequiredSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>


<p>Referenced by <a href="#a4fe6f13a87e5f14e53cfc451ce653775">fromSymbolLookupFlags</a>.</p>

</div>
</div>

### toJITDylibLookupFlags() {#a4a251f1879b77cc5601dfdbd16fa0d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibLookupFlags LLVMOrcLazyCallThroughManagerRef::toJITDylibLookupFlags (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafb8e107655fbfbaa3e0a917891d96d7d">LLVMOrcJITDylibLookupFlags</a> LF)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggafb8e107655fbfbaa3e0a917891d96d7da14e375fd240215bbe64a327b206138a3">LLVMOrcJITDylibLookupFlagsMatchAllSymbols</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggafb8e107655fbfbaa3e0a917891d96d7da9aa2ef9095b2c5d56adac3c6ef9b7387">LLVMOrcJITDylibLookupFlagsMatchExportedSymbolsOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da77fe6095a7470a90a4ae2beafb42efa7">llvm::orc::MatchExportedSymbolsOnly</a> and <a href="#a4a251f1879b77cc5601dfdbd16fa0d1b">toJITDylibLookupFlags</a>.</p>


<p>Referenced by <a href="#a4a251f1879b77cc5601dfdbd16fa0d1b">toJITDylibLookupFlags</a>.</p>

</div>
</div>

### toJITSymbolFlags() {#a3109cc1cfe3ab7823063aaf1f40b9dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags LLVMOrcLazyCallThroughManagerRef::toJITSymbolFlags (<a href="/web-llvm/docs/api/structs/llvmjitsymbolflags">LLVMJITSymbolFlags</a> F)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">llvm::JITSymbolFlags::Callable</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a1ecfc51509e138b79c775e012e9e0b6e">llvm::JITSymbolFlags::getTargetFlags</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4ac48a02bc1bb0a2abdc52ab8cabdc832f">LLVMJITSymbolGenericFlagsCallable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4a6b6d7103485ffe5f3c66b06c9c73911c">LLVMJITSymbolGenericFlagsExported</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4aff61fa1ead7a3e3ac224c144786c4179">LLVMJITSymbolGenericFlagsMaterializationSideEffectsOnly</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga9f61ce88060abadec7f6f6f0f9b457c4a1171237acc9feedb9f2b647be4cb1da1">LLVMJITSymbolGenericFlagsWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbab78b49be60a6b5faf277860a45753ea5">llvm::JITSymbolFlags::MaterializationSideEffectsOnly</a>, <a href="#a3109cc1cfe3ab7823063aaf1f40b9dc4">toJITSymbolFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">llvm::JITSymbolFlags::Weak</a>.</p>


<p>Referenced by <a href="#a3109cc1cfe3ab7823063aaf1f40b9dc4">toJITSymbolFlags</a> and <a href="#a7336a1f6736df7ed14f226fb2f789215">toSymbolMap</a>.</p>

</div>
</div>

### toLookupKind() {#acbcd030527b5870272d6f28828693980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LookupKind LLVMOrcLazyCallThroughManagerRef::toLookupKind (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1077051dfe1f446fda4004011f513e2f">LLVMOrcLookupKind</a> K)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba39f22930a01d67284b1bc6484b325c72">llvm::orc::DLSym</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga1077051dfe1f446fda4004011f513e2fa9f0c0868aa9357723402e1d1afa0e00c">LLVMOrcLookupKindDLSym</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gga1077051dfe1f446fda4004011f513e2faa53dd3ddacef8b825e783bdb887db64e">LLVMOrcLookupKindStatic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a> and <a href="#acbcd030527b5870272d6f28828693980">toLookupKind</a>.</p>


<p>Referenced by <a href="#acbcd030527b5870272d6f28828693980">toLookupKind</a>.</p>

</div>
</div>

### toSymbolDependenceMap() {#ac2cd4bbc01d2cd5cd5ba1cb37b7b4140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolDependenceMap LLVMOrcLazyCallThroughManagerRef::toSymbolDependenceMap (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8e7a4413500f2d0800e67f98aea4370f">LLVMOrcCDependenceMapPairs</a> Pairs, size_t NumPairs)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvmorccsymbolslist/#a2be9945303e72299d0f884bf28c44fbb">LLVMOrcCSymbolsList::Length</a>, <a href="/web-llvm/docs/api/structs/llvmorccdependencemappair/#ac5189d2c4ab9ad944f768a4f59f3b79e">LLVMOrcCDependenceMapPair::Names</a>, <a href="/web-llvm/docs/api/structs/llvmorccsymbolslist/#a2264b1472926db4c7690930d951912fb">LLVMOrcCSymbolsList::Symbols</a>, <a href="#ac2cd4bbc01d2cd5cd5ba1cb37b7b4140">toSymbolDependenceMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="#ac2cd4bbc01d2cd5cd5ba1cb37b7b4140">toSymbolDependenceMap</a>.</p>

</div>
</div>

### toSymbolLookupFlags() {#aeb7746ac80b75a2c9e5536bafdf37940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolLookupFlags LLVMOrcLazyCallThroughManagerRef::toSymbolLookupFlags (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gabd046a5177c36cda183e285788ed6ad6">LLVMOrcSymbolLookupFlags</a> SLF)</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggabd046a5177c36cda183e285788ed6ad6a3117bfd6e182dd2fbfd1c73417c6f339">LLVMOrcSymbolLookupFlagsRequiredSymbol</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ggabd046a5177c36cda183e285788ed6ad6abcfefe9f51ebb38a980c3f742249579b">LLVMOrcSymbolLookupFlagsWeaklyReferencedSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9abaa1734373fb555ce75d3e33411f9ea827">llvm::orc::RequiredSymbol</a>, <a href="#aeb7746ac80b75a2c9e5536bafdf37940">toSymbolLookupFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>


<p>Referenced by <a href="#aeb7746ac80b75a2c9e5536bafdf37940">toSymbolLookupFlags</a>.</p>

</div>
</div>

### toSymbolMap() {#a7336a1f6736df7ed14f226fb2f789215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolMap LLVMOrcLazyCallThroughManagerRef::toSymbolMap (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga42dbd0f3d83438ca4d108439f0da6185">LLVMOrcCSymbolMapPairs</a> Syms, size_t NumPairs)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a3109cc1cfe3ab7823063aaf1f40b9dc4">toJITSymbolFlags</a>, <a href="#a7336a1f6736df7ed14f226fb2f789215">toSymbolMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="#a7336a1f6736df7ed14f226fb2f789215">toSymbolMap</a>.</p>

</div>
</div>

### toSymbolNameSet() {#a3e661458a7dbd8e8273e987d25074ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNameSet LLVMOrcLazyCallThroughManagerRef::toSymbolNameSet (<a href="/web-llvm/docs/api/structs/llvmorccsymbolslist">LLVMOrcCSymbolsList</a> Symbols)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="#a3e661458a7dbd8e8273e987d25074ac4">toSymbolNameSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="#a3e661458a7dbd8e8273e987d25074ac4">toSymbolNameSet</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
