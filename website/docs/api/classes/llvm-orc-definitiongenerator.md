---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/definitiongenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DefinitionGenerator` Class

<p>Definition generators can be attached to JITDylibs to generate new definitions for otherwise unresolved symbols during lookup. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::DefinitionGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">llvm/ExecutionEngine/Orc/Core.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/capidefinitiongenerator">CAPIDefinitionGenerator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator">DLLImportDefinitionGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility class to create <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> dllimport GOT symbols (__imp_*) and PLT stubs. <a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility class to expose symbols found via dlsym to the JIT. <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator">EPCDynamicLibrarySearchGenerator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator">ReexportsGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator">ReexportsGenerator</a> can be used with <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae89dfebe97fc65907c1b9194aafe1ade">JITDylib::addGenerator</a> to automatically re-export a subset of the source <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s symbols in the target. <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility class to expose symbols from a static library. <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ce94f02bbb5665a2c7f0e214f8c4036">~DefinitionGenerator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a66069c05f745e4e6c1303b810395ca">tryToGenerate</a> (LookupState &amp;LS, LookupKind K, JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags, const SymbolLookupSet &amp;LookupSet)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a7a66069c05f745e4e6c1303b810395ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac933feb4562f64d0bcf93f3e07763fcd">M</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3259a595a2c1f47b60fc6ce96ab0088d">InUse</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1eeb489009512ea16294386aa601818">PendingLookups</a></td>
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

<p>Definition generators can be attached to JITDylibs to generate new definitions for otherwise unresolved symbols during lookup.</p>

<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ExecutionSession {#ae073d99ba71b23b530556f075655fc61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator/#a0a18ceb873894a966ded295537737261">llvm::orc::DLLImportDefinitionGenerator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#af9de54b6e1a0704874430d55c7a5b069">llvm::orc::EPCDynamicLibrarySearchGenerator::EPCDynamicLibrarySearchGenerator</a>, <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#a2df05e3d58c3066d603ca3276b873011">llvm::orc::EPCDynamicLibrarySearchGenerator::GetForTargetProcess</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#a0be4b6ee27375703c0be30f0b730d0ba">llvm::orc::EPCDynamicLibrarySearchGenerator::Load</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DefinitionGenerator() {#a5ce94f02bbb5665a2c7f0e214f8c4036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DefinitionGenerator::~DefinitionGenerator ()</td>
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



<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryToGenerate() {#a7a66069c05f745e4e6c1303b810395ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::orc::DefinitionGenerator::tryToGenerate (<a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a> &amp; LS, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; LookupSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>K specifies the kind of this lookup. JD specifies the target <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> being searched, and JDLookupFlags specifies whether the search should match against hidden symbols. Finally, Symbols describes the set of unresolved symbols and their associated lookup flags.</p>


<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InUse {#a3259a595a2c1f47b60fc6ce96ab0088d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::DefinitionGenerator::InUse = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### M {#ac933feb4562f64d0bcf93f3e07763fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::DefinitionGenerator::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### PendingLookups {#ac1eeb489009512ea16294386aa601818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;LookupState&gt; llvm::orc::DefinitionGenerator::PendingLookups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

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
