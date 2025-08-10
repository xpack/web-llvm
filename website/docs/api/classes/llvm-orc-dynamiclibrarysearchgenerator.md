---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/dynamiclibrarysearchgenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DynamicLibrarySearchGenerator` Class

<p>A utility class to expose symbols found via dlsym to the JIT. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::DynamicLibrarySearchGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">llvm/ExecutionEngine/Orc/ExecutionUtils.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a> = std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a305a6ca4a80b77aa5991a3e8fa4a242b">AddAbsoluteSymbolsFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2c1b5c591838d836baac42520e8a4f">DynamicLibrarySearchGenerator</a> (sys::DynamicLibrary Dylib, char GlobalPrefix, SymbolPredicate Allow=SymbolPredicate(), AddAbsoluteSymbolsFn AddAbsoluteSymbols=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that searches for symbols in the given <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">sys::DynamicLibrary</a>. <a href="#a4c2c1b5c591838d836baac42520e8a4f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f48283edeff2b9dfa266043c7229d2f">tryToGenerate</a> (LookupState &amp;LS, LookupKind K, JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags, const SymbolLookupSet &amp;Symbols) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a6f48283edeff2b9dfa266043c7229d2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">sys::DynamicLibrary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e97711592e201e8a78c73f31253866c">Dylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6661875202f22a9579b6c9270b22412">Allow</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a305a6ca4a80b77aa5991a3e8fa4a242b">AddAbsoluteSymbolsFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac103fac5058d21a5c5c5a7fd3b0f2ba9">AddAbsoluteSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12c3f2b2ca76fd3c6c3d0b506f87841">GlobalPrefix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9c2b5ee04aac9abc6857434c7d71b4">Load</a> (const char *FileName, char GlobalPrefix, SymbolPredicate Allow=SymbolPredicate(), AddAbsoluteSymbolsFn AddAbsoluteSymbols=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Permanently loads the library at the given path and, on success, returns a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that will search it for symbol definitions in the library. <a href="#a6a9c2b5ee04aac9abc6857434c7d71b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e13502ce6ca3e87190bc3693208d46">GetForCurrentProcess</a> (char GlobalPrefix, SymbolPredicate Allow=SymbolPredicate(), AddAbsoluteSymbolsFn AddAbsoluteSymbols=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that searches for symbols in the current process. <a href="#a70e13502ce6ca3e87190bc3693208d46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A utility class to expose symbols found via dlsym to the JIT.</p>


<p>If an instance of this class is attached to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> as a fallback definition generator, then any symbol found in the given <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">DynamicLibrary</a> that passes the 'Allow' predicate will be added to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AddAbsoluteSymbolsFn {#a305a6ca4a80b77aa5991a3e8fa4a242b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::DynamicLibrarySearchGenerator::AddAbsoluteSymbolsFn =  unique_function&lt;Error(JITDylib &amp;, SymbolMap)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### SymbolPredicate {#a232bd355bb8de67b8f81c0d8f266fea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::DynamicLibrarySearchGenerator::SymbolPredicate =  std::function&lt;bool(const SymbolStringPtr &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DynamicLibrarySearchGenerator() {#a4c2c1b5c591838d836baac42520e8a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DynamicLibrarySearchGenerator::DynamicLibrarySearchGenerator (<a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">sys::DynamicLibrary</a> Dylib, char GlobalPrefix, <a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a> Allow=<a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a>(), <a href="#a305a6ca4a80b77aa5991a3e8fa4a242b">AddAbsoluteSymbolsFn</a> AddAbsoluteSymbols=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that searches for symbols in the given <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">sys::DynamicLibrary</a>.</p>


<p>If the Allow predicate is given then only symbols matching the predicate will be searched for. If the predicate is not given then all symbols will be searched for.</p>


<p>If <span class="doxyComputerOutput">AddAbsoluteSymbols</span> is provided, it is used to add the symbols to the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a></span>; otherwise it uses JD.define(absoluteSymbols(...)).</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryToGenerate() {#a6f48283edeff2b9dfa266043c7229d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::DynamicLibrarySearchGenerator::tryToGenerate (<a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a> &amp; LS, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; LookupSet)</td>
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


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3a6ca0ed8ac3267e0579452013a2e82d">llvm::orc::absoluteSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddAbsoluteSymbols {#ac103fac5058d21a5c5c5a7fd3b0f2ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddAbsoluteSymbolsFn llvm::orc::DynamicLibrarySearchGenerator::AddAbsoluteSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### Allow {#ad6661875202f22a9579b6c9270b22412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolPredicate llvm::orc::DynamicLibrarySearchGenerator::Allow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### Dylib {#a8e97711592e201e8a78c73f31253866c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::DynamicLibrary llvm::orc::DynamicLibrarySearchGenerator::Dylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### GlobalPrefix {#aa12c3f2b2ca76fd3c6c3d0b506f87841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::orc::DynamicLibrarySearchGenerator::GlobalPrefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### GetForCurrentProcess() {#a70e13502ce6ca3e87190bc3693208d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; DynamicLibrarySearchGenerator &gt; &gt; llvm::orc::DynamicLibrarySearchGenerator::GetForCurrentProcess (char GlobalPrefix, <a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a> Allow=<a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a>(), <a href="#a305a6ca4a80b77aa5991a3e8fa4a242b">AddAbsoluteSymbolsFn</a> AddAbsoluteSymbols=nullptr)</td>
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

<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> that searches for symbols in the current process.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>


<p>Reference <a href="#a6a9c2b5ee04aac9abc6857434c7d71b4">Load</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga989066e131860f8fe758251c061860a7">LLVMOrcCreateDynamicLibrarySearchGeneratorForProcess</a>.</p>

</div>
</div>

### Load() {#a6a9c2b5ee04aac9abc6857434c7d71b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; DynamicLibrarySearchGenerator &gt; &gt; llvm::orc::DynamicLibrarySearchGenerator::Load (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FileName, char GlobalPrefix, <a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a> Allow=<a href="#a232bd355bb8de67b8f81c0d8f266fea7">SymbolPredicate</a>(), <a href="#a305a6ca4a80b77aa5991a3e8fa4a242b">AddAbsoluteSymbolsFn</a> AddAbsoluteSymbols=nullptr)</td>
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


<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a5fe607fc919d5fcd00bdfded75f46643">llvm::sys::DynamicLibrary::getPermanentLibrary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>


<p>Referenced by <a href="#a70e13502ce6ca3e87190bc3693208d46">GetForCurrentProcess</a> and <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7286ab56f015dc3d1364ee35c18248a0">LLVMOrcCreateDynamicLibrarySearchGeneratorForPath</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
