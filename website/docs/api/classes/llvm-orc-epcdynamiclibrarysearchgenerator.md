---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcdynamiclibrarysearchgenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EPCDynamicLibrarySearchGenerator` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCDynamicLibrarySearchGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">llvm/ExecutionEngine/Orc/EPCDynamicLibrarySearchGenerator.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Definition generators can be attached to JITDylibs to generate new definitions for otherwise unresolved symbols during lookup. <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac870c7932e4bf13d01b19e0e611d96a0">AddAbsoluteSymbolsFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9de54b6e1a0704874430d55c7a5b069">EPCDynamicLibrarySearchGenerator</a> (ExecutionSession &amp;ES, tpctypes::DylibHandle H, SymbolPredicate Allow=SymbolPredicate(), AddAbsoluteSymbolsFn AddAbsoluteSymbols=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that searches for symbols in the library with the given handle. <a href="#af9de54b6e1a0704874430d55c7a5b069">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd769134fc784667d68b675ee79b609d">tryToGenerate</a> (LookupState &amp;LS, LookupKind K, JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags, const SymbolLookupSet &amp;Symbols) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#acd769134fc784667d68b675ee79b609d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277a0e3c38d0edda0a0340a9214e7001">EPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5448ce64b173e084b44c61288eb1a3">H</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5595fb70e3d9549f4dbbe984889c28b9">Allow</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac870c7932e4bf13d01b19e0e611d96a0">AddAbsoluteSymbolsFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8beb68f64634ae0552a399ef768361c">AddAbsoluteSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator">EPCDynamicLibrarySearchGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be4b6ee27375703c0be30f0b730d0ba">Load</a> (ExecutionSession &amp;ES, const char *LibraryPath, SymbolPredicate Allow=SymbolPredicate(), AddAbsoluteSymbolsFn AddAbsoluteSymbols=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Permanently loads the library at the given path and, on success, returns a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that will search it for symbol definitions in the library. <a href="#a0be4b6ee27375703c0be30f0b730d0ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator">EPCDynamicLibrarySearchGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df05e3d58c3066d603ca3276b873011">GetForTargetProcess</a> (ExecutionSession &amp;ES, SymbolPredicate Allow=SymbolPredicate(), AddAbsoluteSymbolsFn AddAbsoluteSymbols=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator">EPCDynamicLibrarySearchGenerator</a> that searches for symbols in the target process. <a href="#a2df05e3d58c3066d603ca3276b873011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AddAbsoluteSymbolsFn {#ac870c7932e4bf13d01b19e0e611d96a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCDynamicLibrarySearchGenerator::AddAbsoluteSymbolsFn =  unique_function&lt;Error(JITDylib &amp;, SymbolMap)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>

</div>
</div>

### SymbolPredicate {#a451bf5760fcb04c7a63fcbe745ac7b17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCDynamicLibrarySearchGenerator::SymbolPredicate =  unique_function&lt;bool(const SymbolStringPtr &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EPCDynamicLibrarySearchGenerator() {#af9de54b6e1a0704874430d55c7a5b069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCDynamicLibrarySearchGenerator::EPCDynamicLibrarySearchGenerator (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> H, <a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a> Allow=<a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a>(), <a href="#ac870c7932e4bf13d01b19e0e611d96a0">AddAbsoluteSymbolsFn</a> AddAbsoluteSymbols=nullptr)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that searches for symbols in the library with the given handle.</p>


<p>If the Allow predicate is given then only symbols matching the predicate will be searched for. If the predicate is not given then all symbols will be searched for.</p>


<p>If <span class="doxyComputerOutput">AddAbsoluteSymbols</span> is provided, it is used to add the symbols to the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a></span>; otherwise it uses JD.define(absoluteSymbols(...)).</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator/#ae073d99ba71b23b530556f075655fc61">llvm::orc::DefinitionGenerator::ExecutionSession</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryToGenerate() {#acd769134fc784667d68b675ee79b609d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::EPCDynamicLibrarySearchGenerator::tryToGenerate (<a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a> &amp; LS, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; LookupSet)</td>
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

<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>K specifies the kind of this lookup. JD specifies the target <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> being searched, and JDLookupFlags specifies whether the search should match against hidden symbols. Finally, Symbols describes the set of unresolved symbols and their associated lookup flags.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcdynamiclibrarysearchgenerator-cpp">EPCDynamicLibrarySearchGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3a6ca0ed8ac3267e0579452013a2e82d">llvm::orc::absoluteSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddAbsoluteSymbols {#aa8beb68f64634ae0552a399ef768361c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddAbsoluteSymbolsFn llvm::orc::EPCDynamicLibrarySearchGenerator::AddAbsoluteSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>

</div>
</div>

### Allow {#a5595fb70e3d9549f4dbbe984889c28b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolPredicate llvm::orc::EPCDynamicLibrarySearchGenerator::Allow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>

</div>
</div>

### EPC {#a277a0e3c38d0edda0a0340a9214e7001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl&amp; llvm::orc::EPCDynamicLibrarySearchGenerator::EPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>

</div>
</div>

### H {#a0d5448ce64b173e084b44c61288eb1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tpctypes::DylibHandle llvm::orc::EPCDynamicLibrarySearchGenerator::H</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### GetForTargetProcess() {#a2df05e3d58c3066d603ca3276b873011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; EPCDynamicLibrarySearchGenerator &gt; &gt; llvm::orc::EPCDynamicLibrarySearchGenerator::GetForTargetProcess (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a> Allow=<a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a>(), <a href="#ac870c7932e4bf13d01b19e0e611d96a0">AddAbsoluteSymbolsFn</a> AddAbsoluteSymbols=nullptr)</td>
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

<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator">EPCDynamicLibrarySearchGenerator</a> that searches for symbols in the target process.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator/#ae073d99ba71b23b530556f075655fc61">llvm::orc::DefinitionGenerator::ExecutionSession</a> and <a href="#a0be4b6ee27375703c0be30f0b730d0ba">Load</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>.</p>

</div>
</div>

### Load() {#a0be4b6ee27375703c0be30f0b730d0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; EPCDynamicLibrarySearchGenerator &gt; &gt; llvm::orc::EPCDynamicLibrarySearchGenerator::Load (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibraryPath, <a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a> Allow=<a href="#a451bf5760fcb04c7a63fcbe745ac7b17">SymbolPredicate</a>(), <a href="#ac870c7932e4bf13d01b19e0e611d96a0">AddAbsoluteSymbolsFn</a> AddAbsoluteSymbols=nullptr)</td>
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

<p>Permanently loads the library at the given path and, on success, returns a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that will search it for symbol definitions in the library.</p>


<p>On failure returns the reason the library failed to load.</p>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcdynamiclibrarysearchgenerator-cpp">EPCDynamicLibrarySearchGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator/#ae073d99ba71b23b530556f075655fc61">llvm::orc::DefinitionGenerator::ExecutionSession</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#ab68f0fe783c50ddf340d5d709c1d08a9">llvm::orc::ExecutorProcessControl::getDylibMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a128c42c13c6cee5b388a8748e6a0a797">llvm::orc::ExecutionSession::getExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager/#aa3949ea92bf2614064d7303fb0cc3629">llvm::orc::DylibManager::loadDylib</a>.</p>


<p>Referenced by <a href="#a2df05e3d58c3066d603ca3276b873011">GetForTargetProcess</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a4ece82000ef0a7c6a9e9947cbdbbd1b9">llvm::orc::LLJIT::loadPlatformDynamicLibrary</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdynamiclibrarysearchgenerator-h">EPCDynamicLibrarySearchGenerator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcdynamiclibrarysearchgenerator-cpp">EPCDynamicLibrarySearchGenerator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
