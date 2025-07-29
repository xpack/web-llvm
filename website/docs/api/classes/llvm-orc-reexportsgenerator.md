---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/reexportsgenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ReexportsGenerator` Class

<p><a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator">ReexportsGenerator</a> can be used with <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae89dfebe97fc65907c1b9194aafe1ade">JITDylib::addGenerator</a> to automatically re-export a subset of the source <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s symbols in the target. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ReexportsGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">llvm/ExecutionEngine/Orc/Core.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a5a555694e752e5767fc52c805792a7">SymbolPredicate</a> = std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae22a8db07e22b41fd4d19433634f3030">ReexportsGenerator</a> (JITDylib &amp;SourceJD, JITDylibLookupFlags SourceJDLookupFlags, SymbolPredicate Allow=SymbolPredicate())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a reexports generator. <a href="#ae22a8db07e22b41fd4d19433634f3030">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1cc5b369f4fd3e04b66035eea7c481">tryToGenerate</a> (LookupState &amp;LS, LookupKind K, JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags, const SymbolLookupSet &amp;LookupSet) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a9b1cc5b369f4fd3e04b66035eea7c481">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a868837427f59d15d533a4453a82cb046">SourceJD</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7948444bf99f94d42fe176430091620">SourceJDLookupFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6a5a555694e752e5767fc52c805792a7">SymbolPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0d41abc27b07a5b023cd7f3979f108">Allow</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator">ReexportsGenerator</a> can be used with <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae89dfebe97fc65907c1b9194aafe1ade">JITDylib::addGenerator</a> to automatically re-export a subset of the source <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s symbols in the target.</p>

<p>Definition at line 1939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SymbolPredicate {#a6a5a555694e752e5767fc52c805792a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ReexportsGenerator::SymbolPredicate =  std::function&lt;bool(SymbolStringPtr)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ReexportsGenerator() {#ae22a8db07e22b41fd4d19433634f3030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ReexportsGenerator::ReexportsGenerator (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; SourceJD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> SourceJDLookupFlags, <a href="#a6a5a555694e752e5767fc52c805792a7">SymbolPredicate</a> Allow=<a href="#a6a5a555694e752e5767fc52c805792a7">SymbolPredicate</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a reexports generator.</p>


<p>If an Allow predicate is passed, only symbols for which the predicate returns true will be reexported. If no Allow predicate is passed, all symbols will be exported.</p>


<p>Declaration at line 1946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#ae22a8db07e22b41fd4d19433634f3030">ReexportsGenerator</a>.</p>


<p>Referenced by <a href="#ae22a8db07e22b41fd4d19433634f3030">ReexportsGenerator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryToGenerate() {#a9b1cc5b369f4fd3e04b66035eea7c481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ReexportsGenerator::tryToGenerate (<a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a> &amp; LS, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; LookupSet)</td>
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


<p>Declaration at line 1950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a67fc014ddc6f09ff528b686fd7b1de20">llvm::orc::JITDylib::getExecutionSession</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a432a464dcfc79515467f0ddefd78fc83">llvm::orc::ExecutionSession::lookupFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a6b9e003e73655db7fad152ceddb3b45b">llvm::orc::reexports</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allow {#a3c0d41abc27b07a5b023cd7f3979f108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolPredicate llvm::orc::ReexportsGenerator::Allow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### SourceJD {#a868837427f59d15d533a4453a82cb046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib&amp; llvm::orc::ReexportsGenerator::SourceJD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### SourceJDLookupFlags {#af7948444bf99f94d42fe176430091620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibLookupFlags llvm::orc::ReexportsGenerator::SourceJDLookupFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
