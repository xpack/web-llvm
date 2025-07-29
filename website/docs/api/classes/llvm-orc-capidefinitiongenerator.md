---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/capidefinitiongenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CAPIDefinitionGenerator` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::CAPIDefinitionGenerator { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9552f1d461f0f51d0cff8e2cdf3ab785">CAPIDefinitionGenerator</a> (LLVMOrcDisposeCAPIDefinitionGeneratorFunction Dispose, void *Ctx, LLVMOrcCAPIDefinitionGeneratorTryToGenerateFunction TryToGenerate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4abf80d4f920fc1cffa5622ee9ff354">~CAPIDefinitionGenerator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a004d734e3626fad8ff8455c8e88f1f">tryToGenerate</a> (LookupState &amp;LS, LookupKind K, JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags, const SymbolLookupSet &amp;LookupSet) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a8a004d734e3626fad8ff8455c8e88f1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga63d2bfad712b6c4d803fbf3b0fac6de9">LLVMOrcDisposeCAPIDefinitionGeneratorFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521ddbe22e2fcdd601ef36e0080415fc">Dispose</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d7bf399a485eee0eb23dce355f88b2">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7d174ec56b7cf3fb68e21efdc7453f99">LLVMOrcCAPIDefinitionGeneratorTryToGenerateFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4bda18a01d906101f204ce0c8a9998">TryToGenerate</a></td>
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


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CAPIDefinitionGenerator() {#a9552f1d461f0f51d0cff8e2cdf3ab785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::CAPIDefinitionGenerator::CAPIDefinitionGenerator (<a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga63d2bfad712b6c4d803fbf3b0fac6de9">LLVMOrcDisposeCAPIDefinitionGeneratorFunction</a> Dispose, void * Ctx, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7d174ec56b7cf3fb68e21efdc7453f99">LLVMOrcCAPIDefinitionGeneratorTryToGenerateFunction</a> TryToGenerate)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CAPIDefinitionGenerator() {#ae4abf80d4f920fc1cffa5622ee9ff354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::CAPIDefinitionGenerator::~CAPIDefinitionGenerator ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryToGenerate() {#a8a004d734e3626fad8ff8455c8e88f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::CAPIDefinitionGenerator::tryToGenerate (<a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a> &amp; LS, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; LookupSet)</td>
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

<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>K specifies the kind of this lookup. JD specifies the target <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> being searched, and JDLookupFlags specifies whether the search should match against hidden symbols. Finally, Symbols describes the set of unresolved symbols and their associated lookup flags.</p>


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/orcv2capihelper/#a6111b6a836e661b1c074d51f7b817973">llvm::orc::OrcV2CAPIHelper::extractLookupState</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpoolentryunsafe/#a08a5c6e6a4cc582bb37eb471ba039019">llvm::orc::SymbolStringPoolEntryUnsafe::from</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orcv2capihelper/#a8298f5d156d32df275a52a3dc252013a">llvm::orc::OrcV2CAPIHelper::resetLookupState</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset/#a626abe9dbc9db6925ed835675b1a00df">llvm::orc::SymbolLookupSet::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#a94d7bf399a485eee0eb23dce355f88b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::orc::CAPIDefinitionGenerator::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

### Dispose {#a521ddbe22e2fcdd601ef36e0080415fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcDisposeCAPIDefinitionGeneratorFunction llvm::orc::CAPIDefinitionGenerator::Dispose</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

### TryToGenerate {#aab4bda18a01d906101f204ce0c8a9998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcCAPIDefinitionGeneratorTryToGenerateFunction llvm::orc::CAPIDefinitionGenerator::TryToGenerate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
