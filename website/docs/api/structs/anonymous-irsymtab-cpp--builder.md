---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-irsymtab-cpp-/builder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Builder` Struct Reference

<p>Stores the temporary state that is required to build an IR symbol table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{IRSymtab.cpp}::Builder { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0c562a961438c5436a261418363e99">Builder</a> (SmallVector&lt; char, 0 &gt; &amp;Symtab, StringTableBuilder &amp;StrtabBuilder, BumpPtrAllocator &amp;Alloc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488144c223bdc29e3ba937ac31835b5f">setStr</a> (storage::Str &amp;S, StringRef Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ba1b5d118e3a797eb281a6d578fc8c5">writeRange</a> (storage::Range&lt; T &gt; &amp;R, const std::vector&lt; T &gt; &amp;Objs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a> (const Comdat *C, const Module *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a> (Module *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a> (const ModuleSymbolTable &amp;Msymtab, const SmallPtrSet&lt; GlobalValue *, 4 &gt; &amp;Used, ModuleSymbolTable::Symbol Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a> (ArrayRef&lt; Module * &gt; Mods)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 0 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69498e63d2ce81ee8fcaf2fb57fd319c">Symtab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c659e051ce524d34df8aaa217b1a683">StrtabBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac70956376316c732d2438266fa1fae23">Saver</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1997fd4d8136697427dc700646a58ac7">ComdatMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59bbb0799e077d4df8ebcd235ba83f5">Mang</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb5ff482b7ba66456bddc5456e00d83">TT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/comdat">storage::Comdat</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695b263380f3bd6969112f799a84b235">Comdats</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/module">storage::Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2457ce582c36ed970a154c0ecd28571f">Mods</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol">storage::Symbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb2d735f7e7a7488e58fdc7f7c1d270">Syms</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/uncommon">storage::Uncommon</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c19e6796e1c576916b37b2c7e9322c">Uncommons</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93302fe4ee586af27b89f23f96220769">COFFLinkerOpts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a82a43f37e5141041c44ef1649b6a1">COFFLinkerOptsOS</a> {<a href="#a93302fe4ee586af27b89f23f96220769">COFFLinkerOpts</a>}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/str">storage::Str</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae981c73362f32e7b7d1b2d87341c0f44">DependentLibraries</a></td>
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

<p>Stores the temporary state that is required to build an IR symbol table.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Builder() {#a0e0c562a961438c5436a261418363e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{IRSymtab.cpp}::Builder::Builder (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 0 &gt; &amp; Symtab, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="#ac70956376316c732d2438266fa1fae23">Saver</a>, <a href="#a5c659e051ce524d34df8aaa217b1a683">StrtabBuilder</a> and <a href="#a69498e63d2ce81ee8fcaf2fb57fd319c">Symtab</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a8af0e7caf92ff2e049dc40eceafc15be">llvm::irsymtab::build</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addModule() {#a9e5d9d56a410f0bd58fa931731c9e644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{IRSymtab.cpp}::Builder::addModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/modulesymboltable/#a1793bf2002e7eb8d7199b58aa5252808">llvm::ModuleSymbolTable::addModule</a>, <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a39a82a43f37e5141041c44ef1649b6a1">COFFLinkerOptsOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd1cdae0d7a12aa1861ac142c059f5d2">llvm::collectUsedGlobalVariables</a>, <a href="#ae981c73362f32e7b7d1b2d87341c0f44">DependentLibraries</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="#a2457ce582c36ed970a154c0ecd28571f">Mods</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a571612461ea4af620bc4c441d61579a3">llvm::MDNode::operands</a>, <a href="#a488144c223bdc29e3ba937ac31835b5f">setStr</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesymboltable/#ab3d925fc38ac06d622cfb41f581c1e02">llvm::ModuleSymbolTable::symbols</a>, <a href="#a7cb2d735f7e7a7488e58fdc7f7c1d270">Syms</a>, <a href="#abdb5ff482b7ba66456bddc5456e00d83">TT</a> and <a href="#af7c19e6796e1c576916b37b2c7e9322c">Uncommons</a>.</p>


<p>Referenced by <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

### addSymbol() {#a15ad3b408efc55e12e201e1cd1dfbc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{IRSymtab.cpp}::Builder::addSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesymboltable">ModuleSymbolTable</a> &amp; Msymtab, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 4 &gt; &amp; Used, <a href="/web-llvm/docs/api/classes/llvm/modulesymboltable/#a8ee10b9e113136c4ba54121bc66751c5">ModuleSymbolTable::Symbol</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-irsymtab-cpp-/#a238e67c3c963aa81c512c6608a8d3900">anonymous{IRSymtab.cpp}::buildPreservedSymbolsSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a39a82a43f37e5141041c44ef1649b6a1">COFFLinkerOptsOS</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/uncommon/#ab880b55acb404250230347ce6f0aaba9">llvm::irsymtab::storage::Uncommon::COFFWeakExternFallbackName</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#a6cf3966d2746425299faab5e24315dd7">llvm::irsymtab::storage::Symbol::ComdatIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a39c454028de579646252d421c11e9ff7">llvm::irsymtab::storage::Symbol::FB_common</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ae6a4c6f4fb710d3b1f182ff515ec0f12">llvm::irsymtab::storage::Symbol::FB_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ac9b24a0d1a0b250d9e39e8ea32d25ca3">llvm::irsymtab::storage::Symbol::FB_format_specific</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ac2089e2cc45b6d466d598e96d03905c9">llvm::irsymtab::storage::Symbol::FB_global</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a818b95c61117ffdfb3514347da730b96">llvm::irsymtab::storage::Symbol::FB_has_uncommon</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ab719fc49b41ba3c560bed3b15f6812ec">llvm::irsymtab::storage::Symbol::FB_indirect</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a0c7e3d2ade01c95c114a1c9765d92843">llvm::irsymtab::storage::Symbol::FB_may_omit</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044aa8b208ca059882d330626b67d527bf26">llvm::irsymtab::storage::Symbol::FB_tls</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a3d9d39ed5d35e5b9c47a26e12e648a37">llvm::irsymtab::storage::Symbol::FB_undefined</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a3dbb25ac19ece6e32c9cf553a455e6b5">llvm::irsymtab::storage::Symbol::FB_unnamed_addr</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a8579bc5377de3f38a2e81e5d65632bad">llvm::irsymtab::storage::Symbol::FB_used</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044af436b974827038126ac1f7571fe7c782">llvm::irsymtab::storage::Symbol::FB_visibility</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044aa9fc3498b248880573a354711d74931e">llvm::irsymtab::storage::Symbol::FB_weak</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#ae8128467af78b7c88024035c4dc42b63">llvm::irsymtab::storage::Symbol::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a788ede5201dc9b44e419e9fd2fbb38bf">llvm::GlobalValue::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a98140bed34afff96a44ab31ef977f5ec">llvm::GlobalObject::getComdat</a>, <a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b2e3fb45c4435c29abebf7768a77cd6">llvm::GlobalObject::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesymboltable/#a9c6d3dc79159798bdccacf3e0ee99468">llvm::ModuleSymbolTable::getSymbolFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#a65e8eafa4ca28049374f061a4d17d37b">llvm::irsymtab::storage::Symbol::IRName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#aa59bbb0799e077d4df8ebcd235ba83f5">Mang</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#a1fa126d0b6d1533f884c2b9978a35756">llvm::irsymtab::storage::Symbol::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesymboltable/#a736649b9c166082173376116d527d172">llvm::ModuleSymbolTable::printSymbolName</a>, <a href="#ac70956376316c732d2438266fa1fae23">Saver</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/uncommon/#a0dbcd308a739e3847cfe77a83f1f1530">llvm::irsymtab::storage::Uncommon::SectionName</a>, <a href="#a488144c223bdc29e3ba937ac31835b5f">setStr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a2d0d252cebc6c9ccac230cb8625d8d59">llvm::object::BasicSymbolRef::SF_Executable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac0848bf2e216fe6f4664820d93ab7265">llvm::object::BasicSymbolRef::SF_FormatSpecific</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a9660b615b36c70668b966e987719d9d6">llvm::object::BasicSymbolRef::SF_Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a7cb2d735f7e7a7488e58fdc7f7c1d270">Syms</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="#abdb5ff482b7ba66456bddc5456e00d83">TT</a> and <a href="#af7c19e6796e1c576916b37b2c7e9322c">Uncommons</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a>.</p>

</div>
</div>

### build() {#a0b51b9342dd5e45edcbc6c7237cb1ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{IRSymtab.cpp}::Builder::build (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * &gt; Mods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a93302fe4ee586af27b89f23f96220769">COFFLinkerOpts</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#aabe8d6a7e6063d21fb0a97be69399ed8">llvm::irsymtab::storage::Header::COFFLinkerOpts</a>, <a href="#a39a82a43f37e5141041c44ef1649b6a1">COFFLinkerOptsOS</a>, <a href="#a695b263380f3bd6969112f799a84b235">Comdats</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a15768088710b326e457bb867b234411a">llvm::irsymtab::storage::Header::Comdats</a>, <a href="#ae981c73362f32e7b7d1b2d87341c0f44">DependentLibraries</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#ac2d24303139656e97b36ad867d48f6ce">llvm::irsymtab::storage::Header::DependentLibraries</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a44972a05552d8f94667bb337d8a19d1da0adf4127f038b70609b3c0b176a3b4ee">llvm::irsymtab::storage::Header::kCurrentVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-irsymtab-cpp-/#a331976112aa5c16cfe46764bc97c0dfb">anonymous{IRSymtab.cpp}::kExpectedProducerName</a>, <a href="#a2457ce582c36ed970a154c0ecd28571f">Mods</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a53307908c384f1fcf325e217d15d252b">llvm::irsymtab::storage::Header::Modules</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#afb5f97c61a632d45eaa7ddf0cfe87e72">llvm::irsymtab::storage::Header::Producer</a>, <a href="#ac70956376316c732d2438266fa1fae23">Saver</a>, <a href="#a488144c223bdc29e3ba937ac31835b5f">setStr</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a06f187185e26fb95d5ed837fae1b68d4">llvm::irsymtab::storage::Header::SourceFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a7c9814ac4e49fa7f1f473c57cd6dad1a">llvm::irsymtab::storage::Header::Symbols</a>, <a href="#a7cb2d735f7e7a7488e58fdc7f7c1d270">Syms</a>, <a href="#a69498e63d2ce81ee8fcaf2fb57fd319c">Symtab</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#afe37cf277e521ff592b54dd7955b88ff">llvm::irsymtab::storage::Header::TargetTriple</a>, <a href="#abdb5ff482b7ba66456bddc5456e00d83">TT</a>, <a href="#af7c19e6796e1c576916b37b2c7e9322c">Uncommons</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#af0df3eb934c4136b639da7947fd8acd5">llvm::irsymtab::storage::Header::Uncommons</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a68715f91247eacbf700e7a1fbf783366">llvm::irsymtab::storage::Header::Version</a> and <a href="#a9ba1b5d118e3a797eb281a6d578fc8c5">writeRange</a>.</p>

</div>
</div>

### getComdatIndex() {#aba31a0ce1b4f3f1ff4f3fba69d6231f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int &gt; anonymous{IRSymtab.cpp}::Builder::getComdatIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> * C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a1997fd4d8136697427dc700646a58ac7">ComdatMap</a>, <a href="#a695b263380f3bd6969112f799a84b235">Comdats</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#aa59bbb0799e077d4df8ebcd235ba83f5">Mang</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ac70956376316c732d2438266fa1fae23">Saver</a>, <a href="#a488144c223bdc29e3ba937ac31835b5f">setStr</a> and <a href="#abdb5ff482b7ba66456bddc5456e00d83">TT</a>.</p>


<p>Referenced by <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a>.</p>

</div>
</div>

### setStr() {#a488144c223bdc29e3ba937ac31835b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{IRSymtab.cpp}::Builder::setStr (<a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/str">storage::Str</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/str/#a16bef735d0a180313a385ad5a3b2e7ed">llvm::irsymtab::storage::Str::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/str/#ab9a83ee57679792dc5d3af311350de08">llvm::irsymtab::storage::Str::Size</a> and <a href="#a5c659e051ce524d34df8aaa217b1a683">StrtabBuilder</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a>, <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a>, <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a> and <a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a>.</p>

</div>
</div>

### writeRange() {#a9ba1b5d118e3a797eb281a6d578fc8c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{IRSymtab.cpp}::Builder::writeRange (<a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/range">storage::Range</a>&lt; T &gt; &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; T &gt; &amp; Objs)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Reference <a href="#a69498e63d2ce81ee8fcaf2fb57fd319c">Symtab</a>.</p>


<p>Referenced by <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### COFFLinkerOpts {#a93302fe4ee586af27b89f23f96220769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{IRSymtab.cpp}::Builder::COFFLinkerOpts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

### COFFLinkerOptsOS {#a39a82a43f37e5141041c44ef1649b6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_string_ostream anonymous{IRSymtab.cpp}::Builder::COFFLinkerOptsOS {<a href="#a93302fe4ee586af27b89f23f96220769">COFFLinkerOpts</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a>, <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a> and <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

### ComdatMap {#a1997fd4d8136697427dc700646a58ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Comdat *, int&gt; anonymous{IRSymtab.cpp}::Builder::ComdatMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a>.</p>

</div>
</div>

### Comdats {#a695b263380f3bd6969112f799a84b235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;storage::Comdat&gt; anonymous{IRSymtab.cpp}::Builder::Comdats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a> and <a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a>.</p>

</div>
</div>

### DependentLibraries {#ae981c73362f32e7b7d1b2d87341c0f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;storage::Str&gt; anonymous{IRSymtab.cpp}::Builder::DependentLibraries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a> and <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

### Mang {#aa59bbb0799e077d4df8ebcd235ba83f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Mangler anonymous{IRSymtab.cpp}::Builder::Mang</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a> and <a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a>.</p>

</div>
</div>

### Mods {#a2457ce582c36ed970a154c0ecd28571f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;storage::Module&gt; anonymous{IRSymtab.cpp}::Builder::Mods</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a> and <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

### Saver {#ac70956376316c732d2438266fa1fae23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSaver anonymous{IRSymtab.cpp}::Builder::Saver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a>, <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>, <a href="#a0e0c562a961438c5436a261418363e99">Builder</a> and <a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a>.</p>

</div>
</div>

### StrtabBuilder {#a5c659e051ce524d34df8aaa217b1a683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder&amp; anonymous{IRSymtab.cpp}::Builder::StrtabBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a0e0c562a961438c5436a261418363e99">Builder</a> and <a href="#a488144c223bdc29e3ba937ac31835b5f">setStr</a>.</p>

</div>
</div>

### Syms {#a7cb2d735f7e7a7488e58fdc7f7c1d270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;storage::Symbol&gt; anonymous{IRSymtab.cpp}::Builder::Syms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a>, <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a> and <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

### Symtab {#a69498e63d2ce81ee8fcaf2fb57fd319c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;char, 0&gt;&amp; anonymous{IRSymtab.cpp}::Builder::Symtab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>, <a href="#a0e0c562a961438c5436a261418363e99">Builder</a> and <a href="#a9ba1b5d118e3a797eb281a6d578fc8c5">writeRange</a>.</p>

</div>
</div>

### TT {#abdb5ff482b7ba66456bddc5456e00d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple anonymous{IRSymtab.cpp}::Builder::TT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a>, <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a>, <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a> and <a href="#aba31a0ce1b4f3f1ff4f3fba69d6231f7">getComdatIndex</a>.</p>

</div>
</div>

### Uncommons {#af7c19e6796e1c576916b37b2c7e9322c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;storage::Uncommon&gt; anonymous{IRSymtab.cpp}::Builder::Uncommons</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="#a9e5d9d56a410f0bd58fa931731c9e644">addModule</a>, <a href="#a15ad3b408efc55e12e201e1cd1dfbc45">addSymbol</a> and <a href="#a0b51b9342dd5e45edcbc6c7237cb1ca7">build</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
